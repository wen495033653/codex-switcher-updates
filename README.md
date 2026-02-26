# codex-switcher-updates

codex账号切换器的公开更新清单仓库（不存源码）。

## 主要用途
- 提供客户端更新检测使用的 `update.json`
- 通过 GitHub Actions 手动发布最新版本信息

## update.json 字段
- `version`：版本号（必须与 `codex-switcher/package.json.version` 一致）
- `download_url`：蓝奏云分享链接
- `published_at`：发布时间（UTC）
- `notes`：更新说明

## 发布步骤
1. 在私有仓库 `codex-switcher` 更新 `package.json.version` 并提交。
2. 构建 `exe` 并上传蓝奏云。
3. 打开本仓库 `Actions`，运行 `Publish Update Manifest`。
4. 填写 `version`、`download_url`、`notes`，执行后自动更新 `update.json`。

## 地址
- 清单地址：`https://raw.githubusercontent.com/wen495033653/codex-switcher-updates/main/update.json`
