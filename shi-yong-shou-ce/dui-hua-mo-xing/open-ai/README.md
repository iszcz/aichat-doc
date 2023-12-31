---
description: 简要
---

# 1⃣ Open AI

{% hint style="warning" %}
OpenAI 模型是非确定性的，这意味着相同的输入可能会产生不同的输出。

将`temperature`设置为0可使输出大部分确定性，但可能仍会存在一小部分的变异性。
{% endhint %}

## [GPT-4](gpt-4.md)

`GPT-4` 是一个大型多模态模型（接受文本输入并发出文本输出，未来将出现图像输入），由于其更广泛的常识和先进的推理，它可以比我们以前的任何模型更准确地解决难题能力。对比`gpt-3.5-turbo`，`GPT-4` 针对聊天进行了优化。在我们的GPT指南中了解如何使用 `GPT-4` 。

| 模型名称           | 描述                                                            | MAX Tokens    |
| -------------- | ------------------------------------------------------------- | ------------- |
| GPT-4          | 比任何 GPT-3.5 模型都更强大，能够执行更复杂的任务，并针对聊天进行了优化。                     | 8,192 tokens  |
| GPT-4-0613     | 2023 年 6 月 13 日的快照。与 `gpt-4`不同的是，该模型不会收到更新，并且会在新版本发布 3 个月后弃用。 | 8,192 tokens  |
| GPT-4-32k      | 与基本`gpt-4`模型具有相同的功能，但上下文长度是其 4 倍。将使用我们最新的模型迭代进行更新。            | 32,768 tokens |
| GPT-4-32K-0613 | 2023 年 6 月 13 日的快照。上下文是标准模型的 4 倍，该模型不会收到更新，并将在新版本发布 3 个月后弃用。  | 32,768 tokens |

对于许多基本任务，`GPT-4` 和 `GPT-3.5` 模型之间的差异并不显著。然而，在更复杂的推理情况下，`GPT-4` 比我们之前的任何模型都更有能力。

## [GPT-3.5](gpt-3.5.md)

{% hint style="info" %}
我们建议使用`gpt-3.5-turbo`，因为它具有更低的成本和改进的性能。
{% endhint %}

GPT-3.5模型可以理解并生成自然语言或代码。我们 GPT-3.5 系列中功能最强大且最具成本效益的模型`gpt-3.5-turbo`已针对聊天进行了优化，同时也适用于传统的完成任务。

| 模型名称                   | 描述                                                                      | MAX Tokens    |
| ---------------------- | ----------------------------------------------------------------------- | ------------- |
| GPT-3.5-turbo          | 最强大的 GPT-3.5 模型，并针对聊天进行了优化。将在发布后两周更新我们最新的模型迭代。                          | 4,096 tokens  |
| GPT-3.5-turbo-16k      | 与标准`gpt-3.5-turbo`模型具有相同的功能，但上下文是标准模型的 4 倍。                             | 16,384 tokens |
| GPT-3.5-turbo-0613     | 2023 年 6 月 13 日的快照，`gpt-3.5-turbo`包含函数调用数据。该模型不会收到更新，并且会在新版本发布 3 个月后弃用。 | 4,096 tokens  |
| GPT-3.5-turbo-16k-0613 | 2023 年 6 月 13 日的快照。上下文是标准模型的 4 倍，该模型不会收到更新，并将在新版本发布 3 个月后弃用。            | 16,384 tokens |

