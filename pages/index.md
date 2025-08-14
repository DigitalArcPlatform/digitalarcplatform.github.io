---
layout: blank
title: DigitalArc Toolkit for community storytelling and archives
permalink: /
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

<div class="grid-x grid-padding-x  align-top">
<div class="cell medium-6 align-left" markdown=1>

## Digital Archiving & Storytelling for Historically Excluded Communities

DigitalArc provides relatively easy and inexpensive approaches to organizing, collecting and publishing your histories.  More than platforms for publishing your stories and processes for capturing your stories, DigitalArc **focuses on the people who contribute their stories**.  [Visit the About DigitalArc page to learn more](/about/).  

Whether your community leads the entire digital archiving initiative, from start to finish, or you partner with local organizations, we provide guidance from planning to publishing your digital archive. Our goal is to provide step-by-step instructions that can be easily tailored for your community needs so you can lead and manage this whole process. The stories you are sharing are yours. You should have options for managing how your stories are shared.

### Community & Campus Partners
_This list is slowly growing as we develop relationship with community and campus partners._

* [La Casa Latino Cultural Center](https://lacasa.indiana.edu/) (IU Bloomington, Campus)

</div>
<div class="cell medium-6 align-top" markdown=1>

## DigitalArc Highlights
<div class="orbit" role="region" aria-label="In-Person Workshop Highlights" data-orbit>
    <div class="orbit-wrapper">
      <div class="orbit-controls">
        <button class="orbit-previous"><span class="show-for-sr">Previous Slide</span>&#9664;&#xFE0E;</button>
        <button class="orbit-next"><span class="show-for-sr">Next Slide</span>&#9654;&#xFE0E;</button>
      </div>
  <ul class="orbit-container">
    <li class="orbit-slide is-active">
      <figure class="orbit-figure">
        <img class="orbit-image" src="assets/highlights/slide1.JPG" alt="Group">
        <figcaption class="orbit-caption">Michelle Dalmau leads introductions.</figcaption>
      </figure>
    </li>
    <li class="orbit-slide is-active">
      <figure class="orbit-figure">
        <img class="orbit-image" src="assets/highlights/slide2.JPG" alt="McKenya Dilworth">
        <figcaption class="orbit-caption">McKenya Dilworth introduces herself to Oxford, OH and Roberts Settlement Partners.</figcaption>
      </figure>
    </li>
    <li class="orbit-slide is-active">
      <figure class="orbit-figure">
        <img class="orbit-image" src="assets/highlights/slide3.JPG" alt="Gary partners">
        <figcaption class="orbit-caption">Gary Partners Maya Etienne, Joslyn Washington Kelly, and McKenya Dilworth walk through the check-in station to practice leading a History Harvest.</figcaption>
      </figure>
    </li>
    <li class="orbit-slide is-active">
      <figure class="orbit-figure">
        <img class="orbit-image" src="assets/highlights/slide4.JPG" alt="Sutton">
        <figcaption class="orbit-caption">Dr. Jazma Sutton speaks about her research on descendant archival practices.</figcaption>
      </figure>
    </li>
    <li class="orbit-slide is-active">
      <figure class="orbit-figure">
        <img class="orbit-image" src="assets/highlights/slide5.JPG" alt="Group2">
        <figcaption class="orbit-caption">Workshop attendees and organizers.</figcaption>
      </figure>
    </li>
    <li class="orbit-slide is-active">
      <figure class="orbit-figure">
        <img class="orbit-image" src="assets/highlights/slide6.JPG" alt="Glover">
        <figcaption class="orbit-caption">Bryan Glover, Vice President of Roberts Settlement, annouces upcoming Homecoming.</figcaption>
      </figure>
    </li>
    <li class="orbit-slide is-active">
      <figure class="orbit-figure">
        <img class="orbit-image" src="assets/highlights/slide7.JPG" alt="Photography">
        <figcaption class="orbit-caption">Dr. Kalani Craig addresses the importance of metadata in organizing object photographs.</figcaption>
      </figure>
    </li>
  </ul>
  </div>
  <nav class="orbit-bullets">
    <button class="is-active" data-slide="0">
      <span class="show-for-sr">First slide details.</span>
      <span class="show-for-sr" data-slide-active-label>Current Slide</span>
    </button>
    <button data-slide="1"><span class="show-for-sr">Second slide details.</span></button>
    <button data-slide="2"><span class="show-for-sr">Third slide details.</span></button>
    <button data-slide="3"><span class="show-for-sr">Fourth slide details.</span></button>
    <button data-slide="4"><span class="show-for-sr">Fifth slide details.</span></button>
    <button data-slide="5"><span class="show-for-sr">Sixth slide details.</span></button>
    <button data-slide="6"><span class="show-for-sr">Seventh slide details.</span></button>
  </nav>
</div>

## About the DigitalArc team

Our team got its start at the [Institute for Digital Arts and Humanities](https://idah.indiana.edu/) at Indiana University Bloomington and is now funded by the [Digital Justice Development Grant program at the American Council on Learned Societies](https://www.acls.org/recent-fellows/?program_id=40090&_project_year=2024).

### Principal Project Team:
- Michelle Dalmau
- Vanessa Elias
- Kalani Craig
- Jazma Sutton

## Values
The DigitalArc team to uphold [these values] in fulfilling the social justice goal of our work. (https://claudiatests.github.io/values/)

### About this Jekyll Theme
While the DigitalArc design theme doesn't need to be customized, you can if you have the expertise.
<p><a href="http://digitalarcplatform.kalanicraig.com" target="_blank" class=button>Find out more</a></p>

</div>
</div>
</div>

<div class="darkbg" style="background-color: #FCF0EE; margin-bottom: -1rem; padding-bottom: 1rem;">
<div class="grid-container" markdown=1>

### How it started

In 2017, the [IDAH@IU team](https://idah.indiana.edu) started getting requests to support archiving projects. This repository is the result of a long history of partnerships both in and outside of IDAH, which was sunsetted in 2024. The work here represents partnerships with [Jazma Sutton](https://miamioh.edu/profiles/cas/jazma-sutton.html), [ImaginX en Movimiento (IXeM)](https://www.instagram.com/ixemcollective/?hl=en) co-founded by Marisa Hicks-Alcaraz; [La Casa](https://lacasa.indiana.edu/), the [Center for Research on Race, Ethnicity and Society](https://crres.indiana.edu), and the [Asian Culture Center](https://asianresource.indiana.edu) at Indiana University Bloomington; and the [Remembering Freedom](https://longtownhistory.github.io) descendant community in Greenville and Longtown, Ohio, which hosts the community-archive project that inspired the initial development of this theme's predecessor, the Community-Archive template.

</div>
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
