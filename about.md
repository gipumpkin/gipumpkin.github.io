---
layout: default
title: Bats
permalink: /about.html
favorite-animal: elephant
other-animal: hippo
pajamas: footies
---

{{ page.title }}

The home page was created by using a custom layout.

In this case, I'm using the default layout. It's the very simplest page at this point.

## Features of jekyll

Here, I'm taking information from the front matter.

Page front matter: {{ page.favorite-animal }}

Another animal is a {{ page.other-animal }}

Sitewide config - (this is stored in the config file.): {{ site.birthday }}

I like pajamas that are {{ page.pajamas }}
