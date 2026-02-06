---
layout: default
title: Overview
nav_order: 2
---

# Overview

This section will provide an introduction to some foundational concepts behind how the gallery builder works and offer scenerios within which it could be useful.


## What is IIIF?

IIIF stands for the International Image Interoperability Framework.

It is pronounced "Triple-eye eff"

You can understand why people like to use the acronym.

It is both: 

1. A set of APIs (Application Programming Interfaces) defined by specifications; these specifications dictate how digital cultural objects are to be provided and received 

2. A community that develops and implements these specifications

IIIF aims to *standardize* how digital images are delivered and viewed.

The specifications support interoperability yet allow for flexibility and variety in the description of the object via metadata.

Each participating institution has control over how they describe things in their own collections, but they make the images available in a consistent way.

## What is a manifest?

A **IIIF manifest** is the package that contains all the information related to a particular digital object, including the image itself as well as the metadata.

It is like a shipping manifest, in that it includes important information about the contents.

It is written in a string of text in a format called JSON (pronounced *jay-SOHN*).

JSON is a file format that uses human-readable text to store and transmit data objects.

Today we will be working with a IIIF Manifest endpoint, or the link to the manifest. 

You saw these manifests in the first step:

```html
https://www.davidrumsey.com/luna/servlet/iiif/m/RUMSEY~8~1~296148~90067635/manifest
```

```html
https://purl.stanford.edu/ht369zy9186/iiif/manifest
```

```html
https://iiif.archive.org/iiif/map198204401/manifest.json
```

## A quick peek at some code

Copy one of the links in the boxes above, and paste it into the address bar in your web browser.


### 