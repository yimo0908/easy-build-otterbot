# 写在前面 
[![QQGroup](https://img.shields.io/badge/QQ%20Group-660557003-brightgreen)](https://jq.qq.com/?_wv=1027&k=2ecQU6AV)            [![](https://img.shields.io/badge/OtterBot-Bluefissure-brightgreen)](https://github.com/Bluefissure/OtterBot)            [![system](https://img.shields.io/badge/system-Windows-brightgreen)](https://www.microsoft.com/zh-cn/software-download)

**此页面所有内容基于Windows系统。有任何问题请[进群](https://jq.qq.com/?_wv=1027&k=2ecQU6AV)询问大佬，感谢合作。**

**All things in this page are based on Windows. If you have any question, please [join the QQ group](https://jq.qq.com/?_wv=1027&k=2ecQU6AV) to seek advice. Thanks for your cooperation.**

---

# [OtterBot](https://github.com/Bluefissure/OtterBot) 

A QQ bot for Final Fantasy XIV (mostly served for CN server).

---

# 前期准备 

1. 一个QQ小号

2. 一台接入了互联网的Windows电脑

---

# 正式领养 
## Step 1：在獭窝中注册

登陆獭窝（见下方快捷链接）。

[![Website](https://img.shields.io/website?label=%20%E4%B8%BB%20%E7%AA%9D%20&style=social&up_message=link&url=https%3A%2F%2Fxn--v9x.net%2F)](https://xn--v9x.net/)  [![Website](https://img.shields.io/website?label=%20%E7%AC%94%20%E7%AA%9D%20&style=social&up_message=link&url=https%3A%2F%2Fbot.pencilss.top%2F)](https://bot.pencilss.top/) [![Website](https://img.shields.io/website?label=%20%E9%A3%8E%20%E7%AA%9D%20&style=social&up_message=link&url=https%3A%2F%2Fbotapi.dead-war.cn%2F)](https://botapi.dead-war.cn/)

<details><summary>在领养/更新机器人中添加对应的参数如下：</summary>

- 昵称(长度>2)：机器人的名字，你可以叫他獭獭2号，或者自己起名字

- QQ账号：机器人QQ号

- 主人QQ：你自己的QQ号

- Access Token(长度>5)：自定义这个机器人连接时的认证码，可以任意但不得为空。后续会用到请务必记下。

- Tuling Token：是否采用自定义的图灵机器人token，如不使用请留空，将自动移交獭獭的聊天机器人。

</details>

填写完毕后点击添加机器人保存。

请注意，提交后修改要保证机器人QQ号和Token填写正确，如果遗忘了Token请进群联系群主。

## Step 2：选择机器人框架

可根据自身情况并参考[此文章](./choice.md)选择适合自己的客户端

---

# 占卜 

- **[win only]** mirai一键包自带占卜插件
- **[win only]** mcl/onebot-kotlin可自行加载**mirai_native**插件后，在群文件获得占卜插件的dll和json文件，放入`.\date\MiraiNative\plugins`文件夹即可
- **[win only]** 先驱可自行加载**cqxq**插件后，在群文件获得占卜插件的dll和json文件，再通过cqxq加载占卜插件
- **[all os]** 所有方式可以反向ws连接[基于nonebot重构的占卜插件](https://github.com/LittleNightmare/onebot_Astrologian_FFXIV)。**请注意nonebot的版本，v1 v2互不兼容。**

---

# 注意事项 

!>1. 拉机器人进入新群，或退出旧群后。可能需要使用`/bot update`来刷新机器人的群缓存 。  
2. 必须保持框架打开状态，机器人才在工作

---

# License 
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fyimo0908%2Feasy-build-otterbot.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fyimo0908%2Feasy-build-otterbot?ref=badge_large)