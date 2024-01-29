# 1章

# アプリの起動方法(m1 mac)

```zsh
chmod +x tools/HardwareSimulator.sh
# アプリの起動
./tools/HardwareSimulator.sh
```

# 実装手順
1. `/projects/01/*.hdl`のPARTS:の部分に実装を書いていく。
2. 文法は本書の付録A.1~A.6を読むこと
  - とくに複数bitの扱いはA.6をよく読む
3. アプリの左上の回路ボタンから実装したhoge.hdlを読み込む
4. テストは紙のようなボタンからテストファイルhoge.tstを読み込む
5. >>ボタンを押してテストが実行され、下に`End of script - Comparison ended successfully`が表示されたら成功
6. すべてのhdlファイルを1~5の手順で実装する