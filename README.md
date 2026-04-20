# Claude Code 技能庫

精心整理的 Claude Code 技能集合，用於增強開發工作流程和提高生產力。

> ⚠️ **重要提醒：請只啟用你需要的技能！**
> 每個啟用的技能都會將其 `SKILL.md` 載入到 Claude 的 context 中，**不必要的技能會持續消耗 context 空間，增加 token 費用並降低回應品質。**
> 建議依照專案需求，只勾選當前工作流程所需的技能。

## 📚 技能清單

### 設計與規劃
| 技能 | 說明 |
|------|------|
| **brainstorming** | 創意設計流程，透過對話將想法轉化為完整設計和規格 |
| **prd** | 產品需求文件（PRD）生成指南 |
| **planning-with-files** | 基於檔案的多步驟任務規劃與追蹤，支援 `/clear` 後自動恢復 |

### 程式碼開發
| 技能 | 說明 |
|------|------|
| **code-simplifier** | 簡化和重構程式碼，保持功能不變，提升可讀性與一致性 |
| **simplify** | 對所有已變更檔案進行品質審查並修正問題 |
| **code-review** | 透過 GitHub CLI 對 Pull Request 進行自動化程式碼審查 |
| **test-driven-development** | 測試驅動開發（TDD）指南，先寫測試再實作 |

### 文件處理
| 技能 | 說明 |
|------|------|
| **docx** | Word 文件（.docx）建立、編輯、分析與格式處理 |
| **pdf** | PDF 處理（合併、分割、表單填充、OCR 等） |
| **pptx** | 簡報（.pptx）建立、編輯與內容擷取 |

### 開發工具
| 技能 | 說明 |
|------|------|
| **mcp-builder** | Model Context Protocol (MCP) 伺服器開發指南 |
| **skill-creator** | 創建、改善和評估 Claude Code 技能的完整工作流程 |

## 🔧 安裝方式

在 Claude Code 中，透過 `/skills` 指令加入此儲存庫：

```
https://github.com/skyksl066/skills
```

## 💡 快速對照

| 需求 | 使用技能 |
|------|---------|
| 設計新功能前的思考 | `brainstorming` |
| 撰寫需求文件 | `prd` |
| 規劃複雜多步驟任務 | `planning-with-files` |
| 審查 PR | `code-review` |
| 重構/精簡程式碼 | `code-simplifier` / `simplify` |
| 測試驅動開發 | `test-driven-development` |
| 處理 Word 文件 | `docx` |
| 處理 PDF | `pdf` |
| 製作簡報 | `pptx` |
| 開發 MCP 伺服器 | `mcp-builder` |
| 製作新技能 | `skill-creator` |

## 🏗️ 目錄結構

```
skills/
├── brainstorming/           # 設計流程和想法構思
├── code-review/             # PR 程式碼審查
├── code-simplifier/         # 程式碼簡化重構
├── docx/                    # Word 文件處理
├── mcp-builder/             # MCP 伺服器開發
├── pdf/                     # PDF 處理
├── planning-with-files/     # 檔案型任務規劃
├── pptx/                    # 簡報處理
├── prd/                     # 產品需求文件
├── simplify/                # 程式碼品質審查
├── skill-creator/           # 技能創建工具
└── test-driven-development/ # TDD 指南
```

每個技能目錄包含：
- `SKILL.md` - 技能定義與使用指南（啟用後載入 context）
- `scripts/` - 輔助執行腳本（按需載入，不佔用 context）
- `references/` - 參考文件資源