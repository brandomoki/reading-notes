
## **What is CSS**

**Cacading Style Sheets**
+ CSS is a language for specifying how documents are presented to user
+ CSS allows you to create good looking websites
+ documents are text file using a markup language like HTML
+ Presents documents into usable visual form for the user

> Examples- Change color of text and size of headings. Change single column text into a layout. You can even add animation.

### **CSS syntax**

+ CSS is a rule based language. Rules are defined by you usings groups or elements

+ CSS is the manipulation of data

### **How to add CSS**

1. External CSS
    + Change entire website with just one file
    + Each HTML page must include a reference to the external style sheet file inside the `<link>` element.
1. Internal CSS
    + Internal style sheet if one specific HTML page has a unique style
    + Internal style is defined inside the `<style>` element
1. Inline CSS
    + Used to apply a unique style to a single element
    + To use add the style attribute to the relvant element
    + The style attribute can contain any CSS property.

+ Multiple style sheets
    + If properties have been define for the same selector (element) in different style sheets, the style for the last read sheet will be used

+ **Cascading Order**
    >What style will be used if there are more than one style to an element?

    + All the styles will cascade into a new virtual style sheet by following the rulles, where number one has priority.
        1. Inline style (inside an HTML element)
        1. External and Internal style sheets (in head section)
        1. Browser default

+ `color:`
    + `color:` property specifies the color of text





