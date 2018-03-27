blockはlocalの束縛を連れてく -> クロージャ

フラットスコープ
スコープゲート(class, module, def)はスコープを切り替える
スコープゲートキーワードの代わりにメソッドとブロックを使い
クロージャでスコープを共有する

共有スコープ
スコープゲートで閉じ込めた変数を
フラットスコープで共有させ
参照させる
ex. fibonatti_printer

instance_eval
レシーバをselfとしたコンテキストでblockを実行する。
blockってことはクロージャでローカル変数を共有


Proc lambda
blockを保持する nearly= クロージャを作って保持？
