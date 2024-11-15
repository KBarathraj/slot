# Ex03 Time Table
## Date:15/11/2024

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
 <body>
 <img src="logo.png" alt="" height="200" width="1200">

<table border="1" cellpadding="10">
    <caption>Slot Time Table - K Barathraj (24001402)</caption>
    
    <tr bgcolor="cyan">
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
    </tr>
    <tr bgcolor="yellow">
        <td bgcolor="red">8-10</td>
        <td>FREE</td>
        <td>FWAD</td>
        <td>PLA</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>CE</td>
    </tr>
    <tr bgcolor="yellow">
        <td bgcolor="red">10-12</td>
        <td>BEEE</td>
        <td>BEEE</td>
        <td>CE</td>
        <td>PLA</td>
        <td>PQC</td>
        <td>PLA</td>
    </tr>
    <tr bgcolor="red">
        <td>12-1</td>
        <td colspan="6" align="center" bgcolor="yellow">           <b>LUNCH</b>
        </td>
    </tr>
    <tr bgcolor="yellow">
        <td bgcolor="red">1-3</td>
        <td>CD</td>
        <td>PLA</td>
        <td>MM</td>
        <td>PQC</td>
        <td>FWAD</td>
        <td>FWAD</td>
    </tr>
    
    

</table>

<br>
<br>


<table border="1" cellpadding="10">
    <tr>
        <th>S.NO</th>
        <th>Course Code</th>
        <th>Course Name</th>
        
    </tr>
    <tr>
        <td>1.</td>
        <td>19AI301C</td>
        <td>Python and Linear Algebra(PLA)</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development(FWAD)</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>SH3214</td>
        <td>Physics for Quantum Computing(PQC)</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>19EY308</td>
        <td>Career Development(CD)</td>
    </tr>
    <tr><td>5.</td>
    <td>19EN101</td>
    <td>Communicative English(CE)</td></tr>
    <tr>
        <td>6.</td>
        <td>ECAM-SCOFT</td>
        <td>Mentor Meet(MM)</td>
    </tr>
    <tr>
        <td>7.</td>
        <td>19EE305</td>
        <td>Basic Electrical,Electronic and Measurement Engineering(BEEE)</td>
    </tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (5).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.