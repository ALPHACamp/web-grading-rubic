# Adele 的歌詞本

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
              <ul>
                <li>使用 axios 時的語法是否乾淨俐落（例如：將 BASE_URL 獨立設為一個變數）</li>
                <li>設定監聽器時，使用事件委派方式，並拓善使用 event.target, 由歌詞清單表統一監聽歌詞的點擊</li>
              </ul>
            <li>取得 API response 之後，觀察 Array x Object 的資料結構，選出需要的資料來修改 DOM 元素</li>
            <li>做出 pill 效果：讓在清單上選擇中的項目，顯示鮮明的視覺強調</li>
          </ul>
          <li>其他常設項目</li>
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
      <td>本題可多注意 coding style 是否邏輯清楚、清晰好讀，值得思考的是：
        <ul>
          <li>假設未來有其他歌手出現，是否能不更動程式的邏輯面？</li>
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

## 作業相關資訊

參考課程平台 (<a href="https://lighthouse.alphacamp.co/courses/99/assignments/2990" target="_blank">原文連結</a>)

##### Logs

2021.10.5 取消 Pill 效果使用 Bootstrap 的要求，改成可以用任何方式完成 Pill 效果。
