---
layout: default
title: Rechercher
---

<meta http-equiv="refresh" content="0; url=https://thelinuxcamp.github.io/search/">
<link rel="canonical" href="https://thelinuxcamp.github.io/search/" />

<div id="search-container">
<input type="text" id="search-input" placeholder="Rechercher" style="width: 400px; height: 50px; font-size:18px;">
<ul id="results-container"></ul></div>

<script src="https://unpkg.com/simple-jekyll-search/dest/simple-jekyll-search.min.js"></script>

<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/techlovers/search.json'
  })
</script>