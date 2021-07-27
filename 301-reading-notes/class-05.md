# Thknking in React

1. How would you break a mock into a component heirarchy?

When breaking a mock into components the first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names.

2. What is the single responsibility principle and how does it apply to components?

 the single responsibility principle is that a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents. 

when you are mapping out your page and have compartmentalized and put your components in boxes, using the separate responsibility principle your component structure will then be mapped out nicely.


3. What does it mean to build a ‘static’ version of your application?

A static site is a version of your data model that has no interactivity. you don't use state at all to build a static version of your site. State is reserved for interactivity which is data that changes over time.

4. Once you have a static application, what do you need to add?

You'll need to test your site, If you make a change to your underlying data model and call ReactDOM.render() you can see the updated changes. After you have built your static site, to make your UI interactive, you need to be able to trigger changes to your underlying data model. React achieves this with state.



5. What are the three questions you can ask to determine if something is state?

the three questions you should ask tomdetermine if something is state:

1. Is it passed in from a parent via props? If so, it probably isn’t state.

2. Does it remain unchanged over time? If so, it probably isn’t state.

3.Can you compute it based on any other state or props in your component? If so, it isn’t state.

6. How can you identify where state needs to live?

For each piece of state in your application:

Identify every component that renders something based on that state.

Find a common owner component (a single component above all the components that need the state in the hierarchy).

Either the common owner or another component higher up in the hierarchy should own the state.

If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
