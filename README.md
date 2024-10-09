# Ex03 Time Table
### Date:
### Name:Loshini.G
### Register Number:212223220051
### Department:IT

## AIM:
To write a html webpage page to display your slot timetable.

## ALGORITHM:
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

## PROGRAM:

```html
<doctype! html>
    <html>
        <head>
            <title>
                slot timetable
            </title>
            <body>
                <center>
                    <img src="C:\Users\loshi\Downloads\logo.png" height="100"width="840">
                </center>
                <br>
                <table align="center" width="840" cellspacing="2" cellpadding="10" border="3" bgcolor="cornsilk">
                    <caption><b>SLOT TIME TABLE - Loshini.G (212223220051)</b></caption>
                    <tr align="center"bgcolor="indigo" style="color:ivory;font-style:italic">
                        <th>Day/Time</th>
                        <th>Monday</th>
                        <th >Tuesday</th>
                        <th>Wednesday</th>
                        <th>Thursday</th>
                        <th>Friday</th>
                        <th>Saturday</th>
                    </tr>
                    <tr align="center"bgcolor="lavenderblush" style="color:hotpink;font-style: italic;">
                        <th bgcolor="indigo" style="color:ivory">8-10</th>
                        <td>logic and combinatorics</td>
                        <td >Computer networks</td>
                        <td>Fundamentals of c programming</td>
                        <td>Basic electrical,electronics and measurement engineering</td>
                        <td>Reasoning ability</td>
                        <td>Fundamentals of web application development</td>
                     </tr>
                     <tr align="center" bgcolor="lavenderblush" style="color:hotpink;font-style: italic;">
                        <th bgcolor="indigo" style="color:ivory">10-12</th>
                        <td>Fundamentals of c programming</td>
                        <td>Freeslot</td>
                        <td>Introduction to Iot</td>
                        <td>Fundamentals of web application development</td>
                        <td>Operating system</td>
                        <td>Introduction to Iot</td>
                     </tr>
                     <tr bgcolor="aliceblue" style="color:black;font-style: italic">
                        <th bgcolor="indigo" style="color:ivory">12-1</th>
                        <td colspan ="6", align="center"><b>Lunch</b> </td>
                     </tr>
                     <tr align="center"bgcolor="lavenderblush" style="color:hotpink;font-style: italic">
                        <th bgcolor="indigo" style="color:ivory">1-3</th>
                        <td colspan="2">Freeslot</td>
                        <td> Mentor meet</td>
                        <td>Freeslot</td>
                        <td>Basic electrical,electronics and measurement engineering</td>
                        <td>Freeslot</td>
                     </tr >
                     <tr align="center"bgcolor="lavenderblush" style="color:hotpink;font-style: italic">
                        <th bgcolor="indigo" style="color:ivory;font-style: italic">3-5</th>
                        <td >Fundamentals of web application development</td>
                        <td>Freeslot</td>
                        <td >Computer Networks</td>
                        <td>Operating system</td>
                        <td>Freeslot</td>
                        <td >Logic and Combinatorics</td>
                     </tr>


                </table>
                <br>
                <table align="center" width="840" cellspacing="2" cellpadding="10" border="3" bgcolor="cyan">
                     <tr>
                        <th>S.No</th>
                        <th>Subject Code</th>
                        <th>Subject Name</th>
                     </tr>
                     <tr bgcolor="oldlace" style="color:midnightblue">
                        <td >1.</td>
                        <td >19MA206</td>
                        <td>Logic and Combinatorics</td>
                    
                     </tr>
                     <tr>
                        <td>2.</td>
                        <td>19AI304</td>
                        <td>Fundamentals of C programming</td>
                     </tr>
                     <tr bgcolor="oldlace" style="color:midnightblue">
                        <td >3.</td>
                        <td>19AI414</td>
                        <td>Fundamentals of web application development</td>
                     </tr>
                     <tr>
                        <td >4.</td>
                        <td >19CS406</td>
                        <td >Computer Networks</td>
                     </tr>
                     <tr bgcolor="oldlace" style="color:midnightblue">
                        <td>5.</td>
                        <td>19AM508</td>
                        <td>Introduction to IOT</td>
                     </tr>
                     <tr>
                        <td>6.</td>
                        <td>19EE305</td>
                        <td>Basic electrical,electronics and measurement engineering</td>
                     </tr>
                     <tr bgcolor="oldlace" style="color:midnightblue">
                        <td>7.</td>
                        <td>19CS405</td>
                        <td>Operating System</td>
                        
                     </tr>
                     <tr>
                        <td>8.</td>
                        <td>19EY709</td>
                        <td>Reasoning Ability</td>
                        
                     </tr>
                     <tr bgcolor="oldlace" style="color:midnightblue">
                        <td>9</td>
                        <td>ECA-M</td>
                        <td>Mentor meet</td>
                        
                     </tr>
                </table>
            </body>
        </head>
    </html>
```

## OUTPUT:
![Screenshot 2024-10-09 134436](https://github.com/user-attachments/assets/a6a93f3c-6954-4181-ac9a-5486ee77aa68)
![Screenshot 2024-10-09 134447](https://github.com/user-attachments/assets/d2a7012d-539b-4fb4-a8cc-cf19bb5a2735)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
