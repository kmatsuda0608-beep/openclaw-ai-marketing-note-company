# openclaw-ai-marketing-note-company

OpenClawベースで、AIとWebマーケ（広告）領域の **X → 無料note → 有料note** 導線を、**5人部隊構造**で運営するためのプロジェクト。

## 初期方針
- Claude Codeそのものではなく、OpenClawで同等構造を再現
- 初期MVPは自動投稿なし
- 5人部隊をできるだけ再現
- テーマは AI / Webマーケ（広告）
- 人確認前提の半自動運用から始める

## 5人部隊
1. オーケストレーター
2. X集客部隊
3. 無料note部隊
4. 有料note部隊
5. 販売導線部隊

## 現在あるファイル
- `requirements/requirements-v1.md` — 要件定義の正式版
- `requirements/kpi-draft.md` — 初期KPI案
- `configs/brand-config.example.md` — ブランド設定のたたき台
- `runbooks/daily-operations.md` — 日次運用runbook
- `workflows/content-production-flow.md` — 制作フローの固定化メモ
- `prompts/` — 5部隊の土台プロンプト
- `samples/` — 日次素材テンプレ / 承認テンプレ
- `logs/README.md` — ログ保存方針メモ

## 現在の進捗
- 要件定義 v1 作成済み
- KPI初期案 反映済み
- 日次運用runbook 作成済み
- 5部隊の土台プロンプト 作成済み
- サンプル素材テンプレ / 承認テンプレ 作成済み
- GitHub同期用の初期構成整理済み

## 次の作業
1. 各部隊の出力サンプル作成
2. ログ運用ルールの具体化
3. ブランド設定ファイルの実運用版作成
4. 初回運用ログの雛形追加
