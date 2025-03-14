---
title: Welcome to my crafting projects
---

Let's see how this goes.


# My Crafting Projects  

## 🧶 Knitting  
{% for project in site.knitting %}
![{{ project.title }}]({{ project.image }})  
**[{{ project.title }}]({{ project.url }})**  
{{ project.description }}  
{% endfor %}  

## 🪡 Blackwork  
{% for project in site.blackwork %}
![{{ project.title }}]({{ project.image }})  
**[{{ project.title }}]({{ project.url }})**  
{{ project.description }}  
{% endfor %}  
