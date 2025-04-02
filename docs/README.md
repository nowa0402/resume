# 職務経歴書

<!-- <img src="./profile.jpg" align="right" style="border-radius: 50%; width: 140px; height:140px" >

<br/>

<span style="font-size: 1.4em">和山 直樹（Wayama Naoki）</span>

<br/> -->

## 基本情報

- **氏名**: 和山 直樹（わやま なおき）
- **GitHub**: [github.com/nowa0402](https://github.com/nowa0402)
- **技術ブログ (Zenn)**: [zenn.dev/nowa0402](https://zenn.dev/nowa0402)
- **note**: [note.com/nowa0402](https://note.com/nowa0402)
- **メール**: n.wayama0402@gmail.com

## 職務要約

2015年、新卒で東日本旅客鉄道株式会社に入社。信号設備や運行管理システムの工事監督・保守運用・設計に従事し、RPAやPowerAppsを活用した業務改善も担当。  
2022年、株式会社アーセスに入社。気象プロダクトを活用した水防活動報告書作成システムや気象データAPI、認証認可APIのバックエンド開発を担当。  
2023年、株式会社Specteeに入社。防災系プロダクトのダッシュボード機能に関わるバックエンド開発を担当し、配信機能の拡充やSNSのAPI仕様変更対応を実施。現在に至る。

## 経験・スキルセット

### 経験

- 気象データの加工・表示に関わるバックエンド開発
- SNSデータの収集・加工に関わるバックエンド開発
- Web APIの設計・実装
- スクラムによるアジャイル開発（開発メンバー・スクラムマスター経験あり）
- TDD/ペアプロ/モブプロの導入と実践。
- 後輩エンジニアの育成・メンタリング
- テックブログの立ち上げ・運営
- チームメンバーとの輪読会・勉強会の開催

### スキルセット

| カテゴリ | 技術スタック（経験年数） |
| --- | --- |
| **プログラミング言語** | Python (3年), TypeScript（2年）, Rust（5ヶ月）, JavaScript（2年）, Perl（1年6ヶ月）, C#（1年）, SQL（1年6ヶ月） |
| **フレームワーク** | FastAPI（1年6ヶ月）, Node.js (2年), Express（1年）, Vue.js（3ヶ月） |
| **データベース** | PostgreSQL（1年3ヶ月）, MySQL（6ヶ月）、SQLAlchemy（1年）, Alembic（1年） |
| **インフラ** | AWS （2年）(Lambda, ECS, DynamoDB, RDS, S3, API Gateway, Secrets Manager, SSM, Firehose), AWS CDK(1年6ヶ月), AWS SAM, Docker, LocalStack |
| **CI/CD** | GitHub Actions（1年6ヶ月） |
| **Linter / Formatter** | Ruff, mypy, Biome, Prettier |
| **開発ツール** | Rye, uv, volta, turborepo |
| **ソース管理** | GitHub, Backlog |
| **プロジェクト管理** | Notion, Backlog |
| **コミュニケーション** | Slack, Miro |
| **ドキュメント管理** | Notion, kintone |

## 職務履歴

| 所属        | 時期              | 役割 |
| ---------- | ----------------- | ----------------------------- |
| 株式会社Spectee | 2023/11 -         | Application Engineer(Member,ScrumMaster) |
| 株式会社アーセス | 2022/01 - 2023/10        | Application Engineer(Member) |
| 東日本旅客鉄道株式会社 | 2015/04 - 2021/12        | 指導職 |

## 株式会社Spectee(2023/11 -)

2023年に入社。防災系プロダクトのダッシュボード機能に関わるバックエンド開発を担当。配信できる種類の拡充や、SNSのAPI仕様変更に伴う改修などを担当。

### チーム構成

4~5人1チームのスクラムチーム。ロールは開発メンバー兼スクラムマスター。
全体で30人ほどエンジニアが所属。

### 主な実績

#### アラート・メール配信機能の基盤構築（2024/12 - 現在）

アラート・メール配信機能の基盤を整備する大規模プロジェクトに参画。  
ユーザーが危機を迅速に察知できる仕組みを構築するため、基盤化前にデータフローの整理を実施。

3名のチームのメンバーとして参加。  
新たな技術挑戦の一環として、一部機能にRustを導入。  
GitHub Actionsを活用して**CI/CDパイプラインを構築し、AWS環境へのデプロイを標準化**。これにより、誰でも迷わずデプロイできる環境を整備し、運用負担を軽減。

| カテゴリ | 使用技術 |
| --- | --- |
| **プログラミング言語** | Python, TypeScript, Rust |
| **インフラ** | AWS (Lambda, DynamoDB, S3, SSM, EventBridge), AWS CDK, Docker |
| **CI/CD** | GitHub Actions |
| **Linter / Formatter** | Ruff, mypy, Prettier |
| **開発ツール** | Rye, uv, volta, turborepo |

---

#### ダッシュボード配信機能拡充（気象特別警報・指定河川洪水予報）（2024/06 - 2024/12）

ダッシュボード上に新たな配信データを追加するプロジェクトをリード。  
気象特別警報や指定河川洪水予報、南海トラフ情報等のデータをリアルタイムで配信できるように拡充。

（2024/06 - 2024/12）3名のチームをリードし、開発を推進。  
経験の浅いメンバー（新入社員含む）をサポートするため、**TDD・ペアプロ・モブプログラミングを導入**。知見の共有を促進し、**プロジェクトを遅延なくスケジュール通りリリース**した。  
Ruffを用いたリンター・フォーマッター設定を統一し、**チーム全体のコード品質を向上**。  
GitHub Actionsを活用。プルリク時のテスト実行並びにカバレッジ表示、AWS環境へのデプロイを標準化し、コード品質を一定に保つ仕組みを導入した。

| カテゴリ | 使用技術 |
| --- | --- |
| **プログラミング言語** | Python, TypeScript |
| **インフラ** | AWS (Lambda, DynamoDB, S3, SSM, EventBridge), AWS CDK, Docker |
| **CI/CD** | GitHub Actions |
| **Linter / Formatter** | Ruff, mypy, Prettier |
| **開発ツール** | Rye, uv, volta |

---

#### ツイートデータ取得・解析プログラム開発（2024/03 - 2024/07）

SNSデータの取得・解析を行うシステムの開発。  
API仕様変更に伴い、既存システムの改修と新規機能追加を担当。

3名のチームをリードし、開発を推進。  
チームとして初めてTypeScriptを本格的に活用するプロジェクトであったため、**ペアプロ・モブプログラミングを実施し、知見の共有を促進**。チームで輪読会を行いTypeScriptのキャッチアップも実施した。  
社内初の**Turborepoによるモノレポ管理とBiomeを活用したリンター導入**を実施。これにより、開発の効率化とコード品質向上を実現し、移行期限の**2週間前にプロジェクトを完遂**。

| カテゴリ | 使用技術 |
| --- | --- |
| **プログラミング言語** | TypeScript |
| **インフラ** | AWS (Lambda, ECS, DynamoDB, S3, SSM, EventBridge, Firehose), AWS CDK, Docker |
| **CI/CD** | GitHub Actions |
| **Linter / Formatter** | Biome |
| **開発ツール** | volta, turborepo |

## 株式会社アーセス(2022/01 - 2023/10)

2022年に入社し、気象プロダクトを活用した某県向け水防活動報告書作成システム、気象データAPIや某社向け認証認可API構築などバックエンド開発を主に担当。

### チーム構成

2~3人で1チームのメンバー。所属部署は10人、全体で30人ほどエンジニアが所属。

### 主な実績

#### 気象データAPIの開発（2022/07 - 2023/03）

気象プロダクトの解析・保存機能およびデータ提供APIの開発を担当。
APIは現在または指定された日時の過去データを取得するものである。

2名のチームのメンバーとして参加。  
既存のデータ取得APIは処理が重かったため、格納データのバイナリ化を提案・実装し、**APIレスポンスを実装前から50%高速化**。
社内初のAWS案件だったため、ローカル開発環境にLocalStackを導入、IaCにAWS SAMを調査・提案・実装し、**今後の開発基盤を整備。開発スピードを向上させ、デプロイ前の動作確認の手間を削減**。
1400万円の売上に貢献。かつ利益工数内に収めることができた。

| カテゴリ | 使用技術 |
| --- | --- |
| **プログラミング言語** | Python |
| **フレームワーク** | FastAPI |
| **データベース** | PostgreSQL, SQLAlchemy, Alembic |
| **インフラ** | AWS (Lambda, RDS, S3, SecretsManager, EventBridge), AWS SAM, Docker, localstack |
| **Linter / Formatter** | black, flake8, mypy |
| **開発ツール** | pipenv |

## 資格

- **ORACLE MASTER Java認定資格 Silver**（2021.06）
- **UMTP UMLモデリング認定試験 L1**（2021.07）
- **基本情報技術者試験**（2024.04）
- **LPIC-2**（2024.08）
- **応用情報技術者試験**（2024.12）
- **AWS Certified Solutions Architect - Associate**（2025.02）
- **AWS Certified Developer - Associate**（2025.03）
