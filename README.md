# プログラミングとデザイン入門
## よくある質問
### よくある質問を見たけど解決しない
- 毎週の授業があるから、先生とSAに解決しない部分を教えてくれれば、一緒に解決出来るよ！
### 画像が表示されない
- もう一度表示したいHTMLファイルから画像ファイルまでの位置関係を把握してみよう！
### VSCodeでコードを追加したはずだが、Google Chrome側で反映されない(HTMLを変更したはずなのに、CSSを変更したはずなのに、画像入れたはずなのに...)
- Google Chromeで見ているページとVisual Stadio Codeで見ているページが違うことがあるよ！変更したのに反映されない・・・と思ったら見ているファイルが正しいか確認してみよう！


## 参考ページ
[GitHubを使ってMarkdown文書を５ステップでホームページとして公開する方法](https://qiita.com/MahoTakara/items/3800e9dc83b530d0a050)

## テスト

~~~
<!DOCTYPE html>
<html lang="ja">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .box{
            width: 100px;
            height: 100px;
            background-color: skyblue;
            cursor: pointer;
        }
    </style>
    </head>

    <body>
        <div class="box" id="target"> </div>
    <script>
        'use strict';
        document.getElementById('target').addEventListener('click', ()=>{
            document.getElementById('target').style.background = 'pink';
        });
    </script>

    </body>
</html>
~~~

このような形でブラウザ上にアップすることが出来ます。
