# 项目推送规则

- 默认目标：`origin`，`https://github.com/Dikui/dk-dsh-navigation-fold.git`，`main`。
- 提交信息沿用 Conventional Commits。

## 版本文件

- 插件版本文件：根目录 `package.json` 的 `version`；默认升修订号，用户明确指定版本或要求不升时除外。

## 必须提交的构建产物

- 构建命令：`node scripts/build.mjs`
- 产物：`lib/client.js`

`lib/client.js` 由源码生成，随提交入库，不手改。
