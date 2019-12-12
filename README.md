# Compare data in Python 

> Doc on Comparing two files

A simple GUI that can compare two selected files.
We select two files and check the integrity of the data. 
We can check with an **MD5 Checksum** and also an **SHA1 algorithm**.
In this instance, by checking the integrity of the data we will be checking the 
data set in its entirety and we will either 
pass the test or fail it. 

### MD5 Checksum 
> It's essentially an algo that returns hexadecimal number for
the content of a file. 

### SHA1 Algo 
> It's another algo that converts the file content to a string. 

### Use 
Run the app inside pipenv shell. Then select the two files regex.py
and test.txt. The contents are different so after clicking the submit button 
the app will show the results.    