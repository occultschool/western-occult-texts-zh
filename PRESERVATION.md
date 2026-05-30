# 数字保存记录 / 數位保存記錄 / Digital Preservation Record

**Repository**: OccultSchool Texts — Chinese Archive  
**Curator**: OccultSchool (神秘学讲堂 / 神秘學講堂)

**Generated**: 2026-05-30T22:25:00

**Primary URL**: https://github.com/occultschool/western-occult-texts-zh

**Archive Landing Page**: https://occultschool.org/archive/

**Project Source Record**: https://github.com/CoderSci/lightcoder

## 简体中文

这份文件记录典藏包的长期保存位置、校验方式与接手原则。典藏包的目标是：即使原网站、原域名或原维护者不可用，中文文章与书籍仍能被下载、校验、重新托管和继续阅读。

### 保存副本

| 平台 | URL / Identifier | 狀態 |
| --- | --- | --- |
| GitHub | https://github.com/occultschool/western-occult-texts-zh | active |
| Zenodo | https://zenodo.org/records/19637071 / https://doi.org/10.5281/zenodo.19637071 | active |
| Internet Archive | https://archive.org/details/western-occult-texts-zh | active |
| Software Heritage | https://archive.softwareheritage.org/browse/origin/directory/?origin_url=https://github.com/occultschool/western-occult-texts-zh | active |
| Hugging Face Datasets | https://huggingface.co/datasets/occultschool/western-occult-texts-zh | active |

### 完整性校验

本资料集根目录包含 `manifest.sha256`。解压后可执行：

```bash
shasum -a 256 -c manifest.sha256
```

若任一文件被破坏、遗失或替换，校验会显示 `FAILED`。遇到这种情况，请改从其他公开镜像重新下载。

### 简易阅读器

`index.html` 是可直接托管的典藏首页，会导向 `reader/index.html`。如果原网站无法维护，接手者可阅读 `HOST_THIS_ARCHIVE.md`，将解压后的整个资料夹上传到任意静态主机。此阅读器是便利阅读层；长期保存仍以 Markdown、PDF/EPUB、`catalog.json` 与 `manifest.sha256` 为准。

### 保存原则

本资料集遵循 LOCKSS 原则：Lots Of Copies Keep Stuff Safe。请将此资料集保存于多个独立平台，并在新增镜像后更新本文件或 release notes。

---

## 繁體中文

這份文件記錄典藏包的長期保存位置、校驗方式與接手原則。典藏包的目標是：即使原網站、原網域或原維護者不可用，中文文章與書籍仍能被下載、校驗、重新託管並繼續閱讀。

`index.html` 是可直接託管的典藏首頁，會導向 `reader/index.html`。若原網站無法維護，接手者可閱讀 `HOST_THIS_ARCHIVE.md`，將解壓後整個資料夾上傳到任意靜態主機。此閱讀器是便利閱讀層；長期保存仍以 Markdown、PDF/EPUB、`catalog.json` 與 `manifest.sha256` 為準。

本資料集遵循 LOCKSS 原則：Lots Of Copies Keep Stuff Safe。請將此資料集保存於多個獨立平台，並在新增鏡像後更新本文件或 release notes。
