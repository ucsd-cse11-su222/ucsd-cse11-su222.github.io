---
layout: with-sidebar
index: 9
name: Nested Data
released-on: "2022-08-09"
worksheets:
  - title: Lecture - Part 1 (from Tuesday)
    url: https://drive.google.com/file/d/17kpkdVSvDuP_EUy6_vhbqYJDJN1BtMV-
  - title: Lecture - Part 2 (from Wednesday)
    url: https://drive.google.com/file/d/17rLEo3Hsas5zee8B1UJXoJGUN1xg1ZM0
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik reading (to complete before class on April 15):
- [Stepik 7](https://stepik.org/lesson/584041/step/10?unit=578810)

No pre-watch videos for April 15 (take the time to review some others!).

If you want to watch ahead, the next topic will be from here, but we won't
discuss interfaces until the next class:

<iframe src="https://drive.google.com/file/d/1FsiNPr6N5yiFymHtwCdDHYHt03mWNw_Q/preview" width="640" height="480" allow="autoplay"></iframe>

Handout:

<iframe src="https://drive.google.com/file/d/1n7L9htMXqHneP0HFahuxucobzNIgR-kd/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}