---
layout: minimal
title: Environmental Design Capstone
nav_exclude: True
permalink: /:path/
seo:
  type: Course
  name: Just the Class
search_enabled: true
---

{% include course_header.html %}


Urban and rural communities alike face increasing challenges related to mobility, safety, and equitable access to opportunity. Aging transportation infrastructure, auto-oriented development patterns, and shifting demographic and economic conditions have intensified the need for more integrated and context-sensitive approaches to corridor design. Multimodal corridors and complete streets have emerged as critical frameworks for rethinking how transportation systems can support community health, environmental sustainability, and long-term economic vitality. As these challenges grow more complex, designers are increasingly called upon to work collaboratively, engage communities directly, and translate interdisciplinary knowledge into actionable, real-world solutions.

This course focuses on the transformation of vehicular-dominated community streets into multimodal corridors and complete streets as critical infrastructure for mobility, public health, and economic vitality. Framed as a studio-based learning experience, the course integrates conceptual foundations, applied design methods, and real-world engagement to bridge planning theory and design practice. 

A central component of the course is a two-day intensive design charrette, a professional practice model commonly used in urban design and planning. Students will work collaboratively in teams during the charrette to synthesize research, stakeholder input, and design strategies into actionable proposals. The charrette will be co-led by the course instructor and nationally renowned architect and urban designer [Victor Dover](https://www.doverkohl.com/vdover), providing students with direct exposure to professional design leadership and interdisciplinary collaboration.

Offered in partnership with the [Institute for Quality Communities (IQC)](https://iqc.ou.edu), the course centers on a real, community-based project in the City of Durant, Oklahoma. By the end of the semester, students will synthesize research, community engagement, and design thinking to produce implementable design recommendations that support mobility, safety, equity, and community vitality.

--- 

{% assign latest = site.announcements | sort: "date" | last %}

<div class="announcement">
  <div class="announcement-left">
    <p>{{ latest.date | date: "%B %d, %Y" }}</p>
    <p class="all-announcements">
      <a href="{{site.baseurl}}/announcements/">All announcements →</a>
    </p>
  </div>
  <div class="announcement-right announcement-body">
    <div style="text-transform: uppercase; font-weight: 600;"> {{ latest.title }} </div>
    {{ latest.content | markdownify }}
  </div>
</div>

--- 

## Schedules
<a href="#recent"><i class="fa-solid fa-square-arrow-up-right" style="color: #000000;"></i> **Go to the recent section**.</a> This schedule is subject to change, and please check back regularly for updates. All readings and materials can be directly accessed via the links below, although some may require a OU NetID login. Please give us any anonymous suggestions about the lectures, discussion, design progress, or anything using the **[anonymous suggestions box](https://freesuggestionbox.com/pub/uzxbkym)**.

{% for module in site.modules %}
{{ module }}
{% endfor %}

{% include course_footer.html %}

