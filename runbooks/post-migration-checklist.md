# Post Migration Checklist

Last updated: 2026-04-16

他PCへ移行したあと、このプロジェクトをそのまま運用再開するための確認メモ。

## 1. Git / GitHub
- ローカルでこのリポジトリが開ける
- `origin` が `kmatsuda0608-beep/openclaw-ai-marketing-note-company` を向いている
- fetch / pull / push ができる
- GitHub のブラウザログインが必要なら新PC側でも済ませる

## 2. OpenClaw運用
- OpenClaw が起動する
- Slack DM から通常どおり会話できる
- 必要なら Gateway / Browser Relay が使える
- ブラウザ経由の補修作業が必要になった時に GitHub タブへ接続できる

## 3. プロジェクト実務で埋めるもの
- `configs/brand-config.working.md` を実データで埋める
- SNSアカウント情報を整理する
- 初回運用日に `logs/templates/daily-log-template.md` をコピーして日次ログを作る

## 4. おまつさん側で用意してもらうと早いもの
- ブランド名
- 発信者プロフィールの方向性
- X / Threads / Instagram / YouTube のアカウント名 or URL
- 実績として出してよい情報
- 禁止したい表現や触れたくない話題

## 5. 詰まった時に先に切り分けること
1. GitHub に入れない
2. push / pull だけ失敗する
3. Browser Relay が ON にならない
4. Slack では話せるがブラウザ操作だけできない
5. 新PCで OpenClaw の起動方法が分からない

## 6. 現時点の結論
移行によって致命的な崩れは見つかっていない。
不足していたのは、運用再開後に人が埋める実ファイルと確認メモなので、そこを追加して進める。
