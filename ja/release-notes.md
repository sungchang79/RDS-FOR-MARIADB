## Database > RDS for MariaDB > リリースノート

### 2022. 03. 15.

#### 機能追加

* **DB Configuration**に変数使用機能を導入

#### バグ修正

* 特定条件でモニタリングデータが収集されない現象を修正
* フェイルオーバーが発生したインスタンスの自動バックアップが削除されない現象を修正
* 作成に失敗した自動バックアップが期限切れになったときに削除されない現象を修正
* MySQLに登録されたユーザーが多すぎる場合に、復元に失敗する現象を修正
* access ruleを修正してもバックアップ設定変更イベントが記録される現象を修正

### 2022. 01. 11.

### 機能追加

* MariaDBで実行中のプロセスリストおよびInnoDB状態を確認することができる機能の追加

### 機能改善

* WebコンソールでDBスキーマを作成する時、入力可能な名前の最小文字数をMySQLと同じに修正

### 2021.12.14

#### 新商品発売

- TOAST Relational Database Service (RDS)は、Relational Databaseをクラウド環境で提供する商品です。
- 複雑な設定をしなくても、Relational Databaseを使うことができます。
- MariaDB 10.3.30バージョンを提供します。
