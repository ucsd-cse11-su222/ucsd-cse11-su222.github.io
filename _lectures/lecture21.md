---
layout: with-sidebar
index: 21
name: Debugging
released-on: "2022-08-24"
videos:
worksheets:
  - title: Lecture - Part 1 (from Wednesday)
    url: https://drive.google.com/file/d/1JgZJBMgUmfW8QQEnWO76Wl6J7s_KYqVj
  - title: Lecture - Part 2 (from Thursday)
    url: https://drive.google.com/file/d/1LKNvflueOfuf17hynZfCyatYUN-BaaAH
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

No new videos – go back and study lecture 20's example, because we will use it
heavily for a debugging example in class.

## Handout

Code from class:

<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fucsd-cse11-f21%2Fucsd-cse11-f21.github.io%2Fblob%2Fmain%2F_lectures%2Flecture21%2FRegionMain.java&style=github&showBorder=on&showLineNumbers=on&showFileMeta=on&showCopy=on"></script>

Full example with file contents: [https://github.com/ucsd-cse11-sp22/ucsd-cse11-sp22.github.io/tree/main/_lectures/lecture21](https://github.com/ucsd-cse11-sp22/ucsd-cse11-sp22.github.io/tree/main/_lectures/lecture21)

<iframe src="https://drive.google.com/file/d/1vxoukWPH4FTkbn2jOWl_FoDcwSDPRCr5/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}