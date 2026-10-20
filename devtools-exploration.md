# DevTools Exploration

**Student:** Clinton Hamisi  
**GitHub:** [@Hamisi254IYF](https://github.com/Hamisi254IYF)  
**Assignment:** IYF S12 — Week 1, Task 1.2  
**Date:** October 2026

---

## Overview

This document records my exploration of three websites using browser
Developer Tools. For each site, I inspected the HTML structure, identified
key elements, and answered the questions from Task 1.2.

**Tool used:** Chrome DevTools (Elements panel, Styles pane, `:hov` state toggle)

---

## Website 1: https://example.com

### 1. What HTML tags are used on the page?

The page uses a minimal, semantic set of tags:

| Category | Tags found |
|---|---|
| Document structure | `<html>`, `<head>`, `<title>`, `<body>` |
| Content | `<div>`, `<h1>`, `<p>`, `<a>` |

### 2. What is the page title?

The page title is **"Example Domain"** — visible both in the browser tab
and inside the `<title>` element.

### 3. How many headings are there?

There is **1 heading** — a single `<h1>` element containing the text
"Example Domain".

---

## Website 2: https://developer.mozilla.org

### 1. Navigation menu — what tag is it wrapped in?

The navigation menu is wrapped in a `<nav>` element with the class
`top-navigation`. Inside, the links are grouped using `<ul>` and `<li>`:

```html
<nav class="top-navigation">
    <ul class="top-navigation__list">
        <li><a class="top-navigation--link" href="...">References</a></li>
        <li><a class="top-navigation--link" href="...">Guides</a></li>
        <li><a class="top-navigation--link" href="...">Plus</a></li>
    </ul>
</nav>

