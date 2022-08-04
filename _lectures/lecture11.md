---
layout: with-sidebar
index: 11
name: Interfaces and Recursion
released-on: "2022-08-11"
videos:
  - title: Interfaces (watch 30:00 to the end)
    url: https://drive.google.com/file/d/1FsiNPr6N5yiFymHtwCdDHYHt03mWNw_Q
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik reading:
- [Stepik 8.4-8.5](https://stepik.org/lesson/574433/step/1?unit=569019)

Each week, we will have a student experience survey to tell us how things are going. This survey will be 
graded as engagement, i.e. with the Stepik exercises.

Please fill out the following survey by Monday, August 15th at 10pm for Week 2.
[CSE 11 Student Experience Survey](https://forms.gle/REPLN8uneDgucLE29){:target="_blank"} 

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

(Yes, same as last lecture 🙂)

<iframe src="https://drive.google.com/file/d/1nUCwjiK6tzwEyRciOayfLks_7hh-Hfxs/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}
