# openclaw-ai-marketing-note-company

OpenClawベースで、AIとWebマーケ（広告）領域の **X → 無料note → 有料note** 導線を、**5人部隊構造**で運営するためのプロジェクト。

いわゆる「note自動化ツール」を単体ツールとして作るのではなく、**継続運用できる制作組織**として再現する方針を採る。

## 初期方針
- Claude Codeそのものではなく、OpenClawで同等構造を再現
- 初期MVPは段階導入とし、まずはXスレッド自動投稿から着手
- 5人部隊をできるだけ再現
- テーマは AI / Webマーケ（広告）
- まずは人確認付きで運用し、その後にXスレッド自動投稿へ寄せる

## 5人部隊
1. オーケストレーター
2. X集客部隊
3. 無料note部隊
4. 有料note部隊
5. 販売導線部隊

## 現在あるファイル
- `requirements/requirements-v1.md` — 初期要件定義
- `requirements/requirements-v2-migration-reset.md` — PC移行後のGitHub連携再定義
- `requirements/requirements-v3-build-scope.md` — 今回依頼を反映した最新スコープ案
- `requirements/kpi-draft.md` — 初期KPI案
- `configs/brand-config.example.md` — ブランド設定のたたき台
- `configs/brand-config.working.md` — 実運用で埋めるブランド設定ファイル
- `runbooks/daily-operations.md` — 日次運用runbook
- `runbooks/post-migration-checklist.md` — 他PC移行後の確認メモ
- `workflows/content-production-flow.md` — 制作フローの固定化メモ
- `prompts/` — 5部隊の土台プロンプト
- `samples/README.md` — サンプル群の使い方
- `samples/` — 日次素材テンプレ / 承認テンプレ / 各部隊の出力サンプル
- `logs/README.md` — ログ保存方針メモ
- `logs/templates/daily-log-template.md` — 日次運用ログの雛形
- `logs/2026-04-15.md` — 初回GitHub反映と移行再開の記録
- `logs/2026-04-16.md` — 初回運用サンプル整備の記録

## 現在の進捗
- 要件定義 v1 作成済み
- GitHub連携再定義 v2 作成済み
- 制作スコープ v3 作成済み
- KPI初期案 反映済み
- 日次運用runbook 作成済み
- 5部隊の土台プロンプト 作成済み
- サンプル素材テンプレ / 承認テンプレ 作成済み
- 各部隊の初回出力サンプル 作成済み
- GitHub初回反映と文字化け修正 完了
- 移行後チェックメモ 追加済み
- 実運用用ブランド設定ファイル 追加済み
- 日次ログ雛形 / 初回ログ 追加済み

## 次の作業
1. Xスレッド自動投稿の運用要件を詰める
2. 投稿管理用スプレッドシートを運用開始する
3. 初回有料note案 `requirements/initial-paid-note-v1.md` をベースに販売文面を整える
4. SNSアカウント作成後に導線先URLを反映する
