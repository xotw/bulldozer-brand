# Bulldozer Brand

Single source of truth for Bulldozer brand assets. Reference this repo from any project.

## Quick Reference

### Colors

| Name | Hex | Usage |
|------|-----|-------|
| **Bulldozer Yellow** | `#DDFF56` | Primary accent, CTAs, highlights |
| **Black** | `#000000` | Primary backgrounds, text |
| **Dark Green** | `#032300` | Secondary accent |
| **Grey** | `#C2C2C2` | Supporting text, dividers, muted elements |

### Fonts

| Font | Usage | Weight |
|------|-------|--------|
| **GT Pressura LCGV** | H1, H2, H3, titles, display | Bold |
| **GT Pressura LCGV Mono** | Captions, mentions, code, special text | Regular |
| **Inconsolata** | Website body text (fallback monospace) | 400, 700 |

Font files: download from Notion (Fonts_Bulldozer.zip) or use from `~/Library/Fonts/`

### Logos

Always use **Logo #1** (primary). Logos #2 and #3 are for exceptional use only.

Logo files are in `logos/` directory.

## Tailwind Config Snippet

Drop this into any project's `tailwind.config.ts`:

```typescript
colors: {
  bulldozer: {
    yellow: "#DDFF56",
    black: "#000000",
    dark: "#0a0a0a",
    gray: "#1a1a1a",
    border: "#2a2a2a",
    text: "#e0e0e0",
    muted: "#C2C2C2",
    green: "#032300",
  },
},
fontFamily: {
  display: ['"GT Pressura"', 'sans-serif'],
  mono: ['"GT Pressura Mono"', '"Inconsolata"', 'monospace'],
},
```

## CSS Variables

For non-Tailwind projects:

```css
:root {
  --bulldozer-yellow: #DDFF56;
  --bulldozer-black: #000000;
  --bulldozer-green: #032300;
  --bulldozer-grey: #C2C2C2;
  --font-display: 'GT Pressura', sans-serif;
  --font-mono: 'GT Pressura Mono', 'Inconsolata', monospace;
}
```

## Brand Voice

- **Tone:** Pragmatic, direct, solution-oriented. No bullshit.
- **Design philosophy:** Simplicity and performance. Design is a functional tool to reduce ambiguity and accelerate decisions.
- **Core values:** Pragmatism, "Disagree & Commit", Avant-gardiste

## Resources

- **Figma:** [Branding Bulldozer](https://www.figma.com/design/vHF7P8VAlvxcxvQuw2VSOj/Branding-Bulldozer)
- **Notion Brand Guide:** [Link](https://www.notion.so/576f066a6d3d472baaec62d493a94f6c)
- **Website:** [bulldozer-collective.com](https://www.bulldozer-collective.com)
