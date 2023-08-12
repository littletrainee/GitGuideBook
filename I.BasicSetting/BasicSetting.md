# I.基礎的設定

## 安裝Git
 需要先在當前的電腦安裝[git](https://git-scm.com/)版控軟體，否則無法進行版控的操作，以下是安裝git的畫面與當下建議：
![](./BasicSetting1.png)<br>
**版權說名：有需要可以看一下**<br><br>
![](./BasicSetting2.png)<br>
**預設儲存位置：基本上沒特別需求不用改變**<br><br>
![](./BasicSetting3.png)<br>
**在開始是否要顯示git的資料夾：Git預設有幾個程式可以使用，除了一個GUI以外另外的都是終端機**<br><br>
![](./BasicSetting4.png)<br>
**選擇基本編輯文件的工具：Git的設定檔、commit的文檔編輯工具預設是VIM，但個人是推薦用VSCode相較於終端機編輯器會稍微圖形化一點**<br><br>
![](./BasicSetting5.png)<br>
**最初主幹的命名：看團隊或個人的習慣而定，個人是偏好main，但若以master或其他也可以**<br><br>
![](./BasicSetting6.png)<br>
**操作的Git的方式：第一個或第三個都是純終端機，第二個是終端機與第三方混合，**<br><br>
![](./BasicSetting7.png)<br>
**是否要用自帶的SSH工具還是要用第三方的工具：基本上都會選擇自帶的**<br><br>
![](./BasicSetting8.png)<br>
**同上是否要用自帶的HTTP驗證工具還是windows的安全存證：**<br><br>
![](./BasicSetting9.png)<br>
**行尾符號轉換：跨平台開發有關的部分**<br><br>
![](./BasicSetting10.png)<br>
**Git Bash終端機模擬器的配置**<br><br>
![](./BasicSetting11.png)<br>
**git pull的默認動作：預設是第一個**<br><br>
![](./BasicSetting12.png)<br>
**git憑證管理：** 這邊會牽扯到本地透過HTTP推送到<font color=lightgreen>Gitea</font>的帳號問題，如果常態性的推送到不同<font color=lightgreen>Gitea</font>的帳號會建議選擇下面的選項，並且透過終端機的方式推送否則透過<font color=purple>Visual Studio 2017</font>內建的Git外掛會出現無法推送到目標帳號下遠端庫的問題，但只針對一個單一帳號的話上面的選項即可。<br><br>
![](./BasicSetting13.png)<br>
**額外功能**<br><br>
![](./BasicSetting14.png)<br>
**額外功能**<br><br>
![](./BasicSetting15.png)<br>
**安裝中**<br><br>
![](./BasicSetting16.png)<br>
**到這邊就算安裝完畢了**<br><br>

## 本地Git的使用者資訊
在安裝好Git後需要先設定使用者資訊，設定順序如下： <br/>
![](./BasicSetting17.png)<br>
**點選<font color=lightgreen>"檢視"</font><br><br>**
![](./BasicSetting18.png)
**點選<font color=lightgreen>"Team Explorer"</font>的選項**<br><br>
![](./BasicSetting19.png)<br>
**點選旁邊的<font color=lightgreen>小箭頭</font><br><br>**
![](./BasicSetting20.png)<br>
**點選<font color=lightgreen>"設定"</font>**<br><br>
![](./BasicSetting21.png)<br>
**點選<font color=lightgreen>"全域設定"</font>**<br><br>
![](./BasicSetting22.png)<br>
**這邊在<font color=lightgreen>"使用者名稱"</font>與<font color=lightgreen>電子郵件地址</font>設定想要設定的資訊**<br><br>
![](./BasicSetting23.png)<br>
**填完之後按下<font color=lightgreen>"更新"</font>就設定完使用者資訊了**
![](./BasicSetting24.png)<br>


[返回目錄](../README.md)
