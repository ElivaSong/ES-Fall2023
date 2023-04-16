<a name="000"/>

# 使用VMWare安裝Windows 11

## 目錄
- [我的電腦配置](#111)
- [Windows 11 ISO檔下載](#222)
- [VM安裝WIN11步驟](#333)

<a name="111"/>

### 我的電腦配置：

<div align="p1">
     <img 
      src="https://user-images.githubusercontent.com/126373882/227756346-65945d41-c69f-4380-bdf7-77136d518d4c.jpg" 
      width="75%" height="75%">
    </div>

<a name="222"/>

## Windows 11 ISO檔下載：

> Windows 11 ISO Downloads：https://www.microsoft.com/zh-tw/software-download/windows11

<div align="p2">
     <img 
      src="https://user-images.githubusercontent.com/126373882/226158422-b925a321-1e6c-49d5-ab34-ad82a99c48a7.jpg" 
      width="60%" height="60%">
    </div>

<a name="333"/>

### Windows 11安裝步驟：
1. 開啟VMware Workstation Player。

![image](https://user-images.githubusercontent.com/126373882/227761068-b34250e9-92b4-4c5b-84b5-bcaac9048244.png)

2. 點選「Create a New Virtual Machine」。
<div align="p3">
     <img 
      src="https://user-images.githubusercontent.com/126373882/227756631-75e8fbb1-2ecc-45b3-8547-45a07775df47.jpg" 
      width="50%" height="50%">
    </div>

3. 選擇「Installer disk image file (iso)」，點選「Browse…」。  
   選擇Windows 11光碟ISO映像檔，點選「開啟」。
<div align="p4">
     <img 
      src="https://user-images.githubusercontent.com/126373882/227756662-9efa9bc4-335b-427b-8224-8adb98b5ca1c.jpg" 
      width="80%" height="75%">
    </div>

4. 點選「Next」。

![w11-3](https://user-images.githubusercontent.com/126373882/227756676-b41e418a-af97-4f9d-b681-89975de4ca77.jpg)

5. 輸入自訂的虛擬機器名稱；Location為預設儲存路徑，若需變更請點選「Browse…」。

![w11-4](https://user-images.githubusercontent.com/126373882/227756702-ffce0fcd-ffc9-43b9-b125-49e3c4c2b66d.jpg)

6. 使用預設的選項，輸入自訂的密碼，點選「Next」，啟用encrypted Trusted Platform Module（信賴平台模組，縮寫：TPM）。

![w11-5](https://user-images.githubusercontent.com/126373882/227756714-15b3792e-3aa4-4200-a940-349b1fdc75ce.jpg)

7. 自訂虛擬硬碟的大小，選擇「Store virtual disk as a single files」，將虛擬硬碟儲存為單一檔案，點選「Next」。

![w11-6](https://user-images.githubusercontent.com/126373882/227756738-a43b7c0a-8901-4872-8646-9e6b8429976a.jpg)

8. 點選「Customize Hardware…」。

![w11-7](https://user-images.githubusercontent.com/126373882/227756746-5e2c8aa1-c672-404a-97ff-c161871bbab7.jpg)

9. 在「Memory」的選項，調整記憶體至適當的大小〈建議為實體記憶體的1/3 - 1/2之間〉。

![w11-8](https://user-images.githubusercontent.com/126373882/227756750-c61dc26d-80bb-4d2b-9de0-381eccbea734.jpg)

10. 在「Processors」的選項，選擇CPU的核心數。→ Close

![w11-9](https://user-images.githubusercontent.com/126373882/232272239-5ab7d93e-78e7-46eb-b69a-2e5e247bbac2.jpg)

11. 點選「Finish」，開始安裝虛擬機器。

![w11-10](https://user-images.githubusercontent.com/126373882/232272326-4d080ce1-f119-4b98-bf73-a00c44cfaa0f.png)

12. 正在建立虛擬硬碟。

![w11-11](https://user-images.githubusercontent.com/126373882/227757899-ad443330-8d0b-47c6-a798-101bcf91e822.jpg)

13. 按鍵盤的任一按鍵，開啟安裝程式。

![image](https://user-images.githubusercontent.com/126373882/226159411-c200bdf6-9ae4-41ae-80f9-292973a572be.png)

14. 點選「下一步」，開始安裝Windows 11。(依個人需求選擇中文or英文)

![w11-12](https://user-images.githubusercontent.com/126373882/232272764-ac960383-156b-4d0f-a020-e5caf630e75d.jpg)
   
![image](https://user-images.githubusercontent.com/126373882/232272551-361ba8a0-2448-4c87-8ee8-2a68b2ca1864.png)

15. 沒有金鑰的話可先跳過。

![w11-13](https://user-images.githubusercontent.com/126373882/232273187-16a4ad1b-cf4e-47b3-a40d-c401f73a19df.jpg)

16. 選W11 Pro → Next。

![w11-14](https://user-images.githubusercontent.com/126373882/232273325-468f24a4-dfb0-4ad6-86a7-b8eed32b3691.jpg)

17. 勾選同意 → Next。

![w11-15](https://user-images.githubusercontent.com/126373882/232273416-da9c22e5-afb8-44c7-b710-a40327757b9c.jpg)

18. 選第一個 Upgrade:......

![w11-16](https://user-images.githubusercontent.com/126373882/232273628-594592b1-1d49-4d23-838a-beb1d9bd98c0.jpg)

19. 選New → Size：61440 → Apply

![w11-18](https://user-images.githubusercontent.com/126373882/232273818-0cb88c37-8e9e-4b6d-b866-226defc434a8.jpg)









Windows 11已經安裝完成，如下圖所示。

![w11-37](https://user-images.githubusercontent.com/126373882/232274036-04e5e918-1f6f-420a-891c-cf33825e9489.jpg)


<div align="p5">
     <img 
      src="https://user-images.githubusercontent.com/126373882/227757908-faf9da8e-2e7f-41f5-ace3-42ca880f286b.jpg" 
      width="50%" height="50%">
    </div>





[TOP](#000)
