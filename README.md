#Parcel
 - Dev Build
 - Local Server
 - HMR = Hot Module Replacement
 - File Watching Algorithm - written in C++
 - Caching - Faster Builds
 - Image Optimization
 - Bundling
 - Minification
 - Compress
 - Consistent Hashing 
   -->Consistent hashing is a distributed hashing technique used to achieve load balancing and minimize the need for rehashing when the number of nodes in a system changes. It is particularly useful in distributed hash tables (DHTs), distributed caching systems, and other distributed storage systems
 - Code Splitting
 - Differential Bundling - support older browsers
 - Diagnositic
 - Error Handling
 - HTTPs
 - Zero Config
 - Tree Shaking
     remove unused code for you
 - Different dev and production bundles     




# 2 types Routing in web apps 
-- Client Side Routing 
-- Server Side Routing

# Redux Toolkit
-- Install @reduxjs/toolkit and react-redux
-- Build our store
-- Connect our store to our app
-- Slice (cardSlice)
-- dispatch(action)
-- Selector



# Immer
-- Internally Redux uses immer
-- Tiny Package that allows you to work with immutable state


# Testing 
-- Types of Testing is there 
-- Unit Testing
   There are we testing the specific component in isolation mode
-- Integration Testing
   These are we testing after we integrate them.
-- End to End Testing e-e 
   Selenium 


# Setting up Testing in our app
-- Install React Testing Library 
-- Installed jest
-- Install babel dependencies
-- Configure Babel 
-- Configure Parcel config file to disable default bable transpilation
-- Jest -npx jext init
-- Install JSDOM Library
-- Install @babel/preset-react - to make JSX work in test cases
-- Include @babel/preset-react inside my babel config
-- Include @testing-library/jest-dom