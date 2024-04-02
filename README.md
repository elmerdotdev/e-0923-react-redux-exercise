# E-0923 React Redux Exercise

1. After accepting the assignment, create a branch called *dev* and clone the repository to your local machine
2. Run **git switch dev** to switch to the dev branch
3. Create a new React app by running *npm create vite@latest redux-practice --template react
4. Run *cd redux-practice* and run *npm install* to install the node packages
5. Run *npm install --save react-redux @reduxjs/toolkit* to install Redux Toolkit
6. Create a slice called **UserSlice.ts** and a component called **User.tsx**
7. Inside the slice file, create 3 states: firstname, lastname, and age. You can decide what the default values are
8. Create a reducer to increment the age by 1
9. Create a **store.js** and setup your store
10. Wrap your app with the created Redux store provider
11. On your User.tsx component, output the firstname, lastname, and age from the Redux store
12. Create a "Increment age" button inside the same component. Clicking this button will increase the age by 1
13. After you are done, push your changes to dev branch
14. Create a pull request from dev to master and merge
