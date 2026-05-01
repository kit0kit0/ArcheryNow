# ArcheryNow（法務文書・GitHub Pages）

ArcheryNow アプリの**利用規約**と**プライバシーポリシー**を多言語で公開するリポジトリです。アプリ本体のソースは含みません。

## GitHub Pages

**Settings → Pages** で Branch **`main`**、Folder **`/docs`** を選択してください。

### デフォルト URL（アプリ内 `LegalLinks` と一致）

| 文書 | URL |
|------|-----|
| サイトトップ（言語一覧） | https://kitokito.app/ |
| 利用規約（**日本語・既定**） | https://kitokito.app/terms.html |
| プライバシー（**日本語・既定**） | https://kitokito.app/privacy.html |

### app-ads.txt（Google AdMob）

| ファイル | 公開 URL |
|----------|----------|
| `docs/app-ads.txt` | https://kitokito.app/app-ads.txt |

ストアの開発者サイト URL は `https://kitokito.app/` に統一します。[AdMob のクローラ](https://support.google.com/admob/answer/9363762)はホスト名から `https://kitokito.app/app-ads.txt` を探索するため、このファイルをサイトルートに公開します。

### 対応言語一覧（アプリの `Locale.xcstrings` と同じ 12 言語）

| # | 言語 | コード | 利用規約 | プライバシー |
|---|------|--------|----------|--------------|
| 1 | 日本語 | ja | [/terms.html](https://kitokito.app/terms.html) | [/privacy.html](https://kitokito.app/privacy.html) |
| 2 | English | en | [/en/terms.html](https://kitokito.app/en/terms.html) | [/en/privacy.html](https://kitokito.app/en/privacy.html) |
| 3 | 한국어 | ko | [/ko/terms.html](https://kitokito.app/ko/terms.html) | [/ko/privacy.html](https://kitokito.app/ko/privacy.html) |
| 4 | Español | es | [/es/terms.html](https://kitokito.app/es/terms.html) | [/es/privacy.html](https://kitokito.app/es/privacy.html) |
| 5 | Français | fr | [/fr/terms.html](https://kitokito.app/fr/terms.html) | [/fr/privacy.html](https://kitokito.app/fr/privacy.html) |
| 6 | Deutsch | de | [/de/terms.html](https://kitokito.app/de/terms.html) | [/de/privacy.html](https://kitokito.app/de/privacy.html) |
| 7 | 简体中文 | zh-Hans | [/zh-hans/terms.html](https://kitokito.app/zh-hans/terms.html) | [/zh-hans/privacy.html](https://kitokito.app/zh-hans/privacy.html) |
| 8 | 繁體中文 | zh-Hant | [/zh-hant/terms.html](https://kitokito.app/zh-hant/terms.html) | [/zh-hant/privacy.html](https://kitokito.app/zh-hant/privacy.html) |
| 9 | Türkçe | tr | [/tr/terms.html](https://kitokito.app/tr/terms.html) | [/tr/privacy.html](https://kitokito.app/tr/privacy.html) |
| 10 | Português | pt | [/pt/terms.html](https://kitokito.app/pt/terms.html) | [/pt/privacy.html](https://kitokito.app/pt/privacy.html) |
| 11 | Italiano | it | [/it/terms.html](https://kitokito.app/it/terms.html) | [/it/privacy.html](https://kitokito.app/it/privacy.html) |
| 12 | हिन्दी | hi | [/hi/terms.html](https://kitokito.app/hi/terms.html) | [/hi/privacy.html](https://kitokito.app/hi/privacy.html) |

ソースファイルは `docs/legal/<locale>/terms-of-service.md` および `privacy-policy.md` にあります（`zh-Hans` → フォルダ名 `zh-hans`）。

日本語以外の本文には、**準拠法・管轄（日本法・横浜地方裁判所平塚支部）については日本語版が優先**する旨の注記があります。

## お問い合わせ

公開用メールは設けていません。[Issues](https://github.com/kit0kit0/ArcheryNow/issues) をご利用ください。

## ライセンス

法務文書の著作権は運営者に帰属します。無断転載を禁じます。
