---
permalink: /sample5/
layout: listing5
name: Sample

govready:
  - name: GovReady Metadata
    dedicated_webpage: false
    dedicated_feed: false
    img_src: false
    version: 1
    release: 4
    date: 2014-05-11
    note: 
    packager: Greg Elin <gregelin@gitmachines.com>

  - name: Product
    dedicated_webpage: "http://www.nodejs.org/"
    dedicated_feed: false
    feed_format: false

  - name: Product Web Site
    dedicated_webpage: "http://www.nodejs.org/"
    dedicated_feed: false
    feed_format: false

  - name: Vendor
    dedicated_webpage: "http://www.joyent.com"
    dedicated_feed: false
    feed_format: false

  - name: License
    dedicated_webpage: "https://raw.github.com/joyent/node/v0.10.26/LICENSE"
    dedicated_feed: false
    feed_format: false

  - name: Logos
    dedicated_webpage: "http://nodejs.org/logos/"
    dedicated_feed: false
    feed_format: false
    supplemental_info: 
    img_src: /img/listings/nodejs/nodejs.png

  - name: Logo Usage Policy
    dedicated_webpage: "http://nodejs.org/trademark-policy.pdf"
    dedicated_feed: false
    feed_format: false
    img_src: false

  - name: Videos
    dedicated_webpage: false
    dedicated_feed: false
    feed_format: false
    img_src: false
    supplemental_info:
      - name: Video List
        description: Examples of US Federal Instances
        details: 
          - name: NodeJS Intro
            src: "//www.youtube.com/embed/GJmFG4ffJZU"
            # - <h4>NodeJS intro</h4><iframe width="260" height="157"  src="//www.youtube.com/embed/GJmFG4ffJZU" frameborder="0" allowfullscreen></iframe>
          - name: NodeJS Tech Internals
            src: "//www.youtube.com/embed/L0pjVcIsU6A"

  - name: Security Issues
    dedicated_webpage: "https://nodesecurity.io/advisories"
    dedicated_feed: "https://nodesecurity.io/rss.xml"
    feed_format: rss
    img_src: false

  - name: Security Patches
    dedicated_webpage: false
    dedicated_feed: false
    feed_format: false
    img_src: false


  - name: Federal Government Examples
    dedicated_webpage: false
    dedicated_feed: false
    feed_format: false
    img_src: false
    supplemental_info:
      - name: List of Federal Government Examples
        description: Examples of US Federal Instances
        details: 
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


  - name: Elevator Pitch
    for: web and mobile developers
    who: are building real-time web apps lots of user-to-user or user-to-server interactions
    product_is: a server-side Javascript application framework with integrated web server and rich ecosystem of community plugins
    that: is highly scalable 
    unlike: traditional server-side application frameworks
    product_features: executes in a single threaded loop with callbacks that simplifies management of asynchronous browser-to-server interactions

  - name: Quick Assessment
    dedicated_webpage: false
    dedicated_feed: false
    feed_format: false
    img_src: false
    supplemental_info:
      - name: GovReady Quick Assessment
        description: At-a-glance assessment of product readiness for government use
        details:
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

  - name: FISMA-Components
    dedicated_webpage: false
    dedicated_feed: false
    feed_format: false
    img_src: false
    supplemental_info:
      - name: GovReady Quick Assessment
        description: At-a-glance assessment of product readiness for government use
        details:
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

  - name: FISMA-Certified Configurations
    dedicated_webpage: false
    dedicated_feed: false
    feed_format: false
    img_src: false
    supplemental_info:
      - name: List of FISMA-Certified Configurations
        description: 
        details:
          - name: FBOpen.gsa.gov
            url: https://github.com/18f/fbopen
            provider: 18F (GSA)
            description: a FISMA-Compliant configurtion which has an Authority to Operate issued by GSA. Most of the 800-53 controls are inherited from being hosted on FedRamp-certified AWS cloud and on hardened version of Ubuntu.



# End of Frontmatter. Do not touch the `---` below.
---
