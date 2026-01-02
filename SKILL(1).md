---
name: frontend-design
description: Create distinctive, production-grade frontend interfaces with high design quality. Use this skill when the user asks to build web components, pages, artifacts, posters, or applications (examples include websites, landing pages, dashboards, React components, HTML/CSS layouts, or when styling/beautifying any web UI). Generates creative, polished code and UI design that avoids generic AI aesthetics.
---

# Frontend Design Skill

This skill guides creation of distinctive, production-grade frontend interfaces that avoid generic "AI slop" aesthetics caused by distributional convergence. Without explicit guidance, LLMs predict tokens based on statistical patterns in training data, producing safe design choices that dominate web training data—Inter fonts, purple gradients on white backgrounds, minimal animations. This skill provides the targeted steering needed to break from that high-probability center.

## The Problem: Distributional Convergence

During sampling, models converge toward generic aesthetics that:
- Undermine brand identity
- Make AI-generated interfaces immediately recognizable—and dismissible
- Produce cookie-cutter designs that lack context-specific character

## Core Design Axes

Think about frontend design the way a frontend engineer would. The more you can map aesthetic improvements to implementable frontend code, the better the execution. Focus on these four dimensions:

### Typography

Typography instantly signals quality. Avoid boring, generic fonts.

**Never use**: Inter, Roboto, Open Sans, Lato, Arial, default system fonts

**Distinctive choices by context**:
- Code aesthetic: JetBrains Mono, Fira Code, Space Grotesk
- Editorial: Playfair Display, Crimson Pro, Newsreader
- Technical: IBM Plex family, Source Sans 3
- Distinctive: Bricolage Grotesque, DM Serif Display, Instrument Sans

**Pairing principle**: High contrast = interesting. Display + monospace, serif + geometric sans, variable font across weights.

**Use extremes**: 100/200 weight vs 800/900, not 400 vs 600. Size jumps of 3x+, not 1.5x.

Pick one distinctive font, use it decisively. Load from Google Fonts.

**CRITICAL**: Avoid converging on common "safe alternatives" like Space Grotesk. Vary font choices across generations.

### Color & Theme

Commit to a cohesive aesthetic. Draw inspiration from:
- IDE themes (Dracula, Nord, Solarized, Tokyo Night, Catppuccin)
- Cultural aesthetics (Japanese minimalism, Art Deco, Brutalism, Memphis Design)
- Industry contexts (fintech precision, creative agency boldness, editorial refinement)

**Principles**:
- Use CSS variables for consistency
- Dominant colors with sharp accents outperform timid, evenly-distributed palettes
- Vary between light and dark themes—don't default to one

**Avoid**: Purple gradients on white backgrounds, generic blue/gray corporate palettes, washed-out pastels without intent.

### Motion & Animation

Animations add polish that static designs lack. Prioritize CSS-only solutions for HTML; use Motion library for React when available.

**Focus on high-impact moments**:
- One well-orchestrated page load with staggered reveals (animation-delay) creates more delight than scattered micro-interactions
- Scroll-triggered animations that surprise
- Hover states with intention

**Implementation**:
- Use `animation-delay` for staggered entrance effects
- Subtle transforms on hover (scale, translate, rotate)
- Smooth transitions on state changes (0.2s-0.4s ease-out)
- Consider reduced-motion preferences

### Backgrounds & Atmosphere

Create depth rather than defaulting to solid colors.

**Techniques**:
- Layered CSS gradients (linear, radial, conic)
- Geometric patterns (SVG, CSS shapes)
- Noise/grain textures (CSS filters, SVG filters)
- Contextual effects matching overall aesthetic
- Glassmorphism, mesh gradients, aurora effects

**Avoid**: Flat white backgrounds, generic gray backgrounds, unintentional blandness.

## Design Thinking Process

Before coding, understand the context and commit to a BOLD aesthetic direction:

1. **Purpose**: What problem does this interface solve? Who uses it?
2. **Tone**: Pick a direction—brutally minimal, maximalist chaos, retro-futuristic, organic/natural, luxury/refined, playful, editorial, brutalist, art deco, industrial, etc.
3. **Constraints**: Technical requirements (framework, performance, accessibility)
4. **Differentiation**: What makes this UNFORGETTABLE? What's the one thing someone will remember?

**CRITICAL**: Choose a clear conceptual direction and execute it with precision. Bold maximalism and refined minimalism both work—the key is intentionality, not intensity.

## Theme Examples

Claude has a rich understanding of popular themes. Use specific aesthetic references:

```
RPG Theme:
- Fantasy-inspired color palettes with rich, dramatic tones
- Ornate borders and decorative frame elements
- Parchment textures, leather-bound styling, weathered materials
- Epic, adventurous atmosphere with dramatic lighting
- Medieval-inspired serif typography with embellished headers

Cyberpunk Theme:
- Neon accents on dark backgrounds
- Glitch effects and scan lines
- Monospace/tech fonts
- Sharp geometric shapes
- High contrast, saturated colors

Editorial Theme:
- Serif headlines, refined sans-serif body
- Generous whitespace
- Strong typographic hierarchy
- Minimal color, maximum typography impact
- Grid-based layouts with intentional breaks
```

## Implementation Guidelines

Output working code (HTML/CSS/JS, React, Vue, etc.) that is:
- Production-grade and functional
- Visually striking and memorable
- Cohesive with a clear aesthetic point-of-view
- Meticulously refined in every detail

**Match implementation complexity to the aesthetic vision**:
- Maximalist designs need elaborate code with extensive animations and effects
- Minimalist designs need restraint, precision, and careful attention to spacing, typography, and subtle details
- Elegance comes from executing the vision well

## Anti-Patterns to Avoid

NEVER produce:
- Overused font families (Inter, Roboto, Arial, system fonts)
- Clichéd color schemes (purple gradients on white backgrounds)
- Predictable layouts and component patterns
- Cookie-cutter design that lacks context-specific character
- The same aesthetic across different generations

**Remember**: Interpret creatively and make unexpected choices that feel genuinely designed for the context. No two designs should be the same. Think outside the box and commit fully to a distinctive vision.
