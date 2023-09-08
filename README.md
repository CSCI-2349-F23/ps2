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

Here's a chance for you to practice the new Unix commands we've looked at in class. You'll need to be able to use a command's `man` page to learn about new things these commands can do.

#### Exercise A 
1. Log into `cslab`.
2. Create a directory called `ps2` and move into that directory.
3. Get the file at this location: `https://www.gutenberg.org/files/17489/17489-8.txt`
4. Rename the file to `les_miz_french1.tzt`
5. Get this file at this location: `https://www.gutenberg.org/ebooks/17489.txt.utf-8`
6. Rename the file to `les_miz_french2.tzt`
7. Get this file at this location: `https://www.gutenberg.org/files/135/old/lesms10.txt`
8. Rename the file to `les_miz_english.txt`
9. Using a single command, print out the file format and encoding of the three files.
10. Use a command to inspect the first few pages of each file. Make a mental note of the language and title of each book.

#### Q1: What file format and encoding is reported for each of the three file?

#### Q2: Do you agree with the file format and encoding that was printed out for each file? Explain your reasoning.

#### Q3: Looking at the files, you probably noticed that they are all the same book. One of these files is ASCII, while the others are not? Explain why you think this might be.

#### Q4: What kind of operating system do you think might have been used to create these files? Explain your answer.

#### Q5: What command would you call to convert these files so that they would look like they were created by a different OS?

#### Exercise B

11. Now download this file `https://www.gutenberg.org/files/205/205-0.txt` and rename it to `Walden.txt`.
12. Create a file called `file_contents.txt` whose first line says "Here is information about my books".
13. Append to that file a list of the detailed contents of the `ps2` directory, making sure the size is human readable and the files are ordered in reverse alphabetical order.
14. Create a new file called `book_list.txt` that contains all of the lines of `file_contents.txt` except for the line containing information about `file_contents.txt` itself. **You must create this file using a single line containing one more more unix commands. You may not directly edit the file with vim or emacs.** It might be helpful to explore the `man` page for a few of the commands we have learned. There are several different ways to do this.
15. Convert `Walden.txt` from `ISO8859-1` to `utf8` and save the file as `Walden-utf8.txt`.
16. Use a unix command to look at the differences between `Walden.txt` and `Walden-utf8.txt`.

#### Q6: Are the two files different? If so, describe how they differ with examples.

#### Q7: Do you think the conversion worked correctly? Explain your response with examples. 

#### Q8: What text phenomenon do you see in the converted version of "Walden" that we learned about in class and the readings?

#### Exercise C

17. Confirm your current directory. You should still be in `/home/yourusername/ps2`.
18. List the short version of the contents of this directory.
19. How many lines contain the word "woman" in `les_miz_english.txt`?
20. How many lines contain the word "woman" 


#### Video for Exercises A, B, and C
Make a video of your terminal carrying out the above activities, numbered 1 through 25. Here are some guidelines:

* As before, you will practice a few times, and then once you have it down, you can take a video. 
* Feel free in your video to use "sanity-check" commands (e.g., `ls` and `pwd`) that are not specified in the instructions below.
* It's okay if you make a mistake in your video, but only if it's easy for you to recover from it. For example, if you mistype a file name, it's okay -- just keep going. On the other hand, if you accidentally delete a file, start over.



### Part 3: Show me your text editor skills

---

**Reminder:** To receive full credit you must

* Submit the slide from Part 1 to Canvas.
* Complete the course survey from Part 2.
* Post a message on Slack for Part 3.
* Submit the screen capture video from Part 6 to Canvas.

**All components of this problem set are due by Friday, September 15, by 11:59pm Boston time.**

---

