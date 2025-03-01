### Introduction

We've talked about the client-side and the server-side but how do we keep ahold of all our user's data?  Who remembers that your login password is `CatLover1985` so you can sign into the website?  The bottom layer of any web application is the database and it handles all the remembering for you (we'll cover caching much later).  It can be relatively simple, like an excel spreadsheet, or incredibly complex and split into many giant pieces like Facebook's.

Databases are kind of hidden in the back of the web application so people treat them with a sort of suspicion and awe.  **That's nonsense and you should get over it** -- your database and you are going to become very good friends (or at least frenemies).  By the end of this curriculum, you're going to understand what's going on with your databases and be able to interact with them like a pro (and probably better than some people you'll work with).  This lesson is a teaser for that.

Compared to a normal programming language like you've already learned, SQL (Structured Query Language), which is used to query databases, is a very simple syntax... there are only a small handful of verbs to learn.  What trips people up is that you need to be able to visualize in your head what it's going to be doing.  We'll spend a fair bit of time on SQL and databases because they're so fundamental, but for now we'll just cover enough to get you familiar with what's going on in there.

### Learning Outcomes
Look through these now and then use them to test yourself after doing the assignment

* What is a database?
* What are relational databases?
* How are relational databases different from XML?
* What is SQL?
* What is SQL used for?
* How do you get all the records from a table in SQL?
* How do you insert a record in SQL?

### Assignment

<div class="lesson-content__panel" markdown="1">

  1. Check out this [introduction](https://launchschool.com/books/sql/read/introduction) of how SQL can be used to organise and manage an overwhelming amount of data. (You do not need to go any further than the first page on introductions.)
  2. Watch this [short video introduction to relational databases](http://www.youtube.com/watch?v=z2kbsG8zsLM) to get a feel for why this stuff is useful and some more exposure to the terminology we'll use.
  3. Go through this [Khan Academy tutorial](https://www.khanacademy.org/computing/hour-of-code/hour-of-sql/v/welcome-to-sql), to get a feel for actually creating and manipulating databases.

</div>

### Additional Resources
This section contains helpful links to other content. It isn’t required, so consider it supplemental.

* [What is a Relational Database?](http://computer.howstuffworks.com/question599.htm) from HowStuffWorks.com
* A brief [Simple Wiki article describing relational databases](http://simple.wikipedia.org/wiki/Relational_database)
* Hunter Ducharme created [an e-book](https://hunter-ducharme.gitbook.io/sql-basics/) which is a great documentation on how to do all the basics in SQL.
* Relational databases aren't the only way to store data. Non-relational (aka NoSQL) databases have emerged over the last couple decades. Check out [this article](https://circleci.com/blog/SQL-vs-NoSQL-databases/) to learn the difference between SQL and NoSQL.

### Knowledge Check
This section contains questions for you to check your understanding of this lesson. If you're having trouble answering the questions below on your own, review the material above to find the answer.

- <a class="knowledge-check-link" href="https://launchschool.com/books/sql/read/introduction#structureddata">What is a database?</a>
- <a class="knowledge-check-link" href="https://launchschool.com/books/sql/read/introduction#rdbms">What are relational databases?</a>
- <a class="knowledge-check-link" href="https://youtu.be/z2kbsG8zsLM?t=200">What is a Primary Key?</a>
- <a class="knowledge-check-link" href="https://launchschool.com/books/sql/read/introduction#sql">What is SQL?</a>
- <a class="knowledge-check-link" href="https://www.khanacademy.org/computing/hour-of-code/hour-of-code-lessons/hour-of-sql/pt/querying-the-table">How do you get all the records from a table in SQL?</a>
- <a class="knowledge-check-link" href="https://www.khanacademy.org/computing/hour-of-code/hour-of-code-lessons/hour-of-sql/pt/creating-a-table-and-inserting-data">How do you insert a record in SQL?</a>
