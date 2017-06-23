主機網址：http://140.127.218.151/
================================

# 介紹

### 關於團隊

* 成員：田安得、王凱駿、莊于霆、梁瀛之
* 指導教授：丁一賢、楊書成
* 田安得( A1023353)： MVC架構、後台管理、RWD
* 王凱駿( A1023354)： 訂房系統、資料庫管理
* 莊于霆( A1023317)： 訂餐系統、系統測試
* 梁瀛之(W1055505)： 登入系統、權限管理

### 使用架構、框架

* RWD (HTML5 UP、Sass)
* jQuery
* Sass
* MVC(codeigniter)
>1. 在MVC裡面，所有的**index**都是 403 錯誤
>2. 程式碼路徑：application/views/...
>3. 路徑設定：application/controller/...
>4. css/javascript路徑：assets/...
>5. 資料庫連接：include.php

### 這是一個:虛設"的飯店網站，主要功能有：

* 顧客能依照需求搜尋客房
* 線上訂房、訂餐
* 能後臺在直接編輯網站的文字圖片、客房、餐點

# 使用說明書

### 一般使用

* 左上角的"三"可以縮放 **MENU**。
* News：顯示促銷活動和精選特輯，點擊相應按鈕會出現促銷的活動最新的消息
* 線上訂房：進入**客房查詢**
* 在地指南：顯示吾宿山的地圖、交通方式
* 聯絡我們：可以在該介面進行郵件編輯和傳送，以便通知吾宿山任何的問題和建議
* 會員登入：凡訂房成功者皆為吾宿山之會員，可由此登入

### 非會員訂房流程：

1. 進入**客房查詢**，尋找自己心儀的房型，或使用上方的查詢功能
2. 點擊**詳細**會看到詳細內容，點擊**訂房**會進入"訂房頁面"
3. 選擇入住的時間、房間的數量
4. 點擊**查詢空房**進入個人資訊填寫介面，填寫完個人資訊點擊**下一步**
5. 訂單完成（ps：個人資訊系統會自動給註冊會員，默認帳號為身份證號(字母為大寫)，密碼為信箱）

### 非會員點餐

* 本網站只有入住 **會員** 後才能訂餐
* 有訂房紀錄者皆為會員

### 會員專區(帳號:S123456788 密碼:1)

1. 登入
2. **MENU** 會新增出**客房點餐服務**以及開啟**會員專區**權限
3. 線上訂房：在**訂房頁面**中個人資訊填寫介面會自動提取會員資料，可直接進行編輯。點擊下一步訂單生成成功。
4. 客房點餐服務：會員能在任何時間觀看菜單，但只能在入住的期間才能點餐
5. 送餐的時間預設為點餐的 **45** 分鐘後，也可以自主選擇。不提供提前多日訂餐服務
6. 查詢、修改本房訂餐資訊查詢功能可以查詢和修改訂餐的資訊
7. **MENU** 內的**會員專區**，可以修改個人資料，個人密碼，也可以查詢訂房記錄，並在訂房介面進行付款和取消付款

### 後台管理員(帳號:S123456789 密碼:1)，須點選”員工登入”連結

1. 登入後會多出很多**按鈕**
2. 這些按鈕可以讓管理員對區塊作**新增、刪除、修改**
3. **MENU** 會多出**管理員專區、數據分析、MySQL資料庫**的選項
4. 管理員專區：管理員基本資料的修改，個人密碼的修改
5. 訂房作業進行所有訂單的查詢和查看訂單的付款情況
6. 餐點新增，餐點刪除進行訂餐功能表的新增，和刪除
7. 資料分析功能提供我們的房型統計，餐點統計和月報表資料
8. MYSQL資料庫可以直接進入資料庫進行直接編輯
