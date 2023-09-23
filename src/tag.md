---
pagination:
  data: collections
  size: 1
  alias: selectedTag
permalink: /tags/{{ selectedTag | noEmoji | toWebAddress | slug }}/
layout: layouts/recipes-list.njk
allRecipesLabel: All recipes
eleventyComputed:
  metaTitle: "{{ selectedTag | noEmoji | toWebAddress }}"
---
