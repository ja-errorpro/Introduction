---
layout: default
---

<meta name="viewport" content="width=device-width,initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=yes"/>

# FOR Python遊戲設計

第一堂: IDE: pycharm CE, Module: cocos2d

[彭彭-Python程式設計入門](https://training.pada-x.com/python-start.htm)

[Colab](https://hackmd.io/@jease0502/colab_simple?print-pdf#/)

[CBE30338](https://jckantor.github.io/CBE30338/) 

記得寫程式可放個[小抄](https://drive.google.com/file/d/10Tuhcgdapt0QKy1v6roHRPEwtA0MZVIs/view?usp=sharing)在旁邊...

有問題[請點這個](https://google.com)

作業: 遊玩[CodeCombat](https://codecombat.com/)


<style>

.back-to-top {

display: none; /* 默認是隱藏的，這樣在第一屏才不顯示 */

position: fixed; /* 位置是固定的 */

bottom: 20px; /* 顯示在頁面底部 */

right: 30px; /* 顯示在頁面的右邊 */

z-index: 99; /* 確保不被其他功能覆蓋 */

border: 1px solid #5cb85c; /* 顯示邊框 */

outline: none; /* 不顯示外框 */

background-color: #fff; /* 設置背景背景顏色 */

color: #5cb85c; /* 設置文本顏色 */

cursor: pointer; /* 滑鼠移到按鈕上顯示手型 */

padding: 10px 15px 15px 15px; /* 增加一些內邊距 */

border-radius: 10px; /* 增加圓角 */

}

.back-to-top:hover {

background-color: #5cb85c; /* 滑鼠移上去時，反轉顏色 */

color: #fff;

}

</style>

<button class="js-back-to-top back-to-top" title="回到頭部">&#65085;</button>

<script src="https://cdn.staticfile.org/jquery/2.2.4/jquery.min.js"></script>

<script>

$(function () {

var $win = $(window);

var $backToTop = $('.js-back-to-top');

// 當用戶滾動到離頂部100像素時，展示回到頂部按鈕

$win.scroll(function () {

if ($win.scrollTop() > 100) {

$backToTop.show();

} else {

$backToTop.hide();

}

});

// 當用戶點擊按鈕時，通過動畫效果返回頭部

$backToTop.click(function () {

$('html, body').animate({scrollTop: 0}, 200);

});

});

</script>