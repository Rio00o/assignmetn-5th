# HTTPにまつわる用語

## HTTPとは
「HyperText Transfer Protcol」の略でWebサーバとクライアント(PCやスマホ)のWebブラウザがデータを送受信するためのプロトコル(通信手段)です。
プロトコルがあるから異なるメーカーや機種でも通信が可能。



## URLとは
Uniform Resource Locatorの略語で、Webサイトのページがどこに位置するのかを示す「住所」のようなもの。Internet Explorerなどのブラウザでホームページの上部に表示されており、そのhttpやhttpから始まる半角英数の文字列のこと。

## クエリ文字列とは
クエリ（検索）パラメータ（変数）や、クエストリングとも言う
http://〇〇.jp/?▢＝△
上記URLの、？以降の「?▢=△」がクエリ文字列です。

## パス変数(パラメーター)とは何か
パス変数は、ファイル・システム上のロケーションを指定します。パス変数を使用することによってディレクトリー構造をファイル・システムとまったく同じにすることなく、リンクされたリソースを含むプロジェクトをチーム・メンバーと共有することができます。

## クエリ文字列とパス変数の違いとは
①https://zenn.dev/search

②https://zenn.dev/search?q=Laravel
①と②の違いは「search」の後に「?～」があるかどうか

①のパスパラメータはsearchの部分
②の場合はパスパラメータは①と同じくsearch,クエリパラメータは?q=Laravel

https://qiita.com/Marusoccer/items/7ccc7c959ccb5efc080f

##HTTPメソッドとは何か
###GETメソッド
