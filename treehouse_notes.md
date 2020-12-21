# Web Development Notes for Selected [Treehouse Courses](http://teamtreehouse.com "Link to Treehouse")


#### Created By Paul Brubaker

---

## Table of Contents

* [Dev Tools](#dev-tools)
  * [Markdown Basics Course](#markdown-basics-course)
  * [Introduction to Git Course](#introduction-to-git-course)
  * [GitHub Basics Course](#github-basics-course)
* [Front End Web Development Track](#front-end-web-dev-track)
* [Miscellaneous CSS](#miscellaneous-css)
  * [CSS Transitions and Transforms](#css-transitions-and-transforms-course)
  * [Sass Basics](#sass-basics-course)
  * [Bootstrap 4 Basics Course](#bootstrap-4-basics-course)
  * [SVG Basics Course](#svg-basics-course)
  * [Animating SVG with CSS](#animating-svg-with-css-course)
* [Full Stack JavaScript Track](#full-stack-javascript-track)
* [Learn React Track](#learn-react-track)
* [Security](#security)
  * [OWASP Top 10 Vulnerabilities](#owasp-top-10-vulnerabilities-course)
  * [Introduction to Application Security](#introduction-to-application-security-course)
  * [Security Literacy](#security-literacy-course)
  * [Introduction to Data Security](#introduction-to-data-security-course)
* [Business](#business-track)
  * [Presentation skills](#presentation-skills-course)
  * [Researching User Needs](#researching-user-needs-course)
  * [How to Start a Business](#how-to-start-a-business-course)
  * [Soft Skills](#soft-skills-course)
  * [How to Write a Business Plan](#how-to-write-a-business-plan-course)
  * [How to Freelance](#how-to-freelance-course)
* [APIs](#apis)
  * [Build a Chatbot With Watson APIs](#build-a-chatbot-with-watson-apis-course)
  * [Introduction to GraphQL](#introduction-to-graphql-course)
* [Design](#design)
* [Quality Assurance](quality-assurance)
* [Computer Science](#computer-science)
* [Databases](#databases)











---
---

## Dev Tools
---

### Markdown Basics Course

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

#### Creating a repository on GitHub

























---

### GitHub Basics Course

---
---

## Front End Web Dev Track

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
