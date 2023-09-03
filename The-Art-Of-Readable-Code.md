## The Art Of Readable Code

![IMG_7609.jpg](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/3332958/88addbdf-3276-8fc3-64c7-e1d53e5bccc9.jpeg)

### 「最も読みやすいコードは、何も書かれていないコードだ。」
最も読みやすいコードは、何も書かれていないコードだ。
<br>
最初、私はこの言葉の意味が分かりませんでした。
<br>
その時点で４章くらいまで読んでいたのですが、途中で飽きてきて全部は読んでいないけど感想を書こうかなと考えていました。
<br>
私の前には、昨日TSUTAYAで借りた漫画が乱雑に置かれていました。
<br>
まだ、一冊も漫画を読んでいません。私は本を読んでいるのです。
<br>
それはただ夏休みの宿題だからという理由だけではなくて、この本には何か吸い込まれるような魅力があったのだと思います。
<br>
１ヶ月前にリーダブルコードがAmazonから送られてきた時はとても喜んで、お母さんに感謝のLINEをしましたが今ではもうそんなことも忘れてしまいました。
<br>
ただ、この本を最後まで読みたい。その執念が私の目をかろうじて開けさせてくれました。
<br>
海外に旅行に行っている時も、台湾でタクシーに乗っている時も、私の胸はリーダブルコードでいっぱいでした。
<br>
どのようにしたら、良いコードを書けるのか。そして良いコードとは一体何なのか。
<br>
そんなことを考える夏休みになりました。
<br>
一章を読み終えたあたりに、私の目が少し変わったことに気がつきました。
<br>
ただの目ではありません。コードを見る目です。
<br>
まず、夏休みの課題のDjangoをやっている際にあるデータベースのコードをYoutubeで見ました。
<br>
しかし、私はそのコードが汚いと感じたのです。
<br>
ほんの１ヶ月前では考えもしなかったことを感じるようになったのです。
<br>
具体的には、改行の仕方です。変なところで改行していてコードが読みづらくなっています。
<br>
Post クラスでは、変数が以下のように定義されています。
<br>
```python
favourites = models.ManyToManyField(
        User, related_name='favourite', default=None, blank=True)
```

一方、Commentクラスではこのようになっています。
<br>
```python
post = models.ForeignKey(Post,
                             on_delete=models.CASCADE,
                             related_name='comments')
```

UserとPostがバラバラの行になっています。
<br>
こんな細かいところ、関係ないんじゃない？と思うかもしれませんが、リーダブルコードを読んでからは世界が変わってくると思います。
<br>
２章では、良いコメントの仕方を学びました。
<br>
自分のコードにも良いコメントをしようと試行錯誤しました。簡潔に、でもコードを見た相手が理解できるようなコメントを書くことは案外難しいのだと分かりました。
<br>
本当のことを言うと、３章からはあまり覚えていません。しかし、私の内面化では何かが変わったのだと確信しています。
<br>
ようやく、私はこの本を読み終えました。なぜ諦めなかったのか私にも分かりません。唯一思い当たることは、以前上原さんが言っていた「最後までやりきれ！」と言う言葉をうっすらと思いながら読んでいたのかなということです。
<br>
読んでいる時に、将来100年後かもっとかもしれませんが、脳にこの本のテキストをインプットして1秒で本を一冊読むことが可能になるのかと思っていました。
<br>
そうなると、楽だなと思ってしまった自分が少しいました。
<br>
それは、本当に「最後までやりきる」ことになるのか。
<br>
私たちが考えるべきことはそこだと思いました。
<br>
しかし、仮にそうなったとしてもリーダブルコードを最後まで読んだことは私の脳の中にきちんと残っています。
<br>
良いコードを書こうとした自分も、この文章を書いている自分も全て残っているのです。
<br>
良いコードを考えることをやめるとその自分達をいつか忘れてしまうかもしれません。
<br>
なので、私は決して忘れません。
<br>
自分で考え続けて、「リーダブルコード」を書き続けたいと思います。
<br>
<br>
<br>


[リーダブルコード
ーより良いコードを書くためのシンプルで実践的なテクニック（Theory in practice）ー](https://www.amazon.co.jp/リーダブルコード-―より良いコードを書くためのシンプルで実践的なテクニック-Theory-practice-Boswell/dp/4873115655/ref=sr_1_1?adgrpid=104469311186&hvadid=651746087973&hvdev=c&hvlocphy=1009717&hvnetw=g&hvqmt=e&hvrand=4053586439001498452&hvtargid=kwd-931102096746&hydadcr=1308_13596571&jp-ad-ap=0&keywords=リーダブルコード.&qid=1693546086&sr=8-1)
<br>
<br>
[Dustin Boswell](https://www.amazon.co.jp/Dustin-Boswell/e/B0068WNFOW/ref=dp_byline_cont_book_1) (著), [Trevor Foucher](https://www.amazon.co.jp/s/ref=dp_byline_sr_book_2?ie=UTF8&field-author=Trevor+Foucher&text=Trevor+Foucher&sort=relevancerank&search-alias=books-jp) (著), [須藤 功平](https://www.amazon.co.jp/s/ref=dp_byline_sr_book_3?ie=UTF8&field-author=%E9%A0%88%E8%97%A4+%E5%8A%9F%E5%B9%B3&text=%E9%A0%88%E8%97%A4+%E5%8A%9F%E5%B9%B3&sort=relevancerank&search-alias=books-jp) (解説), [角 征典](https://www.amazon.co.jp/%E8%A7%92-%E5%BE%81%E5%85%B8/e/B00429JIAI/ref=dp_byline_cont_book_4) (翻訳)
<br>
<br>
- **おすすめ度**　　　⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️

### Thank you for reading!!
