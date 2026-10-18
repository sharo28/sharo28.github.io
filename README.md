# sharo28.github.io

個人開発アプリケーションの公開ポータルおよびサポート・法的文書（プライバシーポリシー・利用規約・審査用テスト素材）用静的Webサイト（GitHub Pages）。

## 運用方針
- 静的HTML/アセットの配信専用リポジトリです。
- `main` ブランチへ直接コミット＆pushすることで、GitHub Pages へ即時反映されます（PRやWorktree運用は不要）。

## ディレクトリ構成
- `index.html`: アプリ公開一覧・サポート窓口
- `monorika/`: Monorika アプリ関連
  - `privacy.html`: プライバシーポリシー
  - `terms.html`: 利用規約
  - `sample_qrs/`: Apple審査員用テストQRコード集 (`index.html` + 画像3枚)
- `snapscale/`, `snapsauce/`: 各アプリの公開静的ページ
