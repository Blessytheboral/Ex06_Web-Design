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
~~~
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
    alert("RA Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
~~~



## OUTPUT
![ex 6(1)](https://github.com/Blessytheboral/Ex06_Web-Design/assets/127816463/869ab518-53d7-4dcf-a736-700a6d77bdbb)
![ex 6(2)](https://github.com/Blessytheboral/Ex06_Web-Design/assets/127816463/6190af3b-8139-4e79-8007-b3064b0fc1b0)
![ex 6(3)](https://github.com/Blessytheboral/Ex06_Web-Design/assets/127816463/11f5bdce-01c7-4ad0-8aa3-f491d8f7e5a3)
![ex 6(4)](https://github.com/Blessytheboral/Ex06_Web-Design/assets/127816463/9c458310-c805-4b58-846b-49451c0c5615)
![ex 6(5)](https://github.com/Blessytheboral/Ex06_Web-Design/assets/127816463/94b204e1-b2bd-4dfb-93c2-7cf549736e79)
![ex 6(6)](https://github.com/Blessytheboral/Ex06_Web-Design/assets/127816463/2884f035-2dda-4b4a-91b3-bd64e2a57a8a)


## RESULT
  Student result using JavaScript is created successfully.
