<hr/>

_#1_

Programming languages: Programming languages are used to give computers instructions. A program is a set of instructions that a computer can follow to perform a task. Programs are written using a specific programming language, such as Java or Python.

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// This is a TypeScript program that prints "Hello, world!" to the console.

console.log("Hello, world!");
```

#### Java Example

```java
// This is a Java program that prints "Hello, world!" to the console.

public class Main {
public static void main(String[] args) {
System.out.println("Hello, world!");
}
}
```

</p>
</details>

<hr/>

_#2_

Variables and statements: A variable is like a container that can hold a value. Variables have a name and a type. A statement is a single instruction in a program. Statements are often used to perform actions, such as printing text to the screen or performing calculations.

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// Declare a variable called "message" and assign it a string value.
let message: string = "Hello, world!";

// Print the value of the "message" variable to the console.
console.log(message);
```

#### Java Example

```java
// Declare a variable called "message" and assign it a string value.
String message = "Hello, world!";

// Print the value of the "message" variable to the console.
System.out.println(message);
```

</p>
</details>

<hr/>

_#3_

Control structures: Control structures are used to control the flow of a program. There are several types of control structures, such as "if" statements, "for" loops, and "while" loops. Control structures allow a program to make decisions and repeat tasks.

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// Declare a variable called "x" and assign it a value of 10.
let x: number = 10;

// Use an if statement to check if "x" is greater than 5.
if (x > 5) {
  // If "x" is greater than 5, print "x is larger than 5" to the console.
  console.log("x is larger than 5");
}
```

#### Java Example

```java
// Declare a variable called "x" and assign it a value of 10.
int x = 10;

// Use an if statement to check if "x" is greater than 5.
if (x > 5) {
// If "x" is greater than 5, print "x is larger than 5" to the console.
System.out.println("x is larger than 5");
}
```

</p>
</details>

<hr/>

_#4_

Functions: A function is a group of statements that performs a specific task. Functions can accept input in the form of "arguments" and return output in the form of a "return value". Functions allow programs to be organized into reusable pieces.

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// Declare a function called "add" that takes two numbers as arguments and returns their sum.
function add(a: number, b: number): number {
  return a + b;
}

// Call the "add" function with arguments 3 and 4, and store the result in a variable called "sum".
let sum: number = add(3, 4);

// Print the value of "sum" to the console.
console.log(sum); // Output: 7
```

#### Java Example

```java
// Declare a function called "add" that takes two numbers as arguments and returns their sum.
public static int add(int a, int b) {
return a + b;
}

// Call the "add" function with arguments 3 and 4, and store the result in a variable called "sum".
int sum = add(3, 4);

// Print the value of "sum" to the console.
System.out.println(sum); // Output: 7
```

</p>
</details>

<hr/>

_#5_

Algorithms and data structures: An algorithm is a set of steps for solving a specific problem. A data structure is a way of organizing and storing data in a computer. Different algorithms and data structures are suitable for different types of problems.

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// Declare an array called "numbers" that contains a list of integers.
let numbers: number[] = [1, 2, 3, 4, 5];

// Use the Array.sort() method to sort the "numbers" array in ascending order.
// This is an example of using an algorithm to solve a problem (sorting the array).
numbers.sort((a, b) => a - b);

// Print the sorted "numbers" array to the console.
console.log(numbers); // Output: [1, 2, 3, 4, 5]
```

#### Java Example

```java
// Declare an array called "numbers" that contains a list of integers.
int[] numbers = {1, 2, 3, 4, 5};

// Use the Arrays.sort() method to sort the "numbers" array in ascending order.
// This is an example of using an algorithm to solve a problem (sorting the array).
Arrays.sort(numbers);

// Print the sorted "numbers" array to the console.
System.out.println(Arrays.toString(numbers)); // Output: [1, 2, 3, 4, 5]
```

</details>

<hr/>

_#6_

Types: In programming, a type refers to the kind of data that a variable or expression can represent. Some common types include numbers, strings, and booleans. Programming languages can have both primitive types (e.g. integers, floats) and composite types (e.g. objects, arrays).

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// Declare a variable called "name" and assign it a string value.
let name: string = "Alice";

// Declare a variable called "age" and assign it a number value.
let age: number = 30;

// Declare a variable called "isAdmin" and assign it a boolean value.
let isAdmin: boolean = true;
```

#### Java Example

```java
// Declare a variable called "name" and assign it a string value.
String name = "Alice";

// Declare a variable called "age" and assign it a number value.
int age = 30;

// Declare a variable called "isAdmin" and assign it a boolean value.
boolean isAdmin = true;
```

</p>
</details>

<hr/>

_#7_

Type safety: Type safety refers to the idea that variables and expressions in a progam ould only be allowed to hold and operate on values of the correct type. Type safety helps prevent errors and makes programs more predictable. Some programming languages are statically-typed (type checked at compile-time), while others are dynamically-typed (type checked at runtime).

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// This code will not compile because "message" is expected to be a string, but a number is assigned to it.
let message: string = 123; // Type '123' is not assignable to type 'string'.
```

#### Java Example

```java
// This code will not compile because "message" is expected to be a string, but an integer is assigned to it.
String message = 123;  // Incompatible types. Required: java.lang.String, found: int
```

</p>
</details>

<hr/>

_#8_

Naming conventions: Naming conventions are rules for choosing names for variables, functions, and other program elements. Different programming languages and communities may have different naming conventions.

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// Variable names in TypeScript are typically written in camelCase.
let userName: string = "Alice";

// Class names in TypeScript are typically written in PascalCase.
class UserProfile {
  // ...
}
```

#### Java Example

```java
// Variable names in Java are typically written in camelCase.
String userName = "Alice";

// Class names in Java are typically written in PascalCase.
public class UserProfile {
// ...
}
```

</p>
</details>

<hr/>

_#9_

Syntax: Syntax refers to the set of rules that govern the structure of a program written in a particular language. Examples of syntax include the way that statements are terminated, the way that function calls are formatted, and the way that code blocks are denoted.

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// TypeScript uses semicolons to terminate statements.
console.log("Hello, world!");

// TypeScript uses parentheses to enclose the arguments of a function call.
console.log(1 + 2);

// TypeScript uses curly braces to denote the beginning and end of a code block.
if (x > 0) {
  console.log("x is positive");
}
```

#### Java Example

```java
// Java uses semicolons to terminate statements.
System.out.println("Hello, world!");

// Java uses parentheses to enclose the arguments of a method call.
System.out.println(1 + 2);

// Java uses curly braces to denote the beginning and end of a code block.
if (x > 0) {
System.out.println("x is positive");
}
```

</p>
</details>

<hr/>

_#10_

Operators are special symbols in programming languages that perform specific operations on one or more values. Some common operators include arithmetic operators (e.g. +, -, *, /), comparison operators (e.g. >, <, ==, !=), and logical operators (e.g. &&, ||, !). The type of operator used and the number of values it operates on depends on the specific programming language and context in which it is used.

<details open><summary>Examples</summary>
<p>

#### Typescript Example

```typescript
// Declare two variables "x" and "y" and assign them values of 10 and 5, respectively.
let x: number = 10;
let y: number = 5;

// Use the "+" operator to add the values of "x" and "y" and store the result in a variable called "sum".
let sum: number = x + y;

// Use the ">" operator to compare the values of "x" and "y" and store the result in a variable called "isGreater".
let isGreater: boolean = x > y;

// Use the "&&" operator to check if both "x" is greater than 5 and "y" is less than 10.
let isValid: boolean = (x > 5) && (y < 10);
```

#### Java Example

```java
// Declare two variables "x" and "y" and assign them values of 10 and 5, respectively.
int x = 10;
int y = 5;

// Use the "+" operator to add the values of "x" and "y" and store the result in a variable called "sum".
int sum = x + y;

// Use the ">" operator to compare the values of "x" and "y" and store the result in a variable called "isGreater".
boolean isGreater = x > y;

// Use the "&&" operator to check if both "x" is greater than 5 and "y" is less than 10.
boolean isValid = (x > 5) && (y < 10);

```

</details>

<hr/>
