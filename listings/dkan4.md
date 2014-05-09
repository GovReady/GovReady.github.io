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

# Identify the permalink for the rendered page.
# Tech listings should be `/tech/` to render as `http:/govready.org/tech/`
permalink: /dkan4/


#####################
# Basic Information #
#####################

# Name of tech
name: DKAN

summary: An open data catalog publishing suite.
version: 1.0
release: 2
copyright: various
vendor: NuCivic
packager: Luke Fretwell <luke@nuams.co>
govready_file: https://github.com/GovReady/govready-dkan/raw/master/govready.md

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

  # Does SCAP content exist?
  - name: SCAP?
    value: false


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
elevator_pitch: |
  DKAN is a Drupal-based open data platform with a full suite of cataloging, publishing and visualization features that allows governments, nonprofits and universities to easily publish data to the public. You can host DKAN yourself or leverage cloud-based offerings from NuCivic. 
for: organizations
who: need to offer better access to their public data sets 
product_is: an open data catalog and portal 
that: is built on top of Drupal
unlike: bespoke data portals
product_features: combines features of the CKAN data catalog with full Drupal content management and blog capabilities

##################################
# FISMA-Certified Configurations #
##################################

FISMA_components: 
  - name: facility
    dependency: required
    
  - name: Linux
    dependency: required
    alternatives:
      - None
    
  - name: Apache
    dependency: required
    alternatives:
      - NGINX

  - name: MySQL
    dependency: required
    alternatives:
      - MariaDB
      - PostgreSQL

  - name: PHP
    dependency: required
    alternatives:
      - None

  - name: Drupal
    dependency: required
    alternatives:
      - None
    notes:
      - Part of DKAN download
    
  - name: DKAN
    dependency: required

FISMA_notes:
  - name: DKAN not yet certified
    description: Code specific to DKAN itself is not known to have been FISMA-certified. 
    date: 2014-05-09


FISMA-Certified: |
  <p><b><a href="">NuData</a></b> is a SaaS offering of DKAN that claims FISMA-Compliance because it is hosted on FedRamp-certified <a href="">Acquia Cloud</a> and hardened Drupal configuration.</p>

FISMA-Certified_DIY: |
  Begin with a FedRamp Cloud Provider. Next select a vetted Operating System image. Assemble approved configurations of Apache, PHP5 and MySQL.  DKAN's download includes Drupal version blah, blah, which corresponds to Acquia's blah, blah. The custom Drupal PHP code for DKAN's feature has yet to be FISMA-certified as of May 8, 2014.
  </p>

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
  - name: ec2mapper
    organization: CFPB
    description: EC2mapper is a web application that provides a user-friendly interface to view Amazon AWS network configurations.
    url: "https://github.com/cfpb/ec2mapper"
    img_src: "/img/listings/ec2mapper/ss2_cropped.png"

  - name: design-manual
    organization: CFPB
    description: A set of design principles and standards for the Consumer Financial Protection Bureau. 
    url: "https://github.com/cfpb/design-manual"
    img_src: /img/listings/design-manual/dm_900x500.png
    live_url: "http://cfpb.github.io/design-manual/"


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
  <a href="http://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2013-4450">10/21/2013 - CVE-2013-4450</a> <span class="text-warning">Medium severity</span> The HTTP server in Node.js 0.10.x before 0.10.21 and 0.8.x before 0.8.26 allows remote attackers to cause a denial of service (memory and CPU consumption) by sending a large number of pipelined requests without reading the response.
security:
  - "https://nodesecurity.io/advisories"
  - "https://nodesecurity.io/rss.xml"
  - "https://twitter.com/nodesecurity"
  - "http://blog.nodejs.org/"
  - "https://groups.google.com/forum/#!forum/nodejs-sec"
  - "http://www.slideshare.net/evilpacket/node-day-enterprise-nodejs-security"


####################################
# Videos #
####################################
# Select videos that would help developers, project managemers, IT admins, CIOs rapidly grok the technology
videos:
  - <h4>DKAN 101</h4><iframe width="260" height="157" src="//www.youtube.com/embed/wj-7x9f8SIQ" frameborder="0" allowfullscreen></iframe>
  
videos2:
  - name: DKAN 101
    src: "//www.youtube.com/embed/wj-7x9f8SIQ"
    duration: 

# End of Frontmatter. Do not touch the `---` below.
---
