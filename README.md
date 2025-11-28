# Ex03 Time Table
# Date: 28.11.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
<head>
    <title>Time Table</title>
    <style>
        table, th, td {
            background-color: blanchedalmond; 
            color: rgb(105, 34, 34);
            border: 3px solid black;
            border-collapse: collapse;
            text-align: center;
            padding: 5px;
            font-style: italic;
            margin-left: auto;
            margin-right: auto;
            font-size: 18px;
        }
        span {
            writing-mode: vertical-lr;
            text-orientation: upright;
            letter-spacing: 10px;
        }
    </style>
</head>
<body>
    <center>
        <img src="logo.png" height="180" width="680">
    </center>
    <table>
        <caption><h2>Slot Time Table - Lothika M (25006771)</h2></caption>

        <caption>___________________________________________________________________________________________</caption>
        <tr>
            <th>Day/time</th>
            <th>8:00-10:00</th>
            <th>10:00-12:00</th>
            <th>12:00-1:00</th>
            <th>1:00-3:00</th>
            <th>3:00-5:00</th>
        </tr>
        <tr>
            <th>Monday</th>
            <td>C programming</td>
            <td>FREE SLOT</td>
            <th rowspan="6"><span>LUNCH</span></th>
            <td>FREE SLOT</td>
            <td>Communicative English</td>
        </tr>
        <tr>
            <th>Tuesday</th>
            <td colspan="2">FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <th>Wednesday</th>
            <td>C programming</td>
            <td>FWAD</td>
            <td>Mentor Meet</td>
            <td>Communicative English</td>
        </tr>
        <tr>
            <th>Thursday</th>
            <td rowspan="2">FREE SLOT</td>
            <td>Communicative English</td>
            <td rowspan="3">C programming</td>
            <td rowspan="2">FREE SLOT</td>
        </tr>
        <tr>
            <th>Friday</th>
            <td>FWAD</td>
        </tr>
        <tr>
            <th>Saturday</th>
            <td colspan="2">FWAD</td>
            <td>Communicative English</td>
        </tr>
    </table>
    <table>
        <caption>_________________________________________________________________________</caption>
        <tr>
            <th>Si No</th>
            <th>subject code</th>
            <th>subject</th>
            <th>faculty</th>
        </tr>
        <tr>
            <th >1</th>
            <td>19AI304</td>
            <td>Fundamentals Of C Programming</td>
            <td>Trainer 1</td>
        </tr>
        <tr>
            <th>2</th>
            <td>19AI414</td>
            <td>Fundamentals Of Web Application Development</td>
            <td>Berlin Magthalin</td>
        </tr>
        <tr>
            <th>3</th>
            <td>19EN101</td>
            <td>Communicative English</td>
            <td>David Raja</td>
        </tr>
        <tr>
            <th>4</th>
            <td>-</td>
            <td>Mentor Meet</td>
            <td>Suguna Devi</td>
        </tr>
    </table>
</body>
</html>
```

# OUTPUT
![alt text](<slot time table-1.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
