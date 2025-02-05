# Ex03 Time Table
## Date:05-11-2023

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
	<title>SLOT TIMETABLE</title>
      	<body>
        <center>
        <img src="/static/logo.png" height="100" width="540">
        </center>
		<table align="center" width="540" border="5" bgcolor="cyan" cellspacing="10" cell padding="6">
			<caption> SLOT TIMETABLE-GEDIPUDIDARSHANI(23004619)</caption>
			<tr align="center">
				<th bgcolor="yellow">Day/Time</th>
				<th bgcolor="yellow">8-10</th>
				<th bgcolor="yellow">10-12</th>
				<th bgcolor="yellow">12-1</th>
				<th bgcolor="yellow">1-3</th>
				<th bgcolor="yellow">3-5</th>
			</tr>
			<tr>
				<th bgcolor="yellow">Monday</th>
				<td>ENG</td>
				<td>CHE</td>
				<td>LUNCH</td>
				<td>FREE SLOT</td>
				<td>FREE SLOT</td>
			</tr>
			<tr>
				<th bgcolor="yellow">Tuesday</th>
				<td>ENG</td>
				<td>FREE SLOT</td>
				<td>LUNCH</td>
				<td>CHE</td>
				<td>PHY</td>
			</tr>
			<tr>
				<th bgcolor="yellow">Wednesday</th>
				<td>FWAD</td>
				<td>MAT</td>
				<td>LUNCH</td>
				<td>DE</td>
				<td>FREE SLOT</td>
			</tr>
			<tr>
				<th bgcolor="yellow">Thursday</th>
				<td>SOFTSKILL</td>
				<td>FWAD</td>
				<td>LUNCH</td>
				<td>PHY</td>
				<td>FREE SLOT</td>
			</tr>
			<tr>
				<th bgcolor="yellow">Friday</th>
				<td>DE</td>
				<td>MAT</td>
				<td>LUNCH</td>
				<td>FWAD</td>
				<td>FREE SLOT</td>
			</tr>
			
		</table>
	</body>
</html>

<html>
	<title>COURSE</title>
      	<body>
		<table align="center" width="540" border="5" cellspacing="10" cell padding="6">
			
			<tr align="center">
				<th>S.NO</th>
				<th>Subject Code</th>
				<th>Subject Name</th>
			</tr>
			<tr>
				<th>1</th>
				<td>19AI414</td>
				<td>Fundamentals of Web Application Development(FWAD)</td>
			</tr>
			<tr>
				<th>2</th>
				<td>19CY205</td>
				<td>Principles of Chemistry in Engineering(CHE)</td>
			</tr>
			<tr>
				<th>3</th>
				<td>19EE404</td>
				<td>Digital Electronics(DE)</td>
			</tr>
			<tr>
				<th>4</th>
				<td>19EN101</td>
				<td>Communicative English(ENG)</td>
			</tr>

			<tr>
				<th>5</th>
				<td>19EY701</td>
				<td>Soft Skills</td>
			</tr>
			<tr>
				<th>6</th>
				<td>19MA222</td>
				<td>Probability and Queueing Models(MAT)</td>
			</tr>
			<tr>
				<th>7</th>
				<td>19PH214</td>
				<td>Physics for Quantum Computing(PHY)</td>
			</tr>
		</table>
	</body>
</html>
	
```

## OUTPUT
![Alt text](<Screenshot (18).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
