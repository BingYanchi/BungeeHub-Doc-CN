---
description: 我提供了一个简单易懂的 API 文档。
---
# 开发者 API

## 如何使用

你您需要将此内容复制到您的插件中，然后按照上面提供的功能进行操作。

```java
import java.util.List;

import cn.yistars.bungeehub.api.HubHook;

public class BungeeHubHook implements HubHook {
 
    public static String getGroupName(String server) {
        return HubHook.getGroupName(server);
    }
 
    public static String getGroupType(String groupname) {
        return HubHook.getGroupType(groupname);
    }
 
    public static String getGroupQueue(String groupname) {
        return HubHook.getGroupQueue(groupname);
    }
 
    public static List<String> getGroupCommand(String groupname) {
        return HubHook.getGroupCommand(groupname);
    }
 
    public static String getDefaultGroup() {
        return HubHook.getDefaultGroup();
    }
}
```

{% hint style="info" %}
如果您仍有疑问或困惑。 您可以通过此 Wiki 顶部的 Discord 与我联系。
{% endhint %}
