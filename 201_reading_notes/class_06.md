# Problems Domain, Objects and the Dom

## Objects

What is an object?
Objects group together a set of variables and functions to create a model of something you would see in the real world. In objects variables become propeerties, and properties tell us about something like the names of hotels and rooms numbers. In objects fun ctions become known as methods. Methods represent task that are associate with the object lioke subtracting numbers from a total. literal notation is the easiest and most popular way to create objects. you can access the properties or methods or object using dot notation. you can also access properties using square bracket. See example below.

// Set up the object
var hotel = {
  name : 'Quay',
  rooms : 40,
  booked : 25,
  checkAvailability : function() {
    return this.rooms - this.booked; // Need "this" because inside function
  }
};

// Update the HTML
var elName = document.getElementById('hotelName'); // Get element
elName.textContent = hotel.name;                   // Update HTML with property of the object

var elRooms = document.getElementById('rooms');    // Get element
elRooms.textContent = hotel.checkAvailability();   // Update HTML with property of the object

## THE DOCUMENT OBJECT MODEL (DOM)

DOM specifies how a browser should create a model of an HTML and how JavaScript can access and update the content of the webpage while its still in the browser window. Browsers load web pages and create a model of that web page, the model is called a DOM TREE. Tne Dom Tree consist of Nodes.

- The Document Node
- Element Node
- Atrribute Node
- Text Nodes

## Selecting elements

You can select elements using class attributes and or tag names. The getElementByClassName() method allows you to select elements who class attributes contain a certain value.

The getelementsByTagName() method allows you to select elements using their tag name.

querySelector() returns the first element node that matches the the CSS-style selector, querySelectorAll() returns Nodelist of all of the matches.


