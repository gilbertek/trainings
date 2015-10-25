## Files & Forms
File handling is an important part of any web application.
You often need to open and process a file for different tasks.

The readfile() function reads a file and writes it to the output buffer.

```
<?php
echo readfile("test.txt");
```

A better method to open files is with the fopen() function.
This function gives you more options than the readfile() function.

```
<?php
$myfile = "testFile.txt";
$handle = fopen("file.txt", "r") or die("Unable to open file!");
?>
```

An associative array of items uploaded to the current script via the HTTP POST method ($_FILES)

#### Forms
PHP is one of the most popular means of processing HTML forms.

```
<html>
<body>

<form action="test.php" method="post">
Name: <input type="text" name="name"><br>
E-mail: <input type="text" name="email"><br>
<input type="submit">
</form>

</body>
</html>
```

```
if ($_SERVER["REQUEST_METHOD"] == "POST") {
  $name = $_POST["name"];
```
