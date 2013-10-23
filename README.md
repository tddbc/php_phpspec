TDDBC for PHP with PhpSpec
==========================

これは、TDDBCのPHP向けPhpSpecプロジェクトです。

動作環境
--------

* PHP5.3.3以上


* windowsの場合は以下をインストールしておく必要があります
   * comporser.bat (http://getcomposer.org/download/)
   * curl (http://curl.haxx.se/download.html)


セットアップ
------------

### windows 以外の場合
```sh
$ curl -sS https://getcomposer.org/installer | php
$ composer.phar install
```

`./bin/phpspec`を実行して

```sh
$ ./bin/phpspec run

    Acme\Sample

    10 ✔ is initializable
    15 ✔ said formats hello name


2 examples (2 passed)
6ms
```

のようにテストが正常終了すればOKです。

### windowsの場合
```sh
> curl -sS https://getcomposer.org/installer | php
> php composer.phar install
```
もしcurlがhttpsのエラーになる場合は該当urlの内容をcomposer.pharという名のファイルに保存後
コマンド php composer.phar install を実行してください。


`.\bin\phpspec`を実行して

```sh
> .\bin\phpspec run

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
