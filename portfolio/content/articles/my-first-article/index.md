---
title: "Create a portfolio website"
description: "Learn how to create your portfolio website using Gatsby."
date: "2022-11-09"
banner:
  src: "../../images/Portfolio.png"
  alt: ""
categories:
  - "Portfolio"
  - "Tutorial"
keywords:
  - "Example"
  - "Gatsby"
  - "Markdown"
  - "Blog"
---

To build my portfolio website, I have used a Gatsby starter template. [Gatsby](https://www.gatsbyjs.com/docs/glossary/static-site-generator/) is a static site generator that builds HTML pages by compiling data with components. Gatsby has a [starter library](https://www.gatsbyjs.com/starters/) from which you can pick a template of your choice and modify it to fit your needs. The template I chose was from [konstantinmuenster](https://github.com/konstantinmuenster). 

## Before you start

If you're entirely new to version control systems( for example, Git ), IDEs, and command line worlds, as I was a year ago, you need to consider the following:
- a  Git repository so that you can host your website later 
- an IDE to modify the template
- a command line tool to push and commit your change to the remote repository

For the above purposes, I have used the following:

- [GitHub](https://github.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [GitHub Desktop](https://desktop.github.com/)

In addition, you need to download [Node.js](https://nodejs.org/en/) to run a Gatsby project, as Gatsby is built with Node.js. Node.js comes with the npm package manager. Gatsby uses npm to run command line interface(CLI) tasks. 

> **Tip:** If you're a first-timer, [create a GitHub repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository) and [clone it](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) locally.

## Get started
1. Open your repository in IDE and navigate to the terminal.
2. Run the following commands to ensure that node and npm are installed:
   ```node --version``` <br/>
   ```npm --version``` <br/>
3. Run the npm command to install Gatsby CLI.<br/>
    ```npm install -g gatsby-cli```
  You will see a success message that the Gatsby CLI is installed.

## Select your template
1. Go to the [Gatsby starter library](https://www.gatsbyjs.com/starters/).
2. Optionally, filter for portfolio to show only portfolio templates.
3. Click the portfolio of your choice. <br/>
   > **Tip:** You can visit the demo and see what it looks like.
4. Under **Install with gatsby-cli** field, copy the code.

## Build the project
1. Go to your IDE terminal.
2. Paste the template code you copied. <br/>
   > **Tip:** You can change the project's name in the copied code to one of your choice.
3. Run the code. 
   This will install all the Gatsby dependencies you need to run the project.
4. After you get the success message, run the command: <br/>
   ```cd {your project name}```
5. To build the project, run the command:<br/>
   ```gatsby develop```<br/>
    This command builds the website and provides a link to view the website locally.
6. Click the link and view the build.

## Modify the template

You can now go back to the code and modify the project to fill in your details. 
> **Tip:**   If unsure, change some test and run it and see if it works locally. You can also go to the Gatsby starter library, where you found the template, and click the **Source** to take you to the repository. There you will have instructions on how to modify the template.
