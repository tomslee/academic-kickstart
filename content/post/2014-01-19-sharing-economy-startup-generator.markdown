---
author: Tom Slee
comments: true
date: 2014-01-19 16:53:15+00:00
excerpt: "\n\t\t\t\tIf you can't beat 'em, join 'em.\t\t"
layout: post
link: http://tomslee.net/2014/01/sharing-economy-startup-generator.html
slug: sharing-economy-startup-generator
title: "\n\t\t\t\tSharing Economy Startup Generator\t\t"
wordpress_id: 985
categories:
- sharing economy
tags:
- sharing economy
---


				
 
 


If you can't beat 'em, join 'em. Here's a pithy sharing-economy pitch for the venture capitalist in your life. Click below for more randomness.



[insert_php]
function ts_sesg_like_generate() {
   $companies = array(
        '[Airbnb](http://airbnb.com)',
        '[Etsy](http://etsy.com)',
        '[Lyft](http://lyft.com)',
        '[TaskRabbit](http://taskrabbit.com)',
        '[Uber](http://uber.com)',
   );
   return " " . $companies[array_rand($companies)];  
}

function ts_sesg_thing_generate() {  
    $things = array(  
        'for cemetery plots',
        ', but only for beautiful people', 
        ', but you pay with Bitcoin', 
        'for confession and absolution',
        'for butlers',
        'for [vacant retail spaces](http://mashable.com/2013/08/20/republic-spaces/)', 
        'for [personal fitness trainers](http://techcrunch.com/2014/01/23/backed-with-9-8m-from-mayfield-fitmob-wants-to-reinvent-local-group-fitness/)', 
        'for [people who want to share their unused assets](http://pando.com/2014/01/23/sharing-economy-foes-coming-after-our-business/)', //
        'for [skills](http://www.fastcoexist.com/3028682/change-generation/this-airbnb-for-skills-will-liberate-you-from-your-9-to-5)', // 
        'for string quartets',
        'for standup comedians',
        'for Vice Presidents of Marketing',
        'for Chief Financial Officers',
        'for private prisons and group homes',
        'for endangered species',
        'for airline pilots',
        'for psychoanalysts',
        ', but people bring you chips and guacamole',
        'for Lacanian theorists',
        'for your online reputation',
        'for your personally identifiable information',
        'for brogrammers',
        ', but you buy and sell personal data',
        ', but you auction your online passwords',
        'for software engineers',
        'for software bugs',
        'for death metal bands',
        'for brain surgeons',
        'for heart surgeons',
        'for thinkfluencers',
        'on steroids',
        ', but [only for Oxbridge graduates](http://techcrunch.com/2013/11/27/flatclub-an-airbnb-for-elite-universities-lands-1-5m-investment-to-scale-up/)', 
        'for time-of-flight mass spectrometers',
        'for personal grooming services',  
        'for unconferences and barcamps',
        'for random household appliances',
        'for sharing economy startups',
        'for sharing economy startup generators',
        'for unicycles',
        'for your spouse',
        'for [your dog](http://dogvacay.com/)',
    );       
    return " " . $things[array_rand($things)];  
}

function ts_sesg_adjective_generate() {
    $adjective = array(
        'an awesome',
        'a trusted',
        'a disruptive',
        'a grassroots',
        'a commons-based',
        'a peer-to-peer',
        'a P2P',
        'a collaborative',
        'a sustainable',
        'an innovative',
        'a social',
        'a social media',
        'a crowdsourced',
        'a nextified',
        'a Big Data',
    );
    return " " . $adjective[array_rand($adjective)];  
}

function ts_sesg_place_generate() {
    $place = array(
        'marketplace',
        'community',
        'system',
        'economy',
        'space',
        'network',
        'community marketplace',
        'platform',
    );
    return " " . $place[array_rand($place)];  
}

function ts_sesg_inhabitants_generate() {
    $inhabitants = array(
        'promoting access over ownership',
        'engaged in collaborative consumption',
        'connecting amazing people',
        'of awesome individuals',
        'of regular people',
        'of people and farms you know',
        'of neighbors',
        'of people who take pride in delivering exceptional customer service',
        'of creative individuals',
        ', but personal',
        ', generating value at scale',
        'of people just like you',
        'of makers',
        'for underutilized assets',
        ', but AWESOMER',
        'of everyday folks making a little extra money',
    );
    return " " . $inhabitants[array_rand($inhabitants)];  
}

function ts_sesg_whynot_generate() {
    $whynot = array(
        'You must be kidding',
        'Ashton Kutcher doesn\'t see the opportunity',
        'Andreessen-Horowitz says it\'s not disruptive enough',
        'That may fool Jeff Bezos, but it doesn\'t fool me',
        'Try selling that to Google Ventures',
        'Not a profitable business model',
        'Y Combinator would never combine with that',
        'Insufficiently awesome',
        'I rate you one star out of five',
    );
    return $whynot[array_rand($whynot)];  
}

function ts_sesg_reload_generate() {  
    $reload = array(  
        'TaskRabbit me another',
        'share me another',
        'create me another, micro-entrepreneur',
        'give me what I want, and give it to me right now',
        'show me the money',
        'give me something disruptive',
    );       
    return $reload[array_rand($reload)];  
}
      
$thing = ts_sesg_thing_generate();

// Output
echo "

**";
echo "It's" . ts_sesg_like_generate() . $thing . ".  
";
echo "-- " . ts_sesg_adjective_generate() . ts_sesg_place_generate() . ts_sesg_inhabitants_generate() . ".";
echo "**

";
echo "

\"" . ts_sesg_whynot_generate() . ". Now _" . ts_sesg_reload_generate() . "_.\"

";
[/insert_php]

		
