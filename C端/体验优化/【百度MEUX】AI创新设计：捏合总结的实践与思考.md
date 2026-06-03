## AI创新设计：捏合总结的实践与思考

原创 MEUX 百度MEUX 2024年10月23日 18:30 北京

## 前言

随着AI技术的不断进步，用户对于信息获取的即时性、准确性及个性化程度均提出了更高的期望，而对于设计师的挑战则是如何利用设计思维和AI技术，帮助用户更高效地获取信息，同时打造出具有智能感知的新功能。

本文将结合百度APP近期上线的「捏合总结」功能，分享如何将AI能力与设计思维结合提升产品智能感知，从而优化用户体验，希望能为深耕AI方向的设计师们提供有价值的参考和启发。

## 背景现状

目前百度APP核心场景存在搜索结果选择多、长文阅读低效、视频获取信息慢等问题，导致用户获取信息效率低。为此，我们运用AI技术对内容进行总结提炼，构建了一个覆盖全场景的通用体验链路，即「捏合前引导 $\rightarrow$ 触发捏合 $\rightarrow$ 内容加载 $\rightarrow$ 结果展现」，以提高用户的信息获取效率。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/923c289bd4cf5aff1efb066a3b72e7927265d96b3f52cbb122d0e0aca5b29533.jpg)


## 现状问题


搜索结果页



搜索结果过多，难抉择


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/dce2ae0e312a71034f24ca34a3a91907d9d5f7dddb0f394f58e107dd572882cb.jpg)



三方落地页



内容质量参差，难阅读


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/d2ec17aedf1dc652fe08466bf3d0af88960465a7e4ce52e76a9af0d9322ee1a1.jpg)



图文落地页



长文难以迅速抓住要点


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/a4eac6886beb86a4b9ee81e04ff7cb6354863a2bf3982af880acadb4adc11880.jpg)


MELIX 


视频详情页



长视频费时，观看效率低


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/808d508d90f6623aedea7c729962271dbcc9741a1e5d522dfe4625b30bf135f9.jpg)


Step 1 

Step 2 

Step 3 


捏合前引导


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/149b4cb912eac90871720162c82e97502d99d83f47accf350bdf5795b748a3b0.jpg)



触发捏合


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/b0040ddf724a3b688c7e06fd4f77205343d43b4afad71c086b3b682f8e571b38.jpg)



内容加载


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/af72653d50ef087423c9d96ec631905734897a887fb77af44a7d655df09f58ce.jpg)



结果展现


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/14b90f8bc0b53f517a6e0b2a724a4be6a589c75746053799bd81589ccd532f5d.jpg)


设计协同业务团队围绕以下3个维度展开探索：

①亮点打造—搭建创新链路体验

②智能感知—打造AI智能化设计语言

③信息提效—结构化排版促信息获取

## 一、搭建创新链路体验

## 1. 手势创新 双指捏合触发方式

以兼容百度APP全场景为目标，我们从「功能入口触发」「手势触发」两种方式进行深入对比探索：

- 功能入口触发：在通用框架上增加AI总结入口，直观清晰；

- 手势触发：在触发手势的选择上，从各系统/平台手势规范（iOS和主流机型）和当前手势是否与端内存在冲突两个方面进行深入分析，将目光锁定在“双指捏合”手势上。

## 功能入口触发

优点：快速直观、不过多占用页面空间

缺点：识别性弱、限制框架信息展示、各场景入口位置不稳定

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/3b60a02ca10b19064fb0a090cf844c0b51a809caca39afea5610acae6312969e.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/e8cd7b6f231e1a50034717099915d8cfab9bff69371581c38804e8e2b86ec4b0.jpg)


## 手势触发

优点：自然交互表意清晰、全场景操作稳定

缺点：无外露入口，需要塑造捏合认知及是否有手势冲冲突

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/a33f13cb8756aff260c2b323476f438c2c52cf327a7c37035d6b70172806cd35.jpg)


VS 

通过实验验证，将AI入口嵌入通用框架的方式往往不够显眼，难以激发用户的兴趣，而采用双指捏合作为交互触发机制，不仅设计新颖，还在用户群体中获得了积极反响。

## 2. 精细化引导 建设用户捏合心智

在捏合功能缺乏明显入口的情况下，如何塑造用户捏合心智呢？

我们初步采用「全页面强阻断式引导」以强化用户对该功能的认知，但实验表明这种方法影响了用户获取信息的效率。因此，我们基于用户场景细化引导策略，针对“搜索结果、图文/动态、三方落地页、视频详情页和小程序页”5种页面类型，分别考虑捏合需求、内容可读性和AI文本质量来定制捏合前链路的引导策略。

数据分析显示，用户在搜索落地页和视频详情页的捏合需求最强烈。我们根据页面内容质量和可读性调整了引导强度，对质量低、可读性差的页面加强引导，而对高质量、易读的页面则减少引导。考虑到AI生成文本的质量差异，我们提高了生成文本质量高场景的引导权重。具体总结为以下几点：

- 搜索和视频详情页：用户需求强烈且AI总结质量高，采取强引导方案；

- 三方落地页：页面可读性差而AI总结效果好，选择中引导，以提升用户认知、优化阅读体验；

- 图文/动态落地页和小程序页：内容质量较高且用户捏合需求适中或较低，采用弱引导，以保持浏览体验。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/62b63f8bad60563d19cbd1e0414e0e1978e3b4f1cbe5880700a64cfa558e9194.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/437dda82fe7ba7194397feb9c4fff0c61e73907b2f5ce4f4bdfecd5ab63745dd.jpg)


## 3. 全页面容器 打造沉浸式浏览体验

使用全页面容器展示总结内容，充分利用屏幕空间，优化展示效果，同时增强用户互动和沉浸体验，营造专注而愉悦的阅读氛围。

## 4.动态反馈 丰富感受提升体验

用户执行双指捏合手势时，即时的震动反馈确认了操作的成功，此时用户还可以在界面上双指进行自由拖动，这不仅增加了互动乐趣，也让交互过程更加直观和丰富。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/5f78a4eb8212292b5be7a383153232aebfefe0dcd9d8fb608b420cccd17e4ead.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/b4697d994484c4acbca813cd3fe691d029c1321eb43d60d6825f93af082502ab.jpg)


## 二、打造AI智能化设计语言

在塑造用户体验的初始阶段，视觉元素扮演着至关重要的角色。我们的目标是打造一个智能且引人注目的用户界面，通过其新颖性来突出功能，同时提供一种创新的视觉体验，满足用户对人工智能和未来创新的期待。

## 设计关键词

MEUX 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/92e3a751630450fe4d09932e81ecd91689011eaa2f90132fd2ab0837bdb52e31.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/401d698c9180a774fa98ebd11481d37ce70cf77842803a975b1798a4caf9830d.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/4e709ea577d441fe6a7aa3c4284578b463e523a257f9cc422348da4844ea9910.jpg)


我们着手从智能符号、渐变色彩、表意动效三方面进行深入细化探索。

## 1. 智能符号 增强识别度

为强化AI感知，在界面中融入轻盈的「AI」品牌标识和象征智慧与知识的「星星」符号，使用户能够快速识别相关AI功能。

## 2.渐变色彩 传递科技感知

通过前期情绪版的构思发现，紫色可以传递科技的智能感觉，我们与百度APP的主题蓝色进行了不同效果的组合尝试，最终确定了蓝粉色的渐变效果，创造出一种现代且具有科技感的视觉效果，同时还能传递出AI产品的亲和力和情感智能，进而在用户心中建立起积极的形象。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/b3f261aba698ea0ba13246f5cefaaff6c9490ed6efeaa1b95ddcf735efbd6774.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/750d30a3576989897dc81afee27db7f943cde0aa224af965cc44415a9163aeb4.jpg)


## 3. 表意动效 传递AI抽象概念

动效在UI设计中扮演着至关重要的角色，它不仅能够丰富用户界面的视觉效果，还能极大地提升用户体验。

在捏合功能的设计中，我们利用动画来丝滑地呈现「触发捏合→内容加载」的过渡，从而保证①有效传递产品的智能感；②减少加载等待过程中用户的跳出率。

用户触发捏合功能后会经历「捏合松手后的容器转场」「AI内容的加载」两个关键阶段：

## 1）符合操作预期的容器转场效果

考虑到用户双指捏合的操作行为，采取当前页面跟随手指收缩的转场效果，更符合操作预期。

## 2）沉浸的加载动画

加载动画的目的是为了缓解AI内容生成时用户等待的焦虑感，降低用户的跳出率。结合AI汇总整合分析内容的原理，为缩小后的容器设计了呼吸般的缩放律动效果，辅以页面内波纹同步扩散的效果，模拟AI的思考动态，增加页面沉浸感，营造出一个既智能又富有动感的视觉体验。

在搜索场景的生成页中，增加了更为直观的分析动画，将AI的资料搜集、整合和分析过程具象化呈现，帮助用户理解AI工作的过程。通过直观的骨架屏效果，不仅让页面看起来更加充实，也帮助用户建立预期，从而降低跳出率。

## 3）渐进式披露动态效果

在总结文本的展示上使用打字机效果，搭配渐进式披露的策略，可以更快速地对生成后的内容进行呈现。相较于逐字打字机效果，这种方式不仅提升了信息展示的效率，还增加了页面的律动感。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/4ad8675bb4ea60b1fda4c09e002da67bce3ad1a1e9e5c28e9ebecd1641a7da8e.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/1f1b82c0811dc1286f6e255fa524a4a45b21ad4b5e099e31d6966fbb52d30b10.jpg)


## 三、结构化排版促信息获取

为保证AI总结生成内容的浏览清晰度，我们针对信息层级与模块结构进行了打磨，确保为用户提供一个舒适的浏览体验。

## 1. 结构布局

采用总分结构展示信息，显著提高了内容的易读性和用户阅读效率。通过视觉层次和逻辑顺序，向用户提供了一条易于理解和遵循的信息流，进而提升整体阅读体验。

通过在页面的多个模块间设置宽敞的间距，使浏览过程更为舒适，同时增强了页面的节奏感和呼吸空间。简约的灰色背景与图标、文字之间形成了鲜明的层级关系，使内容突出而清晰，保证了视觉的统一性和简洁性。

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/cf363905071d34fefbb925cbaa6aa5c50fe30d23bbb770586ba948dd3cf78a01.jpg)



结构布局


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/e9c8cb16e9466e10d8ec66a654898d6694d77efe929c7f542afbc963dfc8b162.jpg)


## 2. 内容激发

根据不同类型的页面，底部可以搭配「相关推荐」或「大家还在搜」模块，提供更加个性化的浏览体验。

- 

## 内容激发

MEUX 


内容来源


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/a35129826d5dececad1b97adbb56b47ee6bf65a77f33da86248ce8f2601d6c41.jpg)



相关推荐


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/ea9e0500288ec20ac85cb4b8de40f81a169251e78bbcdf1e833bc0d811070cd1.jpg)



大家还在搜


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/40f537daa7ae0e33c0fb7b14bf968afd9371435223bbf5ff82d632a0d5088ed1.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/83aafc26b42ba4ec63da277ed19650f39a9699e8d65a1f8749e4a3f5ca94a5b7.jpg)



相关推荐


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/3d48990cd4ae16e54ea6bf814c369f02f88889f2b6cc09249d6f99d8a4db5693.jpg)



Q 大家还在搜


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/6dc5544fc2adbcf1f52e1f8dac2d72f6b183424a417df6bad714691d024f0b6a.jpg)


(1) 

项目范围

广力云

(1) 

开户详情介绍

2014年四季度利润分配方案公告

苏州金蓝易开期满

2.2.1 发布式存款明细

去苏州定制的利弊

法定代表人及邮政编码

## 3.图标匹配策略

根据文本的主题、内容和上下文，使用图标辅助增强信息的表达效果，提升用户理解度，使信息传递更为直观、生动和高效。图标匹配策略不仅有助于突出关键信息，还可以提升整体的视觉美感和用户体验。

● 

## 图标匹配策略

MELIX 


图标&分点映射关系


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/90a12b6e269bc452f30bba428e92c304b899c75360c7cdec46963a8622dcfe93.jpg)



生物类


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/bbf5637763e379edf450b3b670f44aa427ebfd9524adc905a53a81bfef90f400.jpg)


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/1a3315928c3dcbb51f2a6dea25170f88356c62d058688b60d38448373330198d.jpg)



购买要求


非苏州户籍在苏州六区购买首套房无需开具纳税证明及社保。


创新发展类


![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/b80ddb53432d158a48e9c8c68117198e0a8f063fb6cea72b2cb4f6d8c72d1ed5.jpg)



贷款追偿


苏州没有住房：不论外地有无须严格登记证，均20%时间，有效期3年。

项目启动

单位：美元 价格：港元/吨 2017年1月26日

## 写在最后

在本次百度APP捏合项目创新探索中，我们将设计思维与AI能力进行创新结合，解决产品原有的体验问题，在这个过程中我们尝试结合用户认知塑成模型，总结以下几点：

- 「发现理解」降低用户学习成本：贴合用户场景的多种功能精细化引导形式；

- 「实施行动」降低用户操作成本：从行为链路上塑造新颖且易用的双指触发交互模式；

- 「接受反馈」降低用户接受成本：使用流畅的动画和触感反馈完成各环节的流畅过渡；

- 「形成认知」塑造产品智能感知：定义轻盈灵动的智能设计语言和清晰的结构化排版强化用户的心智。

通过以上方式，帮助用户在使用功能的过程中逐渐形成「会用→好用→爱用」的心智，从而为用户建立全新的AI产品认知，助力功能发布，逐步提升功能的使用量。


结合用户认知塑成模型优化体验


MEUX 

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/286e7cb8a1bd20497294247cc6d85c26064f2e30ff04f8b4f03cb0b7fb17b5cf.jpg)


本次项目也使我们对产品AI重构产生了一些新的理解，未来百度APP的AI体验将向着交互方式更加自然、视觉语言更加轻盈的方式进行持续探索，也希望本文能为其他正在进行产品AI重构的设计师们带来一些新的启发。

感谢阅读，以上内容均由百度MEUX团队原创设计，以及百度MEUX版权所有，转载请注明出处，违者必究，谢谢您的合作。申请转载授权后台回复【转载】。

也欢迎加入MEUX,交互/视觉/用研

可投简历至meux-talent@baidu.com

(注明信息获取来源如：公众号)

以下文章，你可能也感兴趣

![image](https://cdn-mineru.openxlab.org.cn/result/2026-06-03/0f68b183-c78b-4ca0-90ca-d7dc926870a2/4244f9729284c113d0db97824885952e94e5362d14322afd4150f0995930195c.jpg)


探究大学生眼中理想的AI对话产品

MEUX 「九月」 AI设计观察

娱乐加倍！百度奥运燃情开赛

从对话到嵌入：多元场景AI形态浅析