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
permalink: /nodejs/


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
name: NodeJS

# Primary website
website: "http://www.nodejs.org/"

# Full path to logo images
# Put product name logo in `logo1` and pure icon in `logo2`.
# Use `logo1` only if logo has name and icon
logo1: /img/listings/nodejs/nodejs.png
logo2:

# Is there a formal policy on logo usage? Note link here.
logo1_usage:
  - "http://nodejs.org/logos/"
  - "http://nodejs.org/trademark-policy.pdf"


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
  NodeJS significantly lowers the cost of large scale, real-time web apps with lots of interactions back and forth between the user and the server or between the users. NodeJS is also useful when user interactions trigger different types of events on the server that take varying amounts of time to complete. 


###########################
# Procurement Tab Content #
###########################
# This section is still under development.
# The purpose of this section is to describe how to legally obtain, or "procure" the technology for use. The content of this page is aimed at project managers and procurement professionals.

# Provide a narrative description describing how to categorize the technology from a procurement perspective. 
procurement_guidance: |
  <p>NodeJS is licensed to the general public therefore should be treated as commercial computer software (e.g., COTS) as per <a href="http://acquisition.gov/far/current/html/Subpart%202_1.html#wp1145508">FAR Supbart 2.101</a>.</p> 

  <p>NodeJS is available as open source software and in this format can be acquired and used at no contract directly by agency staff and contractors according to the agency's policy on open source software. Staff and contractors at government agencies that do not have formal open source software policy are authorized to use open source according to the FAR.</p>

  <p>An enterprise version of NodeJS is offered by <a href="http://www.joyent.com/technology/nodejs">Joyent</a>. As of this writing, only Joyent offering an enterprise version of NodeJS and therefore is eligible for sole source acquisition.</p> 

  <p>Various vendors host applications in NodeJS. Various vendors support NodeJS and NodeJS applications.</p>

# List the relevent FAR sections for procurement of this item as a convenience to procurement professionals.
# This section is still under development.
procurement_references: 

  - name: FAR Part 12—Acquisition of Commercial Items
    url: "http://acquisition.gov/far/current/html/FARTOCP12.html"
    description: This section describes purchase options

  - name: Federal Acquisition Regulation; FAR Case 2000-305, Commercially Available Off-the-Shelf (COTS) Items
    url: "https://www.federalregister.gov/articles/2009/01/15/E9-551/federal-acquisition-regulation-far-case-2000-305-commercially-available-off-the-shelf-cots-items"
    summary: |
      The Civilian Agency Acquisition Council and the Defense Acquisition Regulations Council (Councils) have agreed on a final rule amending the Federal Acquisition Regulation (FAR) to implement Section 4203 of the Clinger-Cohen Act of 1996 (41 U.S.C. 431) (the Act) with respect to the inapplicability of certain laws to contracts and subcontracts for the acquisition of commercially available off-the-shelf (COTS) items.

  - name: "Free-Libre / Open Source Software (FLOSS) is Commercial Software"
    url: "http://www.dwheeler.com/essays/commercial-floss.html"
    description: | 
      Nearly all FLOSS projects are commercial. In this essay I’ll explain why it so important to understand that FLOSS software is almost always commercial, and then give examples of each of those four points (listed above) to justify the claim that FLOSS is commercial. 


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


####################################
# Videos #
####################################
# Select videos that would help developers, project managemers, IT admins, CIOs rapidly grok the technology
videos:
  - <h4>NodeJS intro</h4><iframe width="260" height="157"  src="//www.youtube.com/embed/GJmFG4ffJZU" frameborder="0" allowfullscreen></iframe>
  - <h4>NodeJS Tech Internals</h4><iframe width="260" height="157" src="http://www.youtube.com/embed/L0pjVcIsU6A" frameborder="0" allowfullscreen></iframe>
  

# End of Frontmatter. Do not touch the `---` below.
---

