---
layout: topictemplate
---

## {{ site.shortname }}'s hobbies

If you know {{ site.shortname }} well, you will (by now) know that she does not stick to one hobby. She is jack of many but master in none. 

**Note:** She does not regret that! So, through this website she wants to introduce you to all her hobbies.

{% if site.interest == "all" %}
-  [Photography](photography.md)
-  [Sketching](sketching.md)
-  [Star-gazing](stargazing.md)
{% endif %}

{% if site.interest == "photography" %}
[Photography](photography.md)

Ask Smitha to change the value of `interest` to `all` to view all her hobbies.
{% endif %}

{% if site.interest == "sketching" %}
[Sketching](sketching.md)

Ask Smitha to change the value of `interest` to `all` to view all her hobbies.
{% endif %}

{% if site.interest == "stargazing" %}
[Star-gazing](stargazing.md)

Ask Smitha to change the value of `interest` to `all` to view all her hobbies.
{% endif %}

**[Home](../index.md)**