<!DOCTYPE html>
<html>
<head>
  <title>assignment#2</title>
  <style>
    div {
      background-color : skyblue;
      background-color : 100px 100px;
      background-image : url("media/apple1.png");
      background-repeat : repeat-y;
      background-position: center center;
    }
    div {
      width : 200px;
      height : 200px;
      color : blueviolet;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <h3>서승원 박스에 배경 꾸미기</h3>
  <hr>
  <div>안녕하세요 제가 제일 좋아하는 과일은
  사과입니다. 오늘 아침에도 먹었습니다. </div>
  <script src="/__/firebase/init.js"></script>
  <script>
    var perf = firebase.performance();
    // ...
  </script>
</body>
<br><br><br><hr>
<head><title>텍스트 그림자</title>
  <style>
    div {
      font : normal 24px verdana;
    }
    .dropText {
      text-shadow: 3px 3px;
    }
    .redText {
      text-shadow: 3px 3px red;
    }
    .blurText {
      text-shadow: 3px 3px 5px skyblue;
    }
    .glowEffect {
      text-shadow: 0px 0px 3px red;
    }
    .wordArtEffect {
      color : white;
      text-shadow: 0px 0px 3px darkblue;
    }
    .threeDeffect {
      color : white;
      text-shadow: 2px 2px 4px black;
    }
    .multiEffect {
      color : yellow;
      text-shadow: 2px 2px 2px black, 0 0 25px blue, 0 0 5px darkblue;
    }
  </style></head>
  <body>
    <h3>그림자 텍스트 서승원</h3>
    <hr>
    <div class="dropText">맛있는 사과</div>
    <div class="redText">달콤한 사과</div>
    <div class="blurText">새콤한 사과</div>
    <div class="glowEffect">아침엔 사과</div>
    <div class="wordArtEffect">WordArt Effect</div>
    <div class="threeDeffect">3D Effect</div>
    <div class="multiEffect">Multiple Shadow Effect</div>
  </body>
</html>
