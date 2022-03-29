# OJ Diary

続くかどうか分からないですが、日記を書きます。

## セットアップのメモ

1. hugoを入れる

```
$ brew install hugo
$ hugo version
```

2. hugoでプロジェクトを新規作成

```
$ hugo new site oj-diary
```

3. themeを導入する。

```
$ git submodule add https://github.com/EmielH/tale-hugo.git themes/tale
```

素晴らしいテーマをありがとうございます。  
https://themes.gohugo.io/themes/tale-hugo/

4. `config.toml` を変更する

```
- languageCode = 'en-us'
+ languageCode = 'ja-jp'

+ theme = 'tale'
```

5. 動作確認

```
hugo server -t tale
```
