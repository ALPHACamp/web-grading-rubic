# 找出得分王

## 💡 瞭解 AC 作業回饋機制

在寫這份作業之前，請你務必充分瞭解 <a href="https://github.com/ALPHACamp/web-grading-rubic" target="_blank">ALPHA Camp 作業回饋機制</a>，瞭解成果如何被審查，才能主動攻略

- `Meet Expectations` 條件：(1) 充分滿足【產品/程式規格與功能】(2)【驗收重點】無重大問題
- `Try Harder`：代表學生需要停下來釐清問題，修正完成後，可 tag 助教重新判定

## 作業題目

參考課程平台 (<a href="https://lighthouse.alphacamp.co/courses/98/assignments/3628">原文連結</a>)

## 批改標準

> 💡  請優先完成【產品/程式規格與功能】，接著運用【驗收重點】列表檢查。

### 產品/程式規格與功能

1. 這題的設計需要在 Q1 先分析 HTML 架構，再進入 Q2 動手實作。
   1. 因此，Q1 不需要特別檢查 Q1 的正確性，但若沒有提交 Q1 的「HTML 架構規劃」作業，請直接退回。
   2. 實務上比較難檢查出同學有沒有「先思考 Q1、再實作 Q2」，只要 Q1 有交符合意義的內容，就可以著手批改 Q2 實作成果。  
2. 根據[指定設計稿](https://www.figma.com/file/D4tIgxfD2Dry2esT2WGh5Z/CSS_Position?node-id=13%3A2) 切版
   1. 100 % 還原設計稿。
   2. 使用純 CSS 完成切版，不得套用 Bootstrap 來完成。
   3. 下圖四個藍框區塊定位只能使用 CSS Position，並且搭配 `top/right/bottom/left` 的位移屬性來達成，不能使用 Flex、Grid 等語法。
   4. 橘框內的文字置中方法不限。
   ![](https://assets-lighthouse.alphacamp.co/uploads/image/file/14993/ExportedContentImage_01.png)


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
      <td>略</td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>略</td>
    </tr>
      <tr>
      <td>視覺與使用者動線</td>
      <td>
        <ul>
          <li>切版完成度：</li>
          <ul>
            <li>切出和設計稿一致的網頁元件</li>
          </ul>
          <li>期待在處理不同區塊切版時，能依不同的工具特性，選擇適當工具來進行切版，包括：</li>
          <ul>
            <li>box model</li>
            <li>flexbox</li>
            <li>position</li>
          </ul>
        </ul>
      </td>
    </tr>
    <tr>
      <td>資料庫</td>
      <td>略</td>
    </tr>
      <tr>
      <td>軟體開發工具 & 流程</td>
      <td>略</td>
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
      <td>由於「切版」需要 100% 遵照規格，因此本作業不建議同學進行規格擴充。</td>
    </tr>
    <tr>
      <td>開發框架/函式庫</td>
      <td>(略)</td>
    </tr>
    <tr>
      <td>程式邏輯與 Coding Style</td>
      <td>假設已達到了「100% 視覺到位」，下一步的品質追求會在於「命名與文件架構」：
        <ol>
          <li>是否能讓人在龐大的 HTML & CSS 文件裡，很快地查找出某個元件的</li>
          <li>HTML x CSS 佈局的方式，是否能具有可擴充性，也就是說，如果未來要常常修改、新增視覺，你目前的架構方式會容易做到嗎？還是常常會牽一髮動全身？</li>
        </ol>
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
