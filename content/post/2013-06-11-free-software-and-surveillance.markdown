---
author: Tom Slee
comments: true
date: 2013-06-11 02:41:53+00:00
excerpt: "\n\t\t\t\t\t\t"
layout: post
link: http://tomslee.net/2013/06/free-software-and-surveillance.html
slug: free-software-and-surveillance
title: "\n\t\t\t\tFree Software and Surveillance\t\t"
wordpress_id: 564
---


				There is much that is moving and challenging in [Jacob Appelbaum's 29C3 keynote from December 2012](http://boingboing.net/2013/02/15/jacob-appelbaums-29c3-keynot.html), about the surveillance state, and Appelbaum has earned the right to be listened to from his work on the [Tor Project](https://www.torproject.org/). But...



At several places Appelbaum asserts that creating free software is a way of acting against institutions such as the NSA, and a way of building a better world. So at 12'01": "It is possible to make a living making free software for freedom, instead of closed source proprietary malware for cops", and at 40'50": "everyone that's worked on free software and open source software… these are things we should try to focus on… When we build free and open source software… we are enabling people to be free in ways that they were not. Literally, people who write free software are granting liberties."

The picture of hackers versus spooks, positioning free and open source software as an alternative to the surveillance technologies of the NSA, just doesn't hold up. Appelbaum must know that the NSA has a long history of engagement with open-source software, so "closed source proprietary malware for cops" mischaracterizes the technology of surveillance. The NSA [Boundless Informant](http://www.guardian.co.uk/world/2013/jun/08/nsa-boundless-informant-global-datamining) data-mining tool proclaims that it "leverages FOSS technology", specifically the Hadoop File System, MapReduce (perhaps built on the [Apache Accumulo](http://en.wikipedia.org/wiki/Apache_Accumulo) project, which was created by the NSA and contributed to the Apache Foundation), and CloudBase.

These are just the most recent examples: the NSA holds Open Source  industry Days, like [this one](http://www.mil-oss.org/about/news-and-events/13-news/26-ossi-and-nsa-team-up-for-open-source-industry-day) last year; it developed the [SELinux](http://en.wikipedia.org/wiki/Security-Enhanced_Linux) mechanisms for supporting access control security policies that has been integrated into the mainline Linux kernel since version 2.6. There's a good chance that the NSA's [huge new data center](http://www.wired.com/threatlevel/2012/03/ff_nsadatacenter/all/1) in Bluffdale, Utah, which Appelbaum describes at the beginning of his talk, is running open source SELinux software on every computer.

And beyond the NSA, the new set of "Big Data" technologies associated with data acquisition and analysis has strong open source roots. These are the file systems, data storage systems and data-processing systems built to manage data sets that span so many disks that routine failure of servers is expected, and tolerance for such failure must be built into the system. While much of the initiative came from proprietary systems built at the web giants (Google File System, Google Big Table, Amazon Dynamo), the open source implementations of Hadoop File System, Hadoop Map Reduce, and databases such as MongoDB and Cassandra are becoming the industry norm. Surveillance is as much an open source phenomenon as a closed source one.

These are all well-known facts, but maybe they need to be restated. Let me be clear: I'm not reversing Appelbaum's claim. There is a great deal of closed source software around the surveillance and internet control landscape as well. And (full disclaimer), my salary is paid by (but I do not speak for) a company that mainly makes its money off closed source software, so I'm not claiming a moral high ground here. But to trumpet free and open source software as an alternative to the surveillance  systems  it has helped to build is nothing but wishful thinking.

----





Date: 2013-06-10 Mon. [Emacs](http://www.gnu.org/software/emacs/) 24.3.1 ([Org](http://orgmode.org) mode 8.0.3)





		
