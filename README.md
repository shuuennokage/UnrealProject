## 專題-居家擺設規劃系統
### 一、簡介
### 本專題為基於遊戲引擎與3D建模軟體進行家具擺設的軟體，家具使用Blender建模軟體製作，而程式主體則使用Unreal4引擎編輯，使用者可以用第一人稱在房間內自行擺設家具，並進行家具的自由增刪以及位置調整，系統並會給予提示信息等等。
[structure]: https://images.plurk.com/2wXhZkq6BlM7JujB5pmSXb.png  "pic1"
![Alt text][structure]
> 圖一：系統架構圖
### 二、動機與目的
### 由於對於遊戲以及3D建模有高度興趣，且在接觸IKEA的室內擺設模擬系統之後，但因有感於其視野角度的侷限，以及擺設家具時略為薄弱的臨場感，遂欲建立一個由第一人稱視點擺設家具的系統，讓使用者能以在房間內的視角自由的配置家具，感受身歷其境的感覺，並同步增進建模技術。
### 三、研究方法
* (一)使用Blender建造家具模型：利用Blender的各種功能建立各式各樣的家具模型，並且利用Light Map與各種功能塑造家具的外觀與質感。

[blender]: https://images.plurk.com/4bguthUO12oNdgYi74nrvS.png "pic2"
![Alt text][blender]
> 圖二：運用Blender建模示意圖
* (二)使用Unreal Engine建造系統：利用Unreal Engine的強大藍圖(Blueprint)及環境渲染能力，製造出可以放置家具的房間環境。

[unreal]: https://images.plurk.com/2D77pTz7D0ICiGwPj3jIgg.png "pic3"
![Alt text][unreal]
> 圖三：運用Unreal藍圖開發示意圖
### 四、測試結果
### 系統開始後，可在場景內自由走動，並依照自己的喜好擺設家具，且可自由與家具互動與刪除家具。並且在地圖中會有偵測機制，除了空間的利用度之外，也會去偵測可行走性以及家具擺放的危險性等等，讓家具擺放可以不只是單純的擺設，更可以從不同角度去分析，並且從自己的角度建立屬於自己的美感體驗。
[project]: https://images.plurk.com/7dh1J1bUuxzPCjf6xsAhFk.png "pic3"
![Alt text][project]
> 圖四：房間擺設實際示意圖
### 五、結論
### Unreal Engine的便利功能可即時演算各種家具在房間內擺放的光影情形，並模擬各項物理性質，讓使用者可以盡量以直接擺設家具的方式進行各種模擬。未來也期望可以精進UI以及內部偵測功能的設計，讓系統更加完善，增進家具擺設規劃的效率以及滿足各種使用者的需求。
