# アプリ指標ログ（App Store Connect・iOS）

> 出典：本人スクショ。期間はASC「過去90日」（dateSpec=d90）。日付は集計の最終日。
> 目標：まなび 累計インストール 12/31=15 → 2/28=50（iOS+Android）。rooter 閲覧→DL 8%→15%。

| 集計日 | アプリ | 初回DL | 再DL | 表示 | 閲覧 | CVR | 備考 |
|---|---|---|---|---|---|---|---|
| 11/22 | まなび | 3 | – | 129 | 20 | 3.8% | |
| 11/23 | まなび | **4** | 1 | 133 | 21 | 6.1% | +1DL |
| 11/22 | rooter | 2 | – | 366 | 25 | 0.7% | |
| 11/23 | rooter | 2 | – | 378 | 25 | 0.7% | |
| 11/22 | ゾンビ | 1 | – | 27 | 10 | – | |
| 11/23 | ゾンビ | 1 | – | 27 | 10 | – | |
| 11/22 | おはよう | 1 | – | 7 | – | – | |
| 11/23 | おはよう | 1 | – | 9 | – | – | |

## Android（Google Play）
- まなび：製品版は11/20以前から公開中（司令塔報告）。Android累計インストール数＝要確認。
- ゾンビ：11/24 本番アクセス申請 → 11/25 1:01 **不承認**（テスト不足）。再申請可は12/9ごろ。統計のテスター13〜16→3名はゾンビ。方針は保守のみ。

## 11/25ごろ（スマホスクショ・期間は過去90日想定）
| アプリ | 初回DL | 再DL | 表示 | 閲覧 | CVR |
|---|---|---|---|---|---|
| まなび | 要確認 | 1 | 146 | 28 | 5.75% |
| rooter | – | – | 390 | 26 | 0.7% |
| ゾンビ | – | – | 29 | 11 | – |
| おはよう | – | – | 16 | 3 | – |
- ゾンビ：Play本番申請 2回目（11/25 18:46）も 11/26 01:01 不承認 → 保留確定。

## 11/26 夜（司令塔）

| 項目 | 値 | 出どころ | 状態 |
|---|---|---|---|
| まなび iOS 初回DL | 4〜5（11/25 スクショ） | ASC | 要確認（11/26 夜は ASC ログイン切れで取得できず） |
| まなび Android 累計インストール | 5（11/20 時点・デバイス獲得13） | Play Console | 要確認（ダッシュボードは「データ準備中」表示） |
| まなび Android 月間アクティブ端末 | 15（28日） | Play Console 11/26 | 取得済み |
| 12/31 目標 累計15 までの残り | 約5〜6（iOS 4〜5＋Android 5＝9〜10 として） | 上の合計 | 要確認（両方の最新値で取り直す） |

### 計測用リンク
- Play（UTM）
  - Instagram：https://play.google.com/store/apps/details?id=com.manabiteam.app&referrer=utm_source%3Dinstagram%26utm_medium%3Dsocial%26utm_campaign%3Dmanabi_202611
  - X：https://play.google.com/store/apps/details?id=com.manabiteam.app&referrer=utm_source%3Dx%26utm_medium%3Dsocial%26utm_campaign%3Dmanabi_202611
  - LP：https://play.google.com/store/apps/details?id=com.manabiteam.app&referrer=utm_source%3Dlp%26utm_medium%3Dweb%26utm_campaign%3Dmanabi_202611
- App Store（キャンペーンリンク）：https://apps.apple.com/app/apple-store/id6825277216?pt=<プロバイダトークン>&ct=instagram|x|lp&mt=8
  - プロバイダトークンは ASC の「キャンペーンリンクを作成」画面で確認が必要 → 要確認（ASC ログイン後）

## SNS の数字（週次レポート用・マーケ ETC-002）

> 1行＝1投稿。数字が見られないものは「未取得」。投稿前のものは状態に「未投稿」と書く。個人情報・パスワードは書かない。
> UTM：記事告知は utm_campaign=記事名_article、アプリ紹介は manabi_202611。

| 日付 | アプリ | 媒体 | 投稿（候補番号） | いいね・保存 | リンククリック | UTM（utm_campaign） | 状態 |
|---|---|---|---|---|---|---|---|
| 11/26 | まなび | Instagram | アプリ紹介 A＋2 | 未取得 | 未取得 | manabi_202611 | 未投稿（manabi.team 連携待ち） |
| 11/26 | まなび | X | アプリ紹介 1 | 未取得 | 未取得 | （LP 直リンク） | 未投稿（本人がコピペで投稿） |

### 出している候補（本人の選択待ち・#sns投稿用）
- まなび：アプリ紹介1件（選択済み）／1週間分 5件／冬休み記事の告知（utm_campaign=winter_article）
- rooter：アプリ紹介1件／辛口記事の告知（utm_campaign=harsh_article）

## 11/26 20:10 ASC 確認（司令塔）

| 項目 | 値 |
|---|---|
| まなび iOS 初回DL（10/26〜11/24・30日） | 4 |
| 再DL | 1 |
| 表示／閲覧／CVR（30日） | 146／28／5.75% |
| 12/31 目標 累計15 までの残り | 約6（iOS 4〜5＋Android 5＝9〜10 として。Android は 11/20 の値・要確認） |

### App Store キャンペーンリンク（まなび）
- Instagram：https://apps.apple.com/app/apple-store/id6825277216?pt=129406874&ct=instagram&mt=8
- X：https://apps.apple.com/app/apple-store/id6825277216?pt=129406874&ct=x&mt=8
- LP：https://apps.apple.com/app/apple-store/id6825277216?pt=129406874&ct=lp&mt=8
- 数え方：ASC アナリティクス → 獲得 → キャンペーン（5人以上インストールすると表示される）
