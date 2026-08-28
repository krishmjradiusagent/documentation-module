# Documentation module — project rules

## Icons
- Bottom-nav / app icons: **Phosphor Icons** (https://phosphoricons.com), regular weight, 256×256 viewBox, `fill:currentColor`.
- CRM / web surfaces keep Lucide (Radius UI default).

## Components
- Use **Radius UI Design System** components first (bound at `_ds/radius-ui-design-system-c7220bb1-3534-4549-94e9-dd1c4d80b981/`).
- If a component does not exist in Radius UI, take it from **shadcn/ui** (https://ui.shadcn.com/docs/components) and theme it with Radius tokens.
- Never invent colors, type, spacing, or components outside these sources.

## Backups (mandatory)
- **Before any edit** to a file, copy the current version to `backup/<name>.backup.<ext>` (overwriting the previous backup there).
- After the edit lands, refresh that same backup file so it always mirrors the latest shipped version.
- One backup file per source file — never a pile of dated copies.

## Where changes go
- Mobile client app → `radius-client-app.html`
- Agent/office app → `radius-office-app.html`
- Don't spin up a new file for a change to an existing screen unless asked.
