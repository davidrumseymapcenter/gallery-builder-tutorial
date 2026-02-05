---
layout: default
title: Add from Internet Archive
parent: Add Manifests to Your Gallery
nav_order: 1
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

## Add a manifest from the Library of Congress
The [Library of Congress](https://www.loc.gov/){:target="_blank"} is essentially the US national library. It also contains millions of holdings. Many but not all of their item images are available through IIIF.   

- Go to the Library of Congress' [Maps collection](https://www.loc.gov/maps/?sb=shelf-id){:target="_blank"}

- Choose an item and go to the record page. 

- Scroll to the bottom of the record. THe last text entry will be "IIIF Presentation Manifest." Right click on "Manifest (JSON/LD)" and copy the link address.

- Navigate back to the IIIF Gallery Builder. Paste the the manifest in the top field and click “Add Manifest(s)” 

## Add a manifest from a repository of your choice

- The IIIF Consortium maintains a list of participating institutions with links to screenshots that illustrate how to locate those manifests: [https://iiif.io/guides/finding_resources/](https://iiif.io/guides/finding_resources/){:target="_blank"}. 

- Choose a repository from the list to investigate

- Follow the instructions at the link to locate a manifest and add an image to your gallery.

*Note that the Gallery Builder tool does not yet perfectly ingest manifests from all institutions! Please email kllarsen@stanford.edu with requests to add compatibility for a particular manifest format, or add an issue to our repository: <https://github.com/davidrumseymapcenter/set-builder>*
