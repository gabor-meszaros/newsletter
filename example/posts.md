---
layout: lead
title: Posts
permalink: /posts/
lead: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut posuere purus in accumsan ultrices."
sidebar: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut posuere purus in accumsan ultrices. Quisque quis consequat mi. Praesent ac tristique mauris. Maecenas malesuada viverra lobortis. Nam ut nibh turpis. Phasellus nec ligula eget massa dignissim ultricies ut sed nibh. Sed tincidunt ligula placerat nisl tincidunt, a elementum orci venenatis. Fusce vel posuere felis, bibendum aliquam lorem. Aliquam erat volutpat. Sed mauris nulla, pharetra non nisi ac, sollicitudin ornare metus. Sed egestas augue at malesuada consectetur. Aliquam aliquam, justo eu pellentesque pharetra, urna purus efficitur augue, id tincidunt tellus nunc vel arcu. Curabitur arcu turpis, dictum in urna sed, ornare consectetur nulla."
---

<ul>
  {% for post in site.posts %}
  <li>
    <span>{{ post.date | date: "%b %-d, %Y" }}</span>
    <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
  </li>
  {% endfor %}
</ul>
