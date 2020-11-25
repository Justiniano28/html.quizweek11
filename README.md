DOCTYPE html>
html>
head>
<title>Quiz</title>
<link rel="stylesheet" type="text/css" href="quiz.css">
script type="text/javascript" src="quiz .js"></script>
/head


body>
form name="quiz" id="quiz">
<div>
p1. Sino ang pambansang kamao ng pilipinas? 
</p>
<p>input type="radio" name="question1" value="hatton">A. Hatton</p>
pinput type="radio" name="question1" value="Paquiao ">B . Paquiao</p>
pinput type="radio" name="question1" value="Marquez ">C. Marquez</p>
p>input type="radio" name=""question1" value="Swift">D. Swift</p>
</div

<div>
<p12. Ano ang pqmbansang hayop  sa pilipinas?</p>
pinput type="radio" name="question2" value="Aso">A. Aso</p>
p>input type="radio" name="question2" value="Kalabaw">B. Kalabaw</p>
pinput type="radio" name="question2" value="Daga">C. Daga</p>
pinput type="radio" name="question2" value="Swift">D. Swift</p>
/div
<div>
p1. Ano ang pambansang kasuotan ng pilipinas</p>
pinput type="radio" name= "question3" value= "Barong at saya " >A. Barong at saya</ p>
pinput type=""radio" name="question1" value="Poloshirt ">B. Poloshirt</p>
pinput type="radio" name= "question3 " value="Sando">C. Sando</p>
p>input type="radio" name="question3" value="Swift">D. Swift</p>
</div>

input type"button" name" valuea"submit !" ida"buttom" onclicko"check() ">
fore
id="result"></o>
bodyy




function check() {
var c-0;
var q1-document.quiz.question1. value;
var q2-document.quiz.question2 . value;
var q3-document.quiz.question3. value;

if (q1--"Pacquiao") {c+*}
if (q2-="Kalabaw" ) {c++}
if (q3-="Barong at saya") {c++}
document. write (c) ;




body{
background- color: pink;
color:black;
font-size: 20px;
font-weight: bolder;
margin-Left: 2rem;
}
