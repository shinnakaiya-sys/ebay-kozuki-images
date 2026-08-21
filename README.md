# ebay-kozuki-images

eBay出品用の画像ホスティング専用リポジトリ（`ebay-kozuki` 統合システムが使用）。

構成: `<model_key>/01.jpg` `02.jpg` ... （1枚目がeBayのサムネイルになる）

このリポジトリの内容は GitHub Pages で公開され、`config.yaml` の
`images.base_url` から参照される。手動で編集せず、`ebay-kozuki` 側の
スクリプトから撮影画像を追加・削除する。
