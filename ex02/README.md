# 第2回
# 超高機能電卓（ex02/calc.py）
# 追加機能
- 四則演算：＋以外䛾四則演算をする
- クリア：entryに入力されている数字，数式の1文字をdeleteする
- オールクリア：entryに入力されている数字，数式の文字列全体をdeleteする
- 平方根ボタン : entryに入力されている数字の平方根を取る
- 00ボタン : 0を一度に二つ入力する


# ToDo（実装しようと思ったけど時間がなかった）
- べき乗ボタン
- sinなどの三角関数の計算
- %に変更
- 指数関数の計算
- x^yのように自由に累乗可能なボタン
- 「*」ボタンと「/」ボタンをそれぞれ「×」と「÷」ボタンと表示されるようにする


# メモ
- ブランチを作るコマンド：git branch ブランチ名
- ブランチを切り替えるコマンド：git switch ブランチ名
- mainブランチに戻るコマンド：git switch main
- ブランチを切り替える前に，すべて䛾変更履歴をコミットした方がいい


# 反省
- プログラムが少し乱雑になってしまった。もう少しコンパクトにする。
- クリアボタンで最期に入力した数字を消そうとしたら、最初に入力した文字から順番に消えるようになってしまった。
