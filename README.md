# beginner-ruby

## Variables

In order to assign a variable a value, use an equal sign between the variable name and its value

```
length = 20
```

To use variables, you can have the variable value be shown within a text, using a pound sign and a curly bracket.

```
puts "The length is #{length}"
```

The above code shows the text "The length is 20"

Variables can also be used as numbers. You can use mathematical functions to react variables with other variables or variables with numbers.

```
area = length * width
```

The above code would set the area variable equal to the length multiplied by the width.

There are multiple values a variable could have. A variable could have a numerical value, as shown above. Also, a variable could be set equal to a string, meaning that the variable has a message as a value. Below is an example of a variable with a string as its value.

```
message = I could go for a sandwich right about now.
```

## Conditionals

There are two types of conditionals.

#### If Statements

If statements check to see if a condition is true. If the condition is true, a certain action will be taken. If it is false, the code will move forward. The below code would return `Hello` because 43 is greater than 36

```
if 43 > 36
  return("Hello")
end
```

After an if statement, an `elsif` or `else` can be used to carry on the conditional.

An `elsif` checks another condition only if the original if statement was false.


conditionals
  Expressions
  Branching

Methods
