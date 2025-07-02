---
layout: blank
title: About DigitalArc
permalink: /about/
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

# About DigitalArc
{: .subheadline }

Funded by the [Digital Justice Development Grant program at the American Council on Learned Societies](https://www.acls.org/recent-fellows/?program_id=40090&_project_year=2024), our goal is to provide support for local communities to document and share their own stories, on your terms, through the creation and ongoing management of digital archives. We all have an opportunity to contribute to our local and collective stories, enriching our shared historical record with voices that might otherwise not be heard.

DigitalArc provides adaptable guidelines for documenting histories, from the planning process to collecting the stories, from preparing the stories for personal and community records to publishing the stories.

## An Overview
Read all the fun details about the DigitalArc project below or jump to sections:
- [Who?](#who)
- [Why?](#why)
- [What?](#what)
- [When?](#when)
- [Where?](#where)

### Who?
<a id="who"></a>
You! This project is driven by you and your communities. Whether your community leads the entire digital archiving initiative, from start to finish, or you partner with local organizations, we provide guidance from planning to publishing your digital archive. Our goal is to provide step-by-step instructions that can be easily tailored for your community needs so you can lead and manage this whole process. _The stories you are sharing are yours. You should have options for managing how your stories are shared._  

DigitalArc provides options! Your stories and artifacts could be shared widely via the Internet through the DigitalArc platform, platforms already supported by your community, or on social media. Your stories and artifacts can also be captured for personal or familial archives that are yours and yours alone. In every case, your artifacts and stories will be fully controlled by you, your community partners and/or individual contributors. You can designate levels of access from no public access at all to fully open-access.  

[Jump down](#about_team) to learn more about the DigialArc project team.

### Why?
<a id="why"></a>
The historical record is full of gaps. When communities whose histories have been excluded from institutional archives take on the task of telling their own stories, they often do so by using low-barrier platforms, including social media platforms like Facebook. However, easy posting and built-in audiences on social media platforms come with questionable data privacy and data ownership practices. Popular web-hosted platforms like WordPress often come with significant maintenance challenges. Partnerships with academic or cultural heritage institutions result in more sustainable archives but often at the cost of community ownership. This balance is complicated by varied community technical expertise, and a confusing landscape of digital archiving resources.

The DigitalArc project seeks to bridge these gaps in archiving approaches with a scaffolded approach to community-owned archives that honors existing community skills and reflects community needs and preferences. Our approach provides easier and more affordable ways for communities to host and manage their own digital archives. By learning together, we create a shared knowledge base that communities can leverage to support their own community-led and community-centered digital archives. The DigitalArc toolkit helps shift the conversation with community partners about digital community archiving and storytelling to one in which community partners can choose how much or how little institutional support they want as they pursue a community archive.

### What?
<a id="what"></a>
The DigitalArc project seeks to refine community-archiving approaches with constant input from community members. We have budgeted funding to work with a community partner in Indiana and a community partner in Ohio. Our hope is that the community leaders and volunteers can work through the DigitalArc toolkit to lead their own community-archiving project. In turn, the partners will receive in-person training and ongoing remote support from the DigitalArc project team. As we work through the process, we will rely on community members’ constructive criticism to help us improve the toolkit we are collaboratively creating.   

For this grant, we have structured ways we can organize our collective archival work. **The most important of which is to recognize a couple of community leaders who are excited to uphold descendent archival approaches within their communities** and carry the torch by spearheading additional community archiving events. The DigitalArc project team is committed to working with community leaders to this end.

The grant provides modest but helpful funding for this work:

- Honoraria for up to 4 community leaders, 2 in Indiana and 2 in Ohio, in recognition of time and labor investments for organizing a community archiving event and preparing community contributions for the digital archive
- Hospitality contributions for a community archiving event in Indiana and in Ohio to offset food costs, facilities rental, etc.  
- Travel costs are 100% covered for in-person workshop for community leaders and volunteers (6-8 from each state)
- Start-up equipment for this work including lightboxes for photography, audio recorders for oral histories, etc.  
- Software and licensing fees required for hosting the digital archive for two years

The process can be broken down into the following parts:  

- **Before the Event**: During this time, and with respect to this project’s timeline, which is now through late Spring 2025, we are focusing on relationship-building with and across community members. For this project, we plan to partner with Black communities in Indiana and Ohio. This is the time to understand community needs – what are the stories that need to be recorded? Will the community focus on a particular historical event or theme or simply create a living museum and digital archive, highlighting artifacts that contribute to a personal or communal story. Rallying community volunteers is essential during this time as is hands-on workshop training.  
- **During the Event**: This is the big day ... the day of the community archiving event. This part of the process that primarily focuses on logistics ... so many logistics, and we are here to help with that!  
- **After the Event**: Now you have digital photographs of community archives and oral history interviews! In this stage of the process, we will help you organize your digital files, maybe do some “cleaning” (cropping, editing, etc.) and get the files prepped for online publishing with the DigitalArc open-source platform!  
- **Platform-Installation**: This part of the process is the most technical, but we promise we will try to make it as easy as possible. It wouldn't hurt to identify a community member (or two) who is interested in or curious about technology, and not afraid to break things!  

### When?
<a id="when"></a>
We have several key dates for community partners to note:

- **May 29 – June 1, 2025**: Multi-day, hands-on workshop on the process  
- **June/July/August 2025**: Community-led event for collecting stories
- **March/April 2026**: Virtual workshop focusing on next steps  
- **April/May 2026**: Launch of your digital community archive

These dates are fixed to a grant timeline though we may need to shift here and there by a week or two.  **_The May 29 – June 1, 2025 workshop dates are set_**.  
### Where?
<a id="where"></a>
The community archiving work will happen primarily **_in your communities_** – at a church, local library, school, home of a community member, a community-run festival or celebration. You will have remote support from the DigitalArc project team.  

## About the Digital Arc Project Team
<a id="about_team"></a>

The DigitalArc project team is made up of folks affiliated with Indiana University Bloomington and Miami University of Ohio. We also rely on the expertise and generous support of Advisory Team members. Our project is not complete without a shout-out to our community partners in Indiana and Ohio!  

### Community Partners
<a id="comm_partners"></a>
- Samuel Barnett also known as Sam Love is a local activist, historian, and Indiana University Northwest alumni. Sam is co-leading the Gary, Indiana partner collaboration.  
- Karen	Byrd-Gibson 
- Margaret Catania, Co-Executive Director of the Calumet Collaborative
- McKenya Dilworth
- Maya Etienne, Co-Executive Director of the Calumet Collaborative and volunteer Program Director for the Gary Food Council
- Courtney Franklin
- Bryan	Glover, Project Leader of Legacy Walk at Robert Settlement; Retired Corporate Financial Operations leader and small business owner
- Jacqueline Johnson, church member, Bethel AME Church in Oxford, OH
- Joslyn Washington Kelly, Visionary of [This is Gary](https://thisisgaryvw.com) and Owner of [J's Breakfast Club](https://jsbreakfastclubgary.com) in Gary, Indiana. Joslyn is co-leading the Gary, Indiana partner collaboration.  

### Core Project Team
<a id="core_team"></a>
#### Kalani Craig (she/her)
Kalani Craig is Associate Professor of History at Indiana University Bloomington. Kalani’s work is rooted in public history and is a lead collaborator in digital community archiving work. Kalani is the creator of the DigitalArc publishing platform and will lead platform refinement as part of this project. Kalani serves as Co-PI on the project.   

#### Michelle Dalmau (she/her/ella)
Michelle Dalmau is Director of Digital Collections and Digitization Services for the Indiana University Libraries at Indiana University Bloomington. Michelle has a personal connection to community archiving work as a second-generation immigrant and first-generation college student. She is a lead collaborator in digital community archiving work. Michelle is managing the overall grant, including project management, and she’s leading the Indiana community archiving initiative. Michelle serves as PI on the project.    

#### Claudia Gonzalez-Diaz (she/her) 
Claudia Gonzalez-Diaz is a graduate student in the History of Art Department at Tulane University. Claudia is the DigitalArc Project Manager, a position she shares with Alec Smitten, assisting with supporting community partners in digital archiving planning and implementation work including support for post-processing stories captured and publishing the digital archive web site. Prior to assuming the role of DigitalArc Project Manager, Claudia curated and implemented a physical and digital exhibition, _Home Bound_, using an earlier version of the DigitalArc platform. 

#### Vanessa Elias (she/her/ella)
Vanessa Elias is an Information Specialist for the Digital Humanities and User Engagement department at the University of Texas at San Antonio Libraries and Museums.  Vanessa is leading the toolkit documentation, from pre-event to publishing, making sure it makes sense for community members. Vanessa serves as Co-PI on the project. 

#### Nate Howard (he/him) 
Nate Howard is the Digital Methods Specialist for the Institute for Advanced Studies, Indiana University Bloomington and a PhD candidate in History. His research applies digital methods to the study of early medieval pilgrimage accounts of Islamic Palestine. Nate is co-leading publishing platform development. 

#### Lexie Shoulta (she/her) 
Lexis Shoulta is a history major and future librarian with an interest in digital community archives. Prior to joining the DigitalArc team, she interned with the Johnson County Museum of History and The 1947 Partition Archive. 

#### Alec Smitten (he/him)
Alec Smitten is a PhD student in the Classics Department at Indiana University Bloomington. Alec is the DigitalArc Project Manager, a position he shares with Claudia Gonzalez-Diaz, assisting with supporting community partners in digital archiving planning and implementation work including support for post-processing stories captured and publishing the digital archive web site. Prior to assuming the role of DigitalArc Project Manager, Alec contributed to the development of the DigitalArc toolkit documentation.  

#### Jazma Sutton (she/her)
Jazma Sutton is an Assistant Professor of History at Miami University of Ohio. Her research focuses on the histories of slavery and freedom in the U.S. with a particular interest in African American women’s history and the Midwest. Jazma has been leading work in descendant archival practices within African American communities by incorporating Black digital humanities and critical archival studies. She is a lead collaborator in digital community archiving efforts and will be leading the Ohio community archiving initiative. Jazma serves as Co-PI on the project. 

### Project Advisors
<a id="advisors"></a>
#### Jeremy Pekarek (he/him) 
Jeremy Pekarek is an Assistant Librarian/Archivist at Indiana University Northwest. In this role, Jeremy manages the Calumet Regional Archives, which is the largest community-focused archive within Indiana University. In this role, Jeremy is very much engaged with the Gary, Indiana and surrounding communities, and as an advocate for community-led archiving initiatives.

#### Alia Levar Wegner (she/her)  
Alia is the Digital Collections Librarian at Miami University’s Walter Havighurst Special Collections and University Archives where she oversees the digitization of special collections materials, develops digital collections, and collaborates on digital humanities projects. She received her Master's degree in Information from Florida State University and a Master's of Science in Book History and Material Cultures from the University of Edinburgh.  

</div>

<div class="accentbg">
<div class="grid-container">
<div class="grid-x grid-padding-x">
<div class="large-12 cell">
<div class="footer-actions">
<div class="footer-actions-left">
{%if site.twitter.size > 0 %}<a href="https://twitter.com/{{ site.twitter }}" aria-label="Our Twitter"><i class="fa-brands fa-x-twitter" target="_blank"></i></a>{%endif%}
{%if site.instagram.size > 0 %}<a href="https://instagram.com/{{ site.instagram }}" aria-label="Our Instagram"><i class="fa-brands fa-instagram" target="_blank"></i></a>{%endif%}
{%if site.facebook.size > 0 %}<a href="https://facebook.com/{{ site.facebook }}" aria-label="Our Facebook"><i class="fa-brands fa-facebook" target="_blank"></i></a>{%endif%}
</div>
<div class="footer-actions-right">
{%if site.github.size > 0 %}<a href="https://github.com/{{ site.github }}/" target="_blank" aria-label="Our Github"><i class="fa fa-github"></i></a>{%endif%}
{%if site.website.size > 0 %}<a href="{{site.website}}" target="_blank" aria-label="Our Website"><i class="fa-solid fa-globe"></i></a>{%endif%}
{%if site.email.size > 0 %}<a href="mailto:{{ site.email | encode_email }}" aria-label="Email Us"><i class="fa fa-envelope"></i></a>{%endif%}
</div>
</div>

<div class="footer-author-section">

<div class="footer-author">
<img class="avatar" src="{{ site.baseurl }}{{ site.urlimg }}{{ site.sitelogo }}" alt="{{ site.title }}"/>
<div>
<p class="author">{{site.authorname}}</p>
<p class="bio">{{site.description}}</p>
</div>
</div>
</div>
<p class="quiet credits" xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a href="{% if site.copyright_page.size > 0 %}{{site.copyright_page}}{% else %}/copyright/{% endif %}"><i class="far fa-copyright"></i> {{ site.authorname }}, {%if SiteYear != NowYear %}{{SiteYear}} -{%endif%} {{NowYear}}</a>. <a property="dct:title" rel="cc:attributionURL" href="https://digitalarcplatform.kalanicraig.com/">DigitalArc Jekyll Theme</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.kalanicraig.com/">Kalani Craig</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a> Framework: <a href="https://get.foundation/" target="_blank">Foundation 6</a>.</p>
</div>
</div>
</div>
</div>
<script src="{{ site.baseurl }}/assets/js/vendor/jquery.js"></script>
<script src="{{ site.baseurl }}/assets/js/vendor/what-input.js"></script>
<script src="{{ site.baseurl }}/assets/js/vendor/foundation.js"></script>
<script src="{{ site.baseurl }}/assets/js/app.js"></script>
</body>
</html>
