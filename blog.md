--- layout: default title: Blog --- 
{% for post in site.posts %} - [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %-d, %Y" }} {% endfor %}

This is where I'll blog on some various cybersecurity topics.
