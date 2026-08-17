# switch-sale

テクノエッジ向けのSwitchセール一覧ページの配信用リポジトリ。
https://sale.techno-edge.net/ (GitHub Pages + カスタムドメイン)

- 実体は [nintendo-sale-sorter](https://github.com/sotakaki/nintendo-sale-sorter) が毎朝07:00(JST)に生成する `docs/te.html`
- このリポジトリのActions(`.github/workflows/sync.yml`)が毎朝07:30に取り込み、`docs/index.html` として公開する
- アフィリエイトのトラッキングIDは本体リポジトリ側の `AMAZON_TAG` 環境変数で指定
