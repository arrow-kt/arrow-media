# Arrow-media

A showcase of tutorials, conference presentations, and other Arrow-related content.

## Adding a Post

```
title: Handling exceptions in Arrow
icon: /img/icon-article.svg
header-image: /img/blog-image-header.png
category: articles
tags: [core]
link: https://www.spantree.net/blog/2017/09/15/kotlin-exception-handling-with-kategory.html
```
The fields to fill are described below:

### title
The title of the post
### icon
There are 4 different icons to choose from
##### Article
`icon: /img/icon-article.svg`
![article icon](/img/icon/icon-article.png)
##### Podcast
`icon: /img/icon-podcast.svg`
![podcast icon](/img/icon/icon-podcast.png)
##### Talk
`icon: /img/icon-talk.svg`
![talk icon](/img/icon/icon-talk.png)
##### Video
`icon: /img/icon-video.svg`
![video icon](/img/icon/icon-video.png)

### header-image
The image the post will show.
Set to `/img/blog-image-header.png` if you don´t have an image.
### category
Specify the category of the post
##### Tutorials
category: tutorials
##### Conferences
category: conferences
##### Videos
category: videos
##### Articles
category: articles
### tags
Here you can specify the Arrow module or modules to which the post is related: `core`, `fx`, `optics`, `incubator`, or `meta`
You can add more than one tag as follows:
`tags: [core, fx]`
### link
The link to the post


## Books section
This example shows how to add a new book to the **Books** section.
The file needs to be placed in the `content/_books/` folder.

```
---
name: Functional Programming in Kotlin
image: https://images.manning.com/720/960/resize/book/1/9ac0117-69e6-4f0b-98a5-32844e7bd44d/FPinKotlin_hiresMEAP.png
link: https://www.manning.com/books/functional-programming-in-kotlin?a_aid=fpinkotlin&a_bid=1cbbbc55" class="book-item
---
```
