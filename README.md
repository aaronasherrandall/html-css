# html-css
HTML &amp; CSS fundamentals

```html
<html>
    <body>
        <h1>This is the Main Heading</h1>
        <p>This text might be an introduction to the rest of
           the page. And if the page is a long one it might
           be split up into several sub-headings</p>
        <h2>This is a Sub-Heading</h2>
        <p>Mant long articles have sub-headings so to help
           you follow the structure of what is being written.
           There may even be sub-sub-headings (or lower-level
           headings)</p>
        <h2>Another Sub-Heading</h2>
        <p>Here you can see another sub-heading</p>
    </body>
</html>
```

<html>
    <body>
        <h1>This is the Main Heading</h1>
        <p>This text might be an introduction to the rest of
           the page. And if the page is a long one it might
           be split up into several sub-headings</p>
        <h2>This is a Sub-Heading</h2>
        <p>Mant long articles have sub-headings so to help
           you follow the structure of what is being written.
           There may even be sub-sub-headings (or lower-level
           headings)</p>
        <h2>Another Sub-Heading</h2>
        <p>Here you can see another sub-heading</p>
    </body>
</html>

<h2>Structure</h2>

The HTML code is made up of characters that live inside angled 
brackets - these are called HTML <b>elements</b>. Elements are usually 
made up of two <b>tags</b> -  an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML elements tells the browser 
something about how the information that sits between the opening and
closing tags.

<h2>Attributes</h2>

Attributes provide additional information 
about the contents of an element. They appear
on the opening tag of an element and are
made up of two parts: a <b>name</b> and a <b>value</b>,
separated by an equals sign.

```html
<p lang="en-us"> Paragraph in English</p>
```

Here an attribute called lang is
used to indicate the language
used in this element. The value
of this attribute on this page 
specifies it is in US English.

The value of the lang attribute
is an abbreviated way of 
specifying which language is 
used inside of the elements that 
all browsers understand.

## Body, Head & Title
## /<BODY>
Everything inside this elements is shown inside the main browser window.

## /<HEAD>
Before the <body> element you will often see a element. This contains information about the page (rather than information that is shown within the main the main part of the browser window). You will usually find a <title> element inside of the <head> element.

## /<TITLE>
The contents of the <title> element are either shown in the top of the browser, above where you usually type the URL of the page you want to visit, or on the tab for that page.

HTML stands for Hypertext Markup Language. The Hypertext part refers to the fact that HTML allows you to create links that allow visitors to move from one page to another quickly and easily. A markup language allows you to annotate text, and these annotations provide additional meaning to the contents of a document. If you think of a web page, we add code around the original text we want to display and the browser then uses the code to display the page correctly. So the tags we add are markup.
