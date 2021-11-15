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
   They are used when passing data from one component to another.
   ```
2. What is the direction of passing props?

   ```
   From top to bottom. 
   ```

3. How do you get access to props in child component?

   ```
   using a callback function. 
   ```

4. When do you use `state`?

   ```
   If data is managed by one component, but another component needs access to that data, you'd pass the data from the one component to the other component via props. If a component manages the data itself, it should use state and setState to manage it.
   ```

5. When does a component rerender

   ```
   whenever there is a change in their state or props
   ```

6. What will be the values of book and bookCopy? Why?

   ``` js
   const book = {title: "Hobbit", haveRead: false} 
   const bookCopy = book
   bookCopy.haveRead = true
   ```

   ```
   book : {title: "Hobbit", haveRead: true} 
   bookCopy: {title: "Hobbit", haveRead: true} 

   objects are changed on both levels if spread is not used. 
   ```


7. What are the differences of implementing event listener in plain JavaScript vs React?

   ```
  the event listener would action on default where as react will action on state change.
   ```

8. Why do you need to prevent default behaviour of a button?

   ```
   So the button does not perform it's default action.
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
