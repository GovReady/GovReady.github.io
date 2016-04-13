---
layout: blogposts
name: 2014-07-13-value-multi-platform-test-environment.md
title: TestMachines - A Multi-Platform Testing Environment for GovReady
desc: Creating a multi-platform environment to test a multi-platform GovReady 
shortdesc:  In a first attempt at creating a one week cycle of value generation for GovReady, I set out to make the existing GovReady code cross-platform. How well did I do and what did I learn?
permalink: /blog/creating-multi-platform-testing-environment-for-GovReady
year: 2014
month: 07
day: 13
author: Greg Elin
---

## Summary
I have a new goal to create a one week cycle of value generation for GovReady. 

This week's target value: make the existing GovReady code multi-platform to support both Red Hat/CentOS and Ubuntu Linux distros. 

This week's actual value: delivery of a multi-platform testing environment that makes development easier. <a href="http://github.com/govready/testmachines">Clone GovReady's multi-platform testing environment on GitHub</a>.

### Lessons Learned
- Good practices for cross-platform code involves a single code base, choosing SIMPLE over DRY, and really thinking
- VBKick's postinstall is not adding in vagrant additionas as I expected
- Even a fully automated how long build is a long time if you have do it several times to debug
- How to not require TTY in sudoers on CentOS.
- A re-usable test environment should probably be its own repository

### Details

I have a new process-oriented goal to create a one week cycle of value generation for GovReady. The idea is to establish a regular, measurable cadence of producing value in the project. A regular cadence guarantees regular progress and a better ability to measure, estimate, and plan.

The value I wanted to add to GovReady this past week was to make the existing code work across two major flavors of Linux: RedHat and Ubuntu.






The above statement begets the question, what is value? For the moment we will define value from two perspectives, someone using GovReady code (current and future customers) and GovReady investors/stakeholders (myself, the team, and Knight Foundation, and future investors).

Value from the perspective of someone using GovReady is a feature, modification, or change in product, environment, or their situation that heightens their appreciation and attachment to GovReady. In other words, it is a something that improves their circumstance to which they affirmatively attribute GovReady with the improvement. For example, reducing pain, saving them time, providing feeling of accomplishment, improves their standing with others. Helps with their story and journey.

What's value? Value is in eye of beholder. The guys who mow my yard in 40 min save me time and pain and do a better job. I attribute my positive feelings about the yard and my improved standing with neighbors to nary's good work.

Value for GovReady users is the right tools for the job.

Value to me is I can create more value next week. Eventually I offer someone else more value than get themselves and offer investors I can do more w their money.

Value from perspective of GovReady investors/stakeholders is that which transforms their investment into something larger than investment. It means the same expenditure in the future will produce more of the desired result in the future than what a future identical expenditure would have produced if made again with out the change.

Concretely, I added two virtual machines to GovReady to make it easier to test GovReady on different platforms. This is scaffolding. The real goal is one-script that can be run on Fedora-based Linux distress (centos, redhat) popular in government and Ubuntu distributions popular with developers.


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
