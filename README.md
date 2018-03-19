# Redux

To learn how to properly use Redux, we have to understand three basic concepts of this library. The first one is called store. When using Redux to manage our state, we let it keep an updated version of this state in the store. This is the main purpose of this piece of Redux. The store exists to hold (store) the current state of our data and to become the single source of truth.

The second concept is called reducer. Reducer is nothing but a pure function that gets our app's current state and generates a new state based on an action. Actions are the third concept that we are interested in. To define an action to be applied to our state, we simply create an object with a type and any arbitrary number (0..N) of properties.

![Redux graph](https://res.cloudinary.com/nogsantos/image/upload/v1521469412/redux-graph_pbtuql.png)

#### Fonts

[Auth0](https://auth0.com/blog/redux-practical-tutorial/?utm_source=twitter&utm_medium=sc&utm_campaign=redux_tutorial)