## letとconst
### let    
可変的な変数の宣言。
### const　
変数を再代入させないようするための宣言。

## アロー関数
アロー関数とは、functionキーワードを必要としない関数構文。<br>
関数宣言には=>を使う。
### 引数が2つの場合
引数が2つ以上ある場合、()は省略できない。また引数を取らない場合も同様に省略できない。

### 戻り値の返し方
- 簡潔文体

array.map(number => number + number);
- ブロック文体

array.map(number => {<br>
  return number + number;<br>
});<br>
下のブロック文体の場合は自動的に値を返さないのでreturnで返す必要がある。

### アロー関数とthisについて
アロー関数のthisは、関数を囲んでいる実行コンテキストのthisの値が設定される。

### オブジェクトの分割代入
