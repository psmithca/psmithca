---
permalink: /basics/sequence-selection-repetition/
title: "Sequence, Selection and Repetition"
sidebar:
  title: "Project Build"
  nav: "side"
share: true
---
Placeholder

```php
<?php
// Variables
$name = 'My Name';
$value = 12;

// Statements
echo $name . PHP_EOL; //PHP_EOL is a special variable, used for spacing
echo $value . PHP_EOL;

// Selection

if ($name == 'My Name') {
    echo $name . PHP_EOL;
} else {
    echo $value . PHP_EOL;
}

// Accumulators
// Some languages have what we call accumulators,  basically
$x = 0;
$x++;
echo $x . PHP_EOL;
// is the same as
$x = $x + 1;
echo $x . PHP_EOL;
/* Essentially it means take the value of $x,
add one to it, and put the new value back in $x
*/

/*Repetition
We call these loops.  There are multiple kinds
This is a simple one we call a FOR loop.
The code will initialize $y to a value of 0
Next it will check to see if the value of $y is less than 10
if so it will enter the loop, and when complete.
So once $y hits 10, the loop will stop because its no longer less than 10.
*/
for ($y = 0; $y < 10; $y++) {
    echo $y . PHP_EOL;
}
echo 'Value After Loop' . PHP_EOL;
echo $y . PHP_EOL;
?>
```