# Photo to Risograph Skill

A reusable image-transformation skill for turning reference photographs into minimalist risograph-inspired editorial illustrations.

## What it does

- Preserves the original photo composition and recognizable visual anchors
- Simplifies complex photographic detail into broad graphic color blocks
- Compresses the source into a restrained 4-7 color palette
- Adds subtle risograph / screen-print ink texture and paper grain
- Supports architecture, street scenes, documentary people, storefronts, plants, and still-life scenes
- Optionally supports small editorial captions

## Recommended use

Give the agent a source photo and say one of the following:

```text
把这张照片做成 Riso 插画。
```

```text
使用 photo-to-risograph skill 重绘这张照片，保持原构图，不添加文字。
```

```text
把照片处理成复古孔版印刷风极简色块插画，保留人物位置和服装颜色，并在右下角加一句很短的英文文案。
```

## Core visual language

`Risograph + screen print + minimalist editorial illustration + limited palette + rough ink texture + warm paper + negative space`

The target is not a generic cartoon filter. The skill deliberately prioritizes composition preservation, semantic simplification, limited colors, and tactile print imperfections.

## Files

- `SKILL.md` — complete agent instructions and prompt template
- `README.md` — usage notes

## Suggested installation

Copy the `photo-to-risograph` folder into the skills directory used by your Codex / Claude Code environment, or keep it in a project-level skills directory and reference it from your agent instructions.
