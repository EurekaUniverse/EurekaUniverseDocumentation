---
title: "EurekaUniverse"
date: 2019-02-23T20:04:28-06:10
draft: false
---

# Welcome to EurekaUniverse!

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.


# Files

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## Create files and folders

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.

## Switch to another file

All your files are listed in the file explorer. You can switch from one to another by clicking a file in the list.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.


# Synchronization

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
![enter image description here](data:image/jpeg;base64,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)
