# 鈴木商店 事前課題

## 0. 課題のススメ方
本課題では、項目にそって課題をこなしていくことで、開発に必要な最低限の知識を身に着けるように構成しています。

2 から順を追って課題をこなしてみてください。

## 1. 鈴木商店について知る

- 会社情報 : [Website](https://www.suzukishouten.co.jp/)
- 採用情報 : [Wantedly](https://www.wantedly.com/companies/suzukishouten)

鈴木商店について、上記のサイトより知っていただければと思います。

## 2. 事前課題の内容と
鈴木商店ではいち早く即戦力となれるよう、入社前に業務に則した課題を用意しています。

課題をやり終えることで、スムーズに業務を行えるようになることを目指しています。

この課題では、フロントやサーバーサイドの垣根なく、Webシステムとはどういった感じなのかを体感していただければと思い作成しました。

## 3. GitHub のアカウント登録

## 4.SSHキーを登録する
以下の手順はmac用です。
- terminalを起動する
- SSH鍵を保存するためのフォルダを作成
```
$ cd ~
$ mkdir -m 700 ~/.ssh
```
- SSH鍵を生成する
```
$ ssh-keygen -t rsa
Generating public/private rsa key pair.
Enter file in which to save the key (/Users/username/.ssh/id_rsa):  ← 作成される場所。問題なければEnter。
Enter passphrase (empty for no passphrase):  ← パスフレーズの入力。省略する場合はそのままEnter。
Enter same passphrase again:  ← パスフレーズの再入力。省略した場合はそのままEnter。
```
- 生成された鍵を確認
```
$ ls ~/.ssh/
id_rsa      id_rsa.pub
```
- 鍵ファイルの権限を変更
```
$ chmod 600 ~/.ssh/id_rsa
```
- クリップボードに公開鍵をコピー
```
$ cat ~/.ssh/id_rsa.pub | pbcopy
```
- 
[参考サイト](http://cameong.hatenablog.com/entry/2017/02/17/011429)

## 5. web-development-tutorialをForkする

## 6. ローカルにリポジトリをcloneする

## 7. issueを作成する

## 8. branchを切り替える

## 9. リポジトリに変更を加える

## 10. commitする

## 11. pushする

## 12. masterにマージする (Pull request)

## 13. 課題（具体的な何か）
