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

`if` statements check to see `if` a condition is true. If the condition is true, a certain action will be taken. If it is false, the code will move forward. The below code would return `Hello` because 43 is greater than 36

```
if 43 > 36
  return("Hello")
end
```

After an `if` statement, an `elsif` or `else` can be used to carry on the conditional.

An `elsif` checks another condition only if the original `if` statement was false. Below, Goodbye is returned rather than Hello because 78 is greater than 62 but 36 is not more than 43.

```
if 36 > 43
  return("Hello")
elsif 78 > 62
  return("Goodbye")
end
```

`else` statements are conditions that are only used when all other conditions in an `if` statement were false.

The below branch returns Wait, come back! because both other conditions are false.

```
if 36 > 43
  return("Hello")
elsif 62 > 78
  return("Goodbye")
else
  return("Wait, come back!")
end
```

### While statements

`while` statements are similar to if statements in the idea that the code inside will only occur if the condition is true. The difference between the two is as long as the condition is true in a `while` statement, the code will continue repeating until the condition is false.

In the below `while` statement, the code will continue running until x has a value of 3, meaning the code will run 4 times.

```
x = 6

while x > 3
  x = x - 1
end
```


## Methods

Methods are used to implement a certain function a code is made to do multiple times, with different variables. This means that when a function is created, it can be used multiple times in a code, or can be used with different variable for a different result. This is effective because the code will not need to be rewritten and it is easy to change variables without having to make many edits.

Each method begins with a `def` and ends with a `end`. Next to `def` is the function name, and next to the name, in parentheses, are where variables to be used in the method are named.

Methods are then called later with the method name, and in the parentheses, rather than the variable name, are the values to be given to the variables.

In the method below, see if you can what value would be returned for each time the method is called.

```
def numerify(x)
  x = x + 3
  x = x * 4
  x = x - 7
  x = x - 2
  return(x)
end

numerify(17)

numerify(4)
```

If you got 71 and 19 you're doing something right.
