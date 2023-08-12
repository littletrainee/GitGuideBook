# III.推送與標籤
在建立完遠端庫、修改專案、預提交給PM審查或保存當前專案進度都要推送過後才能確保專案統一管理在遠端庫，下面分別說明推送與標籤的部分。
## 推送
**假設現在所編寫的專案已經全部都儲存完成了，再來就要進行推送，其流程如下：**<br>
<br>![](./PushAndTag01.png)<br>
**按<font color=lighblue>右下角</font>的<font color=lightgreen>"新增至原始檔控制"</font>的選項**<br><br>
![](./PushAndTag02.png)
**點選<font color=lightgreen>"Git"</font>**<br><br>
![](./PushAndTag03.png)
**這時候右邊的<font color=lighblue>Team Explorer - 同步處理</font>會出現<font color=lighblue>推送</font>分頁，由於還沒有添加遠端庫的位置因此要在這邊添加，點選推送至遠端存放庫子標籤的<font color=lightgreen>"發行Git存放庫"</font>**<br><br>
![](./PushAndTag04.png)<br>
**這邊要提供<font color=lighblue>遠端庫的URL</font>**<br> <br>
![](./PushAndTag05.png)<br>
**<font color=purple>Visual Studio 2017</font>預設是走<font color=orange>HTTP</font>，因此必須使用<font color=orange>HTTP</font>的選項。確認選項是選<font color=orange>HTTP</font>後按右邊的<font color=lightgreen>複製URL</font>按鈕**<br><br>
![](./PushAndTag06.png)
**貼上之後按下<font color=lightgreen>"發行"</font>就可以綁定現在的專案與遠端庫的連結** <br><br>
![](./PushAndTag07.png)
**由於是透過<font color=purple>Visual Studio 2017</font>創建的庫，因此也會一併進行<font color=lighblue>commit</font>與<font color=lighblue>push</font>，下面兩個狀態提示左邊是<font color=lighblue>"待推送的數量"</font>右邊是<font color=lighblue>"已變更的檔案、資料夾總數"</font>**<br><br>

## 標籤
**若推送的專案沒有設置標籤的話新的檔案會一直堆疊上去，當數量一多的時候會很難找到先前所推送的穩定或共同核可的版本，這時候就是要付加上標籤好讓後續追蹤時可以快速地從某個版本開始動作，下面來講解如何添加標籤：**<br>
![](./PushAndTag08.png)<br>
**點選<font color=lighblue>Team Explorer</font>的<font color=yellow>首頁</font>分頁**<br><br>
![](./PushAndTag09.png)<br>
**點選<font color=yellow>標籤</font>分頁**<br><br>
![](./PushAndTag10.png)<br>
**點選<font color=lighblue>"新增標籤"</font>**<br><br>
![](./PushAndTag11.png)<br>
- **<font color=yellow>標籤名稱</font>：** 一般都會用版本號作為標籤名稱。
- **<font color=yellow>標籤訊息</font>：** 可以填上這個標籤主要是什麼狀態，可能是<font color=lighblue>已發行</font>、<font color=lighblue>內部共識</font>或<font color=lighblue>不穩定版當中的較穩定版</font>等等，可以幫助團隊或自己更容易了解這個標籤的附註說明。<br><br>
![](./PushAndTag12.png)<br>
**當上述確定之後可以按下<font color=lightgreen>建立標籤</font>。** <br><br>
![](./PushAndTag13.png)<br>
**<font color=red>這邊要注意的是標籤雖然已經建立但是這是在前面的推送過後才建立的，因此還需要再推送一次</font>，按下<font color=lightgreen>推送全部</font>，這樣才會把標籤一併放置遠端庫。**<br><br>
![](./PushAndTag14.png)
**到此當前進度才算告一個段落，之後可以去網頁上查看剛剛推送的是否有成功**<br><br>
![](./PushAndTag15.png)
[返回目錄](../README.md)
