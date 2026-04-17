# Contributing to the Western Occult Texts Archive

Thank you for your interest in contributing to this archive. This project aims to make Western esoteric wisdom accessible to Chinese-speaking readers — your help is deeply valued.

## What We Welcome

- **Corrections**: Typos, mistranslations, or formatting errors in existing texts
- **New translations**: Additional books or articles from the Western esoteric tradition
- **Metadata improvements**: Better descriptions, keywords, or difficulty tags on existing files
- **New article contributions**: Original commentary in the `docs/` categories

## File Format Standards

All files must follow this format to be accepted:

### Filename Convention
- Books: `NNN_章節標題.md` (e.g., `001_序言.md`, `002_第一章.md`)
- Articles: descriptive kebab-case or Chinese names with no spaces

### YAML Front-Matter (required for all files)

```yaml
---
sidebar_label: "顯示在側邊欄的短標題"
title: "完整頁面標題 | 書名 作者"
slug: /unique-url-slug
description: "150字以內的摘要描述"
keywords: ["關鍵詞1", "關鍵詞2", "關鍵詞3"]
custom_tags: [標籤A, 標籤B]
difficulty: "beginner" | "intermediate" | "advanced"
---
```

### Encoding
- **Always UTF-8**. Do not save in GB2312, Big5, or any other encoding.
- Use **Traditional Chinese** for `zh-Hant/` and **Simplified Chinese** for `zh-Hans/`

### Dual-Script Requirement
If you add content to one language directory, please provide the equivalent in the other directory as well (or note in your pull request that a translation is pending).

## How to Contribute

1. **Fork** this repository
2. Create a new branch: `git checkout -b add/book-name` or `git checkout -b fix/issue-description`
3. Make your changes following the file format standards above
4. Submit a **Pull Request** with:
   - What text was added/changed
   - Source of the original text (with publication date if applicable)
   - Confirmation that the source is in the public domain or CC-licensed

## Source Text Guidelines

For **book translations**, please include in your pull request:
- The original title and author
- Original publication year
- Confirmation the work is in the public domain (generally: published before 1929, or explicitly CC-licensed)

## Code of Conduct

This archive exists to preserve and share knowledge. Contributors are expected to engage with respect and intellectual honesty. Discussion of the texts is welcome; personal attacks are not.

## Questions?

Open a GitHub Issue or start a Discussion thread.
