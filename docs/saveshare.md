---
layout: default
title: Saving and Sharing
nav_order: 5
---

# Saving and Sharing Collections

## Save Your Gallery 

### For use in this web app
- Save your gallery by typing a name in the field below “SAVE GALLERY” and click “Save File".

- A file will be saved to your desktop with a name like “coolmaps-gallery.json”. The suffix “-gallery” indicates a file that can be read by the gallery builder web app. 

- You can make changes to the gallery after saving it but you will need to save a new version of the document. 

{: .note-title }
> About File Naming Conventions
>
> Use a file naming convention (coolmaps01kl, coolmaps02kl) to keep track of your versions. Include your initials as above if you are collaborating with others by sending files back and forth or uploading them to Google Drive. 

### For use in other IIIF Viewers
- Save your gallery by typing a name in the field below “SAVE GALLERY” and click on the grey IIIF logo in the lower right corner of the input window. 

- A file will be saved to your desktop with a name like coolmaps-manifest.json. The suffix “-manifest” indicates a file that can be opened with other IIIF Viewers like Mirador or Universal Viewer. 

- You will need to host your new manifest somewhere to open it in those viewers.

- If you are editing a gallery that is already being hosted somewhere (like on GitHub or Gist) and a link to it has been shared, you will need to replace the old file– or the code in the old file– in order for other users to see changes at that link. 

## Share Your Gallery 

### Send your JSON file via email
- Save your gallery locally (download JSON file)

- Attach your JSON file to an email

- In the body of the email, paste the link to the webapp: <https://davidrumseymapcenter.github.io/set-builder/>{:target="_blank"}

- Tell the recipient to download the file to their desktop and open it using the "Load Gallery" button in the app

### Create a Sharable Link with GitHub Gist

- Save your gallery locally (download JSON file)

- Go to <https://gist.github.com>

- Sign in (or skip for anonymous gist)

- Drag and drop your JSON file into the text box, or paste the contents

- In "Filename including extension" field, give it a descriptive name (e.g., "colonial-maps.json")

- Optionally add a description

- Click "Create public gist" (or "Create secret gist" for unlisted)

- Click the "Raw" button in the top-right corner

- Copy the URL from your browser's address bar

- Create your shareable link:

```html
https://davidrumseymapcenter.github.io/set-builder/?file=PASTE_GIST_RAW_URL_HERE
```

Example:

```html
https://davidrumseymapcenter.github.io/set-builder/?file=https://gist.githubusercontent.com/kristinallarsen/dd25a0e3fb0535d10d81b327a0d45454/raw/3b479ead4429474900b817bdfe0579d53cefa935/Ink%2520and%2520Empire
```

