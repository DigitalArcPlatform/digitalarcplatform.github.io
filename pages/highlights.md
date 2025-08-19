--- 
title: DigitalArc Highlights
layout: blank
permalink: /highlights/
--- 
{% capture timestamp %}January 1, {{site.sitedate}}{% endcapture %}
{% assign SiteYear = timestamp | date: "%Y" %}
{% assign NowYear = "now" | date: "%Y" %}

<html class="no-js" lang="en" dir="ltr">
<head>
{% include _head.html %}
</head>
<body id="the-body">


<!--
==================================================
Body
================================================== -->

<div data-sticky-container style="width: 100%" class="accentbg">
<div data-sticky data-options="marginTop:0;" data-top-anchor="the-body:top" style="width: 100%">

<div class="title-bar accentbg" data-responsive-toggle="example-menu" data-hide-for="medium" style="width: 100%">
<button class="menu-icon" type="button" data-toggle="example-menu"></button>
<div class="title-bar-title">{{ site.title }}</div>
</div>

<!--
==================================================
Top Bar
================================================== -->
<div class="top-bar accentbg" id="example-menu" style="width: 100%; background-color: #004042">
<ul class="vertical medium-horizontal dropdown menu menu-hover-lines" data-responsive-menu="accordion medium-dropdown">
<!--
==================================================
Home Link for Mobile
================================================== -->
<li class="accentbg home-nav-small">
<a href="{{ site.baseurl }}/">
Home
</a>
</li>
<!--
==================================================
Nav Loop
================================================== -->
{% for nav in site.data.navigation %}
<li class="accentbg {% if page.url == nav.url %}active{% endif %}">
{% if nav.url contains "http" %}<a href="{{ nav.url }}" target="_blank">{% else %}<a href="{{ site.baseurl }}{{ nav.url }}">{% endif %}
{{ nav.title }}<!--{{ page.url }} == {{ nav.url }}-->

</a>
</li>
{% endfor %}
</ul>
</div>

</div>
</div>

<!--default start-->


<div style="background-color: #D3EAEE; padding-bottom: .25rem; border-top, border-bottom: 3px dotted #D94f30">
<div class="grid-container">
<div class="sitetitle center">
<img src="{{site.baseurl}}{{site.urlimg}}DigitalArc.svg" style="height: 9rem;" alt="DigitalArc Platform Logo" />
<h4 class="center" style="margin-bottom: .25rem;">An exhibit platform for collective storytelling &amp; community archives</h4>
</div>
</div>
</div>

<div class="grid-container" markdown=1>
 
# DigitalArc Highlights
{: .subheadline }

## Gary, Indiana Midtown Fest, June 19-22, 2025

> This is Gary along with core community collaborators kick-off the Voices of Gary, a community-led digital archive and storytelling initiative


<img src="../assets/highlights/gary_midtown_memorywalk.png" alt="Gary Indiana Midtown Fest Memory Walk Poster" width="300" height="400" style="border: 1px solid \#000; float: left; padding: .5em;"> 

<img src="../assets/highlights/gary_midtown_voices.png" alt="Gary Indiana Midtown Fest Voices of Gary Poster" width="300" height="400" style="border: 1px solid \#000; float: right; padding: .5em;">

As part of Gary Indiana's Midtown Fest, which celebrates Gary's culture and communities, This is Gary! / Voices of Gary participated in this three-day celebration by hosting a Memory Walk showcasing landmarks, people, and events that makeup this town's glorious past and present. The Memory Walk was developed as a way to engage community members in the telling of a particular story that centers a pivotal aspect of Gary -- what they may recall, what they know, and how they may have particpated. It also allowed community partners to promote an upcoming community story-sharing event in August 2025 in which community members can archive their stories as part of the Voices of Gary digital community archive.

## DigitalArc In-Person Workshop, May 29 - June 1, 2025 in Bloomington, Indiana

> DigitalArc project team and partners walkthrough a “history harvest” during summer in-person workshop

Midwest community leaders worked toward their digital archiving goals at the DigitalArc In-Person Workshop from May 31-June 1, 2025, in Bloomington, Indiana. The focus on this worksop was community and collections. Representing Gary, Indiana Roberts Settlement in Indiana, and Oxford, Ohio, the nine attendees shared approaches to community archiving and learned about the DigitalArc Community Archiving Playbook to weigh which parts of this adapted history harvest format best fit community interests. For the first time, the DigitalArc project team and the project partners met one another in-person during this event!

On Day 1, partners introduced themselves, the community they represented, their community archiving project, and related goals and projected challenges. DigitalArc members spoke about the historical, social justice-driven, and logistical rationale behind DigitalArc philosophy, platform and toolkit. The next day, partners and team members put the Playbook into practice by walking through each station of a hypothetical history harvest event–they checked in “contributors,” tagged objects, collected metadata, and tried out smartphone photography using affordable light boxes.

Learn more about the playbook and the process by visiting the [DigitalArc Toolkit documentation](https://digitalarcplatform.github.io/documentation/), which is a work-in-progress.

<img src="../assets/highlights/slide1.JPG" alt="Michelle Dalmau leads introductions to DigitalArc In-Person Workshop." width="300" height="400" style="border: 1px solid \#000; float: left; padding: .5em;"> 
<img src="../assets/highlights/slide2.JPG" alt="McKenya Dilworth introduces herself to Oxford, OH and Roberts Settlement Partners." width="300" height="400" style="border: 1px solid \#000; float: left; padding: .5em;"> 
<img src="../assets/highlights/slide3.JPG" alt="Gary Partners Maya Etienne, Joslyn Washington Kelly, and McKenya Dilworth walk through the check-in station to practice leading a History Harvest." width="300" height="400" style="border: 1px solid \#000; float: left; padding: .5em;"> 
<img src="../assets/highlights/slide4.JPG" alt="Dr. Jazma Sutton speaks about her research on descendant archival practices." width="300" height="400" style="border: 1px solid \#000; float: left; padding: .5em;">
<img src="../assets/highlights/slide5.JPG" alt="Workshop attendees and organizers." width="300" height="400" style="border: 1px solid \#000; float: left; padding: .5em;"> 
<img src="../assets/highlights/slide6.JPG" alt="Bryan Glover, Vice President of Roberts Settlement, announces upcoming Homecoming." width="300" height="400" style="border: 1px solid \#000; float: left; padding: .5em;"> 
<img src="../assets/highlights/slide7.JPG" alt="Dr. Kalani Craig addresses the importance of metadata in organizing object photographs." width="300" height="400" style="border: 1px solid \#000; float: left; padding: .5em;"> 

