# 211-Blogs


Class 2 -

What are your favorite features of HTML5, and how have you implemented them in your front-end development projects?

- I think DIV is the most important feature of HTML5, I used in almost every project that I have used HTML5

What is the ternary operator?

- A ternary operator evaluates a condition and executes a block of code based on the condition.

-----------------------------------------------------------------------------------------------------------------------

class 4 

Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?

- Form most languages, global variables are considered a “bad thing”. JS is no different, but it probably has more severe consequences than most languages.

Explain function hoisting in JavaScript.

- JavaScript Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables or classes to the top of their scope, prior to execution of the code.
Hoisting allows functions to be safely used in code before they are declared.

-----------------------------------------------------------------------------------------------------------------------

Class 6 

What's the difference between an "attribute" and a "property"?

- Attribute is a quality or object that we attribute to someone or something. For example, the scepter is an attribute of power and statehood.
- Property is a quality that exists without any attribution. For example, clay has adhesive qualities; i.e, a property of clay is its adhesive quality.

What is the difference between call stack and task queue?


- CallStack is a data structure which keeps track of function calls in our program. When ever we call a function for its execution, we are pushing it to the stack. It is popped out of the stack when the execution is completed.

- Task Queue (Micro task Queue) is a JavaScript runtime messaging queue which handles task that is allocated by different Web Apis. This queue is dedicated to handle the Web Apis callbacks. The message are processed once the call stack is clear.

-----------------------------------------------------------------------------------------------------------------------

Class 8

Describe event bubbling.

- Event bubbling is a method of event propagation in the HTML DOM API when an event is in an element inside another element, and both elements have registered a handle  to that event. It is a process that starts with the element that triggered the event and then bubbles up to the containing elements in the hierarchy
wasabi peas

What Is an associative array in JavaScript?

- Associative arrays are basically objects in JavaScript where indexes are replaced by user-defined keys. They do not have a length property like a normal array and cannot be traversed using a normal for loop.


-----------------------------------------------------------------------------------------------------------------------
Class 10 

Can you give an example for destructuring an object or an array?


-let introduction = ["Hello", "I" , "am", "Sarah"];
- let greeting = introduction[0];
- let name = introduction[3];

- console.log(greeting);//"Hello"
- console.log(name);//"Sarah"
 
 What advantage is there for using the arrow syntax for a method in a constructor?
 
 - Arrow syntax binds this to the surrounding code which makes the code simpler and shorter.

-----------------------------------------------------------------------------------------------------------------------

Class 12 

How can you achieve immutability in your own code?

- Mutable objects are those whose state is allowed to change over time. An immutable value is the exact opposite — after it has been created, it can never change. Strings and Numbers are inherently immutable in javascript.

Tell us about something you learned this week.

- we learned how to access API and get data from it.

-----------------------------------------------------------------------------------------------------------------------

Class 14

Write about something you learned this week.

- We learned how to fetch a API and use in a application that I build with a partner

What are the three laws of algorithm recursion?

- A recursive algorithm must call itself, recursively.
  A recursive algorithm must have a base case.
  A recursive algorithm must change its state and move toward the base case.

 -----------------------------------------------------------------------------------------------------------------------
 Class 16

Describe event bubbling.

- Event bubbling is a method of event propagation in the HTML DOM API when an event is in an element inside another element, and both elements have registered a handle to that event. It is a process that starts with the element that triggered the event and then bubbles up to the containing elements in the hierarchy. In event bubbling, the event is first captured and handled by the innermost element and then propagated to outer elements.


Describe the call stack.


- The call stack is used by JavaScript to keep track of multiple function calls. It is like a real stack in data structures where data can be pushed and popped and   follows the Last In First Out (LIFO) principle. We use call stack for memorizing which function is running right now. The below example demonstrates the call stack.


 
