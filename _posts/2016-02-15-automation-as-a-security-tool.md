---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: "Security in a DevOps world doesn't have to be difficult.  In fact, you can automate most of your environment.  But of course, there's a catch."
datePublished: '2016-02-15T19:42:04.754Z'
dateModified: '2016-02-15T19:41:59.448Z'
title: Automation as a Security Tool
author: []
sourcePath: _posts/2016-02-15-automation-as-a-security-tool.md
published: true
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
url: automation-as-a-security-tool/index.html
_type: Article

---
![](https://s3-us-west-2.amazonaws.com/the-grid-img/p/b7723457ef2bc2c1980e531c8152e53e4a7d2b53.jpg)

**The Rise of Automation**

Automation isn't something new. From the dawn of man, we have used our brains to make tools, improve upon them, and make our lives easier. We are now approaching a point of convergence in the Information Technology world, where systems engineering and network engineering are now converging. We talk about this more, in a different post. (The Dawn of the Automation Engineer) Automation is a combination of a multitude of skill sets, including project management, networking, programming, monitoring, reporting, operations, security and more. In order to effectively operate you need orchestration, which currently is disparate and scattered among the variety of open source, closed source, and specific verticals.

At the same time this is happening, we are seeing several critical issues arising in the development, deployment, security and knowledge about how these tools actually work, are secured, and are operated. As many of these systems are less than 5 (five) years old, we are seeing a number of new issues as we move deeper into this space. Some of these problems are race conditions, which everyone fears, but most of them are simpler than that. There have been catastrophic issues with files being exposed to the internet, or an API call not having any AAA on it; to issues with automation being developed to deploy systems or changes, but nothing to manage those systems or changes throughout the entire Information Technology life-cycle. 

Imagine, a system where you could enable all of your users to create new firewall rules for the development environment. Sounds like a great idea! Let's do it! What is going to happen? What do you work on first? When is the tool ready for Operations? Who is going to maintain the code? Is the code portable for a different firewall product/vendor/system/solution in the next 3 years? Who is going to sunset that codebase? Who is going to sunset the firewalls? Who is going to operate, maintain, and clean the firewalls of old rules? How is this going to be accomplished? Who is going to be ultimately responsible when the firewall fails due to the automation system? 

Many of these questions have NEVER been asked in a development life cycle, because companies would actually realize the cost of developing their own software.