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

---
### Day 19: March 25, 2020

**Today's Progress:** Built sqlite3 database. Still need to add functionality, like adding newly submitted entries to separate columns. Learned how important it is to correctly name files the first time around in your repositories :\

**Thoughts:** Apparently renaming a file in git doesn't transfer over history. It will also mess up any references made to the file in other scripts. Moral of the story is; be sure to name the files correctly right off the bat. My next move is to connect db.py in gui.py and automatically add new entries to the db.

---
### Day 20: March 26, 2020

**Today's Progress:** Program works! Added SQL commands to gui.py so now upon submit the user's input will be written to a text file and to a sqlite database.

**Thoughts:** In terms of funtionality, the program works great. It does what it's supposed to and I hope to use it as a useful tool for myself. There are minor improvements to be made, but I think I will revisit that later in time. For now, I plan to spend time working through tutorials and learning data structures and algorithms so I can build my arsenal for tackling problems. There's a fine line between being stuck doing tutorials forever and not creating anything for yourself and only working on projects, where things would go a lot more smoothly with some more prior knowledge.

---
### Day 21: March 27, 2020

**Today's Progress:** Not much actual progress made. I tried to refactor a part of the code that reads the questions and initializes the text boxes and got stuck. I was able to initialize everything with a dictionary, but was having trouble using that to save the user's input to text or the database, so I decided to leave it commented out for now.

**Thoughts:** I'll sleep on it and return to the problem tomorrow and see if I can't crack it. Otherwise, I'm not going to spend too long on it and start a tutorial/course on something python. Maybe data science, but data structures and algorithms would be hugely beneficial as well. I might finish the book I have and build a web app. I would also love to create a basic personal website.

---
### Day 22: March 28, 2020

**Today's Progress:** Took a lot of time understanding how venvs work, how conda works, pipenv, set up sublime text as a new IDE because it's suites my needs better for small random scripts.

**Thoughts:** Was a bit frustrating how long it took for me to get conda working properly and how to really use venvs. I also took a long while setting up sublime text with custom styling options, packages, etc. I was really struggling to get the conda package within sublime text working properly but I eventually found a decent work around/solution.

---
### Day 23: March 29, 2020

**Today's Progress:** I actually set up a venv with conda and downloaded the right version of python and packages to get an old script to work! I also successfully connected to the github and hackernews api and graphed some data using pygal. 

**Thoughts:** I'm beginning to realize how long of a road I have in front of me to truly feel like I am proficient in python. I guess the most important thing is that I can find solutions to these problems that I run into, even if it's at the expense of several frustrating hours. It's truly very fun and fulfilling and is a great hobby to add to my life.

---
### Day 24: March 30, 2020

**Today's Progress:** Started to create a django webapp. Learned some more about classes and how they work.

**Thoughts:** I came across a project that uses machine learning to predict the next lyric in a Taylor Swift song. Seems like a fun idea so I think I'm going to keep that one in my back pocket and pull it out when I'm done with the django web app.

---
### Day 25: March 31, 2020

**Today's Progress:** No progress on the web app. I did start a new jupyter notebook on a pokemon dataset because I want to become proficient in pandas and learn some data viz tools.

**Thoughts:** Because of a job description that I saw, I figured it would be good to familiarize myself with excel. I looked into some resources for doing that and thought "you know what, there's basically no reason why I should use excel over python. Python is more powerful and much more flexible once you get past the 'high barrier of entry'. So then I started a course on codecademy but it was a little bit too basic and I felt like I was wasting my time. I've been really struggling to follow along with any "tutorial" or "guide". I often feel like I'm not really learning the material that well. I understand it logically but as soon as I'm left on my own it becomes a struggle. If I chose my own project I have so much more motivation, time goes by much faster, and I feel like I learned more. For now, I'm going to continue along that path and pay attention to what tools people are using and what's out there.

---
### Day 26: April 1, 2020

**Today's Progress:** Finally cleaned up the dataset by removing all generations of pokemon beyond 3 (because let's be honest the old ones are the coolest) and dropping all the "mega" pokemon. I don't even know what those are by I don't want them conflating the analysis.

**Thoughts:** It seems like the only path forward is continuing to pursue project and then learn from there. I feel like I'm past the point of being a true beginner. I've got the basics down. I still often times feel like I have no idea what I'm doing and get tripped up by minor issues or have common misunderstandings. There's a long, long road ahead to becoming fully capable. I see this journey taking at least another 8 months.. which isn't that long at all, all things considered. The daily grind gets to you, but honestly I enjoy it. I enjoy problem solving. I enjoy creating. I enjor being challenged. I wouldn't want to spend my time any other way. It gets tiring and old after a while, but I guess that's why it's important to balance programming out with other things, like music, socializing, relaxing, exercising. Give me 2-4 hours a day of hard work programming and I'm happy camper.

---
### Day 26: April 2, 2020

**Today's Progress:** Cleaned up pokedata set. Got rid of pokemon beyond Gen 3, got rid of 'mega' pokemon. Made some graphs, filtered out data, etc.

**Thoughts:** Really starting to get the hang of python and pandas. I understand the data structures and am able to do basic things without looking up the documentation. But I'm also getting better at reading documentation.

---
### Day 27: April 3, 2020

**Today's Progress:** started learnsql.com course.

**Thoughts:** Slow day today. Friday. Practiced music a lot and didn't feel like digging into pandas, mostly because I didn't know what to do with it.
