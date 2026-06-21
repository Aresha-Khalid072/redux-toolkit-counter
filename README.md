# Redux Toolkit Counter

A simple counter and like-button app built with **React** and **Redux Toolkit**, created to practice state management fundamentals — actions, reducers, and the store — using RTK's modern, boilerplate-free approach.

## Features

- 🔢 Increment / decrement a counter using Redux Toolkit
- ➕ Increase the counter by a custom amount via an input field
- ⚡ Built with Vite for a fast dev experience
- 🧩 Clean separation of state logic via `redux/features/`

## Tech Stack

- [React](https://react.dev/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [React Redux](https://react-redux.js.org/)
- [Vite](https://vitejs.dev/)

## Project Structure

```
src/
├── redux/
│   ├── features/
│   │   ├── counterSlice.js   # Counter state and reducers
│   │ 
│   └── store.js              # Redux store configuration
├── App.jsx                   # Main component
├── main.jsx                  # App entry point
└── index.css                 # Global styles
```

## Getting Started

### Prerequisites

- Node.js installed on your machine
- npm (comes with Node.js)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Aresha-Khalid072/redux-toolkit-counter.git
   cd redux-toolkit-counter
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm run dev
   ```

4. Open the local URL shown in the terminal (usually `http://localhost:5173`)

## What I Learned

This project was built to understand:
- How to set up a Redux store with `configureStore`
- Creating slices with `createSlice` for cleaner reducer logic
- Connecting React components to Redux state with `useSelector` and `useDispatch`
- Dispatching actions with a payload (`incrementByAmount`) alongside simple actions
- Managing multiple independent pieces of state (counter + likes) in one store

## License

This project is open source and available for learning purposes.