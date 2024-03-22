# Ex03 Time Table
## Date:
22/03/24
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
<!DOCTYPE html>
<head>
    <title>SEC SLOT TIMETABLE</title>
</head>
<center>
<img src="image.png" width='600'align="center">
</center>
<body>
    <table BORDER='3' width='600'bgcolor='white' cellspacing='3' align="center">
        <CAPTION align="above">SLOT TIMETABLE- SHRIKRISHNA V(212223040198)</CAPTION>
        <tr>
            <th align="center" bgcolor="lightcoral">Day/Time</th>
            <th align="center" bgcolor="lightcoral">Monday</th>
            <th align="center" bgcolor="lightcoral">Tuesday</th>
            <th align="center" bgcolor="lightcoral">Wednesday</th>
            <th align="center" bgcolor="lightcoral">Thursday</th>
            <th align="center" bgcolor="lightcoral">Friday</th>
            <th align="center" bgcolor="lightcoral">Saturday</th>
        </tr>

        <tr>
            <th align="center" bgcolor="lightcoral">8-10</th>
            <td align="center" bgcolor="lightskyblue" colspan="2">FREE SLOT</td>
            <td align="center" bgcolor="lightskyblue">FWAD</td>
            <td align="center" bgcolor="lightskyblue">FREE SLOT</td>
            <td align="center" bgcolor="lightskyblue">EXPERT SYSTEMS</td>
            <td align="center" bgcolor="lightskyblue">PROBABILITY AND QUEUEING MODELS</td>
        </tr>

        <tr>
            <th align="center" bgcolor="lightcoral">10-12</th>
            <td align="center" bgcolor="lightskyblue">FREE SLOT</td>
            <td align="center" bgcolor="lightskyblue">FWAD</td>
            <td align="center" bgcolor="lightskyblue">FREE SLOT</td>
            <td align="center" bgcolor="lightskyblue">PROBABILITY AND QUEUEING MODELS</td>
            <td align="center" bgcolor="lightskyblue">FUNDAMENTALS OF C PROGRAMMING</td>
            <td align="center" bgcolor="lightskyblue">FREE SLOT</td>
        </tr>

        <tr>
            <th align="center" bgcolor="lightcoral">12-1</th>
            <td align="center" bgcolor="lightskyblue" colspan="6">LUNCH</td>
        </tr>

        <tr>
            <th align="center" bgcolor="lightcoral">1-3</th>
            <td align="center" bgcolor="lightskyblue">FWAD</td>
            <td align="center" bgcolor="lightskyblue">PHYSICS FOR QUANTUM COMPUTING</td>
            <td align="center" bgcolor="lightskyblue">HRM</td>
            <td align="center" bgcolor="lightskyblue">EDM</td>
            <td align="center" bgcolor="lightskyblue">HRM</td>
            <td align="center" bgcolor="lightskyblue">FREE SLOT</td>
        </tr>


        <tr>
            <th align="center" bgcolor="lightcoral">3-5</th>
            <td align="center" bgcolor="lightskyblue">FUNDAMENTALS OF C PROGRAMMING</td>
            <td align="center" bgcolor="lightskyblue">EDM</td>
            <td align="center" bgcolor="lightskyblue">FREE SLOT</td>
            <td align="center" bgcolor="lightskyblue">CREATIVE SKILLS FOR COMMUNICATION</td>
            <td align="center" bgcolor="lightskyblue" >FREE SLOT</td>
            <td align="center" bgcolor="lightskyblue" >HRM</td>
        </tr>
    </table>

    <table border="3" width="600" cellspacing="3" cellpaddling="3" align="center">

        <tr>
            <th align="center">S.NO</th>
            <th align="center">SUBJECT CODE</th>
            <th align="center">subject name</th>
        </tr>

        <tr>
            <td align="center">1</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamental of Web Application Development(FWAD)</td>
        </tr>

        <tr>
            <td align="center">2</td>
            <td align="center">19AI302</td>
            <td align="center">Engineering designing and modelling</td>
        </tr>

        <tr>
            <td align="center">3</td>
            <td align="center">19AI304</td>
            <td align="center">Fundamentals of C programming</td>
        </tr>

        <tr>
            <td align="center">4</td>
            <td align="center">19AI521</td>
            <td align="center">Expert systems</td>
        </tr>

        <tr>
            <td align="center">5</td>
            <td align="center">19EY702</td>
            <td align="center">Creative skills for communication</td>
        </tr>

        <tr>
            <td align="center">6</td>
            <td align="center">19MA222</td>
            <td align="center">Probability and Queueing models</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19MS156</td>
            <td align="center">Human resource management and team building</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19PH214</td>
            <td align="center">Physics for quantum computing</td>
        </tr>
    </body>
    </html>
```

## OUTPUT
![image](https://github.com/Wkrish28/slot/assets/144295230/7ff4e549-45c9-4ce2-94d0-6d700d74beca)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
