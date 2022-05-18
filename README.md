# Dynamic Gallery

Follow along tutorial on creating a dynamic image gallery using html, css (+ bootstrap css) & javascript.

## Structure

```
│ project-folder/
│   README.md
│   index.html - our main html file, the one that's gone opened first when the site is visited     
│
└─── css/
|       style.css - custom css, for things bootstrap doesn't provide us
|
└─── js/
|       main.js - our javascript which will make our gallery dynamic        
|
└─── images/ - all images that are needed for the website
|
└─── steps/ 
        | *.markdown - instructions written in markdown
        | 
        └─ previews/ - images showing previews at certain points
        
```

## Get started

1. Download the starter template from
   here [Open link & Click `Code` > `Download ZIP`](https://github.com/fakeheal/follow-along-dynamic-gallery/tree/bd5fc39232ba600f9c90ddec2428436ff397e22a)
2. Unzip the downloaded archive and rename the folder
   from: `follow-along-dynamic-gallery-bd5fc39232ba600f9c90ddec2428436ff397e22a` to something more human friendly
   like `dynamic-gallery`.
3. Open the folder in your favorite code editor (Visual Studio Code is recommended).
4. Proceed with the steps below

## Follow along

Each step listed below is a link to another Markdown document. There's also a link to the code of th final result for
each step.

## Steps

1. [Create initial layout with HTML + Bootstrap](./steps/create-initial-layout-with-html-and-boostrap.md) |
   Final [Source code](https://github.com/fakeheal/follow-along-dynamic-gallery/tree/7bf1e44732f0c6507f8795b0e93692a36dfb91f4)
2. [Use JS to create HTML tags and add classes](./steps/use-js-to-create-html-tags-and-add-classes.md) |
   Final [Source code](https://github.com/fakeheal/follow-along-dynamic-gallery/tree/e551c30e4849c35c4655d18665dc1758cccf3372)
3. [`fetch` images from `json` file](./steps/fetch-images-from-json-file.md) |
   Final [Source code](https://github.com/fakeheal/follow-along-dynamic-gallery/tree/f1cc92d039473a3ba55cea5bcc1a83a1caa75dcc)

## Result

At the end you will have a web page which displays images and an easy way to add more images just by adding the files to
the `images/` folder and updating the `json` file by adding the names of the images.

### But why?

![why gif](https://c.tenor.com/R_N2FwCFBbcAAAAM/confused-white-persian-guardian.gif)

#### Because

- editing HTML markup can lead to problems, such as: unclosed tags break the page or file becoming too big and hard to
  read
- separating the logic between multiple files makes the maintenance of a website easier
- JSON file can be easily replaced by an [API endpoint](https://en.wikipedia.org/wiki/API#Purpose) or list of images coming
  from a database, without ever touching the index.html
- practice (makes perfect)
