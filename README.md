# Ex03 Time Table

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

## CODE
```
html
<html>
<head>
  <title>SLOT TIME TABLE- Divakar R(22008432)</title>
	
  <style>
    table{
       border-collapse:collapse;
	text alien: centre;
	margin: 2px ;
	}
	th,td{
	width: 5%;
	border:2px solid;
     }
   </style>
</head>
<body>
<style>
    center text
          {
        text alien: center;
           }   
   </style>
     <body>
       <div class="centre-text">
<p>SLOT TIME TABLE-Divakar(22008432)</p>
          </div>
   <table>
     <tr>
        <th bgcolor="yellow">Day/time</th>
        <th bgcolor="yellow">Monday</th>
	<th bgcolor="yellow">Tuesday</th>
	<th bgcolor="yellow">Wednesday</th>
	<th bgcolor="yellow">Thursday</th>
	<th bgcolor="yellow">Friday</th>
     </tr>
      <tr>
        <th bgcolor="yellow">8-10</th>
	<td colspan="3" bgcolor="blue">FREE SLOT</td>
        <th bgcolor="blue">PHY</th>
        <th bgcolor="blue">CHE</th>
       </tr>
      <tr>
	<th bgcolor="yellow">10-12</th>
	<th bgcolor="blue">GER</th>
	<th bgcolor="blue">FREE SLOT</th>
	<th bgcolor="blue">FWAD</th>
	<th bgcolor="blue">FWAD</th>
	<th bgcolor="blue">PHY</th>
	</tr>
      <tr>
	<th bgcolor="yellow">12-1</th>
	<td colspan="5" bgcolor="blue">LUNCH</td>
	</tr>
      <tr>
        <th bgcolor="yellow">1-3</th>
	<td colspan="2" bgcolor="green">FREE SLOT</td>
	<th bgcolor="blue">MAT</th>
	<th bgcolor="blue">MAT</th>
	<th bgcolor="blue">SS</th>
	</tr>
      <tr>
        <th bgcolor="yellow">3-5</th>
	<td colspan="2" bgcolor="green">FREE SLOT</td>
	<th bgcolor="blue">MAT</th>
	<th bgcolor="blue">MAT</th>
	<th bgcolor="blue">SS</th>
       </tr>
     </table>
    </body>
</html>

<html>
<head>
<style>
    table{
	border-collapse:collapse:collapse;
	text alien:center;
	margin:2px;
	}
	th,td{
	width:1%;
	border:2px solid;
 	}
</style>
</head>
<body>
      <table>
	<tr>
	<th>S.NO</th>
	<th>Subject code</th>
	<th>Subject Name</th>
	</tr>
	<tr>
	<th>1.</th>
	<th>19AI414</th>
	<th>Fundamentals of Web Application Development(FWAD)</th>
	</tr>
	<tr>
	<th>2.</th>
	<th>19EN612</th>
	<th>German Basic(GER)</th>
	</tr>
	<tr>
	<th>3.</th>
	<th>19PH206</th>
	<th>Physics of Information Technology(PHY)</th>
	</tr>
	<tr>
	<th>4.</th>
	<th>19CY205</th>
	<th>Principles of Chemistry in Engineering(CHE)</th>
	</tr>
	<tr>
	<th>5.</th>
	<th>19MA201</th>
	<th>Calculus and Matrix Algebra(MAT)</th>
	</tr>
	<tr>
	<th>6.</th>
	<th>19EY701</th>
	<th>Soft Skills(SS)</th>
	</tr>
</table>
</body>
</html>
```

## OUTPUT
![Output](Out.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
