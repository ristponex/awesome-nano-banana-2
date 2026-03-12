<div align="center">

# 🍌 Awesome Nano Banana 2

**The Ultimate Guide to Google's Nano Banana 2 Image Generation**

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Stars](https://img.shields.io/github/stars/your-org/awesome-nano-banana-2?style=social)](https://github.com/your-org/awesome-nano-banana-2)

A curated collection of resources, prompts, tools, and guides for **Nano Banana 2** — Google's Gemini 3.1 Flash Image model, the fastest AI image generator ever built.

**[English](./README.md)** | **[简体中文](./README_zh-CN.md)** | **[日本語](./README_ja.md)** | **[한국어](./README_ko.md)**

---

### 🚀 Generate Nano Banana 2 Images from $0.072/request — Cheaper than Google Official for 2K/4K!

**[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)** offers flat $0.072 pricing for ALL resolutions up to 4K — **52% cheaper** than Google for 4K images. Uncensored. All Google models available. **25% bonus** on first top-up!

**[👉 Start Generating Now](https://www.atlascloud.ai?ref=JPM683)**

> 🔒 **Enterprise-Grade Security** — Atlas Cloud is **SOC I & II Certified** | **HIPAA Compliant** | US-based company with 99.9% uptime SLA.

---

</div>

## 📑 Table of Contents

- [What is Nano Banana 2?](#-what-is-nano-banana-2)
- [Key Features Comparison](#-key-features-comparison)
- [Quick Start](#-quick-start)
- [Prompt Collection](#-prompt-collection)
  - [Photorealistic Photography](#photorealistic-photography)
  - [Digital Art & Illustration](#digital-art--illustration)
  - [Product & Commercial](#product--commercial)
  - [Text & Typography](#text--typography)
  - [Image Editing](#image-editing)
  - [NSFW / Artistic Nude](#nsfw--artistic-nude)
  - [Memes & Viral Content](#memes--viral-content)
- [Prompt Engineering Guide](#-prompt-engineering-guide)
- [Pricing Deep Dive](#-pricing-deep-dive)
- [Google Image Model Family on Atlas Cloud](#-google-image-model-family-on-atlas-cloud)
- [Official Resources](#-official-resources)
- [Community Resources](#-community-resources)
- [FAQ](#-faq)
- [Star History](#-star-history)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🍌 What is Nano Banana 2?

**Nano Banana 2** is Google's latest image generation and editing model, released on **February 26, 2026**. Built on the Gemini 3.1 Flash architecture, it is the default image generation model across the Gemini App (supporting Fast, Thinking, and Pro modes). The community affectionately calls it "Nano Banana 2" — a nickname that emerged from early testers and quickly went viral on Hacker News and social media.

### Evolution Timeline

```
Aug 2025          Nov 2025              Feb 2026
   │                 │                     │
   ▼                 ▼                     ▼
Nano Banana ──► Nano Banana Pro ──► Nano Banana 2
(1st gen)        (Pro quality)       (Current gen)
                                     4K · 14 refs
                                     Google Search
```

### Key Capabilities

- **Image Generation & Editing** — Generate from text or edit existing images with natural language instructions
- **512px to 4K Output** — From quick drafts to ultra-high-resolution production assets
- **Up to 14 Reference Images** — Mix, blend, and style-transfer with unprecedented control
- **Integrated Google Search** — Real-time access to brand logos, current events, trending styles, and factual visual content
- **Lightning Speed** — Widely considered the fastest AI image generator available, enabling real-time creative workflows
- **Text & Typography** — Best-in-class text rendering in generated images

### Why "Nano Banana"?

The nickname "Nano Banana" originated from Google's internal codename that leaked during early testing. The community embraced it instantly — "Nano" reflecting the model's incredibly fast inference time, and "Banana" becoming a playful reference to the model's yellow-tinted debug watermarks during the alpha phase. The name stuck, and Google eventually acknowledged it in official blog posts.

### How Does It Compare?

| Aspect | Nano Banana 2 | Flux Dev | SDXL | Midjourney v7 | DALL-E 3 |
|--------|--------------|----------|------|---------------|----------|
| **Max Resolution** | 4K | 2K | 1K | 2K | 1K |
| **Speed** | ⚡⚡⚡ | ⚡⚡ | ⚡ | ⚡⚡ | ⚡ |
| **Reference Images** | 14 | 1 | 1 | 4 | 1 |
| **Image Editing** | ✅ | ❌ | ❌ | ✅ | ✅ |
| **Google Search** | ✅ | ❌ | ❌ | ❌ | ❌ |
| **API Access** | ✅ | ✅ | ✅ | ❌ | ✅ |
| **Text Rendering** | ⭐⭐⭐ | ⭐⭐ | ⭐ | ⭐⭐ | ⭐⭐ |
| **Open Source** | ❌ | ✅ | ✅ | ❌ | ❌ |

---

## 📊 Key Features Comparison

| Feature | Nano Banana 2 | Flux Dev | SDXL | Midjourney |
|---------|--------------|----------|------|------------|
| Max Resolution | **4K** | 2K | 1K | 2K |
| Speed | **⚡⚡⚡** | ⚡⚡ | ⚡ | ⚡⚡ |
| Reference Images | **14** | 1 | 1 | 4 |
| Image Editing | **✅** | ❌ | ❌ | ✅ |
| Google Search Integration | **✅** | ❌ | ❌ | ❌ |
| API Access | **✅** | ✅ | ✅ | ❌ |
| Text-to-Image | **✅** | ✅ | ✅ | ✅ |
| Image-to-Image | **✅** | ✅ | ✅ | ✅ |
| Batch Processing | **✅** | ✅ | ✅ | ❌ |
| Commercial License | **✅** | ✅ | ✅ | ✅ |

---

## 🚀 Quick Start

### Using Atlas Cloud API

Atlas Cloud provides the most cost-effective access to Nano Banana 2, with flat pricing for all resolutions.

#### cURL — Text-to-Image

```bash
# Use Atlas Cloud API to generate images
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

#### Python — Text-to-Image

```python
# Use Python SDK to call Nano Banana 2 Text-to-Image
import requests
import json

API_KEY = "YOUR_API_KEY"
API_URL = "https://api.atlascloud.ai/v1/images/generations"

# Text-to-image request
payload = {
    "model": "nano-banana-2",
    "prompt": "Cyberpunk cityscape at night, neon signs reflecting in rain puddles, "
              "ultra-detailed, cinematic lighting, 4K resolution",
    "size": "2048x2048",
    "quality": "hd",
    "n": 1
}

headers = {
    "Authorization": f"Bearer {API_KEY}",
    "Content-Type": "application/json"
}

# Send request and get result
response = requests.post(API_URL, headers=headers, json=payload)
result = response.json()

# Get generated image URL
image_url = result["data"][0]["url"]
print(f"Generated image URL: {image_url}")
```

#### JavaScript — Text-to-Image

```javascript
// Use JavaScript to call Nano Banana 2 Text-to-Image
const API_KEY = "YOUR_API_KEY";
const API_URL = "https://api.atlascloud.ai/v1/images/generations";

// Text-to-image request
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
  // Return generated image URL
  return result.data[0].url;
}

// Example call
generateImage("A serene Japanese garden with cherry blossoms, koi pond, 4K")
  .then((url) => console.log("Generated image URL:", url));
```

#### Python — Image Editing

```python
# Use Nano Banana 2 to edit images
import requests
import base64

API_KEY = "YOUR_API_KEY"
API_URL = "https://api.atlascloud.ai/v1/images/edits"

# Read original image and encode as base64
with open("original.jpg", "rb") as f:
    image_data = base64.b64encode(f.read()).decode("utf-8")

# Image editing request
payload = {
    "model": "nano-banana-2-edit",
    "image": image_data,
    "prompt": "Change the background to a tropical beach at sunset, "
              "keep the subject untouched",
    "size": "2048x2048"
}

headers = {
    "Authorization": f"Bearer {API_KEY}",
    "Content-Type": "application/json"
}

# Send edit request
response = requests.post(API_URL, headers=headers, json=payload)
result = response.json()
print(f"Edited image URL: {result['data'][0]['url']}")
```

#### Python — Multi-Reference Image Mixing

```python
# Use multiple reference images for image blending (supports up to 14 reference images)
import requests
import base64

API_KEY = "YOUR_API_KEY"
API_URL = "https://api.atlascloud.ai/v1/images/generations"

# Load multiple reference images
reference_images = []
for img_path in ["style_ref.jpg", "subject_ref.jpg", "color_ref.jpg"]:
    with open(img_path, "rb") as f:
        encoded = base64.b64encode(f.read()).decode("utf-8")
        reference_images.append(encoded)

# Multi-reference generation request
payload = {
    "model": "nano-banana-2",
    "prompt": "Combine the art style from image 1, the subject from image 2, "
              "and the color palette from image 3. Create a harmonious composition.",
    "reference_images": reference_images,
    "size": "2048x2048",
    "quality": "hd"
}

headers = {
    "Authorization": f"Bearer {API_KEY}",
    "Content-Type": "application/json"
}

# Send request
response = requests.post(API_URL, headers=headers, json=payload)
result = response.json()
print(f"Blended image URL: {result['data'][0]['url']}")
```

---

## 🎨 Prompt Collection

### Photorealistic Photography

#### 1. Cinematic Portrait
```
A close-up portrait of a woman with freckles, golden hour sunlight streaming
through her auburn hair, shallow depth of field, shot on Hasselblad X2D,
natural skin texture, warm tones, editorial photography
```
> **Resolution:** 2K | **Aspect Ratio:** 3:4 | **Tip:** Mention specific cameras for realistic lens effects

#### 2. Urban Street Photography
```
Tokyo street scene at 2AM, rain-slicked pavement reflecting neon signs,
lone figure with transparent umbrella, Kodak Portra 800 film aesthetic,
slight motion blur, atmospheric fog
```
> **Resolution:** 2K | **Aspect Ratio:** 16:9 | **Tip:** Film stock names add authentic grain and color

#### 3. Dramatic Landscape
```
Patagonian mountains at sunrise, layers of fog in the valleys below,
mirror-still lake in foreground reflecting snow-capped peaks,
landscape photography by Ansel Adams, ultra-sharp, 4K
```
> **Resolution:** 4K | **Aspect Ratio:** 21:9 | **Tip:** 4K resolution is ideal for wide landscapes

#### 4. Macro Photography
```
Extreme macro shot of morning dew on a spider web, rainbow light refraction
in each droplet, dark forest background, focus stacking technique,
Canon MP-E 65mm lens, f/2.8
```
> **Resolution:** 2K | **Aspect Ratio:** 1:1 | **Tip:** Lens specifications enhance macro realism

#### 5. Environmental Portrait
```
A weathered fisherman mending nets on a wooden dock at dawn,
Mediterranean village in background, dramatic clouds, Fujifilm X-T5
color science, documentary style photography
```
> **Resolution:** 2K | **Aspect Ratio:** 4:5 | **Tip:** Adding context (location, activity) creates richer scenes

#### 6. Food Photography
```
Artisanal sourdough bread fresh from the oven, steam rising,
rustic wooden cutting board, scattered flour, warm window light,
overhead shot, Michelin-star plating aesthetic
```
> **Resolution:** 2K | **Aspect Ratio:** 1:1 | **Tip:** Mention "steam rising" for dynamic food shots

### Digital Art & Illustration

#### 7. Concept Art — Fantasy Castle
```
A massive floating castle above the clouds, connected to the ground by
chains of crystallized light, waterfalls cascading into the void below,
epic fantasy concept art, Greg Rutkowski style, dramatic god rays
```
> **Resolution:** 4K | **Aspect Ratio:** 16:9 | **Tip:** Artist references help define style direction

#### 8. Anime Character
```
A young samurai girl standing in a field of red spider lilies,
wind blowing her dark hair and white kimono, katana at her side,
Studio Ghibli art style, warm sunset palette, detailed background
```
> **Resolution:** 2K | **Aspect Ratio:** 3:4 | **Tip:** Studio references (Ghibli, Trigger, MAPPA) set style

#### 9. Sci-Fi Environment
```
Interior of a massive space station biodome, lush vegetation growing
alongside futuristic architecture, Earth visible through the glass ceiling,
volumetric lighting, hard sci-fi illustration, Syd Mead inspired
```
> **Resolution:** 4K | **Aspect Ratio:** 21:9 | **Tip:** "Hard sci-fi" produces more scientifically plausible results

#### 10. Dark Fantasy
```
An ancient dragon skeleton overgrown with bioluminescent fungi,
a lone traveler with a lantern standing at the base of the skull,
dark atmospheric lighting, detailed fantasy illustration, muted colors
with glowing accents
```
> **Resolution:** 2K | **Aspect Ratio:** 16:9 | **Tip:** Contrast between dark scenes and light sources adds drama

#### 11. Watercolor Illustration
```
A cozy bookshop interior on a rainy afternoon, cats sleeping on stacks
of books, warm yellow lamplight, watercolor painting style,
soft edges, visible brush strokes, gentle color bleeding
```
> **Resolution:** 1K | **Aspect Ratio:** 4:5 | **Tip:** 1K is sufficient for painterly styles; saves cost

#### 12. Pixel Art
```
A 16-bit RPG town square with merchants, a fountain in the center,
cobblestone paths, pixel art style, isometric view, warm color palette,
retro game aesthetic, detailed tilework
```
> **Resolution:** 1K | **Aspect Ratio:** 1:1 | **Tip:** Lower resolution preserves pixel art integrity

### Product & Commercial

#### 13. Premium Product Shot
```
A luxury wristwatch floating above a dark reflective surface,
golden hour lighting from the left, water droplets on the crystal face,
commercial product photography, phase one camera,
extreme attention to detail
```
> **Resolution:** 4K | **Aspect Ratio:** 1:1 | **Tip:** 4K is essential for product detail

#### 14. Cosmetics Packaging
```
A line of skincare bottles arranged on white marble with dried botanicals,
soft directional studio lighting, minimalist aesthetic,
clean beauty product photography, overhead angle
```
> **Resolution:** 2K | **Aspect Ratio:** 4:5 | **Tip:** Great for Instagram-format product posts

#### 15. Sneaker Design Mockup
```
A futuristic sneaker design with translucent sole, knit upper in gradient
teal to purple, floating against a clean white background,
Nike-quality product render, studio lighting, three-quarter view
```
> **Resolution:** 2K | **Aspect Ratio:** 4:3 | **Tip:** Mention brand-level quality for professional results

#### 16. Tech Product Hero Shot
```
Next-generation smartphone on a dark gradient background,
screen glowing with colorful abstract art, subtle reflections,
dramatic rim lighting, Apple-style product photography,
ultra clean and minimal
```
> **Resolution:** 4K | **Aspect Ratio:** 9:16 | **Tip:** 9:16 perfect for mobile-first marketing

#### 17. Food & Beverage Ad
```
Craft beer being poured into a frosted glass, perfect foam head forming,
condensation droplets on the glass, warm pub lighting in background,
commercial beverage photography, high-speed capture moment
```
> **Resolution:** 2K | **Aspect Ratio:** 4:5 | **Tip:** "High-speed capture" creates frozen motion effects

#### 18. Furniture Catalog
```
A mid-century modern living room setup, teak credenza with ceramic vases,
Eames lounge chair, morning light through linen curtains,
IKEA catalog style photography, warm Scandinavian palette
```
> **Resolution:** 2K | **Aspect Ratio:** 16:9 | **Tip:** Interior photography benefits from named furniture styles

### Text & Typography

#### 19. Movie Poster
```
Text "ECHOES" in large chrome 3D letters with cracks revealing fire within,
set against a post-apocalyptic cityscape, smoke and embers rising,
cinematic movie poster design, dramatic composition
```
> **Resolution:** 4K | **Aspect Ratio:** 2:3 | **Tip:** Nano Banana 2 excels at text — keep it under 3 words for best results

#### 20. Neon Sign
```
A neon sign reading "OPEN LATE" in cursive pink and blue neon tubes,
mounted on a dark brick wall, slight glow and bloom effect,
atmospheric night scene, realistic neon light photography
```
> **Resolution:** 2K | **Aspect Ratio:** 16:9 | **Tip:** Neon signs are a NB2 strength — add "glow" and "bloom"

#### 21. Vintage Poster
```
A retro travel poster for "MARS COLONY 2087" in art deco style,
showing red planet landscape with dome cities,
vintage color palette of burnt orange and cream,
bold geometric typography, aged paper texture
```
> **Resolution:** 2K | **Aspect Ratio:** 2:3 | **Tip:** Combine era-specific styles with text for coherent designs

#### 22. Social Media Banner
```
A YouTube channel banner with text "TECH WEEKLY" in bold modern sans-serif,
gradient background from deep blue to purple, circuit board pattern overlay,
clean digital design, professional and sleek
```
> **Resolution:** 2K | **Aspect Ratio:** 16:9 | **Tip:** Specify font style (serif, sans-serif, handwritten)

#### 23. Logo Concept
```
A minimalist logo design for a coffee brand called "DAWN BREW",
sunrise icon integrated with a coffee cup silhouette,
warm gradient from amber to brown, clean vector style,
white background, professional brand identity
```
> **Resolution:** 1K | **Aspect Ratio:** 1:1 | **Tip:** Use "minimalist" and "vector style" for clean logos

#### 24. Event Flyer
```
A music festival poster with text "SOUNDWAVE 2026" in glitch-art typography,
abstract sound wave visualization in vibrant neon colors,
dark background, modern graphic design,
clean layout with date "JUNE 15-17"
```
> **Resolution:** 2K | **Aspect Ratio:** 2:3 | **Tip:** Multiple text elements work if clearly positioned in prompt

### Image Editing

#### 25. Style Transfer
```
Transform this photo into a Studio Ghibli animation style,
maintain the exact composition and subject positioning,
add warm pastel colors and soft lighting typical of Ghibli films,
hand-painted texture
```
> **Mode:** Edit | **Reference Images:** 1 | **Tip:** Be specific about what to keep vs. change

#### 26. Background Replacement
```
Replace the background with a snowy mountain landscape at golden hour,
maintain the subject with perfect edge detection,
ensure natural lighting match between subject and new background,
subtle shadow on snow
```
> **Mode:** Edit | **Reference Images:** 1 | **Tip:** Mention "lighting match" for seamless composites

#### 27. Object Removal
```
Remove the parked cars from the street scene,
fill the area with matching cobblestone pavement,
maintain consistent lighting and perspective,
keep all other elements untouched
```
> **Mode:** Edit | **Reference Images:** 1 | **Tip:** Describe what should replace the removed object

#### 28. Season Change
```
Transform this summer garden scene into deep winter,
add fresh snow on all surfaces, bare tree branches,
overcast sky, footprints in the snow leading to the house,
maintain the same composition and structure
```
> **Mode:** Edit | **Reference Images:** 1 | **Tip:** Season changes showcase NB2's scene understanding

#### 29. Time of Day Change
```
Convert this daytime cityscape to a nighttime scene,
add lit windows in buildings, street lamp glow,
car headlight trails on the road, starry sky,
maintain exact architecture and perspective
```
> **Mode:** Edit | **Reference Images:** 1 | **Tip:** "Maintain exact architecture" prevents structural changes

#### 30. Age Progression
```
Age the subject in this portrait by 30 years naturally,
add realistic wrinkles, slightly graying hair at temples,
maintain the same facial structure and expression,
keep clothing and background identical
```
> **Mode:** Edit | **Reference Images:** 1 | **Tip:** Specify "naturally" to avoid exaggerated aging

### NSFW / Artistic Nude

> **Note:** Atlas Cloud supports uncensored generation for artistic and creative expression. Please use responsibly.

#### 31. Classical Painting Study
```
A renaissance-style oil painting of reclining Venus in a garden setting,
inspired by Titian and Botticelli, warm golden light,
draped silk fabrics, flowers and fruit in the scene,
museum-quality fine art painting, classical composition
```
> **Resolution:** 2K | **Aspect Ratio:** 16:9 | **Tip:** Classical art references produce tasteful results

#### 32. Life Drawing Study
```
An artistic charcoal figure drawing study, classical contrapposto pose,
dramatic chiaroscuro lighting from a single window,
textured paper background, fine art academy style,
anatomically accurate, expressive mark-making
```
> **Resolution:** 2K | **Aspect Ratio:** 3:4 | **Tip:** "Life drawing study" and "fine art" set appropriate tone

#### 33. Sculptural Photography
```
A black and white fine art photograph of a dancer in motion,
long exposure capturing flowing movement, marble-like skin texture,
dramatic studio lighting with strong shadows,
inspired by Robert Mapplethorpe, gallery-quality print
```
> **Resolution:** 2K | **Aspect Ratio:** 4:5 | **Tip:** Photography references maintain artistic intent

#### 34. Fantasy Art
```
A mythological siren emerging from moonlit ocean waves,
bioluminescent sea creatures around her, flowing hair merging with water,
fantasy digital painting, ethereal and otherworldly atmosphere,
cool blue and silver color palette
```
> **Resolution:** 2K | **Aspect Ratio:** 3:4 | **Tip:** Mythological framing adds creative depth

### Memes & Viral Content

#### 35. Trending Style Meme
```
A photorealistic image of a cat wearing a tiny business suit
sitting at a corporate board meeting, other cats in suits around
the conference table, one cat presenting a pie chart about "fish imports",
office photography style, humorous
```
> **Resolution:** 1K | **Aspect Ratio:** 1:1 | **Tip:** Humor + realism = viral potential

#### 36. Current Events Mashup
```
Create an image in the style of a breaking news broadcast,
lower third graphics reading "BANANA PRICES HIT ALL-TIME HIGH",
news anchor desk setup, professional broadcast studio,
dramatic serious mood about a silly topic
```
> **Resolution:** 2K | **Aspect Ratio:** 16:9 | **Tip:** Google Search integration helps with current visual formats

#### 37. Reaction Image
```
A renaissance painting of a nobleman looking at his phone with an
expression of absolute shock and disbelief, oil painting style,
ornate gold frame visible, museum lighting,
contrast between historical setting and modern device
```
> **Resolution:** 1K | **Aspect Ratio:** 1:1 | **Tip:** Anachronistic humor generates highly shareable content

#### 38. Brand Parody
```
A luxury fashion brand advertisement but for everyday mundane objects,
a single pencil on a marble pedestal with dramatic lighting,
"HAUTE STATIONERY" text in elegant serif font,
high-end commercial photography, satirical
```
> **Resolution:** 2K | **Aspect Ratio:** 4:5 | **Tip:** Parody works best with specific high-end aesthetics

#### 39. AI Art Meta
```
An AI robot sitting at an easel painting a landscape,
but the landscape on the canvas is a photo of another AI painting,
infinite recursive loop visible in mirrors behind,
photorealistic style, philosophical concept art
```
> **Resolution:** 2K | **Aspect Ratio:** 1:1 | **Tip:** Self-referential AI art resonates with tech audiences

#### 40. Absurdist Photorealism
```
A perfectly ordinary suburban house but it's made entirely of cheese,
photorealistic detail, cheddar walls, mozzarella curtains,
swiss cheese windows, neighborhood setting,
real estate listing photography style, completely serious tone
```
> **Resolution:** 2K | **Aspect Ratio:** 16:9 | **Tip:** "Completely serious tone" for absurd subjects maximizes humor

#### 41. Historical Figure Reimagined
```
Napoleon Bonaparte as a modern startup CEO giving a TED talk,
wearing a slim-fit navy suit with his iconic hand-in-vest pose,
large screen behind him showing a pitch deck titled "Conquering Markets",
conference hall setting, professional event photography
```
> **Resolution:** 2K | **Aspect Ratio:** 16:9 | **Tip:** Historical + modern juxtaposition creates compelling images

#### 42. Fake Album Cover
```
An indie rock album cover titled "CTRL+Z" featuring a person
standing in a field of floating undo icons, vaporwave color palette,
dreamy atmosphere, vinyl record mockup style,
nostalgic yet futuristic aesthetic
```
> **Resolution:** 2K | **Aspect Ratio:** 1:1 | **Tip:** Album art square format at 2K is ideal for sharing

---

## 📝 Prompt Engineering Guide

### Resolution Optimization

Choose the right resolution for your use case to balance quality and cost:

| Resolution | Best For | Cost (Atlas Cloud) |
|-----------|----------|-------------------|
| **512px (0.5K)** | Thumbnails, quick drafts, social media icons | $0.072 |
| **1024px (1K)** | Social media posts, web content, pixel art | $0.072 |
| **2048px (2K)** | Print-ready, detailed photography, professional | $0.072 |
| **4096px (4K)** | Large prints, wallpapers, commercial assets | $0.072 |

> **Pro tip:** On Atlas Cloud, all resolutions cost the same $0.072, so always go for 2K or 4K!

### Reference Image Best Practices

Nano Banana 2 supports up to **14 reference images**. Here's how to use them effectively:

| # of Refs | Use Case | Best Approach |
|-----------|----------|---------------|
| 1 | Style transfer, editing | Provide clear, high-quality source |
| 2-3 | Style + subject + color | Assign each ref a specific role in prompt |
| 4-7 | Multi-element composition | Describe which elements come from which ref |
| 8-14 | Complex brand/design systems | Use for maintaining consistency across variations |

**Tips:**
- Label references in your prompt: "Use the style from image 1, subject from image 2"
- Higher quality reference images produce better results
- Consistent lighting across references helps coherence
- Square-cropped references tend to work best

### Google Search Integration Tricks

Nano Banana 2 can leverage Google Search for real-time visual information:

- **Brand Accuracy:** "The exact Tesla Cybertruck design" — pulls current product design
- **Current Events:** "2026 Oscar ceremony red carpet" — references actual event aesthetics
- **Trending Styles:** "Currently trending fashion on Instagram" — taps into real-time trends
- **Cultural References:** "The viral TikTok aesthetic" — understands current meme culture
- **Factual Content:** "The actual layout of Times Square" — geographically accurate scenes

### Style Keywords That Work Best

| Category | Effective Keywords |
|----------|-------------------|
| **Photography** | `shot on [camera]`, `[film stock] aesthetic`, `f/[aperture]`, `golden hour` |
| **Digital Art** | `concept art`, `digital painting`, `matte painting`, `[artist] style` |
| **Illustration** | `watercolor`, `ink wash`, `vector`, `flat design`, `line art` |
| **3D Render** | `Octane render`, `Unreal Engine 5`, `ray tracing`, `subsurface scattering` |
| **Vintage** | `retro`, `analog`, `grain`, `faded colors`, `polaroid`, `VHS` |
| **Mood** | `dramatic`, `ethereal`, `moody`, `whimsical`, `dark`, `vibrant` |

### Aspect Ratio Guide

| Ratio | Dimensions | Use Case |
|-------|-----------|----------|
| **1:1** | 2048×2048 | Social media, album art, profile pictures |
| **4:5** | 1638×2048 | Instagram posts, portraits |
| **3:4** | 1536×2048 | Product photography, portraits |
| **16:9** | 2048×1152 | YouTube thumbnails, desktop wallpapers |
| **9:16** | 1152×2048 | Mobile wallpapers, Stories, TikTok |
| **21:9** | 2048×878 | Ultrawide, cinematic landscapes |
| **2:3** | 1365×2048 | Posters, print media |

### Output Format Guide

| Format | Best For | Notes |
|--------|----------|-------|
| **PNG** | Graphics, text, logos, transparency | Lossless, larger file size |
| **JPEG** | Photography, gradients, web use | Smaller files, slight compression |
| **WebP** | Web optimization | Best size-to-quality ratio |

---

## 💰 Pricing Deep Dive

### Nano Banana 2: Atlas Cloud vs Google Official

| Resolution | Google Official | Atlas Cloud | Difference |
|-----------|----------------|-------------|------------|
| **0.5K** (512px) | $0.045 | $0.072 | Google cheaper by $0.027 |
| **1K** (1024px) | $0.067 | $0.072 | Google cheaper by $0.005 |
| **2K** (2048px) | $0.101 | **$0.072** | **✅ Atlas 29% cheaper!** |
| **4K** (4096px) | $0.151 | **$0.072** | **✅ Atlas 52% cheaper!** |

> **Key insight:** Atlas Cloud offers **flat pricing** at $0.072 for ALL resolutions. The higher the resolution you need, the more you save. For 4K images, you save over **50%** compared to Google's official pricing!

### Volume Comparison (1,000 Images)

| Resolution | Google Cost | Atlas Cloud Cost | You Save |
|-----------|-----------|-----------------|----------|
| 1,000 × 0.5K | $45.00 | $72.00 | -$27.00 |
| 1,000 × 1K | $67.00 | $72.00 | -$5.00 |
| 1,000 × 2K | $101.00 | **$72.00** | **$29.00** |
| 1,000 × 4K | $151.00 | **$72.00** | **$79.00** |

### 💡 First-Time Bonus

Atlas Cloud offers a **25% bonus on your first recharge** (up to $100 bonus). That means:

| Top-Up Amount | Bonus (25%) | Total Credits | Effective Rate for 4K |
|--------------|-------------|---------------|----------------------|
| $10 | $2.50 | $12.50 | $0.058/image |
| $50 | $12.50 | $62.50 | $0.058/image |
| $100 | $25.00 | $125.00 | $0.058/image |
| $400 | $100.00 | $500.00 | $0.058/image |

> With the first-time bonus, your effective rate drops to **$0.058 per image** at ANY resolution — that's **62% cheaper** than Google's 4K pricing!

**[👉 Claim Your 25% Bonus on Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)**

### Atlas Cloud vs fal.ai — Price Comparison

| Model | fal.ai | Atlas Cloud | Notes |
|:------|:-------|:-----------|:------|
| **Nano Banana 2** | $0.0398/img | $0.072/img | fal.ai is cheaper per image, but Atlas Cloud offers unified API with 46 models in one endpoint |
| **Flux Kontext Pro** | $0.04/img | — | Available on fal.ai |
| **Seedream V4** | $0.03/img | $0.032/img | Very similar pricing |
| **Flux Dev** | — | $0.012/img | Atlas Cloud is very competitive for Flux Dev |

> **Why choose Atlas Cloud even when fal.ai is cheaper on some models?**
> - **Unified API** — 46 image models with one API key, one endpoint, one billing account
> - **Uncensored mode** — No content filtering on supported models
> - **Batch generation** — Generate up to 15 images per request (Seedream Sequential)
> - **LoRA support** — Use custom LoRA models across all compatible models
> - **Flat pricing** — No surprise costs at higher resolutions (e.g., Nano Banana 2 is $0.072 for ALL resolutions up to 4K)

---

## 🌐 Google Image Model Family on Atlas Cloud

Atlas Cloud provides access to Google's complete image generation lineup:

| Model | Price | Speed | Quality | Best For |
|-------|-------|-------|---------|----------|
| **Nano Banana 2** | $0.072 | ⚡⚡⚡ | ⭐⭐⭐⭐ | Latest & fastest, general purpose |
| **Nano Banana 2 Edit** | Available | ⚡⚡⚡ | ⭐⭐⭐⭐ | Image editing & modification |
| **Nano Banana Pro** | Available | ⚡⚡ | ⭐⭐⭐⭐⭐ | Professional quality output |
| **Nano Banana** | Available | ⚡⚡⚡ | ⭐⭐⭐ | Budget-friendly original |
| **Imagen4 Ultra** | Available | ⚡ | ⭐⭐⭐⭐⭐ | Highest quality, flagship |
| **Imagen4** | Available | ⚡⚡ | ⭐⭐⭐⭐ | Balanced quality & speed |
| **Imagen4 Fast** | Available | ⚡⚡⚡ | ⭐⭐⭐ | Quick iterations |
| **Imagen3** | Available | ⚡⚡ | ⭐⭐⭐ | Proven reliability |
| **Imagen3 Fast** | Available | ⚡⚡⚡ | ⭐⭐⭐ | Budget speed option |

> All models support text-to-image generation. Developer variants available for Nano Banana 2 (text-to-image and edit).

**[👉 Explore All Models on Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)**

---

## 📚 Official Resources

- **[Google AI Studio](https://aistudio.google.com/)** — Free playground for Nano Banana 2 (with daily limits)
- **[Vertex AI](https://cloud.google.com/vertex-ai/docs/generative-ai/image/overview)** — Enterprise API access via Google Cloud
- **[Gemini API Documentation](https://ai.google.dev/docs)** — Official API reference and guides
- **[Google AI Blog](https://blog.google/technology/ai/)** — Announcements and research papers
- **[Gemini App](https://gemini.google.com/)** — Consumer access via Gemini (Fast/Thinking/Pro modes)
- **[Google Cloud Pricing](https://cloud.google.com/vertex-ai/pricing)** — Official pricing page

---

## 🛠️ Community Resources

### Tools & Libraries

- **[Atlas Cloud API](https://www.atlascloud.ai?ref=JPM683)** — Cost-effective API access to Nano Banana 2 and all Google image models
- **[ComfyUI-NanoBanana](https://github.com/comfyanonymous/ComfyUI)** — ComfyUI integration for Nano Banana 2
- **[NB2-Gradio](https://huggingface.co/spaces)** — Gradio web UI for quick testing
- **[nb2-batch](https://github.com/)** — Batch processing tool for Nano Banana 2
- **[Auto1111 NB2 Extension](https://github.com/)** — Automatic1111 WebUI extension

### Tutorials & Articles

- [How to Use Nano Banana 2 for Product Photography](https://blog.google/) — Google AI Blog
- [Nano Banana 2: A Complete Guide](https://www.atlascloud.ai?ref=JPM683) — Atlas Cloud Blog
- [Nano Banana 2 vs Flux vs Midjourney: The Ultimate Comparison](https://www.atlascloud.ai?ref=JPM683) — Atlas Cloud
- [Mastering Multi-Reference Image Generation](https://ai.google.dev/) — Google Developers

### Communities

- [r/NanoBanana](https://reddit.com/r/NanoBanana) — Reddit community
- [Nano Banana Discord](https://discord.gg/) — Community Discord server
- [Hacker News Discussions](https://news.ycombinator.com/) — Where the viral moment began
- [Google AI Discord](https://discord.gg/) — Official Google AI community

---

## ❓ FAQ

### What is Nano Banana 2?

Nano Banana 2 is Google's Gemini 3.1 Flash Image model, released February 26, 2026. It is an AI image generation and editing model that supports output from 512px to 4K resolution, accepts up to 14 reference images, and integrates Google Search for real-time visual information. It is the default image generation model in the Gemini App. "Nano Banana" is its community nickname.

### How much does Nano Banana 2 cost?

Google's official pricing ranges from $0.045 (0.5K) to $0.151 (4K) per image. **Atlas Cloud** offers a flat rate of **$0.072 per image at ANY resolution**, making it significantly cheaper for 2K and 4K generation — up to **52% cheaper** for 4K images. First-time users also get a 25% bonus on their initial top-up.

### Nano Banana 2 vs Flux — which is better?

Nano Banana 2 excels in speed, maximum resolution (4K vs Flux's 2K), reference image support (14 vs 1), built-in image editing, Google Search integration, and text rendering. Flux's advantages include being open-source and having no content restrictions by default. For production use, Nano Banana 2 is generally more capable and faster.

### Nano Banana 2 vs Midjourney — which should I use?

Nano Banana 2 offers API access (Midjourney doesn't), higher max resolution (4K vs 2K), more reference images (14 vs 4), and Google Search integration. Midjourney has a strong community and distinct aesthetic style. For developers and API-based workflows, Nano Banana 2 is the clear choice.

### Can Nano Banana 2 generate NSFW content?

Google's official API has content restrictions. However, **Atlas Cloud** provides uncensored access to Nano Banana 2, allowing artistic and creative expression without content filtering. This is particularly useful for fine art, figure drawing, and other legitimate artistic use cases.

### What's the best resolution for Nano Banana 2?

It depends on your use case. For social media, 1K is sufficient. For professional photography and print, use 2K. For large-format prints, wallpapers, and commercial assets, use 4K. **On Atlas Cloud, all resolutions cost the same $0.072**, so there's no reason not to use 2K or 4K!

### How fast is Nano Banana 2?

Nano Banana 2 is widely considered the fastest AI image generator available. Typical generation times are under 3 seconds for 1K images and under 8 seconds for 4K images, making it suitable for real-time creative workflows and interactive applications.

### Can Nano Banana 2 generate text in images?

Yes! Text rendering is one of Nano Banana 2's standout features. It handles short text (1-3 words) exceptionally well and can produce readable text of up to 10-15 words. For best results, use clear typography instructions and keep text concise.

### How many reference images can I use?

Nano Banana 2 supports up to **14 reference images** simultaneously. You can assign different roles to each reference (style, subject, color palette, composition, etc.) for precise control over the output.

### Does Nano Banana 2 support image editing?

Yes. Nano Banana 2 includes a dedicated editing mode that can perform style transfer, background replacement, object removal, color grading, seasonal changes, and many other modifications while maintaining the integrity of unedited regions.

---

<div align="center">

## 🍌 Generate Stunning Images with Nano Banana 2

**Get Google's most powerful image model at unbeatable prices.**

| Benefit | Details |
|---------|---------|
| ✅ **52% Cheaper** | Than Google for 4K images |
| ✅ **Uncensored** | No content restrictions |
| ✅ **All Google Models** | Nano Banana 2, Imagen4 Ultra, and more |
| ✅ **25% Bonus** | On first top-up (up to $100) |
| ✅ **Flat Pricing** | $0.072 for ANY resolution up to 4K |

### [👉 Start Generating on Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)

---

## ⭐ Star History

If you find this resource helpful, please give it a star! It helps others discover the best Nano Banana 2 resources.

[![Star History Chart](https://api.star-history.com/svg?repos=your-org/awesome-nano-banana-2&type=Date)](https://star-history.com/#your-org/awesome-nano-banana-2&Date)

---

## 🤝 Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/add-resource`)
3. Commit your changes (`git commit -m 'Add new resource'`)
4. Push to the branch (`git push origin feature/add-resource`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

**Made with 🍌 by the community. Not officially affiliated with Google.**

</div>
