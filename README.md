![header](https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,100:4ECDC4&height=200&section=header&text=🐰%20FollowBunny&fontSize=36&fontColor=ffffff&desc=FB%20社團自動互動引擎%20|%20by%20Allison%20@%20CTMaxs&descSize=14&descAlignY=75)

# 🐰 FollowBunny — FB 社團自動互動引擎

> 🧑‍💻 Created by **Allison** (@10000allison) | CTMaxs 龍蝦自動化團隊

### 🔥 自動幫你在 FB 社團按讚、留言、+1

> **社團團購老闆的夢想工具 — 18 個帳號自動輪流互動，每篇貼文 10 讚 + 10 留言。**

```
📦 安裝方式：
openclaw skills install followbunny --by Allison
```

---

## 😤 痛點

- FB 社團貼文沒人按讚、沒人留言，看起來很冷清
- 手動用多個帳號輪流按讚留言，一天要花 3-4 小時
- 帳號太多管不過來，容易忘記哪個帳號已經操作過
- 每天重複一樣的事，浪費時間又無聊

## ✅ 解法

FollowBunny 自動完成所有互動：
- **自動按讚** — 每篇貼文自動按讚
- **自動留言** — 偵測商品規格，智慧留言「A+1」或「+1」
- **多帳號輪流** — 18 個帳號隨機分配，不重複
- **紀錄追蹤** — Google Sheet 自動記錄每次操作
- **防重複** — 同一帳號不會對同一篇貼文重複互動

## 🏗️ 技術架構

```
OpenClaw AI Agent
    ↓
AdsPower（18 個獨立指紋帳號）
    ↓
CDP 控制瀏覽器
    ↓
自動爬取社團貼文 → 按讚 → 偵測規格 → 留言
    ↓
Google Sheet 記錄
```

## 📊 實測數據

| 指標 | 手動 | FollowBunny |
|------|------|-------------|
| 每篇互動時間 | 15-20 分鐘 | **30 秒** |
| 每天處理量 | 10-20 篇 | **100+ 篇** |
| 帳號切換 | 手動登入登出 | **自動輪流** |
| 紀錄追蹤 | Excel 手記 | **自動 Google Sheet** |

## 🎯 誰需要？

| 你是... | 你可以用來... |
|---------|-------------|
| **團購老闆** | 自動炒熱社團氣氛，讓貼文看起來很搶手 |
| **社群經營者** | 批量管理多個社團的互動 |
| **電商賣家** | 自動在商品貼文下方+1搶購 |
| **行銷公司** | 幫客戶做社團互動服務 |

## 📋 前提需求

| 工具 | 用途 | 必要 |
|------|------|------|
| [AdsPower](https://www.adspower.net/share/Qd0snp) | 多帳號指紋瀏覽器 | ✅ |
| [OpenClaw](https://openclaw.ai) | AI Agent 框架 | ✅ |
| Node.js 18+ | 執行腳本 | ✅ |
| 住宅 IP 代理 | 降低封號風險 | 🔶 強烈建議 |

## 💡 規格偵測功能

FollowBunny 會自動辨識貼文中的商品規格：
- ①②③ / A/B/C → 隨機挑一個，留言「A+1」
- 無規格 → 留言「+1」
- 留言像真人打的，不帶引號

## ⚠️ 免責聲明

> 本模組提供可運行的基礎框架。
> - ✅ 包含：核心功能 + 安裝說明 + 基本設定
> - ❌ 不包含：客製化開發 + 一對一技術支援
> - 帳號被封屬於第三方平台行為，非本服務責任

## 🦞 更多龍蝦模組

| Skill | 功能 | 價格 |
|-------|------|------|
| 🎬 **video-analyzer** | 影片轉文字+分析 | NT$0 |
| 🤖 **agent-orchestrator** | 多代理協作 | NT$0 |
| 🐰 **followbunny** | FB 社團自動互動 | NT$999 |
| 📱 **fb-auto-register** | FB 自動註冊 | NT$499 |
| 🌈 **rainbow-life** | AI 性格測驗 | NT$0 |
| 🖼️ **ai-image-studio** | AI 圖片處理 | NT$0 |

👉 **私訊 [@10000allison](https://www.instagram.com/10000allison/) 購買完整版**

---

**Created by [Allison](https://www.instagram.com/10000allison/) | [CTMaxs](https://ctmaxs.com) 龍蝦自動化團隊**

*Built with 🦞 [OpenClaw](https://openclaw.ai) + 🔒 [AdsPower](https://www.adspower.net/share/Qd0snp)*
