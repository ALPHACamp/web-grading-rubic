# Adele 的歌詞本

### 題幹
參考課程平台([原文連結](https://lighthouse.alphacamp.co/courses/41/assignments/1006))。

### 驗收能力
* 綜合運用以下能力，做出有意義的網頁：
  * 處理 Array x Object 來創造曲目清單的 DOM 元素 
  * 設計事件驅動流程，在適當時機發送 Ajax 請求取得 API 資料
  * 取得 API response 之後，觀察 Array x Object 的資料結構，選出需要的資料來修改 DOM 元素
### 評量項目
* 驗收項目完整度及優化
* 程式邏輯
### Try Harder
* 無法成功搭配 DOM 操作 (任一項)：
  * 透過官方文件的要求向 axios 發出請求和獲得回傳
  * 在左欄透過 album 物件動態產生曲目
  * 在右欄呈現歌詞
### Meet Expectation
若助教看見同學完成這些，會認定這份作業通過：
* 成功搭配 DOM 操作 (每一項)：
  * 透過官方文件的要求向 axios 發出請求和獲得回傳
  * 在左欄透過 album 物件動態產生曲目
  * 在右欄呈現歌詞
### Exceed Expectation
當同學達成 Meet Expectation 的標準後，並達到以下標準 (缺一不可)：
* 查閱 Bootstrap 官方文件，成功使用 pill 在左欄達到題目效果
* 使用 axios 時的語法是否乾淨俐落 (例如：將 BASE_URL 獨立設為一個變數)
* 設定監聽器時，使用事件委派方式，並拓善使用 event.target, 由歌詞清單表統一監聽歌詞的點擊
