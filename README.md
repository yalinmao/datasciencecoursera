# Data-Scientist-s-Toolbox
Data Science Course

## Command Line Interface (CLI)  
directories=folders  
root directory: directory at the top of the tree (/)
home directory: contains personal files (~)  
navigate directories: windows search Git Bash, Mac search terminal  
* pwd: to search the path to your working directory  
command: is the CLI command which does a specific task  
flags: are options we give to the command to trigger certain behaviors, preceded by a -  
arguments : can be what the command is going to modify, or other options for the command  
(pwd is a command that requires no flags or arguments)  
* clear: will clear out the commands in current CLI windows  
* ls: lists files and folders in current directory  
ls -a: lists hidden and unhidden files and folders  
ls -al: lists details for hidden and unhidden files and folders  
(-a and -l are flags, they can be combined into flag -al)  
* cd: stands for "change directory"  
cd takes as an argument the directory you want to visit  
cd with no argument takes you to your home directory  
cd.. allows you to change directory to one level above your current directory  
* mkdir: stands for "make new directory"  
mkdir takes as an argument the name of the directory you're creating  
* touch: creates an empty file  
* cp: stands for "copy"  
cp takes as its first argument a file, and as its second argument the path to where you want the file to be copied  
cp can also be used for copying the contents of directories, but you must use the "-r" flag  
the line: cp -r Documents More_docs copies the contents of Documents into More_docs  
* rm: stands for "remove" or "delete"  
rm take sthe name of a file you wish to remove as its argument  
you can use rm to delete entire directories and their contents by using the "-r" flag  
be very careful when you do this, there is no undo an rm  
* mv: stands for "move"  
with mv you can move files between directories  
you can use mv to rename files (mv oldname_file newname_file)  
* echo: will print whatever arguments you provide  
* date: will print today's date  

## Basic Git Commands


## Basic Markdown 
### Headings
have 2 "#": ## This is a secondary heading  
have 3 "#": ### This is a tertiary heading

## Types of Questions
### * Descriptive analyses
goal: describe a set of data  
the first kind of data analysis performed  
most commonly applied to census data  
the description and interpretation are different steps  
descriptions can usually not be generalized without additional statistical modeling  

### * Exploratory analyses
goal: find relationahips you didn't know about  
exploratory models are good for discovering new connections  
they're useful for defining future data science projects  
exploratory analyses are usually not the final say  
exploratory analyses alone should not be used for generalizing/predicting  
correlation does not imply causation  

### * Inferential analyses
goal: use a relatively small sample of data to say something about a bigger population  
inferential is commonly the goal of statistical models  
inference involves both estimating quantity you care about and your uncertainty about your estimate  
inference depends heavily both on the population and the sampling scheme  

### * Presictive analyses
goal: to use the data on some objects to predict values for another object  
if X predicts Y it does not mean that X causes Y  
accurate prediction depends heavily on measuring the right variables  
although there are better and worse prediction models, more data and a simple model works really well  
prediction is very hard, especially about the future references  

### * Causal analyses
goal: to find out what happens to one variable when you make another variable change  
usually randmized studies are required to identify causation  
there are approaches to inferring causation in non-randomized studies, but they are complicated and sensitive to assumptions  
causal relationship are usually identified as average effects, but may not apply to every individual  
causal models are usually the "gold standard" for data analysis  

### * Mechanistic analyses
goal: understand the exact changes in variables that lead to changes in other variables for individual objects  
incredibly hard to infer, except in aimple situations  
usually modeled by a deterministic set of euqations (science/engineering)  
generally the random component of the data is measurement error  
if the equations are known but the parameters are not, they may be inferred with data analysis  

## What is data?
Data are values of qualitative or quantitative variables, belonging to a set of items.

## Experimental Design
data sharing at:
https://github.com/  
http://figshare.com/  
http://github.com/jtleek/datasharing  

