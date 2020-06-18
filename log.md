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
### Day 27: April 2, 2020

**Today's Progress:** Cleaned up pokedata set. Got rid of pokemon beyond Gen 3, got rid of 'mega' pokemon. Made some graphs, filtered out data, etc.

**Thoughts:** Really starting to get the hang of python and pandas. I understand the data structures and am able to do basic things without looking up the documentation. But I'm also getting better at reading documentation.

---
### Day 28: April 3, 2020

**Today's Progress:** started learnsql.com course.

**Thoughts:** Slow day today. Friday. Practiced music a lot and didn't feel like digging into pandas, mostly because I didn't know what to do with it.

---
### Day 29: April 4, 2020

**Today's Progress:** Kept messing around with the pokemon dataset. Accidentally deleted a lot of work and had to reset to an earlier file version, so I lost a lot.

**Thoughts:** Was kind of bummed that I lost some work. It's not a huge deal because it was all basic stuff for the most part. I learned the importance of saving and creating checkpoints for jupyter notebooks. I also learned that it's probably safer to just use the undo button.

---
### Day 30: April 5, 2020

**Today's Progress:** Completed second part of A-Z SQL couse from learnsql.com.

**Thoughts:** It's a great platform to learnsql, but it's a pretty spendy. It's free for like two more weeks however.

---
### Day 31: April 6, 2020

**Today's Progress:** Refactored a big chunk of code from the cuttlefish project. Practiced SQL. Fixed an issue with the cuttlefish repo. Yoga. Spikeball.

**Thoughts:** Felt great to refactor that code. It's like tangible progress has been made in the learning process. Also I keep forgetting to update this log becuase I've been posting daily updates in a discord community, but I'll be better about remembering.

---
### Day 32: April 7, 2020

**Today's Progress:** Worked a lot of music and it went great. I also practiced more sql.

**Thoughts:** Bit of a lul in programming for me. I'm grinding on SQL because I have free access for like another week to a quality resource. I'm waiting on receiving an intro to computation book in the mail, made by an MIT professor, so I can start working on my CS fundamentals (DS and algorythms).

---
### Day 33: April 8, 2020

**Today's progress:** MORE MUSIC!! MORE SQL!! A NICE WALK! YOGA! ANOTHER LOSS IN MARIO KART!

**Thoughts:** Music production is loads of fun and it's taking up more of my time right now. I'll keep working on SQL and wait for either the stanford course to start or my book to arrive in the mail. Or I might complete that Django web app or start a kaggle ML course.

---
### Day 34: April 9, 2020

**Today's Progress:** SQL! also got my MIT book so I'm going to start working through the online course. Priority to SQL.

**Thoughts:** Super excited to get started on building that fundamental CS knowledge. Also it's super nice today so getting outside.

---
### Day 35: April 10, 2020

**Today's Progress:** Finished SQL basics course.

**Thoughts:** Plenty more SQL to learn but I'm going to work through some practice problems to help test/solidify those basics. Also to add in some variaty I'll start working through MIT book.

---
### Day 36: April 11, 2020

**Today's Progress:** Chapter 2 of MIT book. Figured out some IDE problems.

**Thoughts:** Was having problems with 'inputting' in sublime text so looks like Pycharm will be more useful. I've probably wasted time going back and forth between the two, such is life. I finally took the time to figure out some basics in Pycharm which should make things easier. Sublime text has ultimate customability and in some ways is a lot more simple. In other ways, it's not intuitive at all and pycharm does a better job for getting a newb up and running.

---
### Day 37: April 12, 2020

**Today's Progress:** Very unproductive. Spent too much time going back and forth between resources. Did some work in MIT book.

**Thoughts:** A bit of a frustrating day because I spent so much time trying to figure out the best resource to use and did a bit of back and forth between two. I decided I'd go through harvard's CS50 because it is recently updated, has nice layout, support community, graded assignments, etc. I was hesitant because it's not python (at least the majority of it) and I already spent money on this nice book for the MIT course. However, I found out that the book doesn't have great practice problems and solutions to those problems online. The course offered through OCW is clunky and very out of date, depending on which release. The MIT course that I want to take doesn't start until June 3, and that's offered through Edx. SO, I figured I may as well work through CS50 and, when the time arrives, I'll hop into the MIT course. Or not, idk, just depends on how solid I feel in my CS fundamentals. I've read that people recommend doing both as they are different in a few important ways. For instance, CS50 is mostly teaching C.

---
### Day 38: April 13, 2020

**Today's Progress:** CS50 week one lecture and finished two problems out of the first set. 

**Thoughts:** C isn't all that much different than Python. I mean it is and it isn't. The core programming concepts are the same, but the way you go about doing them is pretty different. I see why C is considered more difficult to pick up. I do kind of like it because it's simpler/more rudimentary in some ways. I get more of a feel for how the source code gets translated into machine language and how that gets executed by the computer. This course would be very hard to do without prior experience. Even the second problem from the first week took me a couple of hours when I thought that it would take me like 30 mins because it's just ascii art, granted I'm doing the 'hard' problems.

---
### Day 39: April 14, 2020

**Today's Progress:** Worked on CS50 assignment. Band meeting.

**Thoughts:** CS50 is a tough course and I'd consider myself proficient in Python. C is not as intuitive as Python but I do like how the error messages are a lot more informative.

---
### Day 40: April 15, 2020

**Today's Progress:** LOTS of debugging on CS50 project. Messed around with making custom drum machine.

**Thoughts:** I'm getting much better at debugging. I've found that just printing damn near everything is a great way to understand and see what is going on and which part of the code may be messing it up.

---
### Day 41: April 16, 2020

**Today's Progress:** FINISHED ASSINGMENT! Lecture 2 of CS50

**Thoughts:** This assignment was tricky. It probably took me around 8 hours to complete it. Doesn't sound like a whole lot on paper but it's a long time to be sitting down and concentrating hard. It's only week one and I already have a good amount of experience with CS so yeah this would be impossible for me if I started this like 6 months ago. Granted, I am doing the 'hard' problems when given the choice, so they're probably geared towards people like me. 

---
### Day 42: April 17, 2020

**Today's Progress:** Worked on problem set 3.

**Thoughts:** I should've made a lot more progress on the first problem than I did today. I got tripped up by a simple logic problem, which made me frustrated, which affected my thinking/coding skills, which made me more frustrated, etc. etc. Just one of those days. Probably best to chalk it up as an L and come back to it later or tomorrow. 

---
### Day 43: April 18, 2020

**Today's Progress:** Another day, another problem complete. One to go for week 2.

---
### Day 44: April 19, 2020

**Today's Progress:** Started the hard problem in problem set two.

---
### Day 45: April 20, 2020

**Today's Progress:** SO CLOSE to finishing problem set two. Just gotta figure out how to convert the char array I built in a for loop into a string.

**Thoughts:** Even though I was really trying to focus on 'mastering' one language, I think learning C is super beneficial to my understanding of computation and programming. This class has gotten me a whole lot more interested in computation as a science and has solidified my desire to pursue it purely out of personal interest. Yes, there are good jobs associated with it, but it's honestly just really interesting, there's so much to learn which I love, and it there's basically barrier to entry to start building things. Even if you screw up on that process, it's 99% of the time not a big deal. It's not like working on your car as a hobby, where you order expensive parts and how you can really screw something up if done incorrectly.

---
### Day 46: April 21, 2020

**Today's Progress:** Finished problem set 2. Fun fact, you can't return an array, you can return a pointer or something but yeah I had to individually print out each char from the array.

---
### Day 47: April 22, 2020

**Today's Progress:** Watched week 4 lecture of algorithms and recursion. Completed first problem which was weirdly easy.

---
### Day 48: Apirl 23, 2020

**Today's Progress:** Started the second problem in set 3. This one is going to be real tough.

**Thoughts:** Well I see why the last one was so easy. This one is much more complicated and harder, granted I am doing the "more comfortable" version of the problem which is supposed to be harder. I almost settled for the easier one because of how intimidating it seems, but I told myself I'd do all the hard ones so that's what I'm going to do. I bet it'll be good for me to struggle and problem solve. That's where you really learn anyways. It'll just increase my confidence in programming if I can get past this.

---
### Day 49: April 24, 2020

**Today's Progress:** Completed a couple different functions for tideman problem

---
### Day 50: April 25, 2020

**Today's Progress:** Completed another function. Slow and steady

**Thoughts:** 50 days down! 50 more to go! Realistically, I'm going to have to do this everyday for like another 6+ months easily.

---
### Day 51: April 26, 2020

**Today's Progress:** Created a function for sorting a 2-D

**Thoughts:** Great learning experience here: tackeling tough problems. This problem started off super intimidating, and it has no doubt been difficult, but I'm making slow and steady progress towards finishing it. Writing down what's happening or what needs to happen on pen and paper has been super helpful for understanding a problem and how I can go about solving it. This problem is difficult to unit test, but so far has been compiling at least haha.

---
### Day 52: April 27, 2020

**Today's Progress:** Slow and steady progress on tideman problem :\

---
### Day 53: April 28, 2020

**Today's Progress:** Another day of hitting my head on the wall, but I think I figured out a tough function

---
### Day 54: April 29, 2020

**Today's Progress:** SO CLOSE! All the test cases passed except for one. I need to figure out how to detect middle cycles in a 2-D array.

**Thoughts:** I'm tempted to call it and turn it in since it's so close. But honestly I've spent so much time/energy trying to figure this out that I'm going to get it right if it kills me. I talked things out with some people and I think I understand theoretically how to solve the issue, but putting down in code in intimidating. I'll give it a shot later if I have time. Otherwise tomorrow I'll give it another crack.

---
### Day 55: April 30, 2020

**Today's Progress:** Nothing, on paper. I have a mucher better understanding for how an adjacency matrix works.

---
### Day 56: May 1, 2020

**Today's Progress:** FINALLY SOLVED THE PROBLEM. I was trying to figure out the lock_pairs function for a solid 4 or 5 days. I used two nested for loops and it was pretty ugly but oh well. It would be much more simple to use recursion but I could not conceptualize how to use it for this. Recursion and 2-D arrays are definitely something that I am going to have to come back to in the future. It's a weak point so I'm just going to have to hit it harder.

---
### Day 57: May 2, 2020

**Today's Progress:** Learned about binary, memory storage, bit storage, all that fun stuff.

---
### Day 58: May 3, 2020

**Today's Progress:** Finished week 4 lecture.

---
### Day 59: May 4, 2020

**Today's Progress:** Started pset4

---
### Day 60: May 5, 2020

**Today's Progress:** pset4 work.

**Thoughts:** This assignment is creating image filter! It's pretty cool and gives me a much deeper understanding for what pictures are and how they're just 2-D arrays. I understand what bytes are, what a 24-bit image is, etc. I understand why higher resolution photos take more memory, why high bit photos take more memory.

---
### Day 61: May 6, 2020

**Today's Progress:** more pset4 work.

**Thoughts:** My buddy identified a stupid mistake in my code and fixed it so that was nice. When I fixed it and before a ran it again, I wasn't convinced that it would really change anything. Lo and behold, I got the correct output. Sometimes it's funny how one little piece can make or break your code. Upon first glance, it didn't seem like it even mattered. 

---
### Day 62: May 7, 2020

**Today's Progress:** pset4 work. Now on the blurring filter function.

**Thoughts:** I need to figure out how to basically replace my old bit map with a newly created bitmap, that has the correct 'blurred values'. I also need to figure out the edge cases (literally how to deal with the pixels on the edge of the bit map). I'm honestly not sure if I could be doing things much more efficiently tbh. Right now I have 3 nested for loops which is probably the most I've had yet. There must be a way to use recursion. I'm just so bad at thinking about how I can actually use recursion, but I get it in theory.

---
### Day 63: May 8, 2020

**Today's Progress:** Shorter day, not much progress. Struggling with blur function.

---
### Day 64: May 9, 2020

**Today's Progress:** More struggle with blur function.

---
### Day 65: May 10, 2020

**Today's Progress:** I understand how to solve the problem and I refactored the code that I had previously and cut it way down and made it much cleaner.

**Thoughts:** I previously solved the problem in a rudimentary way, not understanding that there was a cleaner solution. I found some comments people made on the cs50 discord channel and finally understood what to do. I basically went from changing my for loop initialization depending on where I was in the graph to keeping the initialization consitent, but if I happened to be looking at one of the edge cases, simply do nothing and move onto the next cell.

---
### Day 66: May 11, 2020

**Today's Progress:** FINALLY figured out why I wasn't getting the correct color values in my temp array. Struggled with that for hours yesterday. SO, solved blur function and made very good progress on edge function. Going to revisit that tomorrow, but it shouldn't take more than 1.5 hours.

**Thoughts:** Sometimes I'm convinced I'm real dump and not cut out for this. Sometimes I miss seeing the easier, cleaner solution. Does this make me a bad programmer? Maybe I'm not as bright/clever right off the bat. But, I will work through my struggles, learn and understand the problem, and then revisit the situation with an open mind. I think that that is plenty good enough for building the things that I want to build.

---
### Day 67: May 12, 2020

**Today's Progress:** Finished pset4! 

**Thoughts:** I thought it wouldn't take me as long because I just had to finish up an indexing error and stuff but, lo and behold, I was getting an incorrect output. I spent a good amount of time trying to debug it myself then reached out to the discord community about what the output I was receiving might mean. Turns out, when I was filling the byte array with new values, I was storing int values that were too large. So, some of that int storage got thrown out, giving me an incorrect byte value. All I had to do was switch when I capped the value. I was capping the value after adding it to the byte array, but I needed to do it before. The 'filter' problem was way more interesting than the tideman problem. Tomorrow will the data structures week.

---
### Day 68: May 13, 2020

**Today's Progress:** Watched Week 5 lecture on data structures.

**Thoughts:** I didn't realize there was another problem to do in pset4, so I'll be going back and starting that probably tomorrow :(

---
### Day 69: May 14, 2020

**Today's Progress:** started recover from pset4.

---
### Day 70: May 15, 2020

**Today's Progress:** Made progress on recover. 

**Thoughts:** It's kinda cool learning how to "recover" lost data by inspecting some bits.

---
### Day 71: May 16, 2020

**Today's Progress:** Finished recover. Now I can finally start pset5

**Thoughts:** that problem was harder than I expected. There was one tricky part about reading in info from a file with a while loop and closing out of the while loop properly and stuff. I had a hard time understanding how to open a file object and close it to create a new file object with an updated name and how I could do this depending on the first four bytes of a 'chunk'. I figured out that I needed to open that file object and initialize it with NULL outside of the loop and then close it after the loop ended and the file was done being read.

---
### Day 72: May 17, 2020

**Today's Progress:** started pset5

**Thoughts:** this problem seems very challenging and there's a lot of information to unpack and understand before I can even get started.. which is probably my least favorite activity. It's much more fun when I've gotten a grasp of the situation and I can try different things to tackle a problem. But first it takes understanding of 'what even is my problem'?

---
### Day 73: May 18, 2020

**Today's Progress:** Started tackling the load function.

**Thoughts:** well watching the walkthrough helped a lot so now I can finally try some different stuff out and see what happens

---
### Day 74: May 19, 2020

**Today's Progress:** Still working on speller.

**Thoughts:** I'm struggling to understand how to create a hashtable and add new nodes to it

---
### Day 75: May 20, 2020

**Today's Progress:** Solved a couple more functions in speller.

**Thoughts:** I tried creating my own hash function to start so that I could learn and understand it fully but it was a huge struggle.

---
### Day 76: May 21, 2020

**Today's Progress:** great progress, but given words of a length of ~45, it breaks my hash function. It ends up returning a negative int somehow, even though that is one of the checks in the hash function. Tomorrow will be some debugging :(. Other than that, this problem isn't too difficult from here on out. I should go back and make it more efficient and mess with the hashing function to see what happens.

---
### Day 77: May 22, 2020

**Today's Progress:** more pset5 work.

**Thoughts:** the numbers get too huge to hold in a long int. So i just took the absolute value of the int, which isn't exactly ideal but it works.

---
### Day 78: May 23, 2020

**Today's Progress:** Passed all tests!!

**Thoughts:** before i'm done working on this problem, I want to see if I can't optimize it a little bit more and make it more efficient.

---
### Day 79: May 24, 2020

**Today's Progress:** Cleaned up the code a bit

**Thoughts:** Well I submitted my code in the "speed" contest and got sub 400 out of 1200 so I feel pretty okay about it. I tried cleaning up the code a bit, small refactoring, but nothing made a difference for whatever reason. Perhaps using a trie would speed things but because memory doesn't matter.

---
### Day 80: May 25, 2020

**Today's Progress:** set up java IDE (IntelliJ) with the runelite github repository. Went through the steps of setting that up with Maven and some other things.

**Thoughts:** I'm really excited to contribute to open-source, especially to things that I have interest in. The client I use to play OSRS is open-source and on github so I figured that that would be a great place to start. However, it's all very intimidating. The repo is much more complicated than anything that I've ever worked with. There's lots of connecting pieces and simple navigation is troublesome. It's also written in Java, a language I have little experience in from years ago. However, I am determined to do SOMETHING, even if it's just some documentation editing. It's like trying to drink water out of a fire hose.

---
### Day 81: May 26, 2020

**Today's Progress:** Nothing much, watched a long video on open source contribution. Had a rough day and a long night before that.

**Thoughts:** I was kind of hoping that they'd break down a complicated git repo and show an example, but instead they talked about their experience. They try and make it sound less intimidating and make it sound really cool, which it is. It's a community of people magically working together and it's all around great for people and society.

---
### Day 82: May 27, 2020

**Today's Progress:** Getting myself familiar with the runelite repo.

---
### Day 83: May 28, 2020

**Today's Progress:** Another day spent getting myself oriented, trying to understand what is going on in the code. Trying to understand java syntax. Looked at a couple of issues and tried to solve them, even if they already had pull requests.

**Thoughts:** I still feel like I'm getting blasted in the face by fire hose water, but it is encouraging when I understand how an issue was solved and how it was solved. Almost all the problems are out of scope for me, I'm not ready to tackle the complicated ones. But if it's something like adding an overlay to an object, I figured out how to do that! And how it works by calling the runelite API.

---
### Day 84: May 29, 2020

**Today's Progress:** spent some time looking at issues and their subsequent pull requests and seeing if I could recreate the solution/understand what was going on/even find it in the repo. Even finding where the mentioned issue lies in the codebase is suprisingly difficult.

---
### Day 85: May 31, 2020

**Today's Progress:** looked at an agility overlay issue someone brought up, but eventually figured out that the solution was going to be quite difficult and janky and that it wasn't worth spending the time trying to figure it out.

**Thoughts:** didn't really spend anytime working on programming yesterday. I think I needed a bit of a break, just got laid off and everything. 

---
### Day 86: June 1, 2020

**Today's Progress:** Basically nothing. Spent all day figuring out how to implement a new emoji into runelite. I actually ended up getting it to work but it looked like crap in game and I couldn't figure out why. I tested other emojis and they looked fine, so I think it was the nature of the emoji and the png used. I was convinced there was a problem in not using 8-bit coloring after looking at others people have added, I don't think that was it.

---
### Day 87: June 2, 2020

**Today's Progress:** NOTHING! Spent a lot of time reading the runelite codebase, fixing my git situation, and reading my new java book. I looked at some pull requests that people submitted and basically tried to understand what they did and how everything worked in the code written. There's a lot of syntax in java that is unfamiliar to me, so when I came across things I didn't recognize I looked them up on the web or referenced my book.

---
### Day 88: June 3, 2020

**Today's Progress:** Made my first pull request! I figured out the emojis to use and implemented various country flags and like a rainbow flag.

---
### Day 89: June 4, 2020

**Today's Progress:** Made another pull request! This one is to fix an issue where item buy limit timers were being duplicated.

---
### Day 90: June 5, 2020

**Today's Progress:** Well turns out I didn't understand what the expected output should be so my solution isn't any good. It also turns out the problem isn't quite as simple as I thought it might be. I spent like all day narrowing it down.

**Thoughts:** Doing this contribution is by far the most that I've learned and it's the most real world experience. I also learned a lot creating an automated journal in python, but contributing to Runelite uses many different skills like how to navigate a codebase, read others codes, understand what it happening, fix issues that people bring up, deal with vague info about the issues, work with the other developers, get flack on PRs for people's weird opinions (one guy didn't like the use of hashtags to trigger flag emojis and specifically really disliked the rainbow, white, and blacks flags haha). 

---
### Day 91: June 6, 2020

**Today's Progress:** Submitted PR to fix an issue with a timer being duplicated in a grand exchange widget.

**Thoughts:** I didn't feel like sitting down and working on this today honestly. I was tired of being stuck on this issue and wanted to submit another PR as soon as possible to fix the one that I put in before. It does feel great when you've identified a problem and manage to fix it.

---
### Day 92: June 7, 2020

**Today's Progress:** Read up on java in my new book. Solved a leetcode easy problem.

**Thoughts:** It's not exactly the most ~riveting~ read but it does close a lot of those 'loose ends' in my knowledge of java, which helps me with readability and writing. There's a lot more syntax and 'stuff' to java than C and in some ways Python so it's just going to take some time.

---
### Day 93: June 8, 2020

**Today's Progress:** Submitted another PR that *I THINK* fixes the issue. I tested it in game and it fixed it, I just don't know if my solution is the 'optimal' one.

---
### Day 94: June 10, 2020

**Today's Progress:** Received feedback on latest PR and attempted to make changes.

---
### Day 95: June 11, 2020

**Today's Progress:** Spent most of the day just trying to debug for my latest PR. Turns out the the teleport timers were being created slightly early (before the animation was actually complete). Learned some good stuff on using the debug logs though.

---
### Day 96: June 12, 2020

**Today's Progress:** Okay so after some more debugging I've figured out more of the problem. Unfortunately, it appears to be more complicated than I initially thought, so it may be outside the scope of my knowledge. However, it's a really niche thing (using home teleport from Underwater) that maybe I'll submit a solution that only partially fixes it.

---
### Day 97: June 15, 2020

**Today's Progress:** Worked on cow teleport bug

---
### Day 98: June 16, 2020

**Today's Progress:** More work on cow teleport

---
### Day 99: June 17, 2020

**Today's Progress:** leet code and worked on cow teleport

--
### Day 100: June 18, 2020

**Today's Progress:** leet code and cow teleport work

**Thoughts:** I might just have to move past this cow teleport thing. It's just a minor issue and doesn't really matter much. It has been a great experience for me to learn OOP though. The only thing that's keeping me in it is the fact that I'm having trouble tracking an NPC's animation changes, which I feel like is something useful to know and something that I can definitely do. OH BTW 100 days BABY!!! I plan on continuing this journey as I can see first hand how far I've come since I dedicated myself to programming for at least an hour everyday.

“Most people overestimate what they can do in one year and underestimate what they can do in ten years.”
- Bill Gates

I think this even applies on a smaller scale as well. We overestimate how much we can get done in a day, underestimate how much we can get done in a week. Over estimate how much we can get done in 1 month. Underestimate how we can get done in 3 months. It's *DAILY* chipping away at something, learning some skill, that really adds up over time. Whatever it is you want, it can be achieved with small daily progress. It may take 5 years, it may take 10, it may take 15, etc. But someday it will be achieved or you will have changed your mind along the way/found something better that you never even thought of.
