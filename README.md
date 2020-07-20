我的餐廰清單
====
用了Node.js及Express的網站，展示我個人十分喜愛餐廰名單的網站，可點擊得知該餐廰的名稱、位置、電話、評分及分類，同時透過輸入餐廰名稱快速搜索餐廰。

Features - 網站功能
----
1. 使用者可以首頁瀏覽所有餐廰，並取得它們的照片、名稱、分類及評分
2. 使用者可透過點擊餐廰查看詳細的資料，如餐廰地址、描述及電話，並且按下地址最後的圖案可以進入該餐廰的Google Map
3. 使用者可透過搜尋餐廳名稱來找到指定的餐廳

Environment SetUp - 環境建置
----
1.Node.js v10.21.0<br>2.Express v4.17.1<br>3.Express-Handlebars v5.1.0

Installing - 安裝流程
----
1.開啟terminal，Clone 此專案到本機電腦<br><pre>git clone https://github.com/linly123/assignment_restaurant.git</pre>
  
2.進入並存放此專案的資料夾<br><pre>cd restaurantList</pre>
  
3.安裝 npm 套件<br><pre>於Terminal 輸入 npm install 指令</pre>

4.安裝 nodemon 套件<br><pre>於Terminal 輸入 nodemon app.js 指令</pre>

5.啟動伺服器，執行 app.js 檔案<br><pre>nodemon app.js</pre>

6.成功及完成啟動<br><pre>當 terminal 出現以下字樣，表示伺服器與資料庫已啟動並成功連結
The Express server is running on http://localhost:3000</pre>
