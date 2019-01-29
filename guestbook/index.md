---
title: Guestbook
layout: post
comments: true
# other options
---

留言板
----

{% if page.comments %}
{% include comments.md %}
{% endif %}
