# minimal php quine

https://en.wikipedia.org/wiki/Quine_(computing)

# "empty" quine

you have to create it yourself:

    > quine0_make.php
    php quine0_make.php > quine0.php
    php quine0.php > test0.txt
    diff -q quine0.php test0.txt

# run

Executing \ testing the quines:

    php quineX.php
    cat quineX.php
  
or 

    php quineX.php > testX.txt
    diff -q quineX.php testX.php


Creating / generating the quines:

    php quineX_make.php > quineX.php
