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

# Version of this file
govready_version: 0.3

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
layout: listing4

# Identify the permalink for the rendered page. Example: `/nodejs/` to render as `http:/govready.org/nodejs/`
permalink: /apache4/


#####################
# Basic Information #
#####################

# Name of tech
name: Apache

# Adding the below to leverage RPM package manager conventions
# The information below is just sample content
#
# `Source` should uniquely identify this technology

summary: A very short phrase goes here.
version: 1.0
release: 2
copyright: GPL
group: Applications/Development
source: ftp://ftp.gnomovision.com/pub/cdplayer/cdplayer-1.0.tgz
url: http://www.gnomovision.com/cdplayer/cdplayer.html
distribution: WSS Linux
vendor: Apache Foundation

# Primary website
website: "http://httpd.apache.org/"

logo:
  dedicated_webpage: "http://www.apache.org/foundation/press/kit/"
  dedicated_feed: false
  feed_format: false
  supplemental_info: 
  img_src: "http://www.apache.org/images/feather.gif"

logo_usage:
  dedicated_webpage: "http://www.apache.org/foundation/marks/"
  dedicated_feed: false
  feed_format: false
  img_src: false

#########################
# Quick Assessment Data #
#########################
# YAML list of key-value pairs to drive quick assessment content block in right sidebar
# ONLY CHANGE THE VALUES

quick_assessment: 

  # OK to use as part of an internal-to-government service?
  - name: Internal?
    value: true
  
  # OK to use as part of a public facing service?
  - name: Public?
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

  # Is technology easy to procure
  - name: Easy procurement?
    value: true

  # Vulnerabilities tacked in NVD?
  - name: Tracked in NVD?
    value: true

  # Does SCAP content exist?
  - name: SCAP?
    value: false


##################
# Elevator Pitch #
##################
# This is the first information people will see about the item listed.
#
# The Elevator Pitch describes who, what, and why of the product. The pitch follows the format:
#
# For (target customers) who (customer need or pain paint), (product name) is a (product category) 
# that (key benefit proposition or problem-solving capability). Unlike, the product alternative),
# Our product (describe the key product features).
#
# Product name and punction is automatically inserted. 

for: organizations
who: want to utilize the web for sharing documents, data, and delivery interactive services 
product_is: a HTTP web server
that: is open source, mature, Java-based, highly-configurable and the world's most popular web server
unlike: propietary web servers
product_features: Apache and it's configuration files are well known to most system administrators and ships with most Linux distributions


##################################
# FISMA-Certified Configurations #
##################################

FISMA_components: 
  - name: facility
    tier: Infrastructure/Data center
    dependency: required
    alternatives:
      - Any FedRamp CSP
    
  - name: Linux
    tier: Infrastructure/Operating system
    dependency: required
    adoption_usfed: widely used
    alternatives:
      - Windows
    
  - name: Apache
    tier: Application/Web Server
    dependency: required
    adoption_usfed: widely used
    alternatives:
      - None


FISMA-Certified: |
  <p><b><a href="https://github.com/18f/fbopen">RedHat Enterprise Linux</a></b> by RedHat (GSA) is a widely used by government offering Linux Operationg system that includes signed software packages including Apache. </p>


##################
# Usage Gallery #
##################
# Images should be 900x500 currently. Either send the images to us, or make the image file available online.

usg_instances:
  - name: fcc.gov
    organization: FCC
    description: FCC's web site.
    url: "http://www.fcc.gov"
    img_src: "/img/listings/apache/apache-fcc-gov_900x500.png"


####################################
# Quick Reference - To Be Improved #
####################################
# The following is basic information on the technology
# The goal is to incorporate this information into the Quick Assessment Data. 
# For now just update information

managed_by: Apache Foundation
managed_by_url: "http://httpd.apache.org"
license_url: "http://www.apache.org/licenses/"
about_url: "http://httpd.apache.org/ABOUT_APACHE.html"
issue_tracker_url: "https://issues.apache.org/bugzilla/"
security_url: "http://httpd.apache.org/security_report.html"
src_code_url: "http://svn.apache.org/repos/asf/httpd/"
stable_release: "2.4.9"
stable_release_url: "http://httpd.apache.org/download.cgi"
commercial_support_url: 
  - name: OpenLogic
    url: "http://olex.openlogic.com/support/apache-support"
  - name: Pantek
    url: "http://www.pantek.com/support.php?subsect=apache&_vsrefdom=paidsearch&gclid=CO_anauNor4CFYMSOgodPy4ATw"


############
# Security #
############
# Goal is to automate this content.
# Purpose of this tab is to communicate to security professionals and developers how the technology can be monitored and patched.

security_reports: 
  dedicated_webpage: "http://httpd.apache.org/security_report.html"
  dedicated_feed: false
  feed_format: false



##########
# Videos #
##########
# Select videos that would help developers, project managemers, IT admins, CIOs rapidly grok the technology
videos:
  - <h4>Install Apache</h4><iframe width="260" height="157" src="//www.youtube.com/embed/oeZpY6JY4iI" frameborder="0" allowfullscreen></iframe>
  - <h4>Quick Apache Web Server</h4><iframe width="260" height="157" src="//www.youtube.com/embed/xCJkMIYwjp8" frameborder="0" allowfullscreen></iframe>
  - <h4>The Apache Web Server</h4><iframe width="260" height="157" src="//www.youtube.com/embed/eJ2ZPi3UCG0" frameborder="0" allowfullscreen></iframe>
  - <h4>Install Apache HTTP<br />Server 2.2.13 for Windows</h4><iframe width="260" height="157" src="//www.youtube.com/embed/8tBkEWPOqqk" frameborder="0" allowfullscreen></iframe>

#######################
# Accessibility - 508 #
#######################
# Accessibility support for individuals with disabilities

accessibility_info:
  dedicated_webpage: false
  dedicated_feed: false

accessibility_v-pat:
  dedicated_webpage: false
  dedicated_feed: false

accessibility_notes:
  - name: Apache is text-based configuration
    description: Apache configuration is text-based. Users of assistive-technologies should be able to work with Apache.
    date: 2014-05-12
    severity: success


# End of Frontmatter. Do not touch the `---` below.
---
