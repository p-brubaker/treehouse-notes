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
