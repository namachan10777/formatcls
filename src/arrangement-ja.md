- main.rs : 入出力管理，JSONデータ扱うのはここだけ
  - header.rs : パッケージ部分の作成
  - module.rs : モジュール作成用巻関数提供
  - default.rs : デフォルトの値を作成する関数を提供
  - body.rs : 中身作成、データ提供
    - commands.rs : コマンド作成
    - font.rs : フォント関係
    - doc.rs : ドキュメント関数
    - page.rs : ページサイズ関係
    - func.rs : デフォルト関数作成