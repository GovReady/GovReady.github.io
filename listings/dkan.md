---
###################
# About this file #
###################
# This is a Jekyll content page for GovReady(TM) Clearinghouse technology listing.
# The GovReady Clearinghouse technology listings are still in development and may change.
# The content of this page drives the displayed content.
#
# The syntax for this file is YAML "Frontmatter" plus ASCII text formatted in markdown.
# The Front matter is all content between the "---" and "---"
# Any line begininging with a '#' is a comment and will be ignored.

#######################
# License / Copyright #
#######################
# The underlying structure of this page is Copyrighted 2014 Greg Elin. All Rights Reserved.
# Eventually, the underlying structure of this page will be copyrighted GovReady(TM).
#
# This page is a composite work, Copyrighted 2014 Greg Elin. All Rights Reserved.
# Eventually, the composite work of this page will be copyrighted GovReady(TM).
#
# Much of this page includes facts and publicly available content that is not copyrighted by Greg Elin.
# Effort has been made to identify content elements as proprietary or cited from a source. 
# The remaining should be obvious as facts or copyrighted content by other parties (e.g., logos).
#
# You may re-use the factual content and the content from other sources provided you follow the 
# contents usage guideline as indicated from the content owner.
#
# Content indicated as proprietary, or copyrighted Greg Elin, or copyrightted GovReady may not be
# re-used except as defined by Fair Use provisions or permission granted in writing.


###################
# Using this file #
###################
# To use this file, adjust the content to represent the product.


#######################
# Jekyll Instructions #
#######################

# Identify the layout template to be used for this page
layout: listing2

# Identify the permalink for the rendered page.
# Tech listings should be `/tech/` to render as `http:/govready.org/tech/`
permalink: /dkan/


#########################
# Quick Assessment Data #
#########################
# YAML list of key-value pairs to drive quick assessment content block in right sidebar
# ONLY CHANGE THE VALUES

quick_assessment: 

  # OK to use as part of an internal-to-government service?
  - name: GovReady Internal
    value: true
  
  # OK to use as part of a public facing service?
  - name: GovReady External
    value: true
  
  # Actively being used by federal agency?
  - name: In use?
    value: true
  
  # Are patches regularly published and easy to find automatically?
  - name: Patching?
    value: true
  
  # Is an enterprise version available?
  - name: Enterprise version?
    value: true
  
  # Can support be purchased?
  - name: Support?
    value: true
  
  # Suitable for what version of FISMA, L, M, H?
  - name: Recommended for FISMA
    value: L

  # Is technology easy to procure
  - name: Easy procurement?
    value: true

  # Does SCAP content exist?
  - name: SCAP?
    value: false
      

#####################
# Basic Information #
#####################

# Name of tech
name: DKAN

# Primary website
website: "http://www.nucivic.com/dkan/"

# Full path to logo images
# Put product name logo in `logo1` and pure icon in `logo2`.
# Use `logo1` only if logo has name and icon
logo1: http://nucivic.com/wp-content/uploads/2014/04/logo-dkan.png
logo2:

# Is there a formal policy on logo usage? Note link here.
logo1_usage:
  - "http://nucivic.com/about/media-kit/"


#####################
# About Tab Content #
#####################
# The following content will display under the `About` tab. 
# This is the first information people will see about the item listed.

# The Benefit paragraph is a unique summary of the benefits of the technology for government use. 
# This is content is targeted to government audience.
# GovReady reserves the right to modify this content and to own the copyright on the presented copy.
# Any content you provide will be take as a suggestion. The purpose of this arrangement is to insure
# the benefit description is provided by an editorial independent source. 
# Benefit content is Copyrighted 2014 Greg Elin. All Rights Reserved.
# ========================================================= #
benefit: |
  DKAN is a Drupal-based open data platform with a full suite of cataloging, publishing and visualization features that allows governments, nonprofits and universities to easily publish data to the public. You can host DKAN yourself or leverage cloud-based offerings from NuCivic. 


###########################
# Procurement Tab Content #
###########################
# This section is still under development.
# The purpose of this section is to describe how to legally obtain, or "procure" the technology for use. The content of this page is aimed at project managers and procurement professionals.

# Provide a narrative description describing how to categorize the technology from a procurement perspective. 
procurement_guidance: |
  <p>TBD</p> 

# List the relevent FAR sections for procurement of this item as a convenience to procurement professionals.
# This section is still under development.
procurement_references: 

  - name: TBD
    url: "TBD"
    description: TBD


##################
# Usage Gallery #
##################
# Images should be 900x500 currently. Either send the images to us, or make the image file available online.

usg_instances:
  - name: dkan
    organization: NuCivic
    description: .
    url: "https://camo.githubusercontent.com/3649fae9c6e8ef0f22772340cb88f1b343d40e06/687474703a2f2f662e636c2e6c792f6974656d732f337133763132307130683171326432413373334c2f53637265656e73686f74253230323031342d30342d323925323031382e34302e31352e706e67"
    live_url: "https://camo.githubusercontent.com/3649fae9c6e8ef0f22772340cb88f1b343d40e06/687474703a2f2f662e636c2e6c792f6974656d732f337133763132307130683171326432413373334c2f53637265656e73686f74253230323031342d30342d323925323031382e34302e31352e706e67"


####################################
# Quick Reference - To Be Improved #
####################################
# The following is basic information on the technology
# The goal is to incorporate this information into the Quick Assessment Data. 
# For now just update information

managed_by: NuCivic
managed_by_url: "http://www.nucivic.com"
license_url: "https://github.com/nuams/dkan/blob/7.x-1.x/LICENSE.txt"
about_url: "http://www.nucivic.com/dkan/"
issue_tracker_url: "https://github.com/nuams/dkan/issues"
src_code_url: "https://github.com/nuams/dkan"
stable_release: "v1.0"
stable_release_url: "https://github.com/nuams/dkan"
commercial_support_url: "http://www.nucivic.com/products/nudata"


################
# Security Tab #
################
# Goal is to automate this content.
# Purpose of this tab is to communicate to security professionals and developers how the technology can be monitored and patched.

us_cert_recent: |
  TBD


####################################
# Videos #
####################################
# Select videos that would help developers, project managemers, IT admins, CIOs rapidly grok the technology
videos:
  - <h4>DKAN 101</h4><iframe width="420" height="315" src="//www.youtube.com/embed/wj-7x9f8SIQ" frameborder="0" allowfullscreen></iframe>
  

# End of Frontmatter. Do not touch the `---` below.
---
