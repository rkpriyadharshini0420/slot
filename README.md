# Ex03 Time Table
## Date:15-03-2024

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
<title> My Time Table </title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
<table border="2" cellspacing="5" cellpading="5">
<caption>SLOT TIMETABLE - PRIYADHARSHINI(212223040155)</caption>
<tr>
<th bgcolor="green">Day/Time</th>
<th bgcolor="green">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="green">Wednesday</th>
<th bgcolor="green">Thursday</th>
<th bgcolor="green">Friday</th>
</tr>
<tr>
<td bgcolor="green">8-10</td>
<td bgcolor="pink">BEEE</td>
<td bgcolor="pink">C</td>
<td bgcolor="pink">chemistry</td>
<td bgcolor="pink">free</td>
<td bgcolor="pink">FWAD</td>
</tr>
<tr>
<td bgcolor="green">10-12</td>
<td bgcolor="pink">free</td>
<td bgcolor="pink">free</td>
<td bgcolor="pink">CN</td>
<td bgcolor="pink">C</td>
<td bgcolor="pink">Creative Skills</td>
</tr>
<tr>
<td bgcolor="green">12-1</td>
<td colspan="5" bgcolor="red">----------------LUNCH TIME----------------</td>
</tr>
<tr>
<td bgcolor="green">1-3</td>
<td bgcolor="pink">maths</td>
<td bgcolor="pink">FWAD</td>
<td bgcolor="pink">free</td>
<td bgcolor="pink">FWAD</td>
<td bgcolor="pink">chemistry</td>
</tr>
<tr>
<td bgcolor="green">3-5</td>
<td colspan="3" bgcolor="pink">free</td>
<td bgcolor="pink">OS</td>
<td bgcolor="pink">maths</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Developement(FWAD)</td>
</tr>
<tr>
<td>2.</td>
<td>19CS405</td>
<td>Computer Networks(CN)</td>
</tr>
<tr>
<td>3.</td>
<td>19EE305</td>
<td>Basic Electrical Electronics and Measurement Engineering(BEEE)</td>
</tr>
<tr>
<td>4.</td>
<td>19MA206</td>
<td>Logics and Combinatorics(maths)</td>
<tr>
<td>5.</td>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering(chemistry)</td>
</tr>
<tr>
<td>6.</td>
<td>19CS406</td>
<td>Operating System(OS)</td>
</tr>
<tr>
<td>7.</td>
<td>19EY702</td>
<td>Creative Skills for Communication(creative skills)</td>
</tr>
<tr>
<td>8.</td>
<td>19AI305</td>
<td>Advanced C Programming(C)</td>
</tr>
</table>
</center>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-18 195224.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
