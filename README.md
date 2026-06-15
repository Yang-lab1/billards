# 台球扑克 Pro

手机端多人牌局记分工具。当前联机层使用 Supabase Realtime Broadcast，不再依赖 PeerJS/WebRTC 直连。

## 线上地址

https://billiards-lovat.vercel.app

## 配置说明

前端可以使用 Supabase `Project URL` 和 `publishable/anon key`。不要把 `service_role`、数据库密码、JWT secret 或其他后台密钥提交到仓库。

当前页面会在浏览器本地保存 Supabase URL 和 publishable/anon key。后续如果要让普通用户完全无感，可以把公开配置写入页面或构建环境变量。
