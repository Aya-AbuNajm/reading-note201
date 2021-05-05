# Forms and JS Events



## Forms

![img52](https://cdn.educba.com/academy/wp-content/uploads/2020/04/JavaScript-Form-Events.jpg)
### There are several types of form controls that you can use to collect information from visitors to your site :

1. **ADDING TEXT:**

   * Text input (single-line) :
    ~~~
    <input type="text" name=" " maxlength = "" size="" >
    ~~~
     When the type attribute has a value of text, it creates a singleline , `name` When users enter information into a form, the server needs to know which form control each piece of data was entered into. `maxlength`Its value is the number of characters they may enter. The `size` attribute should not be used on new forms. It was used in older forms to indicate the width of the text input

   * Password input : 
   ~~~
   type="password"
   ~~~

   * Text area (multi-line):  Any text that appears between the opening `<textarea>` and closing `</textarea>` tags will appear in the text box when the page loads.

2. **Making Choices:**

   - Radio buttons : (type="radio") The (value) attribute indicates the value that is sent to the server for the selected option, The (checked) attribute can be used to indicate which value
   - Checkboxes :
   ~~~
   type="checkbox"
   ~~~
   - Drop-down boxes :The `<select>` element is used to create a drop down list box. It contains two or more `<option> `elements. The `selected` attribute can be used to indicate the option that should be selected when the page loads.

3. **Submitting Forms:**

   - Submit buttons :`type="submit"` The submit button is used to send a form to the server.
   - Image buttons :`type="image"`

4. **Uploading Files:**

   - File upload : `type="file"` This type of input creates a box that looks like a text input followed by a browse button.

5. **Button and hidden**

   - Button :The `<button>` element was introduced to allow users more control over how their buttons appear, and to allow other elements to appear inside the button.
   - hidden :`type="hidden"` This example also shows a hidden form control. These form controls are not shown on the page (although you can see them if you use the View Source option in the browser). They allow web page authors to add values to forms that users cannot see.

6. **Labelling Form Controls** :<label> element can be used in two ways. It can:
   1- Wrap around both the text description and the form input.
   2- Be kept separate from the form control and use the for attribute to indicate which form control it is a label for .
   - `for` The for attribute states which form control the label belongs.
7. **Grouping Form Elements**
   - `<fieldset>` You can group related form controls together inside the` <fieldset>` element. This is particularly helpful for longer forms.
   - The `<legend> `element can come directly after the opening`<fieldset>`tag and contains a caption which helps identify the purpose of that group of form controls.

### How forms work?
![imghowwork](https://www.researchgate.net/profile/Amer-Elameer/publication/321708049/figure/fig15/AS:569702479269890@1512839063713/Figure-2-12-How-Forms-Work11.png)
1. A user fills in a form and then presses a button to submit the information to the server.
2. The name of each form control is sent to the server along with the value the user enters or selects.
3. The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.
4. The server creates a new page to send back to the browser based on the information received.




### Lists , Tables & Forms

- In addition to the CSS properties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.
- List markers can be given different appearances using the list-style-type and list-style image properties.
- Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
- Forms are easier to use if the form controls are vertically aligned using CSS.
- Forms benefit from styles that make them feel more interactive.




-------------------------------------------------------------------------

# Events

![imgeventtype](https://slideplayer.com/slide/16279781/95/images/3/%28Some%29+Event+Types+UI+events+%E2%80%93+occur+when+a+user+interacts+with+the+browser%E2%80%99s+user+interface+%28UI%29+%E2%80%93+work+with+window+object..jpg)                                                                 



- KEYBOARD EVENTS Occur when a user interacts with the keyboard (see also input event).
![imgkey](https://www.geeksread.com/wp-content/uploads/2018/05/JavaScript-tutorial-45-Keypress-Event-in-jQuery.png)

 * **keydown**:  User first presses a key (repeats while key is depressed).    
 * **keyup**  :  User releases a key.                                          
*  **keypress** : Character is being inserted (repeats while key is depressed). 





- **MOUSE EVENTS Occur when a user interacts with a mouse. trackpad, or touchscreen**


 * click      : User presses and releases a button over the same element.      
 * dbl click   :User presses and releases a button twice over the same element. 
 * moused own  :User presses a mouse button while over an element.              
 * mouseup     :User releases a mouse button while over an element.             
 * mousemove   :User moves the mouse (not on a touchscreen).                    
 * mouseover   :User moves the mouse over an element (not on a touchscreen).    
 * mouseout    :User moves the mouse off an element (not on a touchscreen).     

![img52](https://miro.medium.com/max/1448/1*L2BEjXe6iOo_Q1CIlq5NIg.gif)

### HOW EVENTS TRIGGER JAVASCRIPT CODE

1.  Select t he element node(s) you want the script to respond to.
2.  Indicate which event on the selected node(s) will trigger the response.
3.  State the code you want to run when the event occurs.

- **TRADITIONAL DOM EVENT HANDLERS** :you can only attach one function to each event handler.
  `element .onevent =functionName() ;`
  `function checkUsername() { // code to check the length of username}`

- **EVENT LISTENERS** :Event listeners are a more recent approach to handling events. They can deal with more than one function at a time.
~~~
element .addEventlistener('event', functionName [, Boolean]) ;
function checkUsername() { }
~~~

1. Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).

2. Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.

3. When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.

4. You can use event delegation to monitor for events that happen on all of the children of an element.

5. The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.