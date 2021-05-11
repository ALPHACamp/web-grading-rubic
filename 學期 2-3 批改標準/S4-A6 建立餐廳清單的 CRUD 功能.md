# A6 餐廳清單擴充 CRUD 功能

> 💡  在寫這份作業之前，請你務必了解 <a href="https://github.com/ALPHACamp/web-grading-rubic" target="_blank">ALPHA Camp 作業回饋機制</a>，包括助教會如何批改你的作業，以及你該怎麼使用助教回饋來幫助自己進步

## 題幹
參考課程平台([連結](https://lighthouse.alphacamp.co/courses/42/assignments/1038))。

## 指定規格與功能

1. 以 To-do List 為範例，打造以下功能
   1. 使用者可以新增一家餐廳
   2. 使用者可以瀏覽一家餐廳的詳細資訊
   3. 使用者可以瀏覽全部所有餐廳
   4. 使用者可以修改一家餐廳的資訊
   5. 使用者可以刪除一家餐廳
2. 建立資料庫，並設定 Express 專案與資料庫的連線
3. 把這支 [restaurant.json](https://drive.google.com/file/d/1W-BD9-c8zJRYCwAD8yhqQdLwcUdN8GZi/view) 裡的資料當成種子資料，完成後新增 `npm run seed` 腳本
4. 首頁 index 頁面需與題幹指定的 wireframe 一致
5. 其他頁面請參考上個章節的樣板，可自行發揮創意，優化使用體驗 (例如：點擊餐廳照片可直接進入 show page、或是在執行刪除前會瀏覽器會跳出提醒視窗等)

若順利完成指定規格，代表你能夠做到：

- 能完成 CRUD 功能與路由設計
- 建立 Express & MongoDB 的連線
- 導入種子資料
- 透過 body-parser 從 POST 方法的路由中取得表單資料
- 根據指定的設計稿完成畫面

## 期待你現階段能做到....

<table>
  <thead style="font-weight: bold; border-bottom: 2px solid #999;">
    <tr>
      <th>觀察角度</td>
      <th>現階段期待你做到⋯⋯</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>程式架構與品質</td>
      <td>
        <ul>
          <li>遵守 JavaScript Standard style (建議安裝自動檢查套件)</li>
          <li>有意義的變數與函式命名</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與動線</td>
      <td>
        <ul>
          <li>根據指定的設計稿完成畫面</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>開發實務 & 第三方工具應用</td>
      <td>
        <ul>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>撰寫清楚明瞭的 README</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>


若你的作業「指定規格」都完成，「期待結果」也沒有重大問題，助教會判定 `Meet Expectation`，代表你已經掌握了此階段的學習內容，可以繼續前進。

若助教發現你「沒有做到產品該有的規格」或是「犯了重大錯誤」，會給你 `Try Harder` 標記，提醒你停下來釐清問題。修正完成後，可以 tag 助教重新判定。

---
## 行有餘力，可參考優化方向
以下我們蒐集了過去學長姐在行有餘力時，會自行延伸學習的方向，並不是每個人現階段都需要攻略這些項目。

行有餘力時，你可以從下方挑選一些有共鳴的項目來優化作業，也歡迎你接續發想新的優化項目。不過請別忘記先守住上述的基本盤再來挑戰唷！

<table>
  <thead style="font-weight: bold; border-bottom: 2px solid #999;">
    <tr style="font-weight: bold;">
      <th>觀察角度</td>
      <th>參考優化方向</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>程式架構與品質</td>
      <td>期待同學開始意識到，程式開發不只是能夠運行功能，且包含異常處理、功能可擴充、可維護性思維，以利後續具備規劃功能、優化功能、有品質交付等能力，可能優化方向包括：
        <ul>
          <li>寫出更加簡潔明瞭程式碼，e.g. 運用解構賦值、三元運算等技巧</li>
          <li>handlebars 自定義 helper</li>
          <li>設計具有意義的路由架構 or 進階資料庫搜尋方法</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與動線</td>
      <td>
        <ul>
          <li>響應式網頁、表單資料驗證、搜尋資料為空處理、自刻網頁</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>開發實務 & 第三方工具應用</td>
      <td>
        <ul>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>撰寫清楚明瞭的 README</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
