
## 課程說明
- 本課程將針對 網站傳輸協議做深度的介紹並且結合 OWASP Top 10 針對漏洞做介紹與攻擊
- 適合完全沒有 網頁基礎、網站運作原理概念 的同學
  - 可以參加 SecurityFoscusOnline2023課程
  - 可以參照並自行學習 [MyFirstSecurity資安入門的第一堂課|網站安全初體驗](https://github.com/MyFirstSecurity2020/20230301)
 
## 解題平台

- ### [http://ctf-isip.tyc4d.tw/](http://ctf-isip.tyc4d.tw/)

## 課程主題 語宸 
- ### CTF基礎概論
- ### 基礎網頁概論
  - 瀏覽器與伺服器傳輸
  - HTTP協議介紹
    - HTTP Request
      - Header
        - Method
        - Protocol
        - Path
        - Addtional Header
      - Body
    - HTTP Resopnse
      - Header
        - Method
        - Protocol
        - Path
        - Addtional Header
      - Body
  - 觀察網站與網頁
  - 網站如何記住你是你，誰是誰 Cookie & Session
    - 存在電腦 Cookie
    - 怎麼保護 Cookie
    - Session 與 Cookie 的差別
- ### 工具介紹
  - BurpSuite 工具介紹
    - 功能 Proxy 介紹
    - Proxy 工作原理
    - 功能 Intercept 介紹 (攔截請求用)
    - 功能 Repeater 介紹 (重複送出)
    - 功能 Intruder 介紹 (自動攻擊)
      - 封包欄位偵測
      - 爆破攻擊
- ### OWASP TOP 10:2021
  - 介紹 OWASP 
  - #### 權限控制失效 Boken Access Control
    - 水平越權
    - 垂直越權
    - IDOR
    - GitHack
  - #### 注入式攻擊 Injection
    - 關聯式資料查詢語法注入攻擊 Relational SQL Injection
      - Relational Server Query Language
      - Relational DataBase Management System
      - SQL Syntax 語法
        - 陳述句
        - 命令 CREATE、DROP、ALTER、SELECT、INSERT、UPDATE、DELETE
        - 受詞
        - 子句
        - 運算子
        - 函數
        - 資料結構
      - SQL 跟 Backend Application 的關係
      - In-band SQLi
        - Error-Based SQLi
        - Union-Based SQLi
      - Blind SQLi
        - Boolean-Based SQLi
        - Time-Based SQLi
    - 指令注入攻擊 Command Injection
      - Backend Introduction & Application
      - Linux Command
      - Windows Command
    - 伺服端後端模板注入攻擊 Server Side Template Injection (進階課程)
      - 後端介紹與基本語法 
      - Python Flask
      - Python Module Tricks
    - Reverse Shell 搭建？
      - 網路環境SETUP
      - ngork 教學
      - 生產 Reverse Shell

## web分析常用工具(Tools)
  - Postman
  - burt suite
  - sqlmap
  - Kali Linux

## 解題標準

- * Find GET Method
- * Find POST Method
- * Find DELETE METHOD
- * Mystery Header
- * Find Cookies
- * Website Under Development & Leak Cookie
- * May I have free point ?
- * Free Point For me ?
- * Fix My Blog …
- * You can't see me
- * Where is Edward
- * Welcome2SQL
- WHERE are you
- Infomation_Sc...?
- Dump All Data!
- * Let the cow Moooooooooow
- Real-World
