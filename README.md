# Ex03 Time Table
## Date:14/03/2024

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
        <title>My Time Table</title>
    </head>
    <body>
        <center>
        <img src="logo.png"  height="150" width="1000">
        </center>
        <table align="center" border="5" cellspacing="5" cellpadding="5" width="540" height="150">
            <h1 align="center">SLOT TIME TABLE-CH.GEETHIKA(212221040032)</h1>
        
            <tr align="center" bgcolor="blue">
                <th >Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="green">
                <th bgcolor="blue">8-10</tH>
                <td>MAD</td>
                <td>FREE SLOT</td>
                <td>MPMC</td>
                <td>MAD</td>
                <td>WEB</td>
                <td>FREE SLOT</td>
            </tr>
            <tr bgcolor="green">
                <th bgcolor="blue">10-12</th>
                <td>FREE SLOT</td>
                <td>SPM</td>
                <td>FREE SLOT</td>
                <td>SPM</td>
                <td>MPMC</td>
                <td>INTRO TO DS</td>
            </tr>
            <tr bgcolor="green">
                <th bgcolor="blue">12-1</th>
                <th colspan="6">LUNCH BREAK</th>
            </tr>
           
            <tr bgcolor="green">
                <th bgcolor="blue">1-3</th>
                <td>FREE SLOT</td>
                <td>WEB</td>
                <td>AI</td>
                <td>WEB</td>
                <td colspan="2">FREE SLOT</td>
                
            </tr>
            <tr bgcolor="green">
                <th bgcolor="blue">3-5</th>
                <td>AI</td>
                <td>INTRO TO DS</td>
                <td colspan="2">FREE SLOT</td>
                
                <td>COMPANY SPECIFIC</td>
                <td>FREE SLOT</td>
            </tr>
         </table>
         <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">

           <tr align="center">
           <th>S.NO.</th>
           <th>SUBJECT CODE</th>
           <th>SUBJECT NAME</th>
           </tr>
           <tr>
           <td align="center">1.</td>
           <td align="center">19AI414</td>
           <td>FUNDAMENTALS OF WEB APPLICATION(WEB)</td>
           </tr>
           <tr>
           <td align="center">2.</td>
           <td align="center">19EC408</td>
           <td>MICRO PROCESSOR MICRO CONTROLLER(MPMC)</td>
           </tr>
           <tr>
           <td align="center">3.</td>
           <td align="center">19EY706</td>
           <td>COMPANY SPECIFIC ASSESMENTS AND EMPLOYABILITY</td>
           </tr>
           <tr>
           <td align="center">4.</td>
           <td align="center">19CS413</td>
           <td>ARTIFICIAL INTELLIGENCE(AI)</td>
           </tr>
           <tr>
           <td align="center">5.</td>
           <td align="center">19AI403</td>
           <td>INTORDUCTION TO DATASCIENCE</td>
           </tr>
           <tr>
           <td align="center">6.</td>
           <td align="center">19CS414</td>
           <td>MOBILE APPLICATION DEVOLOPMENT(MAD)</td>
           </tr>
           <tr>
            <td align="center">7.</td>
            <td align="center">19CS504</td>
            <td>SOFTWARE PROJECT MANAGMENT(SPM)</td>
            </tr>
           </table>
    </body>
</html>


## OUTPUT
![alt text](<Screenshot (331).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
