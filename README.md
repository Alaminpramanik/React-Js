# Getting Started with Create React App

This project was bootstrapped with Create React App

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about running tests

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about deployment for more information.

### `npm run eject`


### `npm run build` fails to minify


### `npm run eject`


### React Js Basic 

### `Distructuring `
const alamin ={
  name:'i am a font-end developer',
  details:{
    react:'40%',
    javascrit:'50% complate',
    bootstrap:'70%'
},
}
const {details :{react} = {} }= alamin;
const {details :react}= alamin;
console.log(react)
const {name}= alamin;
console.log(name)


### `array method filter,find, findIndex, concat, splice, push, map`

numbers =[1,2,3,4,5,6]
const filter=numbers.filter((num)=> num<2);
console.log(filter)

const find=numbers.find((num)=> num>2);
console.log(find)

const findIndex=numbers.findIndex((num)=> num>2);
console.log(findIndex)

const slice=numbers.slice(2,5);
console.log(slice)

const concat=numbers.concat(7,8,9);
console.log(concat)

const splice=numbers.splice(1,2,7,8,9);
console.log(splice)

const push=numbers.push(7,8,9);
console.log('push',push)

const map= numbers.map((num) => {
  return num *2
})
console.log('map',map)


### `function react`
const adnan= (name) => {
  console.log("i'm a full stack developer");
   return "i'm a full stack developer";
}

## `array function react`
const amin= ()=> "i'm a full stack developer"

### `import and export`

const pramanik = ()=>{
    console.log("i'm a full stack developer");
 }

`single export`
const num=20;
multiple export
export default pramanik;

`single import rename`
import {num as number} from './pramanik'; 

`multiple import`
import aaa from './pramanik';

### `spread or rest operations`

### `spread operator`
const number =[1,2,3,4]
const addnumber=[...number,5,6,7,8,9]
console.log(addnumber)

### `rest operator`

const adnan = (...arg)=> {
  console.log(arg)
}
adnan(1,2,3)
