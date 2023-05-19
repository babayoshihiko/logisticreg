こちらは、「Saturday Morning: R によるロジスティック回帰」です。


# 共同著者へ

主に作業するファイルは、

* _bookdown.yml 本を構成している Rmd ファイルを指定
* .Rmd 各章のファイル
* book.bib 引用文献

## R についての注記

作業を始める前に、RStudio の Git タブから PULL をしてください。

作業が終わったら、Build から Build Book してください。gitbook 形式と epub_book 形式をビルドしてください。その後、Git タブから Commit し、PUSH してください。

pdf_book_ja 形式は、LaTeX をインストールする必要がありますが、ハードディスクをかなり使います。インストールには数時間かかります。

索引は、以下のように書きます。\\index を使い、波括弧の中に、読みをひらがなで書き、アットマーク記号後に索引したい単語を書きます。

本章では、あらたにロジスティック回帰 (logistic regression)\index{ろじすてぃっくかいき@ロジスティック回帰}