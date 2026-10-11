# create-proposal-slides

与件ヒアリングから提案書の完成までを工程に分けて進める、日本語の Agent Skill です。

## 収録スキル

| スキル | 内容 |
|---|---|
| [`proposal-writing-ja`](skills/proposal-writing-ja/SKILL.md) | 案件把握 → 与件の具体化とヒアリング設計 → 課題の構造化 → 提案コンセプト → 構成設計 → 本文作成と推敲 → 品質レビューの7工程。議事録や案件ステータスはどの工程でも取り込み、「案件カルテ」に集約します。 |

## 連携するスキル

`proposal-writing-ja` は次の2つのスキルと組み合わせて使う前提です。入っていない場合は、同じやり方をスキル自身が代わりに行います。

- [grill-me](https://github.com/ninehills/mattpocock-skills)：与件の具体化。1問ずつ推奨回答付きで問い詰めます。
- [yomiyasu](https://github.com/nanaism/yomiyasu)：文章の推敲と同梱リンター（`--domain business --full`）。

## 使い方

`skills/proposal-writing-ja/` フォルダを、使っている環境のスキル置き場（例：Claude Code なら `~/.claude/skills/`）にコピーするか、claude.ai のスキル設定からアップロードしてください。
