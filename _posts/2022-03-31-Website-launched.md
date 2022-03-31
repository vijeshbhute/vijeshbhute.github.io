---
layout: post
title: "Website launched"
date: 2022-03-31
---

<style>
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

.left {
  width: 70%;
}

.right {
  width: 30%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>

<h2>Two Unequal Columns</h2>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p>Well. Finally got around to putting this website together. Powered by <a href="http://jekyllrb.com" target ="_blank">Jekyll</a> and special thanks to Jonathan McGlone for a very handy tutorial! If you are interested to use GitHub to build your personal webpage, do check out <a href="http://jmcglone.com/guides/github-pages/" target ="_blank">this blogpost</a>.</p>
    <p>
      ### Testing out latex

$$ \nabla_\boldsymbol{x} J(\boldsymbol{x}) $$

### Trying RSS
Subscribe to updates <a href="/blog/atom.xml">RSS feed</A>
    </p>
  </div>
  <div class="column right" style="background-color:#bbb;">
    <h2>Trying Twitter feed</h2>
    <p><a class="twitter-timeline" href="https://twitter.com/VijeshBhute?ref_src=twsrc%5Etfw">Tweets by VijeshBhute</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script></p>
  </div>
</div>
<div class="row">
  <div class="column"></div>
  <div class="column"></div>
</div>
