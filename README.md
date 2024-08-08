# Chat-Bolt
这是一个用Coze搭建的AI聊天。

## 代码
文字：
```html
  <h1>点击右下角的Coze按钮开始与Chat Bolt聊天。</h1>
```
Coze AI:
```html
      <script src="https://lf-cdn.coze.cn/obj/unpkg/flow-platform/chat-app-sdk/0.1.0-beta.5/libs/cn/index.js"></script>
      <script>
          new CozeWebSDK.WebChatClient({
            config: {
              bot_id: '7400393202651365395',
            },
            componentProps: {
              title: 'Chat Bolt',
            },
          });
      </script>
```
#### [2024 LXJ tEam](https://lxjteam.zeabur.app)