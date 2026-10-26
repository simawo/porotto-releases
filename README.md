# Porotto

入力した文章や音声認識の結果を、配信画面の字幕として表示するWindows向けアプリです。  
VOICEVOXでの読み上げ、辞書、字幕テキストの保存にも対応しています。

- [Porottoの使い方](GUIDE.md)

## インストール

[GitHub Releases](https://github.com/simawo/porotto-releases/releases)から、`porotto_バージョン番号_x64-setup.exe` をダウンロードして実行してください。（Windows 64bit版のみ対応）

### Windowsへのインストール時の警告について

Porottoには、発行元を証明するWindows用のコード署名を付けていません。  
そのため、起動時に「WindowsによってPCが保護されました」（Microsoft Defender SmartScreen）または「不明な発行元」と表示される場合があります。

当リポジトリの[最新リリース](https://github.com/simawo/porotto-releases/releases/latest)からダウンロードしたインストーラーであることを確認し、インストールを実行する場合はSmartScreenの「詳細情報」→「実行」を選択してください。

## 配信画面への表示

Porottoの配信用URLを、OBSのブラウザソースやXSplitのWebpageソースへ設定してください。  
字幕表示・音声認識によるテキスト入力・VOICEVOX読み上げのうち、必要な機能だけを使用できます。（VOICEVOX Engineはアプリ内からダウンロードできます）

## 利用条件

- [利用規約](TERMS.md)
- [プライバシーポリシー](PRIVACY.md)
- [ライセンス・クレジット](LICENSES.md)
- [VOICEVOXの利用について](VOICEVOX.md)

不具合の報告は、このリポジトリの[Issues](https://github.com/simawo/porotto-releases/issues)へお願いします。
