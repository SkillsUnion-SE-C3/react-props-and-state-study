[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# React Props & State: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [What is Props and how to use it](https://reactjs.org/docs/components-and-props.html)
- [What is State and how to use it](https://reactjs.org/docs/state-and-lifecycle.html)
- [Props vs State](https://www.youtube.com/watch?v=m1eZzN1ppPY&t=22s)
- [Primitive and non-primitive recap](https://www.youtube.com/watch?v=pslr6SWXFjQ)
- [What is immutability and it's benefits](https://youtu.be/4LzcQyZ9JOU)
- [Event Handling instructional video](youtube.com/watch?v=Zbjmfqw9RXM)
- [Event Handling in React documentation](https://reactjs.org/docs/handling-events.html)
- [Submit default behaviour and how to overcome it](https://www.youtube.com/watch?v=I_fVO_NzT2g)


## Questions

1. When do you use `props`?

   ```
   Props stands for properties, it is a special keyword used to pass data from one component to another. Components receive data from outside with props, whereas they can create and amanage their own data with state. 
   ```
2. What is the direction of passing props?

   ```
   It can be likened to passing in arguments into functions. 
   As they are read only, data and there is one way unidirectional flow, props can only be passed from parent component to child components, and cannot be changed by child components. 
   ```

3. How do you get access to props in child component?

   ```
   For components that contains child components or React nodes inside of the component, the use of this.props.children can access React node or component instances.

4. When do you use `state`?

   ```
   The simplest way to define a component is to write a Js function. It can accept a single props object argument with data and return a react element, which is known as a function component. React also accepts ES6 classes. 
   Due to React hooks, states can be used in both functional and class Components. 
   Props is used to pass in data but instead state is used to manage data. 

   ```

5. When does a component rerender

   ```
  They rerender when there is a change in their state or props. 
   ```

6. What will be the values of book and bookCopy? Why?

   ``` js
   const book = {title: "Hobbit", haveRead: false} 
   const bookCopy = book
   bookCopy.haveRead = true
   ```

   ```
 Both book and bookCopy will be true as they are pointing to the same reference point. 
   ```


7. What are the differences of implementing event listener in plain JavaScript vs React?

   ```
  As in React it will take effect by change of State, the event handler is often separated e.g. in function from the onclick part otherwise this will happen immediately. 
   ```

8. Why do you need to prevent default behaviour of a button?

   ```
   As the refresh works different in React and you cannot return false to prevent default in React 
 to preventDefault() you can use e. which is a synthetic event, you can pass e in as an argument in a function and then type e.preventDefault();
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice

Reference states and props 
Freecodecamp(2021)
