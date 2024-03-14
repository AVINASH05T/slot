# Ex03 Time Table
## Date: 14.03.2023
## NAME: AVINASH T
## REG NO.: 212223230026

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
```c
<html>
      <head>
            <title>TIMETABLE</title>
      </head>
      <body>
            <center>
            <img src="logo.png" height="100" width="777">
            </center>
  <br>
   <table align="center" width="550" cellspacing="5" cellpadding="5" border="6" bgcolor="black">
   <caption><b><font face="algerian" size="5" color= "black">TIMETABLE - AVINASH T [212223230026]</font></b></caption>
   <tr align="center">
   <th bgcolor="COFFEE">DATE/TIME</th>
   <th bgcolor="yellow" >MONDAY
   <th bgcolor="LIGHTgreen">TUESDAY
   <th bgcolor="skyblue">WEDNESDAY
   <th bgcolor="oyster">THURSDAY
   <th bgcolor="pink">FRIDAY
   <th bgcolor="orange">SATURDAY</tr>
<tr align="center">
<th bgcolor="red">8-10</th>
<td colspan="4" bgcolor="WHITE">FREE SLOT</td>
<td bgcolor="PINK">FUNDAMENTALS OF WEB APPLICATION</td>
<td bgcolor="orange">PYTHON AND LINEAR ALGEBRA</td>
</tr>
<tr align="center">
<th bgcolor="green">10-12</th>
<td bgcolor="WHITE">FREE SLOT</td>
<td bgcolor="LIGHTGREEN">PYTHON AND LINEAR ALGEBRA</td>
<td bgcolor="SKYBLUE">CREATIVE SKILLS FOR COMMUNICATION</td>
<td bgcolor="OYSTER">INTRODUCTION TO ROBOTICS</td>
<td bgcolor="PINK">FUNDAMENTALS OF C PROGRAMMING</td>
<td bgcolor="ORANGE">PROGRAMMING MICROCONTROLLER</td>
</tr>
<tr>
<th bgcolor="GREY">12-01</th>
<td bgcolor="GREY"></td>
<td bgcolor="LIGHTGREEN" align="center"> MENTOR MEET</td>
<td colspan="6" align="center"bgcolor="GREY" > L U N C H</td>
</tr>
<tr>
<tr align="center">
<th bgcolor="BLUE">01-03</th>
<td bgcolor="yellow">INTRODUCTION TO ROBOTICS</td>
<td bgcolor="LIGHTGREEN">FUNDAMENTALS OF WEB APPLICATION</td>
<td bgcolor="WHITE">FREE SLOT</td>
<td bgcolor="OYSTER">FUNDAMENTALS OF WEB APPLICATION</td>
<td bgcolor="PINK">PYTHON AND LINEAR ALGEBRA</td>
<td bgcolor="WHITE">FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="GOLD">03-05</th>
<td bgcolor="YELLOW">FUNDAMENTALS OF C PROGRAMMING</td>
<td bgcolor="LIGHTGREEN">PROGRAMMING MICROCONTROLLER</td>
<td bgcolor="SKYBLUE">PYTHON AND LINEAR ALGEBRA</td>
<td colspan='3' bgcolor="WHITE">FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2" bgcolor="BLACK">
<tr align="center">
<th bgcolor="red">No.</th>
<th bgcolor="gold">Subject code</th>
<th bgcolor="pink">Subject Name</th>
</tr>
<tr>
<td align="center"bgcolor="YELLOW">1.</td>
<td align="center"bgcolor="yellow">19AI414</td>
<td bgcolor="yellow">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
</tr>
<tr>
<td align="center" bgcolor="SILVER">2.</td>
<td align="center"bgcolor="SILVER">19AI304</td>
<td bgcolor="SILVER">FUNDAMENTALS OF C PROGRAMMING(C PROGRAM)</td>
</tr>
<tr>
<td align="center"bgcolor="SKYBLUE">3.</td>
<td align="center"bgcolor="skyblue">19AI301C</td>
<td bgcolor="skyblue">PYTHON AND LINEAR ALGEBRA(PLA)</td>
</tr>
<tr>
<td align="center"bgcolor="LIGHTGREEN">4.</td>
<td align="center"bgcolor="lightgreen">19AI303</td>
<td bgcolor="lightgreen">INTRODUCTION TO ROBOTICS(ITR)</td>
</tr>
<tr>
<td align="center"bgcolor="PINK">5.</td>
<td align="center"bgcolor="PINK">19AI302</td>
<td bgcolor="PINK">PROGRAMMING MICROCONTROLLER(PMC)</td>
</tr>
<tr>
<td align="center"bgcolor="VIOLET">6.</td>
<td align="center"bgcolor="VIOLET">19EY701</td>
<td bgcolor="VIOLET">CREATIVE SKILLS FOR COMMUNICATION(CSC)</td>
</tr
</table>
</body>
</html>
```

## OUTPUT
![alt text](slot.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
