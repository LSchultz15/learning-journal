# Review of Ways to Build Webpages Using HTML and CSS 
## (102 Read 04: Discussion)

**What is HTML?**
  HTML is a language of code used to build webpages. More specifically, HTML utilizes tags to categorize and define how content should be displayed in a webpage. Content, typically text that will be displayed to the audience, is surrounded by an opening and closing tag, and all content between those tags will be affected by the terms of the tag. Additional HTML code can be applied to this content within tags, such as attributes (language, color, size, etc.)

    `HTML Tag Examples:
      <html>= Indicates to the displaying software or browser that anything beyond this tag is HTML code.
      </html>= Indicates that anything before this tag is HTML code. This is used to "stop the power" of the starting <html> tag.
      <h1></h1>= These tags are used to indicate that the content between them is a main heading. Subsequently, tags like <h2> would be a secondary or sub-heading, and so on.
      <p></p>= Start and end of a paragraph.
      <body></body>= Indicates that content (and tags) between these tags is in the body of the webpage.

      Note: It's important to recognize that there is also a hierarchy structure applies to HTML code. For example, you would typically put <body> on a line before placing <p> on the next line, slightly tabbed in. This indicates that the paragraph is within the body of the webpage, which tells the web browser where to place and how to format the paragraph. It might look something like this:

    <body>
        <p> This is a paragraph in the body of the webpage.</p>
    </body>
  
**What is CSS**
  CSS, similarly to HTML, is a coding language that works in tandem with HTML and other languages to specify how the content of an element should appear. CSS can also be used to apply specific display rules to content that shares attributes across an entire project with one line of code, as opposed to using HTML to specify an attribute on each individual content element. We'll discuss CSS more in the future.

**What is the Process of Building a Webpage?**
  I'm glad you asked. There are a number of things to think about as you approach building a website. I recommend the following steps:

    - [ ] Consider who your audience is. Who is this website for? What will they be looking for?
    - [ ] Consider what your audiences goals are. Why are they coming to your site? How can you most effectively give them what they need?
    - [ ] From there, consider your site map. Using card sorting or wireframing (both ways to, on paper, display how your website will be navigated), display in a visual format what pages will make up your website and how each webpage should be structured to offer up the content most effectively.
    - [ ] Consider Design Theory. Think about where the eye goes first (the visual hierarchy of the website, defined by page placement, color, size, font, etc.), what content should be grouped together and in what grouping format, etc.
    - [ ] Begin coding. Using HTML, drop the basic content into your HTML code, organized with tags. CSS and additional display code will be utilized later.

[Return to README](/README.md)