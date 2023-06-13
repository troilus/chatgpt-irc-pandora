# 🤖 chatgpt-irc

chat with chatgpt on irc! And using [pengzhile/pandora](https://github.com/pengzhile/pandora) API.

在IRC中使用chatgpt, 使用[pengzhile/pandora](https://github.com/pengzhile/pandora) 的API.

## demo video

https://user-images.githubusercontent.com/83531587/216813675-52ae3cca-efd0-41e5-928a-b9e8ed1cbe7d.mp4
## Abot Pandora API | 关于Pandora API
https://github.com/pengzhile/pandora/issues/837
## configuration | 配置
- collect your auth token | 取得token
  
  see https://github.com/pengzhile/pandora/issues/837#issuecomment-1585595526 step1 and step2 | 详见https://github.com/pengzhile/pandora/issues/837#issuecomment-1585595526 的第1、2步

- create `config.json` using [the example configuration](#example-config) | 使用[the example configuration](#example-config)创建配置文件，示例


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


- run the bot: `python chatgpt-irc.py` | 运行机器人 `python chatgpt-irc.py`

![image](https://github.com/troilus/chatgpt-irc-pandora/assets/1055100/f8b0e362-1fdb-4dcb-be8a-9161ab990706)



