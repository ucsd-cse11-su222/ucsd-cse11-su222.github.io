---
layout: with-sidebar
index: 19
name: Connect 4!
released-on: "2022-08-23"
videos:
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

## Pre-class Tasks

No new content for pre-class; we'll work through the Connect 4 example more
today.

## Handout

<iframe src="https://drive.google.com/file/d/1vyAaXbHgsHagaOgrKHeFKOVarL3FMM-M/preview" width="640" height="480" allow="autoplay"></iframe>

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}