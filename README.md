# Ex02 Time Table
# Date:28.11.2025
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
<html lang="en">
    {% load static %}
    <head>
        <title>Timetable</title>
        <link rel="icon" href="{% static 'ICON.JPG.jpeg' %}">
        <style>
            table,th,td{
                border:2px solid black;
                border-collapse:collapse;
                text-align:center;
                padding: 12px; 
                margin:auto;
                width:auto;
                font-size: 20px;
            }
            table{
                background-color:whitesmoke;
                color:rgb(14, 104, 137);
            }
            .Rithanya{
                background-color:whitesmoke;
                color:rgb(175, 39, 66);
                background: linear-gradient(90deg,whitesmoke,whitesmoke);

            }
            span{
                writing-mode: vertical-rl;
                text-orientation: upright;
                letter-spacing: 40px;
                padding-top: 30px;
            }
            img{
                display: block;
                margin-left:auto;
                margin-right: auto;
                height: auto;
                width:55%;
            }
            body{
                background-image: url("{% static 'Light Wallpaper iPhone.jpg' %}");
                background-repeat: no-repeat;
                background-size: cover;
                background-position: center;
            }
            class{
                background: linear-gradient(90deg,rgb(211, 222, 227),rgb(200, 225, 234));
            }
            .head{
                background: linear-gradient(180deg,rgb(220, 224, 227),white,rgb(220, 224, 227)) ;
            }
            .red{
             background: linear-gradient(180deg,rgb(246, 198, 198),rgb(245, 246, 247),rgb(246, 206, 206) ) ;  
            }
        </style> 
    </head>
    <body>
        <img src="{% static 'SEC_Header.png' %}">
        <table>
            <caption style="color: black; font-size: 25px;">TIME TABLE - RITHANYA L(25013009)</caption>
            <tr class="head">
                <th> 📅DAY/⌛TIME </th>
                <th> 8-10 </th>
                <th> 10-12 </th>
                <th>12-1</th>
                <th> 1-3 </th>
                <th> 3-5 </th>
            </tr>
            <tr>
                <td class="head"> Monday </td>
                <td colspan="2"> <class>Free Slot</class> </td>
                <td style="background: linear-gradient(180deg,rgb(220, 224, 227),white,rgb(220, 224, 227))", rowspan="6"> <span>LUNCH</span> </td>
                <td> C Programming </td>
                <td> English </td>
            </tr>
            <tr>
                <td class="head"> Tuesday </td>
                <td> <class>Free Slot</class> </td>
                <td> English </td>
                <td> FWAD </td>
                <td> <class>Free Slot</class> </td>
            </tr>
             <tr>
                <td class="head"> Wednesday </td>
                <td> <class>Free Slot</class> </td>
                <td> FWAD </td>
                <td> <class>Free Slot</class> </td>
                <td> C Programming </td>
            </tr>
            <tr>
                <td class="head"> Thursday </td>
                <td colspan="2"> C Programming </td>
                <td> <class>Free Slot</class> </td>
                <td> English </td>
            </tr>
            <tr>
                <td class="head"> Friday </td>
                <td> <class>Free Slot</class> </td>
                <td> FWAD </td>
                <td> English </td>
                <td> <class>Free Slot</class> </td>
            </tr>
            <tr>
                <td class="head"> Saturday </td>
                <td colspan="2"> FWAD </td>
                <td>  <class>Free Slot</class> </td>
                <td> C Programming </td>
            </tr>
        </table>
        <table class="Rithanya" style="margin-top:30px;">
            <tr>
                <th class="red"> S.NO </th>
                <th class="red"> SUBJECT CODE </th>
                <th class="red"> SUBJECT NAME </th>
            </tr>
            <tr>
                <td class="red"> 1 </td>
                <td> 5H1-1 </td>
                <td> Fundamentals of C Programming </td>
            </tr>
            <tr>
                <td class="red"> 2 </td>
                <td> 5K1-1 </td>
                <td> Fundamentals of Web Application </td>
            </tr>
            <tr>
                <td class="red"> 3 </td>
                <td> 5O2-1 </td>
                <td> Communicative English </td>
            </tr>
        </table>
    </body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2025-11-27 164723.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
