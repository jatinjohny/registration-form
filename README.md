# registration-form
In this exercise, you'll learn HTML forms by building a signup page. You'll learn how to control what types of data people can type into your form, and some new CSS tools for styling your page.

## Steps from responsive-web-design program from freeecodecamp
Responsive Web Design

Learn HTML Forms by Buiding a Registration Form

Step 8, vh - stands for viewport height and is relative to 1% of the height of the viewport.

Step 9, get rid of horizontal scroll bar by setting body margin to 0

Step 12, method attribute specifies how to send form-data to the URL specfified in the action attribute.  
The form data can be sent via a GET request as URL parameter or a POST request as data in the requested body 

Step 16, rem units stands for root em, and is relative to the font size of the html element.   

Step 18, For accessibilty - link label with input element using for attribute.

Step 19, specifying type property important for the browser to what kind of data is should expect. If the type is not specified, the browser will defaults to text.

Step 20, The first input element with a type of submit is automatically set to submit its nearest parent form element.

Step 22, certain type attribute comes with built-in form validation. for example type="email". To force user to use 8 character long password, set minlength attribute witha value of "8" on password input element.

Step 23, Using Regular Expression (regex) 
You can use a pattern attribute to define a regex that the password must match  to be considered valid.
[a-z0-5]{8,}- this  pattern requires eight or more lowercase letters OR  the digits 0 to 5. Now you can remove the minlength attribute

Step 24, On to second fieldset

Step 28, to make radio button relatable, give them name attribute with same value.

Step 33, Adding a dropdown with select element. A select element is a container for a group of option elements and the option element acts as a label for each dropdown

Step 36, option  element without value attriube would not send a useful value to the server. By default the text content of the option will be used when form is submitted.

Step 40, use textarea element to get multi-line text from the user. you can also rows and cols attribute to give it appropriate size. for example rows="3" cols="30"

Step 41, You should provide each submittable element with a name attribute

Step 47, Introducing psuedo-class last-of-type, for example p:last-of-type
This will select the last p element. 

Step 50, width: unset property
This will remove the earlier rule which set all the input elements to have width:100%

Step 52, vertical-align: middle property

Step 53, setting background-color and border color to #0a0a23 to blend the input and textarea elements with the rest.

Step 54, setting min-height:2em and color to white on input and textarea elements 

Step 56, to select an element based on attribute value youcan use attribute selector
for example; to target input element with name attribute with value of password,
write input[name="password"] {}

Step 59, styling submit button with background-cokor:#3b3b4f and border-color:white and font-size:1.1rem and giving it height of 2em;

Step 63, changing link color to #dfdfe2
