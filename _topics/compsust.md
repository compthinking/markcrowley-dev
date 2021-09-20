---
layout: page
title: Computational Sustainability
name: Computational Sustainability
permalink: /compsust/
keyword: computational-sustainability
description: Connecting Machine Learning with Global Sustainability challenges.
nav: false
showtitle: true
---

In the field of **Computational Sustainability,** I have worked on learning predictive models of and optimizing policies for domains in invasive species control, forest harvest management and forest fire management. These types of domains offer unique challenges for traditional artificial intelligence and machine learning algorithms for decision making, prediction and anomaly detection.  

See my [blog](http://www.computationallythinking.com) for more writing on this topic.

<div class="publications">
  <h2>Our Papers on {{ page.name }}</h2> 
{% bibliography -q @*[keywords~={{page.keyword}} && self=1] %}
</div>