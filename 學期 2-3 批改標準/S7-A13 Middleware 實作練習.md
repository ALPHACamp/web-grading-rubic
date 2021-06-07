# A13 Middleware 實作練習

## 💡 瞭解 AC 作業回饋機制

在寫這份作業之前，請你務必充分瞭解 <a href="https://github.com/ALPHACamp/web-grading-rubic" target="_blank">ALPHA Camp 作業回饋機制</a>，瞭解成果如何被審查，才能主動攻略

- `Meet Expectations` 條件：(1) 充分滿足【產品/程式規格與功能】(2)【驗收重點】無重大問題
- `Try Harder`：代表學生需要停下來釐清問題，修正完成後，可 tag 助教重新判定

## 作業題目

參考課程平台([原文連結](https://lighthouse.alphacamp.co/courses/42/assignments/1058))。

## 批改標準 - Q1: 伺服器接收請求紀錄

> 💡  請優先完成【產品/程式規格與功能】，接著運用【驗收重點】列表檢查。

### 產品/程式規格與功能

1. 使用題目指定的 app.js 內容
2. 在路由裡加入一支 middleware
3. 伺服器接到任一請求時，server log 上能正確印出：
   1. 時間戳記 (time-stamps) - 以當地時間 (台北) 顯示
   2. 請求的 HTTP 方法
   3. URL

### 驗收重點

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
          <li>在路由系統中，對所有請求設定統一前置處理</li>
          <li>瞭解在 Express 框架中使用時間戳記的相關方法</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>
        <ul>
          <li>程式邏輯是否清晰</li>
          <li>使用 let & const 宣告變數 (不要使用 var)</li>
          <li>變數資料型態保持前後一致</li>
          <li>命名是否有意義、可讀性</li>
          <li>盡量避免多餘的程式碼</li>
          <li>遵守 JavaScript Standard style (建議安裝<a href="https://standardjs.com/index.html#install" target="_blank">自動檢查套件</a>)</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與使用者動線</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>(略)</td>
    </tr>
      <tr>
      <td>軟體開發工具 & 流程</td>
      <td>
        <ul>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>撰寫清楚明瞭的 README</li>
          <li>需要時，加上有意義的註解</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

Q1 與 Q2 為系列題，寫完 Q1 後建議直接前往 Q2

## 批改標準 - Q2: 伺服器回應的時間

> 💡  請優先完成【產品/程式規格與功能】，接著運用【驗收重點】列表檢查。

### 產品/程式規格與功能

1. 延續使用上一題的 app.js
2. 伺服器接到任一請求時，server log 上能正確印出：
   1. 伺服器收到請求的時間戳記，如 2019-5-17 18:51:12 - 以當地時間 (台北) 顯示
   2. 請求的 HTTP 方法
   3. URL
   4. 伺服器回應的時間長度，如 8ms

### 驗收重點

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
          <li>在路由系統中，對所有請求設定統一前置處理</li>
          <li>瞭解在 Express 框架中使用時間戳記的相關方法</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>
        <ul>
          <li>程式邏輯是否清晰</li>
          <li>使用 let & const 宣告變數 (不要使用 var)</li>
          <li>變數資料型態保持前後一致</li>
          <li>命名是否有意義、可讀性</li>
          <li>盡量避免多餘的程式碼</li>
          <li>遵守 JavaScript Standard style (建議安裝<a href="https://standardjs.com/index.html#install" target="_blank">自動檢查套件</a>)</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與使用者動線</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>(略)</td>
    </tr>
      <tr>
      <td>軟體開發工具 & 流程</td>
      <td>
        <ul>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>撰寫清楚明瞭的 README</li>
          <li>需要時，加上有意義的註解</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

## 行有餘力：優化品質、擴充規格

下表蒐集了本作業可能延伸的優化方向，主要蒐集自曾獲 `Exceed expectations` 的作品，若你行有餘力、想挑戰自己，可從下表尋找靈感，若你有不同的想法，也歡迎你貢獻新的優化方法。

注意，並非每位同學都需要攻略這些項目，請你先完成基本規格，行有餘力時再來挑戰。

<table>
  <thead>
    <tr>
      <th>優化方向</td>
      <th>可能作法</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>擴充規格</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>開發框架/函式庫</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>
          <ul>
          <li>顯示時間日期格式：可考慮用 Date 現成的方法。</li>
          <li>未滿十位數補零的方式：可考慮用 String 現成的方法，讓程式碼更精簡。提示可以到 <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String#" target="_blank">MDN<> 找找看。</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與使用者動線</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>軟體開發工具 & 流程</td>
      <td>(略)</td>
    </tr>
  </tbody>
</table>

## 歡迎回饋

若有任何意見，歡迎透過 issue 或 pull requests 功能給予意見。
