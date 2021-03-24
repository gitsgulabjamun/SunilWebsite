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

{% for item in site.data.workhistory %}
- {{ item.Organization}}: {{ item.Title }}: {{ item.Department }}: {{ item.Location }}
: {{ item.From }}: {{ item.To }}
{% endfor %}



I also do some `liquid` code:

```
{% if user %}
  Hello {{ user.name }}!
{% endif %}
```


My email address is {{site.email}}
