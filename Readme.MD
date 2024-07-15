// Activity 1: Variable Declaration

// 1. Declare a variable using var, assign it a number, and log the value to the console.
var a = 1;
console.log(a);

// 2. Declare a variable using let, assign it a string, and log the value to the console.
let str = "akshay";
console.log(str);

// Activity 2: Constant Declaration

// 3. Declare a variable using const, assign it a boolean value, and log the value to the console.
const signIn = true;
console.log(signIn);

// Activity 3: Data Types

// 4. Create variables of different data types (number, string, boolean, object, array) and log each variable's type using the typeof operator.
const num = 10;
const str1 = "akshay more";
const isLogout = false;
const data = {
    name: "akshay more",
    rollono: 7,
};
const fruits = ["apple", "mango", "grapes", "banana"];

console.log(typeof num);      // number
console.log(typeof str1);     // string
console.log(typeof isLogout); // boolean
console.log(typeof data);     // object
console.log(typeof fruits);   // object

// Activity 4: Reassigning Variables

// 5. Declare a variable using let, assign it an initial value, reassign a new value, and log both values to the console.
let initialValue = "hello tu kasie ho";
console.log(initialValue);
initialValue = "hello tu kasie ho";
console.log(initialValue);

// Activity 5: Understanding const

// 6. Try reassigning a variable declared with const and observe the error.
const initialUsingConst = "hello professor";
initialUsingConst = "hello kaha ja rahe ho !!"; // This will cause an error
console.log(initialUsingConst);  // Uncaught TypeError: Assignment to constant variable.
