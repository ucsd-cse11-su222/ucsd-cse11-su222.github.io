---
layout: with-sidebar
index: 22
name: Generics
released-on: "2022-08-25"
videos:
    - title: "Two Similar Loops"
      url: https://drive.google.com/file/d/1RKq-CprnjmDDGPqius4tOZL6F4Xrvf-Q
    - title: "Generics"
      url: https://drive.google.com/file/d/1Gvhq3JsXXSxfjEVwjzHl_5jgQeuX5ixO
    - title: "Implementing with Generics"
      url: https://drive.google.com/file/d/1bXk5leiFDmvc8b5fnqaox0Xd1AdwXS1_
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

Stepik 12.1: [https://stepik.org/lesson/614368/step/1?unit=609810](https://stepik.org/lesson/614368/step/1?unit=609810)

Each week, we will have a student experience survey to tell us how things are going. This survey will be 
graded as engagement, i.e. with the Stepik exercises.

Please fill out the following survey by Monday, August 22nd at 10pm for Week 4.
[CSE 11 Student Experience Survey](https://forms.gle/K3jeXkUrLYZoDd3q7){:target="_blank"} 

Videos:

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}
<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

## Handout

<iframe src="https://drive.google.com/file/d/1w2Q8av80clKFS03ypRvxCKwqMSTQY01n/preview" width="640" height="480" allow="autoplay"></iframe>

## Recording

[Lecture 22 - Recording](https://podcast.ucsd.edu/watch/wi22/cse11_a00/22){:target="_blank"}

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}