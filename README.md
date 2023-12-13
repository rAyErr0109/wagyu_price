# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリはネット上のクラウドやGitHubにある専用サーバに配置された皆さんで共有するリポジトリ。
- ローカルリポジトリは私や皆さんの個々のパソコンにあるリポジトリ。
- また、リポジトリはソースコードやディレクトリ構造の保管場所。


## プッシュとマージの違いは何でしょうか？
- プッシュはローカルリポジトリからリモートリポジトリにデータを送り更新すること。
- マージは同じリポジトリ内にあるブランチ内でデータを送り更新すること。


## コミットとプッシュの違い
- コミットはデータの変更を保存すること。
- プッシュはそのデータ変更をリモートリポジトリに送り更新すること。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 変更内容を的確に書く。
- プレフィックスという接頭辞をつける。
- 例に「add:」や「change:」など


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルはターミナル内でマージをする。
- ローカルのメリットは履歴を確実に詳細を残せること。
- ローカルのデメリットはコンフリクトが起こりやすくなる。
- プルリクエストはギットハブなどでマージの申請をしマージをして頂く。
- プルリクエストのメリットはコードのバグが事前に見つけられることです。
- プルリクエストのデメリットはレビューに時間がかかる。



## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 先マージした内容を取り込む。
- 後にマージした内容を取り込む。
- 両方の内容を取り込む。
- 状況によってその内容にあった方法で取り込む。
- 変更を加えた本人と相手の方と話し合いながら進めていく。