# finance-desk（金融デスク・提案サポート）

個人用。日本の上場企業 1 社について、投資銀行のカバレッジ・バンカーの「初回提案までの頭の動き」を再現する。

- 流れ：企業カルテ → シグナル検知 → 切り口の生成 → 証拠の収集 → 提案メモ → 赤入れ → 書き戻し
- データ：edinetdb.jp（MCP）→ EDINET API v2 → J-Quants → TDnet → 会社 IR。有料データは使わない
- 出力：Markdown の提案メモ（Excel／PPT は上流の pitch-deck / comps-analysis スキルを使う）
- 設計の経緯：Rogo（投資銀行向け AI）のリバースエンジニアリング（Obsidian › リバースエンジニアリング › 金融 › 2026-10-31）

## 構成
- `skills/finance-desk/SKILL.md` — 親スキル（手順）
- `skills/finance-desk/references/angles.md` — 切り口カタログ A1〜A12
- `skills/finance-desk/references/signals.md` — シグナル台帳 S1〜S16
- `skills/finance-desk/references/memo-template.md` — 提案メモの型

## 守ること
公開開示のみ。投資助言はしない。数字には出典、取れない数字は「未取得」。
