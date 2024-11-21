# rpa-challenge

The [RPA Challenge](https://rpachallenge.com/) is a website offering five distinct automation tasks, each progressively increasing in complexity compared to the previous one.
In each task, the objective is to complete it in the shortest possible time.
<br>
<br>

## 1 - Input Forms
For this challenge, I developed two distinct solutions.
<br>
<br>
The first solution involves creating **XPATHs** to locate all elements, which change position each time, and inputting the data into the corresponding target fields.
This method required **between 5000 and 6000 milliseconds** to execute, primarily due to the time needed to iterate through the file and populate the fields.
<br>
<br>
The second solution utilizes a JavaScript script executed within Selenium in Python. This approach accelerates the iteration on the page, making it 50 to 60 times faster compared to looping with XPATH selectors in Python.
This method required **between 85 and 110 miliseconds** to execute.
<br>
<br>

## 2 - Shortest Path
*under development*
