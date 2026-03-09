# Week 2 Agenda
## Technical Tools Introduction

Today we will learn about the tools developers use to build and share software.

By the end of this class, you will:
- Understand what Git and GitHub are
- Learn basic Git commands
- Learn what an IDE is and how to use Visual Studio Code
- Connect VS Code to GitHub
- Create your portfolio repository
- Write your first README using Markdown

---

# Part 1: What are Git and GitHub?

## What is Git?

Git is a **version control system**.

Version control helps developers:
- Save different versions of their code
- Track changes over time
- Work together with other developers
- Undo mistakes if something breaks

Think of Git like a **save history for your code**.

Example:
```
Version 1 → basic website
Version 2 → added navigation
Version 3 → fixed bug
```

Git remembers all of these versions.

---

## What is GitHub?

GitHub is a **website that stores Git repositories online**.

A **repository (repo)** is a project folder that contains:
- code files
- images
- documentation
- project history

GitHub allows developers to:
- store projects online
- collaborate with others
- share their work
- build a portfolio

Example repositories might include:
- a website
- a mobile app
- a game
- a data science project

---

## Basic Git Commands

Here are some important Git commands developers use.

### Clone
Copies a repository from GitHub to your computer.
```
git clone <repository url>
```

### Add
Prepares files to be saved.
```
git add .
```

### Commit
Creates a snapshot of your changes.
```
git commit -m "describe your changes"
```

Example:
```
git commit -m "Added portfolio README"
```

### Push
Uploads your changes to GitHub.
```
git push
```

### Pull
Downloads the newest version from GitHub.
```
git pull
```
---

# Part 2: What is an IDE?

## What is an IDE?

IDE stands for **Integrated Development Environment**.

An IDE is a program that helps developers write and manage code.

Instead of using many separate tools, an IDE combines everything in one place.

Features usually include:
- code editor
- file manager
- debugging tools
- terminal
- extensions

---

## What is Visual Studio Code?

Visual Studio Code (VS Code) is one of the most popular IDEs.

Developers use it to write many programming languages including:
- HTML
- CSS
- JavaScript
- Python
- Java
- C++

It is:
- free
- fast
- customizable
- widely used by professional developers

---

## Main Parts of VS Code

When you open VS Code you will see:

### Explorer
Shows your project files and folders.

### Editor
Where you write code.

### Terminal
Where you run commands like Git commands.

### Extensions
Add extra features to VS Code.

---

## Hands-On Activity

1. Open Visual Studio Code.
2. Explore the following areas:
   - Explorer
   - Terminal
   - Editor

Try creating a new file called:

```

test.txt

```

Write one sentence inside it.

---

# Part 3: Connecting VS Code to GitHub

Developers usually connect their IDE to GitHub so they can upload their work easily.

Steps:

1. Open VS Code
2. Sign in to GitHub
3. Clone a repository OR create one
4. Make changes
5. Commit changes
6. Push changes to GitHub

Workflow example:

```

Edit file
↓
git add
↓
git commit
↓
git push

```

This uploads your work to GitHub.

---

## Hands-On Activity

Follow along with the instructor:

1. Open VS Code
2. Connect your GitHub account
3. Open the Source Control tab
4. Look at how commits work

---

# Part 4: Creating Your Portfolio Repository

Today you will create your **first portfolio repository**.

Your portfolio will store your future projects.

---

## Step 1: Create Repository on GitHub

Go to GitHub and click:

```

New Repository

```

Repository name:

```

portfolio

```

Make sure:
- repository is **public**
- initialize with **README**

Then click:

```

Create repository

```

---

## Step 2: Clone Repository to Your Computer

Copy the repository URL.

In VS Code terminal run:

```

git clone <repository url>

```

This will download your repository to your computer.

---

# Part 5: What is Markdown?

Markdown is a **simple way to format text**.

It is often used for:
- README files
- documentation
- project instructions

Markdown uses symbols to style text.

---

## Basic Markdown Syntax

### Headers

```

# Title

## Section

### Subsection

```

Example:

# My Portfolio
## Projects

---

### Bold Text

```

**bold text**

```

Example:

**My Projects**

---

### Bullet Lists

```

* item one
* item two
* item three

```

Example:

- HTML
- CSS
- JavaScript

---

### Links

```

[link text](website url)

```

Example:

```

[GitHub](https://github.com)

```

---

# Hands-On Activity: Write Your First README

Open the file:

```

README.md

```

Add the following:

```

# My Coding Portfolio

Welcome to my coding portfolio.

## About Me

My name is ______.

I am learning how to build websites and apps.

## Skills I Will Learn

* HTML
* CSS
* JavaScript
* GitHub

## Future Projects

* My personal website
* A game
* A useful app

```

---

# Save Your Work

After editing your README:

1. Save the file
2. Stage the changes

```

git add .

```

3. Commit

```

git commit -m "Created portfolio README"

```

4. Push

```

git push

```

Now your portfolio is saved on GitHub.

---

# Wrap Up

Today you learned:

- what Git is
- what GitHub is
- basic Git commands
- what an IDE is
- how to use VS Code
- how to create a repository
- how to write Markdown
- how to create your portfolio README

Next week we will start building **our first website using HTML.**