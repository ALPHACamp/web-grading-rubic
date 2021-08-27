# Adele 的歌詞本

## 💡 瞭解 AC 作業回饋機制

在寫這份作業之前，請你務必充分瞭解 <a href="https://github.com/ALPHACamp/web-grading-rubic" target="_blank">ALPHA Camp 作業回饋機制</a>，瞭解成果如何被審查，才能主動攻略

- `Meet Expectations` 條件：(1) 充分滿足【產品/程式規格與功能】(2)【驗收重點】無重大問題
- `Try Harder`：代表學生需要停下來釐清問題，修正完成後，可 tag 助教重新判定

## 作業題目

參考課程平台 (<a href="https://lighthouse.alphacamp.co/courses/99/assignments/2990" target="_blank">原文連結</a>)

## 批改標準

> 💡  請優先完成【產品/程式規格與功能】，接著運用【驗收重點】列表檢查。

### 產品/程式規格與功能

1. 運用指定 [CodePen](https://codepen.io/alpha-camp/pen/exQRyQ) 來實作
   1. 已有載入 axios 和 Boostrap 4 様板（注意版本）
   2. 只需要撰寫 JavaScript，不需要更動任何 HTML 和 CSS
2. 點擊左欄的歌曲名稱時，就會發送請求給 lyric-api-403c0.firebaseio.com，並且將回傳的歌曲顯示在右欄
   1. 左欄的曲目由 `album` 物件動態產生
   2. 右欄的歌詞內容需來自 lyric-api-403c0.firebaseio.com 提供的 API，並使用 axios 發送請求
3. 參考 Bootstrap 的 [pill](https://getbootstrap.com/docs/4.0/components/navs/) 使用方式
4. 使用 pre 標籤製作歌詞換行效果

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
          <li>綜合運用以下能力，做出有意義的網頁：</li>
          <ul>
            <li>處理 Array x Object 來動態創造曲目清單的 DOM 元素</li>
            <li>透過官方文件的要求向 axios 發出請求和獲得回傳</li>
            <li>設計事件驅動流程，在適當時機發送 Ajax 請求取得 API 資料</li>
            <li>取得 API response 之後，觀察 Array x Object 的資料結構，選出需要的資料來修改 DOM 元素</li>
            <li>查閱 Bootstrap 4 官方文件，成功使用 pill 在左欄達到題目效果</li>
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
          <li>使用 axios 時的語法是否乾淨俐落（例如：將 BASE_URL 獨立設為一個變數）</li>
          <li>設定監聽器時，使用事件委派方式，並拓善使用 event.target, 由歌詞清單表統一監聽歌詞的點擊</li>
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
