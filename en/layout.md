---
layout: default
lang: en
---

# Welcome to My Website

## Introduction

{% if page.lang == 'en' %}
  This is the introduction to my website.
{% elsif page.lang == 'fr' %}
  Ceci est 1'introduction a mon site web.
{% endif %}

## Features

### English Version

{% if page.lang == 'en' %}
  - Feature 1: This is the first feature.
  - Feature 2: This is the second feature.
  - Feature 3: This is the third feature.
{% elsif page.lang == 'fr' %}
  - Fonctionnalite 1 : Ceci est la premiere fonctionnalite.
  - Fonctionnalite 2 : Cesi est la deuxieme fonctionnaite.
  - Fonctionnalite 3 : Ceci est la troisieme fonctionnalite.
{% endif %}
 ## Contact Us

 For any inquiries, please contact us at[arifmas90408@gmail.com](mailto:arifmas90408@gmail.com)
