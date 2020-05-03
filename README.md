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
<ul>
{% for stu in site.stu %}
  <li><img src = "{{ stu.image }}" height="50" width="50"/>@{{ stu.user }}({{ stu.name }})
      <ul>
          <li><p>{{ stu.content | markdownify }}</p></li>
      </ul>
  </li>
{% endfor %}
</ul>

# Newcomer's Guide
1) Create your 1155xxxxxx.md file under \_stu folder (just follow others' format should be okay)
2) Add your hello card to our project board
3) Read the In-progress issues and pick one to work on. Remember to assign yourself to the issue
4) Frequently check our pull requests and approve them in order to make progress
5) Let's pass this course.
