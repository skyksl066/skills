# Claude Code 技能與插件庫

精心整理的 Claude Code 技能與插件集合，用於增強開發工作流程和提高生產力。

## 📚 技能清單

### 設計與規劃
- **brainstorming** - 創意設計流程，透過對話將想法轉化為完整設計和規格
- **prd** - 產品需求文件編寫指南
- **planning-with-files** - 基於檔案的規劃和追蹤系統

### 程式碼開發
- **code-simplifier** - 簡化和重構程式碼，保持功能不變，提升可讀性
- **code-review** - 自動化的程式碼審查，檢查 bug 和規範遵循
- **skill-creator** - 創建和發佈高品質的 Claude Code 技能
- **test-driven-development** - 測試驅動開發指南

### 文件處理
- **docx** - Word 文件（.docx）建立、編輯和分析
- **pdf** - PDF 檔案處理（合併、分割、表單填充、OCR 等）
- **pptx** - 簡報檔案（.pptx）建立和編輯

### 整合與擴展
- **mcp-builder** - Model Context Protocol (MCP) 伺服器開發指南

## 🔧 安裝指南

### 核心技能
所有技能已在此儲存庫中，可直接使用。

### 插件
若要安裝 UI UX Pro Max 插件：

```bash
/plugin marketplace add nextlevelbuilder/ui-ux-pro-max-skill
/plugin install ui-ux-pro-max@ui-ux-pro-max-skill
```

## 📖 使用方式

1. **選擇相應技能** - 根據工作類型選擇對應的技能
2. **查看文件** - 每個技能目錄內的 `SKILL.md` 包含詳細說明
3. **按照流程** - 遵循各技能提供的步驟和最佳實踐

## 🏗️ 目錄結構

```
skills/
├── brainstorming/          # 設計流程和想法構思
├── code-review/            # 程式碼審查
├── code-simplifier/        # 程式碼簡化
├── docx/                   # Word 文件處理
├── mcp-builder/            # MCP 伺服器開發
├── pdf/                    # PDF 處理
├── planning-with-files/    # 檔案型規劃
├── pptx/                   # 簡報處理
├── prd/                    # 產品需求文件
├── skill-creator/          # 技能創建工具
└── test-driven-development/ # TDD 指南
```

## 💡 快速開始

- **設計新功能** → 使用 `brainstorming` 技能
- **審查程式碼** → 使用 `code-review` 技能
- **優化程式碼** → 使用 `code-simplifier` 技能
- **處理文件** → 選擇 `docx`、`pdf` 或 `pptx` 技能
- **開發 MCP** → 參考 `mcp-builder` 文件

## 📝 貢獻與更新

每個技能目錄包含：
- `SKILL.md` - 詳細的技能文件和使用指南
- `scripts/` - 輔助指令碼
- 參考資源和範例