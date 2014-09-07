---
layout: raw 
permalink: /fixes/require_smb_client_signing/ssg/govready/bash/fix/
rule_id: require_smb_client_signing
---
#!/bin/bash -u
set -e
# Copyright (c) 2014 Greg Elin, Silver SPring, Maryland, USA
#
# This software was developed by Greg Elin for GovReady
#
# This library is free software; you can redistribute it and/or
# modify it under the terms of the GNU Lesser General Public
# License as published by the Free Software Foundation; either
# version 2.1 of the License, or (at your option) any later version.
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an AS IS BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
#  _____________________________________________________________________
# |  Version |   Change Information  |      Author        |    Date    |
# |__________|_______________________|____________________|____________|
# |    1.0   |   Initial Script      | Greg Elin          | 6-Sep-2014 |
# |          |   Creation            |                    |            |
# |__________|_______________________|____________________|____________|
#	                                                                  
   
	
###################### SSG INFORMATION #################################
# Rule ID: require_smb_client_signing
# CCE: CCE-26328-5
# Severity: low
# Rule Title: Require Client SMB Packet Signing, if using smbclient
# Url of this script: http://www.govready.org/fixes/require_smb_client_signing/ssg/govready/bash/fix/raw


[ -f /etc/samba/smb.conf ] || exit 0

sed  -i "/\[global\]/a \ \n\tclient signing = mandatory\n" /etc/samba/smb.conf

