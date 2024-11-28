# Ex03 Time Table
# Date:28-11-2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>

<body>
    
    <center>
    <img src="SEC LOGO.png" width="800">  
    <br>
    <br>
    <br>
     <h2>SLOT TIME TABLE - KABILAN (24900859)</h2>
        <table border="2">
          <center> <style>

                body{
                    background-image: url('SEC WATERMARK.jpg'); width: 100% ;height: 30%;
                    background-size: 50%;height: 125%;
                    background-repeat: no-repeat;
                    background-position: center;
                }
            </style></center> 
            <style>
                table{ 
                    width: 50%;
                    height: 22%;
                }
            </style>
        <TR>
            <th align="center" >DAYS</th>
            <Th align="center" >8-10</Th>
            <Th align="center" > 10-12</Th>
            <Th align="center" >12-1</Th>
            <Th align="center" >1-3</Th>
            <Th align="center" >3-5</Th>
        </TR >
    <tr>
        <th align="center" >MONDAY</th>
        <TD align="center">---</TD>
        <TD  align="center" >FWAD</TD>
        <TD style="position: vertical;" rowspan="6" align="center" >LUNCH</TD>
        <TD  align="center" >BEEE</TD>
        <TD align="center">---</TD>
    </tr>
    <TR>
       <th align="center" >TUESDAY</th>
       <td align="center" >---</td>
       <td align="center" >---</td>
       <td align="center" >BEEE</td>
       <td align="center" >---</td>
    </TR>
    <tr>
        <th align="center">WEDNESDAY</th>
        <td  align="center" >CMA</td>
        <td align="center" >FCP</td>
        <td align="center">MM</td>
        <TD align="center" >---</TD>
    </tr>
    <tr>
        <th align="center">THURSDAY</th>
        <td  align="center" >PQC</td>
        <td align="center" > CMA</td>
        <td  align="center">FWAD</td>
        <td align="center" >---</td>
    </tr>
    <tr>
        <th align="center">FRIDAY</th>
        <TD align="center">---</TD>
        <td align="center" >DE</td>
        <td align="center" >PQC</td>
        <td align="center" >---</td>
    </tr>
    <tr>
        <th align="center">SATURDAY</th>
        <td align="center" >DE</td>
        <td align="center">CDS</td>
        <td align="center" >FCP</td>
        <td align="center">FWAD</td>
    </tr>
    
    </table>
    <br>
    <br>
    <br>
    
    
        <table border="2" >
            <tr>
            <td>S.NO</td>
            <td>SUB CODE</td>
            <td>SUBJECT</td>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI304</td> 
            <td>Fundamental of C Programming</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI414</td>
            <td>Fundamental of Web Application Development</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EE305</td>
            <td>Basic Electrical,Electronic and Mesurement Engineering</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19EY708</td>
            <td>Career Development Skills</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19Ma201</td>
            <td>Calculus and Matrix Algebra</td>
        </tr>
        <tr>
            <td>7</td>
            <td>EC-M-SCOFT</td>
            <td>Mentor Meet</td>
        </tr>
        <tr>
            <td>8</td>
            <td>SH3214</td>
            <td>Physics for Quantum Computing</td>
        </tr>
        </table>
    </center>
    </body>
    </html>
```
# OUTPUT
![alt text](output.png)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
