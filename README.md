# 🐰 FollowBunny — FB 社團自動按讚留言機器人

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=5,10,20&height=180&section=header&text=🐰%20FollowBunny&fontSize=42&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=FB%20社團自動互動%20×%20龍蝦驅動&descSize=18&descAlignY=55" width="100%"/>
</p>

<p align="center">
  🧑‍💻 Created by <a href="https://instagram.com/10000allison">Allison (@10000allison)</a> | CTMaxs 龍蝦自動化團隊
</p>

---

## 🔥 一句話說完

**FB 社團新貼文一出，18 個帳號自動按讚 + 智慧留言，讓你的社團看起來超熱鬧。**

---

## ❌ 社團經營的痛

- 發文後沒人按讚，看起來很冷清
- 找人互動要一個一個叫，累死
- 手動按讚留言太慢，貼文都涼了
- 留言太假、太重複，一看就知道是機器人
- 帳號被封就全部停擺

## ✅ 用 FollowBunny 之後

- 新貼文一出 → 10 讚 + 10 留言自動完成
- 18 個帳號隨機分配，每次不同人按讚
- AI 智慧留言：偵測商品規格，自動選「A+1」或「+1」
- 每個帳號獨立指紋 + 獨立 IP（AdsPower）
- 留言像真人打的，不帶引號、自然口吻

---

## 🎯 適合誰？

| 身份 | 痛點 | 解法 |
|------|------|------|
| 社團團購主 | 貼文沒人氣 | 自動製造初始互動 |
| 電商老闆 | 社團太冷清 | 穩定按讚+留言 |
| 代操公司 | 手動操作效率低 | 全自動批量執行 |
| 直播主 | 需要即時互動 | 開播自動湧入 |

---

## 🏗️ 運作流程

```
📋 Google Sheet（客戶+貼文管理）
  ↓ 新貼文 URL
🦞 龍蝦（OpenClaw）
  ↓ 指派任務
🌐 AdsPower（18 個帳號）
  ├── 隨機選 10 個帳號按讚
  ├── 隨機選 10 個帳號留言
  │   ├── 偵測規格：有 A/B 選項 → 「A+1」
  │   └── 無規格 → 「+1」
  └── 每帳號每天 ~10 篇
  ↓ 完成後
📊 Google Sheet（記錄執行結果）
📱 LINE@（每日推播報告）
```

---

## 🧠 智慧規格偵測

FollowBunny 會自動讀取貼文內容，判斷有沒有商品規格：

| 偵測到的格式 | 範例 | 留言 |
|-------------|------|------|
| ①②③ 圈數字 | ①紅色 ②藍色 | 「①+1」 |
| A./B./C. 英文 | A.大號 B.小號 | 「A+1」 |
| A規格/B規格 | A規格/B規格 | 「A規格+1」 |
| 無規格 | 純文字描述 | 「+1」 |

> 需要 ≥2 個 match 才判定有規格，避免誤判

---

## 📊 實際數據

| 指標 | 數值 |
|------|------|
| 帳號數量 | 18 個 |
| 每篇互動 | 10 讚 + 10 留言 |
| 每帳號每天 | ~10 篇 |
| 代理 IP | 每 6 帳號共用 1 個 |
| 留言速度 | 每篇 ~30 秒完成 |

---

## 🔧 包含什麼？

### Public（你現在看到的）
- ✅ FollowBunny 運作架構說明
- ✅ 智慧留言邏輯解析
- ✅ AdsPower 帳號管理教學
- ✅ Google Sheet 設定範本

### Private Core（付費版）
- 🔒 完整自動化腳本（`followbunny-auto.js`）
- 🔒 AdsPower API + CDP 整合
- 🔒 Google Sheet Apps Script
- 🔒 規格偵測演算法
- 🔒 每日報告自動推播
- 🔒 帳號健康度監控
- 🔒 封號應對 + 帳號替換 SOP

---

## 💼 收費方案（代操服務）

| 方案 | 月費 | 內容 |
|------|------|------|
| 基本方案 | NT$2,500/月 | 每篇 10 讚 + 10 留言 |
| 進階方案 | NT$5,000/月 | 每篇 15 讚 + 15 留言 + 日報 |
| 自架方案 | 一次買斷 | 自己跑，含教學 |

---

## 🦞 龍蝦模組商店

| 模組 | 說明 | 連結 |
|------|------|------|
| 🐰 FollowBunny | 社團自動互動 | 👈 你在這裡 |
| 📱 FB Auto Register | AdsPower 自動養號 | [前往](https://github.com/maxtsai01/fb-auto-register) |
| 🤖 Agent Orchestrator | 多代理協作 | [前往](https://github.com/maxtsai01/agent-orchestrator) |
| 🤝 Lobster × Manus | AI 雙引擎協作 | [前往](https://github.com/maxtsai01/lobster-manus) |
| 🛒 Lobster × 1Shop | 電商自動化 | [前往](https://github.com/maxtsai01/lobster-1shop) |
| 🎬 Video Analyzer | AI 影片情報分析 | [前往](https://github.com/maxtsai01/video-analyzer) |
| 🌈 Rainbow Life | 彩虹人生性格分析 | [前往](https://github.com/maxtsai01/rainbow-life) |
| 🖼️ AI Image Studio | AI 圖片處理 | [前往](https://github.com/maxtsai01/ai-image-studio) |
| 🦞 AI Warbook | 龍蝦兵法 | [前往](https://github.com/maxtsai01/lobster-ai-warbook) |

---

👉 [立即免費領取](https://lumaint.1shop-app.com/lobster-store)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=5,10,20&height=100&section=footer" width="100%"/>
</p>

<p align="center">
  Created by <a href="https://instagram.com/10000allison">Allison</a> | CTMaxs 龍蝦自動化團隊
</p>
