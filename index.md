---
layout: default
---

{% include 01-name.md %}

<br>

{% include 02-image.md %}

<br>

{% include 03-links.md %}

<br>

{% include 04-lists.md %}

<br>

{% include 05-emphasis.md %}
git fetch origin
git checkout -b add-lists-emphasis origin/add-lists-emphasis
git merge maingit checkout main
git merge --no-ff add-lists-emphasis
git push origin main
