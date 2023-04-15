---
title: Accepted Papers
layout: default
weight: 5
---

<h1>{{ site.data.conference.short_name }} {{ site.data.conference.year }} Accepted Papers</h1>

<a href="https://proceedings.mlr.press/v206/"><b>PMLR Conference Proceedings</b></a>
<br>
<a href="https://virtual.aistats.org/virtual/2023/papers.html"><b>Virtual Conference Website: Accepted Papers</b></a>

<h2>Notable papers</h2>

{%- if site.data.orals_fixed -%}
<ul>
	{%- for paper in site.data.orals_fixed -%}
	<li> <b>{{paper.PaperTitle}}</b> <br>{{paper.AuthorNames | remove: "*"}}</li>
	<br>
	{%- endfor -%}
</ul>
{%- endif -%}

<h2>All Accepted Papers</h2>

{%- if site.data.accepted_papers -%}
<ul>
	{%- for paper in site.data.accepted_papers -%}
	<li> <b>{{paper.PaperTitle}}</b> <br>{{paper.AuthorNames | remove: "*"}}</li>
	<br>
	{%- endfor -%}
</ul>
{%- endif -%}