---
layout: page
title: Research, Assessment, & Design  
---

LIS 570 is an introduction to the design of research projects, and the use of research methods to conduct evaluation in library and information science.

It's helpful to think of this course a *survey* of research and evaluation in LIS. Just as a *survey course* in literature or history is meant to give a general overview, so too is LIS 570 with respect to methods and evaluation.

# Schedule

**Class**

- Section A meets 8:30-10:20 each Monday and Wednesday
- Section B meets 10:30-12:20 each Tuesday and Wednesday

**Office hours**: Office hours with TA's are as follows:

- Section A: Yvette - Wednesdays 4-5pm (sign up using the directions on Canvas)
- Section B: Kunsang - Wednesdays 3:00-4:00pm; Thursdays 4:00-5:00pm (sign up using the directions on Canvas)

If you need to schedule a meeting with Dr. Weber use the calendly link found on your canvas site

**Weekly Topics**
<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d' }}</strong>:
        {% if lecture.ready %}
            <a href="/LIS-570-Au2020/{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

Video recordings of the lectures are available on pages throughout this course site and [on YouTube](https://www.youtube.com/playlist?list=PLbfZ2tKmriI7wsTY0fusl6OCrJsdhXSsr).

# About the class

**Staff**: This class is taught by [Nic](http://nicweber.info), and two TA's - [Yvette](https://www.yvetteiribe.com/) and [Kunsang](https://wcleeblog.wordpress.com/).

**Questions**: See the FAQ page above


## Acknowledgements

Thanks and appreciation to Ricardo Gomez for sharing materials related to his teaching of this class, [@tttkay](https://twitter.com/tttkay) for the 'Black Excellence in LIS' reading list which informed many of the readings used here.  

---

<div class="small center">
<p><a href="https://github.com/nniiicc/LIS-570-Au2021">Source code</a>.</p>
<p>Licensed under CC BY-NC-SA.</p>
<p>See <a href="/license/">here</a> for info on license</p>
</div>
