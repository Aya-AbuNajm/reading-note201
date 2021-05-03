# HTML Lists, Control Flow with JS, and the CSS Box Model

 
## Lists
![listimg](https://i.pinimg.com/originals/68/b5/e8/68b5e8885c4389f7d8fe4d0765457ed2.jpg)
**There atr 3 types of lists :**
1- Unordered List <ul> use bullets.
2- Ordered List <ol> use numbers.

* Each type should include <li> to write each partition of this list,
* You can put a several lists inside them by open new list tag and <li> tags and then close it and continue with the first list.

3- Definition Lists : contain <dl> to create or start the definition list ,<dt> create the definition term ,<dd> contain the definition data.

## Boxes
every box has a width and height proparties, by default the size of box just big enough to hold its contents.

**to determine the size of box you can use:**
* **pixels(px)**pixels have been the most popular method because they allow designers to accurately control their size.
* persentage (%) the size of the box is relative to the size of the browser window.
ems the size of the box is based on the size of text within it.

* you can limiting width by using **min-width** specifies the smallest size a box can be displayed at when the rowser window is narrow, **max-width** indicates the maximum width a box can stretch to when the browser window is wide. and the same thing with **min-height , max-height** .

* Overflowing Content: The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:

  1- hidden This property simply hides any extra content that does not fit in the box.
  2- scroll This property adds a scrollbar to the box so that users can scroll to see the missing content.
 
 * **Border**: The border separates the edge of one box from another, they have a severl values to border-width .

* **Margin** : the distance between the border and other box betwwen , you can controled the marign-top , margin-left , .. the same thing to other sides.( If you want to center a box on the page you can set the left-margin and right-margin to auto.)

* **Padding** : the distance between the content and the border,you can controled the padding-top ,.. to other sides.

> - all of margin ,border, padding will adding to the size of box.
- displye values : inline , block , inline-block , none.

![im](https://www.unm.edu/~tbeach/IT145/week08/images/boxmodel.gif)

* **visibility** :The visibility property allows you to hide boxes from users but It leaves a space where the element would have been.

 1- hidde :This hides the element.
 2- visible :This shows the element.
* **box-shadow** The box-shadow property allows you to add a drop shadow around a box.

 1-Horizontal offset :Negative values position the shadow to the left of the box.
 2- Vertical offset:Negative values position the shadow to the top of the box.
 3-Blur distance:If omitted, the shadow is a solidline like a border.
 4-Spread of shadow :If used, a positive value will cause the shadow to expand in all directions, and negative value will make it contract.

* **border-radius** The value indicates the size of the radius in pixels. You can specify individual values for each corner of a box using
~~~
 border-top-right-radius
 border-bottom-right-radius
 border-bottom-left-radius
 border-top-left-radius.
~~~
--------------------------------

## Basic JavaScript Instructions
### Creating an array
* You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array). The values in the array do not need to be the same data type,so you can store a string, a number and a Boolean all in the same array. 
~~~
var array_name=['ayaali ',26,true,1.47];.
~~~
* Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at **zero ~~(not one)~~**.

* Each item in an array is automatically given a number called an index. This can be used to access specific items in the array.

* To retrieve the third item on the list, the array name is specified along with the index number in square brackets. array_name[2] . also you can change the vlaue of the third item by 
~~~ 
array_name[2]=new value.
~~~

* Each array has a property called length, which holds the number of items in the array 
~~~
array_name.lenght().
~~~
![imgarray](https://stackabuse.s3.amazonaws.com/media/remove-an-element-from-an-array-in-java-1.png)

-------------------------
### Decisions and Loops
A switch statement starts with a variable called the switch value. Each case indicates a possible value for his variable and the code that should run if the variable matches that value.

![imgdt](https://i.pinimg.com/736x/6d/3b/d9/6d3bd97ee060f2729f7e06f7f9c25d70.jpg)

* **NaN** is a value that is counted as a number. You may see it when a number is expected, but is not returned.
~~~
 ('ten' /2) results in NaN.
~~~
* Due to type coercion, every value in JavaScript can be treated as if it were true or false; and this has some interesting side effects.

 1- **Falsy** values are treated as if they are fa 1 se. The table to the left shows a hi ghScore variable with a series of va lues, all of which are falsy.Falsy values can also be treated as the number 0 .
 
 2-**Truthy** values are treated as if they are true. Almost everything that is not in the falsy table can be treated as if it were true. truthy values can also be treated as the number 1.

### Loops :
loops check condition if it's True run the code inside { } if false skip the code inside { } .

![loop](https://data-flair.training/blogs/wp-content/uploads/sites/2/2018/01/Loops-in-Java-df-1200x675.jpg)

* FOR if we have a specific times of times . should determine the counter , the stop condition , update the counter .
~~~
for ( var i=0 ; i<5 ; i++){ block of code }.
~~~
* While if we don't know the times of repeating the code and we have a condition
~~~
 while(condition){ block of code }.
~~~
* Do While if we need to run the code at least one time and then check the condition 
~~~
do {block of cade }while(condition)
~~~

[AYA's GitHub](https://github.com/Aya-AbuNajm)

