# WP-CLI で post create するテキストファイル

WordPress の投稿ページの CSS をさくっと作成したい時、さくっと確認をしたい時これを使います。

## こちらをお借りしました。

コンテンツエリアのマークアップで必要なHTMLの要素。コピペすると使える。 - Shinichi Nishikawa's
<http://nskw-style.com/content-area-markup>

WP Content Area Markup
<https://gist.github.com/ShinichiNishikawa/01616298fbcf6ec3426a>

## Usage

```
$ curl -OL https://raw.githubusercontent.com/shimakyohsuke/wp_post_create/master/content-area-markup.txt
$ wp post create content-area-markup.txt --post_title='Nishikawa さんが作成したテストデータ' --post_status=publish
```
