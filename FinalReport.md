# ETL - Final Project Report

Our four original data sets were in CSV. The files we used included:

  - Dog intelligence according to breed
  - Heterozygosity according to breed
  - Expected heterozygozity according to breed 
  - Size according to breed

We found the data from data.world. Fortunately, the data sets were very clean and did not require much cleaning. 

For the dog's intelligence, our data looked at the following:

  - obey: probability that the breed obeys the first command (figure is lower bound)
  - reps_lower: lower limit of repetitions to understand new commands
  - reps_upper: upper limit of repetitions to understand new commands

We loaded each CSV into a dataframe, connected the database to mySQL and SQLalchemy and then cleaned the data on our SQL Workbench. The cleaning requiring was column renaming. 

Our final database was SQL database. Because we found all of the information relevant, we included all columns. We joined the data onto one final table based on the dog's breed. We considered averaging the high and lows of the number of times in which you would need to repeat a command in order to have the dog understand but we believe that representation of the range was necessary.


