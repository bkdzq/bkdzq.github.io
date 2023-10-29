---
title:  "up主历史项目 || my coding project"
mathjax: true
layout: post
categories: media
---

<head>

<style>
  <!-- fany button -->
 html, body {
  height: 100%;
}

.wrap1 {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.button1 {
  min-width: 900px;
  min-height: 60px;
  font-family: 'Nunito', sans-serif;
  font-size: 22px;
  text-transform: uppercase;
  letter-spacing: 1.3px;
  font-weight: 700;
  color: #313133;
  background: #4FD1C5;
background: linear-gradient(90deg, rgba(129,230,217,1) 0%, rgba(79,209,197,1) 100%);
  border: none;
  border-radius: 1000px;
  box-shadow: 12px 12px 24px rgba(79,209,197,.64);
  transition: all 0.3s ease-in-out 0s;
  cursor: pointer;
  outline: none;
  position: relative;
  padding: 10px;
  }

button::before {
content: '';
  border-radius: 1000px;
  min-width: calc(900px + 12px);
  min-height: calc(60px + 12px);
  border: 6px solid #00FFCB;
  box-shadow: 0 0 60px rgba(0,255,203,.64);
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  opacity: 0;
  transition: all .3s ease-in-out 0s;
}

.button1:hover, .button:focus {
  color: #313133;
  transform: translateY(-6px);
}

button:hover::before, button:focus::before {
  opacity: 1;
}

button::after {
  content: '';
  width: 30px; height: 30px;
  border-radius: 100%;
  border: 6px solid #00FFCB;
  position: absolute;
  z-index: -1;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  animation: ring 1.5s infinite;
}

button:hover::after, button:focus::after {
  animation: none;
  display: none;
}

@keyframes ring {
  0% {
    width: 50px;
    height: 50px;
    opacity: 1;
  }
  100% {
    width: 500px;
    height: 500px;
    opacity: 0;
  }
}
<!--   fancy button -->
</style>

</head>


up主所有视频代码都在b站 


<div class="wrap1">
  <button onclick="location.href=' https://bkdzq.github.io/gallery_video/'" class="button1">我的youtube&bilibili视频 / my youtube and bilibili social media  videos</button>
 
</div>


<h1>  </h1>

