<!doctype html>
<html>
<head>
  <title>정치</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, inital-scale=1.0">
  <style media="screen">
    a {text-decoration: none;}
  </style>
</head>
<body>
  <h1><a href="server.html">server</a></h1>

  <input id = "night_day" type="button" value="night"
    onclick="
      var target = document.querySelector('body');
      if(this.value === 'night'){
        target.style.backgroundColor = 'black';
        target.style.color = 'white';
        this.value = 'day';
        var alist = document.querySelectorAll('a');
        var i = 0;
        while(i < alist.length){
         console.log(alist[i]);
         alist[i].style.color = 'powderblue';
         i = i + 1;
        }
      } else {
        target.style.backgroundColor = 'white';
        target.style.color = 'black';
        this.value = 'night';
        var alist = document.querySelectorAll('a');
        var i = 0;
        while(i < alist.length){
         console.log(alist[i]);
         alist[i].style.color = 'black';
         i = i + 1;
        }
      }
    ">

<ol>
  <li><a href="01.html">대북지원</a></li>
  <li><a href="02.html">발전소</a></li>
  <li><a href="03.html">국방</a></li>
  <li><a href="04.html">교육복지</a></li>
  <li><a href="05.html">노동복지</a></li>
  <li><a href="06.html">환경오염</a></li>
  <li><a href="07.html">범죄</a></li>
  <li><a href="08.html">안정감</a></li>
</ol>

<h3>정치</h3>

<p>
  정치란 무엇인가?<br>
  나라의 국민들 부터 세계의 국민들까지 모두의 행복을 찾아주는 것이다
</p>

</body>
</html>
