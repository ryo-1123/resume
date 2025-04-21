# resume

## 個人データ
| Key | Value |
|---|-----|
|Name|Ryo Niida|
|Mail|<adiinoyr.1617@gmail.com>|
|Github|[@ryo-1123](https://github.com/ryo-1123)|

## **Skills | スキル**
| Key | Value |
|---|-----|
|Languages|Python, Shell script, JavaScript, TypeScript, Ruby, Go|
|Frameworks|Django, React, Next|
|Cloud Platforms|AWS, GCP|
|Databases|Mysql, PostgreSQL|
|IaC|Cloudformation, Terraform, Ansible, Serverless Framework, CDKTF(TypeScript)|
|CI/CD|GitHub Actions, Gitlab CI|

## **Certification | 資格**
| Acquisition date | Name |
|---|-----|
|2021/04|AWS Solution Architect Associate|
|2021/09|AWS Developer Associate|
|2022/12|AWS SysOps Administrator Associate|

## **Work Experience Summary | 職歴概要**
- 大学在学中からスタートアップにエンジニアとして参画しサービスの立ち上げしてきた。約3年間サービスを立ち上げては潰してを繰り返し、その中でサービスの設計から開発・運用を経験(2018~2021: 3年間)
- 大学卒業後は受託開発会社に入社し、IoT案件でサーバレスアーキテクチャの設計・開発や自社サービスの改修作業にバックエンド・インフラとして従事(2020/4~2022/3: 2年)
- その後、株式会社エニグモにインフラエンジニアとして入社し、AWS移行や新規機能のアーキテクチャ設計・構築・監視、運用の自動化やDX向上に従事(2022/4~2023/12: 1年8ヶ月)
- また、2023年4月からフィシルコム株式会社にてインフラエンジニアとして副業で参画し、IaCコードのリファクタリング・インフラリソースの最適化に従事。業務範囲を広げたく、バックエンドシステムの開発も少しながら従事(2023/4~現在: 1年10ヶ月)
- 2024年1月からはフリーランスエンジニアとしてフィンテック企業に参画し、PCI DSS 対応・コスト削減・Amazon Linux 2→Amazon Linux 2023 への移行・Fargate への移行・ARM 化や CI/CD の構築・運用効率化などに従事(2024/1~現在)

#### 直近の実績
- PCI DSS対応
  - 要件に合わせた構成の見直し・インフラの各種設定の更新
  - 各種バージョンアップ対応
  - ドキュメント化
- マイクロサービスの新規開発
  - アーキテクチャ設計・構築・監視
- コスト削減
  - Arm化
  - 開発環境の見直し
- DX向上
  - Datadogのアラート整備（不要なアラートの削除を行い、オオカミ少年化していたものを改善）
  - Github Actions, CircleCIのコスト削減・デプロイ速度の改善

## **Work Experience | 職歴**

### **Freelance Engineer (FinTech企業) / January 2024 ~ 現在**
<details> <summary>PCI DSS 対応・コスト削減・AL2→AL2023 への移行・Fargate への移行・ARM 化など</summary>
  
##### **職務内容**
フィンテック企業にて業務委託のSREとして参画。  
セキュリティ対応・コスト最適化・モダナイゼーションを中心に、PCI DSS 対応やコンテナ基盤の移行、CI/CD の構築・運用効率化などインフラ全般を担当

##### **主な実績**
- PCI DSS 対応
  - アプリケーションおよびインフラのセキュリティ要件に合わせた構成の見直し・設定の更新など
- コスト削減
  - リソース使用率の分析と最適化により、AWS 月額コストを削減
- OS 移行（Amazon Linux 2 → Amazon Linux 2023）
  - アプリケーションの互換性調査と検証を実施し、SSM Documentを利用したスムーズな移行を実現
- Fargate への移行・ARM 化
  - 従来の EC2 ベースのコンテナ環境から Fargate へ移行し、運用負荷を軽減
  - ARM アーキテクチャを採用し、パフォーマンスとコスト面での最適化を図る
- CI/CD の構築・運用・効率化
  - パイプラインの構築からデプロイフローの整備など
  - トラブルシューティングとデプロイ速度の改善

##### **使用技術**
- 開発言語: Go, Python, Shell
- インフラ: AWS
- IaC: Terraform
- その他: GitHub Actions, CircleCI

</details>

### **Enigmo Inc.**
Infrastructure Engineer・SRE / April 2022 ~


<details>
<summary>1. AWS移行</summary>

##### **職務内容**
AWSへのシステム移行とクラウドインフラの最適化

##### **規模感、チーム構成、担当した役割**
ソフトウェアエンジニア3人, インフラエンジニア2人
​
##### **主な実績**
- AWS RDS Proxyの検証・導入
  - オンプレミス環境からAWSへの移行を先導する一環として、RDS Proxyの検証と導入を担当
  - パフォーマンスとスケーラビリティの向上を目的に、RDS Proxyを用いてデータベースの効率的な管理と運用を実現
  - 多数のシナリオ下での負荷試験を実施し、システムの耐久性とパフォーマンスを確認・最適化
- 負荷試験の実施
  - AWS環境におけるシステムの性能と耐久性を評価するための負荷試験を計画・実施・評価・報告
- 監視設定
  - Datadogを利用し異常検知とアラート通知を自動化
- ドキュメンテーション
  - 移行プロセスと最適化についてドキュメント化し、チームへのナレッジ共有と今後のリファレンスを充実させた
​
##### **使用技術**
- 開発言語: Ruby, Shell
- クラウドプラットフォーム: AWS(Aurora, EC2（AL2）, Secret Manager, etc..)
- インフラ管理: CloudFormation, Terraform
- その他: Gitlab CI, Datadog
​</details>

<details>
<summary>2. マイクロサービスの新規開発</summary>

##### **職務内容**

マイクロサービスアーキテクチャを基盤とした新規プロジェクトにおいて、インフラエンジニアとしてインフラの設計・構築・運用を担当
システムの安定性、パフォーマンス、開発スピードの最適化を目指した

##### **規模感、チーム構成、担当した役割**
PM1名, バックエンドエンジニア2名, インフラエンジニア1名

##### **主な実績**
- インフラ設計と構築
  - サーバレスアーキテクチャを採用して運用の効率とスケーラビリティを向上
  - イベント駆動型の処理を最適化し、効率的なリソース利用を実現
  - インフラストラクチャアズコード(IaC)を用いて、リソースの管理を自動化し、迅速なデプロイメントと一貫した環境を確保
  - Lambdaとその他のAWSサービスの組み合わせにより、リソースの使用効率を最大化
- 運用と監視
  - Datadogを利用しシステムとアプリケーションの監視設定を最適化
- 開発者へのナレッジトランスファー
  - 開発チームへのインフラ運用のナレッジトランスファーを実施。ドキュメンテーションとワークショップを通じて、リソースの追加や修正を各自が行える体制を確立
​
##### **使用技術**
- 開発言語: Python
- クラウドプラットフォーム: AWS(Lambda, RDS, S3, etc..)
- インフラ管理: CloudFormation, SAM, Datadog
- その他: Gitlab CI
</details>


<details>
<summary>3. その他運用/保守作業</summary>

##### **職務内容**
インフラの運用自動化・最適化や開発・運用プロセスの最適化、および開発者体験の向上に取り組む
##### **主な実績**
- インフラの運用自動化・最適化
  - 手動で作成されたDatadogモニターのIaC化(Terraform)
  - 複数のAWSアカウントの監査ログ(CloudTrailログ)の分析基盤構築
  - ロールの作成・修正/オンプレ・EC2への適用(Ansible)
  - 複数のAWSアカウントのセキュリティスコアのSlack通知(Python)
  - Auroraのポイントインタイムリカバリ実施・IaCへの取り込みの半自動化(Ruby, Shell)
  - GKEアップグレード対応(Terraform)
  - AWSリソースの暗号化・クロスアカウント管理のバックアップ基盤構築
- 開発者体験の向上
  - ローカル開発環境のセットアップと管理の効率化を目指して、ツールの統一化・コンテナ技術と自動化スクリプトを導入
  - Gitlab CIの実行コスト削減
  - 単純作業の自動化
  - デプロイツールの改善(Ruby, Shell, Docker)
##### **使用技術**
- 開発言語: Shell, Ruby, Python
- クラウドプラットフォーム: AWS(Aurora, Lambda, CloudTrail, SecurityHub, etc..), GCP(GKE)
- IaC: Cloudformation, Terraform, Ansible
- その他: Gitlab CI
</details>

### **HANDS LAB Inc.**
Backend・Infrastructure Engineer / April 2020 ~ March 2022

<details>
<summary>1. IoT案件の受託開発</summary>

##### **職務内容**
- タクシーに搭載されるメーターに対して、モバイル回線を利用してリアルタイムでデータ送受信を行うIoTシステムの開発と構築
  - https://www.hands-lab.com/contents/c12016/

##### **主な実績**
- API・非同期処理の開発
  - AWS Lambda (Python)を使用した、非同期処理やデータ送受信のAPIの開発
  - タクシーメーターからのデータを効率的に処理・管理し、リアルタイムでのデータアクセスを可能にした
- CI/CDの修正
  - CI/CDパイプラインの改善を行い、開発・デプロイの効率化と品質の向上を実現
  - 自動テストを最適化し、リリースの速度と信頼性を向上
  - https://www.hands-lab.com/tech/t12239/ (CI/CD修正について執筆)

##### **使用技術**
- 開発言語: Python
- インフラ/クラウド: AWS (Lambda, WAF, DynamoDB, RDS, etc.)
- IaC: Cloudformation, Serverless Framework
- その他: IoT, CI/CD

</details>

<details>
<summary>2. 自社サービス開発</summary>

##### **職務内容**
小売や飲食の店舗が利用する画像共有サービスのバックエンドを近代化・改修し、APIドキュメンテーションを整備
サービスのパフォーマンスと利便性を向上させる目的で実施

##### **主な実績**
- ローカルのテストコード作成
  - バックエンドの改修に伴い、新たにテストコードを設計・作成。機能の正確性と安定性を確保した
- CI/CDの構築
  - CI/CDパイプラインを構築・最適化し、開発フローの効率化と自動化を実現。迅速なリリースと品質保持に貢献
- API仕様書の作成
  - Swaggerを使用してAPI仕様書を作成・更新。開発者と利用者に向けて正確なAPI情報の提供を強化

##### **使用技術**
- 開発言語: Python
- インフラ/クラウド: AWS (CodePipeline, Lambda, etc..)
- IaC: Cloudformation, Serverless Framework
- その他: IoT, CI/CD
</details>

### **Ficilcom Inc.(副業) April 2023 ~ 現在**
Infrastructure・Backend Engineer

<details>
<summary>1. API開発 / インフラリソースの作成・IaCリファクタリング</summary>

##### **職務内容**
APIデータ連携バックエンド開発・​インフラリソース構築・IaCリファクタリング

##### **主な実績**
- IaCコードのリファクタリング
  - インフラリソースの効率的な構築とIaCコードの最適化により、クライアントのシステム運用コストを削減
- 外部API連携バックエンド開発
  - Go言語を使用して、外部APIからデータを効率的に取得、整形、保存するバックエンドシステムを開発

##### **使用技術**
- 開発言語: Go
- インフラ: AWS(ECS, Aurora Serverless, etc..)
- IaC: CDKTF(TypeScript)
</details>

## **Activities | 課外活動**
### **Webサービスの新規開発 サントネール株式会社  April 2022 ~ 現在**

<details>
<summary>新規サービス開発</summary>

##### **職務内容**
- 知人と共に立ち上げたサービスの開発リーダーとして、スマホ向けサービスの設計から開発、テスト、リリースまでを一貫して担当（開発継続中
  - https://qirnara.com/

##### **主な実績**
- サービスの全体設計と機能要件の定義
- 作業効率の向上
  - アジャイル開発メソッドを採用し、迅速かつ効率的にプロダクトを開発
  - Linearの導入
    - チームメンバー間での透明性を高め、作業の優先順位を効果的に管理
    - プロジェクト管理とタスクの効率化を実現
- フロントエンド開発
  - MUIを用いて、コンポーネントベースでの効率的なフロントエンド開発を行い、開発速度と品質を向上
  - カスタマイズ可能なテーマとコンポーネントを活用し、ユーザーインターフェースを最適化
- バックエンド開発
  - 要件定義に応じたカスタムAPIの作成
##### **使用技術**
- 開発言語: React, Wordpress, PHP
- インフラ: AWS(ECS, App Runner, RDS, etc..)
</details>

### **Webサービスの新規開発  Relye Inc, February 2018 ~  September 2021**

<details>
<summary>新規サービス開発</summary>

##### **職務内容**
- 知人と共に立ち上げたスタートアップで、新たな相談サービスの開発リーダーとして、サービスの設計から開発、テスト、リリースまでを一貫して担当
  - https://prtimes.jp/main/html/rd/p/000000006.000054122.html
- 複数サービスリリース後、会社は休眠

##### **主な実績**
- サービス設計
  - ビジネスニーズとユーザー要求をもとに、サービスの全体設計と機能要件の定義
- 開発管理
  - アジャイル開発メソッドを採用し、迅速かつ効率的にプロダクトを開発
- コーディング
  - Amplifyを使用し、サービスの主要部分のコーディングを担当
- サービスリリース
  - サービスのリリースを成功させ、初期ユーザーからのフィードバックを基に改善を進めた

##### **使用技術**
- 開発言語: React
- インフラ: AWS(Amplify)
</details>
