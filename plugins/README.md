# プラグイン

プラグインは、HonKitの機能（電子書籍やウェブサイト）を拡張するための最良の方法です。数学の公式の表示サポートを持って来る、Google Analyticを使用して訪問を追跡するなど：多くのことを行うためのプラグインが存在します。

### プラグインを探すには？

プラグインは[npmjs.com](https://www.npmjs.com/)で簡単に検索することができます。

キーワードでnpmで検索してください。`gitbook-plugin` または `honkit-plugin` とする。

### プラグインをインストールするには？

インストールしたいプラグインが見つかったら、それを `book.json` に追加する必要があります。

```
{
    "plugins": ["myPlugin", "anotherPlugin"]
}
```

を使って、特定のバージョンを指定することもできます。`"myPlugin@0.3.1"`：デフォルトでは、HonKitは現在のHonKitのバージョンと互換性のある最新バージョンのプラグインを解決します。

### プラグインを設定する

プラグイン固有の設定は `pluginsConfig` に格納される。利用可能なオプションの詳細については、プラグイン自体のドキュメントを参照する必要があります。
