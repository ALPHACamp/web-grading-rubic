# 建立 User Profile

## 驗收標準 - Q1: User Profile

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
          <li>綜合運用目前所學，達成以下功能：</li>
          <ul>
            <li>新增個人資料頁面</li>
            <li>使用者可以編輯個人資料</li>
            <li>編輯個人資料時，可以上傳圖片</li>
            <li>只有自己能編輯自己的資料</li>
            <li>常見問題</li>
            <ul>
              <li>上傳 Heroku 之後是否可成功上傳圖片（需要 Heroku 設定環境變數 IMGUR_CLIENT_ID）</li>
              <li>在路由輸入不同使用者ID時，是否會使用 ID 對應的使用者（而非登入使用者）</li>
            </ul>
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
          <li>依照給定的 wireframe 添加指定功能，元件的數量、功能、元件之間的相對位置要和 wireframe 一致，而 style (顏色、邊距、留白、陰影等地方) 可自行優化</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>
        <ul>
          <li>設定題目指定的 admin & normal user 種子帳號</li>
          <li>命名方式與指定規格一致</li>
          <li>設計資料欄位時，選擇正確的資料型態</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>軟體開發工具 & 流程</td>
      <td>
        <ul>
          <li>在 package.json 裡設定執行腳本，讓其他使用 git clone 下載此專案的人，能成功啟動專案（若無法照腳本執行直接 try harder）</li>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>撰寫清楚明瞭的 README</li>
          <li>需要時，加上有意義的註解</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

Q1 與 Q2 為系列題，寫完 Q1 後建議直接前往 Q2

## 驗收標準 - Q2 使用者評論過的餐廳

> 💡  請優先完成【產品功能與規格】，接著運用下方列表檢查。

下表綜合考量了「實務上該如何做」以及「你目前學會什麼」，需要透過助教分享他從你的作業的觀察，才能幫助我們了解哪些行為已經達到水準、繼續保持，反之，也可能會有需要改善的問題。。

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
          <li>綜合運用目前所學，達成以下功能：</li>
          <ul>
            <li>在「個人資料」下方，建立一塊面板，陳列出「使用者評論過的餐廳」(可以先不考慮餐廳重覆問題)</li>
            <li>點擊餐廳時，可以連結到餐廳頁面</li>
            <li>再次用 root 將 user1 改回一般帳號，此時 user1 會從後台退出</li>
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
          <li>依照給定的 wireframe 添加指定功能，元件的數量、功能、元件之間的相對位置要和 wireframe 一致，而 style (顏色、邊距、留白、陰影等地方) 可自行優化</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>
        <ul>
          <li>設定題目指定的 admin & normal user 種子帳號</li>
          <li>新增種子資料，加入「使用者的餐廳評論」</li>
          <li>設計資料欄位時，選擇正確的資料型態</li>
          <li>欄位命名適當</li>
        </ul>
      </td>
    </tr>
      <tr>
      <td>軟體開發工具 & 流程</td>
      <td>
        <ul>
          <li>在 package.json 裡設定執行腳本，讓其他使用 git clone 下載此專案的人，能成功啟動專案（若無法照腳本執行直接 try harder）</li>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>撰寫清楚明瞭的 README</li>
          <li>需要時，加上有意義的註解</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

## 行有餘力的行動建議

現階段，本題暫時沒有 Exceed Expectations 的期待設定，建議同學完成作業後，繼續往下學習。

## 作業相關資訊

參考課程平台 (<a href="https://lighthouse.alphacamp.co/courses/118/assignments/3565" target="_blank">原文連結</a>)
