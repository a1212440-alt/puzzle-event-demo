# Puzzle Event Prototype

可攜帶版活動 prototype。整個資料夾可以直接搬到其他電腦或部署到靜態網站。

## 本機展示

需要 Node.js。進入本資料夾後執行：

```powershell
node preview-server.cjs 8788
```

然後打開：

```text
http://127.0.0.1:8788/
```

## 部署到網頁空間

把整個資料夾內容上傳到任意靜態主機即可，例如 GitHub Pages、Netlify、Vercel、Nginx 或 Apache。

主要檔案：

- `index.html`
- `assets/main-screen.jpg`
- `assets/puzzle-stages/stage-1.png` 到 `stage-6.png`
