# Week 4 Agenda  
## HTML Review + Challenges + Introduction to Styling

Today we will review HTML basics, practice with challenges, and learn how to add styles to our website.

---

## What You Will Learn

By the end of this class, you will:
- Review basic HTML structure and tags
- Practice fixing and writing HTML through challenges
- Learn how to use the `style` attribute
- Add simple styling to your portfolio page

---

# Part 1: HTML Review

## What is HTML?

HTML (HyperText Markup Language) is used to:
- structure a webpage
- organize content like text, images, and links

---

## Basic HTML Structure
```
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
  </head>
  <body>
    <h1>Hello</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

## Important Concepts to Remember
### Tags and Elements
```
<p>Hello</p>
```
<p> = opening tag
</p> = closing tag
whole thing = element

### Common Tags
- `<h1> to <h6>` — headings
- `<p>` — paragraph
- `<a>` — link
- `<img>` — image
- `<ul>, <ol>, <li>` — lists

### Attributes

Attributes give extra information:

`<a href="https://github.com">GitHub</a>`
href is an attribute

# Part 2: Challenge Activities
## Challenge 1: Fix the Errors

Find and fix all mistakes in the code below:
```
<html>
  <head>
    <title>My Page<title>
  </head>
  <body>
    <h1>Welcome
    <p>This is my website
    <a href="https://github.com">My GitHub
  </body>
</html>
```

## Challenge 2: Fix the Order
The structure below is incorrect. Rearrange it into the correct HTML structure.
```
<body>
<!DOCTYPE html>
<h1>My Portfolio</h1>
<html>
<title>Portfolio</title>
<head>
<p>Hello world</p>
</body>
</head>
</html>
```

## Challenge 3: Build a Simple Recipe Page

Create an HTML page that includes:

- A title: "My Favorite Food"
- An image of the food
- A paragraph describing the food
- A section called "Ingredients"
- A bullet list of at least 3 ingredients
- A section called "Steps"
- A numbered list of at least 3 steps
- Use of 3 formatting tags


# Part 3: Introduction to Styling

So far, our website has structure but no design.

Now we will learn how to **style elements**.

## What is the `style` Attribute?

The style attribute allows you to add design directly to an HTML element.

`<p style="color: blue;">This text is blue</p>`

## Syntax

`<tag style="property: value;">`

## Common Style Properties

### Text Color
`<p style="color: red;">Red text</p>`
### Background Color
`<p style="background-color: yellow;">Highlighted text</p>`
### Font Size
`<p style="font-size: 20px;">Bigger text</p>`
### Text Alignment
`<p style="text-align: center;">Centered text</p>`
### Multiple Styles
`<p style="color: blue; font-size: 18px;">Styled text</p>`


## Common Mistakes
### Missing semicolon
`style="color: red font-size: 20px"`
Correct:
`style="color: red; font-size: 20px;"`

### Misspelling property names
`style="colr: red;"`
Correct:
`style="color: red;"`

### Forgetting quotes
`style=color:red;`
Correct:
`style="color: red;"`

# What You Learned

Today you:

- reviewed HTML basics
- solved 3 HTML challenges
- learned how to use the style attribute

Next week, we will learn CSS, which is a better way to style websites.