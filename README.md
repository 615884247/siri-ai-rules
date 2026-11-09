# siri ai分流规则

按用户提供的图片整理的 Loon 远程规则，共 36 个域名，顺序与图片一致。

规则文件：[`siri-ai.list`](siri-ai.list)。每条使用 `DOMAIN` 精确匹配，保留原图中的点和连字符。

## Loon 订阅

订阅链接：<https://raw.githubusercontent.com/615884247/siri-ai-rules/main/siri-ai.list>

在 Loon 中新增远程规则，填写此文件的 GitHub Raw 链接，名称填写 `siri ai分流规则`，然后选择要使用的节点或策略组并启用。

规则文件不固定节点或策略组。为确保优先匹配，请将这条订阅放在可能匹配这些域名的其他 Apple、iCloud 规则之前。

这份清单按原图收录，包含天气、iCloud 等相关域名；不代表其中每个域名都仅供 Siri AI 使用，也不保证导入后能解除设备、账户或地区限制。

语法参考：[Loon 订阅规则](https://nsloon.app/docs/Rule/sub_rule/)。
