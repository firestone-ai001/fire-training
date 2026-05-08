# 🔥 中和消防訓練系統 — 部署說明

---

## 📦 這個資料夾裡有什麼？

```
fire-training/
├── index.html          ← 網頁入口
├── package.json        ← 專案設定
├── vite.config.js      ← 建置設定
├── .gitignore          ← Git 忽略清單
└── src/
    ├── main.jsx        ← React 入口
    └── FireTraining.jsx ← 主程式（您的 App）
```

---

## 🚀 部署步驟（三個平台擇一）

---

### 方法一：Vercel（最推薦，最簡單）

**需要準備：**
- 電腦（Windows / Mac 都可以）
- 免費帳號：GitHub + Vercel

---

#### 第一步：申請 GitHub 帳號
1. 打開瀏覽器，前往 → **https://github.com**
2. 點右上角「Sign up」
3. 填入 Email、密碼、使用者名稱，完成驗證

---

#### 第二步：建立 GitHub Repository（存放專案的地方）
1. 登入後，點右上角「+」→「New repository」
2. Repository name 填：`fire-training`
3. 選「Private」（私人，只有你看得到）
4. 點「Create repository」

---

#### 第三步：上傳專案檔案
1. 在剛建立的 repository 頁面，點「uploading an existing file」
2. 把整個 `fire-training` 資料夾**拖曳**進去
3. 等待上傳完成
4. 下方「Commit changes」點「Commit directly to the main branch」
5. 點綠色「Commit changes」按鈕

---

#### 第四步：申請 Vercel 帳號並部署
1. 打開 → **https://vercel.com**
2. 點「Sign Up」→ 選「Continue with GitHub」（用 GitHub 帳號登入，最方便）
3. 授權後，點「Add New Project」
4. 找到剛剛的 `fire-training` → 點「Import」
5. 設定頁面**不用改任何東西**，直接點「Deploy」
6. 等待約 1 分鐘...
7. 出現🎉畫面，您的網址就完成了！

**網址格式：** `https://fire-training-xxxxx.vercel.app`

---

#### 第五步：分享給隊員
直接把網址傳給隊員，手機瀏覽器打開就能使用！

**建議加到手機桌面：**
- **iPhone：** Safari 打開網址 → 下方分享鈕 → 「加入主畫面」
- **Android：** Chrome 打開網址 → 右上角三點 → 「新增至主畫面」

---

### 方法二：Netlify（同樣簡單，不需要 GitHub）

1. 打開 → **https://netlify.com**
2. 點「Sign up」→ 用 Email 註冊
3. 登入後，把整個 `fire-training` 資料夾**直接拖曳**到頁面中間的方塊
4. 等待部署（約 30 秒）
5. 自動產生網址，點「Site settings」可以改成自訂名稱

---

## ⚠️ 重要說明

### 關於資料儲存
目前版本的資料存在**瀏覽器記憶體**中，這表示：
- ✅ 同一個視窗操作中資料正常顯示
- ❌ 關閉瀏覽器後資料會消失
- ❌ 不同裝置之間資料不會同步

### 如果需要永久儲存資料
需要加入後端資料庫（如 Firebase / Supabase），這是進階功能，可以之後再考慮。

---

## 🔑 登入資訊

| 項目 | 說明 |
|------|------|
| 密碼 | `7119` |
| 幹部帳號 | 馮子軒、陳文彬、李東翰、石能勳 |
| 一般成員 | 其餘隊員 |

---

## 📞 如果遇到問題

遇到任何問題，把錯誤訊息截圖，回到 Claude 詢問即可！
