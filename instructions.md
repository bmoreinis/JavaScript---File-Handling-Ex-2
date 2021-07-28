# Exercise 2: Reading data from a file

### Reading from a text file into separate arrays

Here's an exercise that uses the same HTML and JavaScript template as in Demo 2. Only the function processContents() needs to be different.

'friends.txt' is a text file which stores the name of friends planning a holiday together. Each line of the text file is formatted as follows (forename, surname, town):

```
Matthew Reid Edinburgh\n
```

To store each friend’s forename, surname and town in three arrays called "forenames", "surnames" and "towns" we would have to:

- split the large string from reader.result into separate array elements using .split('\n')
- split each string element into three separate elements using .split(' ')
- append each new element to one of the three arrays

Here's the example data fila
```
Matthew Reid Edinburgh
Niall Dowds Dundee
Emir Duman Glasgow
Lewis Carter Arran
Steven Moyles Stornoway
```

### Instructions

Save a copy of the 'friends.txt' file to your local computer.

Using the techniques you saw in the Example 2 code, write an index.html page and a script.js file that will read the data from the file and then output, using alerts, the fornames, surnames and towns, for example:
```
Matthew,Niall,Emir,Lewis,Steven
```
```
Reid,Dowds,Duman,Carter,Moyles
```
```
Edinburgh,Dundee,Glasgow,Arran,Stornoway
```

Note that the data in the file is separated by spaces but the ouput data is comma separated.


