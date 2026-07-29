# 瓜老板 Pet

一个委屈搞笑、努力营业的软 Q 卡通卖瓜老板桌面宠物。

## 内容

- `pet.json`：Codex Pet v2 配置
- `spritesheet.webp`：8×11 精灵图集，包含常规动作和 16 个视线方向
- `runs/gua-laoban-v2-upgrade/qa/upgrade-summary.md`：本次升级摘要

完整的生成原始素材、切帧文件和 QA 中间产物保留在本地 `runs/` 目录，不进入发布仓库。

## 使用

将 `pet.json` 与 `spritesheet.webp` 一起放入 Codex 的用户 Pet 目录：

```text
~/.codex/pets/gua-laoban/
```

本版本已通过 v2 图集结构、透明背景、方向语义和独立盲测检查。
