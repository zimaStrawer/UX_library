# 大厂实战案例！京东物流AI问答助手体验设计完整复盘

> 原文链接：https://www.uisdc.com/ai-q-a-assistant
> 作者/团队：京东JellyDesign 团队
> 日期：2024/04/16
> 标签：未提供
> 本地归档说明：为尊重原站版权，此文件不逐字转载全文；保留原文链接、图片引用、筛选理由和关键内容线索，方法沉淀见 ux-method-library。

## 筛选理由

京东物流 AI 问答助手复盘，适合沉淀服务型 AI 助手的问题识别、答案组织和信任反馈。

## 关键内容线索

1. AI 在项目中主要有两大作用，一是作为技术支撑，在产品实现功能时借助 AI 技术提供预测数据、推荐数据，从而帮助企业预测/预警风险发生，提前实现调度工作，减少重复劳动，帮助企业实现降本增收。
2. 另一个则是用户通过键盘或者语音输入，对系统发出指令，AI 通过对语言识别去回答用户问题，这类主要用于客服或者知识问答，利用 AI 技术减少人工成本，减少重复劳动力，同时能将知识类文档进行收口，形成企业知识库。
3. 本文主要围绕设计师如何利用 AI 技术赋能物流行业。
4. 2. 当代人机对话的主要形态与特点 AI 智能问答主要通过人机对话实现，其核心本质是自然语言与计算机进行交互，人机对话主要分为 3 种形态：闲聊型、问答型、以及任务型。
5. 物流行业的知识问答更多专业领域问答，偏向于问答型以及任务型，因此对于准确率要求非常高，其次是情感要求。
6. 所以在给出答案时需遵守一个答案原则“宁可无答案、不可有错误答案”，其次在用户问题不清晰时，话术上进行二次引导，方便用户补充信息内容。
7. 二、物流场景下 AI 智能问答的重要性 1. 物流行业的特点 ①业务复杂性： 在物流行业中，B 端业务场景复杂多变，涉及大量的业务操作指导文档。
8. 然而，当前缺乏统一的知识整合与呈现机制，使得用户在获取和使用信息时面临诸多不便，增加了业务操作的难度和成本。
9. ②信息传递会产生缺失： 由于业务属性和特殊需求的多样性，用户遇到疑问时往往依赖于线下一对一或拉群沟通。
10. 这些解答方案多基于个人经验而非专业准确的业务知识，导致问题解答时间长且准确性存在偏差。

## 原文图片

![原文图片 1](https://image.uisdc.com/wp-content/uploads/2024/04/ysbanner-202300413-2-1.jpg)

![原文图片 2](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-24.jpg)

![原文图片 3](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-23.jpg)

![原文图片 4](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-22.jpg)

![原文图片 5](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-21.jpg)

![原文图片 6](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-20.jpg)

![原文图片 7](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-19.gif)

![原文图片 8](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-18.jpg)

![原文图片 9](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-17.jpg)

![原文图片 10](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-16.jpg)

![原文图片 11](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-15.jpg)

![原文图片 12](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-14.jpg)

![原文图片 13](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-13.jpg)

![原文图片 14](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-12.jpg)

![原文图片 15](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-11.jpg)

![原文图片 16](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-10.jpg)

![原文图片 17](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-9.jpg)

![原文图片 18](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-8.jpg)

![原文图片 19](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-7.jpg)

![原文图片 20](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-6.jpg)

![原文图片 21](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-5.jpg)

![原文图片 22](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-25.jpg)

![原文图片 23](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-4.jpg)

![原文图片 24](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-3.jpg)

![原文图片 25](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-2.jpg)

![原文图片 26](https://image.uisdc.com/wp-content/uploads/2024/04/uisdc-wl-20240413-1.jpg)

![原文图片 27](https://image.uisdc.com/wp-content/uploads/2019/10/uisdc-cx-20191021-1.jpeg)

![原文图片 28](https://image.uisdc.com/wp-content/uploads/2026/04/20260410-uisdcbanner-aikt.webp)
