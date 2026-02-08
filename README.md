<h1 id="about"> About HTML Foundations</h1>

<p>
This guide is built to help beginners take their first step into web development and strengthen their understanding of HTML fundamentals.
</p>

<p>
By following this guide, you will: understand the basic structure of a web page, learn the most commonly used HTML tags, discover how to properly use elements like forms, tables, links, and media and eventually build your own simple web pages.
</p>

<p>
I created this guide because I noticed that there aren’t many clear and beginner resources for people who want to start learning frontend development. When I started developing and learning about web development, I couldn't find the kind of resources I wanted, so I decided to create my own resource using information from other sources and what I had learned myself.
</p>

<p>
Not only did this prove very helpful to me during my learning process, but I also hoped others could benefit from it. Many people are interested in web development but don’t know where or how to begin. Although HTML is the foundation of everything in frontend, most tutorials are either too complex or poorly structured, which can make learning overwhelming.
</p>

<p>
With this guide, my goal is to provide a simple, structured, and hands on starting point for anyone who wants to step into the world of frontend development. I believe the best part of this guide is that it encourages learning by doing, helping you understand the building blocks of HTML and gain the confidence to create your own web pages!
</p>

<br>

<p>
This guide was created with the idea that understanding the fundamentals is more important than memorizing tags.
Instead of only listing elements, the goal was to explain how HTML is structured, how the DOM is formed,
and how browsers read and interpret web pages.
</p>

<br>
<ul>
  <li><a href="#about">About Project</a></li>
  <li><a href="#contents">Contents</a></li>
  <li><a href="#references">References & Learning Sources</a></li>
  <li><a href="#skills">Skills you will get</a></li>
</ul>
<br>

<p>
This repository includes a <a href="https://github.com/Kanzyone/HTML5-Foundations/discussions">Discussions section</a> intended to support academic collaboration, questions, and knowledge sharing related to HTML5 fundamentals. Readers are encouraged to use this area to ask questions, discuss concepts, suggest improvements, and exchange ideas about the topics covered in this project.
</p>

<p>
If you have any questions, suggestions, or feedback, feel free to reach out: <a href="mailto:ismailyucel2009@gmail.com">ismailyucel2009@gmail.com</a>
</p>
<br>

<p>License</p>

<p>This project is licensed under the Massachusetts Institute of Technology (MIT) - see the <a href="https://github.com/Kanzyone/HTML5-Foundations/blob/main/LICENSE">LICENSE</a> file for details.</p>


<br>

<h1 id="contents">Contents</h1>

<p>
If you're starting web development from scratch, I recommend reviewing the "Introduction" section.  
The contents are listed in order from top to bottom and you can access them by clicking on each section.

Contents supported by this project:
</p>

<ol>
  <li>
    <h3><a href="#introduction"><strong>Introduction</strong></a></h3>
    <ul>
      <li><a href="#introduction">Introduction</a></li>
      <li>
        <a href="#web">Web</a>
        <ul>
          <li><a href="#howthewebworks">How the Web Works?</a></li>
          <li><a href="#frontend">Frontend Web Development</a></li>
          <li><a href="#backend">Backend Web Development</a></li>
          <li><a href="#fullstack">Fullstack Web Development</a></li>
          <li><a href="#partsofawebsite">Parts of a Website</a></li>
        </ul>
      </li>
      <li>
        <a href="#settingdevelopment">Setting Development Environment</a>
        <ul>
          <li><a href="#browser">Browser</a></li>
          <li><a href="#codeeditor">Code Editor</a></li>
          <li><a href="#vscode">How to use Visual Studio Code</a></li>
        </ul>
      </li>
      <li><a href="#intohtml">Introduction to HTML</a></li>
      <li><a href="#whatishtml">What is HTML?</a></li>
      <li><a href="#w3c">W3C and Web Standards</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="#htmlfundamentals"><strong>HTML Fundamentals</strong></a></h3>
    <ul>
      <li><a href="#htmlelements">HTML Elements</a></li>
      <ul>
        <li><a href="#syntax">Basic Structure of HTML and syntax</a></li>
      </ul>
      <ul>
        <li><a href="#attribute">Attribute</a></li>
        <li><a href="#selfclosing-tags">Self-Closing Tags</a></li>
      </ul>
      <li><a href="#accessibility">Accessibility Basics</a></li>
      <ul>
        <li><a href="#usagesofaccessibility">Examples of Accessibility Usage Areas</a></li>
      </ul>
      <li><a href="#seo">Basic SEO with HTML</a></li>
      <li><a href="#charset">Charset and Language of Elements</a></li>
      <li><a href="#comment">HTML Comment</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="#"><strong>DOM</strong></a></h3>
    <ul>
      <li><a href="#">What is DOM?</a></li>
      <li>
        <a href="#">DOM Tree Structure</a>
        <ul>
          <li><a href="#">Declaration</a></li>
          <li><a href="#">Root Element</a></li>
        </ul>
      </li>
      <li>
        <a href="#">Elements and Nodes</a>
        <ul>
          <li><a href="#">What is a Node?</a></li>
          <li><a href="#">What is an Element?</a></li>
          <li><a href="#">Types of Nodes</a></li>
          <li><a href="#">DOM Tree Connection</a></li>
        </ul>
      </li>
      <li><a href="#">How Browsers Read HTML</a></li>
      <li><a href="#">HTML Document Metadata</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="#"><strong>Page Layout and Structure</strong></a></h3>
    <ul>
      <li><a href="#">Div and Span</a></li>
      <li><a href="#">Block and Inline Elements</a></li>
       <li>
        <a href="#">Semantic HTML</a>
        <ul>
          <li><a href="#">Why is Semantic HTML Important?</a></li>
          <li><a href="#">What is an Element?</a></li>
          <li><a href="#">The Concept of Semantics</a></li>
          <li><a href="#">Core Semantic Structure Elements</a></li>
        </ul>
      </li>
    </ul>
  </li>

  <li>
    <h3><a href="#"><strong>Linking</strong></a></h3>
    <ul>
      <li><a href="#">Link Tag</a></li>
      <li><a href="#">Download Tag</a></li>
      <li><a href="#">Absolute and Relative Links</a></li>
      <li><a href="#">Anchor Navigation</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="#"><strong>Media Elements</strong></a></h3>
    <ul>
      <li><a href="#">Image</a></li>
      <li><a href="#">Video</a></li>
      <li><a href="#">Audio</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="#"><strong>Data Elements</strong></a></h3>
    <ul>
      <li><a href="#">HTML Table Elements</a></li>
      <li>
        <a href="#">HTML Form Elements</a>
      <ul>
          <li><a href="#">input Types</a></li>
          <li><a href="#">Form Structure</a></li>
        </ul>
      </li>
      <li><a href="#">Iframe</a></li>
      <li>
        <a href="#">Lists</a>
        <ul>
          <li><a href="#">Ordered List</a></li>
          <li><a href="#">Unordered List</a></li>
          <li><a href="#">Description List</a></li>
        </ul>
      </li>
    </ul>
  </li>
</ol>



<br>

<h2 id="references">References & Learning Sources</h2>
<p>
This project was built using some of the most trusted and widely used resources in the web development community.
The goal was not only to collect information, but to understand the core logic behind HTML and present it in a clear,
structured, and beginner way.
</p>

<p>
While creating this guide, I focused on learning from official documentation, structured tutorials, and practical examples.
Each topic included in this project is based on knowledge gathered from these sources and simplified to help new learners
build a strong foundation.
</p>

<h3>Documentations</h3>

<p>
These are considered the most reliable and accurate references for web technologies.
They are used by professional developers and recommended for long term learning.
</p>

<ul>
  <li>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
      MDN Web Docs
    </a>
    – One of the most respected and detailed sources for HTML documentation.
    It explains how HTML works, how browsers interpret code, and how elements interact with the DOM.
  </li>

  <li>
    <a href="https://www.w3.org/">
      W3C (World Wide Web Consortium)
    </a>
    – The organization that defines web standards.
    HTML, CSS, and many core web technologies are developed and maintained through W3C guidelines.
  </li>
</ul>

<ul>
  <li>
    <a href="https://www.w3schools.com/html/">
      W3Schools HTML Tutorial
    </a>
    – Easy to follow explanations with interactive examples.
  </li>

  <li>
    <a href="https://github.com/Asabeneh/30-Days-Of-HTML">
      30 Days of HTML
    </a>
    – A structured learning challenge that helped reinforce daily practice and consistency.
  </li>
</ul>

<ul>
  <li>
    <a href="https://youtube.com/playlist?list=PLfAfrKyDRWrG7tK01yW92A2j7Ou0qpOFm">
      HTML Courses by PROTOTURK
    </a>
    – Beginner and friendly video explanations that focus on hands on learning as a Turkish course.
  </li>
</ul>

<hr>

<br>
<br>

<div align="center">
  <h1 id="introduction">1. Introduction</h1>
</div>

<p>
This section provides a general overview of the web and introduces the basic concepts needed to begin learning web development.
Before diving into HTML, it is important to understand what the web is, how it works, and how different parts of a website are connected.
</p>

<p>
In the following topics, you will explore the structure of the web, how browsers and servers communicate, and the role of frontend
and backend technologies in building modern websites. This foundation will help you better understand how HTML fits into the bigger picture.
</p>

<br>

<h2 id="web"> Web</h2>
<p>
The web, also known as the World Wide Web (WWW), is a global system that allows people to access and share information through the internet.
It is made up of millions of websites that can be opened and viewed using a web browser such as Google Chrome, Firefox, or Safari.
</p>

<p>
Every website you visit, every image you see, and every video you watch online is part of the web.
Websites are created using web technologies like HTML, CSS, and JavaScript, and they are stored on servers that can be accessed from anywhere in the world. In simple terms, the web is a collection of connected pages and resources that people can explore through browsers.
It allows users to read content, watch videos, communicate, learn, and interact with online services.
</p>

<p>
Websites are built using frontend and backend technologies. The frontend is what users see and interact with,
while the backend handles data processing, storage, and server side logic.
</p>

<h3 id="howthewebworks"> How the Web Works</h3>
<p>By now you should have clear understanding how the web works based on the information you get on the above two sections. If you want to know more you may also read this <a href="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works">article</a>.</p>
<h3 id="frontend"> Frontend Web Development</h3>
<p>
The frontend, also known as client-side development, is the part of a website that users can see and interact with directly.
It represents everything that appears in the browser when you visit a website.
</p>

<p>
All visible elements such as colors, fonts, buttons, images, videos, audio, layouts, and text content are part of the frontend.
In simple terms, anything you can see or interact with on a webpage belongs to the frontend.
</p>

<p>
The technologies used to build the frontend of a website are called <strong>frontend technologies</strong>.
The core technologies used to create the frontend are:
</p>

<ul>
  <li><strong>HTML</strong> – Builds the structure of the page</li>
  <li><strong>CSS</strong> – Styles and designs the page</li>
  <li><strong>JavaScript</strong> – Makes the page interactive and dynamic</li>
</ul>

<h3 id="backend"> Backend Web Development</h3>
<p>
Backend development, also known as server-side development, refers to the processes that happen behind the scenes of a website.
Unlike the frontend, which users can see and interact with, the backend handles data processing, application logic, and communication
with databases. A typical backend system consists of a server, a backend programming language, and a database. The backend communicates with the
frontend and manages data using programming languages such as Node.js, Python, Ruby, or PHP.
</p>

<p>
When a user interacts with a website, the browser (client) sends an HTTP request to the server. The backend processes this request,
interacts with the database if necessary, and then returns an HTTP response back to the client. This response can be an HTML page,
text, an image, or other types of data.
</p>

<p>
HTTP (HyperText Transfer Protocol) is the communication protocol that allows data to be transferred between the client and the server.
It is the foundation of communication on the web and enables browsers and web servers to exchange information.
</p>

<h3 id="fullstack"> Fullstack Web Development</h3>
<p>
Full-stack web development refers to working with both the frontend and backend parts of a web application.
A full-stack developer is someone who understands how the entire system works, from the user interface to the server and database. In simple terms, full-stack development can be seen as the combination of multiple areas, including frontend development,
backend development, testing, and sometimes additional tools and technologies used to build and maintain modern web applications.
</p>

<p>
By learning both client-side and server-side technologies, full-stack developers gain a broader understanding of how websites function
as complete systems.
</p>

<h3 id="partsofawebsite"> Parts of a Website</h3>
<p>
A website can have a few features or many features depending on its purpose. There is no strict rule that defines what every
website must include. However, most modern websites share a number of common components. For example, the very first website ever created had only one simple page with a few links. Since 1993, HTML has continued to evolve,
and today it is possible to build a complete and decent static website using only HTML.
</p>

<p>
Below are some of the most common parts (components) that you will often find in many websites:
</p>

<ul>
  <li>Website Logo</li>
  <li>Header / Banner</li>
  <li>Navigation Bar / Menu</li>
  <li>Carousel or Slider</li>
  <li>Content Sections</li>
  <li>Forms</li>
  <li>Buttons</li>
  <li>Links</li>
  <li>Images</li>
  <li>Videos</li>
  <li>Audio</li>
  <li>Social Media Links</li>
  <li>Footer</li>
</ul>

<p>
When you build a website, you will create many of these components using HTML. Once a component is created,
it can often be reused in different projects. This is why it is important to think about maintainability
and reusability while developing web pages.
</p>

<p>
You do not need to include all of these components in every website. The structure and features of a website
depend on its purpose, content, and design goals. There are no strict rules about what must be included.
</p>

<br>

<h2 id="settingdevelopment"> Setting Development Environment</h2>

<p>
Before writing HTML code, you need to prepare a simple development environment. This includes choosing a web browser to view your
pages and a code editor to write and manage your code.
</p>

<p>
Having the right tools makes the learning process easier and more productive. In this section, you will learn which browser to use,
which code editor to install, and how to set up your workspace for web development.
</p>

<h3 id="browser"> Browser</h3>

<p>
There are many web browsers available, but most developers prefer to use Google Chrome or Firefox for development.
I personally use Google Chrome and highly recommend it.
<a href="https://www.google.com/chrome/" title="Download Google Chrome" target="_blank">
  Download Google Chrome
</a>
if you do not have it installed.
</p>

<p>
HTML is supported by all modern browsers, including Safari, Opera, Firefox, Edge, and Google Chrome.
Therefore, you should not face any issues viewing HTML pages in any standard browser.
</p>

<h3 id="codeeditor"> Code Editor</h3>

<p>
As a web developer, you should write and manage your code using a text or code editor. To create HTML, CSS, and JavaScript files,
you need a reliable and easy-to-use editor.
</p>

<p>
In this guide, we will use Visual Studio Code. It is one of the most popular code editors because it is lightweight,
powerful, and has many useful extensions that improve productivity.
You can download it here:
<a href="https://code.visualstudio.com/download" target="_blank">
  Download Visual Studio Code
</a>.
</p>

<h3 id="vscode"> How to use Visual Studio Code</h3>

<p>
If you are new to Visual Studio Code, you can learn the basics by watching the following video:
<a href="https://youtu.be/cu_ykIfBprI?si=_2-PMfP3MGc6OUKs" target="_blank">
  Watch tutorial video.
</a>
</p>

<br>
<h2 id="intohtml"> Introduction to HTML</h2>

<p>
HTML is used to build the structure (skeleton) of every website. This structure is styled using CSS (Cascading Style Sheets),
and JavaScript (JS) is used to make websites interactive and dynamic.
</p>

<p>
HTML, CSS, and JavaScript are the three core technologies of web development. These are the essential skills required to become
a web developer. This guide will mainly focus on HTML, but in some sections, small amounts of CSS may be used to make certain
concepts easier to understand.
</p>

<h3 id="whatishtml"> What is HTML?</h3>

<p>
HTML is an acronym that stands for <strong>HyperText Markup Language</strong>. It is the standard markup language used to create
web pages and structure their content.
</p>

<p>
HTML is the building block of the web. It allows developers to create the layout of a page using elements such as headings,
paragraphs, images, links, and more.
</p>

<p>
HTML is not a programming language. Instead, it is a markup language that describes the structure of content on a webpage.
When a browser reads HTML code, it renders it and displays a human-readable web page.
</p>

<h2 id="w3c"> W3C and Web Standards</h2>
<p>
The World Wide Web Consortium (W3C) is the main international organization that creates and maintains web standards.
  
This repository is built around the core philosophy of modern web development: writing HTML5 that follows W3C standards, accessibility rules, and long-term maintainability principles.
  
Understanding web standards is essential for anyone who wants to become a professional developer, because these standards define how the internet actually works behind the scenes.
</p>
<h3>Web standards</h3>
<p>
Web standards are the building blocks of a consistent digitally connected world. They are implemented in browsers, blogs, search engines, and other software that power our experience on the web.

Web standards are official technical rules that ensure websites:
<ul>
 <li>Work the same across all browsers</li>
 <li>Are readable by search engines</li>
 <li>Are accessible to people with disabilities</li>
 <li>Stay compatible with future technologies</li>
<li>Instead of coding randomly, developers follow a shared global system.</li>
</ul>
<br>
  This repository treats HTML5 not just as a language, but as a structured engineering tool. Learn more about <a href="https://www.w3.org/standards/"> web standarts.</a>
</p>

<br>
<br>

<div align="center">
  <h1 id="htmlfundamentals">2. HTML Fundamentals</h1>
</div>
<p>
HTML Fundamentals introduce the core concepts needed to understand how the web works. HTML (HyperText Markup Language) is the standard language used to create and structure web pages. It defines the meaning and layout of content using elements such as headings, paragraphs, links, images, and lists.
</p>

<p>
Learning the fundamentals of HTML helps you understand how browsers read and display content, how pages are structured, and how HTML connects with CSS for styling and JavaScript for interactivity. A strong foundation in HTML is the first step toward becoming a web developer and building modern, accessible websites.
</p>

<br>

<h2 id="htmlelements"> HTML Elements</h2>
<p>
HTML elements are the building blocks of a web page. Every visible part of a website is created using HTML elements.
An HTML element usually consists of:
<ul>
 <li>An opening tag</li>
 <li>Attributes (optional)</li>
 <li>Content</li>
 <li>A closing tag</li>
</ul>
</p>

<br>

<p id="syntax"> An HTML element follows a clear and predictable structure. This structure is called the syntax.</P>


Example of basic syntax:
```html
<h1>Welcome</h1>
```

<ul>
  <li><code>&lt;h1&gt;</code> - Opening tag</li> 
  <li><code>Welcome</code> - Content</li> 
  <li><code>&lt;/h1&gt;</code> - Closing tag</li> 
</ul>

<p>
Also, this example occurs an heading element. The tag name is <b><code>h1</code></b>. It tells the browser to display the text in a large font.
That is why HTML is called a markup language.
</p>

<br>

```html
  <p>
  HTML elements are the blocking of a website. There is not website without
  HTML. Learn HTML and build a website.
  </p>
```

<p>The <code>p</code> tag marks the text to be paragraph that why we call HTML a markup language.</p>






<br>

<h2 id="attribute"> Attributes</h2> 

<p>
Elements can include attributes inside the opening tag. Attributes provide extra information about the element.
</p> 

<ul>
 <li>alt - to add information about added image, use with img element.</li>
 <li>autocompelete - to enable auto complete feature of a form, use with form and input.</li>
 <li>autofocus - enable auto focus of input fields</li>
 <li>autoplay - allows playing an audio/video on the page loads</li>
 <li>charset - enable character encoding of meta tag</li>
 <li>checked - to make a checkbox checked of an input element</li>
 <li>class - to give a common identifier for HTML elements</li>
 <li>cols - to determine the width of a textarea element</li>
 <li>contenteditable - make any element editable</li>
 <li>download - allows a link to download a resource(image, pdf, PPT, etc)</li>
 <li>draggable - to make an element draggable, apply to all elements</li>
 <li>for - to connect/bound a label element with a specific input field, use with a label tag</li>
 <li>href - to specify a URL or a path of a resource, use with a link tag</li>
 <li>id - a unique id for an HTML element, apply to all elements</li>
 <li>lang - specifies the language of the page</li>
 <li>type - specifies the type of the element and it uses with only a certain elements</li>
 <li>src - to specify URL of a media file(img, audio, video, source, embed, script)</li>
 <li>style - to add an inline CSS style to an element</li>
</ul>

<p>
There are also event listener attribute that listen mouse or keyboard. For instance, onclick, onsubmit, onkeydown, onkeyup, onscroll, etc. Remember, do not try to remember by hard. For detail information about, HTML attributes you may check this <a href="https://www.w3schools.com/tags/ref_attributes.asp">link</a>.</p>

<br>

General pattern:
 ```html
 <tag attribute="value">Content</tag>
```

An HTML element with multiple attributes:
```html
<a id="link" href="https://example.com">Visit</a>
```

<ul> 
  <li><code>&lt;a</code> - Opening tag starts</li> 
  <li><code>href="https://example.com"</code> - Attribute</li> 
  <li><code>&gt;</code> - End of opening tag</li> <li><code>Visit</code> - Content</li> 
  <li><code>&lt;/a&gt;</code> - Closing tag</li> </ul> 

<br>

```html
<p style="color:gray;">
  HTML elements are the blocking of a website. There is not website without
  HTML. Learn HTML and build a website.
</p>
```

<p>
The above p tag has a style attribute. The style attribute has a color property and a value gray. The style changes the text color to gray. You can try it by adding other property and value in the style. Each value has to be separated by a semicolon.
</p>
<br>

Another basic example:
```html
<p id="text">Hello</p>
```

  <ul> 
    <li><code>p</code> - Tag name</li> 
    <li><code>id="text"</code> - Attribute</li> 
    <li><code>Hello</code> - Content</li> 
  </ul>

<br>

<p id="selfclosing-tags">
Some HTML elements do not have closing tag, instead they have self-closing tag.
</p>

Example:
```html
<tagname attribute="value" />
```

An example of self closing tags:
```html
<area />
<base />
<br />
<col />
<embed />
<hr />
<img />
<input />
<link />
<meta />
<para />
<source />
<track />
<wbr />
```

<p>
The slash is optional but I strongly recommend to use the slash with self-closing tags. For instance, React.js does not allow you to use without the slash.
</p>

<br>

<h2 id="accessibility"> Accessibility Basics</h2>
<p> Accessibility in web development means designing and building websites so that all people can use them, including individuals with visual, auditory, motor, or cognitive disabilities. This also includes users who rely on assistive technologies such as screen readers, keyboard navigation, or voice control. </p>

<p> Accessibility in HTML begins with using elements correctly and <a href="">semantically</a>. A clear heading structure helps screen readers understand the hierarchy of the page. </p>

Example of correct heading structure:
```html
<h1>Main Title</h1> 
<h2>Section Title</h2> 
<h3>Subsection</h3> 
<p>This is a paragraph explaining the topic.</p>
```

<p>Instead of using generic containers like <b><code>div</code></b> for everything, meaningful elements should be preferred.</p>

<br>
<br>
  
Example of semantic vs non-semantic:
<p> Using meaningful elements instead of generic containers improves accessibility and helps assistive technologies understand the purpose of content. </p>

```html
<!-- Less accessible --> 
<div>Menu</div> 

<!-- More accessible --> 
<nav>Menu</nav>
```

<br>
<br>

<p id="usagesofaccessibility"> Adding alternative text using the <code>alt</code> attribute allows screen readers to describe images to users who cannot see them. </p>

```html
<img src="student.jpg" alt="Student studying in a library">
```

<p>If an image is only decorative, the alt attribute can be left empty:</p> 

```html
<img src="decoration.png" alt="">
```

<br>

<p>Forms are another critical area for accessibility. Each input should be clearly labeled so users understand what information is required.</p>

Example of accessible form label:
```html
<label for="email">Email Address:</label>
<input type="email" id="email" name="email">
```

<p>This helps screen readers connect the label with the input field.</p>

<br>
<br>

<p>Accessibility also means making sure a site can be used without a mouse. Many users navigate only with a keyboard, so interactive elements like buttons and links should be naturally focusable.</p>

Example:
```html
<button>Submit</button>
<a href="#">Go to homepage</a>
```
<p>These elements are keyboard-accessible by default, unlike clickable <code>div</code></div> elements.</p>

<br>
<br>

<p>Clear page structure also improves accessibility. Using landmarks like header, navigation, main content, and footer helps assistive technologies understand different parts of the page.</p>

Example:
```html
<header>
  <h1>My Website</h1>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">About</a>
</nav>

<main>
  <p>Welcome to the site.</p>
</main>

<footer>
  <p>Copyright 2026</p>
</footer>
```

<br>

<h2 id="seo"> Basic SEO with HTML</h2>
<p>
Search Engine Optimization (SEO) is the process of improving a web page so that search engines like Google can better understand, index, and rank its content. HTML plays a critical role in SEO because search engines read a page through its HTML structure. The tags you use help search engines determine what the page is about, how important certain content is, and how different sections are related.
</p>

<p>
One of the most important SEO elements in HTML is the <code>title</code> tag. It defines the main topic of the page and is usually displayed as the clickable headline in search results. A clear and descriptive title helps search engines understand the purpose of the page and improves visibility.
</p>

Example:
```html
<head>
  <title>HTML Fundamentals Guide</title>
</head>
```

<br>

<p>
Another important element is the meta description. This provides a short summary of the page’s content. While it does not directly affect rankings, it often appears in search results and can increase the likelihood that users click on the page.
</p>

Example:
```html
<head>
  <meta name="description" content="Learn the basics of HTML, document structure, and elements.">
</head>
```

<br>

<p>
Heading tags also help search engines understand the structure and main topics of a page. The <code>h1</code> tag is typically used for the main title, while <code>h2</code> and <code>h3</code> divide the content into sections. This makes the content easier to analyze and index.
</p>

Example:
```html
<h1>Learn HTML</h1>
<h2>HTML Elements</h2>
<h2>HTML Document Structure</h2>
<p>This guide explains the core concepts of HTML.</p>
```

<br>

<p>
Links are another important part of SEO. Using clear and descriptive link text helps search engines understand the relationship between pages and the topic of the linked content.  
</p>

Example:
```html
<a href="html-elements.html">Learn about HTML elements</a>
```

<br>

<p>
Images should include descriptive alternative text using the alt attribute. Since search engines cannot see images, they rely on this text to understand what the image represents and how it relates to the page content.
</p>

Example:
```html
<img src="html-logo.png" alt="HTML5 logo">
```

<br>

<p>
Proper content structure also improves SEO. Organizing content using meaningful headings and sections helps search engines identify the most important information on the page.
</p>

Example:
```html
<h1>HTML Basics</h1>

<section>
  <h2>What is HTML?</h2>
  <p>HTML is the standard language used to create web pages.</p>
</section>

<section>
  <h2>Why Learn HTML?</h2>
  <p>HTML forms the foundation of all websites.</p>
</section>
```

<p>
From an academic perspective, applying basic SEO principles with HTML demonstrates an understanding of how search engines interpret and organize web content. It shows the ability to structure information clearly, use meaningful tags, and follow modern web development practices.
</p>

<br>

<h2 id="charset"> Charset and Language of Elements</h2>
<p>
When creating an HTML document, it is important to define how text should be interpreted and which language the content is written in. This is done using character encoding and language settings. These settings help browsers correctly display text and help search engines and assistive technologies better understand the page.
</p>

<p>
One of the most important meta tags in an HTML document is the charset declaration. It defines the character encoding used by the page. The most commonly used value is UTF-8, which supports almost all characters and symbols from different languages.
</p>

<p>
Without defining the correct character set, some characters may appear incorrectly on the page, especially special letters and symbols.
</p>

```html
<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <title>My First Page</title>
</head>
<body>
    Hello World!
</body>
</html>
```

<p>In this example, the <code>meta charset="UTF-8"</code> tag ensures that the browser correctly displays all characters in the document.</p>

<br>

<p>
Another important setting is the language attribute. The language of the page is defined using the lang attribute inside the <code>html</code> tag. This tells browsers, search engines, and screen readers which language the content is written in.
</p>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First Page</title>
</head>
<body>
    Hello World!
</body>
</html>
```

<p>Here, <code>lang="en"</code> indicates that the page content is in English.</p>

<p>
Setting the correct language improves accessibility because screen readers use this information to pronounce words correctly. It also helps search engines better categorize and understand the content.
</p>

<p>
The language attribute can also be used for specific elements if a part of the content is written in a different language.
</p>

```html
<p>This is an English sentence.</p>
<p lang="fr">Bonjour tout le monde</p>
```

<p>
In this case, the second paragraph is marked as French, which helps assistive technologies interpret it properly.
</p>

<p>
From an academic and professional perspective, defining the character set and language of a document is a fundamental part of building well-structured and globally compatible web pages. It prevents display errors, improves accessibility, and supports proper interpretation by browsers and search engines.
</p>

<br>

<h2 id="comment"> HTML Comment</h2>
<p>
Comments in programming are used to make code easier to read, understand, and maintain. In HTML, comments allow developers to leave notes inside the code without affecting how the page is displayed in the browser.
</p>

<p>
Comments are not visible to users on the webpage. They are only seen by developers when reading the source code. This makes them useful for explaining sections of code, leaving reminders, or temporarily disabling parts of the content.
</p>

Example:
```html
<!-- This is an HTML comment -->
```

<p>
In this example, the text inside the comment will not appear on the web page. It is only there to help explain the code.
</p>

<br>

<p>
Comments are often used to describe what a section of code does.
</p>

Example:
```html
<!-- Main title of the page -->
<h1>Welcome to My Website</h1>

<!-- This paragraph introduces the website -->
<p>This website is built using HTML fundamentals.</p>
```

<br>

<p>
They can also be used to temporarily disable parts of the code without deleting them.  
</p>

Example:
```html
<!-- <p>This paragraph is hidden for now.</p> -->
```

<p>
In this case, the paragraph will not be displayed because it is inside a comment.
</p>

<p>
Comments are especially useful in larger projects where multiple developers work on the same code. They help explain structure, clarify decisions, and improve overall readability.
</p>
















<br>
<br>

<hr>
<h2 id="skills">Skills you will get:</h2>

<p>
By following this guide and exploring each section step by step, learners will develop a strong
foundation in HTML and a deeper understanding of how web pages are structured and interpreted by browsers.
</p>

<p>
This project is not only about learning tags, but also about understanding how HTML works as the backbone
of the web and how it connects with the DOM and browser behavior.
</p>

<h3>Technical Skills</h3>

<ul>
  <li>Understanding the structure of an HTML document</li>
  <li>Writing clean and organized HTML code</li>
  <li>Using common HTML elements correctly</li>
  <li>Creating headings, paragraphs, and formatted text</li>
  <li>Working with links, navigation, and anchor systems</li>
  <li>Embedding media such as images, videos, and audio</li>
  <li>Building tables and structured content layouts</li>
  <li>Understanding the difference between block and inline elements</li>
  <li>Using div and span for page structure</li>
</ul>

<h3>Core Web Knowledge</h3>

<ul>
  <li>Understanding how the internet and web pages work</li>
  <li>Learning how browsers read and interpret HTML</li>
  <li>Understanding how the DOM tree is created</li>
  <li>Recognizing the relationship between elements and nodes</li>
  <li>Learning the importance of web standards (W3C)</li>
</ul>

<h3>Development Mindset</h3>

<ul>
  <li>Thinking in structured and logical page layouts</li>
  <li>Breaking down a web page into smaller components</li>
  <li>Building a strong foundation before moving to CSS and JavaScript</li>
  <li>Understanding how simple code becomes a real webpage</li>
</ul>

<h3>Practical Outcomes</h3>

<p>
After completing this guide, learners will be able to:
</p>

<ul>
  <li>Create their own basic web pages from scratch</li>
  <li>Understand and edit existing HTML code</li>
  <li>Build simple structured layouts</li>
  <li>Prepare for learning CSS and JavaScript more effectively</li>
</ul>
