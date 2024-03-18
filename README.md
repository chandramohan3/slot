# Ex03 Time Table
## Date: 18/03/24

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
    <head>
        <title>MY TIME TABLE</title>
    </head>
    <body>
        <center>
        <img src="logo.png" height="100" width="777">
        </center>
        <table align="center" border="2" cellspacing="12" cellpadding="12" height="25" width="50">
            <h1 align="center" >Slot Time Table-S.CHANDRAMOHAN(212221223002)</h1>
            <tr>
            
                <th bgcolor="yellow">DAY/TIME</th>
                <th bgcolor="yellow">MONDAY</th> 
                <th bgcolor="yellow">TUESDAY</th>
                <th bgcolor="yellow">WEDNESDAY</th>
                <th bgcolor="yellow">THURSDAY</th>
                <th bgcolor="yellow">FRIDAY</th>
                <th bgcolor="yellow">SATURDAY</th>
            </tr>
            <tr>
                <td bgcolor="blue">8-10</td>
                <td bgcolor="grey">free slot</td>
                <td bgcolor="grey">free slot</td>
                <td bgcolor="grey">che</td>
                <td bgcolor="grey">free slot</td>
                <td bgcolor="grey">web</td>
                <td bgcolor="grey">maths</td>
            </tr>
            <tr>
                <td bgcolor="blue">10-12</td>
                <td bgcolor="grey">free slot</td>
                <td bgcolor="grey">free slot</td>
                <td bgcolor="grey">free slot</td>
                <td bgcolor="grey">maths</td>
                <td bgcolor="grey">c program</td>
                <td bgcolor="grey">che</td>
            </tr>
            <td bgcolor="red">12-01</td>
                <td align="center" colspan="6" bgcolor="red">LUNCH</td>
            </tr>
            <tr>
                <td bgcolor="blue">01-03</td>
                <td bgcolor="grey">creative</td>
                <td bgcolor="grey">web</td>
                <td bgcolor="grey">english</td>
                <td bgcolor="grey">web</td>
                <td bgcolor="grey">computer networks</td>
                <td bgcolor="grey">free slot</td>
            </tr>
            <tr>
                <td bgcolor="blue">03-05</td>
                <td bgcolor="grey">c program</td>
                <td bgcolor="grey">free slot</td>
                <td bgcolor="grey">computer networks</td>
                <td bgcolor="grey">free slot</td>
                <td bgcolor="grey">english</td>
                <td bgcolor="grey">free slot</td>
            </tr>
        <table align="center" border="3" cellspacing="2" cellpadding="4">
            <tr>
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI304</td>
                <td>Fundamentals of c Programming</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>Fundamentals of web application development</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19CS406</td>
                <td>Computer Networks</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CY205</td>
                <td>Principles of chemistry in Engineering</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY702</td>
                <td>Creative skills for Communication</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19MA222</td>
                <td>Probability and Queueing Models</td>
            </tr>
            <br>
        </table>

        </table>
    </body>
</html>v
```


## OUTPUT

![Screenshot 2024-03-18 105528](https://github.com/chandramohan3/slot/assets/142579775/4b545dd3-74b2-4f0b-ac88-86a3f58b497b)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
