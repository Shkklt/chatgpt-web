# 玲珑-web 基于 ChatGPT-web版本改进，

支持web对于自研大模型的网页端展示与部署，后期还会添加图谱，天气与后台操作等。

纯JS实现的ChatGPT项目，基于OpenAI API

部署一个HTML文件即可使用。

支持复制/更新/刷新会话，语音输入，朗读等功能，以及众多[自定义选项](#自定义选项)。

参考项目: 
[markdown-it](https://github.com/markdown-it/markdown-it), 
[highlight.js](https://github.com/highlightjs/highlight.js), 
[github-markdown-css](https://github.com/sindresorhus/github-markdown-css), 
[chatgpt-html](https://github.com/slippersheepig/chatgpt-html), 
[markdown-it-copy](https://github.com/ReAlign/markdown-it-copy), 
[markdown-it-texmath](https://github.com/goessner/markdown-it-texmath), 
[awesome-chatgpt-prompts-zh](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)

## 自定义选项

- 左边栏支持，搜索会话，新建/重命名/删除(会话/文件夹)，浅色/深色/自动主题模式，导出/导入/重置会话和设置数据，显示API额度，显示本地存储。

- 可选用户头像，可修改为任意图片地址。

- 可选系统角色，默认不开启，有四个预设角色，并动态加载[awesome-chatgpt-prompts-zh](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)中的角色。
- 可选角色性格，默认灵活创新，对应接口文档的top_p参数。

- 可选回答质量，默认平衡，对应接口文档的temperature参数。

- 修改打字机速度，默认较快，值越大速度越快。

- 允许连续对话，默认开启，对话中包含上下文信息，会导致api费用增加。#由于服务郭晓，目前不支持

- 允许长回复，默认关闭

- 选择语音，默认Bing语音，支持Azure语音和系统语音，可分开设置提问语音和回答语音。

- 音量，默认最大。

- 语速，默认正常。

- 音调，默认正常。

- 允许连续朗读，默认开启，连续郎读到所有对话结束。

- 允许自动朗读，默认关闭，自动朗读新的回答。**（iOS需打开设置-自动播放视频预览，Mac上Safari需打开此网站的设置-允许全部自动播放）**

- 支持语音输入，默认识别为普通话，可长按语音按钮修改识别选项。**语音识别必需条件：使用chrome内核系浏览器 + https网页或本地网页。** 如点击语音按钮没反应，可能是未授予麦克风权限或者没安装麦克风设备。
