1. what is the storage of Browser for the React.js 
   5mb
2. how u can convert a given component into a library and how long u will take ??
     1st we will write npm init and then we will have package.json and and all our code which we wrote 
     2nd npm publish then our code willl be publish and then we can use that librray in our code ( npm publish before that we need to auth with npm website as a github)
     
3. what is libarary and framework
4. what u will do to change the theme of complete application and 
5. how u define a component that u want to use for multiple Project
6. how u will use a componenet that act as nodule_modules (just as a dependency)
7. diffence between the redux and redux toolkit and 
8. what is the version of redux and react-redux and toolkit 
 redux-tookit=>4.2.0
 redux ===> 1.8.2
 react-redux ==>8.0.2
9. how can u pass the redux state of the parent project to the iframe 
10. what is ref 
11. what is logermiddleuse thunk 
12. what is hosting
    suppose  
    console.log(a);
    console.log(b);
    console.log(c)
     where
     var a;
     let b;
     const c;
13. what is event loop 
14. const obj={name : {fname :"harish"}, age : 21 } , how to print the fname without the 2 times 
    answer : const {name : {fname}} =obj; console.log(obj);
15. explain the work flow of the Redux 
16. what to center a div extractly center in x and y axis
17. .parent {
    background: red;
    height: 10rem;
    width: 10rem;
    display: flex;
    justify-content: center;
    align-items: center;
    }
    
    grid:
    
    display: grid;
    justify-content: center;
    align-content: center;
    
    
    or 
    display: grid;
    justify-items: center;
    align-items: center;
    
    
    or 
    
    
    display: grid;
    justify-content: center;
    align-content: center;
    justify-items: center;
    align-items: center;
    
    
    or
    display : table-cell;
    vertical-align : middlle

18. differnce between the splice and slice 
const a=[1,2,3,4] 
a.slice(0,3)
[1, 2, 3]
print a
[1, 2, 3, 4]
a.splice(0,3)
[1, 2, 3]
print a
[4]
or another sceneries 
a
[22, 44, 55, 22, 4]
a.splice(0,0,2,4,5)
print a
[2, 4, 5, 22, 44, 55, 22, 4] 


slice will return a new array and it doesnt effect the cuurent array and 
splice will remove or add the element to cuurent array (its changes the current array) and return type is  :: i will return the no of element effected
