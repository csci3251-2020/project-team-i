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
<p>
* <img src = "{{ stu.image }}">@{{ stu.user }}({{ stu.name }})
  * {{ stu.content | markdownify }}
</p>
{% endfor %}

# Newcomer's Guide
1) Create your 1155xxxxxx.md file under \_stu folder (just follow others' format should be okay)
2) Add your hello card to our project board
3) Read the In-progress issues and pick one to work on. Remember to assign yourself to the issue
4) Frequently check our pull requests and approve them in order to make progress
5) Let's pass this course.
