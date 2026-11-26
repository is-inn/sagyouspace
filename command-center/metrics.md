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
  - Instagram：https://play.google.com/store/apps/details?id=com.manabiteam.app&referrer=utm_source%3Dinstagram%26utm_medium%3Dsocial%26utm_campaign%3Dmanabi
  - X：https://play.google.com/store/apps/details?id=com.manabiteam.app&referrer=utm_source%3Dx%26utm_medium%3Dsocial%26utm_campaign%3Dmanabi
  - LP：https://play.google.com/store/apps/details?id=com.manabiteam.app&referrer=utm_source%3Dlp%26utm_medium%3Dweb%26utm_campaign%3Dmanabi
- App Store（キャンペーンリンク）：https://apps.apple.com/app/apple-store/id6825277216?pt=<プロバイダトークン>&ct=instagram|x|lp&mt=8
  - プロバイダトークンは ASC の「キャンペーンリンクを作成」画面で確認が必要 → 要確認（ASC ログイン後）
