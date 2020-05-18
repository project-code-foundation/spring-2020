---
revealjs-url: ../reveal.js
title: Web Design 5
author: Oliver Ni
date: May 4, 2020
---

## Week 4 Recap & Finish forms

---

# Client/server stuff and the web

---

## What happens when I visit a webpage?

![](clientserver5.gif)

---

## Parts of a website

* Client (browser rendering website)
  * *frontend*
* Server (retrieves from database, communicates with client)
  * *backend*
* Database (stores information)

---

## Client vs Server

![](clientserver4.gif)

---

## Client vs Server

![](clientserverscriptschart.jpg)

---

## Client vs Server

* HTML/CSS/JS for client
* Many different languages for server
* We are writing client-side code

---

## Server-side languages

![](backendlanguages.jpg)

---

## Different types of requests

![](getpost.jpeg)

---

## How do forms work?

![](diagram.png)

---

## Form code

```html
<form action="/submitform.php" method="post">

  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>

  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">

  <input type="submit">

</form>
```

* Form will make a request on submit
* `action` specifies where to send the request
* `method` for which http method
* `name` specifies key-value pairs

