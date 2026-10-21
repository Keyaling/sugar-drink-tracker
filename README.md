# 🥤含糖飲料習慣紀錄與健康統計系統(Sugar Drink Tracker)

基於 RWD 響應式前端、Google Apps Script (GAS) Serverless 後端與 Google Sheets 資料庫打造的全棧健康管理網頁應用程式。

👉 **[線上展示連結 (Live Demo)]()**  
*(測試帳號：`admin` / 測試密碼：`123456`)*
https://keyaling.github.io/sugar-drink-tracker/
---

## 📌 專案動機與背景
為了改善日常攝取含糖飲料的習慣，本專案透過每日問答與數據紀錄機制，將抽象的健康風險轉化為具體的數據指標（如熱量換算、消除熱量所需步數、開銷累計等），並結合「好棒做得好徽章」獎勵機制，給予情緒價值，協助使用者建立良好的控糖與健康生活習慣。

---

## ✨ 核心功能與特色
- **今日動態健康問答**：登入即跳出今日飲用確認，若當天未喝含糖飲料，可一鍵領取「好棒做得好徽章」。
- **靈活量化統計與換算**：
  - 支援自訂飲料容量與甜度，系統依公式動態換算增加熱量 (kcal) 與步行消除步數。
  - 考量飲用習慣差異，統一以 **700 ml** 為 1 標準杯動態折算月/年累計杯數。
- **多維度視覺化儀表板**：即時統計今日/本月/今年的飲料開銷、累積徽章數，並提供與上月/去年同期的飲用量增減比較。
- **完整 CRUD 資料管理**：提供詳細紀錄列表，支援最新/最舊動態日期排序、資料彈窗 (Modal) 修改與刪除功能。
- **全響應式設計 (RWD)**：針對 Mobile 與 Desktop 裝置進行最佳化排版與介面適配。

---

## 🛠 系統架構與技術棧
- **前端 (Frontend)**：HTML5, CSS3 (Flexbox/Grid, RWD), Vanilla JavaScript (ES6+ async/await, Fetch API, Crypto API)
- **後端 (Backend)**：Google Apps Script (GAS Serverless Web App API)
- **資料庫 (Database)**：Google Sheets (分離 `User` 驗證表與 `Records` 紀錄表)

---

