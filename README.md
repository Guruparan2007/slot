# Ex03 Time Table
## Date:22.04.2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

```
<html>
    <br>
    <center>
        <img src="/static/logo.png" alt="LOGO" height="200" width="800"> 
    </center>
    <caption><font color="black" size="5"><b>SLOT TIMETABLE</b></font></caption>
    <br>
    <body ALIGN="CENTER">
    <table BORDER="2" CELLPADDING="20" CELLSPACING="5" align="CENTER" BGCOLOR="BLACK">
        <caption><font color="white" size="5"><b>TIMETABLE</b></font></caption>
        <tr bgcolor="black">
            <th><font COLOR="white" FACE="CURSIVE">DAY/TIME</font></th>
            <th><font COLOR="white" FACE="CURSIVE">8-10</font></th>
            <th><font COLOR="white" FACE="CURSIVE">10-12</font></th>
            <th><font COLOR="white" FACE="CURSIVE">LUNCH</font></th>
            <th><font COLOR="white" FACE="CURSIVE">1-3</font></th>
            <th><font COLOR="white" FACE="CURSIVE">3-5</font></th>
        </tr>

        <tr>
            <th bgcolor="black"><font color="white">MONDAY</font></th>
            <td bgcolor="gray"><font color="white">Free Period</font></td>
            <td bgcolor="gray"><font color="white">Python Programming</font></td>
            <td bgcolor="gray"><font color="white">-</font></td>
            <td bgcolor="gray"><font color="white">Communicative English</font></td>
            <td bgcolor="gray"><font color="white">Free Period</font></td>
        </tr>

        <tr>
            <th bgcolor="black"><font color="white">TUESDAY</font></th>
            <td bgcolor="gray"><font color="white">Free Period</font></td>
            <td bgcolor="gray"><font color="white">Principles of Chemistry</font></td>
            <td bgcolor="gray"><font color="white">-</font></td>
            <td bgcolor="gray"><font color="white">Operating System</font></td>
            <td bgcolor="gray"><font color="white">Free Period</font></td>
        </tr>

        <tr>
            <th bgcolor="black"><font color="white">WEDNESDAY</font></th>
            <td bgcolor="gray"><font color="white">Free Period</font></td>
            <td bgcolor="gray"><font color="white">Fundamentals of Web Development</font></td>
            <td bgcolor="gray"><font color="white">-</font></td>
            <td bgcolor="gray"><font color="white">Mentor Meet</font></td>
            <td bgcolor="gray"><font color="white">Operating System</font></td>
        </tr>

        <tr>
            <th bgcolor="black"><font color="white">THURSDAY</font></th>
            <td bgcolor="gray"><font color="white">Free Period</font></td>
            <td bgcolor="gray"><font color="white">Free Period</font></td>
            <td bgcolor="gray"><font color="white">-</font></td>
            <td bgcolor="gray"><font color="white">Principles of Chemistry</font></td>
            <td bgcolor="gray"><font color="white">Probability and Queuing Models</font></td>
        </tr>

        <tr>
            <th bgcolor="black"><font color="white">FRIDAY</font></th>
            <td bgcolor="gray"><font color="white">Free Period</font></td>
            <td bgcolor="gray"><font color="white">Communicative English</font></td>
            <td bgcolor="gray"><font color="white">-</font></td>
            <td bgcolor="gray"><font color="white">Python Programming</font></td>
            <td bgcolor="gray"><font color="white">Fundamentals of Web Development</font></td>
        </tr>

        <tr>
            <th bgcolor="black"><font color="white">SATURDAY</font></th>
            <td bgcolor="gray"><font color="white">Principles of Chemistry</font></td>
            <td bgcolor="gray"><font color="white">Python Programming</font></td>
            <td bgcolor="gray"><font color="white">-</font></td>
            <td bgcolor="gray"><font color="white">Python Programming</font></td>
            <td bgcolor="gray"><font color="white">Probability and Queuing Models</font></td>
        </tr>
    </table>
    </body>
</html>

<html>
    <body ALIGN="CENTER">
        <table BORDER="2" CELLPADDING="20" CELLSPACING="5" align="CENTER" BGCOLOR="WHITE">
            <caption><font color="black" size="5"><b>SUBJECT DETAILS</b></font></caption>
            <tr bgcolor="white">
                <th><font color="black" FACE="CURSIVE">S.No</font></th>
                <th><font color="black" FACE="CURSIVE">Subject Code</font></th>
                <th><font color="black" FACE="CURSIVE">Subject Name</font></th>
            </tr>
            <tr bgcolor="white">
                <td><font color="black">1</font></td>
                <td><font color="black">20AI303</font></td>
                <td><font color="black">Python Programming</font></td>
            </tr>
            <tr bgcolor="white">
                <td><font color="black">2</font></td>
                <td><font color="black">19AI404</font></td>
                <td><font color="black">Fundamentals of Web Development</font></td>
            </tr>
            <tr bgcolor="white">
                <td><font color="black">3</font></td>
                <td><font color="black">19CY510</font></td>
                <td><font color="black">Principles of Chemistry</font></td>
            </tr>
            <tr bgcolor="white">
                <td><font color="black">4</font></td>
                <td><font color="black">19AI304</font></td>
                <td><font color="black">Operating System</font></td>
            </tr>
            <tr bgcolor="white">
                <td><font color="black">5</font></td>
                <td><font color="black">19MA211</font></td>
                <td><font color="black">Probability and Queuing Models</font></td>
            </tr>
            <tr bgcolor="white">
                <td><font color="black">6</font></td>
                <td><font color="black">19CY516</font></td>
                <td><font color="black">Communicative English</font></td>
            </tr>
        </table>
    </body>
</html>
```


```
Developed by: GURUPARAN G
REG NO: 212224220030
```


## OUTPUT

![image](https://github.com/user-attachments/assets/6b3d9d0d-ddd7-46c3-91b7-19509d872b86)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
