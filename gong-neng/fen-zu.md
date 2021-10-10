---
description: 可以设置不同的服务器分组使用不同的大厅。
---
# 分组

## 它是如何使用的？ <a href="ta-shi-ru-he-shi-yong-de" id="ta-shi-ru-he-shi-yong-de"></a>

你需要在 `config.yml` 中进行修改，BungeeHub 会根据你设置的类型和其他相关值进行不同的操作。

### name <a href="name" id="name"></a>

使用 /hub 时，显示的服务器组名称。 可以在 `messages.yml` 的 `UseHub` 中修改相关语句，也可以将语句设置为`""`，可以关闭发送功能。

### type <a href="type" id="type"></a>

支持的类型: `SERVER` `COMMAND` `QUEUE`

#### SERVER <a href="server-1" id="server-1"></a>

使用这种类型，它会直接传输到与组同名的服务器。

#### COMMAND <a href="command" id="command"></a>

使用这种类型，会执行相应的 `command`，可以设置多个命令。 以 Bungee 控制台身份执行，可以使用 [BungeeCommand](https://www.spigotmc.org/resources/bungeecommand.89275/) 插件以玩家执行 Bungee 命令。

#### QUEUE <a href="queue" id="queue"></a>

使用这种类型**需要** [ServerQueue](https://www.spigotmc.org/resources/serverqueue.91672/) 插件，可以根据实际情况选择对应的服务器。请确保您**使用** ServerQueue 并将 queue 设置为相应的值。

### server <a href="server" id="server"></a>

你可以设置使用此分组的服务器列表，并且它需要与服务器名称完全匹配。默认组可以不设置此项。
