# 問題を進めるにあたり
特に注釈がない限り「 > 」で始まる行はコマンドの入力を表します。

例）以下のケースの場合コマンドプロンプトへ`java Sample`と入力し、その結果として`12345`が表示されています。
```
> java Sample
12345
```

# Hint
実装問題は問題の多様性を追求し、一部資格範囲外の技術を用いる場合があります。下記項目を参考にし実装してください。

## ユーザーからの入力を受け付ける
例題：ユーザーから数字の入力を受け付け表示するプログラムを作成せよ

```
> java Sample
あなたの年齢は？→20
あなたは成人です！
```

```java
import java.util.Scanner; // 重要です

class Sample{
	public static void main(String[] args){

		System.out.print("あなたの年齢は？→");
		Scanner sc = new Scanner(System.in);
		int inputAge = sc.nextInt(); // これでユーザーから数値を受け取れます

		if( inputAge >= 20 ){
			System.out.println("あなたは成人です");
		}else{
			System.out.println("あなたは成人ではありません");
		}
	}
}
```

### 解説
`Scanner`クラスを利用することでユーザーからの入力を受け付ける事ができます。`int型`を受け取る`nextInt`メソッド、`String`を受け取る`next`メソッドなどがあります。