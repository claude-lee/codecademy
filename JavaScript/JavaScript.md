confirm("I will get a reply today");

prompt("Where are you from?")
console.log("Xiao Hui".length < 122);
console.log("Goody Donaldson".length > 8);
console.log(8*2 === 16);

if ("name".length > 3 ) {
    console.log("then the globe is round");
}


if ("my name is".length === "Earl" ) 
{
    console.log("Let's go down the first road!");
}
else 
{
    // What should we do if the condition is false? Fill in here:
    console.log("Well then you better hurry up!")
}

1. Confirm and prompt

We can make pop-up boxes appear! 
confirm("I am ok");
prompt("Are you ok?");

2. Data types

a. numbers (e.g. 4.3, 134)

b. strings (e.g. "dogs go woof!", "JavaScript expert")

c. booleans (e.g. false, 5 > 4)

3. Conditionals

If the first condition is met, execute the first code block. If it is not met, execute the code in the else block. See the code on the right for another example.

console.log(14%3)
console.log(99%8)
console.log(11%3)

"wonderful day".substring(3,7)

console.log("Hamburgers".substring(3,10)) -> burgers
var myAge = 31; 
console.log(myAge);

// Declare a variable on line 3 called
// myCountry and give it a string value.
var myCountry = "Sweden"

// Use console.log to print out the length of the variable myCountry.
console.log( myCountry.length);

// Use console.log to print out the first three letters of myCountry.
console.log( myCountry.substring(0,3));

// On line 2, declare a variable myName and give it your name.
var myName = "Claudia"
// On line 4, use console.log to print out the myName variable.
console.log(myName)
// On line 7, change the value of myName to be just the first 2 
// letters of your name.
myName = myName.substring(0,2)
// On line 9, use console.log to print out the myName variable.
console.log(myName)
// Check if the user is ready to play!
confirm("Are you reday to play?")
var age = prompt("What's your age");
if(age < 13)
{
    console.log("Ok, listen. You can play, but i won't take any responsibility.")
}
else
{
    console.log("Awesome! Go ahead and have fun!")
}

// Below is the greeting function!
// See line 7
// We can join strings together using the plus sign (+)
// See the hint for more details about how this works.

var greeting = function (name) {
    console.log("Great to see you," + " " + name);
};

// On line 11, call the greeting function!
greeting("StartUp");
