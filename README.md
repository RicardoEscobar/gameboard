# Gameboard
## Description
Get practice using the click event, `.toggle` share button, `.toggleClass` notification bell, and `.children()` to show details in this project.

## Objective
Gameboard is creating a scoreboard that displays NBA scores from around the league. [Here's what it looks like]("https://s3.amazonaws.com/codecademy-content/projects/2/gameboard/index.html"). Click the More link to see the dropdown menu; click the Share link to see the share menu; click the notification bell.

## Tasks
### 1.
Look at __index.html__:

In the `<div class="row more">`, there are two elements: an `<a class="more-btn">` and a `<ul class="more-menu">`. When the `<a>` is clicked, we want the `<ul class="more-menu">` to appear.

Inside the `<ul class="more-menu">`, there are two elements: an `<li class="share">` and a `<li class="share-menu">`. When the `<li class="share">` is clicked, we want the `<li class="share-menu">` to appear.

There is a `<span class="notification">` element. When that element is clicked, we want the notification bell to turn yellow.

### 2.
In __script.js__, attach a click event handler to the `<a class="more-btn">` element. When clicked, toggle the `<ul class="more-menu">` element. Use `.next()` to toggle the next sibling.

### 3.
Attach another click event handler to the `<li class="share">` element. When clicked, toggle the `<li class="share-menu">` element.

### 4.
Attach another click event handler to the notification bell. When clicked, toggle the class `active`.
