## ディレクトリ構造
- ./src/.env は WordPress で使用する環境変数を簡単に追加するファイルです。
- ./src/config には 開発/検証/本番 で使用する WordPress のシステム設定が記述されたファイルが格納されており、各ファイルは wp-config.php に相当しています。また、処理内容は ./src/.env の環境変数を define 展開するようなものです。
- ./src/web/app は実装したコードを配置するディレクトリで、wp-content に相当しています。
- ./src/web/wp は WordPressのシステムコードが集約されており、開発者は基本的に触らずに隠匿しておきます。また、./src/web/wp-config.php も Bedrock では触る必要はありません。

引用 (https://www.tolog.info/wordpress/bedrock-docker/)

## 参考リンク
- https://www.tolog.info/wordpress/bedrock-docker/
