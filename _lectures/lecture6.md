---
layout: with-sidebar
index: 6
name: Classes and Objects
released-on: "2022-08-04"
videos:
  - title: Creating Objects and Classes (through 22:00)
    url: https://drive.google.com/file/d/1Kn6rVGCTQf2OkZ5-maVpA-MXFd0LHxZ2
  - title: Point add() Method 1
    url: https://drive.google.com/file/d/1PV8W3eaBZbOab42mzne7Wts_kwEuz6ZU
  - title: Point add() Method 2
    url: https://drive.google.com/file/d/1yZX5wo3b-A5AxOwSIccQqsUR3VK0j26i
  - title: Math methods
    url: https://drive.google.com/file/d/1-5P1JWdzCCfGpwh1aW7jLYApipzJgmKc

worksheets:

---

## Problem Session 6 – Classes and Constructors

_{{ page.released-on }}_

## Pre-class Tasks

Readings to be completed **before** problem session.

- Stepik Chapter 5 [https://stepik.org/lesson/573908/step/1?unit=568498](https://stepik.org/lesson/573908/step/1?unit=568498)

Each week, we will have a student experience survey to tell us how things are going. This survey will be 
graded as engagement, i.e. with the Stepik exercises.

Please fill out the following survey by Monday, August 8th at 10pm.
[CSE 11 Student Experience Survey](https://forms.gle/REPLN8uneDgucLE29){:target="_blank"} 

Videos (to watch **before** problem session):

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

Handout:

<iframe src="https://drive.google.com/file/d/1hY2zSmahlGeYhdXlmlN2nhDez5rwYsYx/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}