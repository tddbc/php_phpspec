TDDBC for PHP with PhpSpec
==========================

これは、TDDBCのPHP向けPhpSpecプロジェクトです。

動作環境
--------

* PHP5.3.3以上

セットアップ
------------

依存ライブラリのインストールは[Composer](http://getcomposer.org)を利用します

Composerのインストール方法は[公式ドキュメント](http://getcomposer.org/doc/00-intro.md)を参照ください

```sh
# For Windows (Using Composer-Setup.exe)
composer.bat install

# For *nix
php composer.phar install
```

`./bin/phpspec`を実行して

```sh
$ php ./bin/phpspec run

    Acme\Sample

    10 ✔ is initializable
    15 ✔ said formats hello name


2 examples (2 passed)
6ms
```

のようにテストが正常終了すればOKです。

ライセンス
---------

MIT ライセンスです (詳しくはプロジェクト直下の LICENSE をご覧ください)
