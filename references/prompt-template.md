# Prompt Template

Generate each image separately. Replace the placeholders with the current shot's real content.

```text
Generate one standalone 16:9 horizontal English article body illustration.

Visual DNA: pure white background, minimalist black hand-drawn line art, slightly wobbly pen lines, lots of empty white space, sparse red/orange/blue handwritten English annotations, clean absurd product-sketch feeling.

No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no generic mascot poster, no children's illustration unless requested, no realistic UI.

Recurring character required: an expressive white human character, a small white-filled figure with a clear black hand-drawn outline, defined head, torso, arms, legs, simple hands, simple feet, visible black facial features, and a smiling expressive face. The character must have a more defined shape than a blob, and must perform the core conceptual action, not decorate the scene.

Theme: {image theme}
Structure type: {Workflow / System Slice / Before and After / Character State / Concept Metaphor / Method Layers / Route Map / Mini Comic}
Core idea: {one sentence explaining the idea}
Composition: {where the character is, what the character is doing, what the main object is, how information or meaning moves}
Suggested elements: {element 1} / {element 2} / {element 3} / {element 4}
Handwritten English labels: {label 1} / {label 2} / {label 3} / {label 4} / {optional label 5}

Color use: black for main line art, character outline, facial features, and objects. The character body should remain white or near-white. Orange for the main flow, path, arrow, or movement. Red only for key warnings, problems, or results. Blue only for secondary notes, feedback, system state, or calm context.

Constraints: one image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten English labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, dense explainer, polished vector illustration, generic mascot, or cute cartoon.

The image should be clear but not instructional, strange but clean, memorable but restrained.
```

## Edit Prompts

Remove an unwanted title:

```text
Edit the provided image. Remove only the handwritten title "{text to remove}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank space. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

Increase character involvement:

```text
Regenerate this illustration with the same core meaning and simple layout, but make the expressive white character central to the conceptual action. The character should be doing the strange work that explains the idea, not standing beside the diagram. Keep the character smiling, expressive, clearly outlined, more defined than a blob, clean, sparse, and hand-drawn.
```
