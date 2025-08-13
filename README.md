# 食記AI — 自然語言飲食日誌

這是可直接部署的 React (Vite) 專案。支援：
- 粵語/中文/英文 自然語言輸入
- AI 解析（OpenAI/相容供應商）或離線估算
- 月曆視圖、ICS 匯出

## 本地開發
```bash
npm i
npm run dev
```

## Build
```bash
npm run build
npm run preview
```


## 一鍵部署到 GitHub Pages
> 預設 base 已設為 `/dietlog-ai/`。如果你的 repo 名稱不同，請改 `vite.config.js` 的 `base` 與 `index.html` 裡的 `src` 路徑。

### 步驟
```bash
# 1) 初始化並安裝
npm i

# 2) 打包
npm run build

# 3) 發佈到 gh-pages 分支
npm run deploy:gh

# 4) 到 GitHub Repo 設定 -> Pages
#    Source 選 gh-pages 分支的 / 根目錄，儲存即可。
```
部署後網址大概是：`https://<你的GitHub帳號>.github.io/dietlog-ai/`
