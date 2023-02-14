---
# title: 音乐馆
date: 2021-04-24 21:41:30
type: music
aplayer: true
top_img: false
comments: false
aside: false
---

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HeoMusic - 用音乐感染人心</title>
  <link rel="stylesheet" type="text/css" href="./css/APlayer.min.css">
  <link rel="stylesheet" type="text/css" href="./main.css">
  <link rel="icon" type="image/x-icon" href="./img/icon.webp">
  <link rel="apple-touch-icon" href="./img/icon-r.webp">
  <meta name="apple-mobile-web-app-title" content="音乐">
  <link rel="bookmark" href="./img/icon.webp">
  <link rel="apple-touch-icon-precomposed" sizes="180x180" href="./img/icon-r.webp">
  <meta name="description" content="一个简单好用的音乐播放器。">
</head>
<body>
<div id="music_bg"></div>
<div id="heoMusic-page">
  <meting-js id="8166648359" server="netease" type="playlist" mutex="true" preload="auto" order='random'></meting-js>
</div>
<script src="./js/APlayer.min.js"></script>
<script src="./js/Meting2.min.js"></script>
<script async data-pjax src="./js/main.js"></script>
</body>