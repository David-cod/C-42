**Object Oriented Programming Concepts**
_class_-a blueprint of objects,contains properties(written inside the constructor) and functions of the object.
_objects_-Objects are an instance of the class. Any real world entity can be an object. Every object has properties and functions.
_Abstraction_-Hiding of data from the main program.
_Inheritance_-Concept of deriving subclasses(child class) from the super class/baseclass/parent class. The keyword "extends" is used for deriving the subclass. The keyword "super" is used for derving the properties from the baseclass constructor to the subclass constructor.
**Array**
_array_-An array is used to store multiple datatypes in one variable. Arrays are represented using square brackets. To access elements inside an array, you use index. Array is zero index based. The length of an array is the total number of elements inside the array.
_push operation_-You can use push operation to add an element as the last element of an array.
_pop operation_-Used to delete the last element of an array.
**datatypes**
_numbers_-Integers don't have decimals, and can be negative, positive, or 0. Float numbers are decimal numbers. A long float means that there are 8 digits after hte decimal point.
_string_-Represented with double quotes. Anything can be written inside.
_Boolean_-Can have only two inputs, true or false.
_undefined_-Unknown datatype. For example: var xyz;
_null_-Nothing.
**Loops**
_for loop_-Used to do an action over and over again. 
syntax: 
for(initialization expression;conditional expression; incremental expression){
    //action to be performed
}
_while loop_- Until the condition is met, the loop will keep on performing.
syntax:
var i=0;
while(condition){
    //action to be performed.
}
**API and JSON**
_API_-application programming interface. It is a messenger that connects the client with the server.
_JSON_-Javascript Object Notation. It is a data structure that is used convert the information from the server into a readable text format.
**Conditional programming**
_if condition_-
syntax:
if(condition){
    //action to be performed.
}
_if else condition_-
syntax:
if(condition){
    //action to be performed.
}else if(condition){
    //action to be performed if first condition is false.
}else{
    //action to be performed if both conditions above are false.
}
_switch condition_-an alternative solution to multiple if else conditions.
syntax:
var rand;
switch(variable){
    case1:action to be performed;
    break;
    case2:action to be performed;
    break;
    default:break;
}
**Arithmetic Operaters**
_concatination_-Used for joining a string and a number/string/variable.
_modulus operator_-Denoted as %. The remainder of division. 
**logical operators**
_And operator_-denoted as &&. For combining multiple conditions.Will give output only if all conditions are true
_or operator_-denoted as || For combining multiple conditions.Will give output only if either of the conditions are true

**functions**
_tint()_-for making an object transparent with respect to the background
syntax: 
tint(255,[alpha])
_frameCount()_-for calculating how many frames a sprite has gone through.
syntax:
frameCount(value)
_stroke()_-to add a border color
**ASCII**
_ASCII_-American standard code for information Interchange.Every key on the keyboard have a code. For example "space"=32;
