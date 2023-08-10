# II.建立存放庫

建立遠端存放庫有許多種方式這邊以<font color=lightblue>透過網頁的連線</font>與<font color=lightblue>透過Visual Studio 2017的外掛插件</font>建立，以下分別做示範。<br>

## 透過網頁建立
在最初的個人庫上做推送到遠端庫之前必須先建立庫的資訊
<br> ![](./CreateRemoteRepository01.png)

<br> ![](./CreateRemoteRepository02.png)

如畫面所示：

-   <font color=lighblue>擁有者</font>：類似此專案的 PM，擁有這個庫的所有權。
-   <font color=lighblue>儲存庫名稱</font>：庫的名稱，如說明所示，過長的名稱會使庫的主題過於複雜，若需要更多的說明可在下方的<font color=lighblue>描述</font>做陳述。
-   <font color=lighblue>瀏覽權限</font>：可以選擇將目前的庫設為非公開，若有些部分是做測試或是，只能針對特定客戶，則建議勾選。
-   <font color=lighblue>描述</font>：當庫的名稱所無法詳述的部分適合放在這邊作陳述補充，類似研究文獻中的摘要。
-   <font color=lighblue>.gitignore</font>：有些跟專案無關的設定或是僅本機運行的單元測試，不適合、沒必要或是不允許放在庫上的忽略清單，可以是單一個檔案或是一個資料夾。

*   <font color=lighblue>授權條款</font>：非核心技術，或是讓社群、大眾或是合作單位使用的限制條款。
*   <font color=lighblue>讀我檔案</font>：相較於名稱與描述，更加詳細的描述使用過程、使用方向、庫的限制、釋出的版本、已分享的平台等等，可以放上任何與此庫有關的敘述。
*   <font color=lighblue>預設分支</font>：庫類似樹狀的發展方向，所有分支最終的主線，名稱可以自訂為任何名稱。

當上述選項都設定好後產生的結果會類似下圖

<br>![](./CreateRemoteRepository03.png)

## 透過<font color=purple>Visual Studio 2017</font>的外掛插件
### 首先要先在<font color=purple>Visual Studio 2017</font>安裝外掛
![](./CreateRemoteRepository04.png) <br>
**點選<font color=lightgreen>"工具"</font>**<br><br>
![](./CreateRemoteRepository05.png)<br>
**點選<font color=lightgreen>"擴充功能和更新"</font>，美化或是對於增加IDE輔助的功能基本上在這邊都找得到**<br><br>
![](./CreateRemoteRepository06.png)<br>
**在這個畫面先切換分頁到<font color=lightgreen>"線上"</font>**<br><br>
![](./CreateRemoteRepository07.png)<br>
**在<font color=lightgreen>搜尋欄</font>上打上鑰搜尋的<font color=lightgreen>"gitea"</font>**<br><br>
![](./CreateRemoteRepository08.png)<br>
**點選<font color=lightgreen>下載</font>按鈕**<br><br>
![](./CreateRemoteRepository09.png)<br>
**到這邊就是已經<font color=lightyellow>排定擴充功能安裝</font>的完成，要關閉<font color=purple>Visual Studio</font>才會開始安裝。**<br><br>
![](./CreateRemoteRepository10.png)<br>
**由於先前關閉<font color=purple>Visual Studio</font>之前有<font color=lightyellow>排定安裝擴充功能</font>，因此這邊要按下<font color=lightgreen>"Modigy"(調整)</font>才會開始安裝。**<br><br>
![](./CreateRemoteRepository11.png)<br>
**安裝中**<br><br>
![](./CreateRemoteRepository12.png)<br>
**到這邊就是安裝完畢，進入<font color=purple>Visual Studio</font>就可以使用這個功能了。**<br><br>
![](./CreateRemoteRepository13.png)<br>
**該插件的功能是在<font color=lighblue>Team Explorer</font>裡面，因此要點選<font color=lightgreen>"檢視"</font>**<br><br>
![](./CreateRemoteRepository14.png)<br>
**再點選<font color=lightgreen>"Team Explorer"</font>**
![](./CreateRemoteRepository15.png)<br>

### 這時候畫面右邊的<font color=lighblue>"Team Explorer - 連線"</font>會出現<font color=lightgreen>"Gitea"</font>的功能，到這裡就是插件安裝完成，可以按下<font color=lightgreen>"Connect"</font>開始建立連線。
![](./CreateRemoteRepository16.png)<br>
**在這個畫面要先填上登入的<font color=lightgreen>Gitea網址</font>、當時註冊的<font color=lightgreen>帳號</font>與<font color=lightgreen>密碼</font>**<br><br>
![](./CreateRemoteRepository17.png)<br>
**填完之後就可以將<font color=purple>Visual Studio</font>與Gitea做連線**<br><br>
![](./CreateRemoteRepository18.png)<br>
**這時候就如同網頁上一樣可以建立遠端庫了，點選<font color=lightgreen>"Create"</font><br><br>
![](./CreateRemoteRepository19.png)<br>
**填上<font color=lightgreen>庫的名稱</font>、<font color=lightgreen>說明</font>、<font color=lightgreen>是否要增加".gitignore"</font>、<font color=lightgreen>憑證</font>、<font color=lightgreen>是否是私有的</font>以及<font color=lightgreen>本地庫的儲存位置</font>**<br><br>
![](./CreateRemoteRepository20.png)<br>
**填好之後按下<font color=lightgreen>"New"</font>可以建立好庫了**<br><br>
![](./CreateRemoteRepository21.png)<br>


[返回目錄](../README.md)
