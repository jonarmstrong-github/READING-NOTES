# CODE FELLOWS - CODE 301

## DAY 04 CLASS 04

### [HOME](../README.md)

## AGENDA
1. React and Forms
1. Filtering state based on form inputs, events

## READING
### React Forms
1. What is a ‘Controlled Component’?
    * An input form element whose value is controlled by React.

1. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

1. How do we target what the user is entering if we have an event handler on an input field?

### JavaScript — The Conditional (Ternary) Operator Explained
1. Why would we use a ternary operator?
    * The code is shorter and easier to write.
    
1. Rewrite the following statement using a ternary statement:

    ORIGINAL
    ```js
    if(x===y){
    console.log(true);
    } else {
      console.log(false);
    }
    ```
    RE-WRITTEN
    ```js
    let example = (x === y) ? 'true' : 'false';
    console.log(example);
    ```

## ADDITIONAL RESOURCES

## READING NOTES
### Controlled Components
In HTML, form elements such as ```<input>```, ```<textarea>```, and ```<select>``` typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with ```setState()```.

With a controlled component, the input’s value is always driven by the React state.

### The Conditional (Ternary) Operator
DETERMINING AGE FROM THIS OBJECT

```js
let person = {
  name: 'tony',
  age: 20,
  driver: null
};
```
```js
if ( condition ) {
  value if true;
} else {
  value if false;
}
```

AN IF STATEMENT

```js
if (person.age >= 16) {
  person.driver = 'Yes';
} else {
  person.driver = 'No';
}
```
CONDITIONAL TERNARY OPERATOR

```js
person.driver = person.age >=16 ? 'Yes' : 'No';
```

```js
condition ? value if true : value if false
```

ANOTHER EXAMPLE
```js
let isStudent = false;
let isSenior = true;
let price = isStudent ? 8 : isSenior ? 6 : 10
console.log(price);
// 6
```

## CLASS NOTES
### SORT
By default, the sort() method sorts the array elements in ascending order with the smallest value first and largest value last.

The sort() method casts elements to strings and compares the strings to determine the orders.

### USE SORT FOR STRINGS
[https://www.w3schools.com/jsref/jsref_sort.asp](https://www.w3schools.com/jsref/jsref_sort.asp)

Sorting alphabetically works well for strings ("Apple" comes before "Banana").

But, sorting numbers can produce incorrect results.

"25" is bigger than "100", because "2" is bigger than "1".

You can fix this by providing a "compare function" (See examples below).

### USE COMPARE FOR NUMBERS
[https://www.w3schools.com/jsref/jsref_sort.asp](https://www.w3schools.com/jsref/jsref_sort.asp)
A function that defines a sort order. The function should return a negative, zero, or positive value, depending on the arguments:
function(a, b){return a-b}
When sort() compares two values, it sends the values to the compare function, and sorts the values according to the returned (negative, zero, positive) value.

Example:

The sort function will sort 40 as a value lower than 100.

When comparing 40 and 100, sort() calls the function(40,100).

The function calculates 40-100, and returns -60 (a negative value).

## LINKS
### [Class 04 GitHub](https://github.com/codefellows/seattle-code-301d85/tree/main/class-04)
### [React Docs - Forms](https://reactjs.org/docs/forms.html)
### [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
### [React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
### [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

### [https://www.javascripttutorial.net/javascript-array-sort/](https://www.javascripttutorial.net/javascript-array-sort/)
### [https://en.wikipedia.org/wiki/List_of_Unicode_characters](https://en.wikipedia.org/wiki/List_of_Unicode_characters)

## VOCABULARY

## THINGS I WANT TO KNOW MORE ABOUT

## LEARNING THAT OCCURRED AND PROBLEMS THAT ARE SOLVED

## PROBLEMS THAT HAVE TIMED OUT BEFORE RESOLUTION

### [HOME](../README.md)