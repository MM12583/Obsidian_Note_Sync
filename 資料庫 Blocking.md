
MSSQL 語法 :
~~~~sql
SELECT *
FROM sys.dm_tran_locks
~~~~

查詢示意圖 :
![[messageImage_1698891981680.jpg]]

request_mode : 以下狀態則執行 kill 
![[螢幕擷取畫面 2023-11-02 221359.png]]

kill Blocking session_id
~~~~sql
kill 57
kill 52
~~~~

參考文章 : 
<https://waynecheng.coderbridge.io/2020/11/03/DB-Blocking/>
