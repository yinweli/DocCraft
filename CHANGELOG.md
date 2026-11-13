# Changelog

## Unreleased

- 移除執行 formatter／linter 的指示；文件 lint 是否執行由各專案規範決定。

## v0.2.0

- `description` 改成只寫觸發條件，加入中文關鍵字，並排除規格決策、程式碼註解與 commit message。
- 語言規則改為依序判斷：改現有文件時沿用原文語言；寫新文件時，依序參考專案語言規範與既有文件語言，兩者都沒有才用繁體中文。
- 新增「Reading Scope」，限定只讀目標文件、它直接連結的檔案和使用者指定的檔案；文中提到的指令、版本與預設值，要到定義它的檔案確認；只有搬移或改名文件時，才搜尋整個 repo 的引用。
- 刪除重複的規則。
- README 刪除解壓縮相關的過時說明。

> 用 Sonnet subagent 比較新舊版本：README 改寫情境中，3 次測試都抓到文件與 `package.json` 的不一致（舊版為 2/3）；單句修改情境的讀檔量和 Token 跟舊版相同。

## v0.1.0 — Initial draft

- 建立跨專案技術文件撰寫與改寫 Skill。
- 整合原始 CLAUDE.md 的 C04（可讀性）與 C13（文件規範）。
- 明確區分 DocCraft 的文件表達責任與 SpecKeeper 的規格管理責任。
- 保持單一 `SKILL.md`，避免額外參考文件與不必要 Token 成本。

> 此版本為初稿，尚未在 Claude Code 與 Codex 的實際專案中完成執行測試。
