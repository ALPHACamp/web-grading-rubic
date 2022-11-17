# S3 ALPHA Shop IV：表單實作

## 驗收標準

> 💡 請優先完成【產品功能與規格】，接著運用下方列表檢查。

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
          <li>綜合應用目前為止學會的 React 技巧，完成指定功能</li>
              <ul>
                  <li>前一題進度 (非本題重點，但應正常運作)：</li>
                      <ul>
                          <li> 實作 StepProgressBar 和 StepController 二個 Component 讓頁面中的 step  能正確顯示</li>
                          <li>實作 Cart Component 讓購物車中的小計能顯示正確數值</li>
              </ul>
          <li>本題指定功能：
              <ul>
                  <li>能正確使用 Context 做全站的 state 變數管理</li>
                  <li>使用 Context 儲存購物車總金額 (小計) 及持卡人姓名、卡號、有效期限及 CCV，並在按下 確認下單 後，能成功 console.log 正確資訊</li>
          </ul>
      </td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
        <td>
          <ul>
          <li>正確解析頁面結構，拆成不同的 component 分開實作。 </li>
          <li>React 的寫法是否符合慣例</li>
          <li>其他常設項目</li>
          <ul>
            <li>程式邏輯是否清晰</li>
            <li>使用 let & const 宣告變數 (不要使用 var)</li>
            <li>變數資料型態保持前後一致</li>
            <li>命名是否有意義、可讀性</li>
            <li>適當運用註解幫助他人快速理解程式碼</li>
            <li>盡量避免多餘的程式碼</li>
          </ul>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與使用者動線</td>
      <td>略
      </td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>略</td>
    </tr>
      <tr>
      <td>軟體開發工具 & 流程</td>
          <td>          <li>撰寫清楚明瞭的 README，可幫助下載專案的人成功啟動專案（若無法照 README 啟動專案直接 try harder）</li>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>需要時，加上有意義的註解</li></td>
    </tr>
  </tbody>
</table>

## 行有餘力的行動建議

若成功完成題目指定功能，則滿足了 `Meet expectations` 標準。

此時，建議同學先整理一下專案的元件拆分以及程式碼易讀性，精進方向包括：

- React 的寫法符合慣例（若按照官方 document 內的建議寫法基本上就會符合）
  - 例如不是用 onClick 而是用 document.addEventListener 就會不符合
- 正確解析頁面結構，拆成不同的 component 分開實作。例如拆分共用的元件以重複利用，或是按邏輯將視覺元件拆分。
- 使用適當的 HTML 元素（例如 input type, name）

## 作業相關資訊

參考課程平台([原文連結](https://lighthouse.alphacamp.co/courses/207/assignments/3951))。
ㄒ
