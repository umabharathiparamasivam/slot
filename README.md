# Ex02 Time Table
## Date:22/11/26


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
slot.html
<html>
<head>
    <title>Slot Time Table</title>
 
</head>

<body>
<img src="logo.png" height="100" width="540" >

<h1>SLOT TIME TABLE - UMA BHARATHI P(26018686)</h1>

<table align="center" border="5" cellpadding="12" cellspacing="2">

<tr bgcolor="red">
    <th>Day/Time</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    <th>Saturday</th>
</tr>

<tr bgcolor="cyan">
    <th bgcolor="red">8-10</th>
    <td>CDS</td>
    <td>Python</td>
    <td>Python</td>
    <td colspan="3" align="center">FREE </td>
</tr>

<tr bgcolor="cyan">
    <th bgcolor="red">10-12</th>
    <td>Maths</td>
    <td>FWAD</td>
    <td colspan="2" align="center">FREE </td>
    <td>FWAD</td>
    <td>FREE </td>
</tr>

<tr bgcolor="cyan">
    <th bgcolor="red">12-1</th>
    <td colspan="6"  align="center">L U N C H</td>
</tr>

<tr bgcolor="cyan">
    <th bgcolor="red">1-3</th>
    <td>FWAD</td>
    <td>Maths</td>
    <td>FREE </td>
    <td>English</td>
    <td colspan="2" align="center">FREE </td>
</tr>

<tr bgcolor="cyan">
    <th bgcolor="red">3-5</th>
    <td>EDM</td>
    <td> Communicative English</td>
    <td>BEEE</td>
    <td>FREE </td>
    <td>EDM</td>
    <td>Python</td>
</tr>

</table>

<br><br>



<table align="center" style="text-align:center;" border="3" cellpadding="10" cellspacing="2">

<tr bgcolor="red">
    <th>S.No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
</tr>

<tr bgcolor="cyan">
    <td>1</td>
    <td>19EY708</td>
    <td>Career Development Skills(CDS)</td>
</tr>

<tr bgcolor="cyan">
    <td>2</td>
    <td>19AI301</td>
    <td>Python Programming</td>
</tr>

<tr bgcolor="cyan">
    <td>3</td>
    <td>19AI414</td>
    <td>Fundamentals of Web Application Development(FWAD)</td>
</tr>

<tr bgcolor="cyan">
    <td>4</td>
    <td>19MA201</td>
    <td>Calculus and Matrix Algebra</td>
</tr>

<tr bgcolor="cyan">
    <td>5</td>
    <td>19EN101</td>
    <td>Communicative English(CE)</td>
</tr>

<tr bgcolor="cyan">
    <td>6</td>
    <td>19EE305</td>
    <td>Basic Electrical,Electronics and Measurement Engineering(BEEE)</td>
</tr>

<tr bgcolor="cyan">
    <td>7</td>
    <td>19AI302</td>
    <td>Engineering Design and Modelling(EDM)</td>
</tr>

</table>



</body>
</html>


```


## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
