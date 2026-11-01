# ビデオ再生時のコントロールバーを非表示にする

##  概要

##  手順


###   手順 1. スタイルシートを有効化する

- `about:config`  を開く
- `toolkit.legacyUserProfileCustomizations.stylesheets` を `true` に変更

###   手順 2. スタイルシートを設定する

- プロファイルのフォルダを開く
- このフォルダにある chrome フォルダをプロファイルにコピーする

###   手順 3.

- `about:config`  を開く
- 以下のピクチャーインピクチャーの設定を変更する
    - `media.videocontrols.picture-in-picture.improved-video-controls.enabled`
      を `false`  に変更。シークバーなどを非表示にする
    - `media.videocontrols.picture-in-picture.audio-toggle.enabled`
      を `false`  に変更。音量バーを非表示にする
