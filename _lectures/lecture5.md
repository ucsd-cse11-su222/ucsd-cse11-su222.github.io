---
layout: with-sidebar
index: 5
name: Booleans and If
released-on: "2022-08-04"
videos:
  - title: More on String Methods
    url: https://drive.google.com/file/d/1rYWNaFbrW5W-ITueTlzaPzW8k-CkTuWX
  - title: A Design Recipe Example
    url: https://drive.google.com/file/d/1WgbC_LPGfsRbj-ybdoYYg8SHl8W5Ryvd
  - title: Booleans
    url: https://drive.google.com/file/d/1LHxrTqZfszFmsF6xDTCD8SbAO2iemxY5
  - title: If (watch from 26:00 to 37:30)
    url: https://drive.google.com/file/d/1Akg2I_XKXuyOImRrVD6phPk-x-YBfcL8

worksheets:
  - title: Lecture
    url: https://drive.google.com/file/d/14kC1MMxZKhW0dxiF-98DenK_LO7PcT7U
---

## Problem Session 5 – Booleans and If

_{{ page.released-on }}_

## Pre-class Tasks

Readings to be completed **before** problem session.

- Stepik Chapter 4 [https://stepik.org/lesson/568133/step/1?unit=562510](https://stepik.org/lesson/568133/step/1?unit=562510)


Each week, we will have a student experience survey to tell us how things are going. This survey will be 
graded as engagement, i.e. with the Stepik exercises.

Please fill out the following survey by Monday, August 8th at 10pm for Week 1.
[CSE 11 Student Experience Survey](https://forms.gle/REPLN8uneDgucLE29){:target="_blank"} 

Videos (to watch **before** problem session):

{% for video in page.videos %}
[{{ video.title }}]({{ video.url }}){:target="_blank"}

<iframe src="{{ video.url }}/preview" width="640" height="480" allow="autoplay"></iframe>
{% endfor %}

Handout

<iframe src="https://drive.google.com/file/d/1hV3M2zQloU020laQb6xJY23SQR6URNlJ/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}