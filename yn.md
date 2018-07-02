AJACS1/講習内容/part1
-----------------

<div class="body">
    <div class="section">
        [AJACS1/講習内容](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6 "AJACS1/講習内容 (3770d)")へもどる

        ---

        目次

        <div class="contents">*  自己紹介・かずさDNA研紹介 

            *  講師の中村 
            *  かずさDNA研究所 

        *  【実習】検索使い倒し 

            *  google 

                *  google は、なぜ検索できるのか 
                *  一歩すすんだ検索 

            *  googleなその他のサーヴィスを使い倒す 
        </div>

        ---

        ### [<span class="sanchor">_</span>](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6%2Fpart1#zbc1f740 "zbc1f740") 自己紹介・かずさDNA研紹介  

        <div class="jumpmenu">↑</div>

        ### [_](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6%2Fpart1#te6eb39b "te6eb39b") 講師の中村  

        * 41歳。木更津市在住。

        * こんな人です。

            * http://www.kazusa.or.jp/~yn/jp
            * http://navi.kazusa.or.jp/yn/weblog/
            * http://mixi.jp/show_profile.pl?id=49640


        * 京大→遺伝研→かずさと「ゲノム」と「情報」を扱ってきています。

        <div class="jumpmenu">↑</div>

        ### [_](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6%2Fpart1#y0a2950c "y0a2950c") かずさDNA研究所  

        我が国初の大規模ゲノム塩基配列決定研究機関です。

        * http://www.kazusa.or.jp/

            * シアノバクテリア http://www.kazusa.or.jp/cyano/
            * 根粒菌（共生窒素固定細菌) http://www.kazusa.or.jp/rhizo/
            * 高等植物(シロイヌナズナ、ミヤコグサ、ユーカリ、トマト)


        <div class="jumpmenu">↑</div>

        ### [<span class="sanchor">_</span>](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6%2Fpart1#c09d8a7d "c09d8a7d") 【実習】検索使い倒し  

        <div class="jumpmenu">↑</div>

        ### [_](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6%2Fpart1#ga0bb654 "ga0bb654") google  

        ま、とにかく、まずは「ググれ」  
        http://www.google.co.jp

        <div class="jumpmenu">↑</div>

        #### [_](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6%2Fpart1#db84050e "db84050e") google は、なぜ検索できるのか  

        * 「ロボット」もしくは「クローラー」がリンクをたどって収集にやってくる（以下はとあるかずさのWWWサーバのアクセスログにあったgooglebotの接続の痕跡）


            <pre>
            crawl-66-249-73-53.googlebot.com - - [11/Jul/2007:02:33:55 +0900] "GET /~yn/nekophoto/nekophoto-Thumbnails/82.jpg HTTP/1.1" 200 4612 "-" "Googlebot-Image/1.0"
            crawl-66-249-73-53.googlebot.com - - [11/Jul/2007:02:36:42 +0900] "GET /~yn/images/ika_kaidan.jpg HTTP/1.1" 200 25334 "-" "Googlebot-Image/1.0"
            crawl-66-249-73-53.googlebot.com - - [11/Jul/2007:02:37:01 +0900] "GET /~yn/jp/index.php?BusTable HTTP/1.1" 200 26037 "-" "Mozilla/5.0 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)"
            crawl-66-249-73-53.googlebot.com - - [11/Jul/2007:02:51:15 +0900] "GET /~yn/jp/ HTTP/1.1" 200 15718 "-" "Mozilla/5.0 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)"
            crawl-66-249-73-53.googlebot.com - - [11/Jul/2007:02:53:59 +0900] "GET /~yn/tdiary/images/ika_kaidan.jpg HTTP/1.1" 404 315 "-" "Googlebot-Image/1.0"
            crawl-66-249-73-53.googlebot.com - - [11/Jul/2007:03:03:44 +0900] "GET /~yn/jp/index.php?Genome2005Mac%2F2.BLAST HTTP/1.1" 200 23155 "-" "Mozilla/5.0 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)"
            ...
            </pre>
            * つまり「どこからもリンクのないページ」は原理的に探索不可能
            * どこかからリンクがあれば、いつかはやってくる
            * 他のサイトからのリンクが多いほど、また、更新頻度が高いほど、上位にランクされる


        * IE右上の虫眼鏡右にある三角をクリックして、検索先をLive SearchからGoogleに変えときましょう。

        * 課題：スペース、ダブルコーテーションありなしの意味は？以下の検索結果を比較しましょう。ヒット数・検索結果がそれぞれ違います。


            <pre>
            統合　データベース　センター   515,000件
            統合データベースセンター　160,000件
            "統合データベースセンター　1,060件 
            "統合　データベース　センター　1,060件
            </pre>


        * なお、規定値が「日本語のページを検索」になっていると思います。「検索オプション」から検索の対象にする言語を「すべての言語」に変えときましょう。

        * スペースやダブルコーテーションを入れる場合、全角・半角で違いがありましたか？
        * ダブルコーテーションを閉じる必要は実はない、ということに気がつきましたか？
        * ヒット数の違いが生じる理由を検索結果を参照しながら、考察しなさい

            * 概略: &color(white){単語を空白で分割して検索：OR検索が明示的にかかっている／ダブルコーテーションなし：自動的に「統合／データベース／センター」に分割された結果も混じるが、明示的に分ける程ではない／ダブルコーテーションで囲むと文字通りのフレイズで検索するのでもっともヒットが少ない（が、これも厳密ではなく、分割はされている。また、最後の例では、空白を無視している）}


        * 応用: 遺伝子のアクセッション番号やID, 遺伝子名そのものでググる  

            これが意外に使える。論文のサプリメントファイルが拾えたりする場合も。


        * 応用: 英文、とくに前置詞の使い方がただしいかどうか、ググる  

            日本人の書いた文章がたくさんかかってくると、怪しいわけですよ。


        <div class="jumpmenu">↑</div>

        #### [_](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6%2Fpart1#uf1bc65a "uf1bc65a") 一歩すすんだ検索  

        情報リテラシーを高めましょう

        * OR検索
            googleはなにも指定しないと「AND 検索」つまり、キーワード全てを含むように検索します。  

            キーワードのどちらか一部を含んでいればいい、といった検索「OR検索」には文字通り「OR」を使います。  


        * 実習: 以下の検索の意味を考え、検索結果（特に右上の検索結果数) を比較しましょう。どのように違いますか？


            <pre>
            Xenopus tropicalis laevis
            Xenopus tropicalis OR laevis
            </pre>

        * 意味: <span style="color:white"> 上：３つのキーワードが全部入っているページを検索 (216,000件) 下：Xenopusに加え、tropicalis か laevis の「どちらか」が記載されているページを検索 (1,430,000件)</span>  

        * 応用：以下はそれぞれ、どのような検索をすることになるのでしょうか。その結果は？


            <pre>
            Xenopus OR tropicalis OR laevis
            "Xenopus tropicalis" OR "Xenopus laevis"
            </pre>

        * 解答: <span style="color:white"> 上： 3つのうち、いずれかのキーワードがあればよいという、OR検索(5,410,000件)、下：「Xenopus tropicalis」または「Xenopus laevis」のどちらかのフレイズで検索(1,870,000)</span>  

        * 応用：うっかり OR を小文字にしてしまいました。するとどのような結果が得られたでしょうか？orをいれないない場合と比較してみましょう。また、後ろにorをもってくるとどうかわりますか？


            <pre>
            Xenopus tropicalis or laevis
            Xenopus tropicalis laevis
            Xenopus tropicalis laevis or
            </pre>

        * 考察: <span style="color:white">「or」のような短い頻出パターンも一応キーワードとして考慮されています。キーワードの入力順も検索の考慮の対象になっていますね。</span>  

        * \*  ワイルドカードを使ってみる  

            なにが挟まっていても良いことを示す記号。トランプで言うと「ジョーカー」みたいなものです。以下を検索するとどのような文例が得られるでしょうか。**予測してから**実行しなさい。


            <pre>
            vitamin * is good for *
            </pre>


        * ..  一定の数値範囲を指定


            <pre>
            Arabidopsis 2001..2006
            </pre>


        期間を明示的に検索したい場合「検索オプション」で詳細に指定可能。

        * -(マイナス)  キーワードを除外
            キーワード「mouse」でイキモノのネズミの情報を検索するのはかなり困難だったりする。


            <pre>
            mouse
            mouse -パソコン -ホイール -ワイヤレス -アニメ
            </pre>


        * filetype  filetype:ppt, filetype:pdf, filetype.doc, filetype:xls, filetype:txt, filetype:html  

            ファイルタイプ指定 (Powerpoint, PDF, Word書類, Excel書類, text, html)


            <pre>
            blast filetype:ppt
            mouse filetype:xls
            </pre>


        * site: inurl:  特定のサイト／URLで検索
            以下はそれぞれ何を検索しようとしているかを考え、実際に検索してみて、検索数の違いを比較しましょう


            <pre>
            東京大学
            東京大学 site:u-tokyo.ac.jp
            東京大学 -site:u-tokyo.ac.jp
            </pre>


        * 応用：癌の研究に関係するPDF書類とプレゼンテーションを、文部科学省のサイトで探しなさい
        * 解答：<span style="color:white">癌 研究 site:mext.go.jp filetype:pdf OR filetype:ppt</span>

        * 応用：データベース統合に関係するPDF書類を、内閣府のサイトで探しなさい
        * 解答：<span style="color:white">データベース統合 site:cao.go.jp filetype:pdf</span>

        * link:  特定のサイトへのリンクがあるページ


            <pre>
            link:www.u-tokyo.ac.jp
            </pre>


        * 電卓・通貨
            http://www.google.com/intl/ja/help/features.html#calculator   

            ちょっと便利だったりする。乗算はアスタリスク、アスタリスクが２つでべき乗。では以下を計算する方法は？


            <pre>
            3x2
            3の2乗
            </pre>
            * 解答：<span style="color:white">上：3*2　下 3**2 （3^2　でも可)</span>
            * 応用：「8ルート3」の結果は何が得られると思いますか?
            * 解答：<span style="color:white">（8 かける（ルート３））の結果ですね</span>
            * 応用：「8の3乗根」を求める方法は？
            * 解答：<span style="color:white">3th root of 8　どうやら日本語の表記法は無いようです</span>
            * 「1000円を米ドルに」なんてのも可能


        <div class="jumpmenu">↑</div>

        ### [_](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6%2Fpart1#j2913449 "j2913449") googleなその他のサーヴィスを使い倒す  

        * 学術系検索: http://scholar.google.com   

            学術専門誌、論文、書籍、要約など、さまざまな分野の学術資料を検索。ISIと契約するお金がなくても、論文引用数の概数を知ることは可能。たとえば  


            <pre>
            author:y-nakamura
            </pre>
            y nakamura さん多すぎです。所属である kazusa を追加してみよう。


            <pre>
            author:y-nakamura kazusa
            </pre>
            この人がかずさに来てから10年間の論文のなかで、いちばん引用されてるのはどれだろうか。


        * 応用: BLAST ( basic local alignment search tool ) の初出論文を引用している論文数は膨大なモノだと考えられるが、その数を調べ、また、引用している論文を列挙しなさい

        * 解答: <span style="color:white">basic local alignment search tool で検索し、引用元を確認</span>  

            文献管理ソフトであるBibTeXやEndnoteに取り込むためのファイルダウンロードが可能。see. 検索オプション


        * マップ: http://maps.google.co.jp   

            学会逗留先の土地勘をつかむ。


        * カレンダー: http://www.google.com/calendar   

            ラボやらサークルの予定表共有に便利。iCal との連係も可能。


        ---

        [AJACS1/講習内容](http://MotDB.DBCLS.jp/?AJACS1%2F%B9%D6%BD%AC%C6%E2%CD%C6 "AJACS1/講習内容 (3770d)")へもどる
    </div>
</div>
