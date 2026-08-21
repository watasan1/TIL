# GitHub Pull Requestを使いこなすコツ

作成日: 2026-08-21

## 学んだこと

Pull Requestは作成するだけでなく、「小さく分ける」「わかりやすい説明を書く」など使い方を工夫することでレビューしやすくなる。

## 詳細・メモ

**効果的な使い方のコツ**

- 小さく分ける: 1つのPRで1つの変更に集中する。変更が大きいほどレビュー負担が増え、問題を見落としやすくなる。
- わかりやすい説明を書く: 「何を」はコードを読めば分かるが、「なぜ」はPRの説明文でしか伝わらない。
- レビューしやすく整える: コードを整理し、必要に応じてコメントを添える。
- 早めに出す（Draft PR）: 完成を待たずDraft PRで早期にフィードバックをもらい、方向性のズレを早期発見する。
- 議論を歓迎する: レビューコメントは指摘ではなく改善のチャンス。

**実プロジェクトでの活用例**

- Issue連携: `#1` のように書くと自動リンクされる。
- PRテンプレート: 説明の書き方に統一感が出る。
- CI/CD連携: テスト・ビルドが自動実行され、通過してからマージする運用が多い。
- レビュアー指定: 「誰が確認すべきか」が明確になり、レビュー漏れを防げる。

## 成果物

[TILにPull Requestのコツについての記事を追加する](https://github.com/watasan1/TIL/issues/3)

## 参考

- [Pull Request](https://docs.github.com/ja/pull-requests/reference/pull-requests)
- [pull request の作成](https://docs.github.com/ja/pull-requests/how-tos/create-pull-requests/creating-a-pull-request)
- [サル先生のGit入門 プルリクエストとは？](https://git-tutorial.backlog.com/pull-request/01/)
