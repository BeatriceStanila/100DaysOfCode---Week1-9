✅ REACT RECAP CONTINUED

Each instance of a component has its own lifecycle that it goes through!

Generally, there are 3 main phases of a react component:

**MOUNTING** - when you first decide to show that react component on your page

- if the component is not already on that page, this will be the first time that it gets rendered and shown
- it will run once for every time that the component is rendered onto the page

**UPDATING** - this will happen at a couple of different times

1.  if a prop that comes into your component changes → it will cause the component to re-render
2.  if the component itself has a state variable that is updating

**UNMOUNTING** - when you no longer want to show a react component on the page

BrowserRouter as Router = is a component used to encompass all of the different components in your app that will exist inside of the router system

What is state management?

- the data in your application
- the only time a react app will re-render is when a state changes (add/delete item)
