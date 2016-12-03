+++
title = "投稿の仕方"
date = "2016-12-03T21:58:53+09:00"
categories = ["はじめに"]
tags = ["流山オープンデータラボ"]
thumbnail = "/images/github_top.png"

+++


## まず最初にGitHubのアカウントを作成します

https://github.com

{{< img src="/images/github_top.png" title="GitHubトップページ">}}

1. ユーザー名（半角英数）
2. メールアドレス
3. パスワード

を入力し「Sign up for GitHub」を押すと、こんな画面に遷移します↓

{{< img src="/images/github_login.png" title="アカウント登録完了画面">}}

「Unlimited public repositories for free.」を選んで「Continue」ボタンを押します。

{{< img src="/images/github_login_step2.png" title="アカウント登録時アンケート">}}

いくつかアンケートが出てくるので、答えます。私の場合は

- Totally new to programming
- Other > Hobby
- I'm a hobbyist

と答えておきました。終わったら「Submit」を押します。

{{< img src="/images/github_login_complete.png" title="アカウント登録完了">}}

もうすぐ登録完了です。「Start a project」を押します。

{{< img src="/images/github_verify_email.png" title="メールアドレスの確認">}}

メールアドレスを確認してねという画面が出るので、先ほど登録したメールアドレス宛に届いているメールを開封して「Verify email address」のリンクを開きましょう。

{{< img src="/images/github_relogin.png" title="GitHubにサインインします">}}

GitHubのログイン画面が表示されますので、先ほど入力したユーザー名かメールアドレス＆パスワードを使ってサインインしましょう。これでメールアドレスの確認が完了しました。これでアカウントの作成はおしまいです。お疲れ様でした。

# 流山オープンデータラボ

GitHubにサインインした状態で、このページに移動します。

https://github.com/nlabo/opendata

こんなページですね

{{< img src="/images/github_nlabo_opendata.png" title="流山オープンデータラボのGitHub">}}

## 記事を修正する

表示されているディレクトリのリストから、記事の入っているディレクトリに移動します。
記事は「content」の中に入っています。今回は「流山市について」のページを編集する場合について見ていきます。
「content」＞「posts」の中にある「nagareyamacity.md」を開きます。

{{< img src="/images/github_edit.png" title="記事を開いたところ">}}

この記事を修正してみます。記事の右上の方に、鉛筆マークの「Edit this file」ボタンがあるので押します。

{{< img src="/images/github_edit_button.png" title="編集ボタン">}}

編集画面です

{{< img src="/images/github_edit_editor.png" title="編集画面">}}

なんか色々青いところで難しいことを言われますが、今は気にしなくて大丈夫です。いい感じに文字を追加、削除、変更してみてください。
終わったら

{{< img src="/images/github_edit_complete.png" title="編集完了">}}

こんな感じに、どんなことをしたのか簡単にメッセージを記入して、「Propose file change」を押します。簡単ですね。
するとこんなページが表示されます。

{{< img src="/images/github_edit_check.png" title="編集内容確認">}}

編集した行に色がついて見えます。行単位での確認になりますが、編集した文章の部分が濃い色で表示されるので、修正前後の確認をしてみてください。赤い行は削除した行。緑色が追加した行です。ほんの一部だけ編集していたとしても、基本的に行単位での変更となるため、一度その行を丸ごと削除して、その後緑色の行を追加したという扱いになっています。

## プルリクエスト

確認し終えたら、上の方にある緑色の「Create pull request」ボタンを押します。すると、メッセージ画面がもう一度出てくるので、必要があれば修正し、「Create pull request」を押します。

{{< img src="/images/github_pullrequest.png" title="プルリクエスト">}}

しばらくすると、サーバー側でのチェックが終わります。同時に他の人が同じ場所を編集しているなどある場合はここでエラー（コンフリクト）になったりしますが、あんまりないと思ってて大丈夫です。This branch has no conflicts with the base branchとなっていれば修正完了＆公開申請完了です。
{{< img src="/images/github_pullreq2.png" title="プルリクエスト後の画面">}}

プルリクエストを取り下げたいときは、この画面の一番下「Close pull request」ボタンを押せばOKです。
この時点で管理者に通知が届き、確認・承認後サイトに反映されます。

まずはこんな感じです！
