---
author: slowe
comments: true
date: 2013-04-05 17:24:50+00:00
layout: post
slug: highly-recommended-quantum-and-open-vswitch-resource
title: Highly Recommended Quantum and Open vSwitch Resource
wordpress_id: 3127
categories:
- Networking
- Virtualization
tags:
- Networking
- OpenStack
- Quantum
---

If you want to read a _masterpiece_ of an article describing how OpenStack Quantum works with Open vSwitch (OVS) and the OVS plugin, [this write-up](https://a248.e.akamai.net/cdn.hpcloudsvc.com/h9f25be84b35c201beea6b13c85876258/prodaw2/Bootstrapping_OVS_Quantum---final_20130319.html) by Florian Otel should be your first stop.

Florian's treatise---it's far too in-depth and comprehensive to be referred to as anything else---covers just about everything and anything you want to know about getting OpenStack Quantum and OVS up and running. Florian not only walks readers through the configuration, but then "peels back the covers" to show them what's happening underneath. For example, the write-up documents the settings for using the Quantum DHCP agent and L3 agent, and then goes on to explain (and demonstrate!) how each of these components leverages different Linux network namespaces to accomplish their tasks.

I **highly** recommend reading and reviewing this resource, and on behalf of everyone else out there like me who's searching for more documentation on how the various OpenStack components work, I'd like to thank Florian for his efforts in putting this together. Well done.