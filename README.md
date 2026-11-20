# 建方シーケンス (TC Sequencing)

Trimble Connect 3D Viewer 用の拡張機能（鉄骨建方の順序管理）の公開用ビルドです。

- フェーズ / グループ（色分け）の作成・変更
- 選択部材の追加、基準点から近い順の自動番号付け
- 建方シミュレーション
- Excel レポート出力（プロジェクトの `Sequencing/Sequencing.xlsx`）
- データはプロジェクトの `Sequencing/sequencing.json` に自動保存

## 登録方法

Trimble Connect（Web 版）でプロジェクトを開き、**設定 → 拡張機能** でカスタム拡張機能として次の URL を追加します。

```
https://tc-tools-test.github.io/tc-sequencing/manifest.json
```

このリポジトリはビルド成果物のみです。ソースからの更新は `npm run deploy` で行います。
