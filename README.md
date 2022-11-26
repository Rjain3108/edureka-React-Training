- [Module 1](#module-1)
  - [Introduction](#introduction)
    - [Installation](#installation)
    - [Resources](#resources)
    - [Prequisite (Good to have)](#prequisite-good-to-have)
    - [Diff between Angular and React](#diff-between-angular-and-react)
  - [Architecture](#architecture)
    - [Component Base Architecture](#component-base-architecture)
    - [Single Page Architecture](#single-page-architecture)
  - [Concept of JavaScript](#concept-of-javascript)
    - [ES5](#es5)
    - [ES6](#es6)
    - [Java Script Data type Supprt](#java-script-data-type-supprt)
    - [Array Define and Iteration](#array-define-and-iteration)
    - [Old method to Iterate through array:](#old-method-to-iterate-through-array)
    - [New mathod to iterate through array:](#new-mathod-to-iterate-through-array)
    - [map ----\> use to apply operation](#map------use-to-apply-operation)
    - [filter ----\> Only filter values](#filter------only-filter-values)
  - [Basic of React](#basic-of-react)
    - [npm =\> Node Package Manager](#npm--node-package-manager)
    - [JSON=\> Javascript Object Notation](#json-javascript-object-notation)
    - [package.json =\> backbone of application](#packagejson--backbone-of-application)
    - [How to install](#how-to-install)
    - [Step to install local package](#step-to-install-local-package)
    - [Step to install global package](#step-to-install-global-package)
    - [Step to create react app](#step-to-create-react-app)
- [Module 2](#module-2)
    - [Dependencies:](#dependencies)
    - [Component:](#component)


----------
# Module 1
----------

## Introduction
----------------

### Installation
----------------
To install node.js [Click here](https://nodejs.org/en/)
To install visual studio code [Click here](https://code.visualstudio.com)
````
MEAN: MongoDb, ExpressJs, AngularJs, NodeJs
MERN: MongoDb, ExpressJs, ReactJs, NodeJs
````
### Resources
------
1. codecademy.com
2. w3schools.com
   
### Prequisite (Good to have)
-------
1. JavaScript
2. Bootstrap
3. EcmaScript (ES5 and ES6)

### Diff between Angular and React
----

| Angular       | React    |
|---------------|----------|
| Working on typescript | Working on Javascript |
| Working on actual DOM | Working on Virtual DOM|
| Multipage Application | SinglePage application|

-----------------------
## Architecture
-----------------------
### Component Base Architecture
- We have one page which stand for layout (common part like: Header,Footer)
- For each page we make one component (Like Home,Layout,Contact,About and others)
- One component have its own html,css and logic

### Single Page Architecture
- Page will not refresh
- Application are faster

--------------------------------
## Concept of JavaScript
--------------------------------

### ES5
var => Redeclare and Reassign
*function define:* 

```
function add(a,b) {
  return a+b
}
```

### ES6
let => We can not redeclare but we can reassign
const => we can not redecalre as well reassign

*function define:*

```
const add = (a,b) => {return a+b}
```

### Java Script Data type Supprt
- String => "String", 'string'
- Int => 10 23.45
- Boolean

### Array Define and Iteration
- In Javascript Array is hetrogenous e.g., [7,'Rishabh',true]

### Old method to Iterate through array:

````
var a = [7,'Rishabh',true]
for(var i=0; i < a.length; i++) {console.log(a[i])}
````

### New mathod to iterate through array:
> This is same like dataweave. we have 2 functions 
 - map
 - filter

Example

### map ----> use to apply operation

   > Example 1 
````
var a = [7,'Rishabh',true]
a.map((data)=>{console.log(data)});
var num = [0,1,2,3]
num.map((data)=>{return datax2});
````


### filter ----> Only filter values

````
var num = [0,1,2,3]
num.filter((data)=>{return data*2})
````

--------------------
## Basic of React
--------------------
### npm => Node Package Manager
> help us to build application
> have more tha 12L+ package
> it is open source

we have 2 type of dependency
1. local
2. global => build create test

### JSON=> Javascript Object Notation
````
{
    "name": "joe",
    "class": "2nd"
}
````

### package.json => backbone of application

### How to install
  1. We must install node.js
  2. navigate to folder using cmd/terminal
  3. npm init
  4. answer all question
  5. yes

### Step to install local package
1. navigate to folder using cmd/terminal
2. type-> npm install {package}

### Step to install global package

Win
  1. Run cmd as admin
  2. npm i -g create-react-app

Mac/Linux
  1. open terminal
  2. sudo npm i -g create-react-app

### Step to create react app

Win
  1. Run cmd as admin
  2. npm i -g create-react-app
  3. Navigate to folder where you want to create using cmd
  4. create-react-app myapp
  5. cd myapp
  6. npm start

Mac/Linux
  1. open terminal
  2. sudo npm i -g create-react-app
  3. Navigate to folder where you want to create using terminal
  4. create-react-app myapp
  5. npm start


---------------------
# Module 2
---------------------

### Dependencies:
  1. React
  2. React-dom : To bind componet or JSX file into HTML format
  3. React-Scripts:  To run the code

### Component:

| Functional Base component      | Class Base component (ES6)   |
|---------------|----------|
| Light in weight| Heavy in weight |
| Dumb Component | Logical Component|
| Multipage Application | SinglePage application|

