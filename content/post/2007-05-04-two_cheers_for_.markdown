---
author: Tom Slee
comments: true
date: 2007-05-04 12:23:52+00:00
excerpt: "\n\t\t\t\t\t\t"
layout: post
link: http://tomslee.net/2007/05/two_cheers_for_.html
slug: two_cheers_for_
title: "\n\t\t\t\tTwo Cheers for Technology\t\t"
wordpress_id: 227
---


				

Being a little technosmug I recently volunteered to revive the website for the Kitchener-Waterloo NDP. The results so far are online at [http://www.kwndp.ca](http://www.kwndp.ca). In getting this far I've learned a whole lot of new words and been hugely impressed by some of the software that is now available. It's a new world out there kids. But of course, being also technosceptical, I have some second thoughts.




First things first. I am lazy of course, so I wanted to make sure that not every change
to the web site had to go through me. Also, I wanted a system where
members can log in, so a database-hosted site of some kind made sense.
I found and went with a content-management system called [drupal](http://drupal.org/). To see whether this is widely used I did a google trends search and it seems like [quite the thing](http://www.google.com/trends?q=drupal) these days, although not quite so much as its newer offspring [joomla](http://www.joomla.org/) (google trends comparison [here](http://www.google.com/trends?q=drupal%2C+joomla&ctab=0&geo=all&date=all)).
I went with drupal because it seems a little more open, if a little
less user friendly. It’s a PHP package that is usually hosted on a
MySQL server using the MyISAM storage engine.





There’s quite
a lot of install assistance for drupal. Basically, the ISP provides me
with an empty MySQL database on their server, and an admin login to
that database. I used [filezilla](http://filezilla.sourceforge.net/) to ftp the files to the ISP server, [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/) to get a secure command line interface, and followed the
instructions. After one misstep, which turned a [ten minute process](http://drupal.org/node/130116)
into an hour, I was able to open a browser, point it at the domain
name, log in using the admin password my ISP had provided, and there
was a drupal home page with items to create accounts and add content.
From here on, pretty much everything is done by browser.




There’s a [drupal cookbook for beginners](http://drupal.org/node/120612)
which walks you through making some sensible settings. You can add
menus to each page, allow comments on pages (like the online
documentation initiative), add different content types (individual
pages, “books” which have several pages of related content, and so on). You can also create users and define roles, so that visitors (external
users of the site) see a web site, but users who log in can (depending
on what role I give them) can create content or carry out other tasks.
So I think drupal does the trick in allowing me to be lazy, while
keeping the site secure.




There are two ways of extending a web
site set up with drupal. One is themes - page layouts and colours. I’m
just starting to customize our site so it has a theme that reflects the
organization. The nice thing is that you can submit themes back to
drupal or share them with other sites, so riding associations in other
cities could, if they like the look of the KW site, adopt it too.




The second is modules, which are add-on packages. Some are simple, like providing a contact form. 




I haven’t seen
wiki modules, but there are blogging modules so we could host a
candidate’s blog during the election campaign, and forum modules
(internal or external discussions).




Other modules are complete applications in themselves. For example, I came across something called [CiviCRM](http://civicrm.org/),
which is a “constituent relationship management” package for community
groups. It helps to manage volunteers, fundraising and other campaigns.
So maybe the web site can be not just a public face for the riding
association, but it can also serve (once people log in and once I
assign them to a role that has the right privileges) as a tool for
managing membership, election campaigns (who has signs on their lawns
and so on) and all that. I’m just starting to look into it, but it
looks pretty cool and extensive. It installs as a drupal module, so it
should just add to the site I already have. 




And all this drupal infrastructure (as you can see from the google
trends page) has been built in the last three or four years. Remarkable.  






So I’m very impressed and pretty excited about
doing more with this. Why only two cheers then?




Mainly because, if effective technology is what makes community groups and other volunteer-driven groups effective, we should be living in a golden age of participatory democracy, where larger numbers of people than ever are able to take part in everything from supporting their local orchestra to global projects. And while my friend Ruth disagrees, I don't think we are. Participation in politics (as seen by voting rates and party memberships) is down across the board, I think, compared to a few decades ago; protests against the Iraq war have been, those big ones in 203 excepted, muted compared to previous wars. There's a disconnect.




Technology is fine, but we should remember that it's just one piece of the puzzle. So while an e-mail blast automated from a server is much more efficient than afternoons spent licking envelopes in a church basement or the constituency party rooms, it doesn't necessarily free volunteers up to do other things. My own suspicion is because the social aspect of being in an activist group is essential to people, and while licking stamps may not be that thrilling (Principal Skinner's opinion notwithstanding, if you remember the Simpson's episode about the chocolate factory visit), the opportunity to hang out with other group members for an afternoon is part of what we join groups for.




So I'll carry on with the site, and enjoy doing it. But I won't kid myself that the success or failure of the site has much to do with the success or failure of the NDP.


		
