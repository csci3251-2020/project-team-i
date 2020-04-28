# Introduction
In this project, we will

* Create Issues and Project Board
* Set up readme.md
* Show our team to the Internet
* Keep Checking our project
* Write C code
* Get a status badge and Promote our repo

# Code

# Contributors
 
{% for stu in site.stu %}
  <p><img src = "{{ stu.image }}">@{{ stu.user }}({{ stu.name }})</p>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
