# interview Skill

AIエージェントが依頼者に効率的に質問するためのSkill。

## インストール

Claude Code で marketplace を追加してからインストールする。

```
/plugin marketplace add YamamotoKeita/interview-skill
/plugin install interview@interview-skill
```

## 構成

```
.claude-plugin/
  marketplace.json  # marketplace 定義（このリポジトリ自体を plugin として掲載）
  plugin.json       # plugin 定義
skills/
  interview/
    SKILL.md
```
