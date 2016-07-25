# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	
</body>
</html>
```

2.) What are the differences between these tags?

```html
<!-- Tag 1 -->
<img src="images/me.jpg" alt="My profile image">

<!-- Tag 2 -->
<div></div>
```

```
Explain here.
```
-Tag 1 is a link to an image with an alternate text while 
-Tag 2 is a division created to set a certain part of your html apart from the rest; sometimes to group like items.
---

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- Inline CSS -->
<div style="background-color: red;"></div>

<!-- Internal style sheet -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>

<!-- External style sheet (not shown) -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
Explain here:
```
-Inline SS bypasses using a style sheet and just styles that item in the HTML. 
-Internal SS creates styling within your HTML for multiple items.
-External SS has all your CSS on a seperate page, to make your code presumably less clunky and easier to read since its seperate.

2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* comment like this */
div {
  border-radius: 50%;
}
/* this will curve the edge of a border by 50% */

.header p {
  font-size: 18px;
}
/* This increases the size of your font to 18 pixels */

.footer {
  position: absolute;
  bottom: 0;
}
/* This makes your footer take precedence before all other elements on the page at the bottom. The distance from the bottom is set to zero. */

.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}
/* spash-image is a class which has a background image set to a picture that is linked via URL and it is set to cover the page. 100% is so that the size dynamically adapts to browser window size. */

.ninja:hover {
  display: none;
  color: black;
}
/* hover tells the page to do something while the cursor is hovering over an element. Display set to none make the element visually disappear*/
```


---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
