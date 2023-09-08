# Problem Set 2 

To receive full credit you must:

* thing 1
* thing 2

**All components of this problem set are due by Friday, September 15, by 11:59pm Boston time.**

*Note: Please don't try to commit changes to the repo. Homework should be turned in via Canvas for this class.*

---

### Part 1: Checking in (no credit)

1. Are you able to log into `cslab` yet? If not, email me now at prudhome@bc.edu.

2. Have you changed your password yet from the default one assigned by our systems administrator? If not, log into `cslab` and use the `passwd` command to change your password now.


   
### Part 2: Unix Practice

Here's a chance for you to practice the new Unix commands we've looked at in class. You might need to use a command's `man` page or to read about the command on the internet to discover the interesting things these commands can do. Log into `cslab` and execute unix commands to complete each numbered task in Exercises A, B, and C.

As before, you will be taking a video of your screen as you type the commands. Practice a few times until you feel comfortable, then take your video. You will also submit your command history from the recording session. Finally, you'll provide written answers to some questions. More details are provided below.

#### Exercise A 
1. Create a directory called `ps2`
2. Move into that directory.
3. Get the file at this location: `https://www.gutenberg.org/files/17489/17489-8.txt`
4. Rename the file to `les_miz_french1.txt`
5. Get this file at this location: `https://www.gutenberg.org/ebooks/17489.txt.utf-8`
6. Rename the file to `les_miz_french2.txt`
7. Get this file at this location: `https://www.gutenberg.org/files/135/old/lesms10.txt`
8. Rename the file to `les_miz_english.txt`
9. Using a single command, print out the file format and encoding of the three files.
10. Use a command to inspect the first few pages of each file. Make a mental note of the language and title of each book.

#### Q1: What file format and encoding is reported for each of the three file?

#### Q2: Do you agree with the file format and encoding that was printed out for each file? Explain your reasoning.

#### Q3: Looking at the files, you probably noticed that they are all the same book. One of these files is ASCII, while the others are not? Explain why you think this might be.

#### Q4: What kind of operating system do you think might have been used to create these files? Explain your answer.

#### Exercise B

11. Now download this file `https://www.gutenberg.org/files/205/205-0.txt` and rename it to `Walden.txt`.
12. Using a single line containing one or more unix commands, create a file called `file_contents.txt` whose first line says "Here is information about my books".
13. Append to that file a list of the detailed contents of the `ps2` directory, making sure the size is human readable and the files are ordered in reverse alphabetical order.
14. Create a new file called `book_list.txt` that contains all of the lines of `file_contents.txt` except for the line containing information about `file_contents.txt` itself. **Again, you must create this file using a single line containing one more more unix commands. You may not directly edit the file with vim or emacs.** It might be helpful to explore the `man` page for a few of the commands we have learned. There are several different ways to do this, all of which are fine!
15. Convert `Walden.txt` from `ISO8859-1` to `utf8` and save the file as `Walden-utf8.txt`.
16. Use a unix command to look at the differences between `Walden.txt` and `Walden-utf8.txt`.

#### Q5: Are the two files different? If so, describe how they differ with examples.

#### Q6: Do you think the conversion worked correctly? Explain your response with examples. 

#### Q7: What text phenomenon do you see in the converted version of "Walden" that we learned about in class and the readings?

#### Exercise C

17. Confirm your current directory. You should still be in `/home/yourusername/ps2`.
18. List the short version of the contents of this directory.
19. Print out the number of lines in each book.
20. Print out the number of lines containing the string "candle" in `les_miz_english.txt`?
21. Print out the number of lines containing the string "candle" or "Candle" in `les_miz_english.txt`?
22. Print out the number of lines containing the **word** "candle" or "Candle" in `les_miz_english.txt`?
23. Print out the all lines beginning with "What" in `Walden.txt`.
24. Print out the number of lines ending with "y" in `Walden.txt`.
25. Use a command to inspect the contents of `Walden.txt`.

#### Q8: You should see plenty of lines in `Walden.txt` that seem to end in "y". Most likely, your command for task 24, above, reported that there were no lines that ended in "y". At the very least, the first command that you called reported 0 matches, though you might have figured out away around this after you did task 25. What could explain this discrepancy?

26. Execute a command on `Walden.txt` that will make it possible to use a simple regular expression to report the correct number of lines ending in "y" in `Walden.txt`.
27. Repeat task #24, above.
28. Print out the number of lines in `Walden.txt` containing the string "the house".
29. Print out the number of lines in `Walden.txt` containg the word "the" and the word "house". The two words do not have to appear next to each other, but they can.
30. Print out the number of lines in `les_miz_french1.txt` do not contain "e".
31. Print out the number of lines in `les_miz_french1.txt` do not contain "e" *and* are not blank lines or lines containing only space.
32. Print out the number of lines in `les_miz_french2.txt` that contain any number between 0 and 5.


#### Submission Component 1: List of commands for Exercises A, B, and C
Use the `history` command (along with a few other unix tricks you know) to print out all 32 commands, above, to a file called `ps2_part2.txt`. It's okay, of course, if you include more than 32 commands. You might have some errors or typos, or perhaps you did some sanity checking (e.g., checking your current directory or its contents). Submit this file to Canvas.

#### Submission Component 2: Video for Exercises A, B, and C
Make a video called `ps2_part2.mov` (replace `mov` with whatever file extension is produced by your screen capture software) of your terminal as you carry out the above activities, numbered 1 through 32. Submit this video to Canvas. Here are some guidelines:

* As before, practice a few times, and then once you have it down, take the video. 
* Feel free in your video to use "sanity-check" commands (e.g., `ls` and `pwd`) that are not specified in the instructions below.
* It's okay if you make a mistake in your video, but only if it's easy for you to recover from it. For example, if you mistype a file name, it's okay -- just keep going. On the other hand, if you accidentally delete a file, start over.

#### Submission Component 3: Answers to Questions Q1 through Q8
Submit a pdf, called `ps2_part2.pdf` of your answers to Questions Q1 through Q8 to Canvas. Give thoughtful answers using complete sentences to receive full credit.



### Part 3: Show me your text editor skills
Now you will get to show me that you are learning how to use a text editor. As discussed in class, you can use emacs or vim. They are 

---

**Reminder:** To receive full credit you must

* Submit the slide from Part 1 to Canvas.
* Complete the course survey from Part 2.
* Post a message on Slack for Part 3.
* Submit the screen capture video from Part 6 to Canvas.

**All components of this problem set are due by Friday, September 15, by 11:59pm Boston time.**

---

