# ライセンス・クレジット

最終確認日: 2026-05-20

Porotto は、多くのオープンソースソフトウェアおよび第三者成果物の上に成り立っています。
この一覧は、Porotto が同梱・任意取得・直接連携する主な第三者成果物をまとめたものです。

各成果物の利用条件は、それぞれのライセンス・規約に従います。

## アプリ基盤・UI ライブラリ

- **Tauri / Tauri Plugins**（Apache-2.0 OR MIT）— デスクトップアプリ基盤、ファイル / ダイアログ / ストア / グローバルショートカット等。 [Source](https://github.com/tauri-apps/tauri)
- **React / React DOM**（MIT）— Porotto の画面 UI。 [Source](https://github.com/facebook/react)
- **lucide-react**（ISC）— アプリ内の SVG アイコン。 [Source](https://lucide.dev/)
- **OverlayScrollbars**（MIT）— 設定画面やダイアログのスクロール表示。 [Source](https://github.com/KingSora/OverlayScrollbars)
- **SweetAlert2**（MIT）— 確認 / 通知ダイアログ。 [Source](https://github.com/sweetalert2/sweetalert2)
- **Culori**（MIT）— アプリテーマの色計算・コントラスト調整。 [Source](https://culorijs.org/)
- **Rust backend crates**（MIT / Apache-2.0 / BSD / ISC / MPL-2.0 など）— Tauri バックエンド。serde、tokio、axum、reqwest、cpal、sha2、rand、tar、bzip2、sevenz-rust2、libloading、windows-sys など。

## 同梱フォント

Porotto は字幕フォントとして WOFF2 ファイルを同梱しています。各ライセンスはアプリ内のクレジットから確認できます。

- **LINE Seed JP**（SIL Open Font License 1.1 / Copyright LY Corporation）— [Source](https://seed.line.me/index_jp.html)
- **Zen Maru Gothic**（SIL Open Font License 1.1 / Copyright 2021 The Zen Maru Gothic Project Authors）— [Source](https://github.com/googlefonts/zen-marugothic)
- **Zen Kaku Gothic New**（SIL Open Font License 1.1 / Copyright 2022 The Zen Kaku Gothic Project Authors）— [Source](https://github.com/googlefonts/zen-kakugothic)
- **Kiwi Maru**（SIL Open Font License 1.1 / Copyright 2020 The Kiwi Maru Project Authors）— [Source](https://github.com/google/fonts/tree/main/ofl/kiwimaru)
- **DotGothic16**（SIL Open Font License 1.1 / Copyright 2020 The DotGothic16 Project Authors）— [Source](https://github.com/fontworks-fonts/DotGothic16)
- **PixelMplus12**（M+ Fonts License / Copyright (C) 2002-2013 M+ FONTS PROJECT）— [Source](https://github.com/itouhiro/PixelMplus)

## 任意取得の音声認識コンポーネント

PC 内モデル方式を選んだ場合に、ユーザー操作でアプリ管理フォルダへ取得します。通常の配布物にはモデル本体を同梱しません。

- **sherpa-onnx runtime**（Apache-2.0）— PC 内音声認識の実行ランタイム。 [Source](https://github.com/k2-fsa/sherpa-onnx)
- **ONNX Runtime**（MIT）— sherpa-onnx に含まれる推論ランタイム。 [Source](https://github.com/microsoft/onnxruntime)
- **ReazonSpeech-k2-v2 / sherpa-onnx ReazonSpeech model**（Apache-2.0）— 日本語向け PC 内音声認識モデル候補。 [Source](https://research.reazon.jp/blog/2024-08-01-ReazonSpeech.html)
- **SenseVoice / FunASR model**（FunASR Model Open Source License Agreement 1.1）— 多言語 PC 内音声認識モデル候補。 [Source](https://github.com/FunAudioLLM/SenseVoice)
- **Silero VAD**（MIT）— 常時認識時の音声検出補助モデル。 [Source](https://github.com/snakers4/silero-vad)

## 連携する読み上げコンポーネント（VOICEVOX）

VOICEVOX はユーザーが有効化した場合だけ使用します。通常の配布物には VOICEVOX Engine 本体や音声ライブラリを同梱しません。

- **VOICEVOX Engine**（LGPL-3.0 または別ライセンス + VOICEVOX ソフトウェア利用規約）— Porotto 管理モードでは、ユーザーの同意後に公式 GitHub Release から固定版を取得。Engine 本体を直接再配布しない設計。 [Source](https://github.com/VOICEVOX/voicevox_engine)
- **VOICEVOX voice libraries / speakers**（話者ごとの個別規約）— 生成音声を公開・配信・配布で使う場合は、実際に使った話者ごとの規約とクレジット表記条件に従う必要があります。

VOICEVOX の利用条件・クレジット表記の詳細は [VOICEVOX 連携について](VOICEVOX.md) を参照してください。
