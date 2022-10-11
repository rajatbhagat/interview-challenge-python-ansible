# interview-challenge-python-ansible

## Problem 1



Read the input.csv file using Python or Javascript/Typescript and convert it into json object

First, find the number of duplicate words in each column and output them in the format

Word - count

and then write it back into a .json file with the field names preserved/copied from the orginal input file.



## Problem 2

Write Ansible playbook to accept an input keyword string and using that search through the data pulled from

https://api.publicapis.org/entries

and print out the url name if a input string matches the API and/or description.


## Bonus Problem

Simulate the Linux "tail" command in Python. Add the below options as command line params to configure behaviour of the command.
```commandline
    -f,  Follow the output of the file. The commadn should not stop when it reaches the end. It 
    should waits for additional data.
    -n number , The number of lines to show in the output. 
    -r, The output is displayed in a reverse order 
```