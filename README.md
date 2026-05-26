# OccultSchool Texts — Chinese Archive

**神秘學講堂文本典藏庫**  
**[繁體中文](#繁體中文) · [简体中文](#简体中文) · [English](#english)**

---

## 繁體中文

### 簡介

本資料集是「神秘學講堂」（OccultSchool）的中文文本典藏庫，收錄網站文章、完整書籍譯文、書籍圖片資產與 PDF/EPUB 電子書。此版本以長期保存、再散佈與研究使用為目標，內容已整理為不依賴 Docusaurus 的純文字資料集。

### 內容結構

| 目錄 | 說明 |
| --- | --- |
| `zh-Hant/articles/` | 繁體中文文章，共 230 篇 |
| `zh-Hant/books/texts/` | 繁體中文書籍 Markdown，共 547 個文字檔 |
| `zh-Hant/books/assets/` | 繁體中文書籍引用圖片與封面 |
| `zh-Hant/books/ebooks/` | 繁體中文 PDF/EPUB，共 46 個檔案 |
| `zh-Hans/articles/` | 简体中文文章，共 230 篇 |
| `zh-Hans/books/texts/` | 简体中文书籍 Markdown，共 547 个文字档 |
| `zh-Hans/books/assets/` | 简体中文书籍引用图片与封面 |
| `zh-Hans/books/ebooks/` | 简体中文 PDF/EPUB，共 46 个档案 |

### 整理規則

- Markdown 檔案已移除 Docusaurus/YAML frontmatter。
- 文章中的圖片引用已移除，書籍中的圖片引用保留。
- `index.md` 與 `_category_.json` 不納入典藏文本。
- `zh-Hans` 的資料夾與檔名已轉為簡體中文。
- `manifest.sha256` 可用於完整性校驗，`catalog.json` 可供程式讀取。

### 授權

本作品以 Creative Commons Attribution-ShareAlike 4.0 International（CC BY-SA 4.0）授權。轉載、改作與再散佈時，請署名「神秘學講堂 (OccultSchool)」，並以相同授權分享。

---

## 简体中文

本资料集是「神秘学讲堂」（OccultSchool）的中文文本典藏库，包含文章、完整书籍译文、书籍图片资产与 PDF/EPUB 电子书。本版本面向长期保存、研究与再发布，使用 UTF-8 Markdown 与开放资料格式。

校验方式：

```bash
shasum -a 256 -c manifest.sha256
```

---

## English

This repository-style archive contains OccultSchool Chinese texts in Traditional Chinese and Simplified Chinese. It is generated for preservation and reuse, using UTF-8 Markdown, JSON metadata, SHA-256 checksums, and CC BY-SA 4.0 licensing.

- Repository URL: https://github.com/occultschool/western-occult-texts-zh
- Generated at: 2026-05-26T11:51:16
- Citation metadata: `CITATION.cff`
- Preservation notes: `PRESERVATION.md`
