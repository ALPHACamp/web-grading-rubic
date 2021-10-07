# 餐廳清單．Final

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
          <li>運用第三方工具來強化 app 的功能</li>
          <ul>
            <li>使用 Passport 打造註冊功能</li>
            <li>串接 Facebook 第三方登入</li>
            <li>使用 bcrypt 保護使用者的密碼</li>
          </ul>
          <li>能打造「使用者認證」的基本體驗，包括動線、邏輯、資料設計以及例外處理</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>
        <ul>
          <li>新增/編輯資料時，需要檢查表單類型正確，以及資料是否滿足必填欄位 (至少要在前端檢查)</li>  
          <li>其他常設項目</li>
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
      <td>理論上，本作業不著重視覺，只會在擴充登入功能時，加入必要的表單 & 按鈕
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
          <li>在 package.json 裡設定執行腳本，讓其他使用 git clone 下載此專案的人，能成功啟動專案（若無法照腳本執行直接 try harder）</li>
          <li>建立粒度適當的 git commit 與清楚簡潔的 commit message</li>
          <li>撰寫清楚明瞭的 README</li>
          <li>需要時，加上有意義的註解</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

## 行有餘力：優化品質、擴充規格

若 app 在「一般使用場景」下能讓指定規格順利運作，則滿足了 `Meed expectations` 標準。若要攻略 `Exceed expectations`，原則是：

- 在已「滿足基本規格」的前提下，許多同學在行有餘力時，會針對自己感興趣的地方，強化功能或體驗，例如：
  - 建構新的前端互動設計
  - 強化表單的例外處理
  - 提升 coding style
  - 撰寫 README
  - .....等等
- 若同學在「基本規格外的新嘗試」做出了明確的階段成果（反例是，雖有一些想法，但不知如何實作，只能起個頭，再來和助教討論），若助教評估此同學的「新嘗試」足夠完整，會想推薦給其他同學做為參考，則可考慮給出 `Exceed expectations`

## 作業相關資訊

參考課程平台([原文連結](https://lighthouse.alphacamp.co/courses/118/assignments/3547))。
