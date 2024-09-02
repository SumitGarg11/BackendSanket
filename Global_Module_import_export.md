1 . module  
module is object , that have set of properties , export 
module.export = {
key: function_Name;

}


in index.js i want to use a function from the other file so we need to export or import 
2. __dirname
3. process
4. global

how to consume this detail 
there are two ways 
|- common module
|- es module 

// commmon  module -> require helps to consume this module that export some where , what ever the object you export you can use it 
// es module -> import keyword make sure where u use import keyword , that file have the extenstion of .mjs then u can use it 
// import abcd from './filename.js' u can not change the exports method 
