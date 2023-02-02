---
layout: default
title: Tutorials 
permalink: /tutorials/
---

## Coming Soon

* git and GitHub
* OpenRefine
* Text Processing with R
* Topic Modeling with R
* Static Site Publishing
  * Publishing with GitHub pages
  * Understanding Markdown
  * Understanding Jekyll
  * Using Liquid and YAML 
* WordPress
  * Up and Running with WordPress
  * Customizing the 2023 Theme
* Omeka S
  * Why Omeka S?
  * Adding objects and customizing templates
  * Creating an exhibit with Omeka S sites
* Scalar
  * What is Scalar?
  * Creating Scalar Books

{% for page in site.tutorials %}
  <img class="preview" src="{{ site.baseurl }}/assets/images/{{ page.image }}">
  <section class="description"><h2><a href="{{ site.baseurl }}{{ page.permalink }}">{{ page.title }}</a></h2>
  <p>{{ page.description }}</p>
  </section>
{% endfor %}