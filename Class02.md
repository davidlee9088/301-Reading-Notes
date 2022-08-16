## Reading Notes Class 02

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
Based off the diagram, the first thing that happens during the render is processing the data.  static getDerivedStateFromProps

2. What is the very first thing to happen in the lifecycle of React?
During the life cycle, the first thing happens will be the mounting phase
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
Constructor, componetDidMount, render, componentWillUnmount, React Updates

4. What does componentDidMount do?
If you need to load anything using a network request or initialize the DOM.

1. What types of things can you pass in the props?
Almost any value can be passed in the props. For an example, any JavaScript data type from integers over objects to arrays.
2. What is the big difference between props and state?
Props are used to pass data from one component to another. The state is a local data storage that is local to the component only and cannot be passed to other components.
3. When do we re-render our application?
The react itself re-renders everytime state of componenet has changed.
4. What are some examples of things that we could store in state?
Any data can be stored in the State.