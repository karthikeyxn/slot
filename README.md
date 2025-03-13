# Ex03 Time Table
## Date:

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
<html>
	<head>
		<title>
			Software Companies
		</title>


	</head>
	<body align="center" bgcolor="skyblue" >
		 <center>
            <img src= "logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="yellow">
			<caption>SLOT TIME TABLE- Hariharan A (212223110013) </caption>
            <br>
			<tr>
				<th bgcolor="lightgray"> Day/Time </th>
				<th bgcolor="lightgray"> Monday </th>
				<th bgcolor="lightgray"> Tuesday </th>
                <th bgcolor="lightgray"> Wednesday </th>
                <th bgcolor="lightgray"> Thursday </th>
                <th bgcolor="lightgray"> Friday </th>
                <th bgcolor="lightgray"> Saturday </th>
			</tr>
			<tr>
				<th bgcolor="sky blue"> 8-10 </td>
                <td> Free SLOT </td>
                <td> ENG </td>
                <td> FWAD </td>
                <td> EMBD </td>
                <td> EMBD </td>
                <td> MATH </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 10-12 </th>
				<td> BEEE </td>
                <td> FWAD </td>
                <td> PHY </td>
                <td> MATH </td>
                <td> FUND OF C </td>
                <td> ENG </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 1-3 </th>
                <td> FWAD </td>
                <td> PRG MICR </td>
                <td> CRT SKILLS </td>
                <td> BEEE </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 3-5 </td>
                <td> FUND OF C </td>
                <td> PHY </td>
                <td> PRG MICR </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
			</tr>
			</table>
            <br>
            <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="pink">
                <br>
                <tr>
                    <th align="center"> S.No </th>
                    <th align="center"> Subject Code </th>
                    <th align="center"> Subject Name </th>
                </tr>
                <tr>
                    <th> 1. </td>
                    <td align="center"> 19EE305 </td>
                    <td align="center"> Basic electrical,electronics and measurement engineering (BEEE) </td>
                </tr>
                <tr>
                    <th align="center"> 2. </td>
                    <td align="center"> 19AI414 </td>
                    <td align="center"> Fundamentals of web applications (FWAD) </td>
                </tr>
                <tr>
                    <th align="center"> 3. </td>
                    <td align="center"> 19AI304 </td>
                    <td align="center"> Fundamentals of C programming (FUND OF C) </td>
                </tr>
                <tr>
                    <th align="center"> 4. </td>
                    <td align="center"> 19EN101 </td>
                    <td align="center"> English (ENG) </td>
                </tr>
                <tr>
                    <th align="center"> 5. </td>
                    <td align="center"> 19EE309 </td>
                    <td align="center"> Porgramming Microcontrollers (PRG MICR) </td>
                </tr>
                <tr>
                    <th align="center"> 6. </td>
                    <td align="center"> 19PH214 </td>
                    <td align="center"> Physics (PHY) </td>
                </tr>
                <tr>
                    <th align="center"> 7. </td>
                    <td align="center"> 19CS542 </td>
                    <td align="center"> Embeded board design (EMBD) </td>
                </tr>
                <tr>
                    <th align="center"> 8. </td>
                    <td align="center"> 19EY702 </td>
                    <td align="center"> Creative skills for communication (CRT SKILLS) </td>
                </tr>
                
                </table>
	</body>

</html>


## OUTPUT
![Screenshot 2025-03-13 092710](https://github.com/user-attachments/assets/c9cc060f-1679-470c-85ee-c13d7df98175)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
