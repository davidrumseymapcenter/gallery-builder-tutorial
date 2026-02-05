---
layout: default
title: Add Manifests to Your Gallery
nav_order: 4
---

# Add Images to Your Gallery

## Finding Manifests in Other Collections

IIIF is used by dozens of institutions around the world. In this section of the workshop we will add links from a couple of popular sites and explore the list of other participating entities. 

## Add a manifest from DavidRumsey.com

[DavidRumsey.com](https://www.DavidRumsey.com){:target="_blank"} is an extraordinary source for images of historical maps. At the time of this writing, there are over 145,000 images on the site. It has purpose-built tools for finding maps within the collection, including a geospatial serach function and the ability to search for text wihin the map images. 

- Go to [DavidRumsey.com](https://www.davidrumsey.com/luna/servlet/view/all?res=1&sort=Pub_List_No_InitialSort){:target="_blank"} and choose an item to add to your gallery

- In the top navigation bar, find and click on the dropdown menu that says SHARE.

- Look for the grey box that says IIIF Manifests. Click on the triangle in that box to reveal an additional field. Click the copy icon at right to copy the URL (or use control-click to copy).  

- Navigate back to the IIIF Gallery Builder. Paste the the manifest in the top field and click “Add Manifest(s)” 

- ***Add 2 or more additional items from DavidRumsey.com following this same workflow.***


## Add a manifest from the Internet Archive
The Internet Archive is a digital library that provides free access to millions of items including maps, websites, software applications, music, audiovisual, and print materials. All of the imagery is available via IIIF.

- Go to the [Internet Archive](https://archive.org/){:target="_blank"}. 
[TIP!]
The Internet Archive is vast and can be overwhelming! [This link](https://archive.org/search?query=map&sort=date&and%5B%5D=mediatype%3A%22image%22){:target="_blank"} leads to images labeled as maps.

- Find an item and visit the record page. i.e. [https://archive.org/details/mma_the_celestial_map_northern_hemisphere_358366](/){:target="_blank"}

- Copy the identifier for the record. It’s always right after “details”. In the above example it’s **mma_the_celestial_map_northern_hemisphere_358366**

- Place that identifier or id into the following URL structure: https://iiif.archive.org/iiif/:id/manifest.json.

- Our example becomes: https://iiif.archive.org/iiif/mma_the_celestial_map_northern_hemisphere_358366/manifest.json

- You can use this webapp to streamline the process [https://kristinallarsen.github.io/IIIFmanifest_maker/](/){:target="_blank"}.

- Copy your constructed link and navigate back to the IIIF Gallery Builder. Paste the the manifest in the top field and click “Add Manifest(s)” 

## Add a manifest from the Library of Congress
The Library of Congress is essentially the US national library. It also contains millions of holdings. Many but not all of their item images are available through IIIF.   
- 

- 

## Add a manifest from a repository of your choice

- The IIIF Consortium maintains a list of participating institutions with links to screenshots that illustrate how to locate those manifests: [https://iiif.io/guides/finding_resources/](https://iiif.io/guides/finding_resources/){:target="_blank"}. 

- Choose a repository from the list to investigate, learn to locate a manifest, and try to add an image to your gallery.

*Note that the Gallery Builder tool does not yet perfectly ingest manifests from all institutions. Please email kllarsen@stanford.edu with requests to add compatibility for a particular manifest format, or add an issue to our repository: <https://github.com/davidrumseymapcenter/set-builder>*
