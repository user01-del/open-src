<!doctype html>
<html>
<head>
  <title>액티비티 매칭</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, inital-scale=1.0">
  <style media="screen">
    a {text-decoration: none;}
  </style>
</head>
<body>
  <h1><a href="server.html">메뉴</a></h1>

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
  <li><a href="01.html">회원가입</a></li>
  <li><a href="02.html">로그인</a></li>
  <li><a href="03.html">개인정보수정</a></li>
  <li><a href="04.html">FAQ</a></li>
  <li><a href="05.html">1:1문의</a></li>
  <li><a href="06.html">신고</a></li>
  <li><a href="07.html">개인팀매칭</a></li>
  <li><a href="08.html">단체채팅방</a></li>
</ol>

<h3>액티비티 </h3>

<p>
  액티비티 매칭 이란 ?<br>
  
</p>

</body>
</html>
