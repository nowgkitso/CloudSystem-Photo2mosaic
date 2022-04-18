# Cloud System 雲端相簿-並使用多個計算節點轉換圖片至馬賽克圖片
## 簡介
使用者先上傳想轉換成馬賽克的圖片，以事件為單位（不論幾張圖片Submit，Submit一次就是一個事件)，並使用三個計算節點處理圖片成馬賽克圖片，Webserver排程工作指派節點執行事件
## 系統結構
* Webserver:前端網頁處理（php, html)、上傳圖片、操作系統等功能; 排程Computing Node處理順序
* Computing Node:處理需要轉換成馬賽克的事件（圖片）
## 結果
