# JavaScript-Greeting-Problem-Data-Structures
Using JavaScript , I used and created a Greeting function that uses methods , arrays , loops and algorithms 

Greeting
CODING CHALLENGE
Create a function greeting(name) that accepts a string argument (a name, ex: "Oliver"), and returns a personalized greeting if a name is present.

The function takes a name as its only argument, and returns one of the following strings:


Given : 

- INPUT: greeting("Charlotte");
- OUTPUT: "Hello, Charlotte!";


- INPUT: greeting();
- OUTPUT: "Hello!";



function greeting(name){
	if(name){
		return "Hello, " + name + "!";
	} else {
		return "Hello!";
	}
}
