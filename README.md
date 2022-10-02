**week 1: HTML in depth**<br>

1. [Course Introduction](#course-introduction)
1. [Semantic and Meta Tags](#semantics-and-meta-tags)

# Course Introduction

1. [Intro to HTML and CSS in depth](#introduction-to-html-and-css-in-depth)
1. [How are HTML and CSS used in the real-world?](#how-are-html-and-css-used-in-the-real-world)

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

1. [Semantic Tags and and Why We Need Them](#semantics-tags-and-why-we-need-them)
1. [Practice Quiz](#practice-quiz-semantic-tags)
1. [Metadata](#metadata)
1. [Metadata Cheat Sheet](#metadata-cheat-sheet)
1. [Bare Bones Layout](#bare-bones-layout)
1. [Practice Quiz: Metadata](#practice-quiz-metadata)
1. [Layout Design](#layout-design)
1. [UX with Meta tags](#ux-with-meta-tags)

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

## Practice Quiz: Semantic Tags

1. **What is the purpose of semantic HTML tags?**<br>
   _ans._ To describe the meaning of the HTML doc.

2. **What is the impact of using semantic tags in your HTML doc?**<br>
   _ans._ It allows search engines to understand the HTML doc and allows accessibility software to understand the HTML doc.

3. **What type of content is the &lt;article&gt; semantic HTML element appropriate for?**<br>
   _ans._ Blog posts, New articles, and Forum posts.

4. **Which element is most suitable for describing the navigation of the webpage?**<br>
   _ans._ &lt;nav&gt;

5. **You need to add a copyright notice to the bottom of your webpage, which semantic html tag is most suitable to use?**<br>
   _ans._ &lt;footer&gt;

6. **You need to indicate that an action of text in a &lt;p&gt; element is important. Which semantic tag whould you use?**<br>
   _ans._ &lt;strong&gt;

7. **You need to display a list of descriptions on a webpage. Which tag is best-suited semantically?**<br>
   _ans._ &lt;dl&gt;

## Metadata

- It is pretty clear that each person uses a search engine on a web browser to find their favorite things or their queries. Everytime you do a searh, the search engine returns a list of results that are relevant to the searched keywords, but how does actually happen?

- A major part of launching a website is a process called **Search Engine Optimization** or **SEO**. This process involves making improvements to a website's content semantics and delivery to improve its ranking in search results. When a search engine analyzes an htnl doc of a website, it finds a link to another html doc, it follows the link to that document and continues following links until it is finished analyzing the entire site. Every search engine has its own algorithm for ranking websites based on the content of sites. But for now just let's focus on how **meta** tags influence the ranking of websites.

- Meta tags define metadata about a webpage. It is the data about other data which in this case is data about the webpage. Meta tags are usually added inside the **head** element of an html doc, and content of head element is not displayed on the web browser. Remember that when we called out some basic examples, there is no closing tag for meta tags, unlike other elements. Each meta element consists of two attributes: **name** and **content**. The **name** attribute defines the name of the meta data of that certain website while **content** specifies the value of the meta data.

- Let's checkout some of the examples of meta data. The **author** metadata specifies the author of the webpage. Here name attribute is author and the content can be a person or company.

## Metadata Cheat Sheet

### Name

- The name of the property can be anything you like, although browsers usually expect a value they understand and can take an action upon. An example would be <code>&lt;meta name="author" content="name of author"&gt;</code> to state the author of the page.

### Content

- The content field specifies the property's value. For example, you can use <code>&lt;meta name="language" content="english"&gt;</code>, to specify the language of the webpage to search engines.

### Charset

- The charset is a special field that lets you specify the character encoding used for the page so that the browser can display it properly. The most frequently used is **UTF-8**, and you would add it to your HTML header as: <code>&lt;meta charset="UTF-8"&gt;</code>.

### HTTP-equiv

- This attribute stands for **HTTP equivalent**, and it's used to simulate http response headers. This is rare to see, and it's recommended to use http headers over html http-equiv meta tags. For example, the following tag would instruct the browser to refresh the page every 30 minutes: <code>&lt;meta http-equiv="refresh" content="30"&gt;</code>.

## Basic Meta Tags(meta tags for SEO)

- The description meta tag provides a brief description of the webpage.

```html
<meta name="description" />
```

- Title meta tag defines the title of the webpage.

```html
<meta name="title" />
```

- Author meta tag specifies the author of the page.

```html
<meta name="author" content="name" />
```

- Language meta tag specifies the language.

```html
<meta name="language" content="english" />
```

- The following meta tag tells search engines how to crawl or index a certain page.

```html
<meta name="robots" content="index, follow" />
```

- The following says Google not to show the sitelinks search box for your page when showing search results.

```html
<meta name="google" />
```

- This tells Google you don't want to provide an automatic translation for your page if the user uses a different language.

```html
<meta name="googlebot" content="notranslate" />
```

- This specifies the last modified date and time on which you have made certain changes.

```html
<meta name="revised" content="Friday, September 16th, 2022, 12:09pm" />
```

- The following specifies the expected audience for your page.

```html
<meta name="rating" content="safe for kids" />
```

- This specifies a Copyright.

```html
<meta name="copyright" content="Copyright 2022" />
```

### HTTP-equiv Tags

- This describes the format of the doc returned by the server.

```html
<meta http-equiv="content-type" content="text/html" />
```

- This specifies the format of the styling doc.

```html
<meta http-equiv="default-style" />
```

- Following specifies the duration of the page before it's considered state.

```html
<meta http-equiv="refresh" />
```

- This specifies the language of the page.

```html
<meta http-equiv="Content-language" />
```

- Following instructs the browser how to cache your page.

```html
<meta http-equiv="Cache-Control" content="no-cache" />
```

### Responsive Design Meta Tags

- This indicates that telephone numbers should appear as hypertext links that can be clicked to make a phone call.

```html
<meta name="format-detection" content="telephone=yes" />
```

- It specifies that the page can be properly visualized on mobile devices.

```html
<meta name="HandheldFriendly" content="true" />
```

- The following specifies the area of the window in which web content can be seen.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

## Bare Bones Layout

- An important part of being a web devloper is not only the tools you use, such as your integrated devlopment environment, but also the repository of knowledge and code templates you build up over time.

- Let's learn one of these templates, which will help in building webpages easily and quickly. In our example template, we've an html document called <code>index.html</code>, a JS folder and a CSS folder. Inside the JS folder, there's a file called <code>script.js</code> and there's no content in this file for now. Similarly there's a file called <code>style.css</code> inside the CSS folder. Again the style.css is all empty. It is best to use some example script.js and style.css files in their respective directories.

- In this basic template, remember that the style.css file is always placed inside the head element of index.html, using the <code>&lt;link&gt;</code> tag. Like that the script.js can be linked using <code>&lt;script&gt;</code>, inside the footer of body element.

## Practice Quiz: Metadata

1. **What are some of the main characteristics of meta tags?**<br>
   _ans._ They define metadata about an HTML document, namely information about data; they don't have a visual representation in your pages; they are very important for SEO.

2. **What are some of the most important Meta tags you should use for good SEO?**<br>
   _ans._ Description, Title, Image alt attributes.

3. **Which meta tag is used to specify the character encoding for the HTML document?**<br>
   _ans._ charset

4. **Which meta tag and properties do you need to set to make your pages responsive in desktop and mobile devices?**<br>
   _ans._

```html
<meta name="”viewport”" content="”width" ="window-width," initial-scale="1”" />
```

5. **How do you tell Google you don't want to provide an automation translation for your page if the user uses a different language?**<br>
   _ans._

```html
<meta name="”googlebot”" content="”notranslate”" />
```

6. **Which statements are true about HTTp-equiv tags?**<br>
   _ans._ They can simulate HTTP response headers; they are useful if you don't have access to the server configuration.

## Layout Design

- As you build web pages throughout your career, you'll notice that many pages follow similar layouts and structures. This is the outcome of many years of researh into user interface design and user experience.

### Top Navbar Layout

- Websites often have a top navbar layout to provide a set of essential anchor links to the user. These typically link to the main areas of the website, such as product pages. This provides the visitor to the website with a consistent navigation experience.<br>
  ![Navbar layout](../main/images/navbar-layout.png)

### Carousel Layout

- Product and online-shopping websites often use a large carsoul on their homepage to highlight their featured products, offers and discounts. The carousel contains content items that will keep rotating through the carousel area at a fixed interval.<br>
  ![Carousel layout](../main/images/carousel-layout.png)

### Blog Layout

- The blog layout is used to feature multiple content items of differing importance. It is often seen on news websites where new articles will appear on the page each day based on current happenings.<br>
  ![Blog layout 1](../main/images/blog-layout-1.png)

- The layout typically features different-sized feature areas followed by a series of article summary areas that link to full articles.
  ![Blog layout 2](../main/images/blog-layout-2.png)

### Dashboard Layout

- Dashboard layouts are often used in enterprise software for managing various web applications. They typically feature a sidebar for navigation with the main content area containing forms for configuration or reporting data such as graphs and tables. This trendy layout provides a good user experience for business users.
  ![Dashboard layout](../main/images/dashboard-layout.png)

## UX with Meta tags

- Social networks are a great tool to share content with friends and family, and even with co-workers and business partners. When you share a link, most social networks generate a preview of the link to let users know what the shared webpage about.

- You will learn how Meta tags help webpages create preview of other webpages. By using Meta tags to control what information is displayed to users, you can get more clicks when you share your websites. But the meta tags web devlopers use this purpose are different from the traditional SEO Meta tags as the SEO Meta tags are oriented towards search results, not direct links.

- Facebook's rapid growth led to millions of users sharing thousands of links everyday. To improve the UX, they had to find a way to display information about a website before a user clicks on the link. To address this challenge, Facebook established the **Open Graph Protocol** in 2010. The Open Graph Protocol is set of Metadata rules that allow webpages to describe themeselves to social networks.

- There are a lot of Meta tags available within Open Graph Protocol, but before we dive into that, let's see how the Open Graph Protocol Metadata is defined. We've already learned that Meta tags are usually placed inside the <code>&lt;head&gt;</code> element of an html document, the Open Graph Protocol also uses Meta tags added to the head element, but there's a slight difference.
  <br>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Regular SEO oriented Meta tags -->
    <meta name="author" content="Ritukanta Reddy" />

    <!-- One of the Open Graph Protocol Meta tags -->
    <meta property="og:title" content="My First Web Page" />
  </head>
  <body></body>
</html>
```

- The Open Graph Protocol use the <code>property</code> attribute instead of <code>name</code> attribute, to define the Metadata name. Then, like regular SEO Meta tags, it uses the <code>content</code> attribute to define the Metadata value. Each property in the Open Graph Protocol starts with <code>og</code> followed by a colon (og:), as a convention to identify it as an Open Graph Protocol related tag.

- The Open Graph Protocol requires that you must always include four properties on a webpage. There are **title**, **type**, **url** and **image**.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- title property of Open Graph Protocol -->
    <meta property="og:title" content="My First Web Page" />

    <!-- type property -->
    <meta property="og:type" content="website" />

    <!-- url property -->
    <meta property="og:url" content="https://example.com/" />

    <!-- image property -->
    <meta property="og:image" content="https://example.com/me.png" />
  </head>
  <body></body>
</html>
```

- The title property defines the title of the page, this is the text that will appear in the preview. The type property defines the type of content, such as website, videos, music or article. The URL property defines the permanent web address that the social networks must use for the specific page. The image property defines a url to an image that must display when the website is shared. Together these Open Graph Protocol properties enables social media platforms to create a preview of the shared web link.

- There are also several other optional properties: the description property provides a description of the webpage. The locale property describes the language and territory of the webpage's content. And the site_name property describes the name of the overall website that the webpage belongs to.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- other Open Graph Protocol optional properties -->
    <meta
      property="og:description"
      content="My webpage is all about bla bla bla!"
    />

    <!-- "en" stands for English language and "US" stands for United States, territory -->
    <meta property="og:locale" content="en_US" />

    <meta property="og:site_name" content="Dale's Webpage" />
  </head>
  <body></body>
</html>
```
