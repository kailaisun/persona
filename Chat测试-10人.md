# Chat 测试：Persona 1M · 10 人

使用 Persona 1M 公共数据集随机抽取 10 人（种子 123），让每个 persona 使用 OpenRouter GPT-4o-mini 与 Acme 模拟客服进行订单延迟对话。

## 结果

- 任务：`example-chat-api_support_chatbot`
- 每人：6 轮对话
- 校验：10/10 通过，0 异常
- 输入 tokens：231,077（其中缓存 175,616）
- 输出 tokens：3,837
- OpenRouter 实际费用：$0.02379255
- 需求满足：10 人均为“部分满足”
- 个人偏好满足：5 人“部分满足”、4 人“不满足”、1 人“满足”
- 平均体验评分：4.6/6

## Persona 汇总

| Persona | 来源 | 体验评分 | 个人偏好满足 |
|---|---|---:|---|
| Priya Sharma | Wiki | 5/6 | 部分满足 |
| Noah Williams | Wiki | 4/6 | 不满足 |
| Jordan Okafor | Amazon | 4/6 | 不满足 |
| Jordan Patel | Wiki | 5/6 | 不满足 |
| Ava Lee | GSS | 4/6 | 不满足 |
| Omar Haddad | Wiki | 5/6 | 部分满足 |
| Priya Mehta | Synthetic | 4/6 | 不满足 |
| Noah Patel | Wiki | 5/6 | 部分满足 |
| Valentina Santos | Synthetic | 5/6 | 部分满足 |
| Mateo Garcia | Wiki | 6/6 | 满足 |

任务校验通过表示输出符合任务格式；它不代表客服体验本身没有问题。完整原始结果保存在本地运行目录中。
