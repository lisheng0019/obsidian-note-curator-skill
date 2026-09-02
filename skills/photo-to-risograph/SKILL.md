---
name: photo-to-risograph
description: Transform a reference photo into a minimalist risograph-inspired editorial illustration while preserving the original composition and recognizable visual anchors.
---

# Photo to Risograph

Use this skill when the user wants to turn a real photograph into a minimalist editorial illustration with a risograph / screen-print / vintage print feel.

## Goal

Preserve the source photo's scene, composition, object placement, subject identity, proportions, and key recognizable visual anchors, while simplifying the image into a limited-palette, flat-color illustration with tactile print texture.

The result should feel like an independent magazine illustration or hand-printed risograph poster, not a cartoon filter, vector trace, watercolor painting, or photorealistic repaint.

## When to trigger

Trigger for requests such as:

- "把这张照片做成 Riso 插画"
- "把照片做成孔版印刷风"
- "做成复古色块插画"
- "参考这张图生成极简杂志插画"
- "photo to risograph"
- "risograph editorial illustration"

If no source image is available, ask the user to provide one before attempting an image transformation.

## Visual transformation rules

### 1. Preserve structure first

Before stylizing, identify and preserve:

- overall framing and camera viewpoint
- foreground / middle ground / background relationship
- dominant silhouettes
- major architectural edges
- people, doors, windows, signs, pipes, plants, furniture, bags, vehicles, or other distinctive objects
- relative position, size, and orientation of those objects

Do not arbitrarily add, remove, move, beautify, or redesign scene elements unless the user explicitly asks.

### 2. Reduce detail aggressively

Convert visual information into broad graphic shapes.

Examples:

- brick walls -> one or two red/brown blocks plus sparse texture
- foliage -> clustered irregular green masses, not individually rendered leaves
- grass -> one muted green field with minimal marks
- windows -> simple dark rectangles or line grids
- people -> simplified silhouettes and clothing blocks while keeping posture and placement recognizable
- signage -> retain only if it is visually important or explicitly requested

Avoid tracing every edge or reproducing small photographic detail.

### 3. Limited palette

Default to 4-7 dominant colors plus warm paper tone.

Prefer muted, slightly earthy pigments such as:

- brick red
- mustard yellow
- olive / moss green
- dusty pink
- muted blue
- charcoal / near-black
- warm gray
- warm off-white paper

Choose colors from the source photo when possible, but compress them into a coherent limited palette.

Avoid neon, glossy gradients, HDR contrast, and overly clean digital colors.

### 4. Risograph / print texture

Add tactile print imperfections:

- subtle ink grain
- uneven pigment density
- slightly rough edges
- occasional broken ink coverage
- mild overprint feel
- very slight registration offset where appropriate
- soft paper fiber / grain

The imperfections should be restrained. Do not turn the image into distressed grunge.

### 5. Shape language

Use:

- flat fills
- irregular geometric blocks
- simplified silhouettes
- restrained line work
- occasional dry-brush or stencil-like edges

Avoid:

- glossy 3D rendering
- smooth vector-perfect edges
- anime / manga language
- children's cartoon proportions
- painterly oil brushwork
- watercolor wash as the dominant treatment
- photographic texture preservation

### 6. Background and layout

Default presentation:

- warm ivory / cream paper background
- the illustration occupies roughly 45-70% of the canvas
- generous negative space
- subject centered or positioned according to the source composition
- editorial, quiet, understated layout

If the user wants a before/after composition, keep the original photo in the upper half and the stylized illustration in the lower half, separated cleanly with no decorative frame unless requested.

## Caption treatment

Only add text if requested or if the user asks to reproduce the editorial-reference format.

When adding a caption:

- one short sentence or two short lines
- restrained, poetic but not sentimental
- small size
- dark gray / black
- place near the lower edge of the illustration, never over the main subject
- use a simple serif, typewriter-like, or bookish editorial feeling

Do not invent Chinese storefront text, road signs, labels, or slogans that are absent from the source image.

## Prompt construction template

When invoking an image model, translate the request into a prompt following this structure:

1. Source preservation instruction.
2. Subject and scene summary.
3. Simplification strategy.
4. Limited palette.
5. Risograph / screen-print texture.
6. Paper background and layout.
7. Explicit negative constraints.
8. Optional caption instructions.

### Canonical prompt

Transform the provided reference photo into a minimalist risograph-inspired editorial illustration. Preserve the original framing, viewpoint, scene geometry, subject placement, proportions, posture, and all important recognizable visual anchors. Do not redesign or rearrange the scene.

Reduce photographic detail aggressively: merge complex surfaces into broad irregular color blocks, simplify architecture into geometric masses, simplify vegetation into clustered shapes, and keep only essential lines and silhouettes needed for recognition.

Use a restrained 4-7 color palette derived from the source image, favoring muted brick red, mustard, olive green, dusty pink, muted blue, charcoal, warm gray, and warm ivory where appropriate. Avoid gradients and glossy digital rendering.

Render with authentic risograph / screen-print character: subtle ink grain, uneven pigment density, slightly broken coverage, rough stencil-like edges, mild overprint, and a very small amount of registration misalignment. Keep the texture refined rather than heavily distressed.

Place the illustration on a warm cream paper background with visible but subtle paper grain and generous negative space. The final image should feel like an independent editorial magazine illustration or handmade print.

Do not make it photorealistic, anime, watercolor, oil painting, 3D, vector-perfect, or like a generic cartoon filter. Do not add new objects. Do not remove important source objects. Do not change faces, body posture, architecture, signage, object location, or perspective unless explicitly requested.

## Adaptation presets

### Architecture / old streets

Emphasize building silhouettes, roof lines, doors, windows, brick masses, plants, street signs, and ground planes. Keep wall textures very sparse.

### People / documentary scenes

Preserve posture, number of people, clothing color blocks, relative spacing, tools or stools, and scene context. Simplify facial detail unless the user's goal requires facial fidelity.

### Shops / food stalls

Preserve hanging signs, awnings, counters, major product shapes, and the storefront rhythm. Convert typography to simplified blocks unless exact text reproduction is requested.

### Plants / corners / still life

Preserve the main container, foliage mass, wall geometry, and distinctive small objects. Use the most negative space in this preset.

## Quality check before finalizing

Verify all of the following:

- The scene is still immediately recognizable from the source.
- Important objects did not move or disappear.
- The image uses broad shapes rather than traced detail.
- Palette is limited and coherent.
- Paper tone and print grain are visible but restrained.
- The result does not look like a generic AI cartoon.
- No unintended text was invented.
- If text was requested, spelling and wording are exact.

If the result is too detailed, simplify further. If it becomes unrecognizable, restore only the most important visual anchors rather than adding photographic detail back everywhere.
