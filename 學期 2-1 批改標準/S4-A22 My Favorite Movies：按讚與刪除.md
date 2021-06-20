# A22 My Favorite Movies：按讚與刪除

## 💡 瞭解 AC 作業回饋機制

在寫這份作業之前，請你務必充分瞭解 <a href="https://github.com/ALPHACamp/web-grading-rubic" target="_blank">ALPHA Camp 作業回饋機制</a>，瞭解成果如何被審查，才能主動攻略

- `Meet Expectations` 條件：(1) 充分滿足【產品/程式規格與功能】(2)【驗收重點】無重大問題
- `Try Harder`：代表學生需要停下來釐清問題，修正完成後，可 tag 助教重新判定

## 作業題目

參考課程平台 (<a href="https://lighthouse.alphacamp.co/courses/40/assignments/955" target="_blank">原文連結</a>)

##### Logs

- 2021.6.21 移除題幹描述「不需要特意排除評分為負分的狀況」，納入必要規格

## 批改標準

> 💡  請優先完成【產品/程式規格與功能】，接著運用【驗收重點】列表檢查。

### 產品/程式規格與功能

1. 延續[運用 Template Literal 渲染動態網頁單元](https://lighthouse.alphacamp.co/courses/40/units/5682) 中的專案程式碼
2. 新增兩個功能：
   1. 可以點擊圖示來改變評分
   2. 可以刪除電影
3. 實作中需要使用「事件委派」
4. 在 Rating 中評分下降成 0 以後，繼續點繫不應該出現負分

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
          <li>熟悉 DOM 的事件處理基本方法：</li>
          <ul>
            <li>使用 event listener 綁定滑鼠事件</li>
            <li>運用 event target 裡的資訊，分開處理加分/扣分的情況 (event delegation)</li>
            <li>刪除按鈕：事件驅動刪除 DOM 節點</li>
            <li>使用迴圈或是 template literal 呈現題目要求的畫面</li>
          </ul>
          <li>重覆練習重要的 DOM 操作觀念或技巧：</li>
          <ul>
            <li>使用迴圈或是 template literal 呈現題目要求的畫面</li>
            <li>應注意到從 DOM 元素中取出的值是 string，需轉為 Number 再做進一步運算)</li>
          </ul>
          <li>其他</li>
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
      <td>必要元件長相、相對位置大致與指定設計稿相同</td>
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
      <td>(略)</td>
    </tr>
    <tr>
      <td>開發框架/函式庫</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>(略)</td>
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
