# CHANGELOG - alt-ime-rev-plus

このファイルは **alt-ime-rev-plus** 独自のリリース履歴です。
上流 [alt-ime-rev](https://github.com/yuki0ueda/alt-ime-rev) の変更履歴は
[上流 CHANGELOG](https://github.com/yuki0ueda/alt-ime-rev/blob/main/CHANGELOG.md) を参照してください。

## [plus-1.0.0] - 2026-06-15 — 初回リリース

### Added (plus)

- **コロン / セミコロン入替** — `;` → `:`、`Shift+;` → `;`（修飾子付き対応）
- **シングル / ダブルクォート入替** — `'` → `"`、`Shift+'` → `'`（修飾子付き対応）
- **右 Shift 空打ちでアンダーバー** — Alt 空打ちと同じ `A_PriorHotkey` 判定パターン

### Upstream base

- [alt-ime-rev v1.0.0](https://github.com/yuki0ueda/alt-ime-rev/releases/tag/v1.0.0) (2026-04-13)
  - 左右 Alt 空打ち IME 切替、デバッグモード、ファイルログ、New Outlook 対応 等
  - 詳細は上流 CHANGELOG を参照

### Notes

- 記号リマップは常時有効（US 物理キーボード専用）
- 右 Shift のメニュー抑制は Alt と同様 `vkFF` を使用
- Mac-JIS リマップは [tealgreen0503/alt-ime-ahk-plus](https://github.com/tealgreen0503/alt-ime-ahk-plus)（AHK v1）から v2 移植
