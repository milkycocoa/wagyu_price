# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リポジトリ：ファイルやディレクトリの状態を記録する場所
  - リモートリポジトリ:ネット上に配置して複数人で共有するためのリポジトリ
  - ローカルリポジトリ:開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ

## プッシュとマージの違いは何でしょうか？
- プッシュ：ローカルリポジトリからリモートリポジトリへ変更を反映させること
- マージ：ローカルリポジトリからローカルリポジトリへ変更を反映させること

## コミットとプッシュの違い
- コミット：変更内容の記録
- プッシュ：リモートリポジトリへ反映する

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 一目で変更内容がわかるもの
  - プレフィックス:単語や数字の前につけることで、その言葉や数値に新たな情報や意味を与えるもの
  - プレフィックスの例: ○○という機能を追加、○○で発生するバグを修正など

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- 変更を反映させる前にコードレビューして事前にバグを発見する事ができるかできないか

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 自分以外の人が書いたソースコードの内容を把握する必要があるため、少しでも意図が読み取れない処理とぶつかってしまった場合は、そのソースコードを書いた人と相談しながら作業を進める