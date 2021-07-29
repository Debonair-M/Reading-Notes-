#HTMLNotes
*Wireframe- 
Wireframing is a practice used by UX designers which allows them to define and plan the information hierarchy of their design for a website, app, or product.

Ways Designers can structure the process from design to implementation:
Wireframe > Interactive Prototype > Visual > Design
Sketch > Code
Sketch > Wireframe > Hi-Def Wireframe > Visual > Code
Sketch > Wireframe > Visual > Code
*Tools for Wireframe-
UXPin: UXPin has a wide range of functionalities, but one of the best ones is how it facilitates building responsive clickable prototypes directly in your browser.

InVision: InVision allows you to get feedback straight from your team and users through clickable mock-ups of your site design. It’s completely free too!

Wireframe.cc: Wireframe.cc provides you with the technology to create wireframes really quickly within your browser, the online version of pen and paper.

#HTML Basics
HTML is a markup language that defines the structure of your content. 
*HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way.
*Hypertext Markup Language- is the code that is used to structure a web page and its content. 
 For example, content could be structured within a set of paragraphs, a list of bulleted points, or using images and data tables.
The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller.
##HTML Tags
The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.
The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
The content: This is the content of the element, which in this case, is just text.
The element: The opening tag, the closing tag, and the content together comprise the elemen

*Attributes*-
Attributes contain extra information about the element that you don't want to appear in the actual content.
An attribute should always have the following:
*A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
*The attribute name followed by an equal sign.
*The attribute value wrapped by opening and closing quotation marks.

*Elements*-
*Nesting- puting elements inside other elements.
 Empty- Elements that have no content.
<!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly.
<html></html> — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element.
<head></head> — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
<title></title> — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
<body></body> — the <body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

##Semantics
In programming, Semantics refers to the meaning of a piece of code.
In HTML, for example, the <h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page.
HTML should be coded to represent the data that will be populated and not based on its default presentation styling. Presentation (how it should look), is the sole responsibility of CSS.
####Semantic Elements
<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>





