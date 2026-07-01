# オリカ図鑑

オリジナルMTGカードを画像ごと登録・編集・閲覧できるWebアプリです。

## GitHub Pagesで公開する手順

1. このZIPをiPhoneの「ファイル」アプリで展開します。
2. GitHubの `orica-card-book` リポジトリで Upload files を開きます。
3. ZIPそのものではなく、中身の以下3つをアップロードします。
   - index.html
   - manifest.webmanifest
   - sw.js
4. Commit changes を押します。
5. Settings → Pages → Source: Deploy from a branch → Branch: main / root → Save
6. 数分後に `https://ユーザー名.github.io/orica-card-book/` で開けます。
7. iPhoneのSafariで開き、共有ボタン → ホーム画面に追加。

## 機能

- カード画像登録
- カード追加・編集・削除
- 名前・色・タイプ・シリーズ検索
- 分類フィルター
- お気に入り
- 世界観メモ
- バックアップ・復元
- ホーム画面追加対応
