# A11 我的履歷：RWD 實作應用

## 💡 瞭解 AC 作業回饋機制

在寫這份作業之前，請你務必充分瞭解 <a href="https://github.com/ALPHACamp/web-grading-rubic" target="_blank">ALPHA Camp 作業回饋機制</a>，瞭解成果如何被審查，才能主動攻略

- `Meet Expectations` 條件：(1) 充分滿足【產品/程式規格與功能】(2)【驗收重點】無重大問題
- `Try Harder`：代表學生需要停下來釐清問題，修正完成後，可 tag 助教重新判定

## 作業題目

參考課程平台 (<a href="https://lighthouse.alphacamp.co/courses/40/assignments/945" target="_blank">原文連結</a>)

##### Logs

- 2021.6.21 Q1 從「自行設計 RWD wireframe」改成「依指定的 RWD 設計稿來分析 HTML」，降低同學的前置思考難度，期能強烈強求同學先思考、再實作

## 批改標準 (Q2: 實現你的 RWD 設計)

> 💡  請優先完成【產品/程式規格與功能】，接著運用【驗收重點】列表檢查。

### 產品/程式規格與功能

1. 這題的設計需要在 Q1 先分析 HTML 架構，再進入 Q2 動手實作。
   1. 因此，Q1 不需要特別檢查 Q1 的正確性，但若沒有提交 Q1 的「分析 HTML」作業，請直接退回。
   2. 實務上比較難檢查出同學有沒有「先思考 Q1、再實作 Q2」，只要 Q1 有交符合意義的內容，就可以著手批改 Q2 實作成果。
2. media query 的斷點設置需要符合 mobile first 原則 - 在 CSS 文件，由上而下的順序先是小螢幕，然後再由小到大加入 media query 來控制兩個斷點：576px, 1200px
3. 畫面需符合 Q1 指定的設計稿（見題目說明），共有三個畫面要檢查

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
      <td>(略)</td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>
        <ul>
          <li>CSS 文件需要符合 mobile first 邏輯，</li>
          <li>能夠根據你的 RWD 設計來佈局 HTML 架構</li>
          <li>按照 CSS 由上而下可一層層覆蓋的特性，盡量考慮「設定必要的 CSS」</li>
          <li>class 的命名能快速幫助讀者判斷這是哪一個 HTML 元件</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與使用者動線</td>
      <td>
        <ul>
          <li>必要元件長相、相對位置大致與指定設計稿相同</li>
          <li>在 viewport 大小變化時，讓網頁元素跟著流動</li>
        </ul>
      </td>
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
      <td>本題需符合指定規格，不予自由擴充</td>
    </tr>
    <tr>
      <td>開發框架/函式庫</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>
        <ul>
          <li>充分運用了 CSS 的覆蓋特性，避免重覆或不必要的 CSS 設定，讓人覺得這份 HTML ＋ CSS 文件精簡、沒有多餘</li>
          <li>可考慮用相對單位 rem 來取代絕對單位 px</li>
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
