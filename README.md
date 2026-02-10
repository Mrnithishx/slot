# Ex02 Time Table
## Name:Nithish D M
## reg no:212224235001

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>Slot Schedule</title>
    </head>
    <body>
        <center>
            <img src="logo.png" title="SEC logo" width="1000" height="150">
        </center>
        <br>
            <table border="3" cellspacing="3" cellpadding="8" align="center" width="1000" bgcolor="pink">
            <caption><b><h3><u>SLOT TIME TABLE - RAAGHAVI S (25012715)</u></h3></b></caption>
            <tr bgcolor="violet">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="violet">8-10</th>
                <td>FREE SLOT</td>
                <td>CP</td>
                <td colspan="2">FREE SLOT</td>
                <td>FWAD</td>
                <td>CP</td>
            </tr>
            <tr align="center">
                <th bgcolor="violet">10-12</th>
                <td>FREE SLOT</td>
                <td>ENG</td>
                <td>FREE SLOT</td>
                <td>CP</td>
                <td>FWAD</td>
                <td>FWAD</td>
            </tr>
            <tr>
                <th align="center" bgcolor="violet">12-1</th>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr align="center">
                <th bgcolor="violet">1-3</th>
                <td colspan="2"align="center">FWAD</td>
                <td>MM</td>
                <td>FREE SLOT</td>
                <td>ENG</td>
                <td>CP</td>
            </tr>
            <tr align="center">
                <th bgcolor="violet">3-5</th>
                <td>ENG</td>
                <td colspan="2" align="center">FREE SLOT</td>
                <td>ENG</td>
                <td>CP</td>
                <td>FREE SLOT</td>
            </tr>
        </table>
        <br> <br>
        <table border="3" cellspacing="3" cellpadding="8" align="center" width="1000">
            <tr>
                <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI304</td>
                <td>Fundamentals of C Programming (CP)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19EN101</td>
                <td>Communicative English (ENG)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">ECA-M</td>
                <td>Mentor Meet (ECA-M)</td>
            </tr>
        </table>
     </body>
</html>

```

## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/99851418-b096-4ba7-b32e-a680e4737938" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
