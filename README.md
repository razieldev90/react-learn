# react-learn

# Start a React app
 $ npx create-react-app myapp

# Run Development server
 $ cd myapp
 $ npm start
 
 visit localhost:3000


# Create a react component
 create a file MyComponent.js in src folder

 import React from 'react';

 const MyComponent = () => {
     return (
         <div>
             <h1>MyComponent<h1>
         </div>
     )
 }

 export default MyComponent;


# Fetch data from api

 import React, {useEffect} from 'react';


 const MyComponent = () => {

     useEffect(()=>{
         fetch(URL_API, options)
        .then(res => res.json())
        .then(data => console.log(data))
     },[])

     return (
         <div>
             <h1>MyComponent<h1>
         </div>
     )
 }

 export default MyComponent;
