# alrc-align

音源と歌詞から、ぴったり同期する歌詞ファイル（`.alrc`）を自動で作るツールです。
[Think Songs](https://think-songs.com) の開発者向けのお試し版で、Mac（Apple シリコン）と 64 ビットの Windows で動きます。

- 行ごと・文字ごとの時刻を自動で付けます
- 漢字にふりがなを付け、歌声と合わない読みは確かめます
- 音源も歌詞も外へ送らず、パソコンの中だけで処理します
- Gemini・OpenAI・Claude のキーを自分で入れると、背景画像も作ります

歌詞は自分で用意してください（歌詞サイトから自動では取りません）。

## 入手と使い方

**<https://think-songs.com/alrc-align>** からダウンロードできます。Python や ffmpeg を入れる必要はありません。

## 不具合の報告

[Issues](https://github.com/kanemaru/alrc-align/issues) か、Discord の開発者チャンネルへお願いします。
OS、版（`--version` で出ます）、実行したコマンド、画面に出たエラーを書いてください。

**音源、歌詞の本文、API キーは貼らないでください。** ここは誰でも読める場所です。

## このリポジトリについて

案内と報告の窓口です。ツールのソースコードは置いていません。
利用条件は配布物の `TERMS.txt`、同梱の部品のライセンスは `THIRD_PARTY_NOTICES.txt` にあります。
