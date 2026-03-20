# Week 3 Agenda  
## HTML Fundamentals + Deploying Your Portfolio Website

Today we will learn how to build the **structure of a website using HTML** and publish your **portfolio website** online.

---

## What You Will Learn

By the end of this class, you will:
- Understand what HTML is and how websites work
- Learn HTML syntax (tags, elements, attributes)
- Build your portfolio homepage using HTML
- Deploy your portfolio using GitHub Pages

---

# Part 1: What is HTML?

## What is HTML?

HTML stands for **HyperText Markup Language**.

- It is the **standard language used to create web pages**
- It tells the browser **what content to show and how it is structured** :contentReference[oaicite:0]{index=0}

Think of HTML like the **skeleton of a website**:
- HTML = structure
- CSS = style (colors, layout)
- JavaScript = behavior (interactivity)

---

## How Websites Work (Simple Version)

1. You write HTML code
2. The browser (Chrome, Safari, etc.) reads the code
3. The browser displays a webpage

---

# Part 2: HTML Syntax

## What is an HTML Element?

An **HTML element** is the building block of a webpage.

Basic structure:

```
<tag>Content</tag>
```
Example:
```
<p>Hello world</p>
```
This includes:
- Opening tag: `<p>`
- Content: Hello world
- Closing tag: `</p>`

Together, this is called an element.

## Rules of HTML Syntax

- Tags are wrapped in `< >`
- Most tags come in pairs:
  - Opening: <p>
  - Closing: </p>
- Closing tags always have a `/`
- Tags must match

Correct:
```
<p>Hello</p>
```
Incorrect:
```
<p>Hello</h1>
```

## Some Tags Don’t Need Closing

These are called self-closing tags.

Example:
```
<br>
<img src="image.png">
```

# Part 3: Basic HTML Page Structure

Every website starts with this structure:
```
<!DOCTYPE html>
<html>
  <head>
    <title>My Portfolio</title>
  </head>
  <body>
    <h1>Welcome to My Portfolio</h1>
    <p>Hello! My name is David.</p>
  </body>
</html>
```

## Explanation
`<!DOCTYPE html>` Tells the browser this is an HTML5 document<br>
`<html>` Root element (wraps everything)<br>
`<head>` Contains information about the page (not shown on the page)<br>
`<title>` Shows in browser tab<br>
`<body>` All visible content goes here<br>

# Part 4: HTML Tags You Will Use
## Headings
```
<h1>Main Title</h1>
<h2>Section</h2>
```
- `<h1>` is largest
- `<h6>` is smallest

## Paragraphs
`<p>This is a paragraph</p>`

## Links
`<a href="https://github.com">Visit GitHub</a>`
- href is an attribute
- Attributes give extra information to elements

## Images
`<img src="image.png" alt="My Image">`
- src = image path
- alt = description

## Lists
Unordered List
```
<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>
```
Ordered List
```
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```

# Part 5: Hands-On — Build Your Portfolio Homepage
## Step 1: Create File
Create a file: `index.html`<br>
This is your homepage.

## Step 2: Add Starter Code
```
<!DOCTYPE html>
<html>
  <head>
    <title>My Portfolio</title>
  </head>
  <body>
    <h1>Welcome to My Portfolio</h1>
    <p>Hello! My name is ______.</p>
  </body>
</html>
```

## Step 3: Add More Content
Add:
```
<h2>About Me</h2>
<p>I am learning how to build websites.</p>

<h2>Skills</h2>
<ul>
  <li>HTML</li>
  <li>CSS (coming soon)</li>
</ul>

<h2>Links</h2>
<a href="https://github.com">My GitHub</a>
```

## Step 4: Open Your Website
- Right-click `index.html`
- Open in browser

You should see your portfolio page.

# Part 6: What is GitHub Pages?
GitHub Pages lets you:
- turn your code into a real website
- share your portfolio with others
- host your website for free

# Part 7: Deploy Your Portfolio Website
## Step 1: Push Your Code
```
git add .
git commit -m "Added portfolio homepage"
git push
```

## Step 2: Enable GitHub Pages
1. Go to your repository
2. Click Settings
3. Click Pages
4. Under Source:
   - Select Deploy from a branch
   - Branch: main
   - Folder: /root
5. Click Save

## Step 3: Get Your Website Link

You will get a link like: `https://yourusername.github.io/portfolio/`

## Step 4: Open Your Website
- Click the link
- Refresh after 1–2 minutes if needed