---
layout: default
title: Internet Archive
parent: Add Images
nav_order: 3
---

# Add Images to Your Gallery

## Add a manifest from the Internet Archive
The [Internet Archive](https://archive.org/){:target="_blank"} is a digital library that provides free access to millions of items including maps, websites, software applications, music, audiovisual, and print materials. 

All of the imagery on the site is available via IIIF.

- Go look at [map images ](https://archive.org/search?query=map&sort=date&and%5B%5D=mediatype%3A%22image%22){:target="_blank"} on the Internet Archive.

- Choose an item and visit the record page.
  
>{: .highlight }
Example: [https://archive.org/details/mma_the_celestial_map_northern_hemisphere_358366](https://archive.org/details/mma_the_celestial_map_northern_hemisphere_358366){:target="_blank"}

- Locate the identifier or "id" for the record. It is right after /details/. 

>{: .highlight }
In the above example it’s *mma_the_celestial_map_northern_hemisphere_358366*

- Copy the id and place it into the following URL structure: https://iiif.archive.org/iiif/**:id**/manifest.json.

>{: .highlight }
>Our example becomes: https://iiif.archive.org/iiif/**mma_the_celestial_map_northern_hemisphere_358366**/manifest.json

- Use [this webapp](https://kristinallarsen.github.io/IIIFmanifest_maker/){:target="_blank"} to streamline the process.

<iframe src="https://kristinallarsen.github.io/IIIFmanifest_maker/" allow="clipboard-write" style="border:none;" width="100%" height="500" title="IIIF Manifest Generator"></iframe>

- Copy your constructed link and navigate back to the IIIF Gallery Builder. Paste the the manifest in the top field and click “Add Manifest(s)” 

{: .new }
***Add 1 or more additional items from the Internet Archive following this same workflow.***

