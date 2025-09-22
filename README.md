# 停班停課神器

## ⚠️ 使用前請閱讀免責聲明

### 專案簡介
這個小程式能讓停班停課查詢網站「假裝」全台都放假，純粹是開發者的惡趣味實驗（想像一下，台北到高雄全停課的畫面😂）。

### 警告事項
1. **娛樂限定**：這不是真實工具！別用來騙人、散播假消息，或在社群上PO圖，否則可能觸法（例如散布謠言罪）。
2. **官方為準**：想知道真實停班停課？馬上去 [中央氣象署](https://www.cwb.gov.tw/) 或各縣市公告查。
3. **自負風險**：程式可能有bug，網站改版也可能壞掉。用前備份資料，用後別哭。
4. **道德提醒**：颱風是天災，不是派對。多關心安全，少幻想放假。

有問題？開 issue 討論，但別問「怎麼用來翹班」哦～

## 使用教學

1. 將此網頁設為書籤
2. 複製下列文字
3. 編輯步驟1之書籤，將網址更改為步驟2複製之文字
```js
javascript: fetch("https://raw.githubusercontent.com/meteorTriangle/tingban-tingke-shenqi/refs/heads/main/TTS.txt").then(response => response.text()).then(data => {window.location.href = data;});
```
4. 開啟網站[行政院人事行政總處 全球資訊網](https://www.dgpa.gov.tw/typh/daily/nds.html)
5. 選擇剛剛所編輯完的書籤
