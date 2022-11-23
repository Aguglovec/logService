---
title: Let's talk about static sites!
layout: page
mainPadding: py-0
excerpt: # used for page excerpts and META (will be overwritten if SEO used below)
author: shane-robinson # only displayed on Post lists and detail views. Defaults to _data/meta.authorURL
eleventyNavigation: # Required if want to display in Main Nav Bar
key: main # "main" is required
title: Onepager # as it will appear in the nav
order: 1 # order to display in the nav (index = 1)
seo: # SEO values are used for OG and will overwrite 'title' and 'excerpt' above
title:
description:
image: # used for OG:image and Twitter:image. Overrides default set in _data/meta.siteImage
pagination:
data: collections.section
size: 12
reverse: true
alias: sections
structure:
g_pageWidth: w-full
---

{% for section in sections | reverse %}

    {% set component = ['components/', section.data.component, '.njk'] %}

    {% set heroSettings = section.data.heroSettings %}
    {% include component | join %}


{% endfor %}