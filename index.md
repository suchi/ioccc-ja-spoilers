---
title: IOCCC日本語ネタバレ解説
top: true
layout: default
---

IOCCCをよく知らない人は、まず[このサイトについて]({{ site.baseurl }}{% link about.md %})を見てください。

{% assign contests = site.pages | where: "layout", "contest" | sort: "dir" %}
<div class="contests list-group">
{% for contest in contests %}
  <a href="{{ contest.url | relative_url }}" class="list-group-item list-group-item-action flex-column align-items-center text-center">IOCCC {{ contest.dir | slice: 1, 4 }}</a>
{% endfor %}
</div>

更新履歴:

* 2021/01/03: [IOCCC 1984]({{ site.baseurl }}{% link 1984/index.md %})、[IOCCC 1985]({{ site.baseurl }}{% link 1985/index.md %})、[IOCCC 1986]({{ site.baseurl }}{% link 1986/index.md %})の解説を公開しました。