# 📚 TutorFlow - 家教排課與學生管理儀表板

> 一套專為家教老師與個別指導打造的高顏值、現代化排課與學生管理 Web 應用程式。

---

## 🌟 核心特色

- 🎨 **馬卡龍低飽和色系 UI**：晴藍、甜粉、嫩綠、薰紫、暖杏色塊，營造清爽舒適的使用體驗。
- 📅 **行事曆防呆排課**：自訂 10:00 - 22:00 營業時間軸，點擊網格直接排課，時段衝突自動阻擋與警示。
- 👩‍🎓 **學生檔案與雙欄履歷**：
  - 地址原地快速編輯
  - 時間軸歷史備忘錄（自動帶上時間戳記）
  - 課程歷史雙欄對照（📌 預計進度 vs 📝 實際狀況/回饋）
- 💰 **財務結算與帳務分離**：
  - 手風琴折疊總計儀表板（預設收合省空間）
  - 獨立「學生 x 科目」定價系統（鐘點費、收款方式、銀行帳號備註）
  - 跨月未收款自動遞延置頂，群組化帳單一鍵確認收款
- ⚙️ **簡約設定與 Google 整合**：
  - 老師個人化稱謂設定
  - Google Calendar 雙向連動模擬
  - JSON 資料庫備份匯出與一鍵重置範例資料
- 📱 **全端極致 RWD**：完美支援 iPhone（滑入式漢堡選單抽屜、橫向滑動表格）與 iPad 11吋 / 桌機（固定導覽列、寬屏網格）。

---

## 🚀 部署至 GitHub Pages 進行線上測試 (免安裝即開即用)

因為本專案的 `index.html` 已整合 React 18、Tailwind CSS 與 Context API，可直接於瀏覽器端執行，非常適合啟用 **GitHub Pages** 免費線上預覽：

1. 將本專案上傳至您的 GitHub 儲存庫（Repository）。
2. 在 GitHub 儲存庫頁面點擊 **`Settings`（設定）➔ `Pages`**。
3. 在 **Build and deployment** 區塊：
   - **Source**: 選擇 `Deploy from a branch`
   - **Branch**: 選擇 `main`（或 `master`），資料夾保持 `/ (root)`。
4. 點擊 **Save**，稍等 1~2 分鐘即可獲得專屬的線上測試網址（例如：`https://<你的帳號>.github.io/<儲存庫名稱>/`）！

---

## 💻 本地執行方式

### 方法一：直接雙擊開啟
直接使用任何現代瀏覽器（Chrome、Edge、Safari、Firefox）雙擊開啟 `index.html` 即可使用完整功能。

### 方法二：透過 Node.js 本地伺服器
```bash
node server.js
```
啟動後開啟瀏覽器訪問：`http://localhost:3000`

---

## 🛠️ 技術棧
- **框架**：React 18 (Functional Components, Hooks, Context API)
- **樣式**：Tailwind CSS
- **圖示**：Lucide Icons
- **儲存**：LocalStorage CRUD 資料庫模擬
