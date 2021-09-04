# 打造餐廳清單

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
          <li>正確運用框架/函式庫提供的 API，並遵從使用慣例</li>
          <li>用 Express 建立一個簡單的網路應用程式，包括：
            <ul>
              <li>讀取 JSON 檔案，將種子資料載入應用程式</li>
              <li>把資料帶入 handlebars 樣板中動態呈現</li>
              <li>操作 handlebars 中的 each 迴圈呈現出多張餐廳卡片</li>
              <li>應用 params 打造動態路由</li>
              <li>用 Query String 打造搜尋功能</li>
            <ul>
          </li>
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
          <li>適當運用註解幫助他人快速理解程式碼</li>
          <li>盡量避免多餘的程式碼</li>
          <li>遵守 JavaScript Standard style (建議安裝<a href="https://standardjs.com/index.html#install" target="_blank">自動檢查套件</a>)</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與使用者動線</td>
      <td>
        <ul>
          <li>需以教案提供的靜態檔案為基礎，元件的數量、功能、元件之間的相對位置要和 wireframe 一致，而 style (顏色、邊距、留白、陰影等地方) 可行優化</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>
        <ul>
          <li>無</li>
        </ul>
      </td>
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
      <td>
        <ul>
          <li>優化搜尋功能</li>
          <ul>
            <li>剔除多餘的空白</li>
            <li>搜尋沒有結果時也有對應頁面提示</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>開發框架/函式庫</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>
        <ul>
          <li>
            可以研究「物件的擴展（object literal
            extension）」讓你程式碼可以更精簡。
            <ul>
              <li>
                參考：<a
                  href="https://pjchender.blogspot.com/2017/01/es6-object-literal-extension.html"
                  target="_blank"
                  rel="noopener noreferrer"
                  >PJ助教-[筆記] JavaScript ES6 中的物件的擴展（object literal
                  extension）</a
                >
              </li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>視覺與使用者動線</td>
      <td>
        <ul>
          <li>圖片不會變形</li
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

## 作業相關資訊

此作業為前後端共用作業，題程平台原文連結如下：

- 2-3 前端([原文連結](https://lighthouse.alphacamp.co/courses/101/assignments/3043))
- 2-3 後端([原文連結](https://lighthouse.alphacamp.co/courses/100/assignments/3015))