# Namaste React 🚀

# Parcel

- Dev Build
- Local Server
- HMR = Hot Module Replacement
- File Watching Algorithm - written in C++
- Caching - Faster Builds
- Image Optimization
- Minification
- Bundling
- Compress
- Consistent Hashing
- Code Splitting
- Differential Bundling - support older browsers
- Diagnostic
- Error Handling
- HTTPs
- Tree Shaking - remove unused code
- Different dev and prod bundles

# Namaste Food

/\*\*

- Header
- - Logo
- - Nav Items
- Body
- - Search
- - RestaurantContainer
- - RestaurantCard
-      - Img
-      - Name of Res, Star Rating, cuisine, delery tie
- Footer
- - Copyright
- - Links
- - Address
- - Contact
    \*/

Two types of Export/Import

- Default Export/Import

export default Component;
import Component from "path";

- Named Export/Import

export const Component;
import {Component} from "path";

# React Hooks

(Normal JS utility functions)

- useState() - Superpowerful State Variables in react
- useEffect()

# 2 types Routing in web apps

- Client Side Routing
- Server Side Routing

# Redux Toolkit

- Install @reduxjs/toolkit and react-redux
- Build our store
- Connect our store to our app
- Slice (cartSlice)
- dispatch(action)
- Selector

# Types of testing (developer)

- Unit Testing - Testing One Component in Isolation || means seperately
- Integration Testing - Testing Integration of Components
- End to End Testing (or) e2e Testing - End-to-end testing verifies that all components of a system can run under real-world scenarios. The goal of this form of testing is to simulate a user experience from start to finish. E2E testing can find software dependencies while also validating the system under test, its data integrity and integrations.

# Setting up Testing in our app

- Install React Testing Library
- Install Jest
- Install Babel Dependencies
- Configure Babel
- Configure Parcel Config File to disable default Babel transpilation
- Jest - `npx jest --init`
- Install jsdom library
- Install @babel/preset-react - to make JSX work in test cases
- Include @babel/preset-react inside my babel config
- npm i -D @testing-library/jest-dom
