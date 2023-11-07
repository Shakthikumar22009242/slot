# Ex03 Time Table

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using <table> tag in html.

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
  <title>SLOT TIME TABLE- SHAKTHI KUMAR S(22009242)</title>
	
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
		<img src="logo.png">
       <div class="centre-text">
<p>SLOT TIME TABLE-SHAKTHI KUMAR S(22009242)</p>
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
        <th bgcolor="blue">STAT</th>
        <th bgcolor="blue">FREE</th>
		<th bgcolor="blue">STAT</th>
		<th bgcolor="blue">FWAD</th>
		<th bgcolor="blue">FREE</th>
       </tr>
      <tr>
	<th bgcolor="yellow">10-12</th>
	<th bgcolor="peach">FREE</th>
	<th bgcolor="peach">PQM</th>
	<th bgcolor="peach">PQM</th>
	<th bgcolor="peach">IOT</th>
	<th bgcolor="peach">SS</th>
	</tr>
      <tr>
	<th bgcolor="yellow">12-1</th>
	<td colspan="5" bgcolor="orange">LUNCH</td>
	</tr>
      <tr>
        <th bgcolor="yellow">1-3</th>
	<th bgcolor="green">OS</th>
	<th bgcolor="green">FREE</th>
	<th bgcolor="green">PMC</th>
	<th bgcolor="green">CS</th>
	<th bgcolor="green">FREE</th>
	</tr>
      <tr>
        <th bgcolor="yellow">3-5</th>
	<th bgcolor="blue">FREE</th>
	<th bgcolor="blue">FWAD</th>
	<th bgcolor="blue">FREE</th>
	<th bgcolor="blue">FREE</th>
	<th bgcolor="blue">PMC</th>
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
	<th>Fundamentals of Web Application Development (FWAD)</th>
	</tr>
	<tr>
	<th>2.</th>
	<th>19EE309</th>
	<th>Programming Microcontrollers (PMC)</th>
	</tr>
	<tr>
	<th>3.</th>
	<th>19AM504</th>
	<th>Introduction to IOT (IOT)</th>
	</tr>
	<tr>
	<th>4.</th>
	<th>19MA211</th>
	<th>Statistics and Numerical methods(SNM)</th>
	</tr>
	<tr>
	<th>5.</th>
	<th>19MA222</th>
	<th>Probability and Queuing models(PQM)</th>
	</tr>
	<tr>
	<th>6.</th>
	<th>19EY701</th>
	<th>Soft Skills(SS)</th>
	</tr>
	<tr>
	<th>5.</th>
	<th>19EY702</th>
	<th>Creative Skills for communication(CS)</th>
	</tr>
	<tr>
	<th>5.</th>
	<th>19CS405</th>
	<th>Operating systems(OS)</th>
	</tr>

</table>
</body>
</html></html>
```

## OUTPUT
![](WEB_03.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.