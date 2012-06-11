=======
 Day 2
=======

PayCon Taiwanの運営者へのインタビュー
=====================================
2日目の朝食後に PyCon Taiwan の chairperson(座長)の
Yung-Yu Chen (`@yungyuc <http://twitter.com/yungyuc>`_)氏に時間をとってもらい、インタビューを行いました。
インタビューには PyCon Taiwan スタッフの Timtan 氏にも同席頂きました。

- 今回、なぜ PyCon Taiwan を開催しようと思ったんですか?

大きく2つの理由があります。

1つ目は台湾で Python コミュニティを広く認知してもらいたいと思っているからです。
台湾では多くの人が OSS コミュニティに関わったりしていますが、そのうち 1/10 くらいの人が python を使っていると思います。Java に比べると少ないのが現状です。

.. Industory I start 
   mostly inside 
   lot of people in python. OSS community.
   1/10 くらいは python.
   Java の方が多い

2つ目の理由は Sinker [#]_ が 2011 に開催したアンカンファレンス [#]_ です。
アンカンファレンスで Python についてのセッショんを呼びかけたところ 100 人程度が参加してくれました。
2008年にも Python について呼びかけましたが、そのときは50〜70人が集まったと記憶しています。

Python について話しをしたい人たちがいると感じたので、知り合いでミーティングを行い PyCon Taiwan の開催を決意しました。
US で行われている PyCon のように Python に関わるいろいろな人達の出会いの場となることを期待しています。

.. [#] Sinker: PyCon JP で日本にも来日して発表を行なった台湾の Python 開発者。
.. [#] アンカンファレンス: (アンカンファレンスの説明)

.. Secondary: Sinker 2011 Unconference をやった。2011 100 people.
   2008 50-70 くらい。

   Unofficial meeting をやった。

   PyCon US
   いろんな人達に会えるので、やった。

   Academia Sinica にお金は払っているが co-organizer してくれているので安い。

.. - The goal of PyCon Taiwan.

- 今後 PyCon Taiwan が目指すゴールはどういったものですか?

継続すること、より大きくなっていくことです。
また、継続するためには主催者が燃え尽きないことが大事であると考えています。
主催者は頑張り過ぎない必要があると思います。メンバーがお互い協力しあって会を運営する必要があると考えています。

Python では○◯といいますがこれはプログラミングだけではなく、PyCon イベントの進め方についても共通した考え方だと思っています。

今後、PyCon Taiwan が Pythonic way となることを期待してます。
(pythonic way とは)

.. 1 thing. sustend(つづけて大きくすること)
   nobody should be burn out.

   organize effort.
   organize member collaborating.
   Python やるならやり方はひと通りだよね。これはプログラムだけじゃなくて。

   PyCon Taiwa が Pythonic way となることを期待している。

- 参加者とその内訳を教えてください

全体で260名程度が参加登録してくれました。チケットの制限は250の予定でしたが最終的にこのようになりました。
海外からの参加者は10〜15人程度だと思われます。また台湾在住のオーストラリアの方も参加してくれているようです。
2つのスポンサーが今回つきましたが、スポンサーのボスも台湾人ではありません。

スタッフは当日スタッフも含めて30名程度です。メインスタッフは5〜10人くらいのチームリーダーがいました。
Peter はスポンサー企業のボスですが、もともと予定していた Keynote スピーカーが2週間前に病気にかかり急遽参加できなくなたときに、 Peter のつてで代役を無事探すことができました。

.. - How many participants(from taiwan, outside taiwan).

   - taiwan: 260(limit 250)
   - 10 to 15, 2 keynote, au or america live taiwan.
   - 2つのスポンサー企業のボスも台湾の人じゃないよー
   - staff: 30(当日スタッフとかも)メインスタッフは5 - 10くらいの team leader がいる
   - peter はスポンサーしてくれて: keynote スピーカーのこととか 2週間前に病気になって人変えたりとか手伝ってもらった

- 台湾の Python コミュニティについて教えてください

台湾は Python を使用しているユーザは多いがコミュニティはありません。
Python を使って仕事はしているが、メインのしごとは OSS やコンピュータサイエンスであるという人が多いです。
今回の PyCon Taiwan をきっかけに Python ユーザの横のつながりができ、台湾の Python 事情が変わることを期待しています。

.. - How about Taiwan python community.
   - 水面下で動いている
   - taipei は python ユーザは多いけどコミュニティはない
   - python で仕事はしてるけど、メインは OSS やコンピュータサイエンスなのでpythonではない
   - python ユーザのつながりを作れたらいいなぁ
   - 20回ここでイベントやっている
   - python の人と話すのに飢えているので
   - PyCon Taiwan が変わるといいな
   - Numpy/Scipy 使っているけどコントリビュートは自分はできてない
   - taiwan にはspecific user group.
   - taiwan ユーザーグループは英語のユーザーグループに参加したりしているかも

- 最後の日本の Pythonista にメッセージをお願いします。

We love YOU and Python.

.. - How about python/perl/ruby and other language in Taiwan.
   - Message to Pythonista in Japan.

- どうもありがとうございました。

Keynote
=======
- Python and the Web
- James Tauber(@jtauber)
- Pinax の人
- Eldarion という会社で Django ベースとかでサービスを提供している
- python と web の歴史は似ている

python
------
- pandas, music21, sphinx, PyPI, crate.io

Web
---
- HTML とかから
- 画像
- SSI, CGI
- PHP
- LAMP
- Jabascript
- JSON
- github とかからAPIでとりだしてページを表示

Python and web
--------------
- Zope/Plone: Full stack
- WISG(ウィズギー): CGIっぽいやつ
  Pythonic way
- Flask は小さいのにはいいけどね
- Django: out of the box
- Instagram, Pinterest

最近4年Pinaxやっている

Pyjamas
=======
- Rasiel Chang
- `pyjamas - Python Web Widget Set and python-to-javascript compiler: make your own AJAX framework - Google Project Hosting <http://code.google.com/p/pyjamas/>`_
- python を書いて js と html を生成する GWT みたいなもの
- Single page のアプリケーションには向いているが、普通のweb pageには向いてない

toki
====
- ネットワークゲームのログ解析とか分析のバックエンドについて
- Twisted, Django, MongoDB とか使ってる
- ログは Mongo DB に。スキーマないしログ形式の変更に柔軟に対応できる

Windows Azure
=============
- Windows Azure 上で Python で開発できるよ

日本からの発表
==============
- PyCon JP Promotion -- An Introduction to Python Community in Japan 
- `Shoma Hosaka <http://pycon.tw/2012/speaker/#shoma_hosaka>`_
- I hate Java!!
- メンバーの紹介

PyKinect
========
- ericsk
- Kinect for Windows
- PyKinect How-to
- References

CyberLink Meets Python
======================
- Honder Tzou

QtQuick GUI Programming with PySide
===================================
- Garylee
- `Qt Quick <http://qt.nokia.com/products-jp/qt-quick/>`_
- Qt ベース
- QMLで定義
- Qt Designerとか
- PySide
- PySide v.s. PyQt

What Can Meta class Do For You?
===============================
- hychen
- Singleton, Countable, Class Verification などの例を使って Meta Class プログラミングについて説明

Closing
=======
- プレゼントが配られた
- 日本から持っていったプレゼントも配布された

Dinner
======

PyCon JP 2012のお知らせ
=======================
(たかのり担当)
