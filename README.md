# DBA_Review_2021
this is a helper to install MySQL server client app &amp; UI software called MySQLWorkbench 


# Mac OS 系統隱私與安全的設定

  
  請詳截圖 16、17。


# 官方網站的小路徑

倘若下載後，出現 crash 請確認版本號與作業系統版本是否相容！ 否則會狂踩到 Crash 的坑 -> (截圖 18)

https://downloads.mysql.com/archives/workbench/

懶得登入會員，都請直接將頁面往下拉 -> no thanks , just download. 

如使用 macOS，請確認隱私權與安全的設定。


# 啟用 MySQL Server

* 關於 MySQL 客戶端軟體，下載完成會預設 root 的密碼，請詳記！！！ （截圖 3、6、11）

* 創建 instance 即 DB 實例，切記要勾選下方的 password 進入點，而非上方的，這會影響 MySQLWorkbench 能否連線得到！ (截圖 15)

 ![](https://raw.githubusercontent.com/QueenieCplusplus/DBA_Review_2021/main/15.png)

* 至系統偏好設定左下方，能見到 MySQL Client Server，可以啟動 (截圖4、5)


# MySQL Shell

* 確認下載後檔案的路徑


        which
     
        whereis
        
        find / -name


  ![](https://raw.githubusercontent.com/QueenieCplusplus/DBA_Review_2021/main/0b.png)
  

* 設定環境變數 

  ![](https://raw.githubusercontent.com/QueenieCplusplus/DBA_Review_2021/main/8.png)
  
  
* 確認環境變數 

      sorce 設定檔 或是 重開 prompt 視窗，兩者均可。

      echo $PATH
  
  ![](https://raw.githubusercontent.com/QueenieCplusplus/DBA_Review_2021/main/9.png)
  
  
* 之後啟動 shell 就不用在呼叫冗長的 path ，可以直接呼叫 mysql 來取用。另外，溫馨提醒 mysql 的密碼是自定義的，不是輸入系統的密碼。 （截圖 3、6、11）

   ![](https://raw.githubusercontent.com/QueenieCplusplus/DBA_Review_2021/main/11%20輸入mysql%20密碼%20非系統管理員密碼.png)

# MySQL Workbench

兩軟體安裝完成後，啟動 MySQL Server 並且使用 MySQLWorkbench 匯入測試 sql 腳本，https://github.com/QueenieCplusplus/DBA_Review_2021/blob/main/database.sql

  ![](https://raw.githubusercontent.com/QueenieCplusplus/DBA_Review_2021/main/19.pn)
  
  ![](https://raw.githubusercontent.com/QueenieCplusplus/DBA_Review_2021/main/0a.pn)

