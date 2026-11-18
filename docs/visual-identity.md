# Azure Engineering Editorial — Visual Identity

**Scope:** Dedicated `azure-cloud-portfolio` repository. All illustrations are original abstract technical artwork and do not reproduce Microsoft certification badge art.

## Core concept

A documentation-first engineering portfolio with restrained Azure-blue accents, editorial typography, and clear separation between completed work and learning focus. No fake dashboards, deployment claims, or visitor metrics.

## Palette

| Role | Light | Dark | Usage |
| --- | --- | --- | --- |
| Background | `#F8FBFF` | `#071423` | Asset canvas |
| Surface | `#FFFFFF` | `#102A44` | Cards |
| Headline | `#09243F` | `#F2F8FF` | Primary type |
| Muted | `#4E647C` | `#A9C0D8` | Explanatory copy |
| Azure accent | `#0676CE` | `#53B4FF` | Key lines/labels |
| Borders | `#CBDDEF` | `#2C4C68` | Container edges |
| Soft accent | `#E8F3FE` | `#183958` | Emphasis surfaces |

## Typography

- SVG: `Inter, Segoe UI, Arial, sans-serif`; monospace labels: `Consolas, Menlo, monospace`.
- GitHub Markdown typography is determined by GitHub, not by the README.
- SVG hero heading: ~79px on a 1440x480 canvas; captions 12–18px.

## Hierarchy

1. Banner (visual title) and three professional navigation links.
2. Native Markdown `##` section headings; small number of sections.
3. Graphic cards only where they add meaning: completed credentials, learning status, confirmed projects.
4. Short, explicit technical bullets; source repositories and real evidence linked.

## SVG design rules

- Include accessible `<title>` and `<desc>` plus meaningful README alt text.
- All images have a fixed viewBox and are rendered at `width="100%"` in README.
- Maintain distinct contrast for GitHub's light and dark modes; use `<picture>` in Markdown.
- No JavaScript, remote font imports, animations, fake official logos, or externally fetched images.
- Preserve original `.drawio` diagram files; SVGs used in README are exports or custom originals.

## Scope and status

- Completed: AZ-900, AZ-104 (dates supported by provided Microsoft Learn screenshots).
- In preparation: DP-700 (never a completed credential).
- Verified backend projects: PrepX and SwarnaRatna (not described as Azure deployments).
- Azure-specific project diagrams: add when projects are actually implemented.
