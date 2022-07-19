# My custom minimal theme for Github pages

Original theme is 

## Layouts

There are two built in layouts for markdown generated pages, one for the homepage, and another one for new pages,
such as a tutorial or a bibliography section.

For API documentation generated with pdoc3 it's necessary to create a layout file for each generated html file.

## API documentation

And then for each subdirectory in the pdoc3 API, make a markdown page with the content

```
---
layout: #name of the html file uploaded in layouts without the .html---
permalink: /#name of the index/utils.html
---

```

## Table of contents

There is a built in table of contents taken from https://github.com/allejo/jekyll-toc that worked out of the box by
adding the file in the included folder. By default it show on the side bar of sidepage layout and uses the markdown
titles and subtitles to generate the section pointer.
