# Custom Hook

<br>

> A custom Hook is a JavaScript function whose name starts with ”use” and that may call other Hooks. For example, useFriendStatus below is our first custom Hook:

<br>

> Unlike a React component, a custom Hook doesn’t need to have a specific signature. We can decide what it takes as arguments, and what, if anything, it should return. In other words, it’s just like a normal function. Its name should always start with `use`

<br>

> Custom Hooks offer the flexibility of sharing logic that wasn’t possible in React components before. You can write custom Hooks that cover a wide range of use cases like form handling, animation, declarative subscriptions, timers, and probably many more we haven’t considered. What’s more, you can build Hooks that are just as easy to use as React’s built-in features.

<br>


# React - Lifting State

<br>

> We lift up state to a common ancestor of components that need it, so that they can all share in the state. 
This allows us to more easily share state among all of these components that need rely upon it.


<br>

# Thinking in React

- single responsibility principle, a single component is only do one thing
- build up component hierarchy base on UI
- build a static version
- identify states and decide which parts should live
- add data flow

