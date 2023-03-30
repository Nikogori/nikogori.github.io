# GitHub Pagesのテーマを変更する

GitHub Pagesでテーマを変更しようとしたところ、ちょっと詰まったので備忘録です。

（2023年3月時点の情報です）

## やりたいこと

最低限の労力で、書いたものをネットに公開したい。

## 聞いていた話

1. GitHubでリポジトリを作る。
2. MarkdownファイルをPushする。
3. ブラウザで当該リポジトリのページを開く。
4. Choose a themeのボタンをクリックして、テーマを適用する。
5. テーマが適用された状態で、各ページがビルドされる。

これなら簡単そうだな、ということでGitHub Pagesを選んだ。  
（Htmlファイルをそのまま置くタイプのサイトは作ったことがあった）

## 現実

Choose a themeのボタンがなくなってる！

調べてみたところ、わりと最近（2022年）に廃止されたらしい。

<https://github.com/orgs/community/discussions/33924>

## やったこと

**_config.yml**を作成する。

以下のように書いて保存する。

```yaml
theme: jekyll-theme-modernist
```

ほかのMarkdownファイルと一緒にPushする。  
（適用されるまで若干のタイムラグがあります）

選択可能なテーマは以下のリストを参照してください。

<https://pages.github.com/themes/>

[トップに戻る](/)