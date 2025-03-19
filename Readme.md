# Redux with React

This project demonstrates how to integrate **Redux** with a React application for global state management.

## What is Redux?
Redux is a predictable **state management** tool for JavaScript applications. It helps manage the application state in a centralized store.

## What is React-Redux?
**React-Redux** is the official Redux binding for React. It provides hooks like:
- `useSelector()` → To access the Redux state.
- `useDispatch()` → To dispatch actions.
- `<Provider>` → To connect Redux with React.

---

## **Step 1: Install Redux and React-Redux**
Run the following command in your React project:<br>
- **npm install @reduxjs/toolkit react-redux**

## **Step 2: Create a Redux Store**
/src <br>
 ├── /store <br>
 │   ├── store.js <br>
 │   ├── counterSlice.js <br>
 ├── App.js <br>
 ├── index.js <br>

## **Step 3: Create a Redux Slice**
A slice contains reducers and actions for a specific part of the state.

## **Step 4: Provide the Redux Store to React**
Modify index.js to wrap your app with the Redux Provide

## **Step 5: Using Redux in a React Component**
Now, we will use Redux state and actions in a React component.