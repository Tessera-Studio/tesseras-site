# tesseras.jp

合同会社Tessera Studio の会社サイト。GitHub の Organization「Tessera-Studio」の GitHub Pages で公開し、独自ドメイン tesseras.jp につなぐ。

| URL | ファイル | 使い道 |
|---|---|---|
| https://tesseras.jp/ | `index.html` | 会社のトップ・会社概要 |
| https://tesseras.jp/metermap/ | `metermap/index.html` | メーターマップの紹介・よくある質問・サポート（App Store の「サポート URL」） |
| https://tesseras.jp/metermap/privacy | `metermap/privacy.html` | プライバシーポリシー（App Store の「プライバシーポリシー URL」） |
| https://tesseras.jp/legal | `legal.html` | 特定商取引法に基づく表記（メーターマップのプレミアムの販売）。アプリの購入シート・ヘルプからも開く |
| https://tesseras.jp/app-ads.txt | `app-ads.txt` | AdMob の発行者 ID（会社のアカウント pub-4938846991161247）。App Store の「マーケティング URL」の tesseras.jp を AdMob が確かめる |

## 公開前に埋めるところ

いまはなし（プライバシーポリシーと特定商取引法に基づく表記は公開済み）。

## DNS（お名前.com）

「DNSレコード設定」に次を足す。いまある MX・TXT（SPF・google-site-verification・google._domainkey）・Google 確認用の CNAME は Google Workspace のメール用なので、消したり書き換えたりしない。

| ホスト名 | TYPE | VALUE |
|---|---|---|
| （空欄） | A | 185.199.108.153 |
| （空欄） | A | 185.199.109.153 |
| （空欄） | A | 185.199.110.153 |
| （空欄） | A | 185.199.111.153 |
| www | CNAME | tessera-studio.github.io |

GitHub の Settings → Pages で「Custom domain」に `tesseras.jp` を入れ、確認が通ったら「Enforce HTTPS」をオンにする。
