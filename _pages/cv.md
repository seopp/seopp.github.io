---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* **Ph.D.** in [Major], [University], [Year]
* **M.S.** in [Major], [University], [Year]
* **B.S.** in [Major], [University], [Year]

## Work Experience
* **Researcher**, AITRICS, [Start Date] - Present

## Skills
* [Skill 1]
* [Skill 2]

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
