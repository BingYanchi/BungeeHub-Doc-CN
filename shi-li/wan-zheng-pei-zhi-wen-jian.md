---
description: 包含此插件的所有组类型。
---
# 完整配置文件

{% hint style="danger" %}
此配置文件包含需要 ServerQueue 的内容。 在使用这个配置文件之前，请确保你真的使用了这个插件。
{% endhint %}

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
    type: COMMAND
    command:
    - "bungeecommand %player% queue Lobby"
  bw_lobby:
    name: "&eBedWars Lobby"
    type: QUEUE
    server:
    - bw_1
    - bw_2
    - bw_3
    - bw_4
    queue: Bw_Lobby
  mm_lobby:
    name: "%name% Lobby"
    type: SERVER
    server:
    - mm_1
    - mm_2
    - mm_3
    - mm_4
    - mm_5
    - mm_6
```
