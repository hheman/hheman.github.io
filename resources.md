---
layout: default
title: Resources
---
<h3><span class="list-heading">interesting blogs</span></h3>
<ul>
    {% for item in site.data.interesting-blogs %}
    <li>
        <a href="{{ item.link }}">{{ item.name }}</a>
    </li>
    {% endfor %}
</ul>

<h3><span class="list-heading">software landing pages</span></h3>
<p>Landing pages/documentation pages for organizations responsible for widely used pieces of software (mostly open-source) that one could learn from just browsing.</p>
<ul>
    {% for item in site.data.software-docs %}
    <li>
        <a href="{{ item.link }}">{{ item.name }}</a>
    </li>
    {% endfor %}
</ul>

<h3><span class="list-heading">interesting blog posts</span></h3>
<ul>
    {% for item in site.data.interesting-posts %}
    <li>
        <a href="{{ item.link }}">{{ item.name }}</a>
    </li>
    {% endfor %}
</ul>

<h3><span class="list-heading">learning resources</span></h3>
<ul>
    {% for item in site.data.for-learning %}
    <li>
        <a href="{{ item.link }}">{{ item.name }}</a>
    </li>
    {% endfor %}
</ul>