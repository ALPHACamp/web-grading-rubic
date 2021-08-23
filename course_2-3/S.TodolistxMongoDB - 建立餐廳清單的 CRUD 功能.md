# 餐廳清單擴充 CRUD 功能

## 批改標準

> 💡  請優先完成【產品/程式規格與功能】，接著運用【驗收重點】列表檢查。

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
          <li>用 Express 建立一個簡單的網路應用程式，包括：
            <ul>
              <li>能完成 CRUD 功能與路由設計</li>
              <li>建立 Express & MongoDB 的連線</li>
              <li>建立 seeder 檔案，載入種子資料</li>
              <li>透過 body-parser 從 POST 方法的路由中取得表單資料</li>
            </ul>
          <li>正確運用框架/函式庫提供的 API，並遵從使用慣例</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>
        <ul>
          <li>新增/編輯資料時，需要檢查表單類型正確，以及資料是否滿足必填欄位 (至少要在前端檢查)</li>  
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
          <li>在「打造餐廳清單」專案之上，依照給定的 wireframe 添加可進行 CRUD 的操作介面，元件的數量、功能、元件之間的相對位置要和 wireframe 一致，而 style (顏色、邊距、留白、陰影等地方) 可自行優化</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>
        <ul>
          <li>設計資料欄位時，選擇正確的資料型態</li>
          <li>欄位命名適當</li>
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
      <td>(略)</td>
    </tr>
    <tr>
      <td>開發框架/函式庫</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>期待同學開始意識到，程式開發不只是能夠運行功能，且包含異常處理、功能可擴充、可維護性思維，以利後續具備規劃功能、優化功能、有品質交付等能力，可能優化方向包括：
        <ul>
          <li>寫出更加簡潔明瞭程式碼，e.g. 運用解構賦值、三元運算等技巧</li>
          <li>handlebars 自定義 helper</li>
          <li>設計具有意義的路由架構 or 進階資料庫搜尋方法</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>視覺與使用者動線</td>
      <td>
        <ul>
          <li>點擊餐廳照片可直接進入 show page</li>
          <li>執行刪除前會瀏覽器會跳出提醒視窗</li>
          <li>響應式網頁</li>
          <li>「搜尋資料為空」的例外處理</li>
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

2-3 後端([原文連結](https://lighthouse.alphacamp.co/courses/100/assignments/3019))