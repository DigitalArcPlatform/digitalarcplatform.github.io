---
layout: blank
title: DigitalArc Values
permalink: /values/
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
# DigitalArc's Values

## 1. Community Ownership and Control

The project centers community autonomy over stories, artifacts, and archives. It ensures that communities, not institutions, decide what is shared, how, and with whom. Participants can set access levels, retain ownership, and use platforms that best fit their needs. 

## 2. Accessible, Scaffolded Support and Training

DigitalArc is committed to providing low-barrier, adaptable guidance and technical support. This includes step-by-step toolkits, hands-on workshops, and remote assistance tailored to varying levels of technical experience within communities. 

## 3. Equity in the Historical Record

The project actively works to fill gaps in mainstream archives by enabling marginalized communities to document and share their histories on their own terms. It challenges traditional archival practices that often exclude or misrepresent these voices. 

## 4. Sustainable, Community-Led Capacity Building

Through sustainable shared authority that acknowledges the labor involved in community archive leadership, with a focus on supporting long-term funding for community archive development, training, and equipment, the project invests in building long-term, community-based archival capacity. It recognizes community leaders and encourages them to spearhead future events, sustaining descendant archival practices beyond the life of the grant. 

## 5. Transparency Around Digital Ethics and Infrastructure

Acknowledges the risks of mainstream platforms (e.g., social media data ownership, sustainability issues with WordPress) and offers alternatives that prioritize data privacy, ethical stewardship, and long-term accessibility.  

## 6. Investment in Intergenerational and Local Knowledge

By encouraging community members to lead and by supporting events in familiar, everyday spaces (like homes, churches, festivals), the project reflects a commitment to valuing local knowledge, intergenerational storytelling, and grassroots memory work. 
