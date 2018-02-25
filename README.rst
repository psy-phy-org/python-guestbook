===================
ゲストブックアプリ
===================

目的
=====

Webブラウザでコメントを投稿するWebアプリケーション。

ツールのバージョン
====================

:Python:     2.7.6
:pip:        9.0.1
:virtualenv: 15.1.0


インストールと起動方法
=======================

リポジトリからコードを取得し、その下にvirtualenv環境を用意します::

   $ git https://github.com/psy-phy-org/python-guestbook.git
   $ cd guestbook
   $ virtualenv .venv
   $ source .venv/bin/activate
   (.venv)$ pip install .
   (.venv)$ guestbook
    * Running on http://127.0.0.1:5000/


開発手順
=========

開発用インストール
------------------

1. チェックアウトする
2. 以下の手順でインストールする::

     (.venv)$ pip install -e .

