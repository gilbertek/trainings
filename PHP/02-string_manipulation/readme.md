## String Manipulation - Language Syntax
Strings and variables are at the heart of the language.

#### Printing String
Echo and Print are language constructs that display strings.
We have already seem echo statements. print does the same thing.

#### Difference between Print and Echo Statements

#### Print :
It has a return type 1.
It is a function
It takes in only single parameter, separated by a colon.

```
print ( string $arg )

print "I love PHP!";
```

#### Echo
Is faster
It has return type void.
It takes in multiple parameters.

e.g. :
echo "Hello,","my "," name is ", "Mike";


#### String Manipulation
Concatenation is the operation of joining two character strings/variables together.
In PHP we use . (dot) to join two strings.

```
echo "Hello "."there!";
echo "My"." "."name"."is"." "."George";
```

Single quotes will not interpret the value of variables enclosed within them
It display what is in the quotes 'as-is'

Double quotes however does interpretation and output the result in the generated string

#### Exercise One
Create three variables with values and output their content using string concatenation.

