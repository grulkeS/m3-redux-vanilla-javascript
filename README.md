# m3-redux-vanilla-javascript

# vanilla redux experimental

This is an example application from https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/counter-vanilla extended by Patrick to better see what the reducer is, what are the actions, how does the state look like, how to setup the store correctly, how everything works together. (see also store.dispatch and .subscribe())

Now, lets have some fun with it ...

## The only Iteration - lets change the value by how much we can increase the count per click ...

Lets just simply use what already is there to change the Increase value.

Start by adding a new property/value "increaseBy : 1" to our state-Object, called here "initial". 

Next add two new actions to our reducerFunction which should increase or decrease our state property value for "increaseBy".

We also need two new methods/functions which will dispatch the Action KeyWord to our reducerFunction.

If you have that, the only thing left over is adding two new buttons to our render() function which will call our increase or decrease dispatcher function.
Also add a an element which shows our increasBy value. For example like that: ( increasing counter by: ${store.getState().increaseBy.toString()})

Got it? Great, you now have successfully build your own steps to use redux in full. Thats all it is. 

