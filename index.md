<link href="https://use.fontawesome.com/releases/v5.6.1/css/all.css" rel="stylesheet">
<style>
#page_top {
            width: 50px;
            height: 50px;
            position: fixed;
            right: 0;
            bottom: -50px;
            background: #6600cc;
            opacity: 0.6;
            border-radius: 50%;
        }

            #page_top a {
                position: relative;
                display: block;
                width: 50px;
                height: 50px;
                text-decoration: none;
            }

                #page_top a::before {
                    font-family: 'Font Awesome 5 Free';
                    font-weight: 900;
                    content: '\f102';
                    font-size: 25px;
                    color: #fff;
                    position: absolute;
                    width: 25px;
                    height: 25px;
                    top: -5px;
                    bottom: 0;
                    right: 0;
                    left: 0;
                    margin: auto;
                    text-align: center;
                }

                #page_top a:hover {
                    background: #9977ba;
                    opacity: 0.6;
                    border-radius: 50%;
                }
</style>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script>
jQuery(function () {
            var appear = false, pagetop = $('#page_top');
            $(window).scroll(function () {
                if ($(this).scrollTop() > 100) {
                    if (appear == false) {
                        appear = true;
                        pagetop.stop().animate({ 'bottom': '50px' }, 200);
                    }
                } else {
                    if (appear) {
                        appear = false;
                        pagetop.stop().animate({ 'bottom': '-50px' }, 200);
                    }
                }
            });
            pagetop.click(function () {
                $('body, html').animate({ scrollTop: 0 }, 450);
                return false;
            });
        });

</script>

<div id="page_top"><a href="#"></a></div>

# 筑波大学を便利にする会
筑波大学を便利にする会(MIT: Make It Tsukuba)とは、筑波大学の学生および教職員の生活や業務をより便利にするアプリケーションの開発・運営および保守を主目的に活動する学生団体です。

## 活動内容
### KdBもどき
KdBを代替するサービスです。高速な検索や、お気に入り機能、履修の仮組みなどの機能があります。

[![](https://i.imgur.com/IYkWCJf.png)](https://i.imgur.com/IYkWCJf.png)

- Alternative KdB: <a href="https://make-it-tsukuba.github.io/alternative-tsukuba-kdb/" target="_blank" rel="noopener">https://make-it-tsukuba.github.io/alternative-tsukuba-kdb/</a>
- GitHub リポジトリ: <a href="https://github.com/Make-IT-TSUKUBA/alternative-tsukuba-kdb/" target="_blank" rel="noopener">https://github.com/Make-IT-TSUKUBA/alternative-tsukuba-kdb</a>
- ネットニュースで紹介されました: <a href="https://news.yahoo.co.jp/articles/5d85475cff6b4e2a7b19bed6d822b2f26ad1235a" target="_blank" rel="noopener">リンクはこちら</a>

### 移行判定要件ツール（？）
### アヒルボート
松見池に浮かんでいるアヒルボート(通称: 博士号)にWebサーバーを載せて、保守管理をしています。

- ページのURLとか

### 定期MTG
- 全体ミーティング:毎週水曜日 18:30～
- プロジェクトごとのミーティング（週に1回程度）
- 成果報告会（月に1回）

## お知らせ

<a class="twitter-timeline" data-lang="ja" data-width="400" data-height="600" data-dnt="true" href="https://twitter.com/MakeITTSUKUBA?ref_src=twsrc%5Etfw">Tweets by MakeITTSUKUBA</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## メンバー

### 内訳

- ○学類 30%
- ○学類 20%

### 紹介

- ふろど
    - リーダー

## 参加方法
連絡先からサークルのツイッターアカウントにDMをするか、代表のメールアドレスにメールして参加したい旨を連絡するとサークルのSlackへの招待がされます。

## 連絡先

- サークルのツイッターアカウント
    - <a href="https://twitter.com/MakeITTSUKUBA" target="_blank" rel="noopener">@MakeITTSUKUBA</a>
- 代表および責任者のメールアドレス
    - 代表: [s2111951@coins.tsukuba.ac.jp](mailto:s2111951@coins.tsukuba.ac.jp)

