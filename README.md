# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

* リポジトリ
作成したファイルやディレクトリの状態を保存しておくところ。
* リモートリポジトリ
web上に公開され、すべての人、共同作業する人が見ることができる。
* ローカルリポジトリ
自分のpc上にあり、自分しか見ることができない。

## プッシュとマージの違いは何でしょうか？

* プッシュ
変更や修正を加えたブランチをローカルリポジトリからリモートリポジトリに保存すること。
* マージ
 同リポジトリ内で、現在作業中のブランチに、修正変更の履歴を取り込むこと。

## コミットとプッシュの違い

* コミット
修正や変更内容をリポジトリに保存すること。
* プッシュ
コミットしたデータをリモートのリポジトリに保存すること。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

* 後で見た時や、他人に見られたときに管理しやすいようにどのような内容を修正、編集したのかがわかるようにメッセージを残す。
* プレフィックスというコミットメッセージの先頭にfixやaddなどコミットする内容の情報を簡単に記すという方法がある。
(例)
  * fix(バグの修正)
  * add(ちょっとしたファイルやコードの追加)
  * remove(ファイルなどの削除)　　etc...


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

* ローカル内でのマージは自分にしか見ることができない。プルリクエストでのマージは、一度リモートリポジトリにプッシュした後マージをするので、他人が介入することができる。

* ローカルでのマージは、ほかの人が介入することができないのでミスやバグに気づかないことがある。プルリクエストで間にコードレビューなどを挟むことで、より安全にマージすることができる。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？

* 状況やほかの人の変更内容次第で、下記の３パターンから選ぶ。
1. 先にマージされた内容を取り込む
2. 後にマージされた内容を取り込む
3. どちらも取り込む

    きちんとコミュニケーションをとってチームなどとも相談しながら進める。