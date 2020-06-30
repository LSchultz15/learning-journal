# Review of What Javascript is and How it is Used to Create Dynamic Webpages
## (102 Read 06: Discussion)

**What is Javascript?**
  Javascript is an object-oriented language built with scripts. The scripts are broken down into individual statements or instructions that tell the web browser how to dynamically display information. Think of it this way: If HTML is the content of the webpage and CSS dictates how that content is displayed, Javascript dictates how this information can change its presentation depending on changing factors.

**Quick Javascript Facts**

- Javascripts uses objects and methods. Objects represent an element or group of elements in the webpage that will be affected. Subsequently, the method indicates what should be adjusted and in what way, set by parameters included within the method.

    >Objects and Methods Example:
    >
    >document.write('Good Afternoon!')
    >
    >^In this single line of Javascript code, the word document serves as the object - in this case, the entire web page. Write() is the method, telling the web page to insert unique text (Good Afternoon, this example's parameters) where < script > is written into the html code and includes a source link to the js file.

- The "var" keyword, which stands for Variable, is an object that indicates that the following information, or variable name, should be reanalyzed every time the web page is loaded, as the relevant information may change. Think of var today = new Date() as a way of pulling and subsequently displaying the correct date every time.

- You could then run additional statements or code blocks (additional methods stacked between curly brackets) that can set even further rules, changes, and parameters for the displayed information. 

- Javascript, similar to CSS, can be typed directly into an HTML file, though it is highly recommended to create a separate js file for large projects.

- Given the nature of Javascript, it is recommended to leave regular comments alongside your code to offer insight to why it was structured the way it was. This can be done for single lines of text with // , but can be done for multiple lines of text with /*   */ .

- Protip: Javascript is case sensitive.

[Return to README](/README.md)