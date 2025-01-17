---
author: Tom Slee
comments: true
date: 2015-11-08 20:56:52+00:00
excerpt: "\n\t\t\t\tCurrent reputation systems show to contradictory effects: everybody\
  \ is above average (Lake Wobegon effect) and yet service providers live in fear\
  \ bad of ratings (Panopticon effect). I present a model that explains this, and\
  \ which argues that reputation systems are to be avoided.\t\t"
layout: post
link: http://tomslee.net/2015/11/lake-wobegon-and-the-panopticon-a-simulation-of-real-world-reputation-systems.html
slug: lake-wobegon-and-the-panopticon-a-simulation-of-real-world-reputation-systems
title: "\n\t\t\t\tLake Wobegon and the Panopticon: a simulation of real-world reputation\
  \ systems\t\t"
wordpress_id: 3598
tags:
- reputation-systems
---


				For some time I have been working on a simulation of reputation systems: a computational model I can use to think through some of the issues they raise. A first pass at this model is now available, together with a fairly long document describing how it works and some results, on GitHub as a Jupyter notebook [here](https://github.com/tomslee/provider-reputation/blob/master/provider-reputation.ipynb).

I was particularly interested in a seeming paradox in what we have learned about real-world reputation systems. As I say in the introduction:


In the few years since they have become widespread, reputation systems have shown two seemingly contradictory characteristics:






	
  1. 


<blockquote>(Lake Wobegon effect) Most ratings are very high. While ratings of Netflix movies peak around 3.5 out of 5, ratings on sharing economy websites are almost all positive (mostly five stars out of five). The oldest and most widely-studied reputation system is eBay, in which well over 90% of ratings are positive; other systems such as BlaBlaCar show over 95% of ratings as "five out of five".</blockquote>




	
  2. 


<blockquote>(Panopticon effect). Service providers live in fear of a bad rating. They are very apprehensive that ratings given for the most frivolous of reasons by a customer they will never see again (and may not be able to identify) may wreck their earnings opportunities, either by outright removal from a platform or by pushing them down the rankings in search recommendations. Yelp restaurant owners rail at "drive-by reviewers" who damage their reputation; Uber drivers fear being "deactivated" (fired), which can happen if their rating slips below 4.6 out of 5 (a rating that would be stellar for a movie).</blockquote>







So are reputation systems effective or not? Here's the seeming contradiction:






	
  1. 


<blockquote>The Lake Wobegon effect suggests that reputation systems are useless: they fail to discriminate between good and bad service providers (my take on this from a couple of years ago is [here](http://tomslee.net/2013/09/some-obvious-things-about-internet-reputation-systems.html)). This suggestion is supported by quite a bit of recent empirical research which I have summarized in [MY NEW BOOK!](http://www.orbooks.com/catalog/whats-yours-is-mine-by-tom-slee/). Customers are treating reviews as a courtesy, rather than as an opportunity for objective assessment. Rather like a guest book, customers leave nice comments or say nothing at all.</blockquote>




	
  2. 


<blockquote>The Panopticon effect suggests that rating systems are extremely effective in controlling the behaviour of service-providers, leading them to be customer-pleasing (sometimes extravagantly so) in order to avoid a damaging bad review.</blockquote>





If you are not a fan of computer models, or just have better things to do, here are my main conclusions, paraphrased:

	
  * The model demonstrates the important role of social exchange compared to a pure market or transactional exchange in most customer--service provider exchanges. It is this social exchange that is at the root of the Lake Wobegon effect, where all providers are above average. Reputation systems do indeed fail to discriminate on the basis of competence (quality).

	
  * A small number of entitled customers can induce a Panopticon effect. Service providers who engage in Give & Take exchanges with their customers (even very competent ones) risk being given a negative review, which will damage their business. The incentives of the reputation system encourage providers to indulge their customers, in order to avoid this unlikely but damaging judgement.

	
  * If reputation systems spread and customers become used to rating people in an "honest" fashion, we are building a terrible world for service providers. They must engage in emotional labour, catering to customer whims, or risk their livelihood. The Panopticon is here. The reputation systems continue, it should be noted, to fail to discriminate based on the competence of the service provider -- instead of changing quality, they change attitude.

	
  * The Lake Wobegon effect and the Panopticon effect can coexist, and are coexisting. Reputation systems as they currently stand are failing to discriminate based on quality. But there is only one thing worse than a reputation system that doesn't work, and that's a reputation system that does work: Reputation systems promise a dystopic future for service providers, in which their careers are being shaped by reputation systems that are not working as advertised, but are working to compel compliance.

		
