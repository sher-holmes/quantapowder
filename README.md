# 廣達粉末材料官網（QUANTA POWDER MATERIALS）

東莞清溪廣達粉末材料有限公司官方網站，單頁式設計稿。

## 部署方式（GitHub Pages）

1. 建立新的 GitHub repository，將本資料夾內容全部上傳到根目錄。
2. 到 repo 的 **Settings → Pages**。
3. Source 選擇 `Deploy from a branch`，Branch 選 `main`（或你的預設分支）、資料夾選 `/ (root)`。
4. 儲存後等待 1-2 分鐘，網站會發布在：
   `https://<你的帳號>.github.io/<repo名稱>/`

## 檔案結構

```
index.html   單一自含檔案，含所有 CSS/JS，圖片已用 base64 內嵌
README.md    本說明文件
```

## 尚待處理

- 聯絡我們的表單目前為靜態展示，未串接後端（可考慮之後接 Supabase）
- 六大產品線目前只在首頁做卡片摘要，尚無獨立詳細子頁面
