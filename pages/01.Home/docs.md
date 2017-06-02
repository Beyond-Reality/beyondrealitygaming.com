---
title: ''
body_classes: ''
order_by: ''
order_manual: ''
---

## Welcome to our wiki, Documentation will only be worked on for our 1.11.2 + modpacks.

##### If you would like to contribute please visit, https://github.com/Beyond-Reality/beyondrealitygaming.com/tree/master/pages/02.Mod-Pack's

The formatting is pretty straight forward to make a new page or to edit a existing one. For every new document you need to nest it inside a folder. This adds the slug and link to the side menu of the Wiki. Every folder needs a markdown file labled **docs.md** inside of it. Which will contain all the text displayed inside the slug/link. At the top of each markdown file **(docs.md)** you need to add some YMAL matter to make it all function. 

#### You can copy and paste this for the most part 
```
---
title: Insert name here!
published: true
process:
    markdown: true
    twig: false
routable: true
cache_enable: true
visible: true
---
```
#### To edit any existing pages you can ether find them by looking through the files within our github repo or clicking on the top right **"Edit this page"** button which will bring you directly to the github repo file destination. Please make a pull request and submit your changes. Once accepted the syncing between github and our website is handled automaticly.

More to come about our in game documentation layout and editing.
