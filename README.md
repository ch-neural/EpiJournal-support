# EpiJournal — Support / Marketing / Privacy Pages

此 repo 用來託管 **GitHub Pages** 靜態頁面，提供 App Store Connect 需要的：

- **Support URL**：`/support.html`
- **Marketing URL**：`/marketing.html`
- **Privacy Policy URL**：`/privacy.html`

入口首頁：`/index.html`

---

## 啟用 GitHub Pages（一次設定即可）

1. 到 GitHub repo：`ch-neural/EpiJournal-support`
2. 進入 **Settings → Pages**
3. 在 **Build and deployment** 選擇：
   - **Source**：Deploy from a branch
   - **Branch**：`main`
   - **Folder**：`/docs`
4. 儲存後等待 1–3 分鐘，GitHub 會顯示你的 Pages 網址。

通常會是：

- `https://ch-neural.github.io/EpiJournal-support/`

對應 App Store Connect 欄位可填：

- Support URL：`https://ch-neural.github.io/EpiJournal-support/support.html`
- Marketing URL：`https://ch-neural.github.io/EpiJournal-support/marketing.html`
- Privacy Policy URL：`https://ch-neural.github.io/EpiJournal-support/privacy.html`

---

## 如何修改內容

所有頁面都在 `docs/`：

- `docs/support.html`
- `docs/marketing.html`
- `docs/privacy.html`
- `docs/index.html`

共用樣式：`docs/assets/styles.css`

> 目前聯絡信箱預設為 `support@ch-neural.com`。如需更換，直接在 `support.html` / `privacy.html` / `marketing.html` 內搜尋並修改即可。

---

## 本機預覽（可選）

在 repo 根目錄執行：

```bash
python3 -m http.server 8000 --directory docs
```

然後開啟：`http://localhost:8000`

