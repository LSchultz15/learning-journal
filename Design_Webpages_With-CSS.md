# Review of Ways to Design the Look of HTML Websites with CSS 
## (102 Read 05: Discussion)

**What is CSS?**
  CSS is a StyleSheet language, meaning that it is used in conjunction with a language like HTML to specify how the content should appear. I actually quite like how Jon Duckett describes it: 

  Duckett invites you to imagine that there's an invisible box around every HTML element, such as the header, paragraph, and hyperlink. These elements are indicated by the HTML tags, such as < h1 >, < p >, and < a >. The stylization also follows the HTML heirarchy, so < body > would form a large invisible box around all of the subsequent elements within it. 

  From there, CSS associates rules with HTML elements using a selector and a declaration. The selector indicates that all HTML elements with that tag will be affected by the rules put forward by the declaration. For example, "p" (which refers to paragraphs in the HTML code through the < p > tag) would be a selector that would affect all paragraphs on the webpage.

  In addition to the selector, CSS also uses declarations, or the rules that CSS applies to the elements. Each declaration has a property (specifying what within the element should be adjusted) and a value (which specifies how the element should be adjusted).

    `CSS Code Examples:
      p {
          font-family: Arial;

      In the above example (which would normally end with a closing curly bracket), p is the selector, font-family is the property, and arial is the value. Since p refers to paragraph, font-family refers to...well, font, and arial dictates which type of font, we can deduce that this CSS code here tells all text displayed between < p > tags in the HTML code should be displayed in an arial font.

      h1, h2, h3 {
          font-family: Arial;
          color: yellow;}
    
      In the above example, since all of the selectors are in the same family, we can group them together so the declarations rules can apply equally to every element with those tags. Additionally, we can see that multiple declarations can be used between one pair of curly brackets. So headers in the HTML page will display with an arial font and in the color yellow.
  
**A Note on Internal vs. External Style Sheets:**
  While you can utilize CSS within an HTML page, it is advised to use a separate CSS style sheet when the website is comprised of more than one page for organizational purposes.

**A Note on Color**
  You can dictate both foreground and background color utilizing color names, hex codes, and even RGB values. To set a foreground color, use the property code "color". To set a background color, simply use "background-color" instead. Additionally, you can go even more in-depth with your color customization by setting opacity, hue, saturation, lightness, and even transparency. 

    For example:
    
    body {
        background-color: #c8c8c8;
        background-color: hsla(0,100%,100%,0.5);

    In the above example (which would normally end with a closing curly bracket), the hex code dictates the actual color of the background of the element. Subsequently, the first number in the paranthesis dictates the hue, the second number dictates the saturation level, the third number dictates the lightness, and the fourth number dictates the transparency.

[Return to README](/README.md)