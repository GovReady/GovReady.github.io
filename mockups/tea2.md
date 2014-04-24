---
layout: listing2
permalink: /mockup/tea2/

# Quick Assess
# ========================================================= #

quick_assessment: 

  - name: GovReady Internal
    value: true
  - name: GovReady External
    value: false
  - name: In use?
    value: true
  - name: Patching?
    value: false
  - name: Enterprise version?
    value: false
  - name: Support?
    value: false
  - name: Recommended for FISMA
    value: L, M, H
  - name: Easy procurement?
    value: true
  - name: SCAP?
    value: false
      

# Basic
# ========================================================= #
name: Tea
website: ""
logo1: 
logo2:
logo1_usage:
  - "http://nodejs.org/logos/"
  - "http://nodejs.org/trademark-policy.pdf"
accreditations:
  - FISMA Low (CFPB)
  - Awesome

description: |
  Some description for Tea goes here.

description_src: Wikipedia
description_src_url: "http://wikipedia.org/en/nodejs"

# Benefit - (Copyright 2014 Greg Elin. All Rights Reserved.)
# ========================================================= #
benefit: |
  Tea supports statiticians and economists who need to impute missing and erroneous data in large data sets, including data sets of hundreds of millions of rows. Unlike other techniques, Tea works with data in R and provides user-friendly data quality specification and simple way to specify which  statistical model to use to impute missing data models. 

  <p>Tea is considered <b>GovReady for internal use by federal agencies</b> because Tea was developed by Census economist Ben Klemens and Census econonmist Roland Rodriques and is currently used in the Census data preparation.</p>


# Procurement
# ========================================================= #
procurement_guidance: |
  <p>NodeJS is licensed to the general public therefore should be treated as commercial computer software (e.g., COTS) as per <a href="http://acquisition.gov/far/current/html/Subpart%202_1.html#wp1145508">FAR Supbart 2.101</a>.</p> 

  <p>NodeJS is available as open source software and in this format can be acquired and used at no contract directly by agency staff and contractors according to the agency's policy on open source software. Staff and contractors at government agencies that do not have formal open source software policy are authorized to use open source according to the FAR.</p>

  <p>An enterprise version of NodeJS is offered by <a href="http://www.joyent.com/technology/nodejs">Joyent</a>. As of this writing, only Joyent offering an enterprise version of NodeJS and therefore is eligible for sole source acquisition.</p> 

  <p>Various vendors host applications in NodeJS. Various vendors support NodeJS and NodeJS applications.</p>

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



# Usage - (Facts, no copyright)
# ========================================================= #
usg_instances:
  - name: ec2mapper
    organization: CFPB
    description: EC2mapper is a web application that provides a user-friendly interface to view Amazon AWS network configurations, while allowing changes to be easily tracked over time.
    url: "https://github.com/cfpb/ec2mapper"
    img_src: "/img/listings/ec2mapper/ss4_thm.png"

  - name: design-manual
    organization: CFPB
    description: A set of design principles and standards for the Consumer Financial Protection Bureau. 
    url: "https://github.com/cfpb/design-manual"
    img_src: /img/listings/design-manual/dm_thm.png
    live_url: "http://cfpb.github.io/design-manual/"

  - name: qu
    organization: CFPB
    description: Qu is a framework for building data APIs. It is still under heavy development and is changing rapidly. Qu was created to serve the Consumer Financial Protection Bureau's public data sets.
    url: "https://github.com/cfpb/qu/"
    img_src: /img/listings/qu/qu_thm.png
    live_url: "http://cfpb.github.io/qu/"

# Summary - (Facts, no copyright)
# ========================================================= #
managed_by: Joyent
managed_by_url: "http://www.joyent.com/technology/nodejs"
license_url: "https://raw.github.com/joyent/node/v0.10.26/LICENSE"
about_url: "http://www.nodejs.org/about/"
issue_tracker_url: "https://github.com/joyent/node/issues"
src_code_url: "https://github.com/joyent/node"
stable_release: "v0.10.26"
stable_release_url: "http://www.nodejs.org/download/"
commercial_support_url: "http://www.joyent.com/products/support-nodejs"

# Security - (Copr)
# ========================================================= #
us_cert_recent: |
  <a href="http://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2013-4450">10/21/2013 - CVE-2013-4450</a> <span class="text-warning">Medium severity</span> The HTTP server in Node.js 0.10.x before 0.10.21 and 0.8.x before 0.8.26 allows remote attackers to cause a denial of service (memory and CPU consumption) by sending a large number of pipelined requests without reading the response.
security:
  - "https://nodesecurity.io/advisories"
  - "https://nodesecurity.io/rss.xml"
  - "https://twitter.com/nodesecurity"
  - "http://blog.nodejs.org/"
  - "https://groups.google.com/forum/#!forum/nodejs-sec"
  - "http://www.slideshare.net/evilpacket/node-day-enterprise-nodejs-security"

# Videos
# ========================================================= #
videos:
  - <h4>NodeJS intro</h4><iframe width="260" height="157"  src="//www.youtube.com/embed/GJmFG4ffJZU" frameborder="0" allowfullscreen></iframe>
  - <h4>NodeJS Tech Internals</h4><iframe width="260" height="157" src="http://www.youtube.com/embed/L0pjVcIsU6A" frameborder="0" allowfullscreen></iframe>
  


---

[ec2mapper](https://github.com/cfpb/ec2mapper "ec2mapper on GitHub") (internal)



bekk.github.io/retire.js

oswap
sdfdfsd
