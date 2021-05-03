# HTML Text, CSS Introduction, and Basic JavaScript Instructions

![IMG52D](https://tech3arabi.com/wp-content/uploads/2020/10/%D8%B4%D8%B1%D9%83%D8%A7%D8%AA-%D8%AA%D8%B5%D9%85%D9%8A%D9%85-%D9%85%D9%88%D8%A7%D9%82%D8%B9-%D8%A7%D9%84%D8%A7%D9%86%D8%AA%D8%B1%D9%86%D8%AA-%D9%81%D9%8A-%D8%A7%D9%84%D8%A7%D8%B1%D8%AF%D9%86-.png)
When creating a web page, you add tags(known as markup) to the contents of the page. These tags provide extra meaning
and allow browsers to show users the appropriate structure for the page.
● Structural markup: the elements that you can use to describe both headings and paragraphs.
● Semantic markup: which provides extra information.

### Headings
HTML has six "levels" of headings:
* **<h1>** is used for main headings
* **<h2>** is used for subheadings 
* If there are further sections under the subheadings then the **<h3>** element is used, and so on...

### paragraphs
To create a paragraph, surround the words that make up the
paragraph with an opening <p> tag and closing </p> tag.

### Bold & Italic
* By enclosing words in the tags <b> and </b> we can make characters appear bold.

* By enclosing words in the tags <i> and </i> we can make characters 


### Superscript and Subscript
* <sup>
The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power .
* <sub>
The <sub> element is used to contain characters that should
be subscript. It is commonly used with foot notes or chemical formulas such as H2.

### White Space

In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines.
When the browser comes across two or more spaces next to each other, it only displays one space.

### Line Breaks & Horizontal Rules
* <br />
 the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag <br />.

 *  <hr />
To create a break between themes — such as a change of  topic in a book or a new scene in a play — you can add a horizontal rule between sections using the <hr /> tag.

### Visual Editors & Their Code views
Content management systems and HTML editors such as Dreamweaver usually have two views of the page you are creating:
* a visual editor 
* a code view.

### Semantic Markup
There are some text elements that are not intended to affect the
structure of your web pages, but they do add extra information to the pages — they are known as semantic markup.

### Strong & Emphasis
* <strong>
The use of the <strong> element indicates that its content has strong importance. 

> browsers will show the contents of a <strong> element in bold.

* <em>
The <em> element indicates emphasis that subtly changes the meaning of a sentence.

>By default browsers will show the contents of an <em> element in italic.


### quotations

There are two elements commonly used for marking up quotations:
* <blockquote>
The <blockquote> element is used for longer quotes that take
up an entire paragraph. 
* <q>
The <q> element is used for shorter quotes that sit within a paragraph.

### Abbreviations & Acronyms
* <abbr>

If you use an abbreviation or an acronym, then the <abbr> element  an be used. A title attribute on the opening tag is used to specify the full term.

### Author Details
* <address> 

The <address> element has quite a specific use: to contain contact details for the author of the page.

### Changes to Content
* <ins>
* <del>

The <ins> element can be used to show content that has been inserted into a document, while the <del> element can show text that has been deleted from it.
* <s>
The <s> element indicates something that is no longer accurate or relevant (but that  should not be deleted).
---------------

### Understanding CSS:
Thinking Inside the Box
The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.


### CSS Associates Style rules with HTML elements

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts:
* ** a selector** 
*  **a declaration**

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.
![im](https://alitechtalk.files.wordpress.com/2019/02/css-declaration-small.png)

### Using External CSS
<link> 
The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element.
It should use three attributes:

* href
This specifies the path to the CSS file (which is often placed in   folder called css or styles).

* type
This attribute specifies the type of document being linked to. The value should be text/css.

* rel
This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

### Using Internal CSS
* <style>

You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the **<head>** element of the page.

------------------

## **JavaScript**
 ### STATEMENTS 
* A script is a series of instructions that a computer can follow one-by-one.
* Each individual instruction or step is known as a statement.
* Statements should end with a semicolon.

### COMMENTS

You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code. 

### variables
A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

### DATA TYPES
JavaScript distinguishes between numbers, strings, and true or false values known as Booleans. 
* NUMERIC DATA TYPE
* STRING DATA TYPE
* BOOLEAN DATA TYPE

### RULES FOR NAMING VARIABLES

* The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number. 
* The name can contain letters.
* Use a name that describes the kind of information that the variable stores. 
* You cannot use keywords or reserved words. 
* All variables are case sensitive, so score and Score would be different variable names.
* If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word.

### ARRAYS 
An array is a special type of variable. It doesn't just store one value; it stores a list of values. 

~~~
var colors;
colors ['white', 'black', ' custom'];
var el document.getElementByld('col ors');
el . textContent = col ors[O]; 
~~~
Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at **zero** (not one). 

### EXPRESSIONS
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions: 
1- EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE 
~~~
var color = 'beige'; 
~~~
2- EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE 
~~~
var area = 3 * 2;
~~~

### OPERATORS
 Expressions rely on things called operator's; they allow programmers to create a single value from one or more values.
 ![img235](https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2020/02/types-of-arithmetic-operators-.jpg)

## Decision and loop
  a conditional statement is a set of rules performed if a certain condition is met. It is sometimes referred to as an If-Then statement, because IF a condition is met, THEN an action is performed.

  ### USING COMPARISON OPERATORS 
  ![IM565](https://slidetodoc.com/presentation_image/11097ef0ca4581fdff3d1b8949c9bbd9/image-29.jpg)

**  SWITCH STATEMENTS**
A switch statement starts with a variable called the switch value.
Each case indicates a possible value for this variable and the
code that should run if the variable matches that value. 

**IF ... ELSE**
• There is no need to provide an el se option. (You can just use an if statement.)
• With a series of if statements, they are all checked even if a match has been found (so it performs more slowly than switch).
SWITCH
• You have a default option that is run if none of the cases match.
• If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing
better performance than multiple i f statements). 




