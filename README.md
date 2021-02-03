# HTML

HTML is the standard markup language for creating Web pages.

## What is HTML?

- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

## HTML Page Structure

Below is a visualization of an HTML page structure:

<!--![Page Structure](images/page_structure.PNG)-->

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page title</title>
  </head>
  <body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>
  </body>
</html>
```

## HTML Tag List

|Tag|Description|Done|Example|
|:-|:-|:-:|:-|
|`<!--...-->`|Defines a comment|:heavy_check_mark:|[Example 1][Ex1]|
|`<!DOCTYPE>`|Defines the document type|:heavy_check_mark:|[Example 1][Ex1]|
|`<a>`|Defines a hyperlink|:heavy_check_mark:|
|`<abbr>`|Defines an abbreviation or an acronym||
|`<address>`|Defines contact information for the author/owner of a document||
|`<area>`|Defines an area inside an image map||
|`<article>`|Defines an article||
|`<aside>`|Defines content aside from the page content||
|`<audio>`|Defines embedded sound content||
|`<b>`|Defines bold text|:heavy_check_mark:|[Example 3][Ex3]|
|`<base>`|Specifies the base URL/target for all relative URLs in a document||
|`<bdi>`|Isolates a part of text that might be formatted in a different direction from other text outside it||
|`<bdo>`|Overrides the current text direction||
|`<blockquote>`|Defines a section that is quoted from another source||
|`<body>`|Defines the document's body|:heavy_check_mark:|[Example 1][Ex1]|
|`<br>`|Defines a single line break|:heavy_check_mark:|[Example 2][Ex2]|
|`<button>`|Defines a clickable button|:heavy_check_mark:|
|`<canvas>`|Used to draw graphics, on the fly, via scripting (usually JavaScript)||
|`<caption>`|Defines a table caption||
|`<cite>`|Defines the title of a work||
|`<code>`|Defines a piece of computer code||
|`<col>`|Specifies column properties for each column within a `<colgroup>` element||
|`<colgroup>`|Specifies a group of one or more columns in a table for formatting||
|`<data>`|Adds a machine-readable translation of a given content||
|`<datalist>`|Specifies a list of pre-defined options for input controls||
|`<dd>`|Defines a description/value of a term in a description list|:heavy_check_mark:|[Example 4][Ex4]|
|`<del>`|Defines text that has been deleted from a document|:heavy_check_mark:|[Example 3][Ex3]|
|`<details>`|Defines additional details that the user can view or hide||
|`<dfn>`|Specifies a term that is going to be defined within the content||
|`<dialog>`|Defines a dialog box or window||
|`<div>`|Defines a section in a document||
|`<dl>`|Defines a description list|:heavy_check_mark:|[Example 4][Ex4]
|`<dt>`|Defines a term/name in a description list|:heavy_check_mark:|[Example 4][Ex4]|
|`<em>`|Defines emphasized text|:heavy_check_mark:|[Example 3][Ex3]|
|`<embed>`|Defines a container for an external application||
|`<fieldset>`|Groups related elements in a form||
|`<figcaption>`|Defines a caption for a `<figure>` element||
|`<figure>`|Specifies self-contained content||
|`<footer>`|Defines a footer for a document or section||
|`<form>`|Defines an HTML form for user input||
|`<h1>` to `<h6>`|Defines HTML headings|:heavy_check_mark:|[Example 1][Ex1]|
|`<head>`|Contains metadata/information for the document|:heavy_check_mark:|[Example 1][Ex1]|
|`<header>`|Defines a header for a document or section||
|`<hr>`|Defines a thematic change in the content|:heavy_check_mark:|[Example 2][Ex2]|
|`<html>`|Defines the root of an HTML document|:heavy_check_mark:|[Example 1][Ex1]|
|`<i>`|Defines a part of text in an alternate voice or mood|:heavy_check_mark:|[Example 3][Ex3]|
|`<iframe>`|Defines an inline frame||
|`<img>`|Defines an image||
|`<input>`|Defines an input control||
|`<ins>`|Defines a text that has been inserted into a document|:heavy_check_mark:|[Example 3][Ex3]|
|`<kbd>`|Defines keyboard input||
|`<label>`|Defines a label for an `<input>` element||
|`<legend>`|Defines a caption for a `<fieldset>` element||
|`<li>`|Defines a list item|:heavy_check_mark:|[Example 4][Ex4]|
|`<link>`|Defines the relationship between a document and an external resource (most used to link to style sheets)||
|`<main>`|Specifies the main content of a document||
|`<map>`|Defines an image map||
|`<mark>`|Defines marked/highlighted text|:heavy_check_mark:|[Example 3][Ex3]|
|`<meta>`|Defines metadata about an HTML document||
|`<meter>`|Defines a scalar measurement within a known range (a gauge)||
|`<nav>`|Defines navigation links||
|`<noscript>`|Defines an alternate content for users that do not support client-side scripts||
|`<object>`|Defines a container for an external application||
|`<ol>`|Defines an ordered list|:heavy_check_mark:|[Example 4][Ex4]|
|`<optgroup>`|Defines a group of related options in a drop-down list||
|`<option>`|Defines an option in a drop-down list||
|`<output>`|Defines the result of a calculation||
|`<p>`|Defines a paragraph|:heavy_check_mark:|[Example 2][Ex2]|
|`<param>`|Defines a parameter for an object||
|`<picture>`|Defines a container for multiple image resources||
|`<pre>`|Defines preformatted text|:heavy_check_mark:|[Example 5][Ex5]|
|`<progress>`|Represents the progress of a task||
|`<q>`|Defines a short quotation||
|`<rp>`|Defines what to show in browsers that do not support ruby annotations||
|`<rt>`|Defines an explanation/pronunciation of characters (for East Asian typography)||
|`<ruby>`|Defines a ruby annotation (for East Asian typography)||
|`<s>`|Defines text that is no longer correct||
|`<samp>`|Defines sample output from a computer program||
|`<script>`|Defines a client-side script||
|`<section>`|Defines a section in a document||
|`<select>`|Defines a drop-down list||
|`<small>`|Defines smaller text|:heavy_check_mark:|[Example 3][Ex3]|
|`<source>`|Defines multiple media resources for media elements (`<video>` and `<audio>`)||
|`<span>`|Defines a section in a document||
|`<strong>`|Defines important text|:heavy_check_mark:|[Example 3][Ex3]|
|`<style>`|Defines style information for a document||
|`<sub>`|Defines subscripted text|:heavy_check_mark:|[Example 3][Ex3]|
|`<summary>`|Defines a visible heading for a `<details>` element||
|`<sup>`|Defines superscripted text|:heavy_check_mark:|[Example 3][Ex3]|
|`<svg>`|Defines a container for SVG graphics||
|`<table>`|Defines a table||
|`<tbody>`|Groups the body content in a table||
|`<td>`|Defines a cell in a table||
|`<template>`|Defines a container for content that should be hidden when the page loads||
|`<textarea>`|Defines a multiline input control (text area)||
|`<tfoot>`|Groups the footer content in a table||
|`<th>`|Defines a header cell in a table||
|`<thead>`|Groups the header content in a table||
|`<time>`|Defines a specific time (or datetime)||
|`<title>`|Defines a title for the document|:heavy_check_mark:|[Example 1][Ex1]|
|`<tr>`|Defines a row in a table||
|`<track>`|Defines text tracks for media elements (`<video>` and `<audio>`)||
|`<u>`|Defines some text that is unarticulated and styled differently from normal text||
|`<ul>`|Defines an unordered list|:heavy_check_mark:|[Example 4][Ex4]|
|`<var>`|Defines a variable||
|`<video>`|Defines embedded video content||
|`<wbr>`|Defines a possible line-break||

[Ex1]: src/01_example.html
[Ex2]: src/02_example.html
[Ex3]: src/03_example.html
[Ex4]: src/04_example.html
[Ex5]: src/05_example.html
