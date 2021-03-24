---
layout: template_indexFile
title: Sunil's Profile
author: Sunil Jadhav
---

# {{page.title}}

Hello All,

My Name is Sunil Jadhav. Get to know more about me.

-  [My likes](topics/Hobbies)
-  [Employment History](topics/history)


Following is my employment history

{% for item in site.data.source %}
 - {{ item.material }}: {{ item.source }}

{% endfor %}


I also do some `liquid` code:

``liquid
{% if user %}
  Hello {{ user.name }}!
{% endif %}
``

My email address is {{site.email}}
