# Seedance 2.5 多语言样例目录

[120 场景索引](../README.md) · [English Guide](../../README.md) · [中文指南](../../README_ZH.md)

bestimage.ai 团队维护 **15 种语言的样例覆盖**：简体中文对应主库中的6个场景，另外14份语言文件各含这6个场景的完整译文。不是每种语言都有120条；翻译不重复计入唯一场景数。新增101–120另有完整[英文](../production-workflows.en.md)与[简体中文](../production-workflows.zh.md)版本。

源内容并非全部英语：主库01–60是中文，61–100是英文；共享六例以修订后的中英场景为依据，保持输入、时序与限制一致。

## 语言文件

| 语言 | 六例入口 | 方向 |
| --- | --- | --- |
| 简体中文 | [主库04、31、37、43、46、52](../README.md) | LTR |
| 繁體中文 | [繁體中文](prompt-library.zh-TW.md) | LTR |
| English | [English](prompt-library.en.md) | LTR |
| 日本語 | [日本語](prompt-library.ja.md) | LTR |
| 한국어 | [한국어](prompt-library.ko.md) | LTR |
| Español | [Español](prompt-library.es.md) | LTR |
| Français | [Français](prompt-library.fr.md) | LTR |
| Deutsch | [Deutsch](prompt-library.de.md) | LTR |
| Português do Brasil | [Português do Brasil](prompt-library.pt-BR.md) | LTR |
| العربية | [العربية](prompt-library.ar.md) | RTL |
| Русский | [Русский](prompt-library.ru.md) | LTR |
| Bahasa Indonesia | [Bahasa Indonesia](prompt-library.id.md) | LTR |
| Italiano | [Italiano](prompt-library.it.md) | LTR |
| ไทย | [ไทย](prompt-library.th.md) | LTR |
| Tiếng Việt | [Tiếng Việt](prompt-library.vi.md) | LTR |

## 六个共享场景

| 样例 ID | 主库 ID | 场景 | 检查重点 |
| --- | --- | --- | --- |
| I18N-01 | 04 | 陶瓷滤杯的一次注水 | 六道筋棱、滤纸、液体连续性与注水声 |
| I18N-02 | 31 | 双面衬衫外套的风与布料 | 身份、纽扣与口袋数量、风向、自然落布 |
| I18N-03 | 37 | 阅读应用保存一段高亮 | 已批准屏幕、文字、单次选择与保存 |
| I18N-04 | 43 | 融雪的地表径流与下渗 | 教师审核示意、箭头、科学表述边界 |
| I18N-05 | 46 | 狭长庭院住宅的真实动线 | 平面、门洞、实际行走路径与尺度 |
| I18N-06 | 52 | 猫咪自愿进入航空箱 | 动物福利、毛色、箱体几何与自愿动作 |

## 本地化规则

1. `Image 1`、`Video 1`、`Audio 1` 等素材编号保持固定，必须与上传顺序一致。
2. 镜头方向、动作、音频、一致性和禁止项要一起翻译，不能只翻译风格词。
3. 需要出现在画面中的文字必须放在引号中，并注明目标语言；不需要文字时明确写“无字幕、无伪文字”。
4. 产品几何、界面字段、型号、文件名和已批准的品牌拼写不应自由改写。
5. 阿拉伯语等 RTL 内容要单独定义阅读方向；镜头左右方向不要因为文字方向自动镜像。
6. 涉及服装、手势、食物、建筑、地理、无障碍、健康或公共安全时，应由熟悉当地语境的人复核。

## 人工检查

- 每个语言版本是否保留了相同的素材职责；
- 对白是否自然，口型与语速是否适合目标语言；
- UI、标点、数字和单位是否准确；
- 是否意外删除了版权、安全或一致性限制；
- 是否生成了不必要的字幕、商标、价格或事实声明；
- RTL 版本的 UI 阅读方向与镜头空间方向是否分别处理。

## 模型入口与语言

各语言README和样例使用经核对的 **英文** bestimage.ai页面，不自行拼接语言前缀：[Seedance文生视频](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/)、[图生视频](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/)、[参考生视频](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/)、[GPT Image 2静态图准备](https://bestimage.ai/models/openai/gpt-image-2/)。参考生视频需要至少一段视频；GPT Image 2不是视频接口。详见[API指南](../../docs/bestimage-ai-api-guide.md)。
