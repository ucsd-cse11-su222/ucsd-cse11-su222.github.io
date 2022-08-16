---
layout: with-sidebar
index: 29
name: AUA and Goodbye!
released-on: "2022-09-01"
worksheets:

---

## Problem Session {{ page.index }} – {{ page.name }}

_{{ page.released-on }}_

Each week, we will have a student experience survey to tell us how things are going. This survey will be 
graded as engagement, i.e. with the Stepik exercises.

Please fill out the following survey by Saturday, September 3rd at 10pm for Week 5.
[CSE 11 Student Experience Survey](https://forms.gle/BQoh4ijXm6DnpXd49){:target="_blank"} 

Please submit your CAPEs for the course at [https://cape.ucsd.edu/](https://cape.ucsd.edu/), including evaluations for your TAs!

The theme of this lecture is “Ask Us (Almost) Anything!” Feel free to ask questions about the course, CSE, our experience, programming, and so on. This can be a mix of review and other topics you find helpful. 

## Completed Worksheets from Lecture

{% for worksheet in page.worksheets %}
<div class="worksheetBox">
{{ worksheet.title }}
<br>
<iframe src="{{ worksheet.url }}/preview" width="256" height="192" allow="autoplay"></iframe>
</div>
{% endfor %}