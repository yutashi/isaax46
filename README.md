- configを元のを読むようにする
- なのでconfig.jsは削除



# isaax46

## isaaxのインストール
- sudo systemctl stop yorobled
- sudo systemctl disable yorobled
- sudo systemctl status yorobled
- curl -fsSL get.isaax.io | sh -s stable ....


## 今までのデーモンで動かす
- sudo systemctl stop isaax-project
- sudo systemctl stop isaaxd
- sudo systemctl disable isaax-project
- sudo systemctl disable isaaxd
- sudo systemctl status isaax-project
- sudo systemctl status isaaxd

- sudo systemctl enable yorobled
- sudo systemctl start yorobled
- sudo systemctl status yorobled


## isaaxで動かす
- sudo systemctl stop yorobled
- sudo systemctl disable yorobled
- sudo systemctl status yorobled

- sudo systemctl enable isaax-project
- sudo systemctl enable isaaxd




質問
- 一部の端末のみ、アップデートしたい（カナリアテスト）
- 依存ライブラリの更新を行いたい（npmやpip install）、スクリプトpost-updateを使う？実行時のカレントディレクトリは？
- デバイス数が既に６つあるけど....
   


要望
- 複数のプログラムを管理できるように
- isaax.jsonの仕様が不明（ドキュメントは一部の説明しかない）
- 通信量が不安
- ログの見え方が、コンソールに出力しているように見たい


感想
- 管理しているプログラムがエラー終了すると再起動するのは嬉しい
