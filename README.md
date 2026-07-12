# paint-board-lzcapp

## 自动发布

每天 23:00 UTC 检查 `ghcr.io/fc6a1b03/paint-board` 稳定版本，保留 `xget.xi-xu.me` 代理镜像，构建版本化 GitHub Release Asset，并只发布到喵喵私有商店。推送 `v*` tag 可触发完整发布。
