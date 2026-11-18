# Architecture Diagram Design System

This document defines how future **real** Azure architecture diagrams should be drawn. The bundled `.drawio` file is a **style template only**, not evidence of a deployed system.

## Design rules

| Element | Diagram standard |
| :--- | :--- |
| Canvas | White (`#FFFFFF`) with generous 48px margins; dark mode export optional |
| Typography | Segoe UI or Arial; diagram titles 22–26px, service labels 14–18px |
| Boundary | Navy outline, subtle light surface, clearly named VNet/subnet/resource-group/trust scope **only when applicable** |
| Compute / app | Pale blue fill, Azure-blue outline |
| Database / storage | White fill with neutral border; name actual Azure resource types when verified |
| Connections | Orthogonal blue connector lines, directional arrows, short protocol / traffic labels |
| Legend | Only when several line types or environments require differentiation |
| Icons | Use Azure official icon set when appropriately licensed and service accurate; custom boxes otherwise |

## Architecture notation

1. Draw external users/clients outside trust boundaries when appropriate.
2. Use containers for subscriptions, resource groups, virtual networks, subnets and availability zones only when the real architecture uses them.
3. Label network flow with source, destination and protocol/port when known; do not invent details.
4. Use a single primary flow direction (left-to-right preferred); avoid spaghetti connectors.
5. Include a short diagram version or last-updated note; keep title and caption visible.
6. Mark diagrams as `Proposed` or `Implemented`, and do not present planned services as deployed.
7. Do not use invented monitoring, performance or security results.

## draw.io workflow

1. Open https://app.diagrams.net/.
2. **File → Open from → Device**, select `diagrams/diagram-style-template.drawio`.
3. Use **File → Save As** to make an architecture-specific copy once the project is real.
4. Add confirmed Azure services, boundaries, arrows and data flows.
5. **File → Export as → SVG** (or PNG 2× if diagrams are too complex), include diagram contents but not editor UI.
6. Store editable `.drawio` under `diagrams/` and a README-ready export under `assets/diagrams/` when needed.
7. Inspect output at ~700px browser width and on GitHub dark mode; keep labels readable.

## Naming

Use kebab-case and a project-specific root, e.g., `project-name-architecture.drawio` and `project-name-architecture.svg`. Do not create directories until they hold real files.
