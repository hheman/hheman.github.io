---
layout: default
title: Resources
---
<h2>Interesting Blogs</h2>
<ul>
    {% for item in site.data.interesting-blogs %}
    <li>
        <a href="{{ item.link }}">{{ item.name }}</a>
    </li>
    {% endfor %}
</ul>

<h2>Software landing pages</h2>
<p>Landing pages/documentation pages for organizations responsible for widely used pieces of software (mostly open-source) that one could learn from just browsing.</p>
<ul>
    {% for item in site.data.software-docs %}
    <li>
        <a href="{{ item.link }}">{{ item.name }}</a>
    </li>
    {% endfor %}
</ul>

<h2>Interesting Blog Posts</h2>
<ul>
    {% for item in site.data.interesting-posts %}
    <li>
        <a href="{{ item.link }}">{{ item.name }}</a>
    </li>
    {% endfor %}
</ul>

<h2>Learning Resources</h2>
<ul>
    {% for item in site.data.for-learning %}
    <li>
        <a href="{{ item.link }}">{{ item.name }}</a>
    </li>
    {% endfor %}
</ul>