# Japan Localize Builder

海外で成功しているWebアプリを発見 → 超詳細に分析 → 日本向けにローカライズ → Claude Codeで直接開発するフルスタック自動化スキル。

## 何ができるか

```
海外で流行っているWebアプリを自動リサーチ
    ↓
日本市場でのチャンスをスコアリング
    ↓
ローカライズ戦略 & 超詳細要件定義書を自動作成
    ↓
Claude Codeが Next.js + shadcn/ui + Convex + Clerk で直接開発
    ↓
GitHub / Convex / Vercel に自動デプロイ
    ↓
品質改善ループ（最大20周）で本番品質に仕上げ
```

## インストール方法（Claude Code）

```bash
# 1. マーケットプレイスを登録
/plugin marketplace add kimurataiyou/japan-localize-builder

# 2. プラグインをインストール
/plugin install japan-localize-builder@japan-localize-skills
```

または、UIからインストール:
1. `/plugin` を入力
2. `Browse and install plugins` を選択
3. `japan-localize-skills` を選択
4. `japan-localize-builder` を選択
5. `Install now`

## 使い方

インストール後、Claude Codeに以下のように話しかけるだけ:

- 「海外アプリを日本向けにローカライズして」
- 「Japan localize して」
- 「海外で流行ってるWebアプリを見つけて日本版を作って」

## ワークフロー（9フェーズ）

| フェーズ | 内容 |
|---------|------|
| Phase 0 | 開発済みプロダクト重複チェック |
| Phase 1 | 海外プロダクトのディープリサーチ（5件以上） |
| Phase 1.5 | 候補アプリの実地調査（WebFetch） |
| Phase 2 | 日本市場スコアリング（5軸評価） |
| Phase 3 | ローカライズ戦略 + 超詳細要件定義書 |
| Phase 4 | Claude Codeが直接開発 |
| Phase 5-6 | テスト・品質チェック・SEO・セキュリティ |
| Phase 7 | GitHub / Convex / Vercel デプロイ + 品質改善ループ |
| Phase 8 | Clerk認証セットアップ |
| Phase 9 | 完了レポート |

## 技術スタック

- **フロントエンド**: Next.js 15 + TypeScript + Tailwind CSS + shadcn/ui
- **バックエンド/DB**: Convex
- **認証**: Clerk
- **デプロイ**: Vercel
- **フォント**: Noto Sans JP

## セットアップ（初回のみ）

スキルをインストールした後、`references/built-products.md` に開発済みプロダクトを記録していくことで、重複を自動防止します。

### 個人情報の設定

SKILL.md 内のプレースホルダーを自分の情報に置き換えてください:

- `<YOUR_NAME>` → あなたの名前
- `<YOUR_ADDRESS>` → あなたの住所
- `<YOUR_EMAIL>` → あなたのメールアドレス

## ライセンス

Apache License 2.0
