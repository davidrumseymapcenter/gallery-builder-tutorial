---
layout: default
title: Add from Internet Archive
parent: Add Images
nav_order: 2
---

# Add Images to Your Gallery

## Add a manifest from the Internet Archive
The [Internet Archive](https://archive.org/){:target="_blank"} is a digital library that provides free access to millions of items including maps, websites, software applications, music, audiovisual, and print materials. All of the imagery is available via IIIF.

- Go look at [map images ](https://archive.org/search?query=map&sort=date&and%5B%5D=mediatype%3A%22image%22){:target="_blank"} on the Internet Archive.

- Choose an item and visit the record page. i.e. [https://archive.org/details/mma_the_celestial_map_northern_hemisphere_358366](/){:target="_blank"}

- Copy the identifier for the record. It’s always right after “details”. In the above example it’s *mma_the_celestial_map_northern_hemisphere_358366*

- Place that identifier or id into the following URL structure: https://iiif.archive.org/iiif/**:id**/manifest.json.

- Our example becomes: https://iiif.archive.org/iiif/mma_the_celestial_map_northern_hemisphere_358366/manifest.json

- You can use this webapp to streamline the process: [IA IIIF Manifest Generator](https://kristinallarsen.github.io/IIIFmanifest_maker/){:target="_blank"}.

- Copy your constructed link and navigate back to the IIIF Gallery Builder. Paste the the manifest in the top field and click “Add Manifest(s)” 
