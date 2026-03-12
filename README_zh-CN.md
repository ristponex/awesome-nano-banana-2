<div align="center">

# 🍌 Awesome Nano Banana 2

**Google Nano Banana 2 图像生成终极指南**

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Stars](https://img.shields.io/github/stars/your-org/awesome-nano-banana-2?style=social)](https://github.com/your-org/awesome-nano-banana-2)

精心整理的 **Nano Banana 2** 资源、提示词、工具和指南合集 —— Google Gemini 3.1 Flash Image 模型，公认最快的 AI 图像生成器。

**[English](./README.md)** | **[简体中文](./README_zh-CN.md)** | **[日本語](./README_ja.md)** | **[한국어](./README_ko.md)**

---

### 🚀 Nano Banana 2 图像生成低至 $0.072/次 —— 2K/4K 比 Google 官方更便宜！

**[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)** 提供所有分辨率（最高 4K）统一 $0.072 定价 —— 4K 图片比 Google 官方**便宜 52%**。无内容审查限制。所有 Google 模型可用。首次充值**赠送 25%**！

**[👉 立即开始生成](https://www.atlascloud.ai?ref=JPM683)**

> 🔒 **企业级安全保障** — Atlas Cloud 已通过 **SOC I & II 认证** | **HIPAA 合规** | 美国公司，99.9% 正常运行时间 SLA。

> 💳 **支付便捷** — 支持微信支付、支付宝直接付款，无需国际信用卡。

---

</div>

## 📑 目录

- [什么是 Nano Banana 2？](#-什么是-nano-banana-2)
- [核心功能对比](#-核心功能对比)
- [快速开始](#-快速开始)
- [提示词合集](#-提示词合集)
  - [超写实摄影](#超写实摄影)
  - [数字艺术与插画](#数字艺术与插画)
  - [产品与商业](#产品与商业)
  - [文字与排版](#文字与排版)
  - [图像编辑](#图像编辑)
  - [NSFW / 艺术人体](#nsfw--艺术人体)
  - [梗图与病毒式内容](#梗图与病毒式内容)
- [提示词工程指南](#-提示词工程指南)
- [价格深度对比](#-价格深度对比)
- [Atlas Cloud 上的 Google 图像模型全家桶](#-atlas-cloud-上的-google-图像模型全家桶)
- [官方资源](#-官方资源)
- [社区资源](#-社区资源)
- [常见问题](#-常见问题)
- [Star 历史](#-star-历史)
- [贡献指南](#-贡献指南)
- [许可证](#-许可证)

---

## 🍌 什么是 Nano Banana 2？

**Nano Banana 2** 是 Google 最新的图像生成与编辑模型，于 **2026 年 2 月 26 日**发布。基于 Gemini 3.1 Flash 架构构建，它是 Gemini App 中的默认图像生成模型（支持快速、思考和专业三种模式）。社区亲切地称之为"Nano Banana 2"——这个昵称源自早期测试者，随后在 Hacker News 和社交媒体上迅速走红。

### 演进时间线

```
2025年8月          2025年11月              2026年2月
    │                  │                      │
    ▼                  ▼                      ▼
Nano Banana ──► Nano Banana Pro ──► Nano Banana 2
 (第一代)          (专业版)            (当前一代)
                                      4K · 14张参考图
                                      Google 搜索集成
```

### 核心能力

- **图像生成与编辑** —— 从文本生成图像或使用自然语言指令编辑现有图像
- **512px 到 4K 输出** —— 从快速草稿到超高分辨率商用素材
- **最多 14 张参考图** —— 前所未有的混合、融合和风格迁移控制能力
- **集成 Google 搜索** —— 实时获取品牌标志、时事热点、流行趋势和事实性视觉内容
- **闪电速度** —— 公认最快的 AI 图像生成器，支持实时创作工作流
- **文字与排版** —— 同类最佳的图像内文字渲染能力

### 为什么叫"Nano Banana"？

"Nano Banana"这个昵称源自 Google 在早期测试中泄露的内部代号。社区立刻接受了它——"Nano"反映了模型极快的推理速度，"Banana"则成为对模型在 Alpha 阶段带有黄色调试水印的有趣引用。这个名字就此流传开来，Google 最终也在官方博客中承认了它。

### 与竞品对比

| 维度 | Nano Banana 2 | Flux Dev | SDXL | Midjourney v7 | DALL-E 3 |
|------|--------------|----------|------|---------------|----------|
| **最大分辨率** | 4K | 2K | 1K | 2K | 1K |
| **速度** | ⚡⚡⚡ | ⚡⚡ | ⚡ | ⚡⚡ | ⚡ |
| **参考图数量** | 14 | 1 | 1 | 4 | 1 |
| **图像编辑** | ✅ | ❌ | ❌ | ✅ | ✅ |
| **Google 搜索** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **API 访问** | ✅ | ✅ | ✅ | ❌ | ✅ |
| **文字渲染** | ⭐⭐⭐ | ⭐⭐ | ⭐ | ⭐⭐ | ⭐⭐ |
| **开源** | ❌ | ✅ | ✅ | ❌ | ❌ |

---

## 📊 核心功能对比

| 功能 | Nano Banana 2 | Flux Dev | SDXL | Midjourney |
|------|--------------|----------|------|------------|
| 最大分辨率 | **4K** | 2K | 1K | 2K |
| 速度 | **⚡⚡⚡** | ⚡⚡ | ⚡ | ⚡⚡ |
| 参考图数量 | **14** | 1 | 1 | 4 |
| 图像编辑 | **✅** | ❌ | ❌ | ✅ |
| Google 搜索集成 | **✅** | ❌ | ❌ | ❌ |
| API 访问 | **✅** | ✅ | ✅ | ❌ |
| 文生图 | **✅** | ✅ | ✅ | ✅ |
| 图生图 | **✅** | ✅ | ✅ | ✅ |
| 批量处理 | **✅** | ✅ | ✅ | ❌ |
| 商业许可 | **✅** | ✅ | ✅ | ✅ |

---

## 🚀 快速开始

### 使用 Atlas Cloud API

Atlas Cloud 提供最具性价比的 Nano Banana 2 访问方式，所有分辨率统一定价。

#### cURL — 文生图

```bash
# 使用 Atlas Cloud API 生成图片
curl -X POST "https://api.atlascloud.ai/v1/images/generations" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "nano-banana-2",
    "prompt": "A golden retriever puppy sitting in a field of sunflowers at sunset, 8K photography, shallow depth of field",
    "size": "2048x2048",
    "quality": "hd",
    "n": 1
  }'
```

#### Python — 文生图

```python
# 使用 Python SDK 调用 Nano Banana 2 文生图
import requests
import json

API_KEY = "YOUR_API_KEY"
API_URL = "https://api.atlascloud.ai/v1/images/generations"

# 文生图请求参数
payload = {
    "model": "nano-banana-2",
    "prompt": "赛博朋克城市夜景，霓虹灯在雨水中倒映，"
              "超精细，电影级光照，4K分辨率",
    "size": "2048x2048",
    "quality": "hd",
    "n": 1
}

headers = {
    "Authorization": f"Bearer {API_KEY}",
    "Content-Type": "application/json"
}

# 发送请求并获取结果
response = requests.post(API_URL, headers=headers, json=payload)
result = response.json()

# 获取生成的图片URL
image_url = result["data"][0]["url"]
print(f"生成的图片地址: {image_url}")
```

#### JavaScript — 文生图

```javascript
// 使用 JavaScript 调用 Nano Banana 2 文生图
const API_KEY = "YOUR_API_KEY";
const API_URL = "https://api.atlascloud.ai/v1/images/generations";

// 文生图请求函数
async function generateImage(prompt) {
  const response = await fetch(API_URL, {
    method: "POST",
    headers: {
      "Authorization": `Bearer ${API_KEY}`,
      "Content-Type": "application/json",
    },
    body: JSON.stringify({
      model: "nano-banana-2",
      prompt: prompt,
      size: "2048x2048",
      quality: "hd",
      n: 1,
    }),
  });

  const result = await response.json();
  // 返回生成的图片URL
  return result.data[0].url;
}

// 示例调用
generateImage("宁静的日本庭园，樱花盛开，锦鲤池塘，4K画质")
  .then((url) => console.log("生成的图片地址:", url));
```

#### Python — 图像编辑

```python
# 使用 Nano Banana 2 进行图片编辑
import requests
import base64

API_KEY = "YOUR_API_KEY"
API_URL = "https://api.atlascloud.ai/v1/images/edits"

# 读取原始图片并编码为base64
with open("original.jpg", "rb") as f:
    image_data = base64.b64encode(f.read()).decode("utf-8")

# 图片编辑请求参数
payload = {
    "model": "nano-banana-2-edit",
    "image": image_data,
    "prompt": "将背景更换为日落时分的热带海滩，保持主体不变",
    "size": "2048x2048"
}

headers = {
    "Authorization": f"Bearer {API_KEY}",
    "Content-Type": "application/json"
}

# 发送编辑请求
response = requests.post(API_URL, headers=headers, json=payload)
result = response.json()
print(f"编辑后的图片地址: {result['data'][0]['url']}")
```

#### Python — 多参考图混合

```python
# 使用多参考图进行图片混合（最多支持14张参考图）
import requests
import base64

API_KEY = "YOUR_API_KEY"
API_URL = "https://api.atlascloud.ai/v1/images/generations"

# 加载多张参考图片
reference_images = []
for img_path in ["style_ref.jpg", "subject_ref.jpg", "color_ref.jpg"]:
    with open(img_path, "rb") as f:
        encoded = base64.b64encode(f.read()).decode("utf-8")
        reference_images.append(encoded)

# 多参考图生成请求
payload = {
    "model": "nano-banana-2",
    "prompt": "将图片1的艺术风格、图片2的主体、图片3的配色方案融合在一起，"
              "创建一幅和谐的构图",
    "reference_images": reference_images,
    "size": "2048x2048",
    "quality": "hd"
}

headers = {
    "Authorization": f"Bearer {API_KEY}",
    "Content-Type": "application/json"
}

# 发送请求
response = requests.post(API_URL, headers=headers, json=payload)
result = response.json()
print(f"混合生成的图片地址: {result['data'][0]['url']}")
```

---

## 🎨 提示词合集

### 超写实摄影

#### 1. 电影感人像
```
A close-up portrait of a woman with freckles, golden hour sunlight streaming
through her auburn hair, shallow depth of field, shot on Hasselblad X2D,
natural skin texture, warm tones, editorial photography
```
> **分辨率：** 2K | **宽高比：** 3:4 | **技巧：** 提及具体相机型号可获得真实的镜头效果

#### 2. 城市街拍
```
Tokyo street scene at 2AM, rain-slicked pavement reflecting neon signs,
lone figure with transparent umbrella, Kodak Portra 800 film aesthetic,
slight motion blur, atmospheric fog
```
> **分辨率：** 2K | **宽高比：** 16:9 | **技巧：** 胶片名称可带来真实的颗粒感和色彩

#### 3. 震撼风光
```
Patagonian mountains at sunrise, layers of fog in the valleys below,
mirror-still lake in foreground reflecting snow-capped peaks,
landscape photography by Ansel Adams, ultra-sharp, 4K
```
> **分辨率：** 4K | **宽高比：** 21:9 | **技巧：** 4K 分辨率最适合广阔的风景照

#### 4. 微距摄影
```
Extreme macro shot of morning dew on a spider web, rainbow light refraction
in each droplet, dark forest background, focus stacking technique,
Canon MP-E 65mm lens, f/2.8
```
> **分辨率：** 2K | **宽高比：** 1:1 | **技巧：** 镜头参数可增强微距真实感

#### 5. 环境人像
```
A weathered fisherman mending nets on a wooden dock at dawn,
Mediterranean village in background, dramatic clouds, Fujifilm X-T5
color science, documentary style photography
```
> **分辨率：** 2K | **宽高比：** 4:5 | **技巧：** 添加环境信息（地点、活动）可创建更丰富的场景

#### 6. 美食摄影
```
Artisanal sourdough bread fresh from the oven, steam rising,
rustic wooden cutting board, scattered flour, warm window light,
overhead shot, Michelin-star plating aesthetic
```
> **分辨率：** 2K | **宽高比：** 1:1 | **技巧：** 使用"steam rising"可让美食照片更生动

### 数字艺术与插画

#### 7. 概念艺术 — 奇幻城堡
```
A massive floating castle above the clouds, connected to the ground by
chains of crystallized light, waterfalls cascading into the void below,
epic fantasy concept art, Greg Rutkowski style, dramatic god rays
```
> **分辨率：** 4K | **宽高比：** 16:9 | **技巧：** 艺术家名字可帮助定义风格方向

#### 8. 动漫角色
```
A young samurai girl standing in a field of red spider lilies,
wind blowing her dark hair and white kimono, katana at her side,
Studio Ghibli art style, warm sunset palette, detailed background
```
> **分辨率：** 2K | **宽高比：** 3:4 | **技巧：** 工作室引用（吉卜力、Trigger、MAPPA）可设定风格

#### 9. 科幻环境
```
Interior of a massive space station biodome, lush vegetation growing
alongside futuristic architecture, Earth visible through the glass ceiling,
volumetric lighting, hard sci-fi illustration, Syd Mead inspired
```
> **分辨率：** 4K | **宽高比：** 21:9 | **技巧：** "Hard sci-fi"可产生更科学合理的结果

#### 10. 暗黑奇幻
```
An ancient dragon skeleton overgrown with bioluminescent fungi,
a lone traveler with a lantern standing at the base of the skull,
dark atmospheric lighting, detailed fantasy illustration, muted colors
with glowing accents
```
> **分辨率：** 2K | **宽高比：** 16:9 | **技巧：** 暗场景与光源的对比可增加戏剧性

#### 11. 水彩插画
```
A cozy bookshop interior on a rainy afternoon, cats sleeping on stacks
of books, warm yellow lamplight, watercolor painting style,
soft edges, visible brush strokes, gentle color bleeding
```
> **分辨率：** 1K | **宽高比：** 4:5 | **技巧：** 绘画风格用 1K 就够了，可节省成本

#### 12. 像素艺术
```
A 16-bit RPG town square with merchants, a fountain in the center,
cobblestone paths, pixel art style, isometric view, warm color palette,
retro game aesthetic, detailed tilework
```
> **分辨率：** 1K | **宽高比：** 1:1 | **技巧：** 较低分辨率可保留像素艺术的完整性

### 产品与商业

#### 13. 高端产品摄影
```
A luxury wristwatch floating above a dark reflective surface,
golden hour lighting from the left, water droplets on the crystal face,
commercial product photography, phase one camera,
extreme attention to detail
```
> **分辨率：** 4K | **宽高比：** 1:1 | **技巧：** 4K 对产品细节至关重要

#### 14. 美妆包装
```
A line of skincare bottles arranged on white marble with dried botanicals,
soft directional studio lighting, minimalist aesthetic,
clean beauty product photography, overhead angle
```
> **分辨率：** 2K | **宽高比：** 4:5 | **技巧：** 非常适合 Instagram 格式的产品帖子

#### 15. 球鞋设计稿
```
A futuristic sneaker design with translucent sole, knit upper in gradient
teal to purple, floating against a clean white background,
Nike-quality product render, studio lighting, three-quarter view
```
> **分辨率：** 2K | **宽高比：** 4:3 | **技巧：** 提及品牌级别的品质可获得专业效果

#### 16. 科技产品主图
```
Next-generation smartphone on a dark gradient background,
screen glowing with colorful abstract art, subtle reflections,
dramatic rim lighting, Apple-style product photography,
ultra clean and minimal
```
> **分辨率：** 4K | **宽高比：** 9:16 | **技巧：** 9:16 非常适合移动优先的营销素材

#### 17. 食品饮料广告
```
Craft beer being poured into a frosted glass, perfect foam head forming,
condensation droplets on the glass, warm pub lighting in background,
commercial beverage photography, high-speed capture moment
```
> **分辨率：** 2K | **宽高比：** 4:5 | **技巧：** "High-speed capture"可创建冻结动作效果

#### 18. 家具目录
```
A mid-century modern living room setup, teak credenza with ceramic vases,
Eames lounge chair, morning light through linen curtains,
IKEA catalog style photography, warm Scandinavian palette
```
> **分辨率：** 2K | **宽高比：** 16:9 | **技巧：** 室内摄影提及具体家具风格效果更好

### 文字与排版

#### 19. 电影海报
```
Text "ECHOES" in large chrome 3D letters with cracks revealing fire within,
set against a post-apocalyptic cityscape, smoke and embers rising,
cinematic movie poster design, dramatic composition
```
> **分辨率：** 4K | **宽高比：** 2:3 | **技巧：** Nano Banana 2 擅长文字渲染——保持在3个词以内效果最佳

#### 20. 霓虹灯牌
```
A neon sign reading "OPEN LATE" in cursive pink and blue neon tubes,
mounted on a dark brick wall, slight glow and bloom effect,
atmospheric night scene, realistic neon light photography
```
> **分辨率：** 2K | **宽高比：** 16:9 | **技巧：** 霓虹灯是 NB2 的强项——添加"glow"和"bloom"

#### 21. 复古海报
```
A retro travel poster for "MARS COLONY 2087" in art deco style,
showing red planet landscape with dome cities,
vintage color palette of burnt orange and cream,
bold geometric typography, aged paper texture
```
> **分辨率：** 2K | **宽高比：** 2:3 | **技巧：** 将特定时代的风格与文字结合可获得协调的设计

#### 22. 社交媒体横幅
```
A YouTube channel banner with text "TECH WEEKLY" in bold modern sans-serif,
gradient background from deep blue to purple, circuit board pattern overlay,
clean digital design, professional and sleek
```
> **分辨率：** 2K | **宽高比：** 16:9 | **技巧：** 指定字体样式（衬线、无衬线、手写）

#### 23. Logo 概念
```
A minimalist logo design for a coffee brand called "DAWN BREW",
sunrise icon integrated with a coffee cup silhouette,
warm gradient from amber to brown, clean vector style,
white background, professional brand identity
```
> **分辨率：** 1K | **宽高比：** 1:1 | **技巧：** 使用"minimalist"和"vector style"可获得干净的 Logo

#### 24. 活动传单
```
A music festival poster with text "SOUNDWAVE 2026" in glitch-art typography,
abstract sound wave visualization in vibrant neon colors,
dark background, modern graphic design,
clean layout with date "JUNE 15-17"
```
> **分辨率：** 2K | **宽高比：** 2:3 | **技巧：** 在提示词中明确文字位置可支持多个文本元素

### 图像编辑

#### 25. 风格迁移
```
Transform this photo into a Studio Ghibli animation style,
maintain the exact composition and subject positioning,
add warm pastel colors and soft lighting typical of Ghibli films,
hand-painted texture
```
> **模式：** 编辑 | **参考图：** 1张 | **技巧：** 明确说明哪些要保留、哪些要修改

#### 26. 背景替换
```
Replace the background with a snowy mountain landscape at golden hour,
maintain the subject with perfect edge detection,
ensure natural lighting match between subject and new background,
subtle shadow on snow
```
> **模式：** 编辑 | **参考图：** 1张 | **技巧：** 提及"lighting match"可实现无缝合成

#### 27. 物体移除
```
Remove the parked cars from the street scene,
fill the area with matching cobblestone pavement,
maintain consistent lighting and perspective,
keep all other elements untouched
```
> **模式：** 编辑 | **参考图：** 1张 | **技巧：** 描述移除后应该填充什么

#### 28. 季节变换
```
Transform this summer garden scene into deep winter,
add fresh snow on all surfaces, bare tree branches,
overcast sky, footprints in the snow leading to the house,
maintain the same composition and structure
```
> **模式：** 编辑 | **参考图：** 1张 | **技巧：** 季节变换可以展示 NB2 的场景理解能力

#### 29. 时间变换
```
Convert this daytime cityscape to a nighttime scene,
add lit windows in buildings, street lamp glow,
car headlight trails on the road, starry sky,
maintain exact architecture and perspective
```
> **模式：** 编辑 | **参考图：** 1张 | **技巧：** "Maintain exact architecture"可防止结构性变化

#### 30. 年龄变化
```
Age the subject in this portrait by 30 years naturally,
add realistic wrinkles, slightly graying hair at temples,
maintain the same facial structure and expression,
keep clothing and background identical
```
> **模式：** 编辑 | **参考图：** 1张 | **技巧：** 指定"naturally"可避免夸张的老化效果

### NSFW / 艺术人体

> **说明：** Atlas Cloud 支持无审查生成，适用于艺术和创意表达。请负责任地使用。

#### 31. 古典画作研究
```
A renaissance-style oil painting of reclining Venus in a garden setting,
inspired by Titian and Botticelli, warm golden light,
draped silk fabrics, flowers and fruit in the scene,
museum-quality fine art painting, classical composition
```
> **分辨率：** 2K | **宽高比：** 16:9 | **技巧：** 古典艺术引用可产生有品味的结果

#### 32. 人体素描
```
An artistic charcoal figure drawing study, classical contrapposto pose,
dramatic chiaroscuro lighting from a single window,
textured paper background, fine art academy style,
anatomically accurate, expressive mark-making
```
> **分辨率：** 2K | **宽高比：** 3:4 | **技巧：** "Life drawing study"和"fine art"可设定恰当的基调

#### 33. 雕塑式摄影
```
A black and white fine art photograph of a dancer in motion,
long exposure capturing flowing movement, marble-like skin texture,
dramatic studio lighting with strong shadows,
inspired by Robert Mapplethorpe, gallery-quality print
```
> **分辨率：** 2K | **宽高比：** 4:5 | **技巧：** 摄影师引用可保持艺术意图

#### 34. 奇幻艺术
```
A mythological siren emerging from moonlit ocean waves,
bioluminescent sea creatures around her, flowing hair merging with water,
fantasy digital painting, ethereal and otherworldly atmosphere,
cool blue and silver color palette
```
> **分辨率：** 2K | **宽高比：** 3:4 | **技巧：** 神话框架可增加创意深度

### 梗图与病毒式内容

#### 35. 热门风格梗图
```
A photorealistic image of a cat wearing a tiny business suit
sitting at a corporate board meeting, other cats in suits around
the conference table, one cat presenting a pie chart about "fish imports",
office photography style, humorous
```
> **分辨率：** 1K | **宽高比：** 1:1 | **技巧：** 幽默 + 写实 = 病毒式传播潜力

#### 36. 时事混搭
```
Create an image in the style of a breaking news broadcast,
lower third graphics reading "BANANA PRICES HIT ALL-TIME HIGH",
news anchor desk setup, professional broadcast studio,
dramatic serious mood about a silly topic
```
> **分辨率：** 2K | **宽高比：** 16:9 | **技巧：** Google 搜索集成有助于获取当前视觉格式

#### 37. 表情包
```
A renaissance painting of a nobleman looking at his phone with an
expression of absolute shock and disbelief, oil painting style,
ornate gold frame visible, museum lighting,
contrast between historical setting and modern device
```
> **分辨率：** 1K | **宽高比：** 1:1 | **技巧：** 时代错位的幽默可生成高度可分享的内容

#### 38. 品牌恶搞
```
A luxury fashion brand advertisement but for everyday mundane objects,
a single pencil on a marble pedestal with dramatic lighting,
"HAUTE STATIONERY" text in elegant serif font,
high-end commercial photography, satirical
```
> **分辨率：** 2K | **宽高比：** 4:5 | **技巧：** 恶搞在使用特定高端美学时效果最佳

#### 39. AI 艺术元叙事
```
An AI robot sitting at an easel painting a landscape,
but the landscape on the canvas is a photo of another AI painting,
infinite recursive loop visible in mirrors behind,
photorealistic style, philosophical concept art
```
> **分辨率：** 2K | **宽高比：** 1:1 | **技巧：** 自我引用的 AI 艺术在科技圈很受欢迎

#### 40. 荒诞写实主义
```
A perfectly ordinary suburban house but it's made entirely of cheese,
photorealistic detail, cheddar walls, mozzarella curtains,
swiss cheese windows, neighborhood setting,
real estate listing photography style, completely serious tone
```
> **分辨率：** 2K | **宽高比：** 16:9 | **技巧：** 荒诞题材配上"completely serious tone"可最大化幽默效果

#### 41. 历史人物新编
```
Napoleon Bonaparte as a modern startup CEO giving a TED talk,
wearing a slim-fit navy suit with his iconic hand-in-vest pose,
large screen behind him showing a pitch deck titled "Conquering Markets",
conference hall setting, professional event photography
```
> **分辨率：** 2K | **宽高比：** 16:9 | **技巧：** 历史与现代的对比可创造引人注目的图像

#### 42. 恶搞专辑封面
```
An indie rock album cover titled "CTRL+Z" featuring a person
standing in a field of floating undo icons, vaporwave color palette,
dreamy atmosphere, vinyl record mockup style,
nostalgic yet futuristic aesthetic
```
> **分辨率：** 2K | **宽高比：** 1:1 | **技巧：** 专辑封面的正方形格式在 2K 下非常适合分享

---

## 📝 提示词工程指南

### 分辨率优化

根据使用场景选择合适的分辨率，平衡质量和成本：

| 分辨率 | 最适用于 | 费用 (Atlas Cloud) |
|--------|---------|-------------------|
| **512px (0.5K)** | 缩略图、快速草稿、社交媒体头像 | $0.072 |
| **1024px (1K)** | 社交媒体帖子、网页内容、像素艺术 | $0.072 |
| **2048px (2K)** | 印刷品质、精细摄影、专业用途 | $0.072 |
| **4096px (4K)** | 大幅印刷、壁纸、商业素材 | $0.072 |

> **专业提示：** 在 Atlas Cloud 上，所有分辨率都是相同的 $0.072 价格，所以总是选择 2K 或 4K！

### 参考图最佳实践

Nano Banana 2 支持最多 **14 张参考图**。以下是高效使用方法：

| 参考图数量 | 使用场景 | 最佳方法 |
|-----------|---------|---------|
| 1 | 风格迁移、编辑 | 提供清晰、高质量的源图 |
| 2-3 | 风格 + 主体 + 配色 | 在提示词中为每张参考图分配具体角色 |
| 4-7 | 多元素合成 | 描述哪些元素来自哪张参考图 |
| 8-14 | 复杂品牌/设计系统 | 用于在多个变体中保持一致性 |

**技巧：**
- 在提示词中标注参考图："使用图片1的风格、图片2的主体"
- 高质量的参考图可产生更好的结果
- 参考图之间光照一致有助于连贯性
- 正方形裁切的参考图效果最佳

### Google 搜索集成技巧

Nano Banana 2 可以利用 Google 搜索获取实时视觉信息：

- **品牌准确性：** "特斯拉 Cybertruck 的真实设计" —— 获取当前产品设计
- **时事热点：** "2026 年奥斯卡红毯" —— 引用真实活动美学
- **流行趋势：** "当前 Instagram 上的流行时尚" —— 获取实时趋势
- **文化引用：** "TikTok 上的病毒式美学" —— 理解当前模因文化
- **事实内容：** "时代广场的真实布局" —— 地理位置准确的场景

### 最有效的风格关键词

| 类别 | 有效关键词 |
|------|-----------|
| **摄影** | `shot on [相机]`, `[胶片] aesthetic`, `f/[光圈]`, `golden hour` |
| **数字艺术** | `concept art`, `digital painting`, `matte painting`, `[艺术家] style` |
| **插画** | `watercolor`, `ink wash`, `vector`, `flat design`, `line art` |
| **3D 渲染** | `Octane render`, `Unreal Engine 5`, `ray tracing`, `subsurface scattering` |
| **复古** | `retro`, `analog`, `grain`, `faded colors`, `polaroid`, `VHS` |
| **情绪** | `dramatic`, `ethereal`, `moody`, `whimsical`, `dark`, `vibrant` |

### 宽高比指南

| 比例 | 尺寸 | 使用场景 |
|------|------|---------|
| **1:1** | 2048×2048 | 社交媒体、专辑封面、头像 |
| **4:5** | 1638×2048 | Instagram 帖子、人像 |
| **3:4** | 1536×2048 | 产品摄影、人像 |
| **16:9** | 2048×1152 | YouTube 缩略图、桌面壁纸 |
| **9:16** | 1152×2048 | 手机壁纸、Stories、抖音 |
| **21:9** | 2048×878 | 超宽屏、电影级风景 |
| **2:3** | 1365×2048 | 海报、印刷品 |

### 输出格式指南

| 格式 | 最适用于 | 说明 |
|------|---------|------|
| **PNG** | 图形、文字、Logo、透明底 | 无损，文件较大 |
| **JPEG** | 摄影、渐变、网页使用 | 文件较小，轻微压缩 |
| **WebP** | 网页优化 | 最佳尺寸与质量比 |

---

## 💰 价格深度对比

### Nano Banana 2：Atlas Cloud vs Google 官方

| 分辨率 | Google 官方 | Atlas Cloud | 差额 |
|--------|-----------|-------------|------|
| **0.5K** (512px) | $0.045 | $0.072 | Google 便宜 $0.027 |
| **1K** (1024px) | $0.067 | $0.072 | Google 便宜 $0.005 |
| **2K** (2048px) | $0.101 | **$0.072** | **✅ Atlas 便宜 29%！** |
| **4K** (4096px) | $0.151 | **$0.072** | **✅ Atlas 便宜 52%！** |

> **关键洞察：** Atlas Cloud 对所有分辨率提供 $0.072 的**统一定价**。你需要的分辨率越高，节省就越多。4K 图片比 Google 官方价格节省超过 **50%**！

### 批量对比（1,000 张图片）

| 分辨率 | Google 费用 | Atlas Cloud 费用 | 节省 |
|--------|-----------|-----------------|------|
| 1,000 × 0.5K | $45.00 | $72.00 | -$27.00 |
| 1,000 × 1K | $67.00 | $72.00 | -$5.00 |
| 1,000 × 2K | $101.00 | **$72.00** | **$29.00** |
| 1,000 × 4K | $151.00 | **$72.00** | **$79.00** |

### 💡 新用户奖励

Atlas Cloud 提供**首次充值 25% 奖励**（最高 $100 奖励）。这意味着：

| 充值金额 | 奖励 (25%) | 总额度 | 4K 实际单价 |
|---------|-----------|--------|-----------|
| $10 | $2.50 | $12.50 | $0.058/张 |
| $50 | $12.50 | $62.50 | $0.058/张 |
| $100 | $25.00 | $125.00 | $0.058/张 |
| $400 | $100.00 | $500.00 | $0.058/张 |

> 加上首次奖励，你的实际单价降至 **$0.058/张**，任意分辨率——比 Google 4K 定价**便宜 62%**！

**[👉 在 Atlas Cloud 领取 25% 奖励](https://www.atlascloud.ai?ref=JPM683)**

### Atlas Cloud vs fal.ai — 价格对比

| 模型 | fal.ai | Atlas Cloud | 备注 |
|:-----|:-------|:-----------|:-----|
| **Nano Banana 2** | $0.0398/张 | $0.072/张 | fal.ai 单价更低，但 Atlas Cloud 提供统一 API，46 个模型一个端点 |
| **Flux Kontext Pro** | $0.04/张 | — | fal.ai 上可用 |
| **Seedream V4** | $0.03/张 | $0.032/张 | 价格非常接近 |
| **Flux Dev** | — | $0.012/张 | Atlas Cloud 在 Flux Dev 上极具竞争力 |

> **为什么即使 fal.ai 部分模型更便宜，仍选择 Atlas Cloud？**
> - **统一 API** — 46 个图像模型，一个 API Key、一个端点、一个账单
> - **无审查模式** — 支持模型无内容过滤
> - **批量生成** — 单次请求最多生成 15 张图（Seedream Sequential）
> - **LoRA 支持** — 在所有兼容模型上使用自定义 LoRA
> - **统一定价** — 高分辨率无额外费用（如 Nano Banana 2 所有分辨率至 4K 均为 $0.072）

---

## 🌐 Atlas Cloud 上的 Google 图像模型全家桶

Atlas Cloud 提供 Google 完整的图像生成产品线：

| 模型 | 价格 | 速度 | 质量 | 最适用于 |
|------|------|------|------|---------|
| **Nano Banana 2** | $0.072 | ⚡⚡⚡ | ⭐⭐⭐⭐ | 最新最快，通用场景 |
| **Nano Banana 2 Edit** | 可用 | ⚡⚡⚡ | ⭐⭐⭐⭐ | 图像编辑与修改 |
| **Nano Banana Pro** | 可用 | ⚡⚡ | ⭐⭐⭐⭐⭐ | 专业品质输出 |
| **Nano Banana** | 可用 | ⚡⚡⚡ | ⭐⭐⭐ | 经济实惠的初代版 |
| **Imagen4 Ultra** | 可用 | ⚡ | ⭐⭐⭐⭐⭐ | 最高品质旗舰 |
| **Imagen4** | 可用 | ⚡⚡ | ⭐⭐⭐⭐ | 质量与速度平衡 |
| **Imagen4 Fast** | 可用 | ⚡⚡⚡ | ⭐⭐⭐ | 快速迭代 |
| **Imagen3** | 可用 | ⚡⚡ | ⭐⭐⭐ | 稳定可靠 |
| **Imagen3 Fast** | 可用 | ⚡⚡⚡ | ⭐⭐⭐ | 经济快速选项 |

> 所有模型均支持文生图。Nano Banana 2 的文生图和编辑均提供开发者版本。

**[👉 在 Atlas Cloud 探索所有模型](https://www.atlascloud.ai?ref=JPM683)**

---

## 📚 官方资源

- **[Google AI Studio](https://aistudio.google.com/)** — Nano Banana 2 免费体验平台（有每日限额）
- **[Vertex AI](https://cloud.google.com/vertex-ai/docs/generative-ai/image/overview)** — 通过 Google Cloud 的企业级 API 访问
- **[Gemini API 文档](https://ai.google.dev/docs)** — 官方 API 参考和指南
- **[Google AI 博客](https://blog.google/technology/ai/)** — 公告和研究论文
- **[Gemini App](https://gemini.google.com/)** — 通过 Gemini 消费级入口（快速/思考/专业模式）
- **[Google Cloud 定价](https://cloud.google.com/vertex-ai/pricing)** — 官方定价页面

---

## 🛠️ 社区资源

### 工具与库

- **[Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683)** — 性价比最高的 Nano Banana 2 及所有 Google 图像模型访问方式
- **[ComfyUI-NanoBanana](https://github.com/comfyanonymous/ComfyUI)** — Nano Banana 2 的 ComfyUI 集成
- **[NB2-Gradio](https://huggingface.co/spaces)** — 用于快速测试的 Gradio Web UI
- **[nb2-batch](https://github.com/)** — Nano Banana 2 批量处理工具
- **[Auto1111 NB2 扩展](https://github.com/)** — Automatic1111 WebUI 扩展

### 教程与文章

- [如何使用 Nano Banana 2 进行产品摄影](https://blog.google/) — Google AI 博客
- [Nano Banana 2 完全指南](https://www.atlascloud.ai?ref=JPM683) — Atlas Cloud 博客
- [Nano Banana 2 vs Flux vs Midjourney：终极对比](https://www.atlascloud.ai?ref=JPM683) — Atlas Cloud
- [掌握多参考图生成](https://ai.google.dev/) — Google 开发者

### 社区

- [r/NanoBanana](https://reddit.com/r/NanoBanana) — Reddit 社区
- [Nano Banana Discord](https://discord.gg/) — 社区 Discord 服务器
- [Hacker News 讨论](https://news.ycombinator.com/) — 病毒式传播的起点
- [Google AI Discord](https://discord.gg/) — Google AI 官方社区

---

## ❓ 常见问题

### 什么是 Nano Banana 2？

Nano Banana 2 是 Google 的 Gemini 3.1 Flash Image 模型，于 2026 年 2 月 26 日发布。它是一款 AI 图像生成和编辑模型，支持 512px 到 4K 分辨率的输出，可接受最多 14 张参考图，并集成 Google 搜索以获取实时视觉信息。它是 Gemini App 中的默认图像生成模型。"Nano Banana"是它的社区昵称。

### Nano Banana 2 多少钱？

Google 官方定价从 $0.045（0.5K）到 $0.151（4K）每张不等。**Atlas Cloud** 提供统一 **$0.072/张** 的价格，适用于**任意分辨率**，使 2K 和 4K 的生成成本显著降低——4K 图片最多可**节省 52%**。首次用户还可获得 25% 的充值奖励。

### Nano Banana 2 vs Flux——哪个更好？

Nano Banana 2 在速度、最大分辨率（4K vs 2K）、参考图支持（14 vs 1）、内置图像编辑、Google 搜索集成和文字渲染方面均领先。Flux 的优势在于开源和默认无内容限制。在生产环境中，Nano Banana 2 通常更强大、更快速。

### Nano Banana 2 vs Midjourney——应该用哪个？

Nano Banana 2 提供 API 访问（Midjourney 没有）、更高的最大分辨率（4K vs 2K）、更多参考图（14 vs 4）和 Google 搜索集成。Midjourney 拥有强大的社区和独特的美学风格。对于开发者和基于 API 的工作流，Nano Banana 2 是明确的选择。

### Nano Banana 2 能生成 NSFW 内容吗？

Google 的官方 API 有内容限制。然而，**Atlas Cloud** 提供无审查的 Nano Banana 2 访问，允许没有内容过滤的艺术和创意表达。这对于美术、人体素描和其他合法的艺术用途特别有用。

### Nano Banana 2 最佳分辨率是多少？

取决于你的使用场景。社交媒体用 1K 就够了。专业摄影和印刷用 2K。大幅印刷、壁纸和商业素材用 4K。**在 Atlas Cloud 上，所有分辨率都是相同的 $0.072 价格**，所以没理由不用 2K 或 4K！

### Nano Banana 2 速度有多快？

Nano Banana 2 被广泛认为是目前最快的 AI 图像生成器。1K 图片的典型生成时间在 3 秒以内，4K 图片在 8 秒以内，适合实时创作工作流和交互式应用。

### Nano Banana 2 能在图片中生成文字吗？

可以！文字渲染是 Nano Banana 2 的突出特性。它对短文本（1-3 个词）的处理非常出色，可以生成多达 10-15 个词的可读文字。为获得最佳效果，请使用清晰的排版指令并保持文字简洁。

### 可以使用多少张参考图？

Nano Banana 2 支持同时使用最多 **14 张参考图**。你可以为每张参考图分配不同的角色（风格、主体、配色、构图等），实现精确控制输出。

### Nano Banana 2 支持图片编辑吗？

支持。Nano Banana 2 包含专用的编辑模式，可以执行风格迁移、背景替换、物体移除、色彩调整、季节变换等多种修改，同时保持未编辑区域的完整性。

---

<div align="center">

## 🍌 使用 Nano Banana 2 生成精美图像

**以无与伦比的价格获取 Google 最强大的图像模型。**

| 优势 | 详情 |
|------|------|
| ✅ **便宜 52%** | 4K 图片比 Google 官方便宜 |
| ✅ **无审查** | 无内容限制 |
| ✅ **所有 Google 模型** | Nano Banana 2、Imagen4 Ultra 等 |
| ✅ **25% 奖励** | 首次充值（最高 $100） |
| ✅ **统一定价** | 所有分辨率最高 4K 均为 $0.072 |

### [👉 在 Atlas Cloud 上开始生成](https://www.atlascloud.ai?ref=JPM683)

---

## ⭐ Star 历史

如果你觉得这个资源有帮助，请给个 Star！它能帮助其他人发现最好的 Nano Banana 2 资源。

[![Star History Chart](https://api.star-history.com/svg?repos=your-org/awesome-nano-banana-2&type=Date)](https://star-history.com/#your-org/awesome-nano-banana-2&Date)

---

## 🤝 贡献指南

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。

1. Fork 本仓库
2. 创建你的功能分支 (`git checkout -b feature/add-resource`)
3. 提交更改 (`git commit -m 'Add new resource'`)
4. 推送到分支 (`git push origin feature/add-resource`)
5. 发起 Pull Request

---

## 📄 许可证

本项目基于 MIT 许可证 —— 详见 [LICENSE](LICENSE) 文件。

---

**由社区用 🍌 制作。非 Google 官方关联项目。**

</div>
