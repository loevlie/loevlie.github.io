---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order. generated by jekyll-scholar.
years: [2023, 2022]
nav: true
nav_order: 1
---
# Publications

Publications by category in reverse chronological order (generated by Jekyll-Scholar).

<input type="text" id="pub-search" placeholder="🔍 Search publications..." onkeyup="filterPubs()" style="width: 100%; max-width: 300px; margin-bottom: 1em;">

<div id="pub-list">
{% raw %}{% bibliography %}{% endraw %}
</div>

<script>
function filterPubs() {
  var input = document.getElementById('pub-search');
  var filter = input.value.toLowerCase();
  var list = document.getElementById('pub-list');
  var items = list.getElementsByTagName('li');
  for (var i = 0; i < items.length; i++) {
    var text = items[i].innerText || items[i].textContent;
    if (text.toLowerCase().includes(filter)) {
      items[i].style.display = "";
    } else {
      items[i].style.display = "none";
    }
  }
}
</script>