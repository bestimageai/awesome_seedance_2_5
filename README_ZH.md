<p align="center">
  <a href="https://bestimage.ai/"><img src="assets/bestimage-logo.svg" width="72" alt="bestimage.ai 标志"></a>
</p>

# Awesome Seedance 2.5 提示词

**120个视频创作方案，包含按时间划分的动作、明确的参考素材角色、声音设计和连续性检查。** 由 **[bestimage.ai 团队](https://bestimage.ai/)** 整理、改编和维护。

[![提示词](https://img.shields.io/badge/Prompts-120-blue)](prompts/README.md)
[![Seedance 2.5 API](https://img.shields.io/badge/Seedance_2.5_API-bestimage.ai-5D63FF)](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/)
[![GPT Image 2 API](https://img.shields.io/badge/GPT_Image_2_API-Image_preparation-5D63FF)](https://bestimage.ai/models/openai/gpt-image-2/)
[![欢迎贡献](https://img.shields.io/badge/Contributions-welcome-green)](CONTRIBUTING.md)
[![MIT许可](https://img.shields.io/badge/License-MIT-green)](LICENSE)

[English](README.md) · [简体中文](README_ZH.md) · [日本語](README_JA.md) · [Español](README_ES.md) · [Français](README_FR.md) · [Deutsch](README_DE.md) · [한국어](README_KO.md) · [Português](README_PT.md) · [Italiano](README_IT.md) · [15种语言覆盖范围](prompts/i18n/README.md)

![傍晚，一名文物修复人员将一个陶碗放入博物馆藏品抽屉](assets/seedance-2-5-cover.png)

*场景101的静态概念图，由 Codex ImageGen 制作，并非 Seedance 视频输出。生成方案与局限记录在[图片说明](assets/IMAGE_PROMPTS.md)中。*

本库涵盖产品视频、电商、创作者内容、教育、建筑、以声音推动的叙事、动画、参考素材控制和编辑方案。文字是否准确、物理运动、身份一致性、时间节奏和音画同步，都必须检查实际输出。

## 找到适合的起点

| 你的任务 | 从这里开始 |
| --- | --- |
| 叙事、产品、UGC、动画或镜头控制场景 | [01–24：中文基础库](prompts/prompt-library.md) |
| 商业、界面、教育、建筑、出行或公共服务内容 | [25–60：中文扩展库](prompts/extended-scenarios.md) |
| 应用流程、创作者课程、产品组装、展馆工作和游戏概念 | [61–72：英文专业工作流](prompts/advanced-workflows.en.md) |
| 匹配剪辑、一镜到底、参考图板、局部编辑、延长和预演 | [73–100：英文创作技法](prompts/creative-techniques.en.md) |
| 藏品、产品演示、教学与制作相关的20个新增方案 | [101–120：英文](prompts/production-workflows.en.md) / [简体中文](prompts/production-workflows.zh.md) |
| 完整的标题、模式和入口链接列表 | [120个场景索引](prompts/README.md) |
| 使用你所用语言的六个共用场景 | [语言目录](prompts/i18n/README.md) |
| 根据已有输入素材选择方案 | [用途对照表](docs/use-case-matrix.en.md) |
| 改善时间节奏、镜头、声音或连续性指令 | [提示词与问题排查指南](docs/prompting-guide.md) |

## 使用 bestimage.ai 创作

[bestimage.ai](https://bestimage.ai/) 提供图像和视频模型页面，方便探索工作流程并查看串接要求。请根据实际拥有的素材选择入口。下方链接打开的均为**英文页面**。

| 模型／用途 | 入口 | 需要准备什么 |
| --- | --- | --- |
| Seedance 2.5：从概念或文字分镜开始 | [文本转视频API](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/) | 包含主体、分时动作、镜头和声音的导演方案 |
| Seedance 2.5：让首帧动起来 | [图片转视频API](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) | 必需的首帧图片；可选的匹配尾帧图片 |
| Seedance 2.5：由参考素材引导创作 | [参考素材转视频API](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) | 至少一个必需的参考视频，以及可选的图片和音频 |
| GPT Image 2：为后续视频流程准备静态图像 | [GPT Image 2 API](https://bestimage.ai/models/openai/gpt-image-2/) | 用于概念图、角色设定图或分镜图的独立图像提示词 |

**GPT Image 2 是图像工作流程，不是 Seedance 视频端点。** 生成的参考图片在用于视频请求前，仍需进行视觉检查和权利审核。只有图片的参考图板，不能满足 bestimage.ai 参考素材转视频入口必需的视频输入要求。

请阅读 [bestimage.ai 模型与API工作流程指南](docs/bestimage-ai-api-guide.md)，了解输入素材角色、API接入，以及生成、编辑和延长之间的区别。bestimage.ai 的API基础URL为 `https://api.flaq.ai`，请使用在 bestimage.ai 账户中获取的API密钥。

## 如何理解数量统计

- **120个独立场景：** 24个基础场景 + 36个扩展场景 + 12个专业场景 + 28个技法场景 + 20个新增方案。
- **核心语言分布：** 60个中文场景和40个英文场景。20个新增场景均提供完整的英文版和简体中文版。
- **15种语言的样例覆盖：** 14份在地化文件提供六个共用场景，并对应简体中文主目录中的版本。这不代表每种语言都有120个翻译后的提示词。
- **五张新插图：** 一张封面和四张参考图／概念图，其中包括一张四格图板。译文、分格画面、变体和章节分段不计为额外的独立提示词。
- 本库不附带参考视频或录音。指令中出现 `Video 1` 或 `Audio 1`，意味着必须实际提供对应素材。

## 怎样让这些提示词便于使用？

[Seedance 2.5 官方页面](https://seed.bytedance.com/en/seedance2_5)介绍了更长的音视频生成、参考素材控制和编辑能力。模型提供方具备的能力，与某项服务实际开放的控制项并不相同：不要假定每一种编辑或延长操作都有对应的 bestimage.ai 端点。

实用的方案会让每一项行为要求都可被观察和检查：

```text
[模式] 文本转视频／图片转视频／参考素材转视频／受支持的编辑操作
[目标] 受众、用途、目标时长、构图
[参考素材] 为每份提供的图片、视频或音频指定一个明确角色
[固定要素] 身份、几何形状、物体数量、布局、光线方向
[时间轴] 建立场景 → 动作 → 结果 → 最终画面
[镜头] 起点、路径、速度、焦点、停止位置
[声音] 对白、环境音、拟音、音乐、同步提示
[检查] 哪些内容必须保持不变，哪些问题会使输出不可接受
```

时间轴表达的是创作意图，不保证逐帧精确执行。发布前，请据此检查实际结果。

## 三个以参考素材为起点的场景

### 陶瓷咖啡滤杯——场景04

![钴蓝色六面陶瓷滤杯装有干咖啡粉，下方是空的透明分享壶](assets/ceramic-dripper-reference.png)

一次受控注水：固定产品几何形状，让液体逐渐积累，声音保持克制，以干净的画面收尾。[完整英文提示词](prompts/i18n/prompt-library.en.md#i18n-01-ceramic-coffee-dripper-one-controlled-pour) · [中文主目录](prompts/prompt-library.md#04-陶瓷滤杯的一次注水)

### 毛毡水獭归还图书——场景10

![迷你图书馆里，一只围着蓝色围巾的毛毡水獭站在推车和绿色图书旁](assets/felt-otter-reference.png)

一个具有触感的动画方案，包含可见的车轮运动、有支撑的抬举动作、明确的书架目的地和安静的结尾。[完整中文提示词](prompts/prompt-library.md#10-毛毡水獭的夜间归书)

### 潮位站交接——场景01

![平静的潮位站里，两名分别穿黄色和藏蓝色外套的研究人员与一个银色箱子](assets/tide-station-reference.png)

以一次箱子交接为基础的克制叙事，保持稳定的空间关系，并设计明确的最终视角。[完整中文提示词](prompts/prompt-library.md#01-潮位站的晨间交接)

以上三张图片均为使用 Codex ImageGen 新制作的静态概念参考图，不是目标模型的测试输出。它们展示预期构图，不证明时间上的连续性。[显微镜参考图板](prompts/creative-techniques.en.md#microscope-reference-board)展示了场景73、75和100中各自独立的参考素材角色。

## 实用创作步骤

1. 选择场景，并确认所用服务实际开放该场景要求的模式。
2. 提供已获授权的素材，并保留上传顺序。参考素材可以控制身份、动作、环境或声音；请明确指定具体用途。
3. 将目标时间轴与所选时长匹配。对于图片转视频，应按预期构图准备输入图片，不要编造未受支持的宽高比参数。
4. 先测试一个有限动作，再加入镜头运动和声音。每次迭代只改变一个变量。
5. 逐帧检查几何形状、身体结构、可读文字、物体数量、物理接触和编辑区域边界。音频与延长衔接点应单独检查。
6. 当生成过程无法可靠保留精确内容时，在后期加入标题、声明、署名和在地化界面文案。

## 贡献可复现的示例

请使用[贡献指南](CONTRIBUTING.md)和附带的[提示词提交模板](.github/ISSUE_TEMPLATE/prompt.yml)。提交已测试的提示词时，请附上完整提示词、实际服务方／模型、设置、按顺序列明的参考素材角色、真实输出，以及迭代说明。不要提交机密信息、未获许可的媒体、未经授权的肖像、隐性广告或捏造的性能证据。


模型官方资料：[Seedance 2.5](https://seed.bytedance.com/en/seedance2_5) · [Seedance 2.5 — ByteDance](https://seed.bytedance.com/en/blog/one-take-creation-flexible-referencing-introducing-seedance-2-5).

## 关于 bestimage.ai

本提示词库由 [bestimage.ai](https://bestimage.ai/) 团队整理与维护，将实用创作流程与图像、视频模型 API 连接起来。

## 加入 bestimage.ai 联盟推广计划

制作教程、分享提示词或发布 API 集成案例？加入 [bestimage.ai 联盟推广计划](https://bestimage.ai/affiliate-program/)，向你的受众推荐 bestimage.ai，并获得推荐佣金。

- 受推荐用户的首笔有效付费订单，佣金为 **20%**。
- 该用户**注册后 60 天内**的后续有效付费订单，佣金为 **10%**。

订单资格与结算以[现行联盟协议](https://bestimage.ai/affiliate-agreement/)为准。

## 许可证

[MIT](LICENSE).
