---
title: "How to Create your first website on GitHub Pages"
description: "GitHub Pages are public web pages for users, organizations, and repositories, that are freely hosted on GitHub’s github.io domain Once you’ve signed in, you’ll create a new repository to get started…"
date: "2019-05-02T18:23:48.101Z"
categories: 
  - Github
  - Github Pages

published: true
canonical_link: https://medium.com/@bawantharathnayaka/how-to-create-your-first-website-on-github-pages-a8d65d6f8396
redirect_from:
  - /how-to-create-your-first-website-on-github-pages-a8d65d6f8396
---

![](./asset-1.png)

**What is Github page**

_GitHub Pages_ are public web pages for users, organizations, and repositories, that are freely hosted on GitHub’s github.io domain

1.  First you log into your Github account

![](./asset-2.png)

Once you’ve [signed in](https://github.com/login), you’ll create a new repository to get started and you need to give this repository a special name to generate your website.

![](./asset-3.png)![](./asset-4.png)

### Now open your git bash terminal.

Next go to the folder where you want to store your project, and clone the new repository this command

> **git clone** [**https://github.com/_username_/_username_.github.io**](https://github.com/username/username.github.io)

### Now create the index.html file in folder use this command

> **cd _username_.github.io**

> **echo “Hello World” > index.html**

### And Push it

> git add — all

> git commit -m “Initial commit”

> git push -u origin master

Now go to the your repo settings tab and scroll down you’ll see the **GitHub Pages** section near the bottom and select the master brance and save it

![](./asset-5.png)

### Now your Done!

**Fire up a browser and go to** [**https://_username_.github.io/repositoryname**](https://username.github.io)
