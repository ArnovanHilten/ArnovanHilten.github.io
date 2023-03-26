---
title: "Including a plotly plot in a post!"
date: 2019-04-18T15:34:30-04:00
categories:
  - blog
tags:
  - Jekyll
  - update
---

To include a plotly plot do the following things:

- remove gem jemoji 
- remove the <html> tag in the plotly html and use  raw and endraw 
- and then use the {% include overview.html %}
and here is the result:

{% include overview.html %}

test the iframe:

<iframe
src="https://iframe.embednpages.com/uqWwSEsMRXvsGi1cqqaq"
style="width:100%; height:100%; min-height:500px; border:0; padding:0;"
/>