## 概要

## 詳細
#### アップデート(update.json）

■ 推奨アップデート：
```
{
    "latestVersion": "1.0.1",
    "minimumVersion": "1.0.0",
    "message": "新しいバージョンがあります。"
}
```
- 「新しいバージョンがあります」と表示
- 「あとで」で閉じられる
- latestVersion を更新する

■ 強制アップデート：
```
{
  "latestVersion": "1.0.1",
  "minimumVersion": "1.0.1",
  "message": "ゲームを続けるにはアップデートが必要です。"
}
```
- 「アップデートが必要です」と表示
- 戻る操作やダイアログ外タップで閉じられない
- minimumVersion をインストール済みバージョンより上げる
- 通常は latestVersion も同じ値まで上げる
