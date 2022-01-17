---
layout: default
title: Home
---

<header>

</header>

<section>
<div class="row">
<div class="6u 12u$(medium)">
<ul class="actions vertical">
<!-- <li><a href="#" class="button special fit">About me</a></li> -->
<li><a href="#code_anchor" class="button fit">Software</a></li>
</ul>
</div>
<div class="6u 12u$(medium)">
<ul class="actions vertical">
<!-- <li><a href="#" class="button special fit">CV </a></li> -->
<li><a href="#pub_anchor" class="button fit">Publications</a></li>
</ul>
</div>
</div>
</section>

<hr>
<h2 id="code_anchor">Software</h2>
{% include tiles.html %}
<br>

<p> Find all my code on <a href="https://github.com/aineniamh"><strong>GitHub</strong>.</a></p>

<hr>

<h2 id="pub_anchor"> Publications</h2>
<p>Featured publications:</p>
{% include paper_tiles.html %}
<br>

<p> Full list of publications can be found on <a href="https://scholar.google.com/citations?user=IOY1T30AAAAJ&hl=en"><strong>Google Scholar</strong>.</a></p>
<hr>

<h2>Education</h2>
{% include location_tiles.html %}

<p> Online <a href="{{ site.baseurl }}/cv.html"><strong>CV</strong>.</a></p>