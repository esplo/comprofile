(Written in Japanese)

[comprofile](https://comprofile.fun)

# 概要
comprofile は、競技プログラマー用のブログシステムです。
書きやすく、探しやすいサービスを目標としています。

# 探す機能

ツリーを展開してゆくことで、問題ごとに解法を探すことができます。

<img width="492" alt="gif_finder" src="https://user-images.githubusercontent.com/1843532/27506651-b6936058-58f7-11e7-9c61-54997f8393ed.png">


# エディターの機能

![gif_editor](https://user-images.githubusercontent.com/1843532/27494519-37d6555e-5889-11e7-8c3b-7808e72f2ae6.gif)

- 自動保存
- みたままマークダウン
- 簡単シェアボタン

## MathJax

`$`を押すと開きます。
TeXを記述し終わったら、Tabキーを押してウィンドウを閉じます。

![gif_mathjax](https://user-images.githubusercontent.com/1843532/27433392-7fef8004-578f-11e7-8f8c-47f395f97142.gif)

## カテゴリ

フォームをクリックすると、今までPublishされたカテゴリの中でサジェスチョンが出ます。
問題を一意に特定できるところまでを記入するのがオススメです。

例) 「AtCoder」「ARC」「111」「C」 をカテゴリにする

また、CodeforcesやAtCoderなど、同じ問題が別コンテストとして出題される場合は、難しい方に合わせます。
なお、"."は使えないため、Div2-BやDiv1-Aなどの表記にします。

例) 「Codeforces」「388」「Div1-B」 をカテゴリにする

![gif_category](https://user-images.githubusercontent.com/1843532/27433391-7fed4442-578f-11e7-90d4-4ab90da566a9.gif)

現時点で存在しないカテゴリを追加する際は、記入をしてEnterを押すと保存されます。

## コード

バッククオート3つ（```）に続けて言語名を書き、Enterを押すことでコードをSyntaxHighlight付きで表示します。
対応言語はcpp, java, rust, haskellなどです。要望があれば追加します。

最終行でShift+Enterを押すと、通常のブロックに戻ります。

![gif_code](https://user-images.githubusercontent.com/1843532/27433393-7ff02d9c-578f-11e7-80f7-5d59d137fde5.gif)

※ 現状、コードブロック中でいじると、表示が壊れることがあります。貼り付けのみが無難です。

## 　部分修飾

バッククオート(`)で囲むことで、背景色が変わります。
アスタリスク(*)で囲むことで、強調表示になります。

## リスト

行頭で`-`に続けてスペースを押すとリスト表記になります。
Tabを押すとインデントされ、Shift+Tabでアンインデントされます。
また、行頭で数字 + `.`を押すと番号付きリストになります。
Enter x2、またはShift + Enterで通常の段落に戻ります。

![gif_list](https://user-images.githubusercontent.com/1843532/27433394-7ff08454-578f-11e7-95e6-4918813cda64.gif)

## 絵文字

`:`を押すことで絵文字選択ができます。

![gif_emoji](https://user-images.githubusercontent.com/1843532/27434126-845af4ea-5792-11e7-9317-8f7a7a2661ae.gif)

## その他

- リンクの文字列を貼ると、勝手にリンクになります

# プロフィールの機能

ユーザーページでは、各種サイトのレーティングが追加できます。
各サイトでのハンドルを記入すると、自動で取得してきます。

![gif_rating](https://user-images.githubusercontent.com/1843532/27434638-62ba52ca-5794-11e7-9c34-efa271b11748.gif)

現在の対応サイトは、以下の通りです。

- Topcoder
- Codeforces
- AtCoder
- CodeChef
- yukicoder

`/setting`ページでSNS情報を記載すると、ここに表示されます。


# How to contribute

- 解法をどんどん書く
- 不備のあるドキュメントにプルリクを出す or 翻訳する
- バグ・要望をissueに上げる

# History

- ver. 1.0.0 - 2017/06/24
  - リリース
