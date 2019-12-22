# Arrow-media

A showcase of tutorials, conference presentations, and other Arrow-related content.

## Adding a resource

```
---
title: Handling exceptions in Arrow
icon: /img/icon-article.svg
header-image: /img/blog-image-header.png
category: articles
tags: [core]
link: https://www.spantree.net/blog/2017/09/15/kotlin-exception-handling-with-kategory.html
---
Description of the resource.
```
The fields to fill are described below:

### title
The title of the resource
### header-image
The image the resource will show.
Set to `/img/blog-image-header.png` if you don´t have an image.
### category
Specify the category of the resource
##### Tutorials
```
category: tutorials
```
##### Conferences
```
category: conferences
```
##### Videos
```
category: videos
```
##### Articles
```
category: articles
```
##### SlideDecks

If a talk wasn't recorded, you can add the slide deck with this category:

```
category: slidedecks
```

If the talk was recorded, please, choose `category: conferences` and add the link of the corresponding slide deck in the description.
### tags
Here you can specify the Arrow module or modules to which the resource is related: `core`, `fx`, `optics`, `incubator`, or `meta`
You can add more than one tag as follows:
`tags: [core, fx]`
### link
The link to the resource
### event
In case of a conference, please, indicate the event. For instance: `event: Lambda World, Cádiz, Spain`


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
