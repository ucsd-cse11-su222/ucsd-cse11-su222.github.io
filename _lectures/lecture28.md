---
layout: with-sidebar
index: 28
name: A Big Example
released-on: "2022-09-01"
videos:
    - title: "Choosing a Representation 1"
      url: https://drive.google.com/file/d/1HBrEnxvSnJKey4CVp1V68Bp2HjGUNZnE
    - title: "Choosing a Representation 2"
      url: https://drive.google.com/file/d/1-bU-czn_CPTMEkT19qkdpnlYuB7aesS5
    - title: "Some Examples"
      url: https://drive.google.com/file/d/1NhojJMcGjDd1ajkrE8dmfRoX90AUG0W9
    - title: "More Examples"
      url: https://drive.google.com/file/d/1PWAkAUzP4s9H_536UX9XpMMIxYzoCaDa
    - title: "A Filesystem Method"
      url: https://drive.google.com/file/d/1vk4MnC3RRwHzlipea1ZUYVtXAc0l5Voo
    - title: "Trace 1"
      url: https://drive.google.com/file/d/1zuDP7Ji4Aiu0ULqY_Y0ezqqGgZN0dsD_
    - title: "Trace 2"
      url: https://drive.google.com/file/d/1fIpX2oxDNnKQx2yhilkzDXvklS-S96k3
worksheets:
  - title: Lecture (from Thursday)
    url: https://drive.google.com/file/d/1OLK-SuNj8WHZfPiFjmzJ3jHVVLmlcnsg
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

This worked example will serve as a review of most of the topics we've seen in
class so far, including interfaces, `Collections` classes, loops, recursion,
testing, and memory diagrams.

Each week, we will have a student experience survey to tell us how things are going. This survey will be 
graded as engagement, i.e. with the Stepik exercises.

Please fill out the following survey by Saturday, September 3rd at 10pm for Week 5.
[CSE 11 Student Experience Survey](https://forms.gle/BQoh4ijXm6DnpXd49){:target="_blank"} 

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

Code from videos:

<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fucsd-cse11-s20%2F19-AllTogether%2Fblob%2Fmaster%2FFilesystemExamples.java&style=github&showBorder=on&showLineNumbers=on&showFileMeta=on&showCopy=on"></script>

Handout:

Part1:
<iframe src="https://drive.google.com/file/d/1wQmk5a1U8bDqJ8jkWIR-QY2D0vvDnPqR/preview" width="640" height="480" allow="autoplay"></iframe>

Part2:
<iframe src="https://drive.google.com/file/d/1wBkmYhT0M9pDrUAXX-cGrBp1mdnxJIzU/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}