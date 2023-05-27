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
<html>
<head>
<title>Display the Results Of the Learners</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"));
mark2=parseInt(prompt("Enter Subject-2 Marks"));
mark3=parseInt(prompt("Enter Subject-3 Marks"));
total=mark1+mark2+mark3;
percentage=total/3;
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
alert("RA Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click here to Get the Result of the Learner
</h1>
</body>
</html>

## OUTPUT
![Screenshot (8)](https://github.com/Priyapugaz/Ex06_Web-Design/assets/127816320/5051140a-6db1-4ac6-ba1a-b340d37268b4)
![Screenshot (9)](https://github.com/Priyapugaz/Ex06_Web-Design/assets/127816320/bc069905-2817-4ffe-8210-f81213aeaeb1)
![Screenshot (10)](https://github.com/Priyapugaz/Ex06_Web-Design/assets/127816320/5ff5bc4a-f236-477b-a54b-6e5ce5513c80)


## RESULT
  Student result using JavaScript is created successfully.
