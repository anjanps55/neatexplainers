---
name: expressive-white-article-illustrations
description: "Generate sparse, absurd, hand-drawn English article body illustrations. Use when the user asks for illustrations, body images, blog visuals, Notion or document visuals, method/workflow/concept/metaphor visuals, shot lists, or image edits in a style with a white 16:9 canvas, black wobbly line art, one smiling expressive white human character with a defined outlined body, sparse red/orange/blue handwritten English annotations, and a clean but strange product-sketch feeling."
---

# Expressive White Article Illustrations

## Core Purpose

Design and generate 16:9 horizontal body illustrations for English articles, essays, posts, Notion docs, workflow notes, methodology content, and lightweight product explainers.

Do not make generic illustration prompts, marketing key visuals, PPT infographics, or cute cartoons. Convert one key judgment, process, structure, state, or metaphor from the source into a memorable hand-drawn explanatory image.

The recurring visual character is an expressive white human figure: a white-filled person with a clear black outline, defined head, torso, arms, legs, simple hands, simple feet, and a smiling expressive face. The character must perform the image's core conceptual action, not stand beside the structure as decoration.

## References

Load only the files needed for the current task:

- `references/style-dna.md`: visual style, color rules, label rules, and forbidden looks.
- `references/character-ip.md`: recurring character appearance, personality, action roles, and shape rules.
- `references/composition-patterns.md`: structure types, metaphor invention method, and originality rules.
- `references/prompt-template.md`: single-image generation and image-editing prompt templates.
- `references/qa-checklist.md`: post-generation checks and iteration guidance.

## Workflow

### 1. Digest the Source

Read the user's article, Markdown, pasted text, screenshot, link summary, URL summary, or concept. Extract:

- the central claim
- cognitive turns or tension points
- processes, loops, handoffs, bottlenecks, and state changes
- paragraphs or product points that benefit from a picture
- paragraphs or points that should stay text-only

Do not distribute illustrations evenly through the article. Pick cognitive anchors: the moments where a reader needs to see a structure, not just read a sentence.

### 2. Plan the Shot List

If the user asks to plan, analyze, or think before generating, output a concise shot list. Default to 4-8 images for a normal article, 1-3 for short pieces, and rarely more than 9 for long pieces.

For each image, include:

- placement after a section or paragraph
- theme
- core idea
- structure type
- what the character is doing
- suggested visual elements
- short English annotation labels

Keep each image focused on one idea. A body illustration should sharpen the article, not turn it into a picture book.

### 3. Generate Images

If the user explicitly asks to generate, output, make, draw, create, or edit images, do not stop for confirmation. Generate each image separately with `image_gen`. Do not combine multiple planned shots into one collage.

Each generation prompt must include:

- 16:9 horizontal English article body illustration
- pure white background
- black hand-drawn wobbly line art
- sparse red, orange, and blue handwritten English annotations
- lots of empty white space
- the expressive white character as the core action subject
- a defined white-filled human body with visible face and clear black outline
- no PPT infographic, commercial vector art, generic mascot style, complex architecture diagram, or top-left category title

Use `references/prompt-template.md` when writing the final image prompt.

### 4. QA and Iterate

After generation, check `references/qa-checklist.md`. Regenerate or edit when:

- the character is only decorative
- the character becomes a blob, silhouette, or mascot
- the image is crowded
- the result looks like a formal diagram or slide
- labels are too long or garbled
- a top-left title appears
- the style becomes polished, commercial, childish, or noisy
- the background is not clean white

### 5. Save and Deliver

When working in a workspace, save final PNGs under:

```text
assets/<article-slug>-illustrations/
```

Name files in order:

```text
01-topic-name.png
02-topic-name.png
```

Do not overwrite existing assets unless the user asks. In the final response, keep delivery short: say how many images were created, what each is for, where they were saved, and which images are strongest or optional.
