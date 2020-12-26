# Web Development Notes for Selected [Treehouse Courses](http://teamtreehouse.com "Link to Treehouse")


#### Created By Paul Brubaker

---

## Table of Contents

* [Dev Tools](#dev-tools)
  * [Markdown Basics](#markdown-basics)
  * [Introduction to Git](#introduction-to-git)
  * [GitHub Basics](#github-basics)
* [Front End Web Development Track](#front-end-web-dev-track)
  * [Introduction to HTML and CSS](#introduction-to-html-and-css)
  * [HTML Basics](#html-basics)
* [Miscellaneous CSS](#miscellaneous-css)
  * [CSS Transitions and Transforms](#css-transitions-and-transforms)
  * [Sass Basics](#sass-basics)
  * [Bootstrap 4 Basics](#bootstrap-4-basics)
  * [SVG Basics](#svg-basics)
  * [Animating SVG with CSS](#animating-svg-with-css)
* [Full Stack JavaScript Track](#full-stack-javascript-track)
* [Learn React Track](#learn-react-track)
* [Security](#security)
  * [OWASP Top 10 Vulnerabilities](#owasp-top-10-vulnerabilities)
  * [Introduction to Application Security](#introduction-to-application-security)
  * [Security Literacy](#security-literacy)
  * [Introduction to Data Security](#introduction-to-data-security)
* [Business](#business-track)
  * [Presentation skills](#presentation-skills)
  * [Researching User Needs](#researching-user-needs)
  * [How to Start a Business](#how-to-start-a-business)
  * [Soft Skills](#soft-skills)
  * [How to Write a Business Plan](#how-to-write-a-business-plan)
  * [How to Freelance](#how-to-freelance)
* [APIs](#apis)
  * [Build a Chatbot With Watson APIs](#build-a-chatbot-with-watson-apis)
  * [Introduction to GraphQL](#introduction-to-graphql)
* [Design](#design)
* [Quality Assurance](quality-assurance)
* [Computer Science](#computer-science)
* [Databases](#databases)











---
---

## Dev Tools
---

### Markdown Basics

#### Escaping characters  

`\\ \* \_ \{ \} \[ \] \( \) \# \+ \- \. \!`  

outputs  

\\ \* \_ \{ \} \[ \] \( \) \# \+ \- \. \!  

`\< \> \&`

\< \> \&  

#### Displaying code  

Use one backtick for code snippets and three backticks for code blocks.

#### Headlines, Paragraphs, and Basic Formatting

##### Headlines

`# Largest Heading`  

# Largest Heading

`###### Smallest Heading`  

###### Smallest Heading  

##### Paragraphs and Line Breaks


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed tempor and vitality, so that the labor and sorrow, some important things to do eiusmod. It also does not suspend lakes sometimes the jaws set. Textile manufacturing bookmark for nutrition research.

To start a second paragraph, we hit enter twice. Here is some more Google Translate Ipsum.

Over time, clinical football carton element. Minneapolis developer undergraduate homework sad a lot more items. Nor is it for the aliquam sem et tortor consequat id. In my drink or football. The mass at tellus. Maecenas a weekend sit still needed. Who recommended that pregnant basketball. The mountains of life, and the mouse, viverra quis, ultricies. Scent like football a lot graduated developers to invest in. Macro hung pull any price.

To get a line break without a space, press space twice at the end of a line before hitting enter.

##### Emphasis and Bolding

###### Italics

`*Asterisks are recommended by Treehouse.*`

*Asterisks are recommended by Treehouse.*

`_But underscores also work._`

_But underscores also work._

###### Bolding

`**Asterisks are the preferred method for GitHub.**`

**Asterisks are the preferred method for GitHub.**

`__But underscores can be used as well.__`

__But underscores can be used as well.__

`***We can create bold plus italicized text like this.*** `

***We can create bold plus italicized text like this.***

`***Or like this.***`

***Or like this.***

##### Blockquotes

`> Nature does not hurry, yet everything is accomplished.
-*Lao Tzu*`

> Nature does not hurry, yet everything is accomplished.
-*Lao Tzu*

#### Numbered lists

```
1. Butternut Squash
2. Sweet Potatoes
3. Carrots
```

1. Butternut Squash
2. Sweet Potatoes
3. Carrots

#### Nested Numbered Lists

```
1. Fruits
  Apples
  Oranges
  Pears
```

1. Fruits
  Apples
  Oranges
  Pears

#### Bulleted lists

```
* Dogs
  * Golden Retriever
  * Blue Heeler
  * Corgi
```

* Dogs
  * Golden Retriever
  * Blue Heeler
  * Corgi

---

### Links

[My GitHub](https://github.com/pbrub "Link to Paul Brubaker's GitHub")

#### Reference Links

```
[Reference Link][1]
[1]: https://github.com/pbrub
```

[Reference Link][1]

[1]: https://github.com/pbrub

#### Images

`[![Image of Kitten](https://placekitten.com/250/400)`

[![Image of Kitten](https://placekitten.com/250/400)]

`[![Image of Kitten](https://placekitten.com/250/400)](https://placekitten.com/ "Link to Place Kitten Website")`

[![Image of Kitten](https://placekitten.com/250/400)](https://placekitten.com/ "Link to Place Kitten Website")

---

### Introduction to Git Course

#### Initializing a Repository

To begin with, navigate into the appropriate project directory (The working directory).  
To initialize the new repository, type `git init`

#### First Commits

There are three states your files in the working directory can be in, modified, staged and committed.

The `git status` command shows what state your files are in.

The `git add` command adds a file to the staging area.

The `git commit -m <commit message>` command saves staged changes to the local repository.

The commit message should complete the phrase "this commit will"

`git log` displays information about each commit.

Use `git log -p` to display which lines were added in each file.

#### Viewing changes to a file

The `git diff` command shows what is different between the staged and modified (or previously committed) versions of your files.

Lines that have been removed will have a minus sign preceding them, and changed lines will have a minus sign preceding the old version and a plus sign preceding the new version.

`git diff --staged` compares staged changes against the previous commit, whereas diff normally compares changes that are not yet staged against changes that are already staged.

#### Removing files

To remove a file from your git repository, use `git rm <filename` and then commit your changes. Git will also remove the file in question from the working repository.

#### Moving files

Use `git mv <source> <destination>`, then commit the change.

#### Unstaging Changes

To unstage changes to a file, use `git reset HEAD <filename>`

#### Discarding file modifications

To revert a file to the last committed version, use
 `git checkout -- <filename>`

#### Undoing file deletions

As before, use `git checkout -- <filename>` to undo changes that were made to the file (in this case, undoing the deletion of the file).

#### Undoing commits with SHA1 checksums

The SHA1 checksum is a 40 character string that uniquely identifies each commit, and you can access them with `git log`

To revert the changes made by a specific commit, use
`git revert <SHA1 string>`
(You can also just use the first five or six characters of the SHA1 string.)

To revert the most recent commit, we can use `git revert HEAD`

#### Cloning a repository

A repository stored on one's own machine is referred to as a local repository, while a repository stored on someone else's machine is called a remote repository.

To clone a repository to one's local machine, use `git clone <source> <destination>`

#### pulling commits

`git remote` prints a list of linked repos

The default name for a linked remote repository is origin (The repository that was originally cloned from).

From in the directory of the repository you want to pull to, use
`git pull <source>` or omit the argument to pull from the default remote repo (typically origin).

#### Adding remotes

To set up a repository as a remote (linked) repository, use
`git remote add <name of remote> <URL of remote>`













---

### GitHub Basics

---
---

## Front End Web Dev Track

---

### Introduction to HTML and CSS

*contents:*

* [The Basic Structure of a Web Page](#the-basic-structure-of-a-web-page)
* [Image Tags](#image-tags)
* [Paragraph Tags](#paragraph-tags)
* [Anchor Tags](#anchor-tags)
* [HTML Lists](#html-lists)
* [Select and Style by Element](#Select-and-style-by-element)
* [Select and Style by Class](#)
* [Outside Resources](#intro-to-html-and-css-outside-resources)

#### The basic structure of a web page

HTML, standing for hypertext markup language, is the language that defines the basic structure of a Webpage.
The structure of a web page is nested, with the outermost layer being indicated by the **tag** `<html></html`. Some html tags are self closing, but most must consist of an **opening tag** and **closing tag**, with the closing tag being indicated by a forward slash. Outside of the html tag goes the **doctype** tag, which tells the browser that this is an HTML document, and within the html tag go the **head** and **body** tags. Typically, a web pages content will be comprised of **header**, **main**, and **footer**, but these tags are technically optional.

```
<!doctype html>
<html>
  <head>
    head content (information about the web page for the browser)
  </head>
  <body>
    <header>
      (introductory information, site name, logo, navigation bar, etc.)
    </header>
    <main>
      (content of main area of page)
    <main>
    <footer>
      (copyright info, social media links, secondary nav, etc.)
    <footer>
  </body>
</html>
```

#### Image tags

The image tag requires two **attributes**, the **source attribute** and the **alt attribute**. The source attribute provides the path or URL to the image, and the alt attribute provides an alternate description of the image. The image tag is **self closing** (Also called an empty element).

```HTML
<img src="images/example.png" alt="description of image">`
```

#### Paragraph tags

Paragraph tags enclose blocks of text.

```HTML
<p>
  A block of text goes here.
</p>
```

#### Anchor tags

Anchor tags turn whatever is inside them into a link. The **href attribute** defines the destination of the link. Href stands for hypertext reference. Anchor tags can create links to another part of the page, another page, or another Website.

To create a link to the top of the page, we can us
 ```HTML
 <a href="#top"> (link, which can be text or an image) </a>
 ````

Adding the
```HTML
target="_blank"
```
attribute will cause the browser to open a new tab when the link is clicked, leaving the current page open.

#### HTML Lists

Lists can be either ordered or unordered, and are created by nesting **list item tags** within the ul or ol list tags.

```HTML
<ul>
  <li> (First list item) </li>
  <li> (First list item) </li>
  <li> (First list item) </li>
</ul>
```

#### Select and Style by Element

CSS, which stands for **Cascading Style Sheets**, determines the look of a Webpage. A block of CSS is called a **CSS rule**. Rules select can tags on an HTML page in a variety of ways, and style whatever is within those tags. CSS rules that are listed lowest in the style sheet overrule any conflicting tags that are listed above them, thus the name Cascading. **CSS properties**, which are listed within the CSS rules, change how the browser displays whatever tag(s) are selected by that rule. Built in tags are can be selected by the name of that tag, styling all tags of that type. Every CSS rule begins with a **selector**.

```CSS
body {
  margin: 0;
  padding: 0;
  text-align: center;
  font-family: 'Roboto', sans-serif;
  color: #222;
  background:  #f7f5f0;
}
```

#### Select and Style by Class

CSS classes are developer-defined labels used to apply the same styling rule to any HTML element which has been assigned that class. **Class selectors begin with a dot**. In general, classes should describe something about the identity or characteristics of the element they are assigned to. There are many ways to select elements with CSS, and many CSS properties that can be modified with CSS Rules. For a long list of selectors and properties, a useful resource is the [CSS-Tricks][1] Website.


#### Intro to HTML and CSS Outside Resources
* [*css-tricks*][1]

[1]: https://css-tricks.com/almanac

---

### HTML Basics

*contents*

* [What is HTML?](#what-is-html)
* [Global structure of an HTML Document](#global-structure-of-an-html-document)
* [HTML Basics Outside Resources](#html-basics-outside-resources)

#### What is HTML?

HTML stands for **Hypertext Markup Language**. Text that can be displayed on a document online is called hypertext, and the documents containing that text and linking to other documents are called hypertext, with the links being called **hyperlinks**.

**Markup** is the coded text written by the developer that instructs the browser on  what to display on a Webpage.

In Short, HTML is the language of the Web.

#### Global Structure of an HTML Document

Every HTML document must begin with a doctype declaration, so the browser knows which version of HTML the page is using. After that, the `<html></html>` tags enclose everything that is HTML code. The `<head></head>` and `<body></body>` tags are the remaining two mandatory tags. The head tags enclose special instructions for the browser, such as a title to be displayed in the browser's title bar, while any content to be displayed on the Webpage is **nested** within the body tags.

#### HTML Basics Outside Resources

* [MDN HTML Element Reference][2]

[2]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element



---
---

## Miscellaneous CSS

---
---

## Full Stack JavaScript Track

---
---

## Learn React Track

---
---

## 21st Century Skills

---
---

## Security

---
---

## Business

---
---

## APIs

---
---

## Design

---
---

## Quality Assurance

---
---

## Computer Science

---
---

## Databases
