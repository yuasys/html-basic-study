# study001について
![](https://i.imgur.com/2kriqjf.png)
ここでは、htmlの最も基本的な知識を確認することに焦点をあてて勉強します。

1. HTML, CSS, Javascript それぞれのファイル構造と配置の関係について
2. HTMLの基本的な構造
3. CSSの基本的な記述
4. Javascriptの最小限の書き方

## Tips
### この環境に内蔵してあるServerを動かして成果物を確認しながら演習する方法
1. 必須：node.jsのインストールを確認

```bash=
# VsCodeのコンソールを開いて（ctrl+@)
$ node -v
```
![](https://i.imgur.com/GTvqPGk.png)

2. 内蔵サーバーを起動
```bash=
$ npm run dev
```
![](https://i.imgur.com/WUoYLTo.png)
ターミナル中の表示[http://127.0.0.1:5173](http://127.0.0.1:5173)のマウスを当て直接ctrlキーを押しながらクリックするとブラウザで表示できる。  
ただし、その場合このプロジェクトのルートが表示されるので[ここ(study001)](http://127.0.0.1:5173/study001)をクリックするか、ブラウザのアドレスバーでurlの最後尾に「/study001」を追記してEnterキーを押下する。

