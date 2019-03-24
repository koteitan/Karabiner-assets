# Karabiner-assets
Mac用のキーバインド設定のassetです。下記の設定ができます。

## 内容
- terminal アプリでの ctrl と command の入れ替え
  - Windows の Ctrl は Mac では command キーになっているのに Termnal の Ctrl は Ctrl のままなので Terminal だけ入れ替えます。
- 入力ソースに２つ以上のキーバインドを与えられないので増やします。具体的には ctrl+spacebar をOSの設定の入力ソーストグルにアサインしてある前提で、shift+spacebar にも同様の効果を与えます。

## 設定方法
- Karabiner-Elements というアプリを使って設定します。
  - Karabiner のダウンロードとインストールはこちら:
    - https://pqrs.org/osx/karabiner/
  - json ファイルを ~/.config/karabiner/assets/complex_modifications/ に置きます。
  - Karabiner app を起動して Complex Modifications タブを開いて Add rule を押して欲しいやつをEnable押します
