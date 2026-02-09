---
layout: default
title: Embed Gallery in Canvas
nav_order: 6
---

# Embed a Gallery in a Canvas page
{: .no_toc }

1. TOC
{:toc}

## Why embed a gallery?

[This page](/docs/embed.html) is using an iframe to embed a gallery. 

## About iframes

[https://www.w3schools.com/tags/tag_iframe.ASP](https://www.w3schools.com/tags/tag_iframe.ASP)

## Make an iframe with a deep link

Remember [this step](https://davidrumseymapcenter.github.io/gallery-builder-tutorial/linkforapp.html)?

In that section you put your code in the cloud, got a link to the code in Gist, and put that link inside of another link so that the recipient could click and open a gallery in the gallery builder.

To make an iframe, you will take that link -- the one that contains the link to the Gist -- and put it inside yet another container.

EXAMPLES
```html
<iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials"></iframe>
```

```html
<iframe src="https://davidrumseymapcenter.github.io/set-builder/index.html?file=https://gist.githubusercontent.com/kristinallarsen/dd25a0e3fb0535d10d81b327a0d45454/raw/4150a5ad79cda3e4f90acacf0d7226224ee7daee/Ink%2520and%2520Empire" width="100%" height="1000" loading="lazy"></iframe>
```


## Paste iframe into html


<hr>
