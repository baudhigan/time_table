# Ex03 Time Table
# Date: 22.04.2025
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
<!DOCTYPE html>
<html>
    <head>
    <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE - BAUDHIGAN (212223230028)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">DAY/TIME</th>
                <th bgcolor="yellow">MONDAY</th>
                <th bgcolor="yellow">TUESDAY</th>
                <th bgcolor="yellow">WEDNESDAY</th>
                <th bgcolor="yellow">THURSDAY</th>
                <th bgcolor="yellow">FRIDAY</th>
                <th bgcolor="yellow">SATURDAY</th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">8-10</th>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">10-12</th>
                <td>FREE SLOT</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>TRANSFORMS AND ITS APPLICATIONS</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
                <td>TRANSFORMS AND ITS APPLICATIONS</td>
                <td>COMPUTER NETWORKS</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">12-1</th>
                <th colspan="6" align="center"><b>LUNCH</b></th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">1-3</th>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
                <td>PROBABLITY AND QUEUEING MODEL</td>
                <td>MENTOR MEET</td>
                <td>COMPUTER NETWORKS</td>
                <td>PROBABLITY AND QUEUEING MODEL</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19CS406</td>
                <td>COMPUTER NETWORKS</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19MA219</td>
                <td>TRANSFORMS AND ITS APPLICATIONS</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19MA222</td>
                <td>PROBABLITY AND QUEUEING MODEL</td>
            </tr>
        </table>
    </body>
</html>
```
# OUTPUT
![Alt text](<Screenshot 2025-04-22 085624.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
