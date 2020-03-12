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

**Thought**: The email that sends is poorly formatted and isn't exactly custom. The person using this script would need to be able to have a baselevel of knowledge to open the script and customize the message. This is acceptable for now. I want to use the MIME generator from python's email library to send emails in either plain-text or HTML format. HTML emails are highly customizable.
