

# JAVASCRIPT

## JAVASCRIPT HISTORY AND BASIC
<img src="images/Saved Pictures/js.png">

### CONTROL STRUCTURE SUMMARY TABLE 
|Control Structure|Description|Syntax|
|---------|----------|--------------|
|If-else|If the specific value is true then it will get execute otherwise else condition will execute|if(condition){//execute if condition is true}else{//execute this if  condition is false}|
|For loop|execute code number of times|for(intialization;Condition;Increment/decrement){}|
|While loop|code execute till specific condition is true|while(condition){//code to be execute}|
|Do-While|code execute once then if the condition is true it will execute again|do{//code to be execute}while(condition);|
|Switch|used to choose the option|switch(expression){case n: break}|

### ARITHMETIC OPERATOR SUMMARY TABLE
|Operator|Description|Syntax|
|---------|----------|--------------|
|+|Additon If both operands are number type| a+b|
|+|Concatination if one of the operand is string type|a + "b"|
|-|Substraction|a - b|
|* |Multiplaction|a * b|
|/ |Division | a/b|
| %| Modulus gives remainder as output| a% b |
|==|Equal to|a == b|
|===| first check type of varaiable and then value gives output as boolean value|a === b|
|!=|Not Equal| a != b|
|>|Greater than|a > b|
|<|Less than|a < b|
|>=|Greater than equal to|a >= b|
|<=|Less than equal to|a <= b|

###  LOGICAL OPERATOR SUMMARY TABLE
<table>
        <tr>
                <th>Operator</th>
                <th>Description</th>
                <th>Synatx</th>
        </tr>
          <tr>
                <td>&&</td>
                <td>AND</td>
                <td>(a < 5 && b > 3)</td>
        </tr>
          <tr>
                <td>||</td>
                <td>OR</td>
                <td>(a == 5 || b == 5)</td>
        </tr>
          <tr>
                <td>!</td>
                <td>NOT</td>
                <td>!(a==b)</td>
        </tr>
</table>

### CONDITIONAL OPERATOR SUMMARY TABLE
|Operator|Description|Synatx|
|---------|----------|--------|
|? : |Ternary Operator|a?b:c|

## VARIABLES

JavaScript **variables** are **containers** for storing data.
Their are **_three_** variables in JavaScript.

1.**Var**
This variable is declared in the ES5 script. It has functional scope. You can re-declare var many times. You can update the variable.

**_Syntax: var VariableName = Value;_**

``` JAVASCRIPT
var a = 10;
var b = "myName";
var c = "true";
```
2.**Let**
This variable is declared in ES6 due to the drawback of _var_ Variable. It has lexical scope. You cannot redeclare _let_ variable. You can update it.

**_Synatx: let VariableName = Value;_**

``` v
let a = 5; 
a = 7;
let a =7; //will throw error

```

3.**Const**
This variable is declared in ES6 due to the drawback of _var_ Variable. It has lexical scope. You cannot redeclare _const_ variable. You cannot update it.

**_Synatx: const VariableName = Value;_**

``` JAVASCRIPT
const val= "Hi"; 
val = "Welcome to JavaScript"; // throw error
const val = "Hello";          //will throw error

```
### VARIABLES SUMMARY TABLE

|Variables|Syntax|Function|
|---------|--------|-------|
|var|var name ="Padma";|Have both local and global scope,can be redeclare and reassigned|
|let|let lastname ="Shaha"|lexical scope,cannot redeclare,can assign new value|
|const|const middelname ="Lokesh"|lexical scope.cannot redeclare ,cannot assign new value|

## DATATYPES

Datatypes are used to tell us which type of variable or value is used.
There are two types of data types in JavaScript.

**1.Primitive**(You cannot Change)
- Number
Number can be write in deciaml or without decimal.
``` JAVASCRIPT
var x = 5;
var y= 3.10;

if you see the type of these variables you will following type.
typeof (x);
Number
typeof (y);
Number
```
- String
Every value you write inside **"** will consider as String in JavaScript.

``` JAVASCRIPT
var x = "Sasha";
var y = "10"

typeof (x);
String
typeof (y);
String
```
- Boolean
In JavaScript boolean uses one of the two value - ** true** Or **false**
``` JAVASCRIPT
var a = true;
typeof (a);
Boolean
```
- Undefined
Variable declare without value or given value as undefined will have the value undefined.
``` JAVASCRIPT
var a;
var a = undefined;
typeof (a);
undefined
```
- Null
by default, the type of null falls under the Non-primitive object type. Used to give null value as input.

- Symbol(ES6)

**2.Non-Premitive**(You can Change)
- Object
In JS object are define using {} 
``` JAVASCRIPT
var student = { rollNo:"1",Name:"Taniska"};
typeof (student);
object

**To access the element from objects**
Synatx: NameOFObject.keyName
student.rollNo;
1
**To add new element in objects**
Synatx: NameOFObject.keyName = Value
student.class = "Sixth";
student ={rollNo:"1",Name:"Taniska",class = "Sixth"}
```
- Array
Their is no such concept of array in JS.array are kind of objects.written in [].
``` JAVASCRIPT
var Arraynum=[1,2,3,4,5];
console.log(Arraynum.length);
5
**Can Access array using index**
Arraynum[3];
4
**Can change value using index**
Arraynum[3]=10;
Arraynum = [1,2,3,10,5]

```
### DATATYPE SUMMARY TABLE

|Datatypes|Syntax|Used For|
|---------|--------|-------|
|Number|var num = 10;|Number can be write in deciaml or without decimal.|
|String|var str ="Sasha"|Every value you write inside **""** will consider as String in JavaScript.|
|Boolean|var bool = true;|In JavaScript boolean uses one of the two value - ** true** Or **false**|
|Undefined|var a = undefined; |Variable declare without value or given value as undefined will have the value undefined.|
|Null|var a = ;|by default the type of null falls under Non-premitive object type.|
|Object|var student = { rollNo:"1",Name:"Taniska"};|In JS object are define using {} |
|Array|var Arraynum=[1,2,3,4,5];|Array are kind of objects.written in [].|

## SCOPE
### FUNCTIONAL SCOPE

1.**Local Scope**
variable declare within function can only access by function.
``` JAVASCRIPT
Function local(){
var a =3;
console.log(a);
}
local();

---------
Output: 3
```

2.**global Scope**
variable declare outside the function can  access by  any function.
``` JAVASCRIPT
var a = 3;
function global()
{
var b = 10;
console.log(a);
console.log(a);
}
global();
-------------
output: 3
        10
```

3. **Lexical Scope** 
when variable define inside any {} it is known as lexical scope

A.**Let**

1.**Local Scope**
a variable declared within a function can only access by function.
``` JAVASCRIPT
{                                 
let x = 10;                               
console.log(x);     //lexical/block scope
}                            

---------
Output: 10

----------------------------------------------

function local(){           //Functional Scope      
let a = 5;                                           
if(a)                                                
{                                                    
console.log(x);             //lexical scope
}                                                    
else{                       //lexical scope
}                                                    
}                                 
```
2.**global Scope**
a variable declared outside the function can access by any function.
``` JAVASCRIPT
let y = 15;
{
let x = 10;   
console.log(x);
console.log(y);
}

-------------
output: 10
        15
------------------------------------------------------------
let y = 15;
function local(){                     //Functional Scope      
let a = 5;                                           
if(a)                                                
{                                                    
console.log(x);                       //lexical scope
}                                                    
else{ console.log(y);                 //lexical scope
}                                                    
}                                  
```
B.**Const**

1.**Local Scope**

a variable declared within a function can only access by function.
``` JAVASCRIPT
{                                 
const x = 10;                               
console.log(x);     //lexical/block scope
}                            

---------
Output: 10

--------------------------------------------------

function local(){           //Functional Scope      
const a = 5;                                           
if(a)                                                
{                                                    
console.log(x);             //lexical scope
}                                                    
else{                       //lexical scope
}                                                    
}                                 
```
2.**global Scope**
a variable declared outside the function can access by any function.
``` JAVASCRIPT
const y = 15;
{
const x = 10;   
console.log(x);
console.log(y);
}

-------------
output: 10
        15
--------------------------------------------------------------------
const y = 15;
function local(){                     //Functional Scope      
const a = 5;                                           
if(a)                                                
{                                                    
console.log(x);                       //lexical scope
}                                                    
else{ console.log(y);                 //lexical scope
}                                                    
}                                  
```
## COPY BY VALUE OR COPY BY REFERENCE

A.**Copy By Value**

the value will store in the initialized variable. Primitive datatype used as copy by value.

``` JAVASCRIPT
function square(x)
{
x= x* x;                         //x =100 and y=10(y remain same)
return x;
}
var y =10;                      // declare y and initalize its value 10
var result = sqaure(y);         // x=y the value of y will be copy to x
console.log(y);               //10   ---> no change
console.log(result);          //100 
-------------
output:100
```
**_If it is done by using call by reference then the value of y will also be changed._**



B.**Copy by Reference**

value will store in the pointed location by initialize variable.Non-Primitive datatype used as copy by value.
``` JAVASCRIPT
var student = { Name:Tanu,**rollno:10**,class=5th,subject:Maths}    //typeof student is object.object are non-premitive datatype,and non premitive are call by reference
var newStudent = student;                                       //newStudent is pointing to student
newStudent.rollno = 20;
console.log(student);
console.log(newStudent);

-------------
output:
{ Name:Tanu,**rollno:20**,class=5th,subject:Maths}
{Name:Tanu,**rollno:20**,class=5th,subject:Maths}
```
**_From the output it means if you do any changes in one file and passes its reference to another the changes will display in another field also._**

## FUNCTIONS
A function is a block of code design to perform a specific task. We can pass a function as _parameter_ also. Pure Function doesn't modify values outside the function, Pure function also returns the same values passed as input. High order Function that takes a function as parameter and returns function. 

**Properties of Function**
- Hoisting
- Overwrite
- Scope
- Act as a container
- objects
- Normal declaration using the function name
- Function can be assigned to a variable.
- function can be return from another function
- function returns a function

Synatx:
``` JAVASCRIPT
Function FunctionName(){
//code to be execute
}
```
**Function Returns**
when code reach to _return_ statement the function will stop executing.
Synatx:
``` JAVASCRIPT
var a = add(4,5);
function add(){
retun a+b;
}
-------------------
output:9
```
**IIFE(Immediately invoked function expression)**

Self-executing function expression(SEF)

Syntax:
``` JAVASCRIPT
 ;(function(){
 //code to be execcuted
})();    //calling function
----------------------------
Example:

(function () {                         //anonymous function
                    var a = 10;        //variable declare and initialized
                    var b = 12;
                    function add(a,b)        // function defination
                      {
                          console.log(a + b);
                      }
                      add();                  //function calling
             })();                           //function calling
```
             
## FUNCTION CONSTRUCTOR AND PROTOTYPE

**Constructor is the pointer to the function that created the object.**
``` JAVASCRIPT
Function Person(name,exp){
    this.name = name;                           //this kewyword refers to object of class
    this.exp = exp;
}

var sasha = new Person("Sasha",2);                //created constructor
console.log(sasha.name,sasha.exp);

--------------------------------------
Output:
Sasha 2

```
**Prototype is an object. Acts as a method. The prototype is used to add a new property to the constructor function.**

``` JAVASCRIPT
Function Person(name,exp){
    this.name = name;                           //this kewyword refers to object of class
    this.exp = exp;
}
Person.prototype.age = "25";                      //adding new value using prototype object
var sasha = new Person("Sasha",2,25);                //created constructor
console.log(sasha.name,sasha.exp,this.age);

--------------------------------------
Output:
Sasha 2 25

```

**Built-in Constructors**

1. var car  = new Object();                                                    //A new Object    object  
  
2. var name = new string();                                                   //A new String object  
      _Shuld not used_ 
      _Can be created directly example: var name = "sasha";_

3. var num  = new Number();                                                  //A new Number object 
   _Shuld not used_ 
   _Can be created directly example: var num = 1;_  

4.var yes  = new Boolean();                                                //A new Boolean object  
   _ not used_ 
   _Can be created directly example: var yes = false;_  

5. var arr  = new Array();                                                  //A new Array object  
   _Can be created directly example: var arr = [];_
   
6. var exp  = new RregExp();                                              //A new RegExp object
   _Can be created directly example: var exp = /[]/;_ 

7. var fun  = new Function();                                               //A new Function object 
   _Can be created directly example: var fun = Function(){};_  

8. var val  = new Date();                                                //A new Date object  
   _Can be access as example: val.getDate();_

9. Math () object dont use _new_ keyword.
   _Can be access as example: math.floor();_
   _Can be access as example: math.celi();_
  
 ### CONSTRUCTOR SUMMARY TABLE 
  |Built-In-Constructor|Synatx|
  |--------|---------|
  |Object| var car  = new Object(); |
  |String|var name = new string();  |
  |Number|var num  = new Number();  |
  |Boolean|var yes  = new Boolean();   |
  |Array|var arr  = new Array();   |
  |RregExp|var exp  = new RregExp();|
  |Function|var fun  = new Function(); |
  |Date| var val  = new Date();    |
  |Math ()|Math.floor();|
  
  
 ## ARRAY, OBJECTS, STRING METHODS
 
 1.**Array**
 ``` JAVASCRIPT
 Var names = ["Neha","Manish","Prapti","Ashish","Arjun","Soumya"];
 ```
 |Built in  Methods  | Syntax |Used For|
|------------------|---------|--------|
|Length()|names.[names.length]="Anushka"|easy way to add element at end of array|
|Push()|names.push("NewName")|To add element at end of array|
|Pop()|names.pop("soumya")|To remove element at end of array|
|Shift()|names.shift("soumya")|To remove element at begining of array|
|Unshift()|names.unshift("soumya")|To add element at begining of array|
|Concat()|var CreateNewVariable = names.concat(surname)|joins two array|
|forEach()|names.forEach("PassFunction")|To remove element at end of array|
|Map()|names.map("passFunction")|To add values in array|
|Filter()|names.filter("soumya")|To check wether it will pass the test or not|
|IndexOf()|names.indexOf("soumya")|To find index of element|
|Includes()|names.includes("soumya")|To check wheter element is present in array or not|
|Jion()|names.join("Delemiter(Example-->:,;,\,|,$,@,)")|To convert array to string|
|Slice()|names.slice("Can Pass element/Index of element")|To split an array|
|Splice()|names.pop("soumya")|To remove elemnts from array|
|IsArray()|Array.isArray("VariableName")|To check whether its array or not|


2.**Object**
Creation of object can be done by various type as shown below:
``` JAVASCRIPT
new object
object.create
var car = {}
````

 |Built in  Methods  | Syntax |Used For|
|------------------|---------|--------|
|Console.log|console.log(ObjectName.key Or ObjectName.key[reference]);|To read value from object|
|Key|var VariableName = Object.key(Name of Object);|How to calculate manys keys we have in object ?|
|freeze|ObjectName.freeze()|To stop changing values of object used freeze method to the object so that the new changes will not added to object.|
|assign|ObjectName.assign()|How to copy values of object to another ? used assign method for making copy of object|
|toString|ObjectName.toString() |How to convert object to string? toString() used to convert into string|


3.**String**

 |Built in  Methods  | Syntax |Used For|
|------------------|---------|--------|
|ToUpperCase|variableName.toUpperCase| convert the string into upper case|
|ToLowerCase|variableName.toLowerCase| convert the string into lower case|
|Split|variableName.split(Delimiters)| slipt the string using delimiter|
|Rplace|variableName.replace("Value want to replace","New value")| replaces a specified value with another value in a string|
|Trim|variableName.trim()| remove whitespace from both sides|
|SubString|variableName.substr()| extract the part from string and crreate new string|

## BUILT-IN-FUNCTION IN ES6
1.**SetTimeOut**
The code will run after some time.
``` JAVASCRIPT
const timefn= function(){
console.log("Printing after 2 seconds");
}
setTimeout(timefn,2000);
----------------------------
setTimeout(function(){
console.log("Printing after 2 seconds");
},2000);

```

2.**SetInterval**
It will execute in continous loop.To solve the problem of continuation of loop the new method is used named as clearInterval
``` JAVASCRIPT
setInterval(function(){
console.log("Printing after 2 seconds");
},2000);
```
----------------------
```
lwt counter = 0;
const timer = setInterval(function(){
console.log("Printing after 5 seconds");
if(counter > 5){
clearInterval(timer);
}
counter++;
},3000);
```
3.**ParseInt**
It converts anything into an integer number. It is very risky to never use it in mathematical operations.
``` JAVASCRIPT
const num = 10.18;

let intNum = parseInt(num);
console.log(intNum)
------------------------
Output:10
```
4.**ParseFloat**
It parses through the string and returns a float value. It is very risky, never use it in the mathematical operation.
``` JAVASCRIPT
const num = Sak9.2;

let intNum = parseInt(num);
console.log(intNum)
------------------------
Output:9.2
```
5.**JSON**
JSON is often used to send data over the network.
JSON format is same as object the only difference it used "" to write key  .Write using {"Key":"Value"}.
Example:
``` JAVASCRIPT
var person ={"firstName"="Radhika","firstName"="Radhika","age"=25};
```

###  BUILT-IN-FUNCTION IN ES6 SUMMARY TABLE

|Functions|Used For|Syntax|
|---------|--------|------|
|SetTimeOut|The code will run after some time.|setTimeout(param1,time)|
|SetInterval|It will execute in continous loop.|setInterval(param1,time)|
|ParseInt|It converts any thing into integer number.|parseInt(param)|
|ParseFloat|It parse through string and return float value.|parseFloat(param)|
|JSON|JSON is often used to send data overnetwork.|{"key":"Value"}|

# EXTRA SKILLS
 
## HTML
HTML stands for **HYPER TEXT MARKUP LANGUAGE**.It is used to give structure to the elements inside the webpage.
It tell where the elements of the page will be dislpay.The important elements of HTML are its _TAGS_.
```html
<tagname>CONTENT</tagname>
```
<img src ="images/Saved Pictures/html.png">

## CSS
CSS is used to style the webpage.It stands for **CASCADING STYLE SHEET**.
It is like an animation given to files.It is used to change font , color, size etc.
It is used to change the look of the element structed in the html file .Save with the (extension .css)
<img src ="images/Saved Pictures/css.png">

## SQL
SQL stands for **STRUCTURED QUERRY LANGUAGES**.
It is used to manipulate,store,retrive,delete the data.
<img src ="images/Saved Pictures/sql.png">




