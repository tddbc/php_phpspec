TDDBC for PHP with PhpSpec
==========================

これは、TDDBCのPHP向けPhpSpecプロジェクトです。

動作環境
--------

* PHP5.3.3以上

セットアップ
------------

```sh
curl -sS https://getcomposer.org/installer | php
composer.phar install
```

`./bin/phpspec`を実行して

```sh
$ ./bin/phpspec run
_______________________100%________________________2


2 examples (2 passed)
6ms
```

のようにテストが正常終了すればOKです。

ライセンス
---------

MIT ライセンスです (詳しくはプロジェクト直下の LICENSE をご覧ください)
