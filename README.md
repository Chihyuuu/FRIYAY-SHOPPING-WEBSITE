# Friyay-Shopping-Website
PHP + Apache + MySQL

- ### 首頁
套用模板動態slider效果，並將「Shop Now」連結至商品頁。最上方分別為Home首頁、Products產品頁、Contact聯絡我們頁，和Cart購物車與Login登入選項。

![](https://i.imgur.com/qBC4pxU.png)

![](https://i.imgur.com/AGclOU4.png)

- ### 商品頁（Select）
從資料庫撈取商品名稱、價格與圖片，於網頁中表格呈現所有商品資訊。

![](https://i.imgur.com/05AgGoE.png)

![](https://i.imgur.com/MwSoqdr.png)


 
- ### 聯絡我們 （Insert）
讓使用者留下訊息給予回饋，有姓名、標題與訊息內容三個欄位，其中姓名與訊息內容為必填（有卡控）。使用者成功送出訊息後會傳送到資料庫後端。

![](https://i.imgur.com/Dl9x3VT.png)

![](https://i.imgur.com/4XRsGA2.png)

 
- ### 註冊頁（Insert）
新用戶須先註冊，輸入帳號、密碼、姓名、電話與住址，會以account帳號為primary key，不重複才能成功新增，成功新增後會將資料儲存至資料庫中。

![](https://i.imgur.com/JVQQbgw.png)

- ### 登入頁（Select）
確認使用者輸入之帳號密碼是否與資料庫中相符，正確的話才能成功登入。

![](https://i.imgur.com/TY1tLoh.png)

- ### 會員管理（Select、Update）
登入後之會員可進行資料修改，除帳號之外其餘資料皆可修改，修改後資料會根據該會員帳號，更新至資料庫中。

![](https://i.imgur.com/NfP2dwE.png)

- ### 登入後畫面（Select、Insert）
登入後才可新增商品至購物車，按下新增之按鈕，該商品就會新增至購物車。

![](https://i.imgur.com/YZ9SEVo.png)


- ### 購物車頁（Select、Delete）
從資料去撈取該會員的購物車資料，呈現於表格中，而會員可以由選擇核取方塊並按下Delete鍵，刪除該筆商品。

![](https://i.imgur.com/ASgsiXL.png)


- ### 資料庫所有資料表

![](https://i.imgur.com/w35seil.png)
 
- ### 「帳號」資料表

![](https://i.imgur.com/CpwbnYO.png)

- ### 「購物車」資料表
該資料表包含了所有會員購物車內之資料，撈取資料時可根據會員的cID，撈取該會員的商品。

![](https://i.imgur.com/BNFtY06.png)

- ### 「留言訊息」資料表

![](https://i.imgur.com/GQQkTD1.png)

- ### 「商品」資料表
若賣家需新增商品，直接從資料庫進行新增，圖片是以連結的方式存入。

![](https://i.imgur.com/8oR4uBM.png)
