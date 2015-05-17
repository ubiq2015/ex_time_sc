#　ユビキタス情報システム特論
### Windows

- Step.1 [GitHub for Windows](https://windows.github.com/)をダウンロード(初めての場合)

  インストール後、アプリケーションを起動して登録GitHubアカウントでログイン

- Step.2 リポジトリをクローン(初めての場合)
　
  
  [演習用ページ](https://github.com/MinoruNakazawa/ubiq_ex) 　を開く

  ダウンロード先を指定してクローン
  
  ブランチを作成 
  

  ```
  $ git clone https://github.com/ubiq2015/ex_time_sc.git
  $ cd ex_time_sc
  $ git checkout -b <自分の名前(小文字英字)>
  $ mkdir <自分の名前(小文字英字)>
  $ cd <自分の名前(小文字英字)>
  ```


  jikanwari.mdを自分用のディレクトリにコピーしてファイル名を変更(フォーマット例：jikanwari.md)して使用してください。

- Step.3 リモートリポジトリにアップロード

  __注意!! 現在のブランチがmasterでないか確認！__
  `$ git branch`

  ```
  $ git add .
  $ git commit -m "add my Schedule"
  $ git push origin <自分の名前(小文字英字)>
  ```

- Step.4 [GitHub](https://github.com/MinoruNakazawa/ubiq_ex)上での操作

  Compare & pull requestをクリック

  プルリクエストのコメントを書く(例：スケジュールの追加)

  自分のブランチからmasterブランチに対してPull requestの作成

  __注意!! Pull requestをマージした後に自分用のリモートブランチは消さない！__