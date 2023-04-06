# HTMLの基礎（chapter2)

## 基本構造を作る
  
### **【ソースコード】**

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>猫の実態</title>
    </head>
    <body>
        <h1>猫の実態</h1>
        <p>猫の実態を紹介します。</p>
        <h2>猫の趣味は？</h2>
        <h3>お昼寝大好き！</h3>
        <p>猫は毎日12～16時間は睡眠をとると言われています。ただし、熟睡している時間は意外と少なく、
            ほとんどが浅い眠りです。物音がするとすぐ目をさますのはそのせいなんですね。</p>
        <img src="images/cat001.jpg" alt="昼寝している猫">
        <h3>爪とぎは欠かせません</h3>
        <p>爪とぎをする4つの理由！</p>
        <ul>
            <li>するどい爪の維持</li>
            <li>マーキング</li>
            <li>リラックスや気分転換</li>
            <li>自己アピール</li>
        </ul>
        <h3>気が付けばやっている毛づくろい</h3>
        <p>猫はなぜ「毛づくろい」をするのか？必要不可欠なこと？</p>
        <a href="https://www.anicom-sompo.co.jp/nekonoshiori/4730.html">猫との暮らし大百科</a>
        <h2>好きな食べ物は？</h2>
        <table border=1>
            <tr>
                <th>順位</th>
                <th>食べ物</th>
                <th>理由</th>
            </tr>
            <tr>
                <td>1</td>
                <td>焼き魚</td>
                <td>やっぱりお魚が大好き</td>
            </tr>
            <tr>
                <td>2</td>
                <td>チーズ</td>
                <td>アミノ酸の旨みを感じる味覚をもっていて美味しいと感じる</td>
            </tr>
            <tr>
                <td>3</td>
                <td>鶏肉</td>
                <td>猫は肉食で実は魚よりも肉がすきな猫もいます</td>
            </tr>
        </table>
        <form action="sample.html" method="post" name="contact-form">
            <table>
                <tr>
                    <td>名前：</td>
                    <td><input type="text" placeholder="名字　名前"></td>
                </tr>
                <tr>
                    <td>メールアドレス：</td>
                    <td><input type="email" placeholder="aaaa@gmail.com"></td>
                </tr>
                <tr>
                    <td>性別：</td>
                    <td>
                        <input type="radio" name="gender" value="男">男
                        <input type="radio" name="gender" value="女">女
                        <input type="radio" name="gender" value="その他">その他
                    </td>
                </tr>
                <tr>
                    <td>好きな色：</td>
                    <td>
                        <input type="checkbox" name="color" value="赤" checked>赤
                        <input type="checkbox" name="color" value="青">青
                        <input type="checkbox" name="color" value="黄">黄
                        <input type="checkbox" name="color" value="緑">緑
                    </td>
                </tr>
                <tr>
                    <td>血液型：</td>
                    <td>
                        <select name="bloodtype">
                            <option value="A">A</option>
                            <option value="B">B</option>
                            <option value="O">O</option>
                            <option value="AB">AB</option>
                            <option value="不明" selected>不明</option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td>メッセージ：</td>
                    <td>
                        <textarea neme="message">メッセージ入力</textarea>
                    </td>
                </tr>
            </table>
            <input type="submit" value="送信する">
        </form>
    </body>
</html>

```

<!-- #### **【結果】**   -->

<!-- - [ ] 実行して、「リスト一覧」の文字が表示されること   -->

<!-- ![結果](img/01_result.png) -->
