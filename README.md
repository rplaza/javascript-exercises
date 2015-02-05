# javascript-exercises
Some basic exercises for beginners from nodeschool.io

### Exercises

Each of these exercises has the solution in the file with the same name of the title i nthe folder 'solutions', e.g. Exercise One has a file solution with the name exerciseOne.js 

#### Exercise One

Create a javascript file. In that file declare a variable named example. Make the variable example equal to the value 'some string'.
Then use console.log() to print the example variable to the console.

#### Exercise Two

Create a javascript file. In that file create a variable named someString like this:

var someString = 'this is a string';

Use console.log to print the variable someString to the terminal.

#### Exercise Three

Create a javascript file. In that file, create a variable named example. Assign the string 'example string' to the variable example.
Use console.log to print the length of the string to the terminal.

#### Exercise Four

Create a javascript file. Define a variable named pizza that references this string: pizza is alright. Use the .replace() method to change alright to wonderful.
Use console.log() to print the results of the .replace() method to the terminal.

#### Exercise Five

Create a javascript file. In that file define a variable named example that references the integer 123456789.
Use console.log() to print that number to the terminal.

#### Exercise Five

Create a javascript file. In that file define a variable named roundUp that references the float 1.5. We will use the Math.round() method to round the number up.

An example of using Math.round():

Math.round(0.5);

Define a second variable named rounded that references the output of the Math.round() method, passing in the roundUp variable as the argument.
Use console.log() to print that number to the terminal.

#### Exercise Six

Create a javascript file. In that file define a variable named n that references the number 128; Call the .toString() method on the n variable.
Use console.log() to print the results of the .toString() method to the terminal.

#### Exercise Seven

Create a javascript file. In that file, declare a variable named fruit. Make the fruit variable reference the value orange with the type of String.
Then use console.log() to print "The fruit name has more than five characters." if the length of the value of fruit is greater than five.
Otherwise, print "The fruit name has five characters or less."

#### Exercise Eight

Create a javascript file. In that file define a variable named total and make it equal the number 0. Define a second variable named limit and make it equal the number 10.

Create a for loop with a variable i starting at 0 and increasing by 1 each time through the loop. The loop should run as long as i is less than limit. 

On each iteration of the loop, add the number i to the total variable. To do this, you can use this statement:

total += i;

After the for loop, use console.log() to print the total variable to the terminal.

#### Exercise Nine

Create a javascript file. In that file define a variable named pizzaToppings that references an array that contains three strings in this order: tomato sauce, cheese, pepperoni.
Use console.log() to print the pizzaToppings array to the terminal.

#### Exercise Ten

Create a javascript file. In that file, define a variable named numbers that references this array:

[1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

Like above, define a variable named filtered that references the result of numbers.filter(). The function that you pass to the .filter() method will look something like this:

function evenNumbers (number) {
  return number % 2 === 0;
}

Use console.log() to print the filtered array to the terminal.

#### Exercise Eleven

Create a javascript file. In that file, define a variable named pets that references this array:

['cat', 'dog', 'rat'];

Create a for loop that changes each string in the array so that they are plural. You will use a statement like this inside the for loop:

pets[i] = pets[i] + 's';

After the for loop, use console.log() to print the pets array to the terminal.

#### Exercise Twelve

Create a javascript file. In that file, define a variable named pizza like this:

var pizza = {
  toppings: ['cheese', 'sauce', 'pepperoni'],
  crust: 'deep dish',
  serves: 2
}

Use console.log() to print the pizza object to the terminal.

#### Exercise Thirteen

Create a javascript file. In that file, define a variable named food like this:

var food = {
  types: 'only pizza'
};

Use console.log() to print the types property of the food object to the terminal.

#### Exercise Fourteen

Create a javascript file. In that file, define a function named eat that takes an argument named food
that is expected to be a string. Inside the function return the food argument like this:

return food + ' tasted really good.';

Inside of the parentheses of console.log(), call the eat() function with the string bananas as the argument.

#### Exercise Fifteen 

Create a javascript file. In that file, define a function named math that takes three arguments. It's important for you to understand that arguments names are only used to reference them. 

Name each argument as you like. 

The function math should multiply the second and third arguments, then add the first argument to the outcome of the multiplication and return the value obtained.

After that, inside the parentheses of console.log(), call the math() function with the number 53 as first argument, the number 61 as second and the number 67 as third argument.


