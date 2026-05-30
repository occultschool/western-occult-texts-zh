# 如何接手並託管這份典藏庫

如果神秘學講堂原網站、原網域或原維護者無法繼續運作，請使用這份匯出檔讓文章與書籍繼續被閱讀。

這份典藏包不需要原伺服器、不需要原網域，已經是一個可以直接上傳的靜態網站。

## 最短步驟

1. 解壓縮 `occultschool-texts-YYYYMMDD-HHMMSS.zip`。
2. 上傳解壓後的整個資料夾內容，不要只上傳 zip。
3. 讓靜態主機以根目錄的 `index.html` 作為首頁。
4. 打開新網址，確認能看到「神秘學講堂文本典藏庫」。
5. 分享新網址，並保留原署名與 CC BY-SA 4.0 授權資訊。

## 可用主機

- GitHub Pages：建立新 repository，放入解壓後所有檔案，啟用 Pages。
- Cloudflare Pages：使用 Direct Upload，選擇解壓後資料夾。
- Netlify：使用 Deploy manually，拖曳解壓後資料夾。
- Vercel：匯入靜態資料夾或使用靜態部署流程。
- 普通網頁伺服器：把解壓後內容放到網站根目錄。

若無法控制 `occultschool.org`，請使用任何新網域、子網域或主機提供的預設網址。

## 重要檔案

| 檔案 | 用途 |
| --- | --- |
| `index.html` | 對外首頁，會導向閱讀器 |
| `reader/index.html` | 文章與書籍的簡易 HTML 閱讀器 |
| `manifest.sha256` | 完整性校驗 |
| `catalog.json` | 機器可讀目錄 |
| `README.md` | 典藏內容說明 |
| `PRESERVATION.md` | 保存記錄 |
| `LICENSE` | 授權條款 |

## 完整性校驗

如果會使用命令列，可在解壓後執行：

```bash
shasum -a 256 -c manifest.sha256
```

若出現 `FAILED`，表示檔案損壞或不完整，請改從 GitHub、Zenodo 或 Internet Archive 下載另一份。

## 不需要做的事

- 不需要登入原 VPS。
- 不需要原網域或 DNS 權限。
- 不需要修改文章內容。

緊急情況下，請先讓這份靜態典藏上線。完整網站是否重建，可以之後再處理。
