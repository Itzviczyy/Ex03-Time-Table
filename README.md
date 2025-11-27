# Ex.03_Slot_Time_Table

## AIM
To write a HTML webpage to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and insert HTML code.

### STEP 3
Create a simple table using `<table>` tag in HTML.

### STEP 4
Add header row using `<th>` tag.

### STEP 5
Add your timetable using `<td>` tag.

### STEP 6
Execute the program using `runserver` command.

## PROGRAM
```
html
<!DOCTYPE html>
<html>
<head>
    <title>Slot Timetable</title>
</head>
<body>

    <center>
        <img src="/static/logo.png" width="500">
        <h2>Slot Time-Table</h2>
        <h3>Vignesh G (212224230301)</h3>
    </center>

    <table border="1" cellpadding="10" align="center" bgcolor="cyan">
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
        </tr>

        <tr>
            <th>8-10</th>
            <td bgcolor="red">Web</td>
            <td>CN</td>
            <td>DBMS</td>
        </tr>

        <tr>
            <th>10-12</th>
            <td>Web</td>
            <td>CN</td>
            <td>DBMS</td>
        </tr>

        <tr align="center">
            <th>12-1</th>
            <td colspan="3">Lunch</td>
        </tr>

        <tr>
            <th>1-3</th>
            <td>Web</td>
            <td>CN</td>
            <td>DBMS</td>
        </tr>

        <tr>
            <th>3-5</th>
            <td>Web</td>
            <td>CN</td>
            <td>DBMS</td>
        </tr>
    </table>

</body>
</html>
```


### DEVELOPED BY: Vignesh G
### REGISTER NUMBER: 212224230301

## OUTPUT

<img width="635" height="445" alt="image" src="https://github.com/user-attachments/assets/443d2cb0-853c-4973-903b-1a7cb7101097" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
