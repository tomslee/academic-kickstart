---
author: Tom Slee
comments: true
date: 2013-10-19 04:00:00+00:00
excerpt: "\n\t\t\t\tWhat it says: just some numbers about Airbnb in New York. Conclusions\
  \ are yours to draw.\t\t"
layout: post
link: http://tomslee.net/2013/10/notes-on-airbnbs-new-york-business.html
slug: notes-on-airbnbs-new-york-business
title: "\n\t\t\t\tNotes on Airbnb's New York Business\t\t"
wordpress_id: 813
categories:
- sharing economy
---


				[**Update, Nov 10:** clearer explanation [here](http://tomslee.net/2013/11/airbnb-business-in-new-york-revisited.html). PDF for download [here](http://tomslee.net/wordpress/wp-content/uploads/2013/11/airbnbny_handout.pdf).]

Two recent Airbnb blog posts make statements about its business in New York. One is from David Hantman, Airbnb’s public policy head hired from being Yahoo’s head of government relations, and it is [here](http://publicpolicy.airbnb.com/fighting-for-you/). The other is from CEO Brian Chesky, [here](http://blog.airbnb.com/who-we-are/).

I was interested in whether there are other ways to frame the picture that Chesky paints of the Airbnb business in New York, so I wrote a bit of python that downloaded as many New York listings as I could find and stuck them in a database, and here’s a few notes from what they show. I collected 9527 places rented by 7112 hosts in New York. Airbnb claims 15,000 hosts, but I suspect the others are not doing much business because the searches I did over several days did not find them.


<blockquote>In New York, our 15,000 hosts are regular people from all five boroughs. Eighty-seven percent of them rent the homes in which they live.</blockquote>


Of the 7112 hosts I found, 6038 rent one room, which is 85%. An even greater percentage (92%) rent from a single address, but there is no way to confirm if it is “the home in which they live”. These numbers are close enough to show that the data set is representative of the overall population.

But looking at it another way, only 63% (6038 of 9527) of _rooms_ are single-room offerings (that is, a host who offers only one place to stay). And only 53% (60439 of 114659) of _bookings_ are in single-room offerings (using reviews as a proxy for bookings). Assuming the same length of stay in each place, the amount of _revenue_ that comes from single-room renters is 54%. That is, very nearly half of Airbnb’s business is from hosts who are renting multiple offerings.


<blockquote>The vast majority of these hosts are everyday New Yorkers who occasionally share the home in which they live.</blockquote>


“Share the home” is open to interpretation. The stories that Chesky tells are all of people staying in their home while guests are present, which is the flavour of “sharing” that I get from the statement. But the majority of New York listings (5380 of 9527, or 56%) are for “entire home or apartment” compared to 3636 “private room” and only 511 “shared room”. The same percentage of bookings and 73% of total revenue comes from “entire home or apartment” rentals. The amount of Airbnb revenue that comes from people sharing a part of their home while they stay in it is only just over a quarter.

Chesky says that “If you want to understand Airbnb, you have to understand our beginnings” and describes how he and Joe Gebbia, both designers, had an idea when a design conference came to town: “why not turn our place into a bed and breakfast for the conference? We inflated air beds and called it the AirBed & Breakfast.” This sounds like a shared-room arrangement, but only 511 of 9527 offerings in New York are shared rooms (less than 6%) and less than 4% of the bookings are of this type. Today’s Airbnb has nothing to do with the “origin myth” that the company promotes.

So the Airbnb statements are not factually wrong, but are misleading: Airbnb’s financial interests do not align nearly as closely with its “community” as it claims.		
