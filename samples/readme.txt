About the file:
//all fields are tab-delimited
//file name is <matfilename_subdirectory_name_with_qualifier>
//for example, the attached file was translated from RBP.mat under /Computations/GLRaV-3 and is named RBP_GLRaV-3.37.txt
------------
Format of the data in the file
<meta header>
header_size  <number of rows in the header>
<header>
<variable name 1> <number of rows assigned to this variable in the file>
<variable name 2> <....>
//and so on, for header_size number of variables
//next, the content of the variables appear in the same order as the variables are listed in the header. The variable names do not appear here.
-------------
As you no doubt already know, you can run a sanity-check on the file with 
wc -l
to make sure the the line count is the sum of the rows assigned to all the variables + the number of rows in the header.