# exsercise5

Let's go through the code step-by-step:

1. `let famous_person: string = "Quid e Azam";`
   - This line declares a variable named `famous_person` and assigns the value "Quid e Azam" to it.
   - The `: string` part indicates that the variable is expected to hold a value of the string data type.

2. `let message: string = famous_person + ' once said, “Expect the best, prepare for the worst.”';`
   - This line declares another variable named `message`.
   - The value of `message` is created by concatenating the `famous_person` variable (which holds "Quid e Azam") with the string ' once said, “Expect the best, prepare for the worst.”'.
   - The `+` operator is used to concatenate the two strings.

3. `console.log(message);`
   - This line outputs the value of the `message` variable to the console.
   - The `console.log()` function is a built-in function in JavaScript that allows you to print messages or values to the console, making them visible to the developer during program execution.

In summary, this code declares two variables, `famous_person` and `message`, and then it creates a message by combining the value of `famous_person` with a fixed string. Finally, it prints the resulting message to the console, which will display the following output:

```
Quid e Azam once said, “Expect the best, prepare for the worst.”
```
