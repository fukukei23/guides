# guides

> A collection of quick-reference guides for developers.
>
> 開発者向けクイックリファレンスガイド集（47冊）。モバイル最適化ダークテーマHTML。

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-green)](https://fukukei23.github.io/guides/) [![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## 特徴

- スマートフォンで見やすいモバイル最適化レイアウト
- ダークテーマ（Tokyo Night 配色）
- 外部依存ゼロ（Pure HTML/CSS）
- 開発手法・Claude Code・Git・インフラ・セキュリティなど47カテゴリ

---

## なぜ作ったか

Claude Code で開発中に「あのコマンドなんだっけ」「この設計原則どう使うんだっけ」を素早く確認したい。外部サービスに依存せず、オフラインでも読める静的HTMLガイド集として整備した。

---

## カテゴリ構成

| カテゴリ | ガイド例 |
|---|---|
| 開発手法 | TDD / BDD / DDD / クリーンアーキテクチャ / 仕様駆動開発 |
| 自動化 | dev-cycle / CI/CD / 開発手法×自動化 |
| Claude Code | クイックスタート / LLM切り替え / Hooks / MCP / コマンド |
| Git / GitHub | Git逆引き / GitHub CLI / GitHub Actions |
| インフラ | WSL2 / Docker / Tailscale / SSH / tmux |
| 言語 / ツール | Python基礎 / npm-bun / Regex / Markdown |
| セキュリティ | セキュリティ基礎 / エラー読解 |
| キャリア | ポートフォリオ / 面接用語集 |

---

## プロジェクト状況

| 指標 | 値 |
|---|---|
| ガイド数 | 47冊 |
| 形式 | 静的HTML（GitHub Pages） |
| 更新頻度 | 随時（Claude Code で自動生成） |

---

## セットアップ

GitHub Pages で公開済み。ローカルで確認する場合:

```bash
git clone https://github.com/fukukei23/guides
cd guides
python3 -m http.server 8080
# → http://localhost:8080 で確認
```

---

## 新しいガイドを追加する

```bash
# 1. ディレクトリを作成
mkdir guides/<カテゴリ名>

# 2. index.html を作成（既存ガイドをテンプレートとして使用）
cp guides/development-automation/index.html guides/<カテゴリ名>/index.html

# 3. トップページ (index.html) にリンクを追加
# 4. コミット & プッシュ → GitHub Pages に自動反映
```

---

## 関連リポジトリ

- [claude-code-guide](https://github.com/fukukei23/claude-code-guide) — Claude Code CLI 完全ガイド（HTML版）
- [python-reading-guide](https://github.com/fukukei23/python-reading-guide) — Python読解教材
- [obsidian-ssot](https://github.com/fukukei23/obsidian-ssot) — 知識ベース（非公開）
