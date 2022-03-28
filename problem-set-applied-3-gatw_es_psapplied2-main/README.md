# Psets_template

This is the template repo for 30535 Data and Programming for Public Policy I. 

 1. Problem sets logistics
 1. Problem sets workflow 
 1. Some notes 


 ## Problem Set Logistics 

 Problem sets are due at midnight on Thursdays. You have 9 late coins for the quarter. A late coin extends your deadline 24 hours. You may use up to two on a given problem set. When using themm please acknowledge this in from matrer of your problem set. For each problem set, you will acknowledge that you are following the integrity policy. Please list all classmates who you consult/work with on a given problem set. 

 ## Problem sets workflow 

Watch github video if you don't remember or are confused on how to do all this

1. A pdf with the problem set will be on canvas, it has a link on it 
2. Go to this link (assigment invitation) and accept it 
3. This will fork the starter repository into our organization's repository (datasci-harris), with your Github username
4. Click on code, select open with GitHub Desktop 
5. This will open your GitHub Desktop and ask you if you want to clone the repository, select the folder you want it to live. By defauly Github Desktop will use the last folder you have used.
6. Rename pset_template.Rmd as directed by the homework
7. Work on your assigment using RStudio with this renamed file 
8. Use knitr to create a pdf document for your assigment (now you have a pdf and a Rdm with the same name)
9. Go back to GitHub Desktop and commit and push your assigment to the cloud 
10. You can check if your assigment was succesfully uploaded by going to github from your GitHub Desktop 

Congratulations your pset should be now online! 
REMEMBER to also upload your .pdf to canvas please!  


If you have any questions or something is not working go back to either the GitHub video or the slides. 

 ## Notes 

You'll notice that this repository includes a .gitognore. 
What is this?
By default, GitHub Desktop tracks all files within your local repository. Sometimes this is inconvenient, such as when working with large CSV files that don't need to be tracked or on GitHub. In this case you can use the gitignore feature to instruct git not to track these files.

To do this, go to GitHub Desktop, and click Repository > Repository Settings on the toolbar. Doing so opens a small window that allows you to specify which files or types of files to ignore. For example, if one wants to ignore all CSVs, then add the line *.csv. This will ignore all files with the extension .csv.