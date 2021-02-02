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
  * [CSS Basics](#css-basics)
  * [JavaScript Basics](#javascript-basics)
  * [JavaScript Functions](#javascript-functions)
  * [JavaScript Loops](#javascript-loops)
  * [JavaScript Arrays](#javascript-arrays)
  * [JavaScript Objects](#javascript-objects)
  * [JavaScript and the DOM](#javascript-and-the-dom)
  * [Bootstrap 4 Basics](#bootstrap-4-basics)
  * [AJAX Basics](#ajax-basics)
  * [CSS Selectors](#css-selectors)
  * [CSS Layouts](#css-layouts)
  * [Mobile First CSS Layout](#mobile-first-css-layout)
  * [CSS Flexbox](#css-flexbox)
  * [CSS Grid](#css-grid)
  * [HTML Forms](#html-forms)
  * [HTML Tables](#html-tables)
  * [Accessibility for Web Developers](#accessibility-for-web-developers)
* [Miscellaneous CSS](#miscellaneous-css)
  * [CSS Transitions and Transforms](#css-transitions-and-transforms)
  * [Sass Basics](#sass-basics)
  * [Bootstrap 4 Basics](#bootstrap-4-basics)
  * [SVG Basics](#svg-basics)
  * [Animating SVG with CSS](#animating-svg-with-css)
* [Full Stack JavaScript Track](#full-stack-javascript-track)
* [Learn React Track](#learn-react-track)
  * [React Basics](#react-basics)
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
* [Select and Style by Class](#select-and-style-by-class)
* [Resources](#intro-to-html-and-css-resources)

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


#### Intro to HTML and CSS Resources
* [*css-tricks*][1]

[1]: https://css-tricks.com/almanac

---

### HTML Basics

*contents:*

* [What is HTML?](#what-is-html)
* [Global structure of an HTML Document](#global-structure-of-an-html-document)
* [Paragraphs and Headings](#paragraphs-and-headings)
* [Creating Lists](#creating-lists)
* [Creating Links](#creating-links)
* [Semantic HTML](#semantic-html)
* [Sectioning Content With Article, Nav, and Aside](#sectioning-content-with-article-nav-and-aside)
* [Grouping Content with \<main\> and \<div\>](#grouping-content-with-main-and-div)
* [Adding and Captioning Images](#adding-and-captioning-images)
* [Creating Breaks in Content](#creating-breaks-in-content)
* [Add Meaning to Words With Text Level Elements](#add-meaning-to-words-with-text-level-elements)
* [Linking to Sections of a Webpage](#linking-to-sections-of-a-webpage)
* [Link to Email](#link-to-email)
* [HTML Entities and Reserved Characters](#html-entities-and-reserved-characters)
* [HTML Basics Resources](#html-basics-outside-resources)

#### What is HTML?

HTML stands for **Hypertext Markup Language**. Text that can be displayed on a document online is called hypertext, and the documents containing that text and linking to other documents are called hypertext, with the links being called **hyperlinks**.

**Markup** is the coded text written by the developer that instructs the browser on  what to display on a Webpage.

In short, HTML is the language of the Web.

#### Global Structure of an HTML Document

Every HTML document must begin with a doctype declaration, so the browser knows which version of HTML the page is using. After that, the `<html></html>` tags enclose everything that is HTML code. The html element is known as the **root element**. The `<head></head>` and `<body></body>` elements are the remaining two mandatory elements. The [head][4] tags enclose special instructions for the browser, such as a title to be displayed in the browser's title bar, while any content to be displayed on the Webpage is **nested** within the body tags.

#### Paragraphs and Headings

Heading tags are specified with an h followed by a number 1 through 6, with 1 being the largest heading and 6 being the smallest. Paragraphs are specified with the letter p.

```HTML
  <h1>The Largest Heading goes here</h1>
  <p>Some text goes here here</p>
```

#### Creating lists

There are three types of HTML lists, **ordered lists**, **unordered lists**, and **description lists**. List items are placed within the list item tag. Unordered list are displayed with bullet points, ordered lists with their corresponding numbers, and description lists with the term in bold and the description indented below.

```HTML
Ordered List:
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>

Unordered list:
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

Descrption List:
<dl>
  <dt>Item 1</dt>
  <dd>Description of item 1</dd>

  <dt>Item 2</dt>
  <dd>Description of item 2</dd>
</dl>
```

#### Creating links

Links are created with **anchor tags**, denoted by the letter a. Everything between the opening and closing anchor tags is turned into a link. Links can connect to another page on the same Website, a different Website, a different place on the same page, or even begin composing an email in the user's default email program.

The **href attribute** tells the browser where to navigate to when the link is clicked. Href stands for hypertext reference. It can be a URL or a file path. Attributes, written inside the opening tag of an HTML element, provide the browser with information about that specific element. An attribute is followed by an equals sign and the value assigned to the attribute is enclosed in quotes following the equals sign.

The **target _blank attribute** causes the browser to open the page being linked to in a new tab rather than navigating away from the current page.

```HTML
<a href="https://github.com/pbrub" target="_blank"> Link goes here </a>
```

#### Semantic HTML

Basically, semantic markup means that the meaning of the HTML being written should be self-evident from the way it is written. Semantic markup is important for a variety of reasons, such as search engine performance, accessibility, and code maintainability. This means using tags that make sense with the content that is being displayed.

Some important semantic HTML tags are **header**, **main**, **footer**, and **section**, their meaning being fairly obvious.

#### Sectioning Content With Article, Nav, and Aside.

The article tag is used to separate content that stands on its own in some way, such as a blog entry, news article, or recipe. The `<nav></nav>` tag contains a list of navigation links, and is often found in the header or footer.

The `<aside></aside>` tag is used for content that is loosely related to the main content of the page, but is not necessary to understand it. Visually, this content may be represented separately, such as in a sidebar. Keep in mind that semantic tags do not directly cause the browser to display the content within them in a different way, but they do change the way the pages content is interpreted by search engines and assistive technologies such as screen readers.

#### Grouping Content With Main and Div

The `<main></main>` tag identifies the area where the main content of the page will reside. Main should only be used once per page.

The `<div></div>` tag is used for content that does not clearly fall under the umbrella of any more semantic tag.

#### Adding and Captioning Images

The `<image></image>` tag is used to add images to a page. The image tag needs a `src` attribute that points to the file path of the image. The `alt` attribute, while not needed to make the image tag work, should be included and provides a description of the image.

To include a captioned image or group of images, wrap the `<img>` and `<figcaption>` tags within the `<figure></figure>` tag.

#### Creating Breaks in Content

To force a line break in HTML without creating another div, use the `<br>` empty element where you want the line break to be.

To add a horizontal line separating content, use the `<hr>` empty element between the two elements you want to separate.

Empty elements are sometimes written with a trailing slash to clearly indicate that they are self closing.

It is important to remember that these elements are used to logically group content in HTML documents and CSS should be used instead if the intent is aesthetics.

#### Add Meaning to Words With Text Level Elements

The `<strong>` tag indicate a piece of text is especially important, and is typically displayed in bold by the browser. The `<small>` tag does the opposite. The `<em>` tag indicates there is extra emphasis on the text, and is displayed in italics by default.

The `<span>` element is used like the div element, but for **inline** content rather than **block** content. This makes it an **inline element** rather than a **block level element**.

#### Linking to Sections of a Webpage

To link to one part of a Webpage from another, add an `id` attribute to the element to be linked to, and set the href attribute of the anchor element to the ID preceded by a hash symbol.

`<div id="destination">content</div>`
`<a href="filepath#destination">link</a>`

#### Link to Email

To create a link that opens the user's default email program with the to and from fields already filled out, use the following:

`<a> href="mailto:emailaddress"link</a>`

To add a subject to the subject field of the email, follow the email address with a question mark and then the subject parameter, an equals sign, and the subject to be displayed.

`<a> href="mailto:emailaddress? subject=Hello!"link</a>`

#### HTML Entities and Reserved Characters

To escape characters in HTML code, write an ampersand, then the character code, then a semicolon.

[List of character entities][5]

#### Adding Developer Notes With HTML Comments

Comments are ignored by the browser and are written as follows

```HTML
<!-- comment -->
```

Comments are commonly used to indicate where sections of a page start and end in HTML code.


#### HTML Basics Resources

* [MDN HTML Element Reference][2]

[2]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element

* [HTML in Visual Studio Code][3]

[3]: https://code.visualstudio.com/docs/languages/html

* [What's in the Head? Metadata in HTML (MDN)][4]

[4]: https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML

* [Character entities for escaping reserved characters][5]

[5]: https://dev.w3.org/html5/html-author/charref

---

### CSS Basics

*contents*

* [Inline and Internal styles](#inline-and-internal-styles)
* [External Style Sheets](#external-style-sheets)
* [Importing Style Sheets](#importing-style-sheets)
* [Selectors](#selectors)
* [Pseudo Classes](#pseudo-classes)
* [Data Types and Units](#data-type-and-units)
* [Color Values](#color-values)
* [Text Styles](#text-styles)
* [Font Properties](#font-properties)
* [Line Height](#line-height)
* [The Box Model](#the-box-model)
* [Display Values](#display-values)
* [Width and Height Properties](#width-and-height-properties)
* [Backgrounds](#backgrounds)
* [Floats](#floats)
* [List Styling](#list-styling)
* [Enhancing the Design With CSS](#enhancing-the-design-with-css)
* [Using a Web Font](#using-a-web-font)
* [Media Query Basics](#media-query-basics)
* [CSS Resources](#css-resources)


#### Inline and Internal Styles

If no style sheet is provided by the developer, browsers use what is called a **user agent style sheet** to style the page. These style sheets may vary ever so slightly from browser to browser, but the page should have the same basic look.

Developer provided styles are called **author styles**. The three ways of providing author styles to a page are **inline styles**, **internal styles**, and **external style sheets**.

Example of an inline style:

```
<body style="background-color: orange">
```

Inline styles are generally not considered good practice, and should be used sparingly or only in special circumstances. Inline styles take the highest level of precedence of all CSS styles (they are at the bottom of what is called the **CSS cascade**). This means they override all other styles applied higher up the cascade.

**Internal style sheets are defined inside the head element of an HTML document, using the <style></style> tag.

Example of an internal style sheet:
```HTML
<head>
  <style>
    p {
      font-size: 20px;
      font-weight: bold;
    }
    h1 {
      font-size: 90px;
      color: firebrick;
    }
  </style>
</head>
```

Internal style sheets are also generally not considered good practice because the browser must download the styles each time a new page is loaded, and the styles must be repeated for each different page.

#### External Style Sheets

External style sheets are the preferred way to add styles to an HTML document.

Styles from external style sheets are added to an HTML document using the `<link>` tag within the `<head>` tag. The **rel attribute** tells the browser that the document being linked to the HTML document is a stylesheet. The href attribute points to the filepath of the document being linked to as usual. This link tag is self-closing.

```HTML
<head>
  <link rel="stylesheet" href="css/styles.css">
</head>
```

#### Importing Style Sheets

Another way to include a stylesheet is with a CSS import statement.

Keep in mind that importing many style sheets can affect Website's performance by increasing load time.

```HTML
<style>
  @import "filepath";
</style>
```

#### Selectors

CSS selectors tell the browser which HTML elements to apply a CSS rule to. There are a variety of different kinds of selectors, the most powerful being the **universal selector**, specified with an asterisk.

Here is the syntax for writing a CSS rule:

```CSS
selector {
  property: value;
}
```

**Type selectors**, also known as **element selectors**, select every HTML element of the specified type on the page by only using an element's tag name as the selector. Examples of type selectors could be the paragraph tag p or the anchor tag a.

```CSS
a {
  color: blue;
}

p {
  font-size: 20px;
}
```

**ID selectors** select a single element by specifying its unique ID assigned to it by the developer. Remember that rules with ID selectors will override all other rules.

```CSS
#ID {
  property: value;
}
```

**Class selectors** are useful for targeting specific elements, but more than one of them at a time, unlike ID selectors. Class selectors begin with a dot. Class is a CSS attribute, defined within the opening tag of an element like any other attribute. Class names should be meaningful, identifying something that all elements with that class have in common.

```CSS
.class {
  property: value;
}
```

We can assign more than one class to an element at once, or a classes plus an ID.

```HTML
<div class="class1 class2"></div>
```

**Descendant selectors** target elements based on their relationship in the HTML document.  The ancestor is written first, followed by a space and then the descendant. The descendant tag is the one targeted by the rule, but only tags which are descendants of the specified ancestor will be targeted.

```CSS
ancestor descendant {
  property: value;
}
```

Descendant selectors are useful for being more specific with the elements we target, but more specificity comes with a cost of less reusability.

#### Pseudo Classes

> A CSS pseudo-class is a keyword added to selectors that specifies a special state of the element to be selected. For example *:hover* will apply a style when the user hovers over the element specified by the selector.
-[MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)

```CSS
selector:pseudo-class {
  property: value;
}
```

Pseudo classes are useful for styling elements dynamically based on factors that are independent of the document's content. (like user interaction for example)

Pseudo-classes can belong to several different categories:

* Linguistic
* Location
* User action
* Time dimensional
* Resource state
* Input
* Tree structural

#### Data Types And Units

CSS data types can be described roughly as the different categories that CSS values fall into, for example **integer** or **color**. It is helpful to understand data types when deciding what values to use with our CSS properties.

Units provide dimensional meaning to our CSS values. Some examples of common units are **pixels** and **rems**. While data types are implicit in CSS code, units must be described explicitly, or else the default unit will be used, or the browser will not know how to interpret the CSS code provided. Units are written immediately after the value without a space.

Units can be either **relative** or **absolute**, with the effect of relative units on an element's appearance being dependent on a parameter defined elsewhere in the CSS code and the effect of absolute units being independent of all other parameters.

The **px** unit used to represent one pixel on a device's screen, but now that high definition screens are commonplace, the px unit is relative to the pixel density of the viewing device. The important thing to remember is that the pixel unit will appear just about the same size relative to the viewport across all browsers and viewing devices, and the pixel unit will not scale with the size of the window. This means the pixel unit is technically considered an absolute unit.

**Percentage** units in CSS are measured relative to their parent element's length.

The length of the **em** unit is calculated based on the parent element's font size. To be precise, 1 em is equal to the font size of the parent element. The default font size of the `<html>` element is 16px. Using em units can create difficulties with compounding effects.

A good way to avoid these troublesome compounding effects is to use the **rem** unit, 1 rem being equal to the value of the font size in pixels of the root element (typically 16px by default). This avoids the headache of keeping track of nested calculations while still keeping length relative to the size of the viewing window.

[CSS data types MDN reference][10]

#### Color Values

The three most common ways to specify a color value with CSS are **keywords**, **hexadecimal values**, and **RGB functions**. Keywords and RGB functions are really just more intuitive ways of expressing a hexadecimal color value. There are 256^3 (16,777,216) possible unique colors that can be specified with CSS, but a handful of these come with conveniently predefined keywords that describe the color's appearance, such as *tomato* or *lightblue*.

[Predefined color values MDN reference][11]

Hex color values are written as `#RRGGBB`

A higher number for red, green, or blue means that the overall color contains more of that respective color, so `#000000` is black and `#ffffff` is white, `ff0000` is red and so on.

RGB functions are written as `rgb(R, G, B)`, with parameters for each color being an integer from 0 to 255. This is simply a more intuitive way to express the same integer values for those uncomfortable with hex notation.

RGB functions can be used with a fourth parameter, the **alpha** value, which specifies the opacity of the color via the **alpha channel** and is written as a decimal number.

`rgba(255, 0, 255)` would then be purple color with medium opacity.

#### Text Styles

In CSS code, text styles are defined with properties. Many of these properties have keyword values, such as

```CSS
p {
  text-align: left;
}
```

Some other common text styles are

* `text-transform`
* `text-decoration`
* `font-weight`

#### Font Properties

The `font-family` property specifies the font of the selected text.

Since not all fonts are necessarily available to all users, what are called **web-safe fonts** are assigned as fallbacks in case the user does not have the first choice of font installed on their computer. A **font stack** is written as a comma separated list of fonts, with the highest priority fonts listed first, and a web-safe font at the end of the list.

[A collection of web-safe fonts][12]

**Web fonts** are fonts that are downloaded by the user's browser when the page loads, so they are guaranteed to work in newer browsers with support for web fonts, but can have a detrimental effect on page load time.

Font names that consist of more than one word must be enclosed in quotes.

The `font-style` property is used to make text italic or oblique, but oblique is less common.

#### Line Height

The `line-height` property determines the amount of vertical space between lines of text. This property can accept a unit-less number, pixel, or percentage value, or a relative unit like ems or rems. It is typically best practice to use a unit-less number, which is multiplied by the calculated default line height to yield the new line height.

Font-weight, font-size, font-family and line-height can be specified all at once with the shorthand

`font: weight size/height family`

#### The Box Model

The box model describes how much space each HTML Element takes up on the page. Boxes can be adjacent to each other, or nested within one another. **Padding, **borders**, and **margins** are the three major components of the box model.

The **display value** of an element can be **block**, **inline**, or the hybrid **inline block**. Typically, elements have a default display value of either inline or block.

A block element takes up the full width of its parent element, and creates a new line before and after the element. Inline elements, on the other hand, take up only as much width as needed and do not create a new line.

For each box in the box model, the innermost sub-box is the content area, then the padding area, then the border area. The margin area is the amount of extra space around the box that other boxes must stay out of.

**Padding** can be applied with the shorthand

`padding: 100px 120px`

for example, which applies 100 pixels of padding to the top and bottom of the element's content and 120 pixels to the left and right, or each side can be specified individually, or a uniform padding can be applied with a single parameter. When four parameters are supplied with shorthand notation the values are assigned clockwise from top.

When assigning padding values as percentages, the length is calculated relative to the width of the container, not the height, for top and bottom padding as well as left and right.

**Border properties** are specified in a similar way to padding.

The `border-width` property determines the thickness of a border. If no width is specified, the border will have no width and not be visible.

The `border-style` property gives the border its appearance, for example solid, dashed or dotted. If no style is specified, the border will not be visible.

`border-color` is another commonly used border property. If no border color is specified, the border will be the same color as the text of that element.

The border color, style and width properties can be specified using shorthand in any order and the browser will interpret them correctly, but it is good practice to use the same order for code consistency and readability.

The **margin property** is defined using the same clockwise shorthand as border and padding. Remember that margin is applied outside of the outside edge of the border. Giving the margin property the value **auto** centers the element horizontally within its parent container by having the browser divide the space not taken up by the element equally.

#### Display Values

As mentioned before, the most common display values in CSS are block, inline and inline-block. Some examples of **block level elements** are `<div>` and `<p>`, and some examples of inline elements are `<span>` and `<image>`, and `<a>`.

Block level elements take up the entire width of their parent element, and as much vertical space as necessary.

Top and bottom margin values have no effect on inline elements. However, inline-block elements are allowed to have top and bottom margins.

#### Width and Height Properties

By default, elements are as wide and as tall as their content, but we can force them to take on arbitrary dimensions with the width and height properties.

The width and height properties accept either relative or absolute length units as values.

By default, The height property applies to the content of an element, and any padding or margin adds extra space beyond the height. The same is true of the width property.

#### Box Sizing and Max Width

The **box sizing** property alters the way the total height and width of a box are calculated.

The value **border-box**, when provided to the box-sizing property, causes the borders and padding to be included in the calculated box size of the element rather than adding to it.

It is common to declare box sizing at the beginning of a stylesheet using the universal selector, thus making it the default behavior.

#### Backgrounds

In every an element, everything but the margin is part of the **background layer**. Background layers are transparent by default, meaning they are not visible.

Some common background properties are `background-color`, `background-size`, `background-image`, and `background-repeat`.

 Background images are set with the syntax

 ```CSS
selector {
  background-image: url('filepath')
}
 ```

By using the `background-size` and `background-repeat` properties together, we can set the tiling behavior of the background image.

We can also alter the position of the background image within the element with the `background-position` property. This property can take one parameter or two, and if only one is given that parameter will be applied horizontally and the image will be centered vertically. These values can be keywords, or relative or absolute length units.

These five background properties can be written with shorthand similar to the border properties shorthand.

```CSS
selector {
  background: color image repeat position / size
}
```

#### Floats

Floated elements are removed from the normal flow of the page and placed along the left or right side of their container.

If a block element contains floated children, its height collapses.

This can cause adjacent elements to start wrapping around the floated elements. This problem can be resolved with a **clearfix**.

Basically what a clearfix does is cause the element with the floated children to stretch to accommodate their height.

Here is a sample clearfix

```CSS
.group::after {
  content: "";
  display: table;
  clear: both;
  }
```

#### List Styling

The `list-style-type` property is used to change the look of lists from their default appearance. Their are many values to choose from for this property.

The `list-style-position` property allows us to change the list style marker from its default location (outside the list item element and to the left).

#### Enhancing the Design With CSS

CSS 3 provides a number of newer features that can be used to spice up our designs with some fancy finishing touches such as...

* **Text Shadows**
   The `text-shadow` property does just what it sounds like it does, giving text a drop shadow making it look like light is coming from the top left by default. The syntax is as follows:
<br>
   ```CSS
   selector {
     text-shadow: x-offset y-offset blur-radius color;
   }
   ```

   The color value defaults to the text color and the blur radius defaults to 0. The offsets can be set to a negative value to change the position of the shadow.

   Multiple text shadows can be layered for interesting effects placing them in a comma separated list.
<br>
* **Box Shadows**
  The `box-shadow` property is similar to the `text-shadow` property, except it is used to cast a shadow off an elements containing box rather than the text within it.  
  The syntax of the `box-shadow` property is similar to that of `text-shadow`, except it takes an optional fourth parameter called the **spread** value. This value changes the size of the shadow, how far it spreads out in all four directions. Box shadows that overlap adjacent elements are displayed behind them. Spread values may also be negative, contracting the shadow.

  The optional `inset` parameter can be declared first to make the box shadow an inner shadow.
<br>
* **Border Radius**
  The border radius property allows the creation of rounded corners on HTML elements. For each corner given a radius, imagine a point inset from the nearest sides by the radius length, and then a line of that length rotating to draw out the new corner. Therefore, specifying a `border-radius` of 50% will turn the element into a circle. (If the element is not a square, an ellipse)  

  The `border-radius` property shorthand is written as follows:  
<br>
  ```CSS
  selector {
    border-radius: top-left top-right bottom-right bottom-left;
  }
  ```

* **Gradients**
  Gradients create a smooth, constant transition between two or more colors.

  The syntax for setting a gradient is:

  ```CSS
  selector {
    background-image: linear-gradient(to direction colors);
  }
  ```
  The colors are listed in the `linear-gradient` function in the order they are to appear in the image from top to bottom by default if no direction is specified. We can specify an angle value with `deg`. Zero degrees represents bottom to top and the angle proceeds clockwise. `radial-gradient` creates a gradient that starts from a center point and proceeds outwards. We can add the `circle` keyword before the color values for the `radial-gradient` property to override the default elliptical shape of the gradient. We can also add the `at direction` keyword to specify where the gradient originates.
  <br>
  We can add a **color stop** percent value after any color in a gradient function in order to tell the browser where that color's hue should be at 100%. These percent values can be more than 100% or less than 0%. We can also use `transparent` with a percentage value as a color.

#### Using a Web Font

We can use an `@font-face` CSS rule to import a web font for use on our pages.

Different browsers may only support certain file formats for font files, and the aforementioned rule allows us to link to multiple file formats at once.

Here is an example of how to use the `@font-face` rule. Keep in mind that the files pointed to in the rule must exist at the place specified by their respective paths. The `font-family` property takes an arbitrary name as an argument and that name is used to refer to this font hereafter.

[Font Squirrel, a Resource For Free Web Fonts][13]

#### Media Query Basics

Media queries are CSS rules used to differentiate which styles will be used based on the size of a users viewport.

A media query first specifies a condition that must be met, and if that condition is true, the styles within the media query are applied. If not, they are ignored.

The syntax for media queries is:

```CSS
@media media type (property: value) {
  selector {
    property: value;
  }
}
```

For example, the properties defined in the following media query only take effect when the `max-width` of 960 pixels is not exceeded. Note that the media type `all` is the default when none is specified.

```CSS
@media (max-width: 960px) {
    body {
      background: royalblue;
    }
    p {
      color: white;
    }
  }
```

We can write multiple media queries to create **breakpoints**. The idea behind breakpoints is that the user will always be shown a layout that is optimal for their viewport size, eg. phone, tablet, small monitor or large monitor.

We can also join multiple conditions within one media query with the `and` keyword to create a size range.

Media queries can be made quite complex, but the most important thing is to differentiate between how your website will be displayed on desktop vs mobile devices.

#### CSS Resources

* [MDN Web Docs][6]

[6]: https://developer.mozilla.org/en-US/docs/Web/CSS

* [WebPlatform Docs][7]

[7]: https://webplatform.github.io/docs/css/

* [W3C][8]

[8]: https://www.w3.org/Style/CSS/Overview.en.html

* [Can I Use][9]

[9]: https://caniuse.com/

* [CSS Data Types][10]

[10]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Types

* [Predefined color values MDN reference][11]

[11]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

* [A collection of web-safe fonts][12]

[12]: https://www.cssfontstack.com/

* [Font Squirrel, a Resource For Free Web Fonts][13]

[13]: https://www.fontsquirrel.com

---

### JavaScript Basics

*contents*:
* [Hello JavaScript](#hello-javascript)
* [Intro to JavaScript Variables](#intro-to-javascript-variables)
* [Intro to JavaScript Strings](#intro-to-javascript-strings)
* [JavaScript Conditional Statements](#javascript-conditional-statements)
* [Working With Numbers in JavaScript](#working-with-numbers-in-javascript)



#### Hello JavaScript

What makes JavaScript special is that it can run in the web browser, and is the de-facto language worldwide for adding advanced functionality and interactivity to web pages.

We can experiment with JavaScript by using the **JavaScript console** in our web browser's developer tools.

We signal the end of a line of code in JavaScript by typing a semicolon.

Code blocks are enclosed within curly braces, and function arguments within parentheses.

Whitespace is ignored JavaScript.

To run some JavaScript on our web page, we enclose it in `<script></script>` tags. Script has a source attribute pointing to the location of the JavaScript file to be executed. The script tags should be placed just before the closing body tag, although the JavaScript will still run if it is placed elsewhere.

#### Intro to JavaScript Variables

The most common way to **declare** a **variable** in JavaScript is with the `var` **keyword**. Variables need not be **initialized** when we declare them. To **initialize** or **assign a value** to variable, we use the `=` operator.

```JS
var <variable name> = <variable value>
```

**Camel case** is the preferred style for multi-word variable names in JS.

JavaScript allows the following shorthand for variable reassignment, called the **addition assignment operator**.

```JS
<variable name> = <variable name> + <value>

is equivalent to

<variable name> += <value>
```

The `const` keyword is used to declare **constants**, variables whose value may not be reassigned. Redeclaration of constants is also not allowed.

The `let` keyword is used to declare a variable whose value can be reassigned, but does not allow redeclaration within the same code block.

 There are differences in **scope** with each of these keywords that will be covered later.

#### Intro to JavaScript Strings

The **string** **data type** is written by enclosing characters within quote marks (single or double, single being preferred).

It is common to enclose HTML code within quotes (causing the **JavaScript engine** to treat it as a string) in order to render HTML elements dynamically on a web page.

It is acceptable to enclose a string in double quotes in order to avoid escaping single quotes within said string.

The `\` character is used to escape characters within strings.

**Multi-line strings** can be written by ending each line with a backslash to escape the implicit newline character.

Strings in JavaScript are **objects** with built in **properties** and **methods**. Properties and methods are accessed with dot notation.

Since methods are functions (stored as object properties) they are written with trailing empty parentheses, else the method itself is returned rather than the result of calling the method.

The **prompt method** opens a dialogue box in the web browser and turns whatever the user types in it into a string.

**String Concatenation** can be done with the `+` operator, or with the **concat** method:

```JS
'string1' += 'string2'

or

'string1'.concat('string2')

both output

'string1string2'
```

**Template literals** are a newer way to define strings in JavaScript using a pair of enclosing backticks.

Template literals allow the insertion of JavaScript **expressions** directly in strings by writing a dollar sign character followed by curly braces enclosing the expression.
The name literal comes from the fact that everything within the backticks is taken at face value unless it is identified as an expression by being enclosed within curly braces following a dollar sign.

```JS
 `Substring ${<expression>}`

 is equivalent to

'Substring ' + <expression>  
```

This is known as **string interpolation**.

#### JavaScript Conditional Statements

Conditional statements cause the program to take one of two or more branching paths based on the truth value of an expression.

The `if` conditional is followed by a code block which is run if the condition is true and ignored if the condition is false.

```JS
if ( condition ) {
  code here runs only when condition is true
}
```

The **strict equality operator**, which checks if two values are exactly the same, is written `===` and is the most often encountered conditional operator. The '==' operator should generally not be used to check equality, as it is more lax and may result in unexpected behavior.

The optional **else clause** consists of the keyword `else` followed by a code block that runs only when the `if` condition evaluates to false. Here is the syntax. Note that else is written on the same line as the closing curly brace of the if part of the conditional by convention.

```JS
if (condition) {
  code here runs only when condition is true
} else {
  code here runs only when condition is false
}
```

The preceding code is called an **if else** statement.

We can also stack `else if` statements to create a cascade of conditionals:

```JS
if (condition) {
  <code>
} else if (condition) {
  <code>
} else {
  <code>
}
```

Keep in mind that an if else-if else conditional structured like this will have one and only one code block that runs (This is a desirable thing).

Here is a list of JavaScript conditional operators:

 `>`   Greater Than
 `>=`  Greater Than or Equal To
 `<`   Less Than
 `<=`  Less Than or Equal To
 `==`  Equal To
 `===` Strict Equal To
 `!=`  Not Equal To
 `!==` Strict Not Equal To

Boolean truth values in JavaScript are written `true` and `false`.

Here is a list of JavaScript Boolean operators:

`&&`  AND
`||`  OR
`!`   NOT

JavaScript does not support NOR, NAND, XOR, or XNOR infix operators, so these logical operations need to be implemented with functions.

Standard rules of Boolean algebra and order of operations apply as one would expect for expressions written with the AND, OR and NOT infix operators.

#### Working With Numbers in JavaScript

In JavaScript, all user input is treated by default as a string, so to use numbers entered by a user as such, we use the `parseInt` or `parseFloat` functions.

JavaScript uses something called the math object for working with mathematical constants and functions like pi, cosine and pseudo-ransom numbers for example. The math object is built in and its methods and properties are static. THe syntax is as follows:

`Math.property`

for mathematical constants and

`Math.method(args)`

for mathematical functions.

The `Math.random()` method returns a pseudo-random number between 0 and 1. Used in tandem with `Math.floor()`, or `Math.ceil()`, we can use this method to create (psuedo) random integers, zero inclusive or zero exclusive.

---

### JavaScript Functions

*Contents:*

* [JavaScript Functions Basics](#javascript-functions-basics)
* [Variable Scope](#variable-scope)
* [Function Expressions](#function-expressions)
* [Arrow Function Expressions](#arrow-function-expressions)
* [Default Function Parameters](#default-function-parameters)




#### JavaScript Functions Basics

Functions are said to be **First class citizens** in JavaScript, meaning they can be passed as arguments to other functions, returned by other functions as arguments, and assigned as a value to a variable.

Functions are  written in camel case by convention and should have intuitive names.

The basic syntax for a JavaScript function is:

```JS
function <name>(<parameters>) {
  <code>
}
```

Functions are called by typing their name, and a pair of trailing parentheses, empty if there are no arguments. Arguments are separated by commas, and are assigned to parameters in the order they are written. Arguments are accessed within a function by referencing their parameter name.

To create a function with a return value:

```JS
function <name>(<parameters>) {
  return <expression>;
}
```

A function terminates as soon as it returns something.

#### Variable Scope

By default, parameters named in a JavaScript function's definition have scope local to that function.

Values stored in a scope outside that of the function should be passed to the function as arguments in order to be used within that function. Accessing and modifying global variables within a function definition is allowed by JavaScript, but definitely not recommended.

If a function is to be used to assign a value to a variable with scope outside that function, this should be done by assigning the return value of said function to the globally scoped variable in question.

Using the `const` keyword to declare global variables whenever feasible is a good way to avoid inadvertently modifying the value of a global variable from within a function.

It is safe to use the `let` or `const` keywords to declare variables local to a function, without worrying about another variable elsewhere having the same name.

#### Function Expressions

JavaScript allows the creation of **anonymous functions**, or **function expressions** by assigning a function to a variable. The syntax is:

```JS
const <name> = function(<parameters>) {
  <code>
};
```

Since functions expressions are statements, a semicolon follows the trailing curly brace. Functions assigned to a variable in this way are called with the variable name.

The most important thing to remember about function declarations vs function expressions is that declared functions can be called anywhere in the program, while function expressions can only be called after they have been assigned. The term for this concept is **hoisting**.  Declarations are hoisted while expressions are not.

#### Arrow Function Expressions

Arrow functions are an abbreviated function expression syntax often used for **callback functions** such as in higher order array methods like map.

Here is the syntax for arrow function expressions:

```JS
const <name> = (<parameters>) => {
  <code>
};
```

As with regular function expressions, don't forget about the semicolon after the closing curly brace. As function expressions, arrow functions are not hoisted.

Arrow functions can be written as one-line statements with an implicit return value, and when written in this way curly braces are optional.

```JS
const <name> = <parameters> => <expression>;
```

When using an arrow function with no parameters, an empty set of parentheses goes where the parameters would normally be.

```JS
const <name> = () => {
  <code>
};
```

#### Default Function Parameters

JavaScript allows us to make a function fall back on a default value in the case of an unsupplied parameter. To do this we simply add an equals sign followed by the default value after the parameter in question in the function declaration or expression.

If an argument is supplied, the default parameter is replaced by that argument.

When passing arguments to a function with multiple parameters, arguments will be assigned to parameters in the order they are supplied, so if we want to leave out an argument other than the last one, we can supply the argument `'undefined'` in its place.

#### Descriptive Comments For Functions

The standard syntax for documenting functions in JavaScript is called JSDoc:

```JS
/**
 * [A short description of the myFunc function]
 *
 * @param {[param type]} param1 - [parameter description]
 * @param {[param type]} param2 - [parameter description]
 * @returns {[return type]} [documents the function's return value]
 */
```

### JavaScript Loops

#### JS While Loop

```JS
while (<condition>) {
  <code>
}
```

The code in the block will run if the condition is true. After the code in the block runs, the condition will be checked again and the code will run again if it is still true, and so on ad infinitum until the condition returns false.

While loops should not be used to repeat code a set number of times using a counter. This would require the declaration of a (very likely ambiguously named) global variable, a bad practice which is by avoided using a **for loop**.

If it makes sense to do so, we can break a loop manually with the `break;` keyword. We should be careful using break statements as they have the tendency to create unpredictable code if used unwisely.

#### JS Do While Loop

The do while loop is like the while loop except for the fact that the code in the block always runs at least once, even if the condition is false. Note the inclusion of a semicolon at the end.

```JS
do {
  <code>
} while ( <condition> );
```


#### JS For Loop

```
for ( <initialization statement>; <condition statement>; <repeating statement>; ) {
  <code>
}
```

The first statement is technically optional and runs first (once only), the second statement is checked for truth before the code in the block runs, and the third statement runs after each time the code in the block runs.

---

### Javascript Arrays

**Store and Access Multiple Values in an Array**

In JavaScript, arrays are of flexible length and can hold multiple data types by default. JS arrays are objects with properties and methods.

Basic array declaration syntax:

```JS
let <name>  = [ <comma separated values if not initializing empty> ]
```

To access an element of an array, use

```
<name of array>[<index of element>]
```

Array indices in JavaScript start at zero.

**Add Elements to an Array**

`Array.push(<args>)` adds an element(s) to the end of an array.

`Array.unshift(<args>)` adds an element(s) to the start of an array.

**Remove Elements From an Array**

To remove and access the element at the end of an array, use
`Array.pop()`

To remove and access the element at the beginning of an array, use `Array.unshift()`

**Copy and Combine Arrays with the Spread Operator**

The spread operator is typed using three dots. `...<Array>`

The spread operator expands the contents of one array, allowing them to be added to the contents of another array.

The spread operator can also be used to pass the contents of an array as an argument to a function as if they were typed in a comma separated list.

**Using a For Loop to Iterate Over the Elements in an Array**

```JS
for ( let i = 0; i < arr.length; i++) {
  <do something with arr[i]>
}
```

**Other Useful Array Methods**

The `Array.join(<separator string>)` method returns a string with each element in the array separated by the string supplied in the argument. That is, every element other than the last one will be followed by the separator, then the next element.

`Array.includes(<valueToFind>)` returns true if the value is an element in the array and false if not.

`Array.indexOf(<searchItem>)` returns the index of the item provided as the argument to the method, and `-1` if the item is not found.

---

### JavaScript Objects

**Object Basics**

JavaScript is an object based programming language. Objects are constructs that have properties and methods that belong to them. Objects allow for the storage of data in **key:** **value** pairs, or **property: value** pairs.

Objects are defined using what is called an **object literal**, specified in JavaScript by a pair of curly braces.

```JS
const <objectName> = {
  <key>: <value>,
  <key2>: <value2>
};
```

Key names follow standard JS naming rules, and values can be any valid data type.

**Access Object Properties**

Data stored in objects is accessed using key names, unlike arrays where it is accessed using an index.

```
<objectName>['<keyName>']

and

<objectName>.<keyName>

```

are both valid syntaxed for accessing a value stored in an object.


**Set the Value of Object Properties**

To set the value of one of an object's properties, we use the following syntax:

```
<objectName.<propertyName> = <value>
```

We can add a new property using the same syntax, and also chain the dot syntax to access properties and methods, because objects can contain other objects as values.

**Use For-In To Loop Through an Object's Properties**

Bracket notation must be used with a for-in loop rather than dot notation to iterate over the values corresponding to an object's  properties. Here is the syntax:

```
for ( let <identifier> in <object name>) {
  < do something with <object name>[<identifier>] >;
}
```

With each iteration of the loop, the identifier specified is reassigned to point to the next property of the object, but remember that accessing a value is different from accessing a property, we must specify which one we want in the code within the body of the loop.

**Useful JavaScript Object Methods**

`Object.keys()` returns an array containing the property names (keys) of an object.

`Object.values()` returns an array containing the given object's property values.

The **spread operator** can be used to insert the properties of one object into another.

Objects can be stored in an array without naming each object individually:

```JS
const <name> = [
  { <property>: <value>},
  { <property>: <value>},
  { <property>: <value>}
]
```

---

### JavaScript and the DOM

*Contents:*

* [DOM Basic Information](#dom-basic-informnation)
* [Selecting Elements](#selecting-elements)
* [Modifying and Styling DOM Elements](#modifying-and-styling-dom-elements)
* [Creating, Removing and Manipulating Elements](#creating-removing-and-manipulating-elements)
* [Listening for and Responding to Events](#listening-for-and-responding-to-events)
* [DOM Traversal](#dom-traversal)
Browsers that can run JavaScript have a single global object called **window** which contains the entire JavaScript environment for that browser as its properties.

The **document** object is used to select and control elements of the web page currently loaded in the browser.

When CSS properties and values are invoked with document's methods, the dash syntax is replaced with camel case syntax and **class** is replaced by **className**, and CSS values are enclosed in quotes.

The DOM (Document Object Model) is the abstract representation of a webpage used by JavaScript. The DOM represents the web page's structure as a single object named document.

The three basic types of tasks JavaScript performs with the DOM are:

* Select elements
* Read or change elements
* Listen for and respond to user events

#### Selecting Elements

One way to select an element with JavaScript is with

```JS
document.getElementById('<id>')
```

This method on the document object returns a reference to the corresponding object in the DOM that represents the HTML element in question. Note that it would not be accurate to say that the element itself is returned by this method, there is a subtle but important difference.

To add an event listener to a selected element, we use

```
<HTMLElement>.addEventListener('<event>', <action>)
```

Some other ways to select elements are:

* `getElementsByTagName()`
  (Which returns an HTMLCollection object)  
* `getElementsByClassName()`
  (Also returns a collection)
* `querySelector()`
* `querySelectorAll()`

Query selector only returns the first matching element found by the browser while querySelectorAll returns all matching instances. These two methods will take any valid CSS selector or HTML attribute as an argument. To use an HTML attribute as the argument, the syntax is:

`[attribute=value]`

#### Modifying and Styling Elements

An HTML element's content can be accessed with the following methods:

```
<HTMLElement>.textContent()
```

and

```
<HTMLElement.innerHTML()
```

The `textContent` property can be assigned to a string value, which replaces its current value with said string. The `innerHTML` property can be assigned to any valid HTML code snippet and any HTML inside that element's opening and closing tags will be replaced.

We can also access and change the values of attributes of DOM elements with

```
<HTMLElement>.<attribute name>
```

If we want to access the class attribute, we need to use `className` because `class` is a reserved keyword in JavaScript.

Inline styles can be set on DOM elements by accessing their `style` property, which is itself an object with methods.

It is common to use the style property when using JavaScript to show or hide elements on the page.

#### Creating, Removing and Manipulating Elements

We can use the document object's createElement() method to insert new elements into our web page. This method takes any valid tag name as an argument.

After creating our element, we can add it to the DOM using `Node.appendChild`. This method takes a DOMNode as an argument. This tells the browser where to place the new node in relation to other nodes.

To remove a node, we use `Node.removeChild(childElement)`.

#### Listening for and Responding to Events

There are many events recognized by the browsers JavaScript environment, and most of them involve user interaction.

We add event listeners to objects with

`EventTarget.addEventListener(type, listener[, options])`

Where `EventTarget` is any valid target for events, `type` is a string representing the event type, and listener is an object implementing `the Event.listener` interface, typically a callback function. The callback function is often called an **event handler** when used in this way.

Events propagate up the DOM tree until they reach the root element. This behavior is useful because we can set a single event handler on a parent element rather than a separate event handler for many of its children.

When an event handler is called, it receives an **event object** containing information about the event as its first argument. This allows us to have the event handler do something based on which of the event target elements ancestors triggered the event. The **target** property is a reference to the element that first triggered the event. We must add the **event** parameter as the first argument in the callback function if we wish to make use of its properties. It is acceptable to use the abbreviation **e** in place of **event**.

If we are reading a descendant element's **tagName** property in order to make a decision within the body of our callback function, it is important to remember that the string returned will be in all caps.

#### DOM Traversal

We can obtain a reference to a selected DOM node's parent node with the `Element.parentNode` property.

Non-Document type child nodes have the property `previousElementSibling` which selects the sibling element immediately before that element and returns null if it is the first sibling. The `previousSibling` property returns the nearest previous sibling DOM node, which is not necessarily an element.

The `Node.insertBefore` method belongs to a parent node, and takes a node to be inserted as its first argument, and a reference node as its second argument. If the node to be inserted already exists in the DOM, it will be moved.

The `ParentNode.children` property returns a collection of all of that node's children elements.

To get the first or last child of a parent element, we use

`ParentNode.firstElementChild`

and

`ParentNode.lastElementChild`

---

### Bootstrap 4 Basics

*Contents:*

* [Introducing Bootstrap](#introducing-bootstrap)






#### Introducing Bootstrap

Bootstrap is a front end framework used for rapid development. Bootstrap supplies a variety of ready-made components with pre-written HTML and CSS, making development easier. Bootstrap also includes JavaScript plugins for adding interactivity to our sites.

Bootstrap is mobile-first and has full cross-browser support, solving many layout, typography and compatibility problems automatically.

---

### Ajax Basics

*Contents:*

* [AJAX Basic Information](#ajax-basic-information)
* [Basic AJAX Implementation](#basic-ajax-implementation)
* [Query Strings and Response Formats](#query-strings-and-response-formats)
* [Security Limitations of AJAX](#security-limitations-of-ajax)
* [Using JSON with AJAX](#using-json-with-ajax)

AJAX is an acronym for Asynchronous JavaScript and XML. What AJAX does, is update HTML without loading a new webpage. AJAX can make our pages faster because only the specific data that is needed is requested from the server, which in many cases is much less than the data it takes to reload the entire page. Technically, AJAX is really called **XMLHttpRequest Object**, or XHR. Originally, XML (extensible markup language) was the form that AJAX responses were sent in, but now this is not usually the case.

Browsers, called **clients**, make requests to **servers**, which then send back a **response**. The term AJAX has come to denote a methodology of using several pre-existing technologies to facilitate this process in an efficient, asynchronous way. (Meaning data requests and responses are decoupled from page display, one does not wait for the other). This allows wepages to behave much more dynamically than they would otherwise be able to.

#### Basic Ajax Implementation

AJAX works in a four step process:

1. Create an XMLHttpRequest Object.
2. Create a callback function.
3. Open a request.
4. Send the request.

The first step, repeated for each new request, looks like this:

```
var <name> = new XMLHttpRequest();
```

The second step defines what the browser does with the information it receives back from the server. It is important to know that if there is more than one of these callback functions due to more than one request, there is no way to know what order they will be called in. The callback function is triggered by an event. The `onreadystatechange` event happens whenever there is a change in the state of the AJAX request. A **ready state of 4** indicates that a response has been received back from the server.
```
<name of XMLHttpRequest Object>.onreadystatechange = function () {
    if (<name of XMLHttpRequest Object>.readyState === 4) {
      <do something with XMLHttpRequestObject.property>
    }
}
```

Step 3 uses the XHR Object's `open` method. This method takes two arguments, the first being the HTTP method that is being used, such as `GET` or `POST`, and the second being the url where the request is being sent.

```
<name of XMLHttpRequest Object>.open('<HTML method>', 'url' )
```

The fourth step is simple:

```
<name of XMLHttpRequest Object>.send(<data if posting>);
```

#### Query Strings and Response Formats

Query strings are appended to a url following a question mark:

```
http://website.com/employees.php?key=value
```

The query string describes what specific piece(s) of information is being requested from the server by the browser. Multiple key-value pairs are separated by an ampersand.

The ampersand, space, plus and quote marks are all reserved characters in query strings.

When using the `GET` method, all of the information being sent with the request is sent in the url, making it a less than ideal choice for sending sensitive information. That information will be saved in the computer's browser history and the web servers log files.

The `POST` method sends data separately from the url, in the body of the request. Meta-information about the information being sent with the `POST` request is included in a specially formatted header.

For some simple requests, a server will send back a short response in plain text. For more complex responses, it is standard to use a data interchange format such as XML or JSON (JSON being the most popular currently).

#### Security Limitations of AJAX

In general, using JavaScript to exchange information between websites and servers is not permitted if the two websites are not hosted by the same server, or if the server the information is being requested from is not the host server. These kind of requests are called **cross-origin** requests, and the rules governing them are determined by a browser's **same-origin policy**.

Switching between HTTP and HTTPS is also not allowed, and neither is switching port numbers.

Some ways around this are to invoke a web proxy, or use **JSONP**, which stands for **JSON with Padding** (Which is commonly used to access information such as JQuery libraries or Google fonts). A newer way is called CORS or Cross-Origin Resource Sharing. CORS is recommended by the W3C and allows a server to accept requests from other domains under certain circumstances, including accepting special secure requests that require the requesting browser to supply credentials.

#### Using JSON With AJAX

JSON notation must be written as an array of items, or an object made up of key-value pairs, or a combination of the two. Unlike regular JavaScript object keys, keys in JSON must be enclosed in double quotes. JSON also requires double quotes for string values. A JSON validator can be used to check if a file is formatted with valid JSON.

The browser itself interprets data it receives back from the server as a plain text file, a long string. On the front end, we parse that string and convert it to JavaScript using the `JSON.parse` method:

```
JSON.parse(<XMLHttpRequestObject>.responseText)
```

The JSON parse method always returns a JavaScript object when supplied with valid JSON. At this point, the data is in a form where it can be easily inserted into markup using JavaScript.

---

### Asynchronous Programming With JavaScript

* [Asynchronous JavaScript Basics](#asynchronous-javascript-basics)
* [JavaScript Promises](#javascript-promises)


#### Asynchronous JavaScript Basics

JavaScript is a synchronous, single threaded language, meaning it can process only one request at a time. Because of this, asynchronous operations (operations which may need to wait for some event to happen or resource to become available) are handled separately from normal operations in JavaScript.

**Blocking behavior** refers to code that forces the browser to wait for it to finish executing before anything else can happen in the browser. Blocking behavior is, in general, undesirable.

One of the simplest examples of special JavaScript methods for implementing asynchronous operations is the `setTimeout` method, which takes a callback function and a number of milliseconds as arguments. When called, it executes the callback function after the time delay has expired.

Asynchronous behavior in JavaScript does not come from the JavaScript engine, but rather is handled by various APIs provided by the JavaScript runtime environment. In the browser, some examples of web APIs that handle these kind of operations are setTimeout(), XMLHttpRequest, Fetch API, and the DOM event API.

Asynchronous JavaScript code is run by the the **call stack**, **Web APIs**, and the **callback queue** working together. The call stack consists of a stack of frames, where each frame has its own namespace for arguments and local variables. When a function is called within a function, the latest function called goes to the top of the stack and gets its own frame. Frames at the top of the stack are executed first. When the call stack encounters an asynchronous operation, it is handed off to a web API to be processed. If a callback function is part of the operation handed off to the web API, the API pushes that function onto the callback queue when it is ready to be executed, where it waits for the **event loop** to push it onto the call stack.

#### JavaScript Promises

JavaScript promises are created with the **promise constructor function**.

> The `Promise` object represents the eventual completion (or failure) of an asynchronous operation and its resulting value.
-MDN
>

The promise constructor function takes one argument, a callback with the two parameters `resolve` and `reject`. These parameters are themselves functions, whose parameters are the values to be returned upon resolution or rejection.

The promise API has methods that can be called on a promise object, the two most common of which are `then()` and `catch()`.

The `then` method takes two functions as parameters, one for fulfilled promises, and the second optional one for rejected promises. The `catch` method can be chained to the `then` method to handle rejected promises.

---

### Object Oriented JavaScript

*Contents:*

* [Object Oriented JS Basics](#object-oriented-js-basics)
* [JS Classes](#js-classes)



#### Object Oriented JS Basics

The quickest and simplest way to create our own custom object with JavaScript is to declare an **object literal**.

```
let <object name> = {
  <property name>: <value>,
  <method name>: <function>
};
```

Object properties and methods are accessed with dot notation or bracket notation.

Dot notation:

```
Object.<property name>
```

Bracket notation:

```
Object['<property name>']
```

The `this` keyword is bound to the name of the object within the scope of methods owned by that object.

#### JS Classes

When we declare a class, we define a constructor method belonging to that class that will be called to create new instances of that class. The `this` keyword is used in the constructor method rather than the object name. The object name refers to the class itself rather than the instances of the class that will be created with the constructor method. The syntax for instantiating a new instance of a class is:

```
let <name of instance> = new <Name of class>(<parameters>)
```

Getters and setters are the methods that allow the creation, retrieval, and updating of an object's properties.

The getter method allows the retrieval of properties that have dynamic values. The value is computed by the getter method and passed along, but not stored as the property's value. Getter methods are defined inside the class declaration with the following syntax:

```
get <method name>(args) {
  <code>
}
```

A setter method receives a value and can perform logic on that value if necessary.







---

### CSS Selectors

*Contents:*

* [Attribute Selectors](#attribute-selectors)
* [Combinators](#combinators)
* [CSS Pseudo Classes](#css-pseudo-classes)
* [Substring Matching Attribute Selectors](#substring-matching-attribute-selectors)
* [Element States Pseudo Classes](#element-states-pseudo-classes)
* [Pseudo Class Examples](#pseudo-class-examples)
* [Pseudo Elements](#pseudo-elements)


#### Attribute Selectors

Selecting elements based purely on whether they have a certain attribute may not find many use cases, but if for some reason we want to do that, here is how:

```CSS
[<attribute>] {
  <property>: <value>;
}
```

To add a value, as will most likely be necessary, we use a similar syntax to that in the HTML:

```CSS
[<attribute>="<value>"] {
  <property>: <value>;
}
```

We can add a tag name before the opening bracket with no space to target only elements of that type which have the specified attribute and value.

Attribute selectors are often helpful for styling form elements.


#### Combinators

Combinators target elements based on the relationship between said elements in the HTML code.

The `>` sign is called the **child combinator because it targets elements that are direct children of the specified element.

The following rule targets the child element:

```CSS
parent > child {
  property: value;
}
```
The `+` sign combinator targets only elements that are adjacent siblings of the specified element.

```CSS
element + sibling {
  property: value;
}
```

An element's adjacent sibling is considered the element that follows, not precedes, that element.

The `~` is called the general sibling combinator and targets all sibling elements that follow.

#### CSS Pseudo Classes

Structural pseudo-elements target elements based on their position on the page and relation to other elements. The element to be targeted is typed followed by a semicolon and then the pseudo-class, with no spaces.

An example of a structural pseudo class is the **first-child** pseudo class:

```CSS
element:first-child {
  property: value
}
```

The **first-child** targets only elements that are the first child of another element. The **last-child** pseudo class of course does something similar but targets last child rather than first. These particular pseudo-elements are useful for adding some slick styling to lists and navs.

There are many other useful pseudo-classes. Two more that are covered in the Treehouse tutorial are `:only-child` and `:empty`.

#### Substring Matching Attribute Selectors

Substring matching attribute selectors allow targeting elements based on a specific piece of an attribute's value (regex style).

The **begins-with** selector uses a caret:

```CSS
element[attribute^="substring"] {
  property: value;
}
```

The **ends-with** selector uses a dollar sign:

```CSS
element[attribute$="substring"] {
  property: value;
}
```

The **contains** selector uses an asterisk.

```CSS
element[attribute*="substring"] {
  property: value;
}
```

#### Element States Pseudo Classes

Element states pseudo classes target elements based on the user's interaction with them.

The basic syntax is:

```CSS
element:state {
  property: value;
}
```

Like with other pseudo classes, an element need not be provided, if we wish to target all elements in that state. Here is an example of combining an attribute selector with a combinator and an element state pseudo class:

#### Pseudo Class Examples


The **:nth-child** pseudo class targets elements based on any position within their parent element in relation to their siblings (if any). The argument can be any valid expression, such as **odd**, **even** an integer, or a formula `an+b`, for example.

```CSS
element:nth-child(argument) {
  property: value;
}
```

The **:nth-of-type** pseudo class targets child elements like **:nth-of** does, but only if they are of a given type.

The **:root** pseudo class selects the element that is the root, that is the highest level element in the document.

The **:target** pseudo class selects an element that is the target of a link.

The **:not()** pseudo class is used for negation and targets all elements which do not match the expression given as the argument.

#### Pseudo Elements

Pseudo Elements can style certain parts of an element like just the first line of text or the first letter in a paragraph, for example. They can also be used to insert elements and content into the page without making changes to the **document object model** (DOM).

Pseudo elements can be denoted with one or two semicolons, but two is preferable to distinguish them from pseudo classes.

The **::before** and **:after** pseudo elements are used to insert content (virtual elements) immediately before or after a specified element. This kind of content is called **generated content**. The **content property** is always used with these pseudo classes to specify what content should be inserted. Any further properties and values added to the rule are applied as styles to the content.

```CSS
element::before {
  content: <content to be inserted>;
  property: value;
}
```

The before and after elements can also be used to insert the value corresponding to one of an elements properties by supplying the CSS function **attr()** as the value of the content property. The name of the respective attribute is supplied as the argument to the function.

In actuality, the generated content is created as child content of the targeted element, so it will lie within that element's borders and inherit styles from it.




---

### CSS Layouts

*Contents:*
* [The Display Property](#the-display-property)
* [Relative and Absolute Positioning](#relative-and-absoute-positioning)
* [Fixed and Sticky Positioning](#fixed-and-sticky-positioning)
* [Floated Elements](#floated-elements)
* [The Z Index](#the-z-index)
* [Media Queries](#media-queries)
* [Additional Concepts](#additional-concepts)


#### The Display Property

The display property has four basic values, **none**, **inline**, **block** and **inline-block**.

`display: none` makes an element invisible. This value is useful for toggling element visibility based on user interaction.

`display-block` elements, also known as block level elements, are displayed one after the other vertically, taking up the entire width of their parent container and as much vertical space as they need by default.

`display-inline` causes elements to display on the same line as other elements, taking up one line height vertically and as much space as needed horizontally by default. Inline elements wrap like text.

`inline-block` elements display inline, but their width and height can be changed using CSS, unlike inline elements.

#### Relative and Absolute Positioning

There are five types of positioning in CSS,**static**, **relative**, **absolute**, **fixed** and **sticky**. Static is the default position value.

Directional values can be used to position an element relatively to itself (where it would normally be positioned). Relative positioning may cause an unwanted scroll bar to appear in some cases. The directional values are listed separately like properties:

```CSS
selector {
  positon: fixed;
  top: 20px;
  right: 20px;
}
```

Absolute positioning removes an element from the normal document flow. By default, absolute positioning uses the edges of the viewport as a reference. This is because absolute positioning actually uses the closest positioned ancestor as its reference and the body element is a positioned element that takes up the entire viewport.

#### Fixed and Sticky Positioning

A fixed element is positioned relative to the viewport rather than its closest positioned ancestor. Fixed elements stay in place when the page is scrolled. Fixed content is also removed from the normal document flow.

Sticky content maintains its position once the page is scrolled past that element, until the page is scrolled back past the element in the opposite direction.

A rule for making an element stick to the top of the page when it is scrolled past would look like this:

```CSS
selector {
  position: sticky;
  top: 0px;
}
```

#### Floated Elements

The float property is used to remove elements from the normal document flow and place them on the right or left side of the page, while other content wraps around them.

We can use the `clear` property to prevent content from wrapping around floated elements.

#### The Z Index

CSS' `z-index` property determines how elements stack on the imaginary axis facing into the page. Elements with a higher z-index are displayed on top of elements with a lower z-index. Elements with the same (or default) z-index are stacked according to normal document flow.

#### Media Queries

Media queries are CSS rules that are only applied when certain specified conditions are met. Those conditions are defined within the media query.

Media queries most often target device width, but can be used for a wide variety of different types of media, such as print, low resolution devices, etc.

The **meta viewport declaration** is used to let mobile browsers know your content is optimized for viewing on a mobile device. This prevents the mobile browser from automatically zooming out and making your content too small to be legible.
```HTML
<meta name="viewport" content="width=device-width, initial-scale=1">
```

#### Additional Concepts

A **CSS reset** is a stylesheet used to override the default styles applied by different web browsers so that web pages will have a consistent look across all browsers.

A **wrapper** is a container element used to hold our layout within certain boundaries and center it on the page. The wrapper is an element that will often be styled differently for different sizes of viewports. A wrapper can be made either by using the existing `body` tag or by creating a new div that wraps our page content.

**Collapsing Margins** happen when two margins abut one another. The two margins collapse to the larger of the two values. Only vertical margins collapse, not horizontal ones.

---

### CSS Flexbox

*Contents:*

* [Flexbox Basics and Terminology](#flexbox-basics-and-terminology)
* [Creating a Flex Container](#creating-a-flex-container)
* [Controlling the Direction of Flex Items](#controlling-the-direction-of-flex-items)
* [Wrapping Flex Items](#wrapping-flex-items)
* [Distributing Space Inside a Flex Container](#distributing-space-inside-a-flex-container)
* [Changing the Order of Flex Items](#changing-the-order-of-flex-items)
* [Growing Flex Items](#growing-flex-items)
* [Aligning Flex Items on the Cross Axis](#aligning-items-on-the-cross-axis)

#### Flexbox Basics and Terminology

CSS flexbox is a collection of CSS properties used to create responsive web pages. Flexbox allows one to change the direction, size, and order of HTML elements using CSS.

The two most important elements in Flexbox are **flex containers** and **flex items**. The container sets the context for the flex items within it, that is, the flex properties applied to the flex container determine in what manner the flex items will be displayed.

A flex container can be any inline or block level element. Any direct child of a flex container is automatically a flex item.

By default, the x-axis of a flexbox container is the primary direction in which elements are laid out and is called the **main axis** while the y-axis is called the **cross axis**.

#### Creating a Flex Container

To create a flex container, we set the display property of an element to one of the Flexbox layout styles. By default, the flex children will be displayed one after each other in the order they are written in the HTML, taking up as much space as they require horizontally and stretching vertically to fill the height of the flex container. By default, the flex container is a block level element but we can make it an inline element if we so choose.

The simplest block level flex container:

```CSS
selector {
  display: flex;
}
```

The simplest inline flex container:

```CSS
selector {
  display: inline-flex;
}
```

#### Controlling the Direction of Flex Items

The **flex-direction** property determines the direction that flex items are laid out in the parent flex container. The default value for this property is `row` (think of a row in a matrix). To keep the items in a row but reverse their order, we can use the value `row-reverse`. Since this reverses the start and end positions of the main axis, by default this value will push the flex items to the right side of their parent container as well as reversing their order.

As one might expect, to lay the flex items out vertically we use `flex-direction: column`. This switches the main axis with the cross axis, so now the flex items take up only as much space as they require vertically and expand to fill their parent container horizontally. `column-reverse`, of course, causes the items to display from the bottom of the container up, leaving any extra space above.

#### Wrapping Flex Items

By default, all items in a container will be displayed along one line called a **flex line**, and will not wrap even if the items overflow the container.

To apply basic wrapping behavior to out flex container, we can use `flex-wrap: wrap`.

#### Distributing Space Inside a Flex Container

The `justify-content` property determines how space and alignment are distributed and controlled along the flex container's main axis. The default value for this property is `flex-start`. Some other useful values are `center`, `space-between`, and `space-around`.

Giving a flex item a `margin: auto` property will cause it to push items around it to the edge of the flex container.

#### Changing the Order of Flex Items

Unlike the previous properties, the `order` property belongs to flex items rather than a flex container, and does not include the word "flex". Order overrides the order the items are written in the HTML, and the default value for the order property is zero. Items with higher order are displayed after items of lesser order along the main axis.

#### Growing Flex Items

The `flex-grow` property determines how flex items expand in relation to each other and the available space in their parent flex container. This property is applied to flex items individually. (Although in practice they are usually targeted in groups with a tag or class selector). Assigning a numeric value to the `flex-grow` property tells an item how much space to take up in relation to its sibling items (The values of two items together make a ratio). The grow property is applied separately and sequentially to separate flex lines. Remember that this ratio applies to the amount of extra available space each element will take up, not to the total resultant size of each element in relation to its siblings.

The `flex-basis` property sets a bottom threshold size for flex items. After this size is taken up, remaining space is allocated by the `flex-grow` property. The `flex-basis` property is applied to items and takes a length unit.

#### Aligning Flex Items on the Cross Axis

The `align-items` property belongs to the flex container and dictates how children of that container will be aligned along the cross axis. The default value for this property is `stretch`, which means fill all the available space along the cross axis. Other values include `flex-start` and `flex-end`, and `center`.

The `align-self` property decides the same behavior, but is applied to individual flex items.

---

### CSS Grid







---

### HTML Forms

*Contents:*

* [HTML Forms Basics](#html-forms-basics)
* [The Input Element](#the-input-element)
* [The Textarea Element](#the-textarea-element)
* [The Button Element](#the-button-element)
* [The Label Element](#the-label-element)
* [Fieldsets and Legends](#fieldsets-and-legends)
* [Select Menus](#select-menus)
* [Radio Buttons](#radio-buttons)
* [Checkboxes](#checkboxes)


#### HTML Form Basics

The `<from></form>` element is used to capture user input.

Forms are normally used in combination with a server side language like python, ruby, etc. to send the data to a server for processing. Forms have **attributes** that determine what happens to the data that gets entered into them.

The **action attribute** takes a URL as its value and tells the browser where to send the data entered into the form.

The **method attribute** takes either **get** or **post** as its value and determines what happens with the data. Get Appends the form-data to the URL given by the action attribute as name/value pairs. Post sends the form-data as an HTTP post transaction.

The resultant URL corresponding to the **get** method:

`http://example.com?name=value`

#### The Input Element

The input tag is a self closing tag. It has **type**, **id**, and **name** attributes.

The `type` attribute tells the browser what sort of information we are sending with the form, such as text, a telephone number or a password to name a few examples.

The `id` attribute, while not mandatory, is a good thing to include. There is a good chance we will need to target our input element with CSS or JavaScript and the id attribute allows us to do so. It also allows associating labels to specific form controls.

The `name` attribute provides vital information to the server so it can understand the form data and process the values sent.

#### The Textarea Element

This element takes text as its input data type automatically, so it doesn't need a type attribute like `<input>`. The entry field is formatted to accept multiple lines of text. In most browsers, the textarea element renders a draggable corner that the user can interact with to adjust the size of the input field. The `<textarea></textarea>` tag is not a self-closing tag like the input tag.

#### The Button Element

The `<button></button>` element is an HTML element provided for the user to signal the browser to do something with the information currently residing in the form's input fields, such as submit it or reset it. Button elements have a `type` attribute, the most common value for which is `submit`. Buttons do not have a default type, so be sure to specify one or the button won't do anything.

#### The Label Element

The `<label></label>` element provides some text that specifies to the user what data is supposed to be entered into an input field. The `for` attribute takes the input element's `id` attribute as a value and associates the label with that element. This means using labels properly is very important for accessibility.

```HTML
<label for="mail">Email:</label>
<input type="email" id="mail" name="user_email">
```

When the user clicks on the label element, the page focuses on the corresponding input field.

#### Fieldsets and Legends

The `<fieldset></fieldset>` element is used to logically group HTML form elements. (The elements that are children of the form, not the form element itself) Fieldsets are labelled using the `<legend><legend>` element. The legend is placed within the fieldset tags as the first element. The reason for having a separate tag just to label the fieldset is semantic HTML.

#### The Select Element

To allow the user to pick from a list of predetermined options to submit, we use the `<select></select>` element. The select element should receive `id` and `name` attributes and have a corresponding label element that explains what the user is choosing. Within the select tags go the `<option></option` tags. The option tags need a `value` attribute to function properly. Whatever text may be nested in between the option tags is for the users benefit and will not be sent by the form. Here is an example:

```HTML
<select id="job" name="user_job">
  <option value="frontend_developer">Front-End Developer</option>
  <option value="php_developer">PHP Developer</option>
  <option value="haskell_developer">Haskell Developer</option>
  <option value="react_developer">React Developer</option>
</select>
```

The `<optgroup></optgroup>` element can be used to organize options logically by placing them in between its opening and closing tags. The optgroup tag takes an attribute `label` the value of which will be displayed by the browser to the user.

#### Radio Buttons

Radio buttons work like the option element in that they allow the user to pick one option from a list, but instead of having to click a select element and then choose from a pop up list, all options are displayed up front and the user chooses by clicking a button next to the option they want.

Radio button elements should have `for`, `id` and `name` attributes. The syntax for a radio button as an input is:

```HTML
<input type="radio" id="id" value="value" name="name">
```

 Writing the label for the radio button after the button itself may be helpful for the user, as this will display the button to the left of the text describing what the button selects, and this is more intuitive than having the button to the right. If the `name` attribute is the same for a group of radio buttons, the browser will only allow one of them to be selected at a time.

#### Checkboxes

Checkboxes are used when we have a  group of predefined options for the user to choose from, but we need the user to be able to select more than one of them. Here is an example checkbox group:

```HTML
<label>Interests</label>
<input type="checkbox" id="development" value="interest_development" name="user_interest">
<label class="light" for="development">Development</label><br>
<input type="checkbox" id="design" value="interest_design" name="user_interest">
<label class="light" for="design">Design</label><br>
<input type="checkbox" id="business" value="interest_business" name="user_interest">
<label class="light" for="business">Business</label><br>
```

Note that it the use of the checkbox attribute rather than the radio attribute that tells the browser to only allow one option to be selected at a time, not some difference in how we use the name and value attributes, this part of the syntax is identical for checkbox and radio buttons.

---

### HTML Tables

HTML tables display information in tabular form (rows and columns). Table rows are declared explicitly with tags, while table columns are implied from the number of children the rows have. The table tag is `<table></table>` and the table row tag is `<tr></tr>`. Table cells have the `<td>` tag.

The table header cell element, `<th></th>` tells the browser, search engine crawlers, and screen readers that this cell contains the label that the information in the following row or column is associated with. The `scope` attribute defines whether the table header cell element is labeling its row, column, remainder of its row or remainder of its column.

The `<thead>` element is used for semantic purposes and wraps the table header information, typically the leading row. The `<tbody>` element, also a semantic element, wraps the remaining rows.

The table footer element, `<tfoot></tfoot>`, is placed between the table head and table body tags in the HTML. The table footer is optional and typically includes aggregate or meta information.

The `<caption></caption` element gives the table a title that tells browsers, search engines, etc. what information the table is meant to display. It is placed immediately after the opening `<table>` tag.





---

### Accessibility for Web Developers

*Contents:*

* [What is Accessibility](#what-is-accessibility)
* [Web Content Accessibility Guidelines](#web-content-accessibility-guidelines)
* [Form Accessibility](#form-accessibility)

Accessibility is important because there are many people who use the web and are disabled. It is important to provide these people with the best experience possible.

Making our websites accessible has other benefits too, like improving user experience for all users in ways that may not at first be obvious, ensuring our sites are legally compliant, and boosting search rankings. Accessible websites work with assistive technologies to ensure that disabled users are able to access the information on the site.

Some common assistive technologies:

* Screen Reader
* Screen Magnifiers
* Switch Controls
* Closed Captioning

The Americans With Disabilities Act, Title 3

* Websites and apps are "places of public accommodation"
* Prevents discrimination against people with disabilities

#### Web Content Accessibility Guidelines

The Web Content Accessibility Guidelines are the internationally recognized standard for web accessibility, although laws vary from country to country.

The WCAG Four Principles of Accessibility

* Perceivable
* Operable
* Understandable
* Robust

Within these four principles are 13 accessibility guidelines. Here is resource that summarizes them:

[13 Days of Accessibility](http://a11ycalendar.kaseybon.com/)

The WCAG has three levels of compliance, **A**, **AA**, and **AAA**, with **AAA** being optional as it may not always be feasible to achieve.

**WCAG Perceivable Principle**

* Text alternatives
* Captions and transcripts
* Present content using semantic html
* Portrait and landscape orientation
* Sufficient color contrast
* Combine multiple visual cues, not just color
* Avoid autostarting audio or video
* Responsive body copy
* Legible at 200% zoom

**WCAG Operable Principle**

* Keyboard navigation
* Focus indicators
* Allow enough time
* Disable distracting content
* Careful with flashing animations
* Help users navigate
* Titles
* Make link purpose clear
* Semantic heading structure
* Provide alternatives to complex interactions
* Generous target sizes

**WCAG Understandable Principle**

* Set HTML language attribute
* Use plain language
* Create predictable navigation
* No unexpected changes in context
* Make errors easy to spot and correct

**WCAG Robust Principle**

* Write valid HTML
* Use Semantic Markup
* Changes in content status

#### Form Accessibility

**Form accessibility principles**

* Avoid unnecessary questions
* Minimize Questions per screen
* Provide context clues
* Group related questions
* Use clear input labels
* Make focus indicators obvious
* Help users spot and correct errors

Example of an accessible form:

```HTML
<form>
  <fieldset>
    <legend>Delivery Information</legend>
    <p class="hint">* - required field</p>
    <label for="name">Your Name *</label>
    <input type="text" id="name" name="user-name">
    <label for="email">Email Address *</label>
    <input type="email" name="user-email">
    <p class="hint">Receipt will be sent to this address.</p>
    <label for="address1">Street Address *</label>
    <input type="text" id="address1" name="user-address1">
    <label for="address2">Apartment/Office Number</label>
    <input type="text" id="address2" name="user-address2">
    <label for="zip">Zip Code *</label>
    <input type="text" id="zip" name="user-zip">
    <p class="hint">City and state will be looked up from Zip Code.</p>
    <label for="phone">Phone</label>
    <input type="text" id="phone" name="user-phone">
    <p class="hint">No phone? Include alternate contact below.</p>
    <textarea id="delivery-instructions"
    name="user-delivery-instructions"></textarea>
    <button type="submit">Continue to Billing</button>
  </fieldset>
</form>
```



---
















---
---

## Miscellaneous CSS

---
---

## Full Stack JavaScript Track

---
---

## Learn React Track

### React Basics

*Contents:*

* [React Fundamentals](#react-Fundamentals)



#### React Fundamentals

React is a component based JavaScript library for building user interfaces. All react actually does is create and update HTML elements for the UI. This is done using a syntax called JSX.










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
