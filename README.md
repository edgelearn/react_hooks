# ReactJS Hooks

Run the following command to get a basic ReactJS application setup for Hooks:

```
npx create-react-app my-app
cd my-app
yarn start
```

1. useEffect

* Add a button to the App.js file

* Add an event handler to that button to track how many times it was clicked

* Add a useEffect in the render() to change the document title to display how many times the button has been clicked.

* Update the useEffect to only be triggered when the counter has changed it's value.

* Update the useEffect to have a cleanup function that sets the document title to a generic title.

2. useRef

* Create a new functional component and have it be used within App.js

* Add a link and a text input field.

* Add the useRef so that when the link is clicked the input field has the focus.

3. useState

* Create a new functional component and have it be used within App.js

* Add a button to the functional component

* Add a useState to track a counter for each click

* Display the count as part of the button's text

4. useMemo

* Create a new functional component and have it be used within App.js

* Add a text input and a button to the functional component

* Add useState to manage the value stored in the text input

* Add useMemo to calculate the volume of a sphere based upon the the value in the text input = radius of the sphere

* Display the results from the useMemo below the button

5. useContext



6. useReducer


After you have completed all of the exercises, commit your changes with the following command:

```
git commit -am "ReactJS Hooks Examples"
```
