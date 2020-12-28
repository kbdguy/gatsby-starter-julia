---
title: "Code Examples: GIF img in Markdown file"
date: "2020-12-28"
draft: false
path: "/blog/gif-img-example"
---
```js

```
##Gatsby/Markdown gif img example

Of course, you can reference the image hosted externally to the site like this:

```js
![Bad driver](https://i.pinimg.com/originals/be/4d/69/be4d69c683f8eae492e02330ee0917bb.gif)
```

![Bad driver](https://i.pinimg.com/originals/be/4d/69/be4d69c683f8eae492e02330ee0917bb.gif)

<hr />
To host the image internally, one way to do it is to put the gif in the project's "static" folder (directly off of the project root).  To get the image "static/17-Bad-Driver.gif", use this code:

```js
![Bad driver](/17-Bad-Driver.gif)
```

![Bad driver](/17-Bad-Driver.gif)

<hr />

Similarly, you can use html syntax if you need to do something not supported by markdown:
```js
  <img src="https://wanna-joke.com/wp-content/uploads/2016/07/parking-gif-fail-driving-car.gif" alt="bad driver" height="200">
```
<img src="https://wanna-joke.com/wp-content/uploads/2016/07/parking-gif-fail-driving-car.gif" alt="bad driver" height="200">

