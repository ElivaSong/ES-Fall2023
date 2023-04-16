<a name="000"/>

# 使用VMWare安裝Windows 11

## 目錄
- [我的電腦配置](#111)
- [Windows 11 ISO檔下載](#222)
- [VM安裝WIN11步驟](#333)
- [將系統環境英文改為中文](#444)
- [NAT](#555)

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

11. 選擇NAT:Used to share the host's IP address

![w11-46](https://user-images.githubusercontent.com/126373882/232302465-d136f513-2c03-41c7-9e43-4d772c77c09b.jpg)

12. 點選「Finish」，開始安裝虛擬機器。

![w11-10](https://user-images.githubusercontent.com/126373882/232272326-4d080ce1-f119-4b98-bf73-a00c44cfaa0f.png)

13. 正在建立虛擬硬碟。

![w11-11](https://user-images.githubusercontent.com/126373882/227757899-ad443330-8d0b-47c6-a798-101bcf91e822.jpg)

14. 按鍵盤的任一按鍵，開啟安裝程式。

![image](https://user-images.githubusercontent.com/126373882/226159411-c200bdf6-9ae4-41ae-80f9-292973a572be.png)

15. 點選「下一步」，開始安裝Windows 11。(依個人需求選擇中文or英文)

![w11-12](https://user-images.githubusercontent.com/126373882/232272764-ac960383-156b-4d0f-a020-e5caf630e75d.jpg)
   
![image](https://user-images.githubusercontent.com/126373882/232272551-361ba8a0-2448-4c87-8ee8-2a68b2ca1864.png)

16. 沒有金鑰的話可先跳過。

![w11-13](https://user-images.githubusercontent.com/126373882/232273187-16a4ad1b-cf4e-47b3-a40d-c401f73a19df.jpg)

17. 選W11 Pro → Next。

![w11-14](https://user-images.githubusercontent.com/126373882/232273325-468f24a4-dfb0-4ad6-86a7-b8eed32b3691.jpg)

18. 勾選同意 → Next。

![w11-15](https://user-images.githubusercontent.com/126373882/232273416-da9c22e5-afb8-44c7-b710-a40327757b9c.jpg)

19. 選第一個 Upgrade:......

![w11-16](https://user-images.githubusercontent.com/126373882/232273628-594592b1-1d49-4d23-838a-beb1d9bd98c0.jpg)

20. 選New → Size：61440 → Apply → OK → Next

![w11-18](https://user-images.githubusercontent.com/126373882/232273818-0cb88c37-8e9e-4b6d-b866-226defc434a8.jpg)

![w11-19](https://user-images.githubusercontent.com/126373882/232279102-dbf9f797-ec13-4918-a273-64febf8e5a0d.jpg)

![w11-20](https://user-images.githubusercontent.com/126373882/232279166-10cb13d9-edeb-4cd0-b9f3-114b9f3b34e2.jpg)

21. 建立中

![w11-22](https://user-images.githubusercontent.com/126373882/232279264-7cfe7010-290b-487e-808f-2090b312d3e7.jpg)

22. 選擇國家 → 鍵盤設定(也可先Skip後面再設定)。

![w11-23](https://user-images.githubusercontent.com/126373882/232279292-8158636f-8c6a-4040-9141-f51437a70fef.jpg)

![w11-24](https://user-images.githubusercontent.com/126373882/232279298-4209795d-52a5-4be8-ab30-313224167d2e.jpg)

![w11-25](https://user-images.githubusercontent.com/126373882/232279536-5e1a3222-d905-4f03-83de-5bd9f5777c88.jpg)

![w11-26](https://user-images.githubusercontent.com/126373882/232279457-cb86403f-477c-47c8-bdf8-b9219667e5e5.jpg)

23. 選擇設置：Set up for personal use (個人) / Set up for work or school (工作or學校)

![w11-28](https://user-images.githubusercontent.com/126373882/232279606-dc4295ba-9c12-4423-85df-b82b485e60bc.jpg)

24. 登入Microsoft帳號 / 密碼

![w11-29-1](https://user-images.githubusercontent.com/126373882/232280179-cf6708a5-9102-42bc-916f-1ca27e74531e.jpg)

![w11-30-1](https://user-images.githubusercontent.com/126373882/232280189-9676168f-815e-4927-ba9c-6aba72d31f2b.jpg)

25. 設定密碼

![w11-32](https://user-images.githubusercontent.com/126373882/232280070-39715ffd-7206-484a-8530-17fb211f2b76.jpg)

26. Next → Next → Skip → Next

![w11-33](https://user-images.githubusercontent.com/126373882/232280287-d5b04af4-64c5-4a8f-94df-e536acef66bf.jpg)

![w11-34](https://user-images.githubusercontent.com/126373882/232280292-f09d4a71-cb5a-4748-82c5-241b60aec7e4.jpg)

![w11-35](https://user-images.githubusercontent.com/126373882/232280299-e1ec224f-60da-4518-81ee-5aa240ab7f83.jpg)

![w11-36](https://user-images.githubusercontent.com/126373882/232280304-39c8b9c0-9fac-4a58-83ae-fd792d0b6a06.jpg)

<a name="444"/>

27. 將系統環境(英文)改為中文

![w11-38](https://user-images.githubusercontent.com/126373882/232280743-c1225c4f-d9aa-4a01-907f-2099de4e9289.jpg)

![w11-39](https://user-images.githubusercontent.com/126373882/232280749-314da438-bd0e-4557-b434-4b83fb9022b7.jpg)

![w11-41](https://user-images.githubusercontent.com/126373882/232280871-c0ff6067-1cc7-4cba-8d0f-29e28b29e53d.jpg)

![w11-42](https://user-images.githubusercontent.com/126373882/232280873-b4de2c21-5f08-411b-833b-87c08fc05f23.jpg)

![w11-43](https://user-images.githubusercontent.com/126373882/232280875-241914a1-da16-4a0b-afd6-5d77e8fde03c.jpg)

Windows 11已經安裝完成，如下圖所示。

![w11-37](https://user-images.githubusercontent.com/126373882/232274036-04e5e918-1f6f-420a-891c-cf33825e9489.jpg)

<a name="555"/>

### NAT

![w11-45-1](https://user-images.githubusercontent.com/126373882/232303248-ec49e6d9-68a5-4d86-aa4b-9e4fb497259f.jpg)

![w11-47-1](https://user-images.githubusercontent.com/126373882/232303296-725ce6bf-7dda-4906-8e03-147066423e4c.jpg)


[TOP](#000)
