# Post-Migration Checklist

Last updated: 2026-04-15

他PCへ移行した直後に、人側で確認すると詰まりにくい項目をまとめる。

## 今回の結論
現時点では、OpenClaw / GitHub / Browser Relay は再開可能な状態まで確認済み。

## 1. すぐ必要な確認（優先）
### 1-1. GitHub
- GitHub にログインできている
- 対象リポジトリ `openclaw-ai-marketing-note-company` を開ける
- 編集・アップロード・コミットができる

### 1-2. Browser Relay / Chrome拡張
- OpenClaw Browser Relay の拡張が入っている
- GitHub 作業タブで Relay が ON になっている
- ブラウザ操作が必要な時に、対象タブへ再アタッチできる

### 1-3. Slack / OpenClaw
- Slack DM から通常どおり会話できる
- メインスレッドと必要スレッドが読める
- OpenClaw が起動していて、このDMから作業再開できる

## 2. できれば確認したいこと
### 2-1. 再起動耐性
- PC再起動後も OpenClaw を立ち上げ直せる
- Chrome と Browser Relay を復旧できる
- GitHub ログイン状態が保持される

### 2-2. 作業環境
- 新PCでも `openclaw-ai-marketing-note-company` リポジトリにアクセスできる
- 旧PCと新PCで使うアカウントがズレていない
- 必要なブックマーク / タブ / 拡張が揃っている

## 3. もし詰まったら優先して教えてほしいこと
1. GitHub に入れない
2. Browser Relay が ON にならない
3. Slack では話せるがブラウザ操作だけできない
4. 新PCで OpenClaw の起動方法が分からない
5. リポジトリやファイル場所が変わった

## 4. 今後追加で共有してほしい情報（必要になったら）
- 新PCで使うブラウザが変わったか
- GitHub / Slack / note / SNS のログイン状態
- ファイル保存場所や運用ディレクトリが変わったか
- 自動起動や再起動後の復旧手順で困った点
