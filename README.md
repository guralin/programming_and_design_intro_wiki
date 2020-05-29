# プログラミングとデザイン入門のよくある質問

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

このような形でブラウザ上にアップすることが出来ます
