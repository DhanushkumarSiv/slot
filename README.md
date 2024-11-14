# Ex03 Time Table
## Date: 12/11/2024

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
    <title>
        timetable
    </title>
    <body>
        <img src = "logo.png" width="800" height="200"
        <h1 align ="left"> <b> SLOT TIMETABLE DHANUSH (24901013)</b>
            <table border ="1" cellspacing="15" cellpadding="2">
                <tr bgcolor ="yellow">
                    <th><b>Day/Time</b></th>
                    <th><b>Monday</b></th>
                    <th><b>Tuesday</b></th>
                    <th><b>Wednesday</b></th>
                    <th><b>Thursday</b></th>
                    <th><b>Friday</b></th>
                    <th><b>Saturday</b></th>

                </tr>
                <tr>
                    <td>8-10</td>
                    <td> </td>
                    <td> CD </td>
                    <td> Maths</td>
                    <td> </td>
                    <td> Web </td>
                    <td> EDM </td>

                </tr>
                <tr>
                    <td> 10-12 </td>
                    <td> EDM</td>
                    <td> DE</td>
                    <td> C </td>
                    <td> Math </td>
                    <td> C </td>
                    <td> </td>

                </tr>
                <tr>
                    <td> 12-1 </td>
                    <td colspan = "6" align="center"> <b> LUNCH </b></td>
                </tr>
                <tr>
                    <td> 1-3 </td>
                    <td> Web </td>
                    <td> Web </td>
                    <td> </td>
                    <td> </td>
                    <td> DE </td>
                    <td> Chemistry </td>
                </tr>
                <tr>
                    <td> 3-5</td>
                    <td> </td>
                    <td> </td>
                    <td> Chemistry </td>
                    <td> </td>
                    <td> </td>
                    <td> </td>
                </tr>

            </table>
            </h1>

    </body>
    
</html>
<br>
<html>
    <body>
        <table border="1" cellspacing="15" cellpadding="2">
            <caption><b>SUBJECTS </b></caption>
            <tr bgcolor="yellow">
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
                
            </tr>
            <tr>
                <td>1</td>
                <td> 19MA201</td>
                <td> Matrix and Vector Algebra</td>
            </tr>
            <TR>
                <td>2</td>
                <td>19EY708</td>
                <td>Career Development</td>
                
            </TR>
            <tr>
                <td>3</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>

            </tr>
            <tr>
                <td>4</td>
                <td>19CY205</td>
                <td>Chemistry</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Development</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19AI304</td>
                <td>C Programing</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19AI302</td>
                <td> Engineering Design and Modelling</td>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
