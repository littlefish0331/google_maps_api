# README

這個資料夾記錄我學習 [Google Maps API - 網頁載入地圖(起手式)](https://www.oxxostudio.tw/articles/201707/google-maps-1.html) 文章的過程與成果。

- demo/: 存放學習撰寫的網頁。
- reference/: 存放學習的文章。

## 檔案功能

- demo01: place 地點模式
- demo02: directions 路線規劃模式
- demo03: Search 搜尋模式
- demo04: View 檢視模式
- demo05: streetview 街景服務模式

## 語法筆記

只記錄有遇到的，沒有用到，或是不知道功能的就先不記錄了!!

**html語法:**

- <!DOCTYPE html>: 標記文件類型為html。
- <meta charset="UTF-8">: set html encoding，這樣傳遞網址值就不會有亂碼的問題。
- <link type="text/css" rel="Stylesheet" href="./demo01_css.css">: 連結css檔。

- 註解語法 <!-- 這是註解語法 -->

- iframe屬性(舊版，現在仍可使用，但是html5已經有新的規範)
  - frameborder:是否顯示邊框，1(yes), 0(no)
  - height: height屬性指定了iframe的像素高度，建議使用css設置。
  - width: width屬性指定了iframe的像素寬度，建議使用css設置。
  - name: iframe的名稱，window.frames[name]時專用的屬性。
  - scrolling: iframe是否滾動。yes, no, auto。
  - src： iframe的網址。
  - style: 這個attribute，要使用css語法做填入
  - link: 規定了當前文檔與外部資源的關係。
    - type="text/css"。type屬性包含了鏈接資源的MIME類型。
    - rel="stylesheet"。rel代表關係(relationship)，stylesheet代表樣式表。常見的還有"icon"等等
    - href="./demo01_css.css"，要連結的檔案路徑。
  - allowfullscreen。據說現在用法改為 allow = "fullscreen"。

**css語法:**

- border: solid 3px rgb(207, 0, 0); 這句話可以拆解成下面三句
  - border: solid;
  - border-width: 3px;
  - border-color: rgb(207, 0, 0);
- width: 100%; 這個可以無視 iframe 的 width 屬性，直接邊框放到最大。

