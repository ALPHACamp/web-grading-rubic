# TodoList 體驗強化版

## 💡 瞭解 AC 作業回饋機制

在寫這份作業之前，請你務必充分瞭解 <a href="https://github.com/ALPHACamp/web-grading-rubic" target="_blank">ALPHA Camp 作業回饋機制</a>，瞭解成果如何被審查，才能主動攻略

- `Meet Expectations` 條件：(1) 充分滿足【產品/程式規格與功能】(2)【驗收重點】無重大問題
- `Try Harder`：代表學生需要停下來釐清問題，修正完成後，可 tag 助教重新判定

## 作業題目

參考課程平台 (<a href="https://lighthouse.alphacamp.co/courses/99/assignments/2991" target="_blank">原文連結</a>)

##### Logs

- 2021.8.6 指定規格明定「Done 清單中的項目也要能夠被刪除。」
- 2021.5.26 題幹說明微幅編輯

## 批改標準

> 💡  請優先完成【產品/程式規格與功能】，接著運用【驗收重點】列表檢查。

### 產品/程式規格與功能

1. 承接學期 2-1 的實作進度，延續此 [CodePen](https://codepen.io/alpha-camp/pen/oJoqaa) 中的已有功能
   1. 使用者可以在輸入框按 Add 來新增 to-do
   2. 使用者可以按垃圾桶按鈕來刪除 to-do
   3. 使用者可以點擊 to-do 文字來標誌 checked
2. 追加規格（畫面呈現請看題目說明）：
   1. 防止產生空白 `todo`。當使用者在 `input` 按一堆空白鍵沒有打字，要無法建立新 `todo。`
   2. 當使用者在 `input#newTodo` 裡按下 Enter 鍵時，可以新增 to-do。 (提示：使用 `keypress` 事件，並且用 `event.key === "Enter"` 來鎖定 Enter 鍵)
   3. 當使用者點擊完成的 `todo` 時，該項目會被送進 Done 清單。Done 清單中的項目也要能夠被刪除。
3. 需要驗證表單、防止例外，如：
   1. 當使用者在 `input` 直接按 Enter，不應該建立新的 todo。
   2. 或者，按了一堆空白鍵卻沒有打字，也需要防止新 todo 產生

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
          <li>HTML 結構要分成三大區塊：輸入框、待完成清單、已完成清單</li>
          <li>除了完成功能，也期待同學在多次練習 DOM 實作後，能運用以下技巧提高程式碼的可能性：</li>
          <ul>
            <li>監聽事件並運用 event.target 來分流事件操作</li>
            <li>熟練地使用迴圈配合 template literal</li>
            <li>依情況選用迭代工具，如 for loop 或 map、forEach & filter</li>
          </ul>
          <li>其他</li>
          <ul>
            <li>程式邏輯是否清晰</li>
            <li>使用 let & const 宣告變數 (不要使用 var)</li>
            <li>變數資料型態保持前後一致</li>
            <li>命名是否有意義、可讀性</li>
            <li>適當運用註解幫助他人快速理解程式碼</li>
            <li>盡量避免多餘的程式碼</li>
            <li>遵守 JavaScript Standard style</li>
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
      <td>以不推翻既有規格為前提，可盡量加入自己的巧思，優化使用者體驗，打造你心目中的 todolist</td>
      <td>例如： Done 清單裡面的項目能夠被使用者還原回 Todo 清單中</td>
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
