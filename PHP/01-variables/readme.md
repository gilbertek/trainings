## Variables - Language Syntax

Variables are at the heart of the language.
Variable are a named storage location in memory
It stores a value for later use.

e.g. $name, $age , $message

PHP as a dynamic language and offers:
1) Type inference
2) variable must begin with '$'
3) variables are case sensitive

#### Our first program

1) Create a folder "training"
2) Create a file named "index.php"

```
<?php
  echo "Hello world!";
<?
```

#### Exercise One
Create a webpage that contains PHP code that displays: "Hello <your name>"

We can assign value to a PHP variable using assignment operator(=).

```
<?php

  $integer_value = 42
  $string_value = "The meaning of life"
  $double_value = 3.14

  echo $integer_value
```

#### Exercise Two
Store your name in a variable and use it to replace your name in the previous exercise.


#### Whitespace and comments
PHP ignore whitespaces so use to make your code readable

// single line comment

/*
  Block of comments
 */
