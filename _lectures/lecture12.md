---
layout: with-sidebar
index: 12
name: Arrays
released-on: "2022-08-11"
videos:
  - title: Arrays
    url: https://drive.google.com/file/d/1TglDg1vHTC1ibjO4WJR8SJJSfvpMp9fC
  - title: Arrays, Indexing
    url: https://drive.google.com/file/d/1WkQ5PoQxwNFVio_tp9RD7y-h188zGKoF
  - title: Arrays, Methods
    url: https://drive.google.com/file/d/1PzrWhXBRerq0oTeVhlnuNc0vNJ6xQW9k
  - title: Arrays, Memory
    url: https://drive.google.com/file/d/14QiAfHlccvCZTVsU3MuBvLoFkSU-_UAo
worksheets:
  - title: Lecture - Part 1 (from Thursday)
    url: https://drive.google.com/file/d/1807QbHohLtiNSiqoFaMJGi4oRhq8vueb
  - title: Lecture - Part 2 (from Monday)
    url: https://drive.google.com/file/d/18XlKbV-KwjzPCsD3zeXNOljOBGTXrRuY
---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik reading:
- [Stepik 9](https://stepik.org/lesson/579631/step/1?unit=574281)

Each week, we will have a student experience survey to tell us how things are going. This survey will be 
graded as engagement, i.e. with the Stepik exercises.

Please fill out the following survey by Monday, August 15th at 10pm for Week 2.
[CSE 11 Student Experience Survey](https://forms.gle/JeBtAES9AswppffU9){:target="_blank"} 

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1tZWPqxH7Ct7Nb9jyL-sV2ID5JzP30K9L/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}