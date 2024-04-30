# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("No Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click here to Find Grade Result of a Student
</h1>
</body>
</html>
```
## OUTPUT
![Screenshot (821)](https://github.com/mrmdsuhail/Ex06_Web-Design/assets/165985737/f9b2a350-fbf7-4570-9189-6fd1ee69d55a)
![Screenshot (826)](https://github.com/mrmdsuhail/Ex06_Web-Design/assets/165985737/f7b76467-31ed-4c86-b99e-f9567d8e2be7)
![Screenshot (825)](https://github.com/mrmdsuhail/Ex06_Web-Design/assets/165985737/12a43d03-5aab-41a2-99d3-bc794d27adfa)
![Screenshot (824)](https://github.com/mrmdsuhail/Ex06_Web-Design/assets/165985737/2f4712fc-471c-4ee0-b922-51a694bf67e2)
![Screenshot (823)](https://github.com/mrmdsuhail/Ex06_Web-Design/assets/165985737/08657401-733c-46a4-a81f-5d154d9bedce)
![Screenshot (822)](https://github.com/mrmdsuhail/Ex06_Web-Design/assets/165985737/43fa3cb4-306b-4333-a1c3-ea39cb137440)

## RESULT
  Student result using JavaScript is created successfully.
