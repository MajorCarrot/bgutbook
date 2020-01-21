# Day 3 - Showing the content of a file

{blurb, icon: quote-right}
-- _So, have a look inside._
Enemy Mine (1985)
{/blurb}

Do you remember when I said that the second most important thing a computer can do is to move four ghosts in a labyrinth flooded with beads that you are trying to eat? I didn't lie, it's true. The third one, however, is to show the content of text files.

Back in the ages when I was a teenager (the 90s, just to be clear) we used to exchange data on floppy disks. Yes I know, it sounds like a time where dinosaurs still walked on earth and men went hunting with flint spears (spoiler alert, these two things never happened during the same age), but it's true. Text files were very important, song lyrics, programming tutorials, jokes, all these things came in text files. And you know what? Now, when I open a web page with some band lyrics and my screen is flooded by advertisements, pop-ups, cookie alerts, and unwanted videos I definitely miss those amazing plain dull simple text files.

OK, enough riding the train of nostalgia. My point is that these days text files are... still one of the most important things in the world of computer science! Let's consider this: every Web page and every computer program are, at their source, text files. That's it, easily 80% of what is travelling on data networks these days is still a text file. So, let's see the content of a text file, for once without firing up a text editor.

If you followed the instructions in the setup section, you should have the example files in your current directory. One of these files is `examples.txt`, and we will use it throughout the next lessons to test some commands. 

``` sh
$ cat examples.txt
```

You should have been glorified by the content of the `examples.txt` file, and you are probably wondering why things so unrelated with each other are listed together in a text file. Trust me, I'm not completely crazy yet, these things will come in handy.

There is not much more to say, so far. I warned you, text files are not as exciting as all those pop-ups and advertisements you get on your browser.

As this lesson was a bit short and there are not many smart exercises that you can run through, I will entertain you with a fun fact about `cat`. While it is a very appealing name for feline lovers like I am, `cat` actually stands for conCATenate. Indeed, you can name multiple file names on its command line, and what you will get as an output is the concatenation of their content. A side effect is that if you name only one file you are just asking the command to print its content.

* * *

## Exercises

Printing the content of a file is pretty straightforward, but there are a couple of interesting tricks that may come handy later, so these exercises will help you to discover them.


{#exercise_3_01}
#### Exercise 3.01
Print the content of the file `examples.txt` numbering lines.

[Go to solution](#solution_3_01)

{#exercise_3_02}
#### Exercise 3.02
Check if the file `examples.txt` contains spaces at the end of any line.

[Go to solution](#solution_3_02)


* * *

Cool, have a walk, enjoy some music, relax. From next lesson we will start to go a bit deeper into Unix command line tricks, and I want you ready for the fight! Feel free to bring the cat along.

Suggested film for the evening: That Darn Cat! (1965) - A beginner Unix programmer has issues with one of the simplest commands and involves the FBI in their struggle.
