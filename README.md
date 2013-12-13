# TUNet CLI

version 0.0.1

----

清華校園網命令行版用戶認證工具。

用於無圖形界面之環境。可顯示當前在線狀態、登入登出校園網。

1.  顯示在線狀態

    ```sh
    python tunet.py
    ```

2.  登入

    ```sh
    python tunet.py -l
    
    # 使用文件保存的用戶信息（計劃中，尚未實作）：
    python tunet.py -lf user.txt
    ```

3.  登出

    ```sh
    python tunet.py -o
    ```

4.  顯示幫助

    ```sh
    python tunet.py -h
    ```

----

### TODO

* [ ] 用文件保存/讀取用戶名與密碼（md5散列值）
* [ ] 處理網絡異常
* [ ] 將服務器原始錯誤信息改為提示信息
* [ ] 多語言（不一定實作…因為無圖形界面時貌似不需要多語言？）
