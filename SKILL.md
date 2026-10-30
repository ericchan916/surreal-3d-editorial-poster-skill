---
name: surreal-3d-editorial-poster-skill
description: Generate a Simplified-Chinese 9:16 poster in the 「超现实3D」(surreal-3d-editorial) style by 一张有戏. Use when the user wants a 超现实3D / surreal 3d editorial poster.
---

# 超现实3D · surreal-3d-editorial poster skill

一张有戏「超现实3D」风格海报技能。输出一张 9:16 竖版、简体中文的独立海报。

## 用法
1. 确定一个主标题（2–4 字）和一句短句。
2. 画面只出现三段文字：主标题、短句、页脚「一张有戏 · 视觉习作」。
3. 版式可选：centered-hero, frame-within-frame。
4. 参照下方完整提示词模板，替换 Headline / Supporting phrase / 场景描述。

## 示例主题
- 把云装进口袋：让轻盈拥有一个容器（centered-hero）— One oversized soft cobalt cloth pocket holding a physically believable fluffy white cloud, studio cream cyclorama and soft shadow.
- 窗里的海：把远方放进日常的尺度（frame-within-frame）— One minimal glass window frame containing a miniature ocean with small waves, standing as impossible sculptural object on cream studio floor.
- 轻一点：让重量有另一种答案（centered-hero）— One heavy rough stone sphere supported impossibly by one fine feather, believable studio materials and generous quiet ivory space.
- 柔软的边界：让坚硬也学会弯折（frame-within-frame）— One sculptural chrome ribbon knotted like soft fabric, realistic reflections and matte coral plane, no extra fantasy clutter.
- 时间开花：让流逝拥有可见的形状（centered-hero）— One clear glass hourglass whose upper chamber grows a single sculptural blossom, physically coherent glass/light and graphite studio ground.
- 折叠日常：把熟悉的形状重新打开（frame-within-frame）— One giant blank paper cup whose side folds into an impossible miniature staircase, precise paper material and cream/cobalt studio lighting.
- 月亮来信：把夜色折进一封信里（centered-hero）— One open ivory envelope holding a small softly lit rough moon sphere, subtle violet shadow and quiet premium studio photograph.
- 重力之外：让稳定拥有新的关系（frame-within-frame）— One inverted balanced stone arch floating a few centimeters above cream floor, grounded realistic shadow and one cobalt object detail.

## 完整提示词模板（第 1 张原文）
```
Use case: ads-marketing. Create exactly ONE polished professional 9:16 portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: 把云装进口袋. Supporting phrase: 让轻盈拥有一个容器. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.

SOURCE UNIVERSAL RULES:


These rules apply to every poster. Do not repeat them in layout or style notes.

- Build around one dominant message, one clear focal point, and one communication goal.
- Establish a simple reading order: headline -> focal image -> supporting copy -> supplied details.
- Preserve required copy exactly unless the user explicitly asks for rewriting.
- Keep important text readable, high-contrast, and inside safe margins.
- Use confident spacing and avoid overstuffed layouts.
- Avoid fake extra text, random logos, QR codes, decorative clutter, malformed typography, and generic AI-poster noise.
- Treat the poster canvas as static print/editorial artwork rather than a clickable interface. If the source explicitly requests a product UI, browser window, dashboard, or device mockup, preserve that depicted content inside the poster.
- CTA copy is extractive-only: include it only when the source explicitly supplies the wording. When output language differs, verify the translated CTA against a recorded exact source quote. Never invent action or status labels.
- If no CTA is sourced, leave the action area empty. If one is sourced, render it as ordinary poster typography in a footer or text lockup. Do not place poster-level action copy inside a button, rounded rectangle, pill, chip, capsule, tab, input field, or any other clickable-looking UI container; do not decorate it with a shadow, arrow, chevron, or cursor icon.



SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Surreal 3D Editorial

## Intent

Create a premium editorial poster using surreal 3D objects, impossible scale, studio lighting, and conceptual art direction.

## Typography

- Use clean editorial sans-serif or refined serif paired with strong object composition.
- Keep type secondary to the surreal visual unless the headline is the concept.
- Place text in calm negative space.

## Palette

Studio neutrals with one surreal accent: clay, cream, graphite, cobalt, acid green, coral, violet, chrome.

## Imagery

Floating objects, impossible architecture, oversized everyday items, abstract sculptures, soft 3D forms, dreamlike product metaphors.

## Texture / Material

Matte clay, chrome, glass, rubber, velvet, soft shadows, studio cyclorama, realistic lighting.

## Composition Rules

- Use one clear surreal idea.
- Make the impossible object feel physically believable.
- Preserve strong negative space for typography.
- Use lighting and shadow to create premium realism.

## Avoid

Random fantasy clutter, incoherent objects, plastic-looking cheap 3D, warped text, and overcomplicated scenes.


INTERNAL COMPOSITION:
# Centered Hero

## Composition Structure

- Place one dominant subject in the optical center.
- Keep headline above, below, or tightly integrated with the hero subject.
- Use symmetrical or near-symmetrical balance with subtle asymmetry for sophistication.
- Reserve the bottom area for source-supplied date, location, sponsor, or other factual details. If the source includes action copy, typeset it as a plain footer line rather than a button.

## Hierarchy Rules

1. Hero subject and headline compete as a unified first read.
2. Subheadline supports the meaning without fragmenting attention.
3. Details sit smaller in a stable footer or corner lockup.

## Text Placement

- Use large, simple headline blocks.
- Keep secondary copy outside the hero silhouette.
- Avoid placing small text over textured image areas.

## Image Treatment

Use a clean product/person/object/abstract hero with strong lighting, crisp edges, and controlled background separation.

## Spacing Rules

Use generous margins and breathing room around the hero. Do not fill every corner.

## Aspect-Ratio Behavior

Works especially well in `2:3`, `3:4`, `4:5`, and `9:16`. In `16:9`, widen the hero and shift text into side gutters.

## Avoid

Multiple competing subjects, busy backgrounds, small scattered text, and generic centered stock-poster symmetry.


SPECIFIC SUBJECT AND ART DIRECTION:
One oversized soft cobalt cloth pocket holding a physically believable fluffy white cloud, studio cream cyclorama and soft shadow.

Quality: exquisite thoughtful art direction, one immediate focal point, sophisticated typographic spacing and clear reading order, original expressive composition with wide enough safe margins. Headline large and readable at phone thumbnail; secondary text restrained, not generic template. Typography adapted sensitively to real Chinese glyphs, with the visual weight demanded by style. Material/light/print treatment consistent with selected style. If any person appears, fictional mainland Chinese adult, natural anatomy and authentic face; otherwise no people. All props physically coherent unless the SPECIFIC surreal idea deliberately changes physics. No trademarks or label text on products, no fake logos/watermarks/QR. No poster mockup, wall frame, multiple-poster collage, UI buttons or decorative website components. The creative theme must determine composition; vary crop, hierarchy and negative space across the series. Output one finished poster only.
```

全部 8 条提示词见 `PROMPTS.json`，来源见 `SOURCES.md`。
