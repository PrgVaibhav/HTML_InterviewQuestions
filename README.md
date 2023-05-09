# HTML Interview Questions and Answers

#### Want CSS Questions Visit [Here](https://github.com/PrgVaibhav/CSS_Interview_Questions)
#### Want JS Questions Visit [Here](https://github.com/PrgVaibhav/JS_Interview_Questions)

> We will cover a variety of HTML questions ranging from basic to advanced. Let's get started!

## Question 1: What is HTML?

HTML stands for Hypertext Markup Language. It is a markup language used to create web pages and applications. HTML provides a structure for content on the web, such as text, images, and links. It is the foundation for creating web pages and is used in conjunction with other technologies such as CSS and JavaScript.

## Question 2: What are some new features of HTML5?

HTML5 introduced several new features, including:

-   New semantic elements such as header, footer, section, and article
-   The canvas element for drawing graphics and animations
-   The video and audio elements for embedding multimedia content
-   Improved form controls, including new input types such as email and date
-   The ability to store data locally with the localStorage and sessionStorage objects
-   Support for geolocation and web workers

## Question 3: What is the difference between HTML and XHTML?

HTML and XHTML are both markup languages used for creating web pages, but there are some differences between them.

HTML is more forgiving than XHTML and allows for more flexibility in the syntax. XHTML, on the other hand, is stricter and requires well-formed XML syntax.

HTML allows for empty tags, while XHTML requires all tags to be closed. HTML also allows for attribute values to be unquoted, while XHTML requires all attribute values to be quoted.

## Question 4: What are the different types of HTML elements?

There are two main types of HTML elements:

1.  Block-level elements: These elements create a block of content on the page and take up the full width of the parent container. Examples include div, h1, p, and ul.
    
2.  Inline elements: These elements are contained within a block-level element and do not create a new line. Examples include span, a, and img.
    

## Question 5: What is the purpose of semantic HTML?

Semantic HTML is the use of HTML markup to reinforce the meaning of content on a web page. By using semantic HTML, we can make our web pages more accessible and easier to understand for both humans and machines.

Semantic HTML uses descriptive tags such as header, footer, section, and article instead of generic tags like div and span. This helps search engines and screen readers to understand the content and structure of the page.

## Question 6: What is the difference between a div and a span?

A div is a block-level element used to create a container for content on a web page. It is typically used to group related elements together and apply styles to them.

A span, on the other hand, is an inline element used to apply styles to a specific section of text within a block-level element. It is often used for small pieces of text, such as individual words or phrases.

## Question 7: How do you add comments in HTML?

In HTML, comments are added using the following syntax:

htmlCopy code

`<!-- This is a comment -->` 

Anything between the `<!--` and `-->` is treated as a comment and is ignored by the browser. Comments are often used to document code or temporarily remove code for testing purposes.

## Question 8: What is the purpose of the alt attribute in an img tag?

The `alt` attribute in an `img` tag specifies alternative text that is displayed if the image cannot be loaded or if the user is using a screen reader. This text is also used by search engines to understand the content of the image.

The `alt` attribute should be descriptive and provide information about the content of the image. It is important for accessibility and SEO purposes.

## Question 9: What is the difference between a relative and absolute URL?

A relative URL is a URL that is relative to the current page. It only includes the path to the file or resource and does not include the domain name. For example, if the current page is `http://example.com/page1.html` and you want to link to `http://example.com/page2.html`, you can use a relative URL of `page2.html`.

An absolute URL, on the other hand, includes the full path to the file or resource, including the domain name. For example, `http://example.com/page2.html` is an absolute URL.

## Question 10: What is the purpose of the meta tag in HTML?

The `meta` tag in HTML is used to provide metadata about the web page. This metadata includes information such as the page title, author, description, and keywords.

The `meta` tag is also used to specify the character set used.

## Question 11: What is the difference between HTML and CSS?
HTML is used to define the structure and content of a web page, while CSS is used to style the presentation of that content.

## Question 12: What is the role of the `<head>` element in HTML?
The `<head>` element is used to provide metadata about the document, such as the document's title, author, and keywords. It is not visible to the user.

## Question 13: How do you create a link that opens in a new tab?
You can create a link that opens in a new tab using the target attribute with a value of "_blank". For example: `<a href="https://www.example.com" target="_blank">Example Link</a>`

## Question 14: What is the difference between the `<ul>` and `<ol>` tags?
The `<ul>` tag is used to create an unordered list, while the `<ol>` tag is used to create an ordered list.

## Question 15: What is the purpose of the `data-*` attribute in HTML?

The `data-*` attribute allows you to store custom data for an HTML element, which can be accessed using JavaScript or CSS.

## Question 16: How do you make an HTML element draggable?

You can make an HTML element draggable using the "draggable" attribute with a value of "true". You can also use JavaScript to handle the drag events.

## Question 17: What is the purpose of the tabindex attribute in HTML?

The tabindex attribute specifies the order in which elements should be focused when the user presses the tab key.

## Question 18: How do you create a custom HTML attribute?

You can create a custom HTML attribute by prefixing the attribute name with "data-". For example:
`<div data-custom-attribute="value">`

## Question 19: What is the purpose of the "rel" attribute in the `<a>` tag?

The `rel` attribute specifies the relationship between the current document and the linked document, such as "stylesheet" for a CSS file or "nofollow" for a link that should not pass PageRank.

## Question 20: How do you embed a video in HTML?

You can embed a video in HTML using the `<video>` tag and the source attribute. For example: `<video width="320" height="240" controls> <source src="movie.mp4" type="video/mp4"> </video>`
