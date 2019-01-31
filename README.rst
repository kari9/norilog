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

依存ライブラリ変更時
------------------

１．'' setup.py '' の '' install_requires '' を更新する
２．以下の手順で環境を構築する::

    (venv) $ deactivate
    $ python -m venv --clear venv
    $ source venv/bin/activate
    (venv) $ pip install -e ./norilog
    (venv) $ pip freeze > requirements.txt

３．setup.pyをリポジトリにコミットする