# REGULAR EXPRESSIONS 
## Github Link - https://github.com/KeerthivasanSuryanarayanan/DataScienceApplications/blob/main/DSA%20Assignment%20-%20Regular%20Expressions.ipynb
![RE_ASSIGNMENT 1](https://user-images.githubusercontent.com/104590925/213351349-7ece4228-ded8-4bb9-85da-cb0867d66707.jpg)
### EXPLANATION
#### As shown in the code above initially the import re statement imports the regular expressions library to the notebook
#### The count variable is initialised to 0
#### The string and the list of words are taken as the input
#### A Function is created to build a regex statement to match the pattern
#### The statement x = re.findall(r"((\w)\2*)", w)  will find matches of each letter in the word and store them in a list 
#### An empty string reg is created
#### for loop is created to access all the values stored in x
#### The statement reg = reg+"("+j[1]+"{3,}"+"|"+j[0]+")" will match expressions with minimum 3 and maximum infinite lettes of j
#### The return statement returns the expression back to the function
#### For loop is created for passing each word seperately
#### The starting and ending of the pattern are denoted by ^ and $
#### ^(h{3,}|h)(i{3,}|i)$ is an example of one of the patterns
#### If the pattern is found the count is incremented and finally the output is printed
