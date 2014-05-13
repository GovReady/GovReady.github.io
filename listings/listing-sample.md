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
govready_version: 0.3.1

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
permalink: /nodejs4/


#####################
# Basic Information #
#####################

# Name of tech
name: NodeJS

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
vendor: White Socks Software, Inc.
packager: Santa Claus <sclaus@northpole.com>
govready_file: govready

# Primary website
website: "http://www.nodejs.org/"

# Full path to logo images
# Put product name logo in `logo1` and pure icon in `logo2`.
# Use `logo1` only if logo has name and icon
logo1: /img/listings/nodejs/nodejs.png
logo2:

# Is there a formal policy on logo usage? Note link here.
logo_usage:
  - "http://nodejs.org/logos/"
  - "http://nodejs.org/trademark-policy.pdf"


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

for: web and mobile developers
who: are building real-time web apps lots of user-to-user or user-to-server interactions
product_is: a server-side Javascript application framework with integrated web server and rich ecosystem of community plugins
that: is highly scalable 
unlike: traditional server-side application frameworks
product_features: executes in a single threaded loop with callbacks that simplifies management of asynchronous browser-to-server interactions


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
    
  - name: NodeJS
    tier: Application/Programming Language
    dependency: required
    adoption_usfed: rare
    alternatives:
      - n/a


FISMA-Certified: |
  <p><b><a href="https://github.com/18f/fbopen">FBOpen.gsa.gov</a></b> by 18F (GSA) is a FISMA-Compliant configurtion which has an Authority to Operate issued by GSA. Most of the 800-53 controls are inherited from being hosted on FedRamp-certified AWS cloud and on hardened version of Ubuntu.</p>


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

  - name: qu
    organization: CFPB
    description: Qu is a framework for building data APIs. 
    url: "https://github.com/cfpb/qu/"
    img_src: /img/listings/qu/qu_900x500.png
    live_url: "http://cfpb.github.io/qu/"


####################################
# Quick Reference - To Be Improved #
####################################
# The following is basic information on the technology
# The goal is to incorporate this information into the Quick Assessment Data. 
# For now just update information

managed_by: Joyent
managed_by_url: "http://www.joyent.com/technology/nodejs"
license_url: "https://raw.github.com/joyent/node/v0.10.26/LICENSE"
about_url: "http://www.nodejs.org/about/"
issue_tracker_url: "https://github.com/joyent/node/issues"
src_code_url: "https://github.com/joyent/node"
stable_release: "v0.10.26"
stable_release_url: "http://www.nodejs.org/download/"
commercial_support_url: "http://www.joyent.com/products/support-nodejs"


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



##########
# Videos #
##########
# Select videos that would help developers, project managemers, IT admins, CIOs rapidly grok the technology
videos:
  - <h4>NodeJS intro</h4><iframe width="260" height="157"  src="//www.youtube.com/embed/GJmFG4ffJZU" frameborder="0" allowfullscreen></iframe>
  - <h4>NodeJS Tech Internals</h4><iframe width="260" height="157" src="http://www.youtube.com/embed/L0pjVcIsU6A" frameborder="0" allowfullscreen></iframe>

# End of Frontmatter. Do not touch the `---` below.
---