<a name="111"/>

# VMware_Ubuntu：安裝 Apache 網頁伺服器與其應用

## 目錄
- [什麼是Apache？](###222)
- [安裝](###333)
- 

-----

<a name="222"/>

### 什麼是Apache網頁伺服器(Web Server) ？

![image](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/1b47e8a4-67f0-47a1-af29-c8d183816d17)

　　Apache HTTP Server是一個免費和開放原始碼的網頁伺服器，是世界上使用最廣泛的 Web 伺服器（Web Server），通過互聯網提供網絡內容。Apache HTTP 服務器項目旨在為 UNIX 和 Windows NT 等操作系統開發和維護開源 HTTP 服務器。該項目旨在提供一個安全、高效、可擴展的服務器，提供 HTTP 服務 sync 與當前的網絡標準。
  
  　Apache的特點之一是其跨平台性，可以在大多數電腦操作系統上運行，包括Windows、Linux、Mac OS等。它以其穩定性、可靠性和可定制性而廣受用戶青睞，讓用戶充分體驗到開放源碼的優點。




<a name="333"/>

### 安裝

1. 對桌面點選右鍵 > Open in Terminal

![ub-1](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/c924f9a5-b5d4-4740-aa75-0846612c430c)

2. 打上 `sudo apt update && sudo apt install apache2` 開始進行安裝

![ub-2_1](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/fc6e6e3c-b254-455b-869b-29d3928ddda8)

![ub-2_2](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/298ab85d-c086-4a56-98e5-11ad489287ac)

3. 測試：確認是否有active (running)？

打上 `sudo service apache2 status`

![ub-3](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/6428b96d-691d-474c-9a49-00f2eab5ef91)

4. 從你的Ubuntu Browser和Windows Browser來連到你的Web Site看看~

開啟瀏覽器 > 輸入IP：127.0.0.1

![ub-4](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/895c1f4b-da9e-46a8-98a1-ff13ecd9c0ed)
> Note：如果有問你是否要Configure Network, 建議選No Configure.

5. 如何安裝Ubuntu的網路工具組 net-tools？

打上 `sudo apt install net-tools`

![ub-5](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/1b0d1a07-a08b-42d6-b7eb-adef0f5d2c27)

6. 如何檢查 Ubuntu IP？

![ub-7](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/7e0bd1d0-fedb-415b-a93d-beb3f4d3d5a2)

![ub-6](https://github.com/ElivaSong/ES-Fall2023/assets/126373882/8678701a-ab98-416e-9294-e3b9c03225bc)


[TOP](#111)
