---
revealjs-url: ../reveal.js
title: Web Design 2
author: Oliver Ni
date: April 6, 2020
---

## Week 1 Recap

Kahoot!

---

## CSS!

Style your page

---

## Here's how

![](comic_sans.png)

```html
<p style="color: blue; font-family: 'Comic Sans MS';">
    This text is blue and in Comic Sans
</p>
```

---

## Examples of CSS properties

* color
* background-color
* font-size
* font-family
* text-align
* margin
* padding

---

## Where to put CSS

* Inline CSS: `style` attribute in element
  * Generally bad, avoid doing this
* Instead, we can use a `<style>` element

---

## Here's how

```html
<!--... -->
<head>
    <style>
        /* CSS goes here */
    </style>
</head>
<!--... -->
```

---

## CSS Syntax

```css
h1 {
    color: blue;
    font-size: 100px;
    font-family: monospace;
}
```

```html
<h1>This is blue and big!</h1>
<h1>This is also blue and big!</h1>
```

* Use *selectors*
* Most basic selector: element name
* Find all the `h1` elements and style them

---

## Classes

Mark elements with *classes* and select them in CSS with `.class`

```css
.blue {
    color: blue;
}
```

```html
<p>This is not blue.</p>
<p class="blue">This is blue</p>
```

---

## Back to HTML

Let's learn some more HTML

---

## Lists

```
<ul>
    <li>One</li>
    <li>Two</li>
    <li>Three</li>
    <li>Four</li>
</ul>
```

---

## "About Me" page

Open Repl.it classroom, in week 2 make a short webpage about yourself! Ask me if you have any questions