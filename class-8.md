* Layout in CSS
 **Controlling the Position of Elements**

![pic1](https://cdn.educba.com/academy/wp-content/uploads/2019/12/CSS-Position.jpg)

**Block-level elements** start on a new line
Examples include:
~~~
<h1> <p> <ul> <li>
~~~
**Inline elements** flow in between surrounding text
Examples include:
~~~
<img> <b> <i>
~~~
![img659](https://media.gcflearnfree.org/content/5e82363212da9215e057b928_03_30_2020/block_vs_inline_diagram.png)

* CSS has the following positioning schemes that allow you to control the layout of a page:
     1- **Normal flow** Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit  ide-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).
     2- **Relative Positioning** This moves an element from the position it would be in normal flow, shifting it to the  op, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding  elements; they stay in the position they would be in in normal flow.
     3- **Absolute positioning** This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.


![pic35](https://www.bapugraphics.com/multimediacoursetips/wp-content/uploads/2017/05/Explain-Absolute-Relative-Fixed-Positioning-Difference.jpg)


> <div> elements are often used as containing elements to group together sections of a page. 


* To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how  far from the top or bottom and left or right it should be placed.
     1- **Fixed Positioning** This is a form of absolute positioning that positions the element in relation to the browser window.
     2- **Floating Elements** Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.
         * Using Float to Place El ements Side-by-Side.
         * The clear property allows you to say that no element (within the same containing element) should touch the sides of a box. It can take the following values:**left, right, both, none**.
* **z-index** property allows you to control which box appears on top.

> X Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.

<br> 
----------------------------
## Grids help create professional and flexible designs

 ### The only rules we needed to add are :
* Control the font and the position of the text in the boxes
* Set the background colors for the boxes
* Set the height of the feature and article boxes
* Add a margin to the top and bottom of each box

