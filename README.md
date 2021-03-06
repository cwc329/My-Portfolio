My-Portfolio
===
## Demo Links
[Simple Blog](http://mentor-program.co/mtr04group6/cwc329/blog/V1_0_0/)  
[Simple Bulletin](http://mentor-program.co/mtr04group6/cwc329/bulletin/V1_1_0/index.php)  
[Twitch API 練習](https://cwc329.github.io/)  
[SPA Simple Bulletin](http://mentor-program.co/mtr04group6/cwc329/bulletin/V1_2_0/index.html)  

## Simple Blog
[Blog demo](http://mentor-program.co/mtr04group6/cwc329/blog/V1_0_0/)  
以 PHP 開發，練習使用 PHP 做後端資料驗證，並且與資料庫互動。
### 頁面：
- 一般頁面－所有人都可瀏覽
  1. 首頁，顯示最新的五篇文章。
  2. 文章列表，可以看到所有文章，文章由新到舊排序，有分頁機制，每頁顯示五篇文章。
  3. 分類專區，看到所有分類，各分類有幾篇文章以及未分類的文章。
  4. 文章頁面，可以看到文章全文。
  5. 關於我，製作中。
- 發表與管理頁面－僅管理員與小編可以進入
  1. 發表與編輯文章，可以發表新文章與編輯舊文章串接 CKEditor4 作為文章編輯器。
  2. 文章管理頁面，顯示所有文章標題、作者、分類與發表時間。
  3. 新增與編輯分類，可以編輯現有分類以及新增分類。
  4. 分類管理頁面，可以一覽目前所有分類。

### 功能：
  1. 有管理員身份，管理員可以發表、編輯與刪除文章與分類。
  2. 有小編，小編可以發表、編輯文章與分類，但是無法刪除。
  3. 文章分類，每篇文章可以選擇一個分類，也可以不設分類。
  4. 在首頁與文章列表可以預覽文章部分內容，並且有「read more」按鍵可以看到所有內容。

## Simple Bulletin
[Bulletin demo](http://mentor-program.co/mtr04group6/cwc329/bulletin/V1_1_0/index.php)  
同樣以 PHP 開發，簡易的小型留言板，有會員制，可以發文並且有管理員與小編。
### 頁面：
- 一般頁面－所有人都可瀏覽
  1. 首頁，顯示所有留言，登入後可以在首頁發表留言並且更改自己的暱稱。
  2. 註冊頁面，註冊帳號，限制帳號密打為英文與數字，但不限長度。組別限制1-6。
  3. 登入頁面。
  4. 編輯留言頁面，會員可以編輯自己的留言。

- 管理頁面－僅管理員
  1. 會院管理頁面，可以看到所有會員的資料以及變更會員類型。


### 功能：
  1. 可以註冊會員，需要註冊會員才能發留言。使用者可以任意編輯與刪除自己的留言。
  2. 有管理員與小編，管理員可以編輯與刪除任意留言；小編可以編輯任何留言，但不能刪除。
  3. 禁言功能，可以使特定會員不得發表新留言，不過可以刪除以及編輯會員自己的舊留言。

## Twitch API 練習
[Twitch APT 練習](https://cwc329.github.io/)  
以 XMLHttpRequest 練習 AJAX，串接 Twitch API。  
### 功能
1. 顯示目前最多人觀看的 20 個實況，點擊該實況連結可以直接前往頻道觀看。 
2. 右上角為目前 Twitch 最熱門的 5 個遊戲，點擊可以顯示該遊戲最多人觀看的 20 個實況。
3. 頁面最下面有顯示更多的按鈕，按下之後可以再顯示 20 個實況。
4. 左上角可以搜尋遊戲，可以查詢該遊戲目前的實況。

## SPA Simple Bulletin
[SPA Bulletin demo](http://mentor-program.co/mtr04group6/cwc329/bulletin/V1_2_0/index.html)  
改良留言板，嘗試前後端分離。自己寫 restful API 並且用前端串接交換資料，
由於此 API 只有留言板使用，所以沒有開放 CORS。
前端使用 jQuery 開發，製作 SPA 留言板，僅會員能留言。

### 功能
  1. 顯示留言，有 load more 功能，每次載入 5 則留言。
  2. 可以註冊會員，僅有會員可以留言。



