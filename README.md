# React + Vite

- npm run dev

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- First of all we need to make store named as store in App. and store need features that are necessasry that's why it is better than flux(not good structre)
- now make feature folder which take todo,goto,purchase etc etc files or say reducer. todoslice is basically a reducer which we need(slice name is standard)
- createSlice is used to make reduce and nonoid is used to give id it is just a new feature
- slice takes 3 parameter name,initial state and reducer property
- each single reducer takes 2 parameter 1: state and 2: action
- then we export all the reducers individually and also collectively
- useSelector is used to get the data from the store
- useDispatch is use to change the data in the store with the help of reducer methods.
