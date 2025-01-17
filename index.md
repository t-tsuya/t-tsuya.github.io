---
layout: default
title: "top page"  # トップページのタイトルとして表示されます
---

# Welcome to t-tsuya's blog from Japan

このサイトでは、日本文化にまつわる様々な話題や、
確率論に関するエッセイを公開していきます。

## サイトのコンセプト

- **日本文化**  


- **確率論**  


## 最新の記事

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})**（{{ post.category }}） - *{{ post.date | date: "%Y-%m-%d" }}*

  ---

{% endfor %}

## 今後の予定



## サイト管理情報

- このサイトは [GitHub Pages](https://pages.github.com/) と [Jekyll](https://jekyllrb.com/) で構築しています。
- ご意見・ご感想などありましたら、ぜひ [GitHub Issues](https://github.com/t-tsuya/t-tsuya.github.io/issues) やSNSでお寄せください。

---

日本の文化に触れたい方、あるいは確率論や統計に興味がある方に楽しんでもらえるよう、今後も少しずつ記事を増やしていきます。  
ぜひお付き合いください。
