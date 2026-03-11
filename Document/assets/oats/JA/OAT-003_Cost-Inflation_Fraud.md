---

layout: col-sidebar
title: OAT-003 Cost-Inflation Fraud
site_side: false
tags: oatsEN
project: true

---

**コストインフレ詐欺 (Cost-Inflation Fraud)** は自動化された脅威です。 OWASP Automated Threat Handbook - Web Applications ([pdf](https://github.com/OWASP/www-project-automated-threats-to-web-applications/tree/master/assets/files/EN), [印刷物](http://www.lulu.com/shop/owasp-foundation/automated-threat-handbook/paperback/product-23540699.html)) は [OWASP Automated Threats to Web Applications Project](../../../) の成果物であり、それぞれの脅威、検出方法、対策についてより詳しいガイドを提供します。 [脅威識別チャート](https://www.owasp.org/www-project-automated-threats-to-web-applications/assets/files/oat-ontology-decision-chart.pdf) は自動化された脅威を正しく識別するのに役立ちます。

## 定義
### OWASP Automated Threat (OAT) ID 番号
OAT-003

### 脅威イベント名
コストインフレ詐欺 (Cost-Inflation Fraud)

### 特徴・特性の概要
機能を大量に使用して、有料サポートサービスから不正に利益を得ます。

### イメージ図
<img alt="Indicative diagram for OAT-003" src="images/500px-OAT-003_Cost-Inflation_Fraud.png" style="background-color:#eeeeee;padding:1em;">

### 解説
API 使用イベント (例: マッピング、検索、AI 呼び出し、メッセージング)、アクセス課金 (例: ドキュメント、調査、データ)、広告/アフィリエイトマーケティング (例: クリックスルー、広告表示)、サービス成果報酬 (例: SEO) などのサードパーティが提供するサービスを利用する機能を使用します。これらのインタラクションは関連するサービスプロバイダから請求される料金を水増しします。この攻撃はサービスプロバイダ (または従業員、エージェント、仲介者など) が不正な行動を行ったり、何らかの方法で侵害されていることを前提としており、攻撃者は水増しされた料金の恩恵を受けます。

攻撃者に利益をもたらすような料金のインフレーションを伴わない同様の行為については [OAT-016 スキューイング (Skewing)](OAT-016_Skewing.md) を参照してください。v1.3 以前には、OAT-003 は広告偽装 (Ad Fraud) と名付けられていました。


### 他の名称や事例
API 使用のインフレ (API usage inflation); 人工的に膨らませたトラフィック (Artificially Inflated Traffic, AIT); 広告偽装 (Advert fraud); アドウェアトラフィック (Adware traffic); クリックボット (Click bot); クリック偽装 (Click fraud); ヒット偽装 (Hit fraud); インプレッション偽装 (Impression fraud); クリック課金型広告の不正使用 (Pay per click advertising abuse); 偽装広告トラフィック (Phoney ad traffic); SMS ポンピング (SMS Pumping); トール詐欺 (Toll fraud); 移転価格 (Transfer pricing)

### 関連項目
* [OAT-016 スキューイング (Skewing)](OAT-016_Skewing.md)
* [OAT-017 スパム行為 (Spamming)](OAT-017_Spamming.md)

## クロスリファレンス
### CAPEC Category / Attack Pattern IDs
* 210 Abuse Existing Functionality

### CWE Base / Class / Variant IDs
* 799 Improper Control of Interaction Frequency
* 841 Improper Enforcement of Behavioural Workflow

### WASC Threat IDs
* 21 Insufficient Anti-Automation
* 42 Abuse of Functionality

### OWASP Attack Category / Attack IDs
* Abuse of Functionality

<br/><br/>[OWASP ウェブアプリケーションに対する自動化された脅威プロジェクト](../../../) に戻る。<br/><br/>
