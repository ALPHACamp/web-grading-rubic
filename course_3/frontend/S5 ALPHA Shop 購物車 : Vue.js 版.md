# ALPHA Shop 購物車 : Vue.js 版

## 驗收標準

> 💡  請優先完成【產品功能與規格】，接著運用下方列表檢查。

下表綜合考量了「實務上該如何做」以及「你目前學會什麼」，需要透過助教分享他從你的作業的觀察，才能幫助我們了解哪些行為已經達到水準、繼續保持，反之，也可能會有需要改善的問題。

<table>
  <thead>
    <tr>
      <th>驗收重點</td>
      <th>現階段期待你做到⋯⋯</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>開發框架/函式庫</td>
      <td>
        <ul>
          <li>綜合應用目前為止學會的 Vue 技巧，包括：</li>
          <ul>
            <li>使用 props 向下傳遞資料</li>
            <li>使用 vue 指令綁定事件</li>
          </ul>
        </ul>
      </td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>
        <ul>
          <li>檔案名稱與 component 名稱是否一致</li>
          <li>正確解析頁面結構，拆成不同的 component 分開實作 - 例如拆分共用的元件以重複利用，或是按邏輯將視覺元件拆分。</li>
          <li>Vue 的寫法是否符合慣例（若按照官方 document 內的建議寫法基本上就會符合）</li>
          <li>其他常設項目</li>
          <ul>
            <li>程式邏輯是否清晰</li>
            <li>使用 let & const 宣告變數 (不要使用 var)</li>
            <li>變數資料型態保持前後一致</li>
            <li>命名是否有意義、可讀性</li>
            <li>適當運用註解幫助他人快速理解程式碼</li>
            <li>盡量避免多餘的程式碼</li>
            <li>遵守 JavaScript Standard style (建議安裝<a href="https://standardjs.com/index.html#install" target="_blank">自動檢查套件</a>)</li>
          </ul>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與使用者動線</td>
      <td>
        <ul>
          <li>依照給定的 wireframe 添加指定功能，元件的數量、功能、元件之間的相對位置要和 wireframe 一致，而 style (顏色、邊距、留白、陰影等地方) 可自行優化</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>略</td>
    </tr>
      <tr>
      <td>軟體開發工具 & 流程</td>
      <td>
        <ul>
          <li>撰寫清楚明瞭的 README，可幫助下載專案的人成功啟動專案</li>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>需要時，加上有意義的註解</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

## 行有餘力的行動建議

若成功完成題目指定功能，則滿足了 `Meed expectations` 標準。

此時，建議同學先整理一下專案的元件拆分以及程式碼易讀性，精進方向包括：

- Vue 的寫法符合慣例（若按照官方 document 內的建議寫法基本上就會符合，反例則是用 document.addEventListener 而非 v-on）
- 正確解析頁面結構，拆成不同的 component 分開實作。例如拆分共用的元件以重複利用，或是按邏輯將視覺元件拆分。
- 使用適當的 HTML 元素（例如 input type, name）
- 結帳二字下方顯示「當前步驟」的元件 (stepper) 不是放在 Vue-Router 內，而且狀態是由 props 控制

若行有餘力，我們規劃了以下挑戰功能，同學可選擇完成，記得在提交作業時向助教說明你選擇了哪些挑戰功能。

注意，並非每位同學都需要攻略這些項目，請你先完成基本規格，行有餘力時再來挑戰。

#### 挑戰 1 (資料處理)

使用者在結帳區塊輸入的資料應被保存。在使用者點擊「確認下單」後，結帳結果會顯示在畫面上，呈現方式有下列兩種：

- 難度一：在 console 上印出來
- 難度二：顯示在 Modal 上

<div style="width:100%"> <a href="https://assets-lighthouse.alphacamp.co/uploads/image/file/16186/ExportedContentImage_01.png" target="_blank"><img style="max-width:700px;width:100%;" src="https://assets-lighthouse.alphacamp.co/uploads/image/file/16186/ExportedContentImage_01.png"></a></div>

#### 挑戰 2 (Router 設定)

使用 Vue-Router 設定，處理「結帳區」的三個階段。使用了 Vue-Router 以後，每按下「下一步」時網址會變，若重新整理還是會留在同一個步驟。

#### 挑戰 3 (使用者體驗)

使用 localStorage 把使用者填過的資料存下來，當頁面重新整理後，填過的資料也不會不見。

終極版本的 live demo 如下：

<div style="width:100%"> <a href="https://i.imgur.com/xOjJNCR.gif" target="_blank"><img style="max-width:700px;width:100%;" src="https://i.imgur.com/xOjJNCR.gif"></a></div>

## 作業相關資訊

參考課程平台([原文連結](https://lighthouse.alphacamp.co/courses/119/assignments/3613))。
