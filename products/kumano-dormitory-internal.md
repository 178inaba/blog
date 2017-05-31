title: 熊野寮内部ページ
abstract: 熊野寮で使われるWebアプリ
image_path: /assets/image/kumano-dormitory-internal.png
technologies: Django | Python | Bootstrap
---

- [ソースコード](https://github.com/genya0407/kumanodocs)

PythonのWebフレームワーク[Django](http://djangoproject.jp/)で作成した。

私が居住している京都大学熊野寮の寮生用ページ。

寮には、月に二回開かれるホームルームのようなものがある。
このWebアプリは、そこで読む資料を出力するWebアプリである。
大まかには、記事を投稿・閲覧する機能と、それらの記事を一つのPDFファイルにまとめて出力する機能の二つからなっている。

突貫で作成したということもあり、汚く長すぎるコードが散見される。現在リファクタリング中である。

投稿された記事は寮外秘ということになっているので、アクセスできません。ご容赦ください。
