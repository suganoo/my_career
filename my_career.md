# 自己PR
## 業務歴
※新しいものから
- **2017/04 ~ (現職) Cloudera Hadoop運用**
  - 業務委託にて従事(株式会社リツアンSTC所属)
  - DSP広告企業にて常駐業務
  - 配信ログをHadoopにて管理(オンプレミス環境)、ログサイズ約2PB
  - 業務内容
    - Hadoopクラスター運用関連作業
      - Cloudera Hadoopバージョンアップ作業、それに伴うジョブ等の全面移行
      - クラスター移行に伴うクラスター間同期システムの構築(distcp後不要なファイルの同期)
      - 定期的なHadoopの状況レポート作成、および状況共有MTGの開催
      - レポートデータのためImpalaクエリログ、Hadoopの各DBサイズ、レコード件数を定期的にElasticsearchにイ  ンポートするシステムの構築、Kibanaによる描画構築(Python)
      - Cloudera Hadoopの機能調査、不具合調査、Cloudera サポートへの質問対応
      - Hadoopクラスターの設定チューニング
      - ハードウエア障害、クラスター障害、ディスク障害など全般的な障害の調査・対応
    - 各種調査、または業務ツール構築・運用関連作業
      - 配信ログの取り込みツールの作成(Python, Go)
      - Erasure Coding、Zstandard機能調査
      - COMPUTE STATS機能調査、および障害対応
      - Impala、Hiveのパーティション動作調査
      - HadoopのメタデータDBの調査
      - TestDFSIO、terasort、teragenによるHadoopのベンチマーク調査
      - Namenodeのメタデータファイルの中身、およびバックアップ復旧調査
      - AWSサービスで出力されるログの取り込みシステムの構築(SNS, SQS, EC2, Python, Ansible)
      - HDFSに保管されたログファイル数の圧縮システムの構築(Go)
    - ジョブスケジューラー関連の調査および運用
      - airflow、luigi、Jenkins等のジョブスケジューラーの選定調査
      - DockerによるJenkinsの構築、ジョブ構築
      - Jenkinsジョブの結果をDB、およびJIRAに取り込み、ジョブ実行の分析が可能となるシステムの構築(Go)
      - チーム内で使うジョブ標準の策定
      - チケット運用の推進
  - 使用したプロダクトなど
    - (AWS)EC2, S3, SQS, SNS
    - Shell, Python, Go
    - Hadoopディストリビューション：Cloudera
    - Hadoop, HDFS, Spark, Hive, Impala, beeline
    - CentOS, Jenkins, Confluence, Ansible, Docker
  - その他アピール事項
    - 2019年3月 Hadoop/Spark Conference Japan 2019 のLTにて発表
      - https://www.slideshare.net/suganoo1/2impalahadoop
- **2012/03 ~ 2017/03 (5年) 検索システム構築/運用サポート業務**
  - 業務委託にて従事(株式会社デジタル・インフォメーション・テクノロジー所属)
  - 某人材系大手企業にて常駐業務
  - 企業内で共通して使用する検索システムの管理
  - 業務内容
    - Solr
      - Solrの機能調査、機能試験、機能拡張-バージョンアップ時の検証
      - 各部署からのメール質問対応
      - 検索システムの負荷性能試験、JVMのチューニング、GC機能調査
      - 性能検証時にPythonにてログのパースをし、Elasticsearch + Kibanaによる描画ツールシステムの構築
      - 検索性能の向上調査、およびアドバイス業務
      - 自然言語分析の勉強会開催
    - Elasticsearch
      - PKG化されている検索システムの構築・メンテナンス
      - 機能拡張-バージョンアップ時の検証
      - 描画ツールによるログ解析
      - 検索システムの負荷性能試験、JVMのチューニング
      - 検索システムの監視
      - 検索ログをFluentdにて取り込み監視
    - MWの導入支援
      - redis, rabbitMQの機能調査
      - 単体試験自動化(rspec)
  - 使用したプロダクトなど
    - 検索エンジン: Solr, Elasticsearch
    - MW: redis, rabbitMQ
    - デプロイ: Chef, Ansible
    - 監視: Zabbix
    - (AWS)EC2, S3
    - 仮想環境ツール: Vagrant, Docker
    - その他使用ツール: Jmeter, Jenkins, td-agent, norikra, rspec
- **2010/02 ~ 2012/02 (2年) カーナビソフトウエアの仕様策定**
  - 業務委託にて従事(以降すべて旧株式会社ソフトウエア興業所属)
  - 某大手メーカー企業にて常駐業務
  - 大手自動車への納入用に、カーナビハードウエアのメーカーにて従事。
  - EUカーナビソフトウエアの仕様調査。
  - 主な業務
    - カーナビソフトウエアの機能調査
    - オランダの企業と使用調査のため電話会議
    - EU企業来日時の通訳
    - 各部門による設計図の確認依頼
    - サンプル品の送付手続き
- **2009/07 ~ 2010/01 (6か月) 電気回路図のドローイングソフトの開発**
  - 電機メーカー向けに通電イメージ、回路図をWindowsアプリケーションで描くソフトの開発。
  - 使用言語: C#
  - 担当業務: 基本設計、機能設計、製造、単体試験
- **2007/06 ~ 2009/06 (2年) 3G携帯端末評価**
  - 国内・海外メーカーの携帯端末の評価検証(ストレージ機能)。
  - 海外メーカー不具合のレポートを英語で作成。
- **2006/10 ~ 2007/05 (7か月) 無線LANアプリのWindowsアプリ開発**
  - 無線LANの電波強度を携帯端末に表示するアプリの開発。
  - C++にて画面設計、および開発を担当。

## その他自己紹介
### SNS
- Qiita
  - https://qiita.com/suganoooo
- blog
  - https://blog.suganoo.net/

### 語学
- 英語 (5年以上前だがTOEIC820、業務にて英語で電話会議、メールなど経験あり)

### 資格等
- 応用情報技術者試験
- 統計検定2級

### その他アピール事項
- Go のロガーを作りました。
  - https://github.com/suganoo/gologger
- アルゴリズム学習中
  - https://github.com/suganoo/algorithm_and_data_structure_for_procon
- UdemyにてgRPC学習
  - https://qiita.com/suganoooo/items/8bdf43542eb4ceb80044
- UdemyにてKafka学習中
  - https://www.udemy.com/course/apache-kafka/
