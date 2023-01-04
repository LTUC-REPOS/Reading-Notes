
# What is global state with React?

<br>

>  originally, the state is held and modified within the same React component. In most applications, different components may need to access and update the same state.

<br>

> The main purpose of the `global state` is to share a state among multiple components.

<br>

### There are three ways this communication can happen


<br>


- With a child component
- With a parent component
- With a sibling component

<br>

# Context

<br>

> Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language

<br>

> Props drilling is a term to describe when you pass props down multiple levels to a nested component, through components that don't need it.

<br>


### Use React context

<br>

- Create context using the createContext method.
- Take your created context and wrap the context provider around your component tree.
- Put any value you like on your context provider using the value prop.
- Read that value within any component by using the context consumer.

<br>

# Redux 

<br>

> Redux is an Open Source Library which provides a central store, and actions to modify the store. It can be used with any project using JavaScript or TypeScript

<br>


### Comparing Redux & Context API

<br>


![image](https://user-images.githubusercontent.com/98183485/210637035-a3d0f5c2-0b34-424e-96d8-51bdc852d977.png)



