# 房仲 AI 文案生成器 Demo

> 一句話：房仲上傳照片 + 填物件資料 → AI 自動生成 591/FB/IG/LINE 四種平台文案

## 技術棧
- 純前端：HTML + CSS + Vanilla JS（單一檔案）
- AI 引擎：Google Gemini 2.0 Flash（支援圖片辨識）
- 無需後端，API Key 由使用者自行輸入

## 功能
1. 拖曳上傳房屋照片（最多 5 張，自動壓縮至 1024px）
2. 填寫物件資訊（名稱、地址、坪數、格局、價格、特色標籤）
3. 選擇生成平台（591 售屋網 / Facebook / Instagram / LINE）
4. 一鍵生成 → AI 撰寫各平台文案
5. 一鍵複製 / 單平台重新生成

## 開發指令
```bash
# 本地預覽
open index.html
# 或用 live server
npx serve .
```

## 部署
- 靜態頁面，直接丟 GitHub Pages 或任何 hosting
- API Key 存在使用者瀏覽器 localStorage

## 來源
- BNI 會員 Aston（房仲）的需求
- 三大需求之一：房屋文案自動生成
