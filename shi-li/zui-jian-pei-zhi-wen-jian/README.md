---
description: 最简单的配置文件。
---
# 最简配置文件

此配置实现了的所有服务器的玩家使用 /hub 都传送到 `lobby` 服务器。

```yaml
# 调试模式
DebugMode: false

# 更新检查
CheckUpdate: true

# 默认服务器组
DefaultGroup: lobby

# 需要 bungeehub.use 权限才可以使用
NeedPermission: false

# 前往大厅使用的指令
Commands:
  hub: true
  lobby: false

# 服务器组
# type 类型: SERVER COMMAND QUEUE
Group:
  lobby:
    name: "%name%"
    type: SERVER
```
