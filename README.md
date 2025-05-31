# 居研所前端系統（Vue 3）

本專案為資展會全端班結訓專題 —— **租屋媒合平台「居研所」** 的前端部分，使用 Vue 3 + Pinia + Axios + Vue Router 開發，整合後端 API 提供房東與房客操作介面，包含聊天室、刊登房源、快速回應、會員系統等功能。

##  專案架構

- `Vue 3 + Composition API`
- `Pinia` 狀態管理
- `Axios` 串接後端 API
- `Vue Router` 前後台路由切換
- `Bootstrap / Tailwind` UI 風格
- `SignalR` 即時通訊（聊天室）
- 支援桌機與手機版切換

##  主要負責功能模組

| 模組 | 說明 |
|------|------|
|  即時聊天室 | 使用 SignalR 建立房客與房東的即時通訊功能 |
|  金流流程 | 串接綠界金流付款 API，供房東購買曝光方案使用 |
|  智慧提醒 | 自動標記訊息關鍵字，顯示「這間房還有嗎？」等快速標籤 |
|  響應式 UI | 桌機 / 手機自適應介面，支援骨架 loading、卡片動畫等效果 |

>  本專案為團隊共同開發，本版本為個人備份與展示用途。

##  開發環境建置

```bash
# 安裝依賴
npm install

# 本機開發（預設 port 5173）
npm run dev

# 打包建置
npm run build
```
## 🔗 後端搭配

後端採用 ASP.NET Core MVC 架構，配合 MS SQL Server 建立 RESTful API。

[前往後端倉庫][(https://github.com/你的帳號/GeeYeangSore)](https://github.com/aaron5ching/GeeYeangSore)
