# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

リモートリポジトリ
ネットワーク上のサーバで運用され、プロジェクトの大本のファイル群を保管、管理するリポジトリ。

ローカルリポジトリ
利用者の手元のコンピュータに作成・複製されたリポジトリ。


## プッシュとマージの違いは何でしょうか？

プッシュは、ローカルリポジトリの変更をリモートリポジトリに反映させること。
マージは、他のユーザーが行った変更と、自分の変更を統合させること。


## コミットとプッシュの違い

リポジトリへファイルを追加したり、変更履歴を保存したりする操作を「コミット」と呼ぶ。
 一方の「プッシュ」とは、ローカルで変更した内容をリモートリポジトリ（GitHub）にアップして反映させること。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

履歴を見た際にそのコミットメッセージから「どんな変更を行なったのか」がわかるようなメッセージにすること。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

ローカルでマージするフローは、リモートリポジトリでレビュワーが細かく確認できないまま、リモートリポジトリに送られるのに対して、プルリクエストでマージするフローは、リモートリポジトリー環境内での再現性が担保されやすく、レビュワーもきちんと確認できる違い。



## コンフリクトを起こしてしまった場合、どう対処すべきですか？

コンフリクトが起こっているファイルを開いて、コンフリクト部分を修正する。

