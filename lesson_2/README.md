# vi 講座(emacs使いはすっ飛ばして結構です)

* vi file名

* insert modeとcommand modeが存在
* insert modeへの切り替えは「i」
* command modeへの切り替えは「esc」

## command
### カーソル移動系
* h = ←, j = ↓, k = ↑, l = ⇢
* 「gg」で先頭
* 「G」で末尾
* 「0」で行頭
* 「$」で行末

### 編集系コマンド
* 「:w」 で上書き保存
* 「:q」 で終了
* 「:q!」 で保存せずに終了
* 「dd」で行削除
* 「yy」で行コピー
* 「p」でペースト

### 検索系コマンド
* 「/」のあとに検索したい文字列を入れる
* 検索中に「n」で次へ、「N」で前へ

0. vi-test.txtをvimで開こう
1. 上下左右にカーソルを動かそう
2. insert modeで適当な文字を入力しよう
3. command modeにしよう
4. 「ここにテキストが入ります」をコピペしよう
5. コピペした行を削除しよう
6. 「ここ」を検索しよう
7. 保存しよう
8. 終了しよう
