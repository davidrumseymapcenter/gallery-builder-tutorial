---
layout: article
title: Working with the IIIF Gallery Builder
url: /gallery-builder-tutorial/
show_title: false
aside:
  toc: true
sidebar:
  nav: webmap-workshop
---

# Overview

This tutorial covers how to build an image gallery set with the IIIF Gallery Builder web app using images from Searchworks and DavidRumsey.com.

1. Open the Gallery Builder
- https://davidrumseymapcenter.github.io/set-builder/

2. Find a IIIF Manifest 
- Go to Searchworks.stanford.edu and find a record for a map that includes an image. In the item record, click on the “hamburger” menu in the upper left corner of the box containing the image to toggle the sidebar

- Scroll to the bottom of the sidebar and locate the IIIF Manifest
- (It is a link that starts with "https://purl.stanford.edu/...
 and ends with "manifest")

 - Right click on the clink and click "Copy Link Address"

3. Add the manifest to your gallery
- in the IIIF Gallery Builder tool, paste the manifest into the top field and click “Add Manifest(s)”
- If the item has multiple pages, you will see a pop-up window where you can select the desired page or pages.  

- A card should appear below the Input Panel that shows the thumbnail and metadata for the item you just added

Add additional items following this same workflow. 

<hr>

4. Finding and using manifests from DavidRumsey.com

Open an item record on DavidRumsey.com
Find and click the dropdown menu that says SHARE.
Click on the triangle to the left of the heading that says IIIF Manifests to reveal an additional field. Click the copy icon at right to copy the URL. 

Back in the IIIF Gallery Builder, paste the the manifest in the top field and click “Add Manifest(s)” 

5. Finding Maifests in Other Collections
- The IIIF Consortium maintains a list of participating institutions with links to screenshots that illustrate how to locate those manifests: https://iiif.io/guides/finding_resources/. 

- Note that the gallery builder tool does not yet perfectly ingest manifests from all institutions. Please email kllarsen@stanford.edu with requests to add compatibility for a particular manifest format, or add an issue to our repository: https://github.com/davidrumseymapcenter/set-builder   

6. Editing and Saving Collections

Rearrange your collection
- You can rearrange cards as needed by dragging and dropping. (Click within the box but outside of the thumbnail image to drag a card.)
- If you need to remove a card, click the x in the upper right corner.

Change the view
- Use the control links at upper right to hide and show the input panel and hide and show the viewing pane. 
- Change the size of the viewing pane by dragging the vertical grey bar to your desired location.

Save Gallery 
1. For use in this web app
- Save your gallery by typing a name (use the class name with underscores instead of spaces) in the field below “SAVE GALLERY” and click “Save Locally”. 
- A file will be saved to your desktop with a name like “coolmaps-gallery.json”. The suffix “-gallery” indicates a file that can be read by the gallery builder web app. 
- You can make changes to the gallery after saving it but you will need to save a new version of the document. 
- Use a file naming convention (coolmaps01kl, coolmaps02kl) to keep track of your versions. Include your initials as above if you are collaborating with others by sending files back and forth or uploading them to Google Drive. 

- If you are editing a gallery that is already being hosted somewhere (like on GitHub or Gist) and a link to it has been shared, you will need to replace the old file– or the code in the old file– in order for other users to see changes at that link. 

2. For use in other IIIF Viewers
- Save your gallery by typing a name in the field below “SAVE GALLERY” and click on the grey IIIF logo in the lower right corner of the input window. 
- A file will be saved to your desktop with a name like coolmaps-manifest.json. The suffix “-manifest” indicates a file that can be opened with other IIIF Viewers like Mirador or Universal Viewer. 
- You will need to host your new manifest somewhere to open it in those viewers – follow the instructions for creating links in the Help Doc.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
