# スポコミ - コミュニティ活性化によるスポーツ実施率の向上

サービス紹介ページ: [OpenDataHackathon2024 Collection 92](https://odhackathon.metro.tokyo.lg.jp/collection/92/)

## 取り組む課題
- 私達は[都知事杯OpenDataHackathon2024](https://odhackathon.metro.tokyo.lg.jp/)で西東京市の[行政課題](https://odhackathon.metro.tokyo.lg.jp/issues/)「スポーツ相談窓口システムの機能拡充によるスポーツ実施率向上」に取り組みます。

## 解決策
- 西東京市が目指すスポーツ実施率70%近くを達成している国は、地域のスポーツコミュニティを活性化させるための体制を政策として実現しています。私達は身近な人達からなる **スポーツを実施するスモールコミュニティ** を育成し、徐々につながっていくことで国全体にスポーツをするコミュニティネットワークを広げていく仕組み「スポコミ」を提案します。
- 「運動したいけど、どう始めたらいいかわからない」そんな気持ち、誰もが一度は感じたことがあるはず。気軽に参加できる小さなグループがあれば、もっと運動を楽しめると思いませんか？スポコミは、地域に根ざしたネットワークを「スポーツをする楽しさ」を共有することで再構築します。身近な人たちと一緒にスポーツを楽しむための、便利で使いやすいツールを提供し、自然とスモールコミュニティの形成を促します。無数に生まれたスモールコミュニティは、自治体の窓口や運動施設の掲示板をハブにしたネットワークを形成し、試合のマッチングやちょっとしたイベントの共催、さらにはイベントの開催テンプレートや練習ノウハウの共有が進むような仕組みが利用できます。スポーツをきっかけに地域活動が活性化し、人々が自然に助け合う地域社会が生まれる。スポコミは、そんな未来を目指しています。



## 作品説明
- 作品の一部にTokyo OSS Party!!で作成したSports Barrier-free Hubの設備・備品貸出システムを取り入れ、行政の窓口や設備をHubにコミュニティ形成を促進させる構想です。
- FirstStageではBackendのコミュニティ形成機能を中心に実装します。
- FinalStageではBackendのコミュニティ連携機能、UIなどを実装予定です。


### [BackEnd動作デモ](https://youtu.be/M3vnbaVYyG0)のストーリー説明
- MySQLのコンテナ起動
- IntelliJ IDEのデバッグモードでcommunity APIを起動
- 1. ユーザー２人を登録（userA, userB)
- 2. それぞれのユーザーでログインし、認証用のtokenを取得
- 3. userAでコミュニティを３つ登録
- 4. userBでコミュニティを２つ登録
- 5. コミュニティ全リスト取得
- 6. userA所属のコミュニティリスト取得
- 7. （コミュニティ間連携機能などを順次開発中）


### 作品構成要素
| 構成要素 | 概要 | GitHub Repository | 備考 |
| --- | --- | --- | --- |
| **spocomi-frontend** | コミュニティ情報の検索・閲覧を行うフロントエンド | [spocomi-frontend](https://github.com/dx-junkyard/spocomi-frontend) |  |
| **api-community-spring** | コミュニティ管理・検索 API | [api-community-spring](https://github.com/dx-junkyard/api-community-spring) |  |
| **spocomi-mysql** | API が利用する MySQL 定義 | [spocomi-mysql](https://github.com/dx-junkyard/spocomi-mysql) |  |


## システム構成
![システム構成](spocomi_system.jpg)

## 作品のロードマップ
![ロードマップ](spocomi_roadmap.jpg)


## dx-junkyard参加のお誘い
dx-junkyardでは、技術共有やコラボレーションを通じて、互いに学び、支援し合うメンバーを募集しています。一緒に創造性と革新性に満ちた社会の実現に貢献しましょう。
[コミュニティ参加はこちらのフォームから](https://forms.gle/PVW4kYYh53SzbfdbA)


## 連絡先
スポコミやデモ動画に関するご質問、その他のお問い合わせはこちらからお願いいたします。
[https://www.dx-junkyard.com/](https://www.dx-junkyard.com/)

![メール](em_add.png)


