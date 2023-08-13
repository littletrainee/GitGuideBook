# IV.克隆與分支
在瀏覽線上的原始碼代管服務平台時，對某個<font color=lightgreen>庫</font>有興趣，而且瀏覽過該庫所提供的代碼覺得某些部份可以修改或優化時，可以在平台上對該庫進行<font color=orange>分叉(fork)</font>的動作，這個動作類似開新的<font color=lightgreen>分支</font>，但是這個分支並不屬於原本的庫，而是類似<font color=orange>切割</font>的概念，接下來會分別說明克隆與分支的操作。
## 克隆
若再瀏覽平台的列表時看到該專案有興趣比如下圖的例子：<br>
![](./CloneAndBranch01.png)<br>
**在探索的其間找到有興趣的專案**<br><br>
![](./CloneAndBranch02.png)<br>
**對這個庫的專案有興趣或是想要基於這個庫的架構開發新的不同軟體可以按上方的<font color=lightgreen>"Fork"</font>按鈕**<br><br>
![](./CloneAndBranch03.png)<br>
**由於原本的專案是屬於開源的方式因此權限已經被綁定不能設為私有。<font color=lightgreen>描述</font>可以選擇要寫下什麼方向，修改或是切割成新的專案等等。確認好之後就可以按下<font color=lightgreen>"Fork儲存庫"</font>**<br><br>
![](./CloneAndBranch04.png)<br>
**這時候眼尖的會發現庫的名稱下會有一小行註明這個專案是<font color=lighblue>fork自其他人的庫</font>，到這時候網頁上的<font color=lightgreen>"Fork"</font>工作就完成了，接下來本地要對這個庫進行克隆下載的動作，同樣確認傳輸類行為<font color=orange>HTTP</font>並且複製URL**<br>
**<font color=red>P.S.</font>** 如果不Fork也是可以，但基本要確認這個庫的所有權是否為自己的，如果不是自己的克隆下來是肯定不能推送上去，更何況同公司不同部門之間的干預影響程度會有多大。<br><br>
![](./CloneAndBranch05.png)<br>
**對本地來說遠端庫上的專案是不存在的，因此克隆的概念類似創建新的專案，點選<font color=lightgreen>"複製"</font>**<br><br>
![](./CloneAndBranch06.png)<br>
**這邊要填上剛剛在網頁上<font color=lightgreen>複製的URL</font>，並且設定好專案在本地<font color=lighblue>儲存的位置</font>**<br><br>
![](./CloneAndBranch07.png)<br>
**接著按下<font color=lightgreen>"複製"</font>**<br><br>
![](./CloneAndBranch08.png)<br>
**到這時候就算是<font color=yellow>克隆</font>完成了，但如果沒進行接下來的動作，會一直重複無意義的提交與推送，這是因為每次開啟<font color=purple>Visual Sutdio 2017</font>都會修改某幾個檔案，又會添加根本與此專案完全無相關的東西，但這些檔案對.net認為是必須的，因此這些用不到的檔案或是個人認為不需要推到遠端庫上的檔案或資料夾可以註記在<font color=orange>.gitignore</font>內，這樣IDE每次在開啟專案即便添加或改動這些無相關的檔案時，就不會自行去比對與上次推送的提交有什麼差異**<br><br>
![](./CloneAndBranch09.png)<br>
**點選<font color=lighblue>"連線"</font>分頁**<br><br>
![](./CloneAndBranch10.png)<br>
**點選<font color=lightgreen>"設定"</font>分頁**<br><br>
![](./CloneAndBranch11.png)<br>
**點選<font color=lightgreen>"存放庫設定"</font>**<br><br>
![](./CloneAndBranch12.png)<br>
**點選<font color=lightgreen>"加入"</font>**<br><br>
![](./CloneAndBranch13.png)<br>
**到這邊就顯示.gitignore已經創建，並且內容已經套用IDE自帶的部份了，後續有需要再添加忽略的部分可以再自行添加**<br>
**<font color=red>P.S.</font>** 創建完要記得<font color=lighblue>commit</font>與<font color=lighblue>push</font>，這樣才算完整的建立。<br>

## 分支
**接續上面的克隆專案，假設現在本身的專案添加的新的檔案，但不確定新增的檔案是否核可，因此可以將現在已經到一個段落的專案放在其他分支上，當核可之後可以將這個分支合併到主幹上，從而使專案在兩個狀態之間不會互相影響，下面來說明如何放在新的分支上：**<br><br>
![](./CloneAndBranch14.png)
**現在新增了一個檔案但不確定這個檔案是否核可，因此可以點選<font color=lighblue>右下角</font>的<font color=lightgreen>"main"</font>**<br><br>
![](./CloneAndBranch15.png)<br>
**點選<font color=lightgreen>"新增分支"</font>**<br><br>
![](./CloneAndBranch16.png)<br>
**這邊要輸入要分支的名稱**<br><br>
![](./CloneAndBranch17.png)<br>
**<font color=lighblue>簽出分支</font>如果不勾選的話是會維持在原本的分支，設定好之後可以按下<font color=lightgreen>建立分支</font>**<br><br>
![](./CloneAndBranch18.png)<br>
**可以看到剛剛<font color=lighblue>右下角</font>的<font color=lightgreen>"main"</font>已經變成剛剛新增的分支了。接下來進行提交的動作在，點選<font color=lighblue>分支</font>分頁**<br><br>
![](./CloneAndBranch19.png)<br>
**在這邊填上這份提交的附註說明，有可能是什麼檔案的改動、資料夾變更、或是移除等等**<br><br>
![](./CloneAndBranch20.png)<br>
**當確認訊息完成之後可以按下<font color=lightgreen>全部認可</font>提交目前的進度到本地的庫當中**<br><br>
![](./CloneAndBranch21.png)<br>
**這邊顯示剛剛的提交已經成功了，接下來就是使用同步推送到遠端庫，同樣點選上方的<font color=lighblue>"變更"</font>分頁**
![](./CloneAndBranch22.png)<br>
**點選<font color=lighblue>"同步"</font>分頁**<br><br>
![](./CloneAndBranch23.png)<br>
**這邊可以檢視到剛剛提交到本地庫的部分，按下<font color=lightgreen>"推送"</font>的選項，就會開始執行推送這個分支到遠端儲存庫**<br><br>
![](./CloneAndBranch24.png)<br>
**到這邊就是已經<font color=lighblue>"推送"</font>完畢，如果需要確認是否有推送成功可以去網頁上面查看**<br><br>
![](./CloneAndBranch25.png)
**在這邊可以切換分支查看分支的狀態與確認專案的發展**

[回上一層](../README.md)