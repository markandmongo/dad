dad
===

Database Administration Dashboard 

Covered under LGPL, initially by Mark Nielsen. 
However, make donations under Public Domain. It easier to change to a new license or perhaps
make some libraries GPL instead of LGPL. 
Only donations in public domain will be accepted for now. 

Initially, everything will be written in Python. 
The goals are:

1. Inserting data into a database. 

2. Getting the data for monitoring services, like nagios, etc. 

3. Displaying the data. 

4. Creating a management interface so that you add/remove hosts, etc. 

The main purposes of DAD are:

1. Include all databases possible, SQL or NoSQL. MariaDB, PostgreSQL, Oracle, Mongo, CouchDB, db, etc. 

2. Report cpu, i/o, diskspace usage and growth, process information. 

3. A non-DBA computer geek should be able to tell what is going on with the systems without being a DBA. 

4. Messages about possible remedies or more excplicit messages about what is wrong. 

5. Warning levels for things that appear to be bad. 

6. Projections on cpu, memory, diskspace, I/O etc over a period of 1 month, 6 months, and 1 year. 

7. To eliminate the need to hire a DBA. Everything should be done so that reporting and suggestions removes 
the need of having a DBA. 

8. Displays should be total informattion oriented so that you can tell what is happening to your systems in one page 
and further drilldowns contain all useful infomration on one page. The most important stuff should be on the page
you are looking at where you don't need more drill downs in most places. Reduce the clicks and usage to get the
information you want so in a time of crisis you can work fast. 
