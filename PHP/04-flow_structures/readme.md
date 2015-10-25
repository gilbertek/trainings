## Flow Structures - Language Syntax
Control Structures are noting but Control flows
i.e. "order of flow of individual statements based of certain Conditions".

#### If/Else
If statement is a conditional statement that decides the flow of statements.
If is one of the important statements in programming languages.
The syntax of PHP if conditional statement is just like any other programming language.
```
  if (<something is true>)
  {
    do_something();
  } else
  {
    do_something_else();
  }
```

When we want to repeat some set of statements we use loop statements.
We may want to repeat the statement-block for certain number of times until a particular condition is met.

In PHP we have three kinds of looping statements available,
1. for loop statement.
2. while loop statement.
3. do-while loop statement.

#### For
for (expression1 ; expression2 ; expression3) {
  statement or block of statements
}

#### While
```
<?php

$number = 1;
while ($number++)
{
    if ($number == 2)
    {
        continue;
    }
    if ($number == 6)
    {
        break;
    }
    echo $number . "<br>";
}

?>
```

```
while(<some condition is true>)
{
  do_something();
}

- for(<starting value>; <ending value>; <increment>)
{
  do_something();
}

- foreach(<element> in <list of elements>)
{
  do_something();
}

for ($i = 0; $i < 100; $i++)
{
  if ($i == 42)
  {
    break;
  }
}

$counter = 0;

while( $counter < 10 )
{
  echo "I am running mile#:$counter";
  $counter++
}

$numbers = array(1, 2, 3, 4, 5);

foreach($number as $number) {
  echo "Here is integer value $number";
}
```

#### Switch
When we have multiple if-else statements (if-else) with conditions on the same variable,
we can replace it with Switch Statement
  switch(<value>)
  {
    case <some value>:
      dothis();
    default:
      echo 'you get the default';
  }

#### Exercise One
Continue from the last exercise, use if/else or switch in the exercise below.

if $result = 21 print you're a genius;
else print 'Are you sure this is what you want?'

#### Exercise two
Create a for loop statement that print values from 10 to 0

#### Exercise three
Create a while loop that print the square root (n*n) of a number n.
