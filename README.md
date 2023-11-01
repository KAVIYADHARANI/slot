# Ex03 Time Table
## Date:01/11/2023

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
<html>
<head>
<title>Slot Timetable</title>
</head>
<body> 
<center>
<img src="logo.png" height="200" width="500">
</center>
<br>
<table align="center" border="2" width="5" cellspacing="2">
<caption> <b>SLOT TIME TABLE - KAVIYA D (23012396)</caption>

<tr align="center">
<th bgcolor="pink">Day/Time</th>
<th bgcolor="pink">Monday</th>
<th bgcolor="pink">Tuesday</th>
<th bgcolor="pink">Wednesday</th>
<th bgcolor="pink">Thursday</th>
<th bgcolor="pink">Friday</th>
</tr>
<tr>
<td bgcolor="pink">7-7:20</td>
<th bgcolor="cyan" colspan="3">Free Slot</th>
<td bgcolor="cyan">Tamil</td>
<td bgcolor="cyan">Free Slot</td>
</tr>
<tr>
<td bgcolor="pink">8-10</td>
<td bgcolor="cyan">Soft Skills</td>
<td bgcolor="cyan">Free Slot</td>
<td bgcolor="cyan">FWAD</td>
<td bgcolor="cyan">Mathematics</td>
<td bgcolor="cyan">Digital Electronics</td>
</tr>
<tr>
<td bgcolor="pink">10-12</td>
<td bgcolor="cyan">Python</td>
<td bgcolor="cyan">Mathematics</td>
<td bgcolor="cyan">Free Slot</td>
<td bgcolor="cyan">FWAD</td>
<td bgcolor="cyan">Free Slot</td>
</tr>
<tr>
<td bgcolor="pink">12-1</td>
<th bgcolor="cyan" colspan="5">Lunch</th>
</tr>
<tr>
<td bgcolor="pink">1-3</td>
<td bgcolor="cyan">Physics</td>
<td bgcolor="cyan">Free slot</td>
<td bgcolor="cyan">Digital Electronics</td>
<td bgcolor="cyan">Python</td>
<td bgcolor="cyan">FWAD</td>
</tr>
<tr>
<td bgcolor="pink">3-4</td>
<th bgcolor="cyan" colspan="4">Free Slot</th>
<td bgcolor="cyan">Physics</td>
</tr>
</table>
<br>
<table align="center" border="5" width="600" cellspacing="5">
<tr>
<th>S.No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td>1.</td>
<td>19AI301</td>
<td>Python Programming</td>
</tr>
<tr>
<td>2.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Development</td>
</tr>
<tr>
<td>3.</td>
<td>19EE404</td>
<td>Digital Electronics</td>
</tr>
<tr>
<td>4.</td>
<td>19EY701</td>
<td>Soft Skills</td>
</tr>
<tr>
<td>5.</td>
<td>19MA201</td>
<td>Calculus and Matrix Algebra</td>
</tr>
<tr>
<td>6.</td>
<td>19PH214</td>
<td>Physics for Quantum Computing</td>
</tr>
<tr>
<td>7.</td>
<td>19HS101</td>
<td>Heritage of Tamils</td>
</tr>
</table>
</body>
</html>

```

## OUTPUT

![Alt text](slot.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
