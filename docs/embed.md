---
layout: default
title: Embed Gallery in a webpage
nav_order: 6
---

# Embed a Gallery in a webpage
{: .no_toc }

1. TOC
{:toc}

## Why embed a gallery?
Once you've created a gallery and have the code for it hosted online, you can provide context for it by embedding it within other webapges. 
[This page](https://davidrumseymapcenter.github.io/gallery-builder-tutorial/example.html) is using an iframe to embed a gallery. 
This is also a fairly straightforward way for to include selected items into a Canvas page for use with a class.  

## About iframes
The term "iframe" is short for "inline frame" and is an html element that lets you nest one HTML document inside of another.

{: .highlight}
Learn more about iframes at the W3 website:
[https://www.w3schools.com/tags/tag_iframe.ASP](https://www.w3schools.com/tags/tag_iframe.ASP)

## Make an iframe with a deep link

Remember [this step](https://davidrumseymapcenter.github.io/gallery-builder-tutorial/linkforapp.html)?

In that section you put your code in the cloud with Gist, got a link to the code, and put that link inside of the gallery builder tool link so that the recipient could click and open a both in one shot.

To make an iframe, you will take that link -- the one that contains the link to the Gist -- and put it inside yet another container.

Here is the basic structure:

```html
<iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials"></iframe>
```

Here is the code for the embedded gallery from the example in this tutorial:
```html
<iframe src="https://davidrumseymapcenter.github.io/set-builder/index.html?file=https://gist.githubusercontent.com/kristinallarsen/dd25a0e3fb0535d10d81b327a0d45454/raw/4150a5ad79cda3e4f90acacf0d7226224ee7daee/Ink%2520and%2520Empire" width="100%" height="1000" loading="lazy"></iframe>
```
Note that you can set the width and height of the container of your iframe.


## Paste iframe into html

In an html or markdown site, just paste the iframe in where you would like it to appear. 

While editing a Page in Canvas, look under the text box for the </> symbol. Click this to display the html. Paste your iframe code into the right spot, then shift back to html by clicking </> again, save your changes, and admire your handiwork.

{: .highlight}
Learn more about embedding content in Canvas on the website "[How to Canvas](https://www.howtocanvas.com/create-amazing-pages-in-canvas/embedding-content)" by Sean Nufer.

<hr>
