---
layout: with-sidebar
index: 18
name: More Loops Practice
released-on: "2022-08-22"
videos:
  - title: More Array Construction
    url: https://drive.google.com/file/d/11YimqsLqytwGygYh6YVmCSI7lo1iYHo_
  - title: null and Array Construction
    url: https://drive.google.com/file/d/1rptvmC3Kz2N5SLO8pMgCIYHfJwDRWf6O
  - title: Arrays, loops, and memory
    url: https://drive.google.com/file/d/1cb9Vc0xpG1PfjrDa11mGTVobC37YvuLJ
  - title: Range
    url: https://drive.google.com/file/d/1C_rnkqz2YHE6BsBcd2NUnWIYC1Fvts5Z
worksheets:
  - title: Lecture - Part 1 (from Monday)
    url: https://drive.google.com/file/d/1JSYNi_UM7gu1a2A3YQZpMRHXGs84LRHf
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik 11.1 [https://stepik.org/lesson/609849/step/1?unit=605131](https://stepik.org/lesson/609849/step/1?unit=605131)

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/18lEuJJk5rSbDCb_t79BaKsWmQ6gxlZPm/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}