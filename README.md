# CSS and HTML workbook
This repository was created to reflect the main points of the theory of web development self-study.
## 🎀 Table of contents
- [Flow and block model](#flow-and-block-model)
- [Padding and margin shortcut](#padding-and-margin-shortcut)
- [List of implemented API tests](#bookmark_tabs-list-of-implemented-api-tests)


## Flow and block model 
Document flow (data flow) in HTML is the order in which elements are displayed on the page. In the usual form, all blocks are displayed in the order in which they are written inside the HTML document.
The browser reads the file code from top to bottom and renders the page in the same way. Therefore, the elements are said to follow each other in a flow.

The <code>div</code>, <code>section</code>, <code>header</code>, <code>h1</code> - <code>h6</code> and <code>p</code> tags, when flowing, take up the entire width of their parent by default. Such elements are conventionally called *block elements*.
The model of any element looks like this:

-content with dimensions width (ширина) and height (высота);

-margins (внешние отступы, поля);

-padding (внутренние отступы);

-borders (границы).

![padding_margin_edges.png](media/pictures/padding_margin_edges.png)

When they say “element 200 by 300”, they mean the size of the content up to and including the border, margin is not included here.


## Padding and margin shortcut
![padding_margin_shortcut.png](media/pictures/padding_margin_shortcut.png)
Placement direction - clockwise, starting from the top.

*with 4 values*: each side has its own value

<code>padding: 20px 15px 30px 15px;</code>

*with 3 values*: top - 10px, sides - 20px, bottom - 30px

<code>padding: 10px 20px 30px; </code>

*with 2 values*: top and bottom - 10px, sides - 20px

<code>padding: 10px 20px;</code>

*with 1 value*: 10px on all sides

<code>padding: 10px; </code>

This approach works for both margin and padding.
