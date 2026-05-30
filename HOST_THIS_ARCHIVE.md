# 如何接手并托管这份典藏库 / 如何接手並託管這份典藏庫

## 简体中文

如果神秘学讲堂原网站、原域名或原维护者无法继续运作，请使用这份导出包让文章与书籍继续被阅读。

这份典藏包不需要原服务器、不需要原域名、不需要原账号，已经是一个可以直接上传的静态网站。紧急情况下，请先让这份静态典藏上线，完整网站是否重建可以之后再处理。

### 最短步骤

1. 下载最新的 `occultschool-texts-YYYYMMDD-HHMMSS.zip`。
2. 解压缩。
3. 上传解压后的整个资料夹内容，不要只上传 zip。
4. 让静态主机以根目录的 `index.html` 作为首页。
5. 打开新网址，确认能看到「神秘学讲堂文本典藏库」或阅读器目录。
6. 分享新网址，并保留原署名与 CC BY-SA 4.0 授权信息。

### 可用主机

- GitHub Pages：建立新 repository，放入解压后所有文件，启用 Pages。
- Cloudflare Pages：使用 Direct Upload，选择解压后的资料夹。
- Netlify：使用 Deploy manually，拖拽解压后的资料夹。
- Vercel：导入静态资料夹或使用静态部署流程。
- 普通网页服务器：把解压后内容放到网站根目录。
- 对象存储静态网站：上传解压后的全部文件，并把首页设为 `index.html`。

若无法控制 `occultschool.org`，请使用任何新域名、子域名或主机提供的默认网址。

### 重要文件

| 文件 | 用途 |
| --- | --- |
| `index.html` | 对外首页，会导向阅读器 |
| `reader/index.html` | 文章与书籍的简易 HTML 阅读器 |
| `manifest.sha256` | 完整性校验 |
| `catalog.json` | 机器可读目录 |
| `README.md` | 典藏内容说明 |
| `PRESERVATION.md` | 保存记录与公开镜像 |
| `LICENSE` | 授权条款 |
| `CITATION.cff` | 引用元数据 |

### 完整性校验

如果会使用命令行，可在解压后执行：

```bash
shasum -a 256 -c manifest.sha256
```

若出现 `FAILED`，表示文件损坏或不完整，请改从 GitHub、Zenodo、Internet Archive 或 Hugging Face 下载另一份。

### 不需要做的事

- 不需要登录原 VPS。
- 不需要原域名或 DNS 权限。
- 不需要原维护者账号。
- 不需要修改文章内容。

---

## 繁體中文

如果神秘學講堂原網站、原網域或原維護者無法繼續運作，請使用這份匯出包讓文章與書籍繼續被閱讀。

這份典藏包不需要原伺服器、不需要原網域、不需要原帳號，已經是一個可以直接上傳的靜態網站。緊急情況下，請先讓這份靜態典藏上線，完整網站是否重建可以之後再處理。

### 最短步驟

1. 下載最新的 `occultschool-texts-YYYYMMDD-HHMMSS.zip`。
2. 解壓縮。
3. 上傳解壓後的整個資料夾內容，不要只上傳 zip。
4. 讓靜態主機以根目錄的 `index.html` 作為首頁。
5. 打開新網址，確認能看到「神秘學講堂文本典藏庫」或閱讀器目錄。
6. 分享新網址，並保留原署名與 CC BY-SA 4.0 授權資訊。

### 可用主機

- GitHub Pages：建立新 repository，放入解壓後所有檔案，啟用 Pages。
- Cloudflare Pages：使用 Direct Upload，選擇解壓後資料夾。
- Netlify：使用 Deploy manually，拖曳解壓後資料夾。
- Vercel：匯入靜態資料夾或使用靜態部署流程。
- 普通網頁伺服器：把解壓後內容放到網站根目錄。
- 物件儲存靜態網站：上傳解壓後全部檔案，並把首頁設為 `index.html`。

若無法控制 `occultschool.org`，請使用任何新網域、子網域或主機提供的預設網址。

### 重要檔案

| 檔案 | 用途 |
| --- | --- |
| `index.html` | 對外首頁，會導向閱讀器 |
| `reader/index.html` | 文章與書籍的簡易 HTML 閱讀器 |
| `manifest.sha256` | 完整性校驗 |
| `catalog.json` | 機器可讀目錄 |
| `README.md` | 典藏內容說明 |
| `PRESERVATION.md` | 保存記錄與公開鏡像 |
| `LICENSE` | 授權條款 |
| `CITATION.cff` | 引用元資料 |

### 完整性校驗

如果會使用命令列，可在解壓後執行：

```bash
shasum -a 256 -c manifest.sha256
```

若出現 `FAILED`，表示檔案損壞或不完整，請改從 GitHub、Zenodo、Internet Archive 或 Hugging Face 下載另一份。

### 不需要做的事

- 不需要登入原 VPS。
- 不需要原網域或 DNS 權限。
- 不需要原維護者帳號。
- 不需要修改文章內容。
