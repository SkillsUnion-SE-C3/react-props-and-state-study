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
   Props stand for properties and is essentially JavaScrips. It is used when you want to represents an object property and returns a React element.
   ```
2. What is the direction of passing props?

   ```
   Top to bottom from parent to child
   ```

3. How do you get access to props in child component?

   ```
   By replacing props with this.props
   ```

4. When do you use `state`?

   ```
   You would use state when you want React components to be able to change their output over time - as in the example of a timer, you want the output to update per second.
   ```

5. When does a component rerender

   ```
   Each time there is an update
   ```

6. What will be the values of book and bookCopy? Why?

   ``` js
   const book = {title: "Hobbit", haveRead: false} 
   const bookCopy = book
   bookCopy.haveRead = true
   ```

   ```
   Because it is a referene type and mutable, firstly book would remain as it is and then bookCopy would create a new object with true for haveRead instead of what is currently there.
   ```


7. What are the differences of implementing event listener in plain JavaScript vs React?

   ```
   In react the event handler uses camel case and whereas in JavaScript, the event handler is string, in JSX it is a function
   ```

8. Why do you need to prevent default behaviour of a button?

   ```
   You would need to use the preventDefault method.
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
