---
layout: default
parent: Saving and Sharing
title: Open Deep Link in App 
nav_order: 4
---

# Saving and Sharing

To share your gallery without moving files to drive or as email attachments you can create a special link called a "deep link" that will open your collection in the gallery builder in a browser window.

[This is an example](https://davidrumseymapcenter.github.io/set-builder/?file=https://gist.githubusercontent.com/kristinallarsen/dd25a0e3fb0535d10d81b327a0d45454/raw/3b479ead4429474900b817bdfe0579d53cefa935/Ink%2520and%2520Empire
){:target="_blank"}

This is slightly complicated and requires a little more work to accomplish, but it is totally doable and worth the effort in most cases!
<hr>

## :octocat: Working with Github "Gists"

- [**Gist**](https://gist.github.com){:target="_blank"} is a website operated by GitHub that allows users to save code snippets without creating full-blown respositories.

- To include your gallery in a deep link, it must be in the cloud somewhere.

- A straightforward way to do this is to create a code snippet file (called a Gist) that contains the code from your gallery JSON.

<hr>

### :tada: Create a Gist account

- Go to [https://gist.github.com](https://gist.github.com){:target="_blank"}

- If you already have a GitHub account you can sign in with that.

- If not, create a new account.

{: .warning }
You can create Gists without an account. These are called "anonymous gists". The drawback is that once you make an anonymous gist there is no way for you to manage it, and it can't be changed or deleted. You have been warned :grinning: 

<hr>

## :link: Create a Sharable Link with GitHub Gist

- Sign in (or skip for an anonymous gist)

- Drag and drop your JSON file into the text box, or paste its contents

- In "Filename including extension" field, give it a descriptive name ending with -gallery.json

- We are using "-gallery" to keep straight which files we have made that will work in the Gallery Builder and which ones will work in IIIF Viewers. You can leave it out or choose another method for distinguishing link types for yourself.

- Optionally add a description

- Click "Create public gist" or "Create secret gist" to make it unlisted

{: .highlight } 
:shushing_face: Secret gists are fine! they can't be opened without the gallery builder link so there is no reason to make them public. 

- Click the "Raw" button in the top-right corner

- Copy the URL from your browser's address bar

- Build your shareable link:

```html
https://davidrumseymapcenter.github.io/set-builder/?file=PASTE_GIST_RAW_URL_HERE
```

Example:

```html
https://davidrumseymapcenter.github.io/set-builder/?file=https://gist.githubusercontent.com/kristinallarsen/dd25a0e3fb0535d10d81b327a0d45454/raw/3b479ead4429474900b817bdfe0579d53cefa935/Ink%2520and%2520Empire
```

## :zap: Test and share your work

Paste your link into the doc below.

- Test it to see if you can open it successfully 

- Try opening other people's links

<iframe src="https://docs.google.com/document/d/17KlJ8MjEnF-qfIc2yxGw6py7XIWMFh68mzPeiteO1OQ/edit?embedded=true" width="800" height="600"></iframe>


<hr>
