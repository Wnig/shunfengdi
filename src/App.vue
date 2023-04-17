<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import './font/style.css'
export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
  /* CSS reset */
  html{color:#000;background:#fff;-webkit-tap-highlight-color:rgba(0,0,0,0);font-family: 'PingFangSC-Ultralight',"Microsoft YaHei","微软雅黑","sans-serif";font-size: 12px;}
  body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,form,input,button,textarea,p,th,td,strong{padding:0;margin:0;font-family: 'PingFangSC-Ultralight',"Microsoft YaHei","微软雅黑","sans-serif";}
  table{border-collapse:collapse;border-spacing:0;}
  img{border:0;}
  a{text-decoration:none; color:#999; outline:none;}/*此处待添加默认链接颜色*/
  var,em,strong{font-style:normal;}
  em,strong,th,var{font-style:inherit;font-weight:inherit;}
  li{list-style:none;}
  caption,th{text-align:left;}
  h1,h2,h3,h4{font-size:100%;font-weight:normal;}
  input,button,textarea,select,option{font-family:inherit; font-size:inherit;font-style:inherit;font-weight:inherit;}
  input,button,textarea,select{*font-size:100%;}
  .clearfix:after {content:"\200B"; display:block; height:0; clear:both; }
  .clearfix { *zoom:1; }

  html {
    position: relative;
    width: 100%;
    overflow: hidden;
    overflow-y: scroll;
  }
  #app {
  }
  .pc {
    width: 100%;
    overflow: hidden;
  }
  .selection {
    position: relative;
    width: 100%;
    height: 100vh;
    overflow: hidden;
  }
  .down-con {
    position: absolute;
    left: 0;
    width: 100%;
    bottom: 8.7vh;
  }
  .down {
    position: relative;
    margin: 0 auto 2.59vh;
    width: 2.81vw;
    height: 2.45vw;
  }
  .down:after {
    position: absolute;
    left: 0;
    top: -3vh;
    content: '';
    width: 2.81vw;
    height: 2.45vw;
    background: url('../src/assets/down.svg') center center no-repeat;
    background-size: 100% 100%;
    cursor: pointer;
    -webkit-animation: fall 1.2s infinite;
    animation: fall 1.2s infinite;
  }
  .slidedown {
    margin: 0 auto;
    width: 11.41vw;
    height: 2.76vw;
    line-height: 2.76vw;
    background: url('../src/assets/04.svg') center center no-repeat;
    background-size: 100% 100%;
    cursor: pointer;
  }

  .title {
    color: #fff;
    text-align: center;
    font-size: 2.34vw;
    line-height: 2.34vw;
    font-family: 'PingFangSC-Regular';
  }
  .left_bor, .right_bor {
    display: inline-block;
    position: relative;
    width: 2.81vw;
    height: 1.25vw;
  }
  .left_bor {
    margin-right: 0.4vw;
  }
  .right_bor {
    margin-left: 0.4vw;
  }
  .left_bor:after {
    position: absolute;
    left: 0;
    top: 0;
    content: '';
    width: 2.81vw;
    height: 1.25vw;
    background: url('../src/assets/12.svg') center center no-repeat;
    background-size: cover;
  }
  .left_bor_000:after {
    background: url('../src/assets/05.svg') center center no-repeat;
    background-size: cover;
  }
  .right_bor:after {
    position: absolute;
    left: 0;
    top: 0;
    content: '';
    width: 2.81vw;
    height: 1.25vw;
    background: url('../src/assets/13.svg') center center no-repeat;
    background-size: cover;
  }
  .right_bor_000:after {
    background: url('../src/assets/06.svg') center center no-repeat;
    background-size: cover;
  }

  /*fixed*/
  .fixed {
    display: none;
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 16.11vh;
    background: rgba(0, 0, 0, 0.7);
    z-index: 999;
  }
  .fixed .cont {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  .fixed .left {
    margin-right: 7.55vw;
  }
  .fixed .left p {
    margin-bottom: 1.3vh;
    color: #FFFFFF;
    text-indent: 0.5em;
    font-size: 1.04vw;
  }
  .fixed .reply {
    display: inline-flex;
  }
  .fixed input {
    color: #fff;
    outline: none;
    border: none;
    background-color: transparent;
    font-size: 1vw;
  }
  .fixed .input_ {
    width: 13.02vw;
    height: 1.98vw;
    margin-right: 0.68vw;
    padding-left: 0.94vw;
    line-height: 1.98vw;
    background: rgba(255, 255, 255, 0.18);
    border-radius: 100px;
  }
  .fixed .button {
    width: 7.34vw;
    height: 1.98vw;
    border-radius: 100px;
    color: #000000;
    text-align: center;
    line-height: 1.98vw;
    font-size: 1.04vw;
    background: #FBBB02;
    cursor: pointer;
  }
  .bor_c {
    width: 1px;
    height: 7.78vh;
    margin-right: 6.93vw;
    background-color: #424242;
  }
  .fixed .right {
    width: 26vw;
  }
  .fixed .right p {
    color: #FFFFFF;
    font-size: 1.04vw;
  }
  .fixed .right h3 {
    color: #FFFFFF;
    font-size: 2.34vw;
    font-family: 'PingFangSC-Regular';
  }
  .fixed .right i {
    position: absolute;
    right: 7.03vw;
    top: 3.89vh;
    color: #fff;
    font-size: 1.5vw;
    cursor: pointer;
  }

  .fixed-right {
    display: none;
    position: fixed;
    right: 0;
    bottom: 28px;
    height: 50px;
    padding: 0 30px;
    background: rgba(22, 21, 25, 0.7);
    border-radius: 25px 0 0 25px;
    -webkit-transition: all .5s ease;
    transition: all .5s ease;
    z-index: 100;
    transform: translateX(0px);
    cursor: pointer;
  }
  .fixed-right p {
    font-size: 14px;
    color: #fff;
    letter-spacing: 0;
    margin: 0;
    line-height: 50px;
  }
  .fixed-right_ {
    transform: translateX(354px);
    -webkit-transition: all .5s ease;
    transition: all .5s ease;
  }
  
  .mob {
    display: none;
  }

  /*向下效果*/
  @-webkit-keyframes fall {
    0% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    60% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    100% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }
  @keyframes fall {
    0% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    60% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    100% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }

  /*漂浮*/
  @-webkit-keyframes float_01 {
    0% {
      -webkit-transform: translateY(5px);
      -moz-transform: translateY(5px);
      -ms-transform: translateY(5px);
      -o-transform: translateY(5px);
    }
    50% {
      -webkit-transform: translateY(-5px);
      -moz-transform: translateY(-5px);
      -ms-transform: translateY(-5px);
      -o-transform: translateY(-5px);
    }
    100% {
      -webkit-transform: translateY(5px);
      -moz-transform: translateY(5px);
      -ms-transform: translateY(5px);
      -o-transform: translateY(5px);
    }
  }
  @keyframes float_01 {
    0% {
      -webkit-transform: translateY(5px);
      -moz-transform: translateY(5px);
      -ms-transform: translateY(5px);
      -o-transform: translateY(5px);
    }
    50% {
      -webkit-transform: translateY(-5px);
      -moz-transform: translateY(-5px);
      -ms-transform: translateY(-5px);
      -o-transform: translateY(-5px);
    }
    100% {
      -webkit-transform: translateY(5px);
      -moz-transform: translateY(5px);
      -ms-transform: translateY(5px);
      -o-transform: translateY(5px);
    }
  }
  @-webkit-keyframes float_02 {
    0% {
      -webkit-transform: translateY(10px);
      -moz-transform: translateY(10px);
      -ms-transform: translateY(10px);
      -o-transform: translateY(10px);
    }
    50% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    100% {
      -webkit-transform: translateY(10px);
      -moz-transform: translateY(10px);
      -ms-transform: translateY(10px);
      -o-transform: translateY(10px);
    }
  }
  @keyframes float_02 {
    0% {
      -webkit-transform: translateY(10px);
      -moz-transform: translateY(10px);
      -ms-transform: translateY(10px);
      -o-transform: translateY(10px);
    }
    50% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    100% {
      -webkit-transform: translateY(10px);
      -moz-transform: translateY(10px);
      -ms-transform: translateY(10px);
      -o-transform: translateY(10px);
    }
  }
  @-webkit-keyframes float_03 {
     0% {
      -webkit-transform: translateY(30px);
      -moz-transform: translateY(30px);
      -ms-transform: translateY(30px);
      -o-transform: translateY(30px);
    }
    50% {
      -webkit-transform: translateY(-30px);
      -moz-transform: translateY(-30px);
      -ms-transform: translateY(-30px);
      -o-transform: translateY(-30px);
    }
    100% {
      -webkit-transform: translateY(30px);
      -moz-transform: translateY(30px);
      -ms-transform: translateY(30px);
      -o-transform: translateY(30px);
    }
  }
  @keyframes float_03 {
    0% {
      -webkit-transform: translateY(30px);
      -moz-transform: translateY(30px);
      -ms-transform: translateY(30px);
      -o-transform: translateY(30px);
    }
    50% {
      -webkit-transform: translateY(-30px);
      -moz-transform: translateY(-30px);
      -ms-transform: translateY(-30px);
      -o-transform: translateY(-30px);
    }
    100% {
      -webkit-transform: translateY(30px);
      -moz-transform: translateY(30px);
      -ms-transform: translateY(30px);
      -o-transform: translateY(30px);
    }
  }
  @-webkit-keyframes float_04 {
    0% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    50% {
      -webkit-transform: translateY(-15px);
      -moz-transform: translateY(-15px);
      -ms-transform: translateY(-15px);
      -o-transform: translateY(-15px);
    }
    100% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
  }
  @keyframes float_04 {
    0% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    50% {
      -webkit-transform: translateY(-15px);
      -moz-transform: translateY(-15px);
      -ms-transform: translateY(-15px);
      -o-transform: translateY(-15px);
    }
    100% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
  }

  @media screen and (max-width: 750px) {
    .mob {
      display: block;
    }
    .pc {
      display: none;
    }

    .down-con {
      position: absolute;
      left: 0;
      width: 100%;
      bottom: 8.7vh;
    }
    .down {
      margin: 0 auto 3.45vh;
      width: 9.07vw;
      height: 11.47vw;
    }
    .down:after {
      position: absolute;
      left: 0;
      top: 0;
      content: '';
      width: 9.07vw;
      height: 11.47vw;
    }
    .slidedown {
      width: 28vw;
      height: 6.4vw;
      line-height: 6.4vw;
      font-size: 2.8vw;
    }

    .title {
      line-height: 12vw;
      font-size: 6.67vw;
      font-family: 'PingFangSC-Regular';
    }
    .left_bor, .right_bor {
      display: inline-block;
      position: relative;
      width: 8.81vw;
      height: 12vw;
    }
    .left_bor {
      margin-right: 1.4vw;
    }
    .right_bor {
      margin-left: 1.4vw;
    }
    .left_bor:after {
      top: 4vw;
      width: 8.81vw;
      height: 12vw;
      background: url('../src/assets/12.svg') center center no-repeat;
      background-size: 100% 100%;
    }
    .left_bor_000:after {
      background: url('../src/assets/05.svg') center center no-repeat;
      background-size: 100% 100%;
    }
    .right_bor:after {
      top: 4vw;
      width: 8.81vw;
      height: 12vw;
      background: url('../src/assets/13.svg') center center no-repeat;
      background-size: 100% 100%;
    }
    .right_bor_000:after {
      background: url('../src/assets/06.svg') center center no-repeat;
      background-size: 100% 100%;
    }

    .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet {
      width: 2.67vw;
      height: 2.67vw;
      margin: 0 3.73vw;
      display: inline-block;
      border-radius: 100%;
      background: #fff;
      opacity: .2;
    }
    #swipers01 .swiper-pagination-bullet {
      margin: 0 1.73vw;
    }
    .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active {
      opacity: 1;
      background: #FBBB02;
    }

    .swiper-container .swiper-pagination {
      bottom: 0;
    }
  }
</style>
