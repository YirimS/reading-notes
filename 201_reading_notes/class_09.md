# Forms and Events.

Forms are refered too as printed documents that contain spaces for you to fill in information allowing you to collect information from visitors to your site. There are several types of form controls you can use to collect information. you create forms for adding text and passwords, forms for making choices, check boxes and dropdown boxes.  there are also submitting forms that allow you to subscribe to mailing list, and uploading files.

# Form Structures and how they work.

Type	Description
<input type="text">	Displays a single-line text input field
<input type="radio">	Displays a radio button (for selecting one of many choices)
<input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)
<input type="submit">	Displays a submit button (for submitting the form)
<input type="button">	Displays a clickable button

The <action> attribute defines the action to be performed when the form is submitted.

Usually, the form data is sent to a file on the server when the user clicks on the submit button.

In the example below, the form data is sent to a file called "action_page.php". This file contains a server-side script that handles the form data:

<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>

First name:
John

Last name:
Doe



# List Tables and Forms.

When building tables and forms you  can:
- specify bullet point styles 
- Adding boarders and backgrounds to tables
- Changing the appearance of form elements

These properties allow you take more control over specific parts of your pages.

List can be given different appearances using the list-style-type and list-style-image properties.

ul.a {
  list-style-position: outside;
}

ul.b {
  list-style-position: inside;
}

# Events

Event handlers can be used to handle and verify user input, user actions, and browser actions:

Things that should be done every time a page loads
Things that should be done when the page is closed
Action that should be performed when a user clicks a button
Content that should be verified when a user inputs data
And more ...
Many different methods can be used to let JavaScript work with events:

HTML event attributes can execute JavaScript code directly
HTML event attributes can call JavaScript functions
You can assign your own event handler functions to HTML elements
You can prevent events from being sent or being handled
And more.

const btn = document.querySelector('button');

function random(number) {
  return Math.floor(Math.random() * (number+1));
}

btn.onclick = function() {
  const rndCol = 'rgb(' + random(255) + ',' + random(255) + ',' + random(255) + ')';
  document.body.style.backgroundColor = rndCol;
}


