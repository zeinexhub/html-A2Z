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
