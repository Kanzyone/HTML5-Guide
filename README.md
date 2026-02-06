<h1>HTML Foundations</h1>

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

References & Learning Sources:
<ul>
  <li>Focus on understanding structure, not just syntax</li>
  <li>Learn step by step from basic concepts to more technical topics</li>
  <li>Build a strong foundation before moving into CSS and JavaScript</li>
  <li>Encourage learning by doing with simple examples</li>
</ul>

<br>
<br>

<p>
If you have any questions, suggestions, or feedback, feel free to reach out:
<br>
<a href="mailto:ismailyucel2009@gmail.com">ismailyucel2009@gmail.com</a>
</p>

<br>

<h1>Contents</h1>

<p>
If you're starting web development from scratch, I recommend reviewing the "Introduction" section.  
The contents are listed in order from top to bottom and you can access them by clicking on each section.

Contents supported by this guide:
</p>

<ol>
  <li>
    <h3><a href="Introduction.md">Introduction</a></h3>
    <ul>
      <li><a href="Introduction.md#introduction">Introduction</a></li>
      <li>
        <a href="DOM.md#elements-and-nodes">Wev Development</a>
        <ul>
          <li><a href="DOM.md#what-is-a-node">Front-End Development</a></li>
          <li><a href="DOM.md#what-is-an-element">What is an Element?</a></li>
          <li><a href="DOM.md#types-of-nodes">Types of Nodes</a></li>
          <li><a href="DOM.md#dom-tree-connection">DOM Tree connection</a></li>
        </ul>
      </li>
      <li><a href="Introduction.md#internet">Internet</a></li>
      <li>
        <a href="Introduction.md#setting-development-environment">Setting Development Environment</a>
        <ul>
          <li><a href="Introduction.md#browser">Browser</a></li>
          <li><a href="Introduction.md#code-editor">Code Editor</a></li>
          <li><a href="Introduction.md#how-to-use-visual-studio-code">How to use Visual Studio Code</a></li>
        </ul>
      </li>
      <li><a href="Introduction.md#introduction-to-html">Introduction to HTML</a></li>
      <li><a href="Introduction.md#what-is-html">What is HTML?</a></li>
      <li><a href="Introduction.md#w3c-and-web-standards">W3C and Web Standards</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="HTML Fundamentals.md">HTML Fundamentals</a></h3>
    <ul>
      <li><a href="HTML Elements.md#html-elements">HTML Elements</a></li>
      <li><a href="HTML Document Structure.md#html-document-structure">HTML Document Structure</a></li>
      <li><a href="Charset and Language of Elements.md#charset-and-language-of-elements">Charset and Language of Elements</a></li>
      <li><a href="HTML Comment.md#html-comment">HTML Comment</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="DOM.md#dom">DOM</a></h3>
    <ul>
      <li><a href="DOM.md#what-is-dom">What is DOM?</a></li>
      <li>
        <a href="DOM.md#dom-tree-structure">DOM Tree Structure</a>
        <ul>
          <li><a href="DOM.md#declaration">Declaration</a></li>
          <li><a href="DOM.md#root-element">Root Element</a></li>
        </ul>
      </li>
      <li>
        <a href="DOM.md#elements-and-nodes">Elements and Nodes</a>
        <ul>
          <li><a href="DOM.md#what-is-a-node">What is a Node?</a></li>
          <li><a href="DOM.md#what-is-an-element">What is an Element?</a></li>
          <li><a href="DOM.md#types-of-nodes">Types of Nodes</a></li>
          <li><a href="DOM.md#dom-tree-connection">DOM Tree connection</a></li>
        </ul>
      </li>
      <li><a href="DOM.md#how-browsers-read-html">How Browsers Read HTML</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="Text Content Elements.md">Text & Content Elements</a></h3>
    <ul>
      <li><a href="Paragraph Element.md#paragraph-element">Paragraph Element</a></li>
      <li><a href="Heading Element.md#heading-elements">Heading Elements</a></li>
      <li>
        <a href="Formatting Elements.md#formatting-elements">Formatting Elements</a>
        <ul>
          <li><a href="Formatting Elements.md#b">b</a></li>
          <li><a href="Formatting Elements.md#strong">strong</a></li>
          <li><a href="Formatting Elements.md#i">i</a></li>
          <li><a href="Formatting Elements.md#em">em</a></li>
          <li><a href="Formatting Elements.md#mark">mark</a></li>
          <li><a href="Formatting Elements.md#small">small</a></li>
          <li><a href="Formatting Elements.md#del">del</a></li>
          <li><a href="Formatting Elements.md#ins">ins</a></li>
          <li><a href="Formatting Elements.md#sub">sub</a></li>
          <li><a href="Formatting Elements.md#sup">sup</a></li>
          <li><a href="Formatting Elements.md#pre">pre</a></li>
          <li><a href="Formatting Elements.md#u">u</a></li>
        </ul>
      </li>
    </ul>
  </li>

  <li>
    <h3><a href="Layout Basics.md">Layout Basics</a></h3>
    <ul>
      <li>
        <a href="Div Span.md#div-span">Div & Span</a>
        <ul>
          <li><a href="Div Span.md#div">div</a></li>
          <li><a href="Div Span.md#span">span</a></li>
          <li><a href="Div Span.md#summary">Summary of Differences</a></li>
        </ul>
      </li>
      <li><a href="Layout Basics.md#block-and-inline-elements">Block and Inline Elements</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="Links.md">Links</a></h3>
    <ul>
      <li><a href="Links.md#link-tag">Link Tag</a></li>
      <li><a href="Links.md#download-tag">Download Tag</a></li>
      <li><a href="Links.md#absolute-and-relative-links">Absolute and Relative Links</a></li>
      <li><a href="Links.md#anchor-navigation">Anchor Navigation</a></li>
      <li><a href="Links.md#id-system">ID System</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="Media Elements.md">Media Elements</a></h3>
    <ul>
      <li><a href="Media Elements.md#image">Image</a></li>
      <li><a href="Media Elements.md#video">Video</a></li>
      <li><a href="Media Elements.md#audio">Audio</a></li>
    </ul>
  </li>

  <li>
    <h3><a href="Table.md">Table</a></h3>
    <ul>
      <li><a href="Table.md#table-elements">Table Elements</a></li>
      <li><a href="Table.md#iframe">Iframe</a></li>
      <li><a href="Table.md#list-tags">List Tags</a></li>
    </ul>
  </li>
</ol>

<br>

<h2>References & Learning Sources</h2>
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
<h1>1. Introduction</h1>
</div>

<h2>Setting Development Environment</h2>

<h3>Browser</h3>

There are many browsers out there but most developers prefer to use Google Chrome or FireFox. I usually use Google chrome for development and I recommend it too. <a href="https://www.google.com/aclk?sa=L&ai=DChsSEwid-qOt7caQAxWDU38AHT74KZsYACICCAEQARoCb2E&co=1&gclid=EAIaIQobChMInfqjre3GkAMVg1N_AB0--SsnH8EzLaU85Of6v5vdZhfwHc2qzEqenBE7EBwibV1JKUQENe0ifVJLUKoub5e0HsKrt98e1viJNEAUTM8cZ1gQ95aJzBSHEHKU8iv0vby0M0zeZOgy-Brvj2w-UWdpunvrMj77EbAmbHZuvrU81SrEGwPuYzMh5dBmIKQN7XgqM5g63Gmf2HRNCmoEgTXhJtGO2dGou3d&cce=1&sig=AOD64_1jmEVdKRpamXAvGKVCTmM722-qaQ&q&adurl&ved=2ahUKEwjmh5-t7caQAxV44ckDHbkNDLYQ0Qx6BAgWEAE" title="Google site" target="_blank"> Download Google Chrome </a> if you do not have one.

HTML supports many browsers such as Safari, Opera, FireFox, Edge and Google Chrome. So I don't think so you will be have any problem for browser.

<h3>Code Editor</h3>

As web developer, you should write code using a text or code editor. Therefore, to write HTML code, CSS, JS, React or other you need to have a code edit.

I will use Visual studio code and I will use it in this challenge too. I strongly suggest to use Visual Studio Code because it has lots of productivity extensions that makes super productive. Now, let's [Download Visual Studio Code](https://code.visualstudio.com/download).

<h3>How to use Visual Studio Code</h3>

To know how to use visual studio code, watch the following [video](https://youtu.be/cu_ykIfBprI?si=_2-PMfP3MGc6OUKs)

<br>

<h2>Introduction of HTML</h2>

HTML is used to build the skeleton or outline of any website. The skeleton or outline of the website is styled(beautified) by CSS(Cascading Style Sheet). JavaScript (JS) can make a website interactive and dynamic. HTML, CSS and JS are the core technologies to build websites and these are the skills required to be a web developer. This challenge will focus on HTML but we will use little CSS to make some HTML concepts more clear to the readers.

<h3>What is HTML?</h3>

The word HTML is an acronym. That is stands for Hypertext Markup Language. It is the standard markup languages to develop websites. HTML is the build block of the web that allows building layouts of page using HTML elements. HTML is not not a programming language instead it is a markup language.
HTML code will be rendered by a browser and it give a human readable output. Look at the figure bellow to understand better how the HTML code convert to a website using a browser.




























<hr>
<h2>Skills you will get:</h2>

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
