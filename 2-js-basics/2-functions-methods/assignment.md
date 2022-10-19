# Fun with Functions

## Instructions

Create different functions, both functions that return something and functions that don't return anything.

See if you can create a function that has a mix of parameters and parameters with default values.

// creating a function that returns something

function displayUserNameMessage(name){
const userNameMessage = `Hello, ${name}`;
return userNameMessage;
};
const userName = displayUserNameMessage("Lisa");

console.log(userName);

// creating a function that doesn't return

function countItems (itemCount) {
console.log("Current count of items is ", itemCount)
}

## Rubric

| Criteria | Exemplary                                                                              | Adequate                                                         | Needs Improvement |
| -------- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------- |
|          | Solution is offered with two or more well-performing functions with diverse parameters | Working solution is offered with one function and few parameters | Solution has bugs |
