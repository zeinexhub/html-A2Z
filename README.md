### Introduction

---

- Markup Languages

> Markup languages are systems for annotating text in a way that makes it readable by both humans and computers. They use tags to define elements within a document, specifying how the text should be structured, formatted, and displayed. For example, HTML uses tags like `<p>` for paragraphs and `<h1>` for headings to structure web content, while XML uses custom tags to define data structures for various applications.

- Frontend Development

> Frontend development is the practice of creating the user interface and user experience of a website or web application. It focuses on the parts of a website that users directly interact with, such as buttons, text, images, and navigation menus. Frontend developers use languages like HTML, CSS, and JavaScript to build these interactive elements and ensure they are visually appealing and function correctly across different devices and browsers.

- HTML

> HTML (HyperText Markup Language) is the standard markup language for creating web pages. It provides the structure of a webpage, defining elements like headings, paragraphs, images, and links using tags. Web browsers interpret these tags to display the content to users.

- CSS

> CSS, or Cascading Style Sheets, is a language used to describe the look and formatting of a document written in HTML. It controls things like the layout, colors, fonts, and overall visual presentation of web pages, ensuring a consistent and appealing user experience across different devices and screen sizes.

- JavaScript

> JavaScript is a programming language primarily used to create interactive and dynamic effects within web browsers. It allows developers to implement complex features on web pages, updating content dynamically, controlling multimedia, animating images, and much more, enhancing the user experience beyond static HTML and CSS.

### How the web works

---

- HTTP

> HTTP (Hypertext Transfer Protocol) enables browser-server communication through requests and responses. Stateless protocol using methods like GET and POST. HTTPS provides encrypted security. Newer versions (HTTP/2, HTTP/3) offer improved performance. Fundamental for web development understanding.

- Domain Name

> Domain names are human-friendly web addresses (e.g., google.com) substituting numerical IP addresses. Comprise second-level ("google") and top-level (".com") domains. Registered through registrars, essential for branding and online presence. DNS translates names to IP addresses for accessibility.

- Web Hosting

> Web hosting stores website files on servers, making sites accessible online. Types include shared (multiple sites per server) and dedicated (exclusive server) hosting. Providers offer additional services like email, domains, and security certificates. Critical for website performance and accessibility.

- DNS

> DNS (Domain Name System) translates human-readable domain names into IP addresses through a global, decentralized server network. Enables easy internet navigation by converting names like www.example.com to numeric addresses browsers can connect to.

- Browsers

> Web browsers request and display websites by interpreting HTML, CSS, and JavaScript. Use rendering engines (Blink, Gecko) for display and JavaScript engines (V8) for code execution. Handle security, bookmarks, history, and user interactions for web navigation.

- SEO

> Search Engine Optimization, or SEO, is the practice of improving your website to increase its visibility when people search for products or services related to your business in search engines like Google. The better visibility your pages have in search results, the more likely you are to garner attention and attract prospective and existing customers to your business. A related concept, Generative Engine Optimization (GEO), focuses on optimizing content for AI-powered search experiences, ensuring your information is accurately and effectively presented in AI-generated summaries and responses.

### HTML

---

- Tags and Attributes

> Tags and attributes are fundamental building blocks of HTML. Tags define the structure and content of a webpage, such as headings, paragraphs, and images. Attributes provide additional information about HTML elements, modifying their behavior or appearance, like specifying the source of an image or the destination of a link.

- Case Insensitivity

> HTML isn't picky about capitalization. You can write tags and attributes using uppercase, lowercase, or a mix of both. For example, `<html>`, `<HTML>`, and `<Html>` all work the same way. While browsers understand all these variations, it's generally considered good practice to stick to lowercase for better readability and consistency in your code.

- Entities

> HTML entities are special codes used to represent reserved characters or characters that are difficult to type directly in HTML. They allow you to display characters like angle brackets (< and >), ampersands (&), and copyright symbols (©) that have special meanings in HTML or are not readily available on a standard keyboard. Using entities ensures that these characters are displayed correctly in a web browser.

- Comments

> Comments in HTML are notes that you can add to your code to explain what's going on, make reminders, or temporarily disable parts of your code. These comments are not displayed in the browser, so they're only visible when someone views the source code. To create a comment in HTML, you enclose your text within `<!--` and `-->`. Anything between these tags will be ignored by the browser.

- Whitespaces

> Whitespaces in HTML refer to the spaces, tabs, and line breaks that are used to format the code. Browsers typically collapse multiple consecutive whitespaces into a single space when rendering the content. While using whitespaces can improve the readability of your HTML code, they generally don't affect how the page is displayed to the user.

### Basic Tags

---

- !DOCTYPE Declaration

> The `<!DOCTYPE>` declaration is an instruction to the web browser about the HTML version used to write the page. It's placed at the very top of an HTML document, before the `<html>` tag, and ensures that the browser renders the page in "standards mode," following the correct specifications for that HTML version. Technically, It is not an HTML tag itself.

- HTML Element

> The `<html>` element is the root element of an HTML page. It tells the browser that this is an HTML document. All other HTML elements (except for the `<!DOCTYPE>` declaration) must be descendants of the `<html>` element.

- Body Tag

> The `<body>` tag in HTML defines the main content of an HTML document. It contains all the visible elements of a webpage, such as text, images, links, tables, lists, and more. Think of it as the container for everything you actually see and interact with on a website.

- head

> The `<head>` element in HTML acts as a container for metadata (data about data) about the HTML document. This metadata isn't displayed on the page itself, but it provides information like the document's title, character set, linked stylesheets, scripts, and other important configurations that help browsers and search engines understand and process the HTML document correctly.

- Meta Tags

> Meta tags are HTML elements that provide metadata about a webpage. This data is not displayed on the page itself but is used by browsers, search engines, and other web services to understand the content and purpose of the page. They are placed within the `<head>` section of an HTML document and can specify information like character set, description, keywords, author, and viewport settings.

### Textual Tags

---

- h1 to h6

> Headings are used to define the titles and subtitles within a document. HTML provides six levels of headings, from `<h1>` (the most important and largest) to `<h6>` (the least important and smallest). They help structure content and improve readability by creating a clear hierarchy.

- Title Tag

> The `<title>` tag in HTML defines the title of the HTML document. This title is displayed in the browser's title bar or tab, and it's also used for bookmarking pages and in search engine results. It's placed within the `<head>` section of the HTML document.

- p Tag

> The `<p>` tag in HTML defines a paragraph. Browsers automatically add a single blank line before and after each paragraph, creating a clear separation between blocks of text. It's a block-level element, meaning it occupies the full width available to it and starts on a new line.

- Horizontal Rule

> The `<hr>` tag in HTML creates a thematic break in an HTML page and is most often displayed as a horizontal rule. It's used to separate content visually, like dividing sections of text or indicating a change in topic. The `<hr>` tag is an empty element, meaning it doesn't have a closing tag.

- br Tag

> The `<br>` tag in HTML creates a line break within a text block. It's used to start a new line without creating a new paragraph, effectively forcing the text that follows to appear on the next line. It is an empty element, meaning it has no closing tag.

- b / strong

> The `<b>` and `<strong>` tags in HTML are used to make text appear bold. While both achieve a similar visual effect, the `<b>` tag is primarily for stylistic purposes, indicating text that should be visually distinguished without necessarily conveying importance. On the other hand, the `<strong>` tag signifies that the enclosed text has strong importance, seriousness, or urgency.

- pre

> The `<pre>` tag in HTML represents preformatted text. Text inside a `<pre>` element is displayed in a fixed-width font, and it preserves both spaces and line breaks. This is useful for displaying code snippets, ASCII art, or any other text where formatting is important.

- i / em

> The `<i>` and `<em>` tags in HTML are used to emphasize text. The `<i>` tag represents text that is set off from the normal prose, such as technical terms, foreign words, or thoughts. The `<em>` tag represents stress emphasis of its contents. While both may render similarly in browsers (often as italicized text), `<em>` has semantic meaning, indicating importance, whereas `<i>` is purely presentational.

- Mark Text

> The `<mark>` tag in HTML is used to highlight specific parts of text within a larger block of content. It's primarily intended to draw the reader's attention to these sections, often because they are relevant to the user's current activity or search query. The default styling usually renders the marked text with a yellow background, but this can be customized using CSS.

- Subscript Text

> The `<sub>` tag in HTML is used to display text as subscript. Subscript text appears slightly below the normal line of text and is typically rendered in a smaller font size. It's commonly used for mathematical formulas, chemical formulas, or footnotes.

- sup

> The `<sup>` tag in HTML is used to display text as superscript. Superscript text appears slightly above the normal line of text and is typically rendered in a smaller font size. It's commonly used for things like exponents, ordinal numbers (e.g., 1st, 2nd), and footnotes.

- Links

> Links, also known as hyperlinks, are elements that connect one web resource to another. They allow users to navigate between different pages on the same website or to external websites. Links are created using the `<a>` (anchor) tag, and they can point to various types of resources, including HTML pages, images, documents, and more.

### Grouping text

---

- div

> The `<div>` element is a generic container for flow content, which in simpler terms means it's a way to group together other HTML elements. It doesn't inherently represent anything specific on its own, but it's commonly used to structure and style sections of a webpage. It has no effect on the content or layout until styled in some way using CSS (e.g., styling is directly applied to it, or some kind of layout model like Flexbox is applied to its parent element).

- span element

> The `<span>` element is an inline container used to mark up a part of a text, or a part of a document. It is used to group elements for styling purposes or because they share attributes such as lang or dir. It doesn't inherently represent anything on its own, but becomes useful when combined with CSS or JavaScript to target specific sections of text.

### Standard attributes

---

- id Attribute

> The `id` attribute in HTML provides a unique identifier for an element within a document. This identifier allows you to target and manipulate that specific element using CSS styles, JavaScript code, or even link directly to it using fragment identifiers in URLs (e.g., #section1). Each id value should be unique within the entire HTML document to ensure proper functionality.

- Class Attribute

> The `class` attribute in HTML is used to specify one or more class names for an HTML element. These class names can then be used by CSS and JavaScript to style and manipulate specific elements or groups of elements that share the same class. Essentially, it's a way to categorize and target elements for styling and scripting purposes.

- Data Attributes

> Data attributes are special attributes in HTML that allow you to store extra information directly within HTML elements. These attributes start with `data-` followed by a name of your choosing. They are primarily used to store custom data private to the page or application, meaning they are not intended for use by search engines or other external services. This data can then be accessed and used by JavaScript to enhance the functionality and interactivity of your web pages.

- Style Attribute

> The `style` attribute in HTML allows you to apply CSS (Cascading Style Sheets) directly to individual HTML elements. It's used to define inline styles, overriding external stylesheets or default browser styles. You can set properties like color, font, size, and layout directly within the HTML tag.

### Lists and Types

---

- Ordered lists

> Ordered lists in HTML are used to display a series of items in a specific order. Each item in the list is typically numbered, allowing readers to easily follow a sequence or ranking. The `<ol>` tag is used to create an ordered list, and each list item is defined using the `<li>` tag.

- Unordered lists

> Unordered lists present items in a bulleted format, where the order of the items is not significant. They are used to group related content together without implying any specific sequence or priority. Each item in the list is typically marked with a bullet point, making it easy to visually distinguish and scan the list's contents.

- Definition lists

> Definition lists in HTML are used to present terms and their corresponding definitions. They are structured using three main elements: `<dl>` (definition list), `<dt>` (definition term), and `<dd>` (definition description). The `<dl>` element acts as the container for the entire list, while each term is marked with `<dt>` and its associated description is enclosed within `<dd>`. This structure allows for a clear and organized presentation of terms and their meanings.

- Nested Lists

> Nested lists in HTML allow you to create lists within lists, forming a hierarchical structure. This is achieved by placing one list (either ordered `<ol>` or unordered `<ul>`) inside a list item `<li>` of another list. This creates a sub-list that is visually indented, helping to organize information into related categories and subcategories.

- Table tag

> The HTML `<table>` tag is used to create tables on web pages. It organizes data into rows and columns, similar to a spreadsheet. Within the `<table>` tag, you'll find tags like `<tr>` for table rows, `<th>` for table headers, and `<td>` for table data cells, which define the structure and content of the table.

### Embedding Media

---

- Images

> Images are a way to display visual content on a webpage. They are added to HTML documents using the `<img>` tag, which links to an image file. Attributes like src (source), alt (alternative text), width, and height are used to specify the image's location, description, and dimensions.

- img vs figure

> The `<img>` tag in HTML is used to embed a simple image directly into a webpage. It requires a src attribute to specify the image source. On the other hand, the `<figure>` element represents self-contained content, like an image, illustration, diagram, code snippet, etc., that is referenced as a single unit. It is typically used with the `<figcaption>` element to provide a caption for the figure.

- Priority Hints

> Priority Hints in HTML allow developers to indicate the relative priority of fetching resources like images. This helps the browser decide which images to load first, potentially improving page load times and user experience by prioritizing content that is immediately visible or more important to the user. This is achieved using the `fetchpriority` attribute.

- Audio

> Audio on the web involves incorporating sound files into HTML documents. This allows users to listen to music, podcasts, or other audio content directly within a webpage. The HTML <audio> element is used to embed audio, providing attributes for controlling playback, displaying controls, and specifying multiple source files for browser compatibility.

- Video

> The `<video>` element in HTML is used to embed video content directly into a webpage. It allows you to display video files, control playback, and provide options for users to interact with the video, such as pausing, playing, adjusting volume, and viewing in fullscreen. The element supports various video formats and attributes to customize the video's appearance and behavior.

- Content Security Policy

> (CSP) is a security standard introduced to prevent cross-site scripting (XSS), clickjacking, and other code injection attacks. It works by allowing you to define a whitelist of sources that the browser is permitted to load resources from. This helps to control the origins of scripts, stylesheets, images, and other assets, effectively reducing the attack surface of a web application.

- iframe

> An `iframe` (Inline Frame) is an HTML element that allows you to embed another HTML document within the current HTML page. It essentially creates a window within your webpage where you can display content from a different source, such as another website, a video, or even another HTML file on your own server.

### Forms

---

- Labels and Inputs

> Labels and inputs are fundamental building blocks for creating forms in HTML. Labels provide descriptive text that tells users what information is expected in a corresponding input field. Input elements, on the other hand, are the interactive controls where users can enter data, such as text, numbers, dates, or make selections from options. They work together to create a user-friendly and accessible form experience.

- File Uploads

> File uploads allow users to send files from their computer to a web server. This is typically achieved through an HTML form that includes an `<input>` element with the type attribute set to "file". When the form is submitted, the selected file(s) are sent to the server for processing and storage.

- Form Validation

> Form validation is the process of checking if the information a user provides in a form is correct and complete before it's submitted. This ensures that the data received is accurate and meets the required format, preventing errors and improving data quality. It can involve checking for things like required fields, correct email addresses, valid date formats, and acceptable password strength.

- Form Constraints

> HTML form constraints are rules you set on form fields to control what kind of data users can enter. These constraints help ensure that the information submitted is valid and meets your requirements. For example, you can specify that a field is required, set a minimum or maximum length for text, or restrict the input to a specific data type like a number or email address. These limitations are defined using HTML attributes directly within the form elements.

### Semantic Markup

---

> Semantic markup uses HTML tags to convey the meaning and structure of content, rather than just its appearance. This approach makes web pages more accessible to both humans and machines by providing context about the different parts of the content, such as headings, paragraphs, articles, and navigation menus. By using semantic elements, developers create more organized and understandable code, which improves search engine optimization and overall website usability.

- Abbreviation Element

> The `<abbr>` tag in HTML represents an abbreviation or acronym. It's useful for providing a full description of the abbreviated term when the user hovers over it, improving accessibility and clarity. The title attribute is used to specify the expanded form of the abbreviation.

- The cite element

> The `<cite>` element in HTML is used to define the title of a creative work (e.g., a book, article, song, movie, painting, sculpture, etc.). It's typically used to provide a reference or citation for a source. The content inside the `<cite>` element is often rendered in italics by browsers, but this styling can be overridden with CSS.

- dfn

> The `<dfn>` element in HTML represents the defining instance of a term. It's used to indicate the specific location where a word or phrase is being defined for the first time within a document. Typically, the term being defined is included within the <dfn> tags, and often a definition or explanation of the term is provided nearby.

- address

> The `<address>` element in HTML represents contact information for the author or owner of a document or article. This can include physical addresses, email addresses, phone numbers, and social media links. It's typically used within the `<footer>` of a page or section to provide contact details.

- blockquote

> The `blockquote` element in HTML represents a section of text that is quoted from another source. It's used to indicate that the enclosed content is an extended quotation, often displayed with indentation or other visual cues to distinguish it from the surrounding text. The `cite` attribute can be used to specify the URL of the source document or message.

- q

> The `<q>` element in HTML represents a short, inline quotation. Browsers typically render this element with quotation marks around the content it contains. It's designed for brief quotes that fit within a paragraph, as opposed to longer, block-level quotations that would use the `<blockquote>` element.

- del

> The `<del>` element in HTML represents text that has been deleted or removed from a document. Browsers typically render deleted text with a strikethrough, visually indicating that the content is no longer valid or accurate. This element is useful for showing edits and revisions in a clear and understandable way.

- s

> The `<s>` element in HTML represents content that is no longer accurate or relevant. It indicates things that are no longer correct, accurate, or no longer relevant. Browsers typically render this element with a strikethrough, visually indicating the text has been removed or is no longer valid.

- ins element

> The `<ins>` element in HTML represents text that has been inserted into a document. It's used to indicate additions or updates to content, often displayed with an underline to visually distinguish it from the original text. This element helps to clearly communicate revisions and modifications within a webpage.

- Header

> The `<header>` element represents introductory content, typically containing a group of introductory or navigational aids. It might contain a heading, logo, search form, or other relevant content. It's used to define the top section of a document, article, or section.

- Nav

> The `<nav>` element in HTML is used to define a section of a page that contains navigation links. It's intended for major navigational blocks, like a site's menu, a table of contents, or a set of breadcrumbs. Using <nav> helps structure your content and makes it more accessible to screen readers and search engines by clearly identifying navigation sections.

- Main Element

> The `<main>` element in HTML defines the primary content of a document's `<body>`. It should contain the central topic of the page, excluding any content that is repeated across multiple pages, such as navigation, headers, or footers. Using `<main>` helps improve accessibility and provides a clear structure for search engines and assistive technologies to understand the page's purpose.

- Section Tag

> The `<section>` tag in HTML is used to define thematic groupings of content within a document. It's a way to organize related content together, like chapters, introductions, or news items. A section typically has a heading and can contain other HTML elements to structure the content within it.

- Article Element

> The `<article>` element in HTML represents a self-contained composition in a document, page, application, or site. It is intended to independently distributable or reusable, for example, in syndication. This could be a forum post, a magazine or newspaper article, a blog entry, a user-submitted comment, or any other independent item of content.
