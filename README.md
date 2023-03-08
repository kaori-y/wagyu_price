# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

* リモートリポジトリは複数人で共有するためのリポジトリで、ローカルリポジトリは開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ

## プッシュとマージの違いは何でしょうか？

* プッシュはリモートリポジトリに変更内容を反映することで、マージは別ブランチで編集した内容を対象のブランチに反映すること

## コミットとプッシュの違い

* コミットはローカルリポジトリに変更を反映することで、プッシュはリモートリポジトリに変更を反映すること


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

* 変更した内容を一見でわかるようにする


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

* プルリクエストを作成し、コードレビューをしてからマージすることで、事前にバグを発見する事ができる
* ローカルでマージするフローではバグがそのまま本番環境にアップされてしまう可能性がありバグに気づけない可能性がある

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

1. 先にマージされた変更内容を取り込む
2. 後にマージしようとしている変更内容を取り込む
3. どちらの変更内容も取り込む

  どれにせよそのソースコードを書いた人と相談しながら作業を進める