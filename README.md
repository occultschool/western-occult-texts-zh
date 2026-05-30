# OccultSchool Texts — Chinese Archive

**神秘学讲堂 / 神秘學講堂文本典藏库**

**[简体中文](#简体中文) · [繁體中文](#繁體中文) · [English](#english)**

---

## 简体中文

### 这是什么

本资料集是「神秘学讲堂」（OccultSchool）的中文文本典藏库，收录网站文章、书籍译文、书籍图片资产，以及 PDF/EPUB 电子书。它是一个可长期保存、可重新发布、可研究引用的公开文本包。

这份典藏包已经整理成可直接保存和托管的静态资料集：核心文本使用 UTF-8 Markdown，机器索引用 JSON，完整性校验用 SHA-256。根目录的 `index.html` 和 `reader/index.html` 可直接托管为简易阅读网站。部分译文仍在新译、校订、补齐来源与统一术语，因此本典藏库是持续更新的 living archive，而不是最终定本。

### 内容结构

| 目录 | 说明 |
| --- | --- |
| `zh-Hans/articles/` | 简体中文文章，共 238 篇 |
| `zh-Hans/books/texts/` | 简体中文书籍 Markdown，共 547 个文本文件 |
| `zh-Hans/books/assets/` | 简体中文书籍引用图片与封面 |
| `zh-Hans/books/ebooks/` | 简体中文 PDF/EPUB，共 46 个文件 |
| `zh-Hant/articles/` | 繁體中文文章，共 238 篇 |
| `zh-Hant/books/texts/` | 繁體中文書籍 Markdown，共 547 個文字檔 |
| `zh-Hant/books/assets/` | 繁體中文書籍引用圖片與封面 |
| `zh-Hant/books/ebooks/` | 繁體中文 PDF/EPUB，共 46 個檔案 |
| `index.html` | 可直接托管的典藏首页，会进入简易阅读器 |
| `reader/index.html` | 可直接打开或上传到静态主机的简易 HTML 阅读器 |
| `catalog.json` | 机器可读目录，列出文件路径、类型、语言、标题、大小与 SHA-256 |
| `manifest.json` | 本版本的统计信息与技术记录 |
| `manifest.sha256` | 完整性校验清单 |
| `INDEX.md` | 人可读目录，按语言与类型列出主要条目 |
| `HOST_THIS_ARCHIVE.md` | 原站无法维护时的紧急托管说明 |
| `PRESERVATION.md` | 长期保存记录与公开镜像入口 |
| `CITATION.cff`、`datapackage.json`、`codemeta.json`、`.zenodo.json` | 引用、数据集与发布平台元数据 |

### 使用说明

- Markdown 文件可直接阅读、检索、引用或再整理。
- 书籍中的图片引用保留，并尽量复制对应图片与封面。
- `zh-Hans` 的资料夹名与文件名已转为简体中文，方便简体读者直接浏览。
- `reader/index.html` 是典藏包内附的便利阅读层；Markdown、PDF/EPUB、`catalog.json` 与 `manifest.sha256` 才是长期保存的主资料。
- 若原网站无法维护，请阅读 `HOST_THIS_ARCHIVE.md`，将解压后的整个资料夹上传到任意静态主机。

### 如何验证完整性

解压后在典藏包根目录执行：

```bash
shasum -a 256 -c manifest.sha256
```

如果出现 `FAILED`，表示文件损坏、缺失或被替换，请改从 GitHub、Zenodo、Internet Archive 或其他镜像重新下载。

### 如何引用

优先引用 Zenodo DOI 或特定版本页面。长期入口：

```text
OccultSchool. Western Occult Texts — Chinese Archive. Zenodo. https://doi.org/10.5281/zenodo.19637071
```

### 授权

本作品以 Creative Commons Attribution-ShareAlike 4.0 International（CC BY-SA 4.0）授权。转载、改作与再发布时，请署名「神秘学讲堂 / 神秘學講堂 (OccultSchool)」，注明是否修改，并以相同授权分享。

---

## 繁體中文

### 這是什麼

本資料集是「神秘學講堂」（OccultSchool）的中文文本典藏庫，收錄網站文章、書籍譯文、書籍圖片資產與 PDF/EPUB 電子書。它是一份可長期保存、可重新發布、可研究引用的公開文本包。

典藏包已整理為可直接保存與託管的靜態資料集：核心文本使用 UTF-8 Markdown，機器索引用 JSON，完整性校驗用 SHA-256。根目錄的 `index.html` 與 `reader/index.html` 可直接託管為簡易閱讀網站。部分譯文仍會隨新譯、校訂、補齊來源與術語統一持續更新，因此這是一個 living archive，而非最終定本。

### 重點檔案

- `zh-Hant/articles/`：繁體中文文章。
- `zh-Hant/books/texts/`：繁體中文書籍 Markdown。
- `zh-Hans/articles/`：簡體中文文章。
- `zh-Hans/books/texts/`：簡體中文書籍 Markdown。
- `index.html`、`reader/index.html`：可直接託管的簡易閱讀器。
- `catalog.json`、`manifest.json`、`manifest.sha256`：目錄、來源統計與完整性校驗。
- `HOST_THIS_ARCHIVE.md`：原站失效時的接手託管說明。
- `PRESERVATION.md`：長期保存記錄與鏡像入口。

### 校驗與再散佈

解壓後可執行 `shasum -a 256 -c manifest.sha256`。若出現 `FAILED`，請改用其他鏡像重新下載。本典藏包以 CC BY-SA 4.0 授權；轉載、改作與再散佈時，請署名「神秘學講堂 / 神秘学讲堂 (OccultSchool)」，並以相同授權分享。

---

## English

This repository-style archive contains OccultSchool Chinese texts in Simplified Chinese and Traditional Chinese. It is prepared for preservation, citation, emergency re-hosting, and research reuse, using UTF-8 Markdown, JSON metadata, SHA-256 checksums, and CC BY-SA 4.0 licensing.

- Hostable emergency entry: `index.html`
- Standalone reader: `reader/index.html`
- Emergency hosting guide: `HOST_THIS_ARCHIVE.md`
- Machine-readable catalog: `catalog.json`
- Integrity manifest: `manifest.sha256`
- Repository URL: https://github.com/occultschool/western-occult-texts-zh
- Archive landing page: https://occultschool.org/archive/
- Generated at: 2026-05-30T22:25:00
- Citation metadata: `CITATION.cff`
- Preservation notes: `PRESERVATION.md`
