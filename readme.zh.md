<div align="center">
	<img width="500" height="350" src="media/logo.svg" alt="Awesome">
	<br>
	<br>
	<br>
	<br>
</div>
<br>
<br>
<br>
<br>
<br>

<div align="center">
	<h1>Awesome LLM Free APIs</h1>
</div>

<br>

<div align="center">
    <a href="readme.zh.md">中文</a>
    <span>|</span>
    <a href="readme.md">English</a>
</div>

<br>

<div align="center">
    <p>查看 <a href="https://github.com/jobsimi/awesome-llm-free-apis">Github</a> <span>| </span> <a href="https://gitee.com/jobsimi/awesome-llm-free-apis">Gitee</a> 以获取最新内容</p>
</div>

<br>

## 目录

- [目录](#目录)
- [术词](#术词)
- [APIs](#apis)
	- [仅限制 QPS](#仅限制-qps)
	- [易封 IP，限制模型](#易封-ip限制模型)
	- [限制 QPS、次数、模型](#限制-qps次数模型)
	- [限制总次数、tokens、RPM、PRD](#限制总次数tokensrpmprd)
	- [限制总次数、模型](#限制总次数模型)
	- [限制总次数、有效期](#限制总次数有效期)
	- [限制模型、并发、RPM、TPM、TPD](#限制模型并发rpmtpmtpd)
	- [限制模型、总 Tokens](#限制模型总-tokens)
	- [限制 QPS、模型](#限制-qps模型)
	- [限制模型、总 Tokens、有效期](#限制模型总-tokens有效期)

<br>
<hr>

## 术词

| 术词  |                                                                                                                        解释                                                                                                                        |
| :---: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Token | 文本生成模型以 Token 为基本单位来处理文本。Token 代表常见的字符序列。例如，单个汉字"夔"可能会被分解为若干 Token 的组合，而像"中国"这样短且常见的短语则可能会使用单个 Token。大致来说，对于一段通常的中文文本，1 个 Token 大约相当于 1.5-2 个汉字。 |
|  QPS  |                                                                                                           Queries Per Second, 每秒查询率                                                                                                           |
|  RPM  |                                                                                                         Requests Per Minute, 每分钟请求数                                                                                                          |
|  TPM  |                                                                                                         Tokens Per Minute, 每分钟 Token 数                                                                                                         |
|  TPD  |                                                                                                           Tokens Per Day, 每天 Token 数                                                                                                            |

## APIs

### 仅限制 QPS

- [智汇 API](https://cognihub.baystoneai.com) - 我是智汇 API，向开发者提供大模型推理 API，注册开发者账号后，即可获得 APPKEY，可以切换市面上所有主流大语言模型，兼容 OpenAI API

### 易封 IP，限制模型

- [gpt4free](https://github.com/xtekky/gpt4free) - 官方的 gpt4free 库 | 各种强大的语言模型的集合

### 限制 QPS、次数、模型

- [GPT_API_free](https://github.com/chatanywhere/GPT_API_free) - Free ChatGPT API Key，免费 ChatGPT API，支持 GPT4 API（免费），ChatGPT 国内可用免费转发 API，直连无需代理。可以搭配 ChatBox 等软件/插件使用，极大降低接口使用成本。国内即可无限制畅快聊天。

### 限制总次数、tokens、RPM、PRD

- [Coze](https://www.coze.com/docs/developer_guides/coze_api_overview) - Coze 是下一代人工智能应用和聊天机器人开发平台。不管你的编程经验如何，Coze 可以让你毫不费力地创建各种聊天机器人，并将它们部署到不同的社交平台和消息应用程序上。

### 限制总次数、模型

- [LLaMA3.1-8B](https://build.nvidia.com/explore/discover#llama-3_1-8b-instruct) - NVIDIA LLaMA3.1-8B 是一种大型语言模型，可用于各种自然语言处理任务，包括文本生成、翻译和问答。它是基于 LLaMA 体系结构，并在互联网上的大型文本数据集上进行训练。

### 限制总次数、有效期

- [DeepSeek](https://platform.deepseek.com/api-docs/zh-cn/) - DeepSeek API 使用与 OpenAI 兼容的 API 格式，通过修改配置，您可以使用 OpenAI SDK 来访问 DeepSeek API，或使用与 OpenAI API 兼容的软件。

### 限制模型、并发、RPM、TPM、TPD

- [Kimi](https://platform.moonshot.cn/docs/intro) - Moonshot 提供基于 HTTP 的 API 服务接入，并且对大部分 API，我们兼容了 OpenAI SDK。

### 限制模型、总 Tokens

- [ChatGLM](https://open.bigmodel.cn/dev/api#overview) - 智普清言大模型。人工智能 MaaS 平台。调用 GLM 模型 API 容易。快速构建人工智能应用程序。

### 限制 QPS、模型

- [Spark Lite](https://xinghuo.xfyun.cn/sparkapi#price) - 星火大模型 API：· 整体能力接近 GPT 4-Turbo，语音大模型效果领先 · 适用于各类业务场景，更提供大模型生命周期定制工具 · Lite 版本接入全免费，Pro/Max/Ultra 版本行业低价

### 限制模型、总 Tokens、有效期

- [Spark 4.0 Ulta 等等](https://xinghuo.xfyun.cn/sparkapi#price) - 星火大模型 API：最强大的星火大模型版本，效果极佳，全方位提升效果，引领智能巅峰，优化联网搜索链路，提供精准回答，强化文本总结能力，提升办公生产力
