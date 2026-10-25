# Porotto

入力した文章や音声認識の結果を、配信画面の字幕として表示するWindows向けアプリです。VOICEVOXでの読み上げ、辞書、字幕テキストの保存にも対応しています。

## インストール

[GitHub Releases](https://github.com/simawo/porotto-releases/releases)から、`porotto_バージョン番号_x64-setup.exe` をダウンロードして実行してください。Windows 64bit版です。

VOICEVOX Engineとローカル音声認識モデルは、必要なものをPorotto内からダウンロードできます。

### Windowsの警告について

現在のPorottoには、発行元を証明するWindows用のコード署名を付けていません。そのため、起動時に「WindowsによってPCが保護されました」（Microsoft Defender SmartScreen）や「不明な発行元」と表示される場合があります。SmartScreenは署名やダウンロード実績などで判定するため、この表示だけでウイルスが検出されたという意味ではありません。[Microsoftの説明](https://learn.microsoft.com/ja-jp/windows/apps/package-and-deploy/smartscreen-reputation)

このリポジトリの[最新リリース](https://github.com/simawo/porotto-releases/releases/latest)からダウンロードしたインストーラーであることを確認し、実行する場合はSmartScreenの「詳細情報」→「実行」を選んでください。

ウイルス対策ソフトが脅威を検出した場合は別途確認が必要です。保護機能を無効にせず、[Issues](https://github.com/simawo/porotto-releases/issues)へ警告の内容をお知らせください。

## 配信画面への表示

Porottoの配信用URLを、OBSのブラウザソースやXSplitのWebpageソースへ設定してください。テキスト入力・音声認識・VOICEVOXのうち、必要な機能だけを使用できます。

## アプリの更新

アプリ内からの更新機能に対応しており、起動時に更新を確認します。「更新を自動確認」をOFFにして、手動で確認することもできます。自動でインストールや再起動を行うことはありません。更新がある場合は、設定の「アプリ情報」から適用してください。更新後にアプリが再起動するため、配信が終わってからの操作をおすすめします。

## 利用条件

- [利用規約](TERMS.md)
- [プライバシーポリシー](PRIVACY.md)
- [ライセンス・クレジット](LICENSES.md)
- [VOICEVOXの利用について](VOICEVOX.md)

不具合の報告は、このリポジトリの[Issues](https://github.com/simawo/porotto-releases/issues)へお願いします。
