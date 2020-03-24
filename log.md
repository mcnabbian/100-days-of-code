# 100 Days Of Code - Log

*I basically started this challenge almost 3 weeks ago, but I figured I would just 'restart' because it would be nice to have a daily log of progress to look back on. In addition to the time of spent learning, I've created a jupyter notebook available [HERE](https://github.com/mcnabbian/cuttlefish).*

---
### Day 1: March 5, 2020

**Today's Progress**: Began learning SQL. Learned about relational databases and how to make some basic queries. Also learned what it means to clone a repository and what a 'remote' is in relation to git.

**Thoughts**: SQL seems like a really easy way to explore (filter, groupby, etc.) a dataset. I'm excited to complete the intro SQL course and start digging into some interesting data. I started off using 'brute force', like iterating through each row of a dataset, building lists/dictionaries, etc. That was pretty aweful and clearly inefficient when it comes to big data. I then learned how to utilize Pandas and NumPy libraries. That was much much better but still had a bit of a steep learning curve. By no means have I mastered it, but I understand how pandas dataframes are structured, how to use indexes to filter out data, how to relate two or more columns to each other, how to use the describe method to quickly get basic statistics, etc. I'm excited to see what can be done using SQL. Honestly it seems a lot more straightforward, so maybe I won't have to bang my head against the wall quite as much.

Link to work: https://github.com/mcnabbian/cuttlefish, https://sqlbolt.com/

---
### Day 2: March 6, 2020

**Notes:**
- SQL; types of joins
![join types](https://www.dofactory.com/Images/sql-joins.png)
*source: https://www.dofactory.com/sql/join*

**Today's Progress**: Progressed in SQL course. Learned how to limit and offset results. More importantly, learned several
different kinds of joins.

**Thoughts**: Spent a bit of time stuck on a left join problem; turns out I was writing the column name
incorrectly woooo. Classic. Slow day, working through tutorials isn't particularly interesting, but probably best to understand the basics.

---
### Day 3: March 7, 2020

**Today's Progress**: Learned how to use aggregates (functions) in a SQL select query. Also learned how to filter out NULL values from my results.

**Thoughts**: It's saturday and it's sunny and I'm hungry but you know what; my hour is complete. Working through this tutorial is dreadfully boring, but necessary.

---
### Day 4: March 8, 2020

**Today's Progress**: Almosted completed intro to SQL tutorial. Learned all the basics for making select queries and started to learn how to make modifications (update, delete, insert rows) to the datatable.

**Thoughts**: Another tough day to work up the motivation to sit down for at least an hour, only because I didn't get much sleep and had a pretty active day. BUT once you start, it's not so bad. Some days maybe all I do is watch informative youtube videos.

---
### Day 5: March 9, 2020

**Today's Progress:** Finished up SQL basics tutorial. Spent about an hour researching how to use Python with SQL, how to read a CSV into a database, etc.

**Thoughts**: SQLite is part of the Python standard library, so you can create queries using that. I've seen how you connect to the database and use a cursor to create queries, etc. but what I haven't seen is how you can read in an existing dataset. How do you convert a CSV into a datatable? I think that this would be much more useful than creating my own table manually. I'd like to add some SQL commands to my cuttlefish repository in order to showcase that skill, but I'm not seeing how I can convert that CSV to a database.

---
### Day 6: March 10, 2020

**Today's Progress:** Started automated_journal project. Learned about SSL, TLS, HTTP, HTTPS, encryption, and connecting to a server.

**Thoughts**: I was feeling bored and unmotivated to continue on with the same 'data project'. There doesn't seem to be a good way to read a csv into sqlite3, which is part of the python standard library. And I don't want to get into working in applications such as MySQL or SQL Server just yet. It's something that I will come back to. I've had a bit of a hard time keeping my PyCharm project files organized, using the correct intepreter, etc. so I'm going to give Sublime text editor a try in hopes that it's a little simpler and more suited to my current needs.

---
### Day 7: March 11, 2020

**Today's Progress:** "Logistical" work today; setup remote repository, reset local repository, created README, configured PyCharm project path, laid out a general 'plan of attack' for this project, listed some possible questions for the prompt to include. View the repo [here](https://github.com/mcnabbian/automated_journal).

**Thoughts**: A boring but important day today. Didn't have much time, already a quarter after 10pm, but I should be all ready to hack away at this in the future. It's weird, I almost always have anxiety before sitting down and coding, but once I do it, 5 minutes in, it's all good. I wonder if that ever goes away?

---
### Day 8: March 12, 2020

**Today's Progress:** Updated automated_journal main.py. Added try, except blocks. Added user input prompts for receiver and sender addresses. Successfully sends plaintext email.

**Thoughts**: The email that sends is poorly formatted and isn't exactly custom. The person using this script would need to be able to have a baselevel of knowledge to open the script and customize the message. This is acceptable for now. I want to use the MIME generator from python's email library to send emails in either plain-text or HTML format. HTML emails are highly customizable.

---
### Day 9: March 13, 2020

**Today's Progress:** updated main.py in automated_notebook to use an HTML message with a plain-text alternative. Learned how to use f strings. SQL practice.

**Thoughts**: I'm not sure whether I should go straight into creating a GUI for the automated notebook. If I stick with the email, I will need to learn how to use HTML to format it and how/if I can save the replies into a database. Either way, it was probably helpful to learn how to use python to send emails. There are simpler libraries out there that I could also use (like Yagmail) to make it look a lot cleaner, but knowing how to get it done with the standard library is a plus. I might put the email part on hold and look into using a GUI tomorrow.

---
### Day 10: March 14, 2020

**Today's Progress:** Created my first gui using python's tkinter package. Did some learning about navigating and reading documentation, which is something that's been a struggle for me.

**Thoughts:** I figured I may as well just go ahead and create a gui for my automated journal project. It's something that I would rather have in the long run and I feel like learning how to format an email properly is too much of a time waste. Also, I want to get better at learning how to do things by reading documentation. So far, I've had a much better of a time learning from a third party source like youtube, geeksforgeeks, etc. I think that being able to learn and read documentation effectively will make me that much better of a programmer.

---
### Day 11: March 15, 2020

**Today's Progress:** Replaced entry box with text box. Added submit button. Formatted window dimensions. Practiced SQL queries.

**Thoughts:** Things are starting to get more interesting from a project perspective. I was thinking of fun things to do down the line, create a database for entries, then pull some fun statistics/metrics from it; like most used words, consecutive days of entries, etc.

---
### Day 12: March 16, 2020

**Today's Progress:** added a popup window to appear after clicking the submit button asking whether or not the user is sure that they are ready to submit. If they click yes it 'destroys' the program. Next step is saving the entire form along with the entry to a database.

**Thoughts:** Ending up being a short day because of work and an unexpected visit to the doctors'. However, this project is seeming more and more doable and I found myself excited to get back to it.

---
### Day 13: March 17, 2020

**Today's Progress:** Cleaned up the code. Seperated a couple of actions into their own separate functions. Added functionality so that after confirming a submit, saves input in text widget to a textfile. Plan to work through SQL exercises.

**Thoughts:** More and more doors keep opening as I dig more into this project which is nice. This has been the most satisfying work I've done yet, at least when it comes to programming. Tomorrow I will see if I can efficiently add more questions and then efficiently save the responses. Later, I plan on using sqlite3 to create/use a database to save responses.

---
### Day 14: March 18, 2020

**Today's Progress:** Added multiple questions to gui by reading from a txt file. Reformatted root to include canvas and frame widget to pack widgets together and to create/use a scrollbar.

**Thoughts:** I feel good about the progress made today. For some reason though it's turning out to be more difficult to add a functional scrollbar that can be use to scroll the entire window while also keeping widgets grouped together properly. I'll need to become more familiarized with tkinter, specifically creating new windows, what a root is, frame, canvas, and their respective functionalities. It's not exactly pretty, but the program works; Got all the questions, scrollable window to see questions, submit button, and saves responses to a txt file with a nicely formatted date and time attached to each entry.

---
### Day 15: March 19, 2020

**Today's Progress:** Created new method 'create_questions' to clean code up a bit and make it more readable. Reorganized packing of widgets. Reformatted frame and window so that window is larger and the frame is centered.

**Thoughts:** I'm seeing some downfalls of using tkinter. It's simplicity make it easy to create a simple gui, but it is also it's biggest hinderance in getting windows nicely configurated. For instance, it doesn't seem like centering a window, centering widgets within that window, and adding a scrollbar to the window shouldn't be as difficult as it has proven to be. It may be worth exploring other, more complex gui packages. For my purposes right now, tkinter should suffice.

It looks like the canvas is only being created in order to implement a scrollbar. I wonder if I can bypass the canvas and just add a scrollbar to the frame instead? Because I'm not seeing much of a point to using a canvas.

---
### Day 16: March 20, 2020

**Today's Progress:** Pretty much nothing at all! On paper that is. Banged my head against the wall. 

**Thoughts:**  I'm struggling to figure out how to save multiple text widgets within the same window. I'm looking for a way that isn't just 'brute force'. Right now I know two options: (1) Save one text widget per window, which would mean I'd open, write, and submit one question at a time. (2) Initalize each text widget separately. Things could get real ugly real fast with this. I'll do some more research and definitely reach out to communities that may be able to help first before doing anything.

I'm slightly bummed that my streak will be ending tomorrow. I'll be out of town with no internet having some fun. Oh well, it will pick back up on Sunday.

---
### Day 17: March 23, 2020

**Today's Progress:** Fixed automated_journal and now it runs correctly. However, it's using 'brute force' and is ugly to look at. Got started on a solution to clean up the code.

**Thoughts:** Happy that the program now runs as expected. I'm having a hard time figuring out a more elegant solution. After deliberating with my friend and a lot of frustration, he got me started on a possible solution. It basically is by creating a list of Text objects and indexing them when I need to call .get(). 

---
### Day 18: March 24, 2020

**Today's Progress:** Automated_journal now has cleaner, more flexible code. I also updated the github remote repository.

**Thoughts:** After all that frustration, it really didn't take me long to figure out how to use a list and for loop to refactor all that code. It's super satisfying figuring that out and having my program run as expected. Now I plan on adding a database to it, probably using sqlite3 or mysql. I'll also add other useful features, like try-except blocks, possibly statisitcs, basically anything I can think of to make the program more user friendly and robust.
