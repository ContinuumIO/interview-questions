Welcome to Continuum's open source repository for interview questions!

This work is licensed under a <a href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License.</a>

We typically expect job applicants to spend around 1-2 hours answering these
questions as part of the initial application process (i.e. at the time you
submit your resume).

You should view these questions as an opportunity to showcase your strengths,
skill set, experiences, past successes (and failures) and anything else you
think helps portray who you are and why you think you'd be a good fit within
Continuum.  We feel this is a better approach for assessing candidates than
afforded by the traditional resume-submission process.

You can pick any questions you like.  We anticipate the types of questions you
choose to answer will be dependent upon the individual; are you a generalist
or specialist?  Low-level, bit-slinging C/C++ programmer, front-end engineer,
quantitative developer, statistician, data scientist, or database architect?

If you don't feel like the existing questions allow you to best depict your
strengths -- you are more than welcome to write new questions.  Extra points
if you submit a pull request (against this repo) for the new questions.

### Software Engineering Questions

1. What was your most memorable debugging experience?  Can be any language.

1. What tools are in your toolkit with regards to debugging?  How do you
   normally debug: a) your own code, b) someone else's code (or foreign
   code bases).  Ideally cover Python debugging and a compiled language
   (C/C++ ideal).

1. Tell us about a chunk of code that you've written before that you're
   particularly fond of.  What do you like about it?  (e.g. elegant,
   evil, clever, simple) (This is along the lines of the
   'http://stilldrinking.org/programming-sucks -> All Code is bad'
   section.)

1. Tell us about a past project that you were particularly proud/fond of
   from a technical perspective.  What did you like about it technically?

1. Worst code base you've ever come across?  What were some of the issues?
   How did you rectify them?

1. Tell us about a project that required a novel,
   thinking-out-side-of-the-box sort of solution?  What did you come up
   with?  Why was it better than the alternatives?

1. Describe your ideal development environment (platform, tools, editor,
   IDEs, compilers, language, database vendor, etc).

1. What tools do you have customized dotfiles for?  Do you have the
   dotfiles available publicly?

### Bookshelf

1. Send us a picture of your (technical) bookshelf.  (We have a very
   liberal definition of what constitutes a "bookshelf".  Piles of books
   stacked on top of each other on the floor of your garage still counts.)

1. Do you own (or have you read) any of the following?
   * Design Patterns (GoF)
   * Any of the Stevens' tomes (Adv. UNIX, TCP/IP etc)
   * Mythical Man Month
   * Pragmatic Programmer


1. What are some of the pivotal technical books you've read that you feel
   had the biggest impact on you professionally?

1. What's your collection of .pdfs look like?  (i.e. papers, articles etc)


### Relational Databases

1. Tell us about some memorable database performance tuning work you've
   done in the past.  Can be from the perspective of query tuning, index
   strategies, data layout, etc.

1. A query runs "slow" -- walk us through how'd you'd approach that at a
   technical level (feel free to use hypothetical or real-life examples).

1. How does a data warehouse schema usually differ from an OLTP schema?
   *Why* do they differ?

1. How does an index-organized table (Oracle) or table with a clustered
   primary key (SQL Server) differ from default tables?  What *is* the
   default?  When would you use one over the other?

1. What's a bitmap index?  When would you use one? What are some drawbacks?
   What about a bitmap join index?  Which vendors provide bitmap index
   capabilities?

1. Open source databases: MySQL vs Postgres, have you had experience with
   both?  Which do you prefer?  What sort of things would you use one for
   over the other?

1. An experienced DBA or database developer has just set up MySQL for the
   first time (with the standard, out-of-the-box configuration).  What's
   likely to trip them up, catch them off guard, or incite incredulity?

1. What are some of the ORMs you've had experience with, if any?  What do
   you like/dislike?  Where are areas where they're well suited, versus
   areas where they're not?

1. What options are available for exploiting multiple cores on an Oracle
   or SQL Server host machine?  How could I control/affect this?

1. You've got a time-series (i.e. there's a unique datetime each row)
   table with half a billion rows and you need to process each row, one by
   one.  What are some of the issues you're going to face?  What
   techniques would you use to handle this optimally?

1. You're in charge of designing the table above (i.e. you issue the
   `create table`).  What techniques would you use for storing such a
   large amount of data?

1. What are some options for bulk loading data? Why are these typically
   faster than just doing lots of inserts?

1. What are some ways you can do windowed result sets?  Why do you need to
   do windowing?  How do different vendors offer different approaches for
   doing windowing?

1. How does Oracle differ from other vendors with regards to automatic ID
   generation?  What's are some of the advantages and disadvantages behind
   the way they do it?

1. Where would you expect to find b-trees behind the scenes?  Why are
   b-trees used in these instances?

1. Insert row if primary key doesn't exist, update if it does -- what
   options are available for achieving this?  Do different vendors provide
   different approaches?

1. You have read-only access to a production datamart/warehouse. You have
   read/write access to a powerful dev box that also has the same vendor
   database available (which you have more control over -- i.e. can create
   databases and administer locally).  You want to get the data from prod
   to your dev box so you can slice and dice however you see fit (say, in
   preparation for a new data mining project).  How do you do it?  (You
   can list multiple things you'd try.)

1. You run explain plan on a query; the IO cost is 84819818, the CPU cost
   is 84800511 -- how optimal is this query likely to be?  What sort of
   query (or queries) do you think it might be?

1. You run explain plan on a query; the IO cost is 90204, the CPU cost
   is 981098091981 -- how optimal is this query likely to be?  What sort
   of query (or queries) do you think it might be?

1. Oracle PL/SQL: what's an autonomous transaction?  When would you
   typically use one?

#### Oracle-specific

1. Data compression -- what are your options?  What are some of the areas
   you'd typically encounter compression?  What are the advantages and
   disadvantages?

1. When would you typically encounter histograms?

### Things We Would Never Ask

A tongue-in-cheek collection of questions we'd never ask.  Which probably
means we've had them asked to us before in previous job interview situations.
(What's being asked is not the issue -- it's the paper/whiteboard/offline
environment the interviewer wants the candidate to implement the solution in.)

1. Reverse this string.  In C.  On that whiteboard.  Must compile.

1. Implement queue, given stack, in Python.  In this shared Google Doc
   link we send you.  Include doctests.  All doctests must pass on first
   attempt.  No you can't run it through Python locally first.

1. What's the big-oh of (quicksort|mergesort|bubblesort|timsort)?  No, you
   can't Google it.  You should have it memorized.

1. Implement a linked-list in C on paper and make sure it compiles the
   first time.  No, you can't have access to a compiler.

1. What's the syntax for reverting your last git commit?  No you can't
   Google it.

### License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span
xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Interview
Questions</span> by <a xmlns:cc="http://creativecommons.org/ns#"
href="http://continuum.io" property="cc:attributionName"
rel="cc:attributionURL">Continuum Analytics, Inc.</a> is licensed under a <a
rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative
Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a
work at <a xmlns:dct="http://purl.org/dc/terms/"
href="https://github.com/ContinuumIO/interview-questions"
rel="dct:source">https://github.com/ContinuumIO/interview-questions</a>.

vim:set ts=8 sw=4 sts=4 tw=78 et:
