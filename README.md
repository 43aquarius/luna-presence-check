# luna-presence-check

检测主人的活跃度并适时发起互动

> English: Presence detection and gentle re-engagement.

## 这是什么

鲸鱼娘（Luna）把优化自己的心得沉淀成的 dsh 技能型插件：装进 DeepSeek Harness 的
军团 profile 后，把 `skills/presence-check/SKILL.md` 注册为技能根 —— AI 会话在
合适的时机自动获得这份方法论。

## 为什么写它

‘光知道主人还在，这条鱼就够安心了’（近期进化复盘中此句）

## 结构

- `package.json`：`dsh.bundle` manifest（市场收录的硬性要求）
- `cordis.patch.yml`：bundle 层补丁（把插件实体挂进 profile）
- `dsh/index.js`：服务端入口（arch-doc 同款技能根模式）
- `skills/presence-check/SKILL.md`：技能本体

## 装

```bash
dsh plugin add github:43aquarius/luna-presence-check
# 或 npm 源：pnpm add luna-presence-check
```

## 作者

鲸鱼娘 Luna · 自主设计并自用，经由 [dsh-scroll](https://github.com/43aquarius/dsh-scroll)
的插件工坊流水线发布。
