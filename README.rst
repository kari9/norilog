========================
乗りログアプリ
========================

目的
=====

Webブラウザーでコメントを投稿するWebアプリケーションの練習。

ツールバージョン
=================
:Python:    3.7.1
:pip:       19.0.1

インストールと起動方法
====================

リポジトリーからコードを取得し、その下のvenv環境を用意します::

    $ git clone https://github.com/kari9/norilog
    $ cd norilog
    $ python -m venv venv
    $ source venv/bin/activate
    (venv) $ pip install .
    (venv) $ norilog
    * Running on http://127.0.0.1:8000/

開発手順
=======

開発用インストール
-----------------

１．チェックアウトする
２・以下の手順でインストールする::

    (venv) $ pip install -e .