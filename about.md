---
layout: page
title: About
permalink: /about/
subtitle: A magazine of economic history and ideas.
---
The Economic Historian publishes essays on the history of money, markets, and economic ideas, and on how that history shapes the present.

We publish historians, economists, and writers from outside the academy. The register is the essay, not the journal article: argument first, written for a general reader, with the scholarship underneath it.

## Editors

{% for editor in site.editors %}{{ editor }}  
{% endfor %}

Write to the editors at [{{ site.editor_email }}](mailto:{{ site.editor_email }}).
