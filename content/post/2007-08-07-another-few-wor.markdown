---
author: Tom Slee
comments: true
date: 2007-08-07 21:56:38+00:00
excerpt: "\n\t\t\t\t\t\t"
layout: post
link: http://tomslee.net/2007/08/another-few-wor.html
slug: another-few-wor
title: "\n\t\t\t\tAnother Few Words on Netflix\t\t"
wordpress_id: 205
---


				

Last week's [post](http://whimsley.typepad.com/whimsley/2007/07/the-limitations.html) on the Netflix Prize brought more readers here than anything else I've written. 




Being vain I tracked its progress - it got few readers in the first couple of days, then a burst because of being picked up by the Economist Link Mafia of [Brad DeLong](http://delong.typepad.com/sdj/2007/07/tom-slee-on-dis.html) and [Marginal Revolution](http://www.marginalrevolution.com) - thanks to both. But the big spike came when someone picked it up from there and posted it to [reddit](http://www.reddit.com). Then it made its way to some other tech sites like [ycombinator](http://news.ycombinator.com) and [geekpress](http://www.geekpress.com), and that kept things going for a while. After a week, the server's disks are having a chance to cool down.




There were lots of good comments as well on the various places it got listed (as well as here).




[ZH](http://whimsley.typepad.com/whimsley/2007/07/the-limitations.html#comments) suggested using a Java app together with HSQL to do analysis. I'm confident that SQL Anywhere is as fast as HSQL, but you are right that you could do more with the data in an application than with simple queries like I was doing. However, in the end you have to deal with sparse matrices, and databases don't usually store or manipulate those well.




Someone on reddit (can't find the link now) posted that they have posted a C++ framework for analyzing the data set, together with one of the more popular avenues, a Singular Value Decomposition algorithm. So if you want to be able to try out algorithms that are better than Netflix' current one, then go hunt the article on reddit and you'll find one.




Quite a few people pointed out that just because there seem to be challenges with the Netflix Prize because of the way the data is collected doesn't mean all recommender systems must be thrown in the bin, and I agree. Narrowing it down to one person per "customer" instead of a household would help. Other things (mood indicators, half star ratings) may make incremental improvements. But for movies, mostly watched once, there are always going to be some issues of variability. For music - and anything else where we return over and over again to something we buy or experience - rating systems have a better chance of success. Mostly we buy music we either know we like or have a good idea we will like, so we can use purchases instead of surveys as a way of tracking preferences. But movies are experience goods except for those few you may watch more than once.




The other main topic was people's experience of rating systems. This seemed highly variable - some say they are useless, others that they are fine, and others that a small difference in accuracy may make a big difference. Some suggested that tracking the RMSE is not very useful - but that was Netflix's decision, not mine. What I find interesting here is that with all the impressions we have collected now there is so little (that I know of) to back up or refute our subjective impressions.




And now it's time for this blog to step off the information highway and back onto the information backroads where it belongs.


		
