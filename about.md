---
layout: page
title: About
permalink: /about/
subtitle: A magazine of economic history and the history of economic ideas.
---
The Economic Historian is a journal of ideas. It publishes work that analyzes current events, world politics, the global economy, state power, historical events and ongoing historical processes from a range of disciplines. In its intellectual range and coverage, it draws on the history of Hobsbawm, E. P. Thompson, Abrahamian and Du Bois, and on the political economy of Marx, Polanyi, Minsky and Brenner. It also engages the history of capitalism of Sven Beckert, Caitlin Rosenthal and Walter Johnson, and the economic history of Robert Fogel, Gavin Wright and Paul Rhode.



## Editors

{% for editor in site.editors %}{{ editor }}<br>
{% endfor %}

Correspondence and submissions should be sent to <a href="mailto:{{ site.editor_email }}">{{ site.editor_email }}</a>. See the <a href="{{ '/submissions/' | relative_url }}">submission guidelines</a> before sending work.
