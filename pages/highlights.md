--- 
title: In-Person Workshop
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
 
# DigitalArc project team and partners practice “history harvest” during spring in-person workshop 

Midwest community leaders worked toward their digital archiving goals at the DigitalArc In-Person Workshop from May 31-June 1, 2025, in Bloomington, Indiana. Representing Gary, Roberts Settlement, and Oxford, Ohio, the nine attendees learned about the DigitalArc Community Archiving Playbook to weigh which parts of the history harvest format best fit their interests. For the first time, the DigitalArc project team and the project partners met one another in person during this event. 

On Day 1, partners introduced themselves, the community they represented, their community archiving project, and related goals and projected challenges. DigitalArc members spoke about the historical, social justice driven, and logistical rationale behind the proposed community archiving organization. The next day, partners and team members put the playbook into practice by walking through each station of a hypothetical history harvest event–they checked in “contributors,” tagged objects, collected metadata, and tried out smartphone photography using affordable light boxes.  

Partners will revisit the lessons from this in-person workshop during the digital workshop series on September 27 and October 25, 2025.  

 
