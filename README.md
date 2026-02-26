# codex-switcher
codex 账号切换器

## 主要功能
- 一键切换账号

## 数据位置
- 账号数据：`%APPDATA%/codex-switcher/accounts.json`
- Codex 配置：`~/.codex/auth.json`

## 下载地址
- `xxxxx`（替换为蓝奏云分享链接）

## 自动发布 Release
- `Actions -> Publish Update Manifest` 会自动：
  - 更新 `update.json`
  - 更新本 README 的 `## 下载地址`
  - 下载 EXE 并发布到对应版本的 GitHub Releases
- 输入说明：
  - `download_url`：蓝奏云分享链接（用于客户端更新提示）
  - `asset_url`：可选，EXE 直链（用于 Release 资产上传，蓝奏云分享页通常不能直接下载 EXE）
