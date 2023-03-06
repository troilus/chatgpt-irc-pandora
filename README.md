# 🤖 chatgpt-irc

chat with chatgpt on irc!

## demo video

https://user-images.githubusercontent.com/83531587/216813675-52ae3cca-efd0-41e5-928a-b9e8ed1cbe7d.mp4

## configuration

- head to the [chatgpt website](https://chat.openai.com/chat) and sign in
- open the network tab in devtools (press F12)
- say "hi" to chatgpt
- collect your auth token, user agent, and cookie from the *headers* tab
  - make sure to escape the cookie value as it can contain quotes and other special characters  
- create `config.json` using [the example configuration](#example-config)
  below or by copying `example-config.json`
- run the bot: `python chatgpt-irc.py`

![](https://rj1.su/img/chatgpt-irc-sshot1.png)

## example config

```
{
    "server": "internetrelaychat.net",
    "port": 6697,
    "ssl": true,
    "nickname": "chatgpt",
    "ident": "chatgpt",
    "realname": "chatgpt",
    "password": "",
    "channels": ["#rj1"],
    "auth_token": "",
    "cookie": "",
    "useragent": ""
}
```
