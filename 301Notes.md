### 301 NOTES

   # react lifecycle

   1. The rendering occurs before the componentDidMount
   2. The first thing that happens is that an instance of a component is created
   3.  constructor, render, componentDidMount, react updates, componentWillUnmount
   4. componentDidMount is invoked directly after a component is mounted and can be used to load anything with network requests, initialize the DOM, set up subscriptions,set states

   # react states vs props

   1. You can pass counter components through props
   2. states happen outside of components, props are on the outside and components are passed through them
   3. We rerender our app when