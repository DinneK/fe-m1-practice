## Day Two Exercises

### Chapter 3 and 4 Questions:

1. There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences
- An ordered list is a numbered list, like something your would you use for step in a recipe. Unordered lists are bullet point lists. Lastly, definition lists allow you to define words, they look a lot like what you would find in a dictionary.

2. What is the basic structure of an element used to link to another website?
- The basic element used to link another website is the `a` element, it is an `a href` to open followed by an equal sign, then the website you are linking. Between the opening `a` element and the closing is the link text.

3. What attribute should you include in a link to open a new tab when the link is clicked?
- If you want open a link in a new tab you should include a target attribute. The target attribute is included in the opening tag and is followed by `_blank`.

4. How do you link to a specific part of the same page?
- To link to a specific part of the same page an id attribute is used. Only one id by the same name can be used per page. You will then link the part of the page you would like linked with a hashtag symbol.

### Chapter 10, 11 and 12 Questions:

1. What is the purpose of CSS?
- CSS is like the body of a website. It is what gives you the look that you want. Without CSS we would be very limited in the way our websites looked.

2. What does CSS stand for? What does cascading mean in this case?
- CSS stands for cascading style sheets. Cascading means it works from the top down.

3. What is the basic structure of a CSS rule?
- CSS rules have a basic structure, they have two parts, a selector, which indicates what element the rule applies to and a declaration, which will tell you how the element should be styled.

4. How do you link a CSS stylesheet to your HTML document?
- The `link` tag will link a stylesheet to an HTML document. A link tag is a self contained attribute, therefore it does not need a closing tag. You simply write a link tag, followed by a href to specify the path it will take, then the type attribute to tell you what type of document is being linked, finally a rel attribute to tell the relationship between the HTML page and the file it's being linked to. `<link href="css/styles.css" type="text/css" rel="stylesheet" />`.

5. When is it useful to use external stylesheets as opposed to using internal CSS?
- It is almost always advisable to use an external stylesheet, an external stylesheet allows you to make changes to your entire website, without having to go to each individual page and make the change each time.

6. Describe what a color hex code is.
- A hex code is a six-digit code that represents the amount of red, green and blue in a color. The hex code is preceded by a hashtag/pound sign.

7. What are the three parts of an HSL color property?
- The three parts of HSL color are hue, saturation and lightness. Hue is the colloquial term representing color, saturation is the amount of grey in a color, and lightness is the amount of white or black in a color.

8. In the world of typeface, what are the three main categories of fonts? What are the differences between them?
- The three main categories of typeface are serif, fonts with extra detail at the top and bottom, considered easier to read in print. Sans-serif, which traditionally have straight ends to the letters and are considered easier to read on a screen. Monospace, in which all of the letters take up the same width, considered easier to read for coding.

9. When specifying font-size, what are the main three units used?
- The three main units used for specifying font-size are pixels, percentages and EMS. Pixels, allow for very precise control over the size of the font. Percentages use the default size of a text in a browser which is 16px (pixels) and size accordingly by percentage. EMS is equivalent to the width of the letter m.
