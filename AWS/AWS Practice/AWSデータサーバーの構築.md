RDS

フルマネージドなリレーショナルデータベースのサービス
メリット
 - 構築・運用の手間を省きエンジニアが業務に集中できる

webサーバーからRDSに接続

mysqlのインストール
> sudo yum -y install mysql

webサーバーからmysqlへの接続
> mysql -h [エンドポイント] -u [マスター名] -p

終了コマンド
> exit;
