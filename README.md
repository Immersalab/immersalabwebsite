# ImmersaLab Website

Official website for **ImmersaLab** — a creative lab building the future of graphics and immersive experiences through [Glint3D](https://github.com/QuinnAho/Glint3D), the living renderer.

## Overview

This repository contains the marketing site for ImmersaLab and Glint3D, showcasing our rendering technology, product vision, and team.

## What's Inside

### Current Sections

- **Updates Coming Soon** — 6 feature cards highlighting upcoming technology (Gaussian Splatting, Neural Denoising, etc.)
- **Rendering OS** — Overview of the unified pipeline with distributed rendering capabilities
- **What Sets It Apart** — Key features including:
  - AI-Native Design (JSON-Ops for machine-readable scenes)
  - **Task-Based Workflow** (with real-time animations: frame counters, progress bars, workflow steps)
  - Autonomous Rendering capabilities
- **Platform Roadmap** — 3 phases: VizPack (product visualization), DataGen (synthetic training data), FinViz (financial storytelling)
- **Technical Foundation Strip** — Core technology highlights
- **Company Page** — Team section with two founders + early contributors
- **Resources** — Links to documentation, research, and GitHub

### Key Features

  - Live frame counter (0 → 1247)
  - Timer with MM:SS format
  - Animated progress bar (0-100%)
  - Workflow step transitions (Pending → Processing → Complete)
  - Throughput calculation (fps)
- **Terminal/CLI aesthetic** throughout with JetBrains Mono font
- **WCAG AA+ accessibility** compliance (7:1+ contrast ratios)
- Fully responsive design with mobile breakpoints

## Planned Additions

### Near-term
- [ ] Developer blog/posts section with technical deep-dives
- [ ] Render gallery showcasing CLI output examples with command snippets

### Future Enhancements
- [ ] Documentation search integration
- [ ] Real-time render progress from cloud API
- [ ] Download metrics dashboard

## Structure

```
immersalabwebsite/
├── index.html          # Main landing page
├── company.html        # Team and company info
├── styles.css          # Global styles and design system
├── Glint3DIcon.png     # Brand assets
└── README.md           # This file
```

## Design System

### Colors
```css
--primary-color: #f59e0b      /* Amber */
--secondary-color: #8b5cf6    /* Violet */
--background-primary: #000000 /* Pure black */
--background-secondary: #0f0f0f
--background-tertiary: #1a1a1a
--text-primary: #f9fafb
```

### Typography
- **Headings**: Inter (Google Fonts)
- **Body**: Inter
- **Code/Terminal**: JetBrains Mono

## Development

Simply open `index.html` in a browser. No build process required.

For local development with live reload:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## Contributing

This is the official ImmersaLab website repository. For issues or suggestions, please open an issue.

## License

© 2024 ImmersaLab. All rights reserved.

---

**Building Glint3D** — The Living Renderer that learns, adapts, and improves with every frame.
