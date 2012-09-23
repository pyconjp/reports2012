=================================
 PyCon JP 2012 参加レポート第1回
=================================

2012年9月15日から17日までの3日間、都立産業技術大学院大学で毎年恒例になりましたPyCon JP 2012 が開催されました。

本記事では3回に渡り、PyCon JP 2012 で行われたセッションについてレポート致します。第1回の今回では、主にPyCon JP の紹介と、KeyNote の模様をお伝え致します。

****************
 PyCon JP とは
****************
PyCon JP とは、アメリカやヨーロッパを始めとする15ヶ国以上で開催されているプログラミング言語Python のカンファレンスPyCon の日本バージョンです。日本国内はもちろんのこと、アメリカや台湾などからも参加者が訪れました。

また、PyCon JP の開催に先立ち開催されたPyCon Taiwan にPyCon JP の運営スタッフが参加しました。その模様は `「PyCon Taiwan 2012」参加レポート <http://gihyo.jp/news/report/01/pycon-taiwan2012>`_ でご報告させていただいています。

**************
 参加に先立ち
**************
PyCon JP 2012 では昨年開催されたPyCon JP 2011 に引き続いてスマートフォンアプリ、guidebook が配布されました。guidebook とはiOS, Android, Blackberry, Windows Phone 7 で使用することができる、イベントガイドブックアプリです。

セッションの一覧やセッション紹介、発表者プロフィールが見られることはもちろん、スケジュール機能がついており、どのセッションを聞くかを事前に決め、セッションが始まる前にアラートを出してくれる機能が搭載されています。

************
 ノベルティ
************
PyCon JP 2012 ではノベルティとして参加者全員にPyCon JP ステッカーにストラップ、そして缶バッジが渡されました。また、8月中に参加登録を済ませた方全員にグレーのT シャツも配られました。

.. image:: /_static/participants-1st-novelty.jpg
    :width: 45%
.. image:: /_static/participants-1st-Tshirt.jpg
    :width: 45%

今回のPyCon JP 2012 ではYouTube Live によってすべてのセッションが生放送された上、セッションの録画がいつでもYouTube で見ることができるようになっています。

*********
 Keynote
*********
##################################################################
 Armin Ronacher (`@mitsuhiko <https://twitter.com/mitsuhiko>`_)氏
##################################################################

Armin 氏は開発チーム `Pocoo <http://www.pocoo.org/>`_ の創立者の1人で、 Pacoo チームとしてWSGI ツールキットのWerkzeug を始め、ドキュメント作成支援ツールのSphinx 、テンプレートエンジンJinja2 、そしてマイクロウェブフレームワークのFlask を開発したことで知られています。

またArmin 氏は日本好きでも知られ、彼がハンドルとして使っている"mitsuhiko" は漫画「名探偵コナン」の登場人物から来ているとお話されていました。また、彼が発表で使用していたマシンのホスト名は名は"nausicaa" に設定されていました。

Armin 氏のKeyNote は「Happiness Through Ignorance」というタイトルで、技術に関することではなく、主にプログラマーに関することで、色々なことを無視することで幸せになれる、というお話でした。

----------------------------------------
 あるオープンソースソフトウェアのゲーム
----------------------------------------
Armin 氏は、後にMac App Store で公開されたあるオープンソースソフトウェアのゲームを例にあげました。このゲームの実装は、残念なものでコードはとても初心者的でした。しかし、このゲームは成功を収めました。それは、この開発チームが、初心者的な実装を気にせず、とても多くのことを"無視すること"によってもたらされました。

--------------------
 複雑さは幸せを殺す
--------------------
SAML 2.0 はXMLをベースにした認証情報提供者と、サービス提供者の間で認証情報を交換するためのオープンな規格です。この規格には、XML, XPath, XPath Filter 2.0, Xpointer, XLST, HTTP, XMLENC, X509, XMLDSIG, Canonical XML が使われています。もし、これをスクラッチで実装しようとするなら、これは非常に難しく幸せになれません。SAML は非常に複雑なので、SAML を使うソリューションを販売する企業の金儲けの方法になっています。対して、SSO 101はわずか20数行で実装することができます。

また、PHP は成功した言語の1つだと思っています、とも述べられました。それは、PHP は問題を抱えている言語ですが、学ぶことは非常に簡単で、PHP をはじめることは簡単だからだそうです。

------
 資料
------
* `発表スライド <https://speakerdeck.com/u/mitsuhiko/p/happiness-through-ignorance>`_
* `YouTube 発表録画 <http://www.youtube.com/watch?v=EDlFk1hc8kc>`_

#########################################################
 小飼 弾 (`@dankogai <https://twitter.com/dankogai>`_)氏
#########################################################
小飼氏はプログラミング言語Perl のJcode.pm というライブラリを開発したことで知られています。また、Perl 5.8 の開発にも携わりました。

.. figure:: /_static/dankogai.*
   :width: 640px

   小飼 弾氏


.. figure:: /_static/dankogai_screen.*
   :width: 640px

   セッションの部屋があふれたために別室でのストリームの放送も行われた


-----------------------------------
 The Three Virtues of a programmer
-----------------------------------
小飼氏はまず、Perl 開発者であるLarry Wall 氏が提唱した"The Three Virtues of a Programmer" にPerl, Ruby, Python を当てはめて、"Laziness" はPerl 、"Impatience" はRuby、そして"Hubris" はPython であると述べられました。

Python がHubris である理由を"Zen of Python" に絡めてKeynote の主題としてお話になりました。

---------------
 Zen of Python
---------------
Zen of Python とは、"Python らしさ" を示した19行の短い詩です。Python のインタプリタを立ちあげ、"import this" を実行することでいつでも全文を読むことができます。

また、以下のように PEP(Python Extension Proposal) としても登録されています。
`The Zen of Python (PEP20) <http://www.python.org/dev/peps/pep-0020/>`_

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 Beautiful is better than ugly.
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
小飼氏はまず、Zen of Python の"Beautiful is better than ugly." という記述について、配列の各要素をjoin する処理を例として取り上げました。
オブジェクト指向言語であるRuby, JavaScript, Python において、Ruby, JavaScript は"配列オブジェクトのメンバメソッド" を使って配列要素をjoin するのに対し、Python は文字列オブジェクトのメンバメソッドを使って行う、という特徴を持っています。この独特な方法は果たして、"Beautiful" なのか、小飼氏は会場にいるPythonista に問いかけました。結果、会場でこの実装を"Beautiful" だと思っている人がマイノリティであることが印象的でした。

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 Explicit is better than implicit.
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
次に、小飼氏はPython で文字列を表現する際のuリテラルを取り上げました。Python 2系では文字列を表すのに、str 型とunicode 型が存在します。ただのクオートでくくられたものはstr 、uリテラル付きクオート(u"" ないし, u'') でくくられたものはunicode 型として扱われています。小飼氏はまず、この表現は明示的でよい、とおっしゃいました。
一方、Python 3では文字列を表すものはPython 2のunicode 型が名を変えたstr 型のみになりました。この変更に伴い、Python 3系ではuリテラルが廃止されました。しかし、Python 3.3 ではこのu リテラルが復活し、ただのクオートとuリテラル付きクオートが同じものとして扱われる事になりました。この過去からのimport について、小飼氏は"わけがわからないよ" とおっしゃっていました。

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 There should be one-- and preferably only one --obvious way to do it.
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
小飼氏は、Python のlen 関数を取り上げました。len(u"\U0001F40D") これを実行するとどんな結果が返ってきますか - 小飼氏の問いかけに対して会場から出てきた答えは、1, 2, "わからない" の3つで、小飼氏がおっしゃった正解は"わからない"でした。u"\U0001F40D"はUnicode のサロゲートペアで、未定義領域にある2文字をあわせて1文字を表現します。Python が"--enable-unicode=ucs4" オプションと共にコンパイルされたならサロゲートペアは適切に扱われlen は1を返しますが、そうでない場合は2 を返します。この動作は言語としての一貫性を失っており大きな問題である、と小飼氏はおっしゃりました。

また小飼氏は、Perl はサロゲートペアの問題の対応を10年前に対応を終わらせ、Rubyは5年前に対応を終わらせているが、Python もこの問題の対応は終わった、と言っているもののこのとおりの振る舞いを見せている、という事実も加えて説明なさりました。

小飼氏はPerl の開発者としてJcode.pm など文字エンコードに関するモジュールを開発してきた経験からか、Python の文字の扱いに関することについて特に大きな時間を割いてお話になっていました。

| セッションの最後に小飼氏は
| "禅は唱えるべきものではありません
| 禅はなすべきものです"
| とおっしゃってKeyNote を締めくくりました。

------
 資料
------
* `発表スライド <http://www.dan.co.jp/~dankogai/pyconjp2012/python.html>`_
* `YouTube 発表録画 <http://www.youtube.com/watch?v=H8zcRv_XyeQ>`_

*********************
 MongoDB with Python
*********************
Mathias Stearn 氏によるPython からMongoDB を扱う方法を解説するセッションです。Mathias Stearn 氏はMongoDB を開発している10gen のエンジニアで、彼自身MongoDB サーバーコアの開発やMongoDB のC++ ドライバーのメンテナンスを行なっています。

.. figure:: /_static/mongodb.*
   :width: 640px

   Mathias Stearn 氏


.. figure:: /_static/mongodb_banner.*
   :width: 640px

   MongoDB の開発元である 10gen は PyCon JP 2012 のスポンサーでもある


#########
 MongoDB
#########
MongoDB はリレーショナルでないデータベースで、JavaScript で操作し、データをJSON(正確にはBSONというバイナリ化されたJSONライクな表現方式)で表現します。

Python からMongoDB に接続するモジュールにpymongo があります。このセッションではこのpymongo の使い方の解説が主なテーマでした。

######
 CRUD
######
pymongo では、ドキュメントを表すためにPython のdict 型を使用します。pymongo の各種メソッドにこのdict を渡すことでCRUD を実現します。

###########
 MapReduce
###########
MongoDB では冒頭に書いたとおり、JavaScript で操作します。MapReduce も同様で、map, reduce 共にJavaScript の関数で定義します。pymongo からMapReduce を利用する場合も、JavaScript の関数を定義するコードを文字列としてpymongo に渡すことで行います。

#####
 ORM
#####
pymongo にORM の機能はありませんが、Python のclassmethod を利用することで、辞書ではなくオブジェクトとしてドキュメントを扱う事ができます。サンプルコードをMathias Stearn さんのスライドより引用します。::

    import pymongo
    conn # pymongo.Connection()
    db # conn['test']

    class Post:
        @classmethod
        def by_id(cls, id):
            p # cls()
            p.__dict__ # db.posts.find_one({'__id': id})
            return p

        def save(self):
            db.posts.save(self.__dict__)


筆者は自身で運営するサービスでMongoDB を利用していますが、このセッションの後半で主にMongoDB 自身の機能について知らない事が多く取り上げられ目から鱗でした。

######
 資料
######
* `YouTube 発表録画 <http://www.youtube.com/watch?v#Gd05QjkceH8>`_


*********************************************
 シンプルなシステム構成フレームワーク alnair
*********************************************
稲田 尚也氏によるセッションで、ご自身がPython で開発したサーバー構築ツールalnair(アルナイル) の解説でした。

####################
 サーバー構築ツール
####################
複数台のサーバーを構築する作業はとても面倒なものです。筆者も複数台のサーバーを運用しているためその苦労がよくわかります。この作業をなるべく自動化するツールとして稲田氏があげられたのが以下の3つ。

* Chef
* Puppet
* Kokki

しかし、これらには専用にサーバーを立てる必要や、Ruby を導入する必要等があり、それぞれに導入コストがかかります。

########
 alnair
########
稲田氏が製作したalnair では、作業マシンにPython が入っていれば、専用のサーバーを立てる必要も、インストール先のサーバーに事前準備を剃る必要もなくサーバーを構築することができます。

alnair の導入はalnair がPyPI に登録されているため、easy_install コマンドまたはpip コマンドによって導入することができます。

alnair は個々のパッケージ導入方法をレシピと呼び、このレシピを定義するファイルは標準的なPython スクリプトです。従って、Python を知っていれば新たに専用のDSL や複雑な設定を覚える必要はなく使い始めることができます。さらに、レシピにはPython からできるすべての操作を記述することができるので、導入が複雑なパッケージも自動で導入することができるそうです。

######
 資料
######
* `発表スライド <http://www.slideshare.net/naoina/alnair>`_
* `YouTube 発表録画 <http://www.youtube.com/watch?v#ZLcSnreXvj4>`_


**********
 次回予告
**********
次回はPyCon JP で行われたセッションの内、主にWeb 開発に関するものを取り上げる予定です。よろしくお願いします。
