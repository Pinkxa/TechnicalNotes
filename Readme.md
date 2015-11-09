# Pretty's Technical Notes

## Workshops

* [Functions & Objects](./workshops/functions_and_objects_slides.html)
* [Useful algorithms](./workshops/useful_algorithms.md)
* Useful algoritms using functions (lodash)
* How does a web application work?
* Others?
* How to create a method
* The better way of seeing the expected results

## Keep updated

To ensure your fork have the latest changes from this repository.

[Look at these instructions](https://help.github.com/articles/configuring-a-remote-for-a-fork/)

You need to create an upstream repository for your fork.

## Notes

Notes on things I learned & snippets of code that will make my life easier

### How to print a string to the console

```javascript
// how do I print to the console again?
console.log("Hello World!");
```

### How to write if/else statement

```javascript
//how do I write if/else statement
if(condition){
      return something;
} else {
      return another thing;
}
```

### How to test with mocha
In my project folder I create a test folder and create a test.js file inside the test folder.

Here is an example of test:

```javascript
//how do I write a test using mocha
var assert = require("assert");

describe("In the ferry kata", function(){
	it("I should be able to create a car", function(){
	      //Assemble
      	//Act
	      //Assert
	   assert.equal("car", "car");
	});
});
```
Then to the terminal you get into the project folder that contains your test folder, test file and a function and you run mocha, this test will pass.

Here is another example of a failing test:

```javascript
//a mocha failing test
var assert = require("assert");

      describe("In the ferry kata", function(){
      it(" I should be able to create cars", function(){
            //Assemble
            //Act
            //Assert
         assert.equal("car", "cars");
      });
});
```
When you run this test the same way as the first one, it will fail.

### A note about something else
add more here...

### If things get to long...

* [Todo something useful](notes/my_file.md) A short description here
* [Create a basic Express app](notes/my_file.md) How to get going with express
* [pretty's link](pretty.md) Pretty's staff to know
