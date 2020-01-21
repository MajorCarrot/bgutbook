# Day 3 - Showing the content of a file

## Solutions to exercises

{#solution_3_01}
#### Exercise 3.01
Print the content of the file `examples.txt` numbering lines.

#### Solution
According to the man page of `cat` the `-n` option numbers all output lines. So

``` sh
$ cat -n examples.txt
     1  dog
     2  cat
     3  elephant
     4  ostrich
     5  Dug the Dog
[...]
```

gives the desired result.

[Go back to the exercise](#exercise_3_01)

* * *

{#solution_3_02}
#### Exercise 3.02
Check if the file `examples.txt` contains spaces at the end of any line.

#### Solution
According to the man page of `cat` the `-E` option displays `$` at the end of each line. So

``` sh
$ cat -E examples.txt
dog$
cat$
elephant$
ostrich$
Dug the Dog$
[...]
```

shows you that each line terminates with a `$` immediately after the text, so there are no nasty "invisible" spaces. Later in the book we will learn how to check this without having to manually look at each line.

[Go back to the exercise](#exercise_3_02)

* * *

