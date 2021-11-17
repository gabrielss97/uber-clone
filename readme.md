<h1>Building Uber Clone</h1>

<h2>Configuring Redux</h2>

Set up redux ("yarn add @reduxjs/toolkit" and "yarn add react-redux") 
Now wrap the App with a PROVIDER and inside the tag provider we put store={} and create store.js in the main folder

Now inside the store.js we put:
<code>import { configureStore } from '@reduxjs/toolkit'
export const store = configureStore({
  reducer: {},
})</code>

and create a reducer, in this case ->  nav:navReducer, then we create a folder named slices and put inside navSlice.js to store your initial states and reducers,
in this js we will use <a href="https://redux-toolkit.js.org/api/createSlice" target="_blank">createSlice()</a> method.

After configuring createSlice we distructuring navSlice.actions then create Selectors and export default navSlice.reducer

Import the store in App.js

<h2>Doing the HomeScreen</h2>

Starting create the folder screens and HomeScreen.js inside, for the component I use the shortcut rnfes and import the SafeAreaView from react-native to prevent the text going to a wrong position

Lets add <a href="https://github.com/jaredh159/tailwind-react-native-classnames" target="_blank">Tailwind</a> in this project with: <b> yarn add tailwind-react-native-classnames</b>

Now just import 'tailwind-react-native-classnames' into component





Obs: In React Native flex is by default column
