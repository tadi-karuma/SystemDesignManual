# 🧭 INDEX.md：SystemDesignManual 構成目次

本ドキュメントは、SystemDesignManual リポジトリ内の各ファイルが果たす役割と、それらの関係性を明示するための目次です。構想設計を構造的に進めるために、どの文書をどう参照すべきかを把握する助けとなります。

---

## 📁 構成カテゴリ一覧

### 1. 設計・評価指針
- [`docs/DESIGN.md`](DESIGN.md)：構想設計における原則と構成要素の説明
- [`docs/ETHICS.md`](ETHICS.md)：構想に必要な倫理観・責任設計・想定被影響者の把握
- [`docs/EVALUATION.md`](EVALUATION.md)：構想をどう評価し検証するかの視点

### 2. 構想実施に向けた支援
- [`docs/AI_USAGE.md`](AI_USAGE.md)：AIを活用した構想支援の使い方と留意点
- [`docs/AI_INPUT_TEMPLATE.md`](AI_INPUT_TEMPLATE.md)：AIに構想を渡すときの入力テンプレート
- [`docs/ai_prompts/AI_COMMAND_TEMPLATE.md`](ai_prompts/AI_COMMAND_TEMPLATE.md)：AIへの命令文テンプレート
- [`docs/ai_prompts/AI_STRUCTURAL_CHECKLIST.md`](ai_prompts/AI_STRUCTURAL_CHECKLIST.md)：構造整合性・重複検出テンプレート
- [`docs/ai_prompts/AI_SUMMARY_TEMPLATE.md`](ai_prompts/AI_SUMMARY_TEMPLATE.md)：応答が長くなったときの要点整理テンプレート
- [`docs/ai_prompts/AI_COMPLETION_REVIEW.md`](ai_prompts/AI_COMPLETION_REVIEW.md)：構想全体の完成度評価テンプレート

### 3. テンプレート（構想記述用）
- [`docs/templates/template_generic.md`](templates/template_generic.md)：汎用構想テンプレート
- [`docs/templates/template_policy.md`](templates/template_policy.md)：制度・政策構想用テンプレート
- [`docs/templates/template_technical.md`](templates/template_technical.md)：技術・仕様提案用テンプレート
- [`docs/templates/template_research.md`](templates/template_research.md)：研究構想・助成申請用テンプレート

### 4. 構想事例（Examples）
- [`examples/list.md`](../examples/list.md)：実際にテンプレートで記述された構想事例集

### 5. 運営・貢献情報
- [`CONTRIBUTING.md`](../CONTRIBUTING.md)：このリポジトリへの貢献・改善方法の案内

---

各ファイルは独立して読める構造になっていますが、`DESIGN.md` → テンプレート → `AI_INPUT_TEMPLATE.md` → `AI_USAGE.md` → `EVALUATION.md` の順に進めると効果的です。

