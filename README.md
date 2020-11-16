# Lab 16 - Covid Data Lab

You will be using the Sinbad library to get access to the New York Time's Covid data.  You will use this data to answer a non-trivial question of your choosing.  Pick something you think would be interesting to know.

1. Go to the [New York Times's Covid Data Repo](https://github.com/nytimes/covid-19-data), browse through it, and find the URL of a dataset CSV file you want to use.
2. Using what you learned in the last lab, load the data into a useful format.
3. Use the data to answer a non-trivial question or make a non-trivial connection.  
4. Put the link to the CSV file, your question, and your findings in the appropriate comment block in `Main.java`.

### What is a non-trivial question? ###

A trivial question is one that is easy to answer.  Asking which state has the most cases is trivial.  You could open the CSV file in Excel, click on the column for cases, click sort, and you have your answer.  A non-trivial case requires a bit more work and would not be easily solved by sorting a column or looking at the spreadsheet.

**Example non-trivial quesions:**

* For each state, which day showed the largest percent increase in cases? (You'd have to add some sort of filter, too.  The days that increased from 1 case to 2 probably shouldn't be at the top of the list with a 100% increase.)
* Which state showed the largest percent increase, or the most total cases, in the 2 weeks after July 4th (or another event or big weekend)?