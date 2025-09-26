# Ex03 Time Table
## Date:26.09.2025

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
    <head>
        <title>
            Slot Timetable
        </title>
    </head>
    <body>
        <img src="logo.png" width="700" height="100">
        <h1>Slot Timetable</h1>
        <h2>Dhanavishni(25016333)</h2>
        <table border="1" cellspacing="5" cellpadding="5" bgcolor="pink">
            <tr>
                <th bgcolor="lightblue">Date/Time</th>
                <th bgcolor="lightblue">Monday</th>
                <th bgcolor="lightblue">Tuesday</th>
                <th bgcolor="lightblue">Wednesday</th>
                <th bgcolor="lightblue">Thursday</th>
                <th bgcolor="lightblue">Friday</th>
                <th bgcolor="lightblue">Saturday</th>
            </tr>
            <tr>
                <th bgcolor="lightblue">8-10</th>
                <td colspan="2" align="center">FWAD</td>
                <td>ENG</td>
                <td>C Programming</td>
                <td>FWAD</td>
                <td>Free Slot</td>
            </tr>
            <tr>
                <th bgcolor="lightblue">10-12</th>
                <td>Free Slot</td>
                <td colspan="2" align="center">ENG</td>
                <td>Free Slot</td>
                <td colspan="2" align="center">ENG</td>
            </tr>
            <tr>
                <th bgcolor="lightblue">12-1</th>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr>
                <th bgcolor="lightblue">1-3</th>
                <td colspan="2" align="center">FWAD</td>
                <td>Mentor Meet</td>
                <td>C Programming</td>
                <td>ENG</td>
                <td>Free Slot</td>
            </tr>
            <tr>
                <th bgcolor="lightblue">3-5</th>
                <td colspan="2" align="center">C Programming</td>
                <td colspan="2" align="center">Free Slot</td>
                <td>C Programming</td>
                <td>Free Slot</td>
            </tr>
        </table>
        <br>
        <table border="1" cellspacing="3" cellpadding="5">
            <tr>
                <th>S.no</th>
                <th align='center'>Subject Code</th>
                <th align="center">Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>ECA-M</td>
                <td>Mentor Meet</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (27).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
