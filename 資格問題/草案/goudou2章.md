## 変数の宣言
変数の宣言と初期化して正しい物はどれですか

1. int num = 100;
1. int num = 100L;
1. int num = "100";
1. int num = 100.0;
1. int num = '100';

`答え:1`

## 配列の宣言
配列の宣言として有効なものは次のどれですか。4つ選択してください。

1. int[] array = {1, 2, 3, 4};
1. int[] array = new int[3];
1. int []array = new int[4]{1, 2, 3, 4};
1. int[] array = new int[];
1. int []array = new int[]{1, 2, 3, 4};
1. int array = new int[];
1. int array[3] = new int[];

`答え:1,2,5`

## コマンドライン引数の利用
次のコードがあります。

```java
public Sample {
  public static void main(String[] args){
    System.out.println(args[0] + args[3]);
  }
}
```

実行する際は次とします。

`java Test 1 2`

コンパイル、実行した結果として正しい物は次のうちどれですか。1つ選択してください。

1. 03 と表示される
1. 12 と表示される
1. コンパイルエラーになる
1. 実行時エラーになる

`答え:4`

## コマンドライン引数の利用2
次のコードがあります。

```java
public Sample {
  public static void main(String[] args){
    System.out.println(args[0] + args[3]);
  }
}
```

実行する際は次とします。

`java Test args[1] = 10; //代入しました

コンパイル、実行した結果として正しい物は次のうちどれですか。1つ選択してください。

1. 00 と表示される
1. 03 と表示される
1. args[1]//代入しました と表示される
1. コンパイルエラーになる
1. 実行時エラーになる

`答え:3`

## 配列の長さ
次のコードがあります

```java
public Sample {
  public static void main(String[] args){
    boolean array1 = { true, false, false, false};
    boolean array2 = new boolean[3];
    array2[0] = true;
    array2[1] = true;
    
    System.out.println(array1.length + " " + array2.length);
    
  }
}
```
コンパイルして実行した結果として正しい物はどれですか。

1. コンパイルエラー
1. 実行時エラー
1. 4 3
1. 4 2
1. 何も表示されない

`答え:3`

##コマンドライン引数の利用
コマンドライン引数を用いて以下のような入出力結果となるJavaファイルを作成してください。

```
> javac Sample.java
> java Sample Hello World
Hello!World
```

