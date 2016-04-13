listi---
layout: blogposts
name: 2014-07-13-value-multi-platform-test-environment2.md
title: TestMachines - A Multi-Platform Testing Environment for GovReady
desc: Creating a multi-platform environment to test a multi-platform GovReady 
shortdesc:  In a first attempt at creating a one week cycle of value generation for GovReady, I set out to make the existing GovReady code cross-platform. How well did I do and what did I learn?
permalink: /blog/creating-multi-platform-testing-environment-for-GovReady2
year: 2014
month: 07
day: 13
author: Greg Elin
---

## Summary
When you start a project, it's easy to imagine the yyyyyy.

This week's target value: make the existing GovReady code multi-platform to support both Red Hat/CentOS and Ubuntu Linux distros. 

This week's actual value: delivery of a multi-platform testing environment that makes development easier. <a href="http://github.com/govready/testmachines">Clone GovReady's multi-platform testing environment on GitHub</a>.

### Lessons Learned
- Good practices for cross-platform code involves a single code base, choosing SIMPLE over DRY, and really thinking
- VBKick's postinstall is not adding in vagrant additionas as I expected
- Even a fully automated how long build is a long time if you have do it several times to debug
- How to not require TTY in sudoers on CentOS.
- A re-usable test environment should probably be its own repository

### Details

I have a new process-oriented goal to create a one week cycle of value generation for GovReady. The idea is to establish a regular, measurable cadence of producing value in the project. 



The value I hoped to add to GovReady this past week was to make the existing code work across two major flavors of Linux: RedHat and Ubuntu.



I only got as far as creating a repository of two virtual machines for to GovReady to make it easier to test GovReady on different platforms. This is scaffolding. The real goal is one-script that can be run on Fedora-based Linux distress (centos, redhat) popular in government and Ubuntu distributions popular with developers.


So what value did I create and how well efficiently did I create that value?

Two vm for testing.
Highlight here is the inclusion of vbkick to control all the elements.

I want. Cross platform. Found this link on cross platform. And here is test.

Click also have me trouble and learned something. Require ttty.
Don't understand why it is failing.

Did about a 2 or 3 on a scale of 5.  My first time.
Estimating effort poor.
Shipping good. I shipped something
Blog post good b. I did it and easy to not do it.


Next week do the cross platform changes.
