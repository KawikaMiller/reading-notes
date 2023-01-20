# Reading - Class10

These notes will cover debugging and how to interpret error messages.

## Troubleshooting

1. **Name some key differences between a Syntax Error and a Logic Error.** A syntax error is a spelling error or sometimes a missing semi-colon that prevents the code from executing. A logic error is an error where the code still runs but not in the way you intend it to, typically these yield incorrect results or sometimes no results at all. 


2. **List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.** I cant remember the exact kind of error message I got but I know they have mostly been because I either misspelled something or was using the incorrect variable or wrong data type. For example, in Lab09 I was trying to use a loop inside of a loop and I used `i` as my iterator for the outer loop and `j` as the iterator for the inner loop. I kept getting some kind of error that made no sense because it was saying that something was undefined on a certain line, and after staring my code for what felt like eternity and trying all kinds of `console.log`s to check values I realized that I was using `i < arr.length` for my inner loop when I should have been using `j < arr.length`.

3. **How will this topic continue to influence your long term goals?** Errors and error messages are inevitable and getting better at understanding them and what they mean will only make me a stronger developer. 

## The Debugger

1. **How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development? The debugger is like being able to get results from a doctor visit/checkup, but instantaneously. When you're feeling sick, unwell, etc. you can go to the doctor and they can run tests which give you a more detailed look into what's going on with your body. Is your cholesterol too high? Is your blood pressure too low? Do you have some kind of infection? Without going to the doctor it's difficult for us to know for certain what's happening behind the scenes but when we get those test results back then we know exactly whats going on in our bodies. From there, the doctor can prescribe us medicine or a remedy for our problems. The debugger tool is similar in that it returns instant results about what's going on inside a webpage / application and from there we can troubleshoot the condition and try to find a remedy for it.

2. **Define what a breakpoint is** We can use a breakpoint to define a specific place in our code where we want to stop the execution so that we can check values of certain variables and properties to identify any possible problems occuring within the code.

3. **What is a call stack?** A call stack is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions - what function is currently being run and what functions are called from within that function, etc. [source](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)

## Things I Want to Know
- Is there something similar to the CSS diner exercise that we can use to practice debugging and interpreting the debugger / error messages?