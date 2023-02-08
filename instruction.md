---
layout: default
title: Instruction Offerings 
permalink: /instruction/
---

# Requesting Instruction with the Office of Digital Research and Scholarship

If you would like to request instruction on a specific topic in your class, email [lib-digischol@fsu.edu](mailto:lib-digischol@fsu.edu) with the following information:

* Your name
* Your email
* Course number (if applicable)
* Requested topic
* At least two preferred dates

Instruction requests should be submitted at least one month prior to the date of instruction in cases where no lesson plan exists, and two weeks prior to the requested instruction when there is an existing lesson plan (see below).

## Lesson Plans

The following are lesson plans that we have used in lessons before. We are happy to adapt these lesson plans to fit with your course's learning objectives, or to create a brand new lesson plan for your instructional needs.

<hr>
<br>
*Lesson plans coming soon!*

{% for page in site.lesson-plans %}
  <section class="description"><h2><a href="{{ site.baseurl }}{{ page.permalink }}">{{ page.title }}</a></h2>
  <p>{{ page.description }}</p>
  </section>
{% endfor %}