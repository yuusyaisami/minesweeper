# minesweeper
昔作ったゲームをもう一度作りたい、懐かしさに浸りたいという思いで作りました。
私が初めてコンピュータを触ったのは、小学生のころ
家にあるwindows vistaに内蔵されているマインスイーパーをこっそり起動して、よく遊んでいた。
それと同時並行に、ゲームの製作も行っていた、
そして、私が一番最初に作ったゲームがマインスイーパーだった。
プログラムの世界に足を踏み入れた最初のステップだった
それは今のようにオブジェクト指向でなく、すべて配列内の数値で処理を変える書き方だったため、汎用的なプログラムではなかったのを覚えている

当時はDXライブラリで作成していたが、最近はpythonを使う機会が増えたため、pythonで作成してみた。

今となってはゲームにあまり良い印象はない。
エンターテイメントとしては程度が低いと感じることが多い。

しかし、世の中には人の創造力や思考力を高めるゲームがある。
ソーシャルゲームでもなく、放置ゲームでもなく、作業ゲームでもない、クリエイティブで自由なゲームを、自分の用途に合わせて"遊んでほしい。"
スキル習得や学習において最も重要な要素は、それを楽しむことができるかどうかだと思う

# プログラム
使用する大まかなクラス
### GameScene
ゲームのシーン移行のためのクラス。
だがゲームのシーン移行は導入していない、ほかのプロジェクトに挿入する機会があるとき、使う
### Box
ユーザーのクリック検知処理や、ブロックの表示、オートでブロックをオープンする処理が書かれている
### Text
周りのbom数を表示するクラス  
### 詳細
基本的な処理はすべて、GameSceneの関数で書かれている
ブロック数を増やすと処理が重くなるのが欠点である
