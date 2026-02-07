---
layout: default
parent: Saving and Sharing
title: Put Your Code in the Cloud
nav_order: 3
---

# Saving and Sharing

To share your gallery without moving files to drive or as email attachments you can create a special link called a "deep link" that will open your collection in the gallery builder in a browser window.

[This is an example](https://davidrumseymapcenter.github.io/set-builder/?file=https://gist.githubusercontent.com/kristinallarsen/dd25a0e3fb0535d10d81b327a0d45454/raw/3b479ead4429474900b817bdfe0579d53cefa935/Ink%2520and%2520Empire
){:target="_blank"}

This is slightly complicated and requires a little more work to accomplish, but it is totally doable and worth the effort in most cases!
<hr>

## 🤓 Working with Github "Gists"

- [**Gist**](https://gist.github.com){:target="_blank"} is a website operated by GitHub that allows users to save code snippets without creating full-blown respositories.

- To include your gallery in a deep link, it must be in the cloud somewhere.

- A straightforward way to do this is to create a code snippet file (called a Gist) that contains the code from your gallery JSON.

<hr>

### 🎉 Create a Gist account

- Go to [https://gist.github.com](https://gist.github.com){:target="_blank"}

- If you already have a GitHub account you can sign in with that.

- If not, create a new account.

{: .warning }
You can create Gists without an account. These are called "anonymous gists". The drawback is that once you make an anonymous gist there is no way for you to manage it, and it can't be changed or deleted. You have been warned 😀

<hr>

## 🔗 Create a Sharable Link with GitHub Gist

- Sign in (or skip for an anonymous gist)

- Drag and drop your JSON file into the text box, or paste its contents

- In "Filename including extension" field, give it a descriptive name (e.g., "colonial-maps.json")

- Optionally add a description

- Click "Create public gist" or "Create secret gist" to make it unlisted

{: .highlight } 
🤫 Secret gists are fine! they can't be opened without the gallery builder link so there is no reason to make them public. 

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


<hr>
