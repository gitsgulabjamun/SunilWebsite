---
layout: default
title: Sunil's Profile
author: Sunil Jadhav
---

# {{page.title}}

Hello All,

My Name is Sunil Jadhav. Get to know more about me.

-  [My likes](./topics/Hobbies)
-  [Employment History](./topics/history)


Following is my employment history

{% for item in site.data.workhistory %}
- {{ item.Organization}}: {{ item.Title }}: {{ item.Department }}: {{ item.Location }}
: {{ item.From }}: {{ item.To }}
{% endfor %}



I also do some `liquid` code:


```
{% if Profile.PREFERED_LANGUAGE == "Spanish" %}
Hola!
{% elsif Profile.PREFERED_LANGUAGE == "English" %}
Hello!
{% endif %}

```


My email address is {{site.myemail}}

# Social Channels

twitter_username: messwithsunil

github_username: gitsgulabjamun
