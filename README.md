# DocCraft

**DocCraft** 是可供 Claude Code 與 Codex 使用的精簡技術文件撰寫 Skill，強調**以人為本的可讀性**、Markdown 結構、精確措辭及文件可維護性。

## 功能

- 將複雜規則拆成易讀的段落、條列、步驟與必要的表格。
- 撰寫或改善 README、技術說明、開發者操作手冊及設計文件的表達方式。
- 改善文件的表達、結構與可讀性，保留原有需求與規格意義；遇到歧義或矛盾時提出問題，不自行定案。
- 遵守既有文件的名稱、格式、連結與專案慣例。
- 文件移動或改名時更新相關引用；尊重既有產生流程。
- 依專案既有工具執行適用的文件驗證，不虛報結果。

DocCraft 不強制所有文件使用 `Design/` 或 Obsidian；對這類細節遵循專案既有規範。

## Repository 結構

```text
DocCraft/
├── README.md
├── CHANGELOG.md
└── skills/
    └── doc-craft/
        └── SKILL.md
```

## 安裝

將 `skills/doc-craft/` **整個資料夾**複製到對應工具的 Skill 目錄：

| 工具 | 個人 Skill 目錄 | 專案 Skill 目錄 |
| --- | --- | --- |
| Claude Code | `~/.claude/skills/` | `.claude/skills/` |
| Codex | `~/.agents/skills/` | `.agents/skills/` |

安裝後的檔案路徑例如 `~/.claude/skills/doc-craft/SKILL.md`。工具版本可能影響重新載入方式，請以實際環境為準。

若要放上 GitHub，請先解壓縮，並將 `DocCraft/` **內部內容**上傳至 Repository 根目錄。

## 使用範例

- 「幫我把 README 改成新開發者容易上手的版本。」
- 「整理這份 API 操作說明，保留所有必要條件，但讓段落更容易理解。」
- 「把這段複雜流程改寫成清楚的操作步驟。」

## 維護

- 以單一精簡 `SKILL.md` 為核心，需要時才加入參考文件。
- 不預設任何特定程式語言、Markdown lint 指令或專案目錄。
- 先在 Claude Code 與 Codex 中測試觸發、文字改寫、格式與引用更新，再考慮發布穩定版本。
- 初版未包含 `LICENSE`；公開授權方式由 Repository 擁有人決定。
