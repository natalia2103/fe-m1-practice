## Chapters 3 & 4 Review Questions

1.  There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
- **Ordered lists** are lists where each item in the list is numbered. An **unordered list** are lists that begin with a bullet point(rather than characters that indicate order). A **definition list** is a list made up of a set of terms along with the definitions for each of those terms.

2.  What is the basic structure of an element used to link to another website?
- Links are created using the <a> element. You specify which page you want to link to using the 'href' attribute.
  ex: <a href="http://www.imdb.com">IMDB</a>

3.  What attribute should you include in a link to open a new tab when the link is clicked?
- Use the 'target' attribute. The value of the attribute should be '_blank'
  ex: <a href-"http://www.imdb.com" target="_blank">Internet Movie Database</a>

4.  How do you link to a specific part of the same page?
- Use the 'id' element to identify the points in the page that the link will go to. The value of the 'id' element should start with a letter or an underscore. On a single page, no two id elements should have the same value. In the <a> element, the value of the 'href' attribute starts with '#' and is followed by the value of the id attribute of the element you want to link to.

## Chapters 10-12 Review Questions:

1.  What is the purpose of CSS?
- CSS allows us to create rules that specify how the content of an element should appear.

2.  What does CSS stand for? What does cascading mean in this case?
- CSS stands for **Cascading Style Sheets.** In this case, cascading means
3.  What is the basic structure of a CSS rule?
 a CSS rule contains two parts, a **selector** and a **declaration**. Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas. Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.
  ex: p {
    font-family: Arial;
    color: yellow;}

4.  How do you link a CSS stylesheet to your HTML document?
- By using the empty link element(meaning it doesn't need a closing tag) in your HTML document. It lives inside the <head> element. Link elements contain three attributes: **href** (specifies the path to the CSS file), **type** (specifies the type of document being linked to, either text/css), and **rel** (specifies the relationship between the HTML page and the file it is linked to).
  ex: <link href="css/styles.css" type="text/css" rel+"stylesheet" />

5.  When is it useful to use external stylesheets as opposed to using internal CSS?
- Using an external stylesheet allows all pages to use the same style rules (rather than repeating them in each page), keeps the content separate from how the page looks, and it means you can change styles used across all pages by altering just one file (rather than each individual page).

6.  Describe what a color hex code is.
- Hex codes are six-digit codes that represent the amount of red, green, and blue in a color, preceded by a '#'. ex: #ee3e80

7.  What are the three parts of an HSL color property?
- The three parts of an HSL color property are hue, saturation, and lightness.

8.  In the world of typeface, what are the three main categories of fonts? What are the differences between them?
  1. **Serif** - These fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs. Usually used for long passages of text because they are considered easy to read.
  2. **Sans-Serif** - These fonts have straight ends to letters , and therefore have a a much cleaner design. If the print is small, sans-serif is considered clearer to read.
  3. **Monospace** - Every letter in monospace (or fixed-width) font is the same width. These fonts are commonly used for code because they align nicely, making the text easier to follow.

9.  When specifiying font-size, what are the main three units used?
  1. **Pixels** - Commonly used becasue they allow the web designers very precise control over how much space their text takes up. The number of pixels is followed by the letters 'px'.
  2. **Percentages** - The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px.
  3. **EMs** - An em is equivalent to the width of a letter m.
