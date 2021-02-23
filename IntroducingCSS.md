# Introducing CSS

![Growth mindset VS Fixed Mindset](https://upload.wikimedia.org/wikipedia/commons/3/3d/CSS.3.svg)
## What is CSS ?

is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language.

## How to associate html code with css formats?

### You can insert CSS flowchart styles by:   
External file method is best when applied to a large number of files, as you can make adjustments to the view of all pages by modifying in only one file.
In this method, all CSS commands are inserted into a text file that is called by all HTML pages via the "link" command. This command must be inserted in the "head" area, as in the following example:

* link rel = "stylesheet" href = "style.css" 

Taking into account that the correct file path is, for example, if the css file is inside another internal directory, the file call code is written in this way

* link rel = "stylesheet" href = "css / style.css"

## What is css cascade does ?   
The CSS Cascade is the algorithm by which the browser decides which CSS styles to apply to an element — a lot of people like to think of this as the style that “wins”.

## How CSS rules cascade?
Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).   
So:
1. If there are two or more rules that apply to the same element, it is important to understand which will take precedence.   
2. If the two selectors are identical, the latter of the two will take precedence. Here you can see the second i selector takes precedence over the first.
3. If one selector is more specific than the others, the more specific rule will take precedence over more general ones. 
4. You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.

### CSS rules usually appear in a separate document, although they may appear within an HTML page.    

## Why use externaL styLe sheets?   

The external style sheet is generally used when you want to make changes on multiple pages. It is ideal for this condition because it facilitates you to change the look of the entire web site by changing just one file. It uses the <link> tag on every pages and the <link> tag should be put inside the head section.