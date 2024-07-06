### 键盘映射表类

```csharp
public class KeyMapping
    {
        public string actionName;
        public KeyCode keyCode;

        public KeyMapping(string actionName, KeyCode keyCode)
        {
            this.actionName = actionName;
            this.keyCode = keyCode;
        }
    }
```

<code>KeySettingManager</code>为单例类
//todo