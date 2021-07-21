## React and Forms.

HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state. For example, this form in plain HTML accepts a single name:

<form>
  <label>
    Name:
    <input type="text" name="name" />
  </label>
  <input type="submit" value="Submit" />
</form>

This form has the default HTML form behavior of browsing to a new page when the user submits the form. If you want this behavior in React, it just works. But in most cases, it’s convenient to have a JavaScript function that handles the submission of the form and has access to the data that the user entered into the form. The standard way to achieve this is with a technique called “controlled components”.

1. What is a ‘Controlled Component’?

- In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState(). We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.


2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

3. How do we target what the user is entering if we have an event handler on an input field?

#The Conditional (Ternary) Operator Explained. 

##Why would we use a Ternary Operator?

- Using a conditional, like an if statement, allows us to specify that a certain block of code should be executed if a certain condition is met. But, we can right the same if/else statement using one line, this shorter code yields us the same result


 if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

  console.log((age >= 21) ? "Enjoy your drink!" : "Sorry, you're not old enough.");
