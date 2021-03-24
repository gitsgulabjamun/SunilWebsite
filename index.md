---
layout: default
title: Stay a while
author: Sunil Jadhav
---

# {{page.title}}

Hello All,

My Name is Sunil Jadhav. Get to know more about me.

-  [My likes](topics/Hobbies)
-  [Employment History](topics/history)

## Nerd alert!

I have a cool reading list that may interest you. Following are some of my favorite books:

{% for item in site.data.readinglist %}
- {{ item.book }}: {{ item.creator }}
{% endfor %}


I also do some `liquid` code:


```

{% raw %}{{ 5 | plus: 6 }}{% endraw %} equals 11.

```


My email address is {{site.myemail}}

# Social Channels

twitter_username: messwithsunil

github_username: gitsgulabjamun


_This site was last updated at {{site.time}}_
