# **3D 隕石穿越遊戲 (3D Asteroid Runner Game)**

[直接體驗](https://jeffery8910.github.io/3D-Asteroid-Runner-Game/)

## **遊戲描述**

這是一款刺激的 3D 網頁遊戲，玩家需要操控一艘太空船，在不斷來襲的隕石流中穿梭，挑戰自己的反應極限並獲得高分。當隕石進入警戒區時會變紅，此時若發生碰撞將會損失生命值。

## **如何遊玩**

### **控制方式**

* **鍵盤：**  
  * 向上箭頭 或 W 鍵：向上移動太空船  
  * 向下箭頭 或 S 鍵：向下移動太空船  
  * 向左箭頭 或 A 鍵：向左移動太空船  
  * 向右箭頭 或 D 鍵：向右移動太空船  
* **觸控螢幕 / 滑鼠點擊：**  
  * 點擊畫面下方的 ▲ 按鈕：向上移動太空船  
  * 點擊畫面下方的 ▼ 按鈕：向下移動太空船  
  * 點擊畫面下方的 ◀ 按鈕：向左移動太空船  
  * 點擊畫面下方的 ▶ 按鈕：向右移動太空船

### **遊戲目標**

* 盡可能長時間地躲避隕石。  
* 每成功躲避一個飛出視野的隕石，即可獲得分數。  
* 當隕石進入警戒區（變為紅色）並與太空船碰撞時，會損失一點生命值。  
* 當生命值耗盡時，遊戲結束。

## **遊戲特色**

* **真 3D 視覺效果：** 使用 Three.js 函式庫打造的沉浸式 3D 環境。  
* **動態隕石流：** 隨機生成不同大小、形狀和飛行軌跡的隕石。  
* **生命值系統：** 玩家擁有多次機會，以愛心圖示顯示。  
* **警戒區警告：** 當隕石接近玩家時，會變為紅色以示警告，此時碰撞才會扣除生命值。  
* **計分系統：** 根據成功躲避的隕石數量來計分。  
* **響應式控制：** 支援鍵盤、觸控螢幕和滑鼠點擊操作。  
* **遊戲結束與重新開始：** 清晰的遊戲結束畫面，並提供重新開始遊戲的選項。  
* **視覺效果：** 包含霧效、光照以及太空船和隕石的簡單模型。

## **使用技術**

* **HTML5:** 網頁基本結構。  
* **CSS3 (Tailwind CSS):** UI 介面樣式和佈局。  
* **JavaScript (ES6+):** 遊戲主要邏輯和互動。  
* **Three.js (r128):** 核心 3D 圖形渲染函式庫。

## **如何執行**

1. 將提供的完整 HTML 程式碼複製。  
2. 將其儲存為一個 .html 檔案（例如 asteroid\_runner.html）。  
3. 使用現代網頁瀏覽器（如 Chrome, Firefox, Edge, Safari）開啟該 HTML 檔案即可開始遊戲。

## **未來可能的增強功能**

* **更精緻的太空船與隕石模型：** 引入更細緻的 3D 模型和紋理。  
* **多樣化的隕石種類：** 例如，某些隕石可能需要多次撞擊才能摧毀（如果加入射擊功能）。  
* **道具系統：** 例如，暫時無敵、加分、恢復生命值等道具。  
* **射擊功能：** 允許玩家射擊並摧毀隕石。  
* **背景音樂與音效：** 增加遊戲的沉浸感。  
* **排行榜：** 記錄並顯示高分。  
* **難度等級選擇：** 提供不同的難度選項。  
* **更複雜的關卡設計：** 例如，特定的隕石陣列或 Boss 戰。

希望這份 Readme 文件對您有所幫助！
