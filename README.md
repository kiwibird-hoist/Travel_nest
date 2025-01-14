# Travel_Nest
![image](https://firebasestorage.googleapis.com/v0/b/javel-85c60.appspot.com/o/Travel_Nest.png?alt=media)
期末小組專題 - 機票比價訂購網
[專題ppt](https://docs.google.com/presentation/d/1wBvzUMSD7u4sN4ec42IK8gBruckoFzE6/edit?usp=drive_link&ouid=102176453339459578791&rtpof=true&sd=true)
iSpan 資展國際，跨域Java軟體工程師就業養成班 楊凱宇

## 專案分工
網站畫面使用此作者的資源作為[前端模板](https://github.com/technext/travelista/tree/master)，感謝作者提供開源的模板。
小組專案以 Spring boot 開發網頁程式，使用預設的 Tomcat 作為 Web 伺服器；
使用了 Spring Data JPA 來進行資料庫操作，以及 Thymeleaf 作為模板引擎來渲染動態頁面；
遵循了 MVC 架構完成專案，使用 RESTFul API 標準進行資料交換；
資料庫方面，使用 MAMP 搭建的 MySQL 資料庫。

我負責的功能有
1. 首頁的前端畫面設計和後台功能。
2. 首頁新聞的後台管理。
3. 第三方登入，使用 firebase 工具製作 google 和 line 的第三方登入。
4. 第三方支付，使用 ECPay 提供的 SDK。

## 資料庫
航空機票的票價、日期、航班等資訊，是組員們大家共同查詢機場，一一手動輸入的資訊。
其餘資料表則由相關功能負責人負責，如我負責首頁，所以也建置了首頁新聞的資料庫。
