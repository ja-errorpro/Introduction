---
layout: post
author: 白磷
---

<meta name="viewport" content="width=device-width,initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=yes"/>

# FOR Python遊戲設計

檔案庫: [Here](https://drive.google.com/drive/folders/1MlQkB7COIBu_EZDFaYExBuVVb_FxZpiW?usp=sharing)

Python程式列表(全自寫):  [LIST](./pythonprograms/list)

Cocos2d: [Docs](https://docs.cocos.com/creator/2.3/manual/zh/getting-started/cocos2d-x-guide.html)

## 第一堂: IDE: pycharm CE, Module: cocos2d

[彭彭-Python程式設計入門](https://training.pada-x.com/python-start.htm)

[Colab](https://hackmd.io/@jease0502/colab_simple?print-pdf#/)

[CBE30338](https://jckantor.github.io/CBE30338/) 

記得寫程式可放個[小抄](https://drive.google.com/file/d/10Tuhcgdapt0QKy1v6roHRPEwtA0MZVIs/view?usp=sharing)在旁邊...

有問題[請點這個](https://google.com)

作業: 遊玩[CodeCombat](https://codecombat.com/)

---

## 第二堂

安裝Pycharm : [Pycharm](https://www.jetbrains.com/pycharm/)

> **<u>Community版為開源,免費 / Professional為完整版(30天免費試用)</u>**

> 需要先安裝Python (Ver. >3.7),Windows:可在Microsoft市集搜尋Python / MacOS可在官網上下載 / Linux有些版本已預安裝,安裝方式: (`` $ apt update && apt install python3 ``)

安裝方式: [Here](https://pygame.hackersir.org/Lessons/01/PyCharm_install.html)

設定: [here](https://pygame.hackersir.org/Lessons/01/PyCharm_config.html)

安裝Cocos2d: Files>Setting>Project: Inter..>(+)>搜尋cocos2d>安裝

學程式的技巧: 先抄再讀 不懂可Google

#### Vim:

分為**命令模式,插入模式,底線命令模式,視覺模式**

**命令模式**: 為預設模式,在任何模式中按下Esc即可到此模式,可按下某些鍵來切換模式

**插入模式**: 切換方式:在命令模式中按下i,a,o等按鍵,可在游標位置插入需要的文字

**底線命令模式**: 切換方式:按下:,可輸入指令操作內容,

離開: :q

強制離開: :q!

存檔不離開: :w

強制存檔不離開: :w!

存檔並離開: :wq

強制存檔並離開: :wq!

**視覺模式**: 切換方式:按下v , 方便用於閱讀和強調

作業: 安裝環境,開啟範例專案並測試執行幾個程式,並拍照

---

## 第三堂

讀懂程式碼的方式:

> 1.小程式直接讀
>> 從頭到尾讀

>> 依執行順序讀

> 2.大程式需要:
>> 大綱工具,定義(Ctrl+b\|Ctrl+\[),搜尋,更多專業技巧

> 3.善用Debugger除錯器

作業: 閱讀test中任意程式,試著更動程式碼並觀察執行結果

---

## 第四堂

作業: 修改程式or以test資料夾中程式片段組合成一個遊戲,不懂的可註解發問研究



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