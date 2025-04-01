# Ex03 Time Table
# Date:01.04.2025
# NAME : NISHMA SHERIN.K
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
<<html>
<head>
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="/static/Screenshot 2025-03-25 194722.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="5" border="7" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - NISHMA(24002101)</b></caption>
<tr align="center">
<th bgcolor="gray">Day/Time</th>
<th bgcolor="gray">Monday</th>
<th bgcolor="gray">Tuesday</th>
<th bgcolor="gray">Wednesday</th>
<th bgcolor="gray">Thursday</th>
<th bgcolor="gray">Friday</th>
</tr>
<tr align="center">
<th bgcolor="gray">8-10</th>
<td colspan="3"></td>
<td>PHY</td>
<td>CHE</td>
</tr>
<tr align="center">
<th bgcolor="gray">10-12</th>
<td>GER</td>
<td> BEEE</td>
<td>   </td>
<td>TAIA</td>
<td>C</td>
</tr>
<tr>
<th bgcolor="gray">12-1</th>
<td colspan="5" align="center">      </td>
</tr>
<tr align="center">
<th bgcolor="gray">1-3</th>
<td colspan="2">    </td>
<td>C</td>
<td>FWAD</td>
<td>SANM</td>
</tr>
<tr align="center">
<th bgcolor="gray">3-5</th>
<td colspan="2">   </td>
<td>BEEE</td>
<td>IiOT</td>
<td>iIOTd>
</tr>
</table>
<br>
<table align="center" cellspacing="3" cellpadding="4" border="2">
<tr align="center">
<th>s. No.</th>
<th>SUB
    CODE</th>
<th>SUB NAME</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19EE305</td>
<td>BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING(BEEE)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMING(C)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUMDAMENTALS OF WEB APPLICATION DEVELOPMENT(FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA219</td>
<td>TRANSFORMS AND ITS APPLICATIONS(TAIA)</th>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>STATISTICS AND NUMERICAL METHODS(SANM)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AM509</td>
<td>INDUSTRIAL INTERNET OF THINGS(IiOT)</td>
</tr>
</table>
</body>
</html>

```

# OUTPUT

![Screenshot 2025-04-01 234346](https://github.com/user-attachments/assets/1a3a3549-f350-4495-ad22-e7f568a9abc1)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
