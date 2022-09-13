**week 1: HTML in depth**<br>

# Course Introduction

## Introduction to HTML and CSS in depth

- The next HTML section will focus on bringing websites to life with media elements. You will learn how to embed video and audio players and even **iframes**.

- Following the module about HTML, is when all about **CSS**. This part of the course will go beyond basic **styling**. You will learn how to create layouts with grids and flex boxes. You will also learn about CSS **selectors** and how you can combine them to refine the styling of elements on your web pages.

- Not only that, but you'll also learn how to use **pseudo-class selectors** to improve the interactivity of a web page. But there's even more. You will learn how to add effects on web pages using purely CSS and you will cover basic transform and transition animations, as well as more advanced animations using **key frames**.

## How are HTML and CSS used in the real-world?

- By you know that **HTML** is a markup language for creating webpages. Together with **CSS**, it has helped the web browser expand beyond just desktop computers.

- HTML has been around since 1990, and it was originally designed to provide a way for people to share information over the Internet. HTML webpages used to only show basic images and text.

- But HTML can do much more than just defining how content is displayed in the browser. CSS is a **stylesheet** language that is used to describe **the look** and **layout** of a document written in HTML. While CSS is not a **programming language**, it does allow for some programming like features such as **variables** and **nested rules**.

- CSS gives you control over **color**, **size**, **spacing**, **fonts**, **positioning** and more. One of the fundamental principles of CSS is the **separation of content and style**.

# Semantics and Meta Tags

## Semantics tags and why we need them

- The basic HTMl semantis is:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

- There are really lots of semantic tags available to help describe the meaning of your HTML doc. They are:<br>

#### Sectioning Tags

1. <code>&lt;header&gt;</code> - The header of a section content or the webpage. The webpage header usually contains the website branding or logo.

2. <code>&lt;nav&gt;</code> - The navigation links of section or the webpage.

3. <code>&lt;footer&gt;</code> - The footer of a content or the webpage. On a webpage, it often contains secondary links, the copyright notice, privacy policy and cookie policy links.

4. <code>&lt;main&gt;</code> - Specifies the main content of a section or the webpage.

5. <code>&lt;aside&gt;</code> - A secondary set of content that is not required to understand the main content.

6. <code>&lt;article&gt;</code> - An independent, self-contained block of content such as a blog post or product.

7. <code>&lt;section&gt;</code> - A standalone section of the document, that is often used within the body and article elements.

8. <code>&lt;details&gt;</code> - A collapsed section of content that can be expanded if the user wishes to view it.

9. <code>&lt;summary&gt;</code> - Specifies the summary or caption of a &lt;details&gt; element.

10. <code>&lt;h1&gt;</code> <code>&lt;h2&gt;</code> <code>&lt;h3&gt;</code> <code>&lt;h4&gt;</code> <code>&lt;h5&gt;</code> <code>&lt;h6&gt;</code> - Headings on the webpage. &lt;h1&gt; indicates the most important heading whereas &lt;h6&gt; indicates the least important.

#### Content Tags

1. <code>&lt;blockquote&gt;</code> - Used to describe a quotation.

2. <code>&lt;dd&gt;</code> - Used to define a description for the preceding &lt;dt&gt; element.

3. <code>&lt;dl&gt;</code> - Used to define a description list.

4. <code>&lt;dt&gt;</code> - Used to describe terms inside a &lt;dl&gt; element.

5. <code>&lt;figcaption&gt;</code> - Defines a caption for a photo image.

6. <code>&lt;figure&gt;</code> - Applies mark up to a photo image.

7. <code>&lt;hr&gt;</code> - Adds a horizontal line to the parent element.

8. <code>&lt;li&gt;</code> - Used to define an item within a list.

9. <code>&lt;menu&gt;</code> - A semantic alternative to &lt;ul&gt; tag.

10. <code>&lt;ol&gt;</code> - Defines an ordered list.

11. <code>&lt;p&gt;</code> - Defines a paragraph.

12. <code>&lt;pre&gt;</code> - Used to represent preformatted text. Typically rendered in the web browser using a monospace font.

13. <code>&lt;ul&gt;</code> - Defines an unordered list.

#### Inline Tags

1. <code>&lt;a&gt;</code> - An anchor link to another HTML doc.

2. <code>&lt;abbr&gt;</code> - Specifies that the containing text is an abbreviation or acronym.

3. <code>&lt;b&gt;</code> - Bolds the containing text. used to indicate importance, use &lt;strong&gt; instead.

4. <code>&lt;br&gt;</code> - A line break. Moves the subsequent text to a new line.

5. <code>&lt;cite&gt;</code> - Defines the little creative work, for example a book, a poem, a song, a movie, a painting, or a sculpture. The text in it is usually rendered in italics.

6. <code>&lt;code&gt;</code> - Indicates that the containing text is a block of computer code.

7. <code>&lt;data&gt;</code> - Indicates machine-readable data.

8. <code>&lt;em&gt;</code> - Emphasizes the containing text.

9. <code>&lt;i&gt;</code> - The containing text is displayed in italics. Used to indicate idiomatic text or technical terms.

10. <code>&lt;mark&gt;</code> - The containing text should be marked or highlighted.

11. <code>&lt;q&gt;</code> - The containing text is a short quotation.

12. <code>&lt;s&gt;</code> - Displays the containing text with a strikethrough or line through it.

13. <code>&lt;samp&gt;</code> - The containing text represents a sample.

14. <code>&lt;small&gt;</code> - Used to represent small text, such as copyright and legal text.

15. <code>&lt;span&gt;</code> - A generic element for grouping content for CSS styling.

16. <code>&lt;strong&gt;</code> - Displays the containing text in bold. Used to indicate the importance.

17. <code>&lt;sub&gt;</code> - The containing text is subscript text, displayed with a lowered baseline.

18. <code>&lt;sup&gt;</code> - The containing text is is superscript text, displayed with a raised baseline.

19. <code>&lt;time&gt;</code> - A semantic tag used for displaying both dates and times.

20. <code>&lt;u&gt;</code> - Displays the containing text with a solid underline.

21. <code>&lt;var&gt;</code> - The containing text is a variable in a mathematical expression.

#### Embedded content and media tags

1. <code>&lt;audio&gt;</code> - Used to embed auido in webpages.

2. <code>&lt;canvas&gt;</code> - Used to render 2D and 3D graphics on web pages.

3. <code>&lt;embed&gt;</code> - Used as containing element for external content provided by a external application such as a media player or plud-in application.

4. <code>&lt;iframe&gt;</code> - Used to embed a nested webpage. You will learn more about iframes later.

5. <code>&lt;img&gt;</code> - Embeds an image on the web page.

6. <code>&lt;object&gt;</code> - Similar to &lt;embed&gt; but the content is provided by a web browser plug-in.

7. <code>&lt;picture&gt;</code> - An element which contains one img element or more source elements to offer alternative images for different devices.

8. <code>&lt;video&gt;</code> - Embeds a video on the web page.

9. <code>&lt;source&gt;</code> - Specifies media resources for picture, audio and video elements.

10. <code>&lt;svg&gt;</code> - Used to define Scalable vector Graphics within the web page.

#### Table Tags

1. <code>&lt;table&gt;</code> - Defines a table element to display tabular data within the web page.

2. <code>&lt;thead&gt;</code> - Represents the header content of the table. Typically contains one tr element.

3. <code>&lt;tbody&gt;</code> - Represents the main content of the table. Contains one or more tr elements.

4. <code>&lt;tfoot&gt;</code> - Represents the footer content of the table. Contains one tr element.

5. <code>&lt;tr&gt;</code> - Represents a row in a table. Contains one or more td elements when used within tbody or tfoot. When used within thead, contains one or more th elements.

6. <code>&lt;td&gt;</code> - Represents a cell of a table. Contains the text content of the cell.

7. <code>&lt;th&gt;</code> - Defines a header cell of a table. Contains the text content of the header.

8. <code>&lt;caption&gt;</code> - Defines the caption of the table element.

9. <code>&lt;colgroup&gt;</code> - Defines a semantic group of one or more columns in a table for formatting.

10. <code>&lt;col&gt;</code> - Defines a semantic column in a table.

## Semantic tags in action

- 
