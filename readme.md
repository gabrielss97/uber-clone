<h1>Building Uber Clone</h1>

<h2>First Steps</h2>

1- Set up redux ("yarn add @reduxjs/toolkit" and "yarn add react-redux")
   Now wrap the App with a PROVIDER and inside the tag provider we put store={} and create store.js in the main folder

2- Now inside the store.js we put:
<code>import { configureStore } from '@reduxjs/toolkit'

export const store = configureStore({
  reducer: {},
})</code>

and now create a reducer, in this case ->  nav:navReducer, then we create a folder named slices and put inside navSlice.js to store your initial states and reducers,
in this js we will use <a href="https://redux-toolkit.js.org/api/createSlice">createSlice()</a> method

Obs: In React Native flex is by default column
