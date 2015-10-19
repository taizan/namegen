### usage

var nameGen = new NameGen();
name1 = nameGen.getName( NameGen.prototype.name_base.france ,"castle" );
name2 = nameGen.getName( NameGen.prototype.name_base.german ,”river” );

名前のタイプと後に付ける称号のタイプを指定してそれっぽい名前を生成します。
名前のタイプは今の所franceとgerman

アルゴリズム的には３つくらいのワードを組み合わせてるだけですが、
フィn + eスト ＝ フィネストみたいな感じで、音の途中の組み合わせも一応出来る様にしています。

参考：http://tinyangel.jog.client.jp/Name/NameGenerator.html　それっぽい名前ジェネレータ