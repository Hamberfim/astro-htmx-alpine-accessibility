# Astro, HTMX, Alpine, Alpine Ajax, & Accessible Astro Components

## 🧭 Project Shape | The AHA Stack
Mimic a content-heavy reference site that includes:
- A homepage
- A small set of content pages (10–20 short entries)
- A few interactive examples
- A few of accessible components
- Some JSON-driven data and/or widgets
- A few htmx partial updates

This structure teaches the stack without drifting into “build a full marketing site” or “build a blog product.”

## Core Purpose
Learn how to build a content-heavy website using:

- Astro (core framework)
- htmx (server-driven partial updates)
- Alpine.js (UI interactivity + small state)
- Alpine Ajax (JSON/data-driven interactions)
- Accessible Astro Components + related accessibility tools
- GitHub (repo + GitHub Pages deployment)

This is a learning project, not a product. Every feature exists only to teach one of the tools.
#### Resource
- https://docs.astro.build/en/getting-started/
- https://htmx.org/docs/
- https://alpinejs.dev/start-here
- https://alpine-ajax.js.org/reference/
- https://accessible-astro.incluud.dev/getting-started/introduction/

## 🧩 Project Structure (Minimal + Focused)
### 1. Astro (foundation)
**Focus Learning:**
- File-based routing
- Layouts
- Components
- Content organization
- API routes (for htmx + Alpine Ajax)

**Deliverables:**
- A base layout
- A few content pages
- A simple API endpoint

### 2. htmx (HTML-driven interactivity)
**Focus Learning:**
- `hx-get`, `hx-post`, `hx-target`, `hx-swap`
- Returning HTML fragments from Astro endpoints
- Updating part of a page without reload

**Deliverables:**
- Two or more partial updates (e.g., load more, filter, sort)

### 3. Alpine.js (client-side micro‑interactions)
**Focus Learning:**
- `x-data`, `x-show`, `x-bind`, `x-on`
- Scoped component behavior
- Enhancing htmx-updated regions

**Deliverables:**
- A toggle, disclosure, and/or small UI component

### 4. Alpine Ajax (JSON/data-driven behavior)
**Focus Learning:**
- Fetching JSON
- Updating Alpine state from responses
- When to choose JSON vs HTML

**Deliverables:**
- One or two small JSON-driven widget (stats, random item, etc.)

### 5. Accessible Astro Components
**Focus Learning:**
- How to use their accessible UI primitives
- How to integrate them with htmx + Alpine
- How to override styles safely

**Deliverables:**
- Two or more accessible components (tabs, accordion, dialog)

### 6 (& 1). GitHub + GitHub Pages Deployment
**Focus Learning:**
- Repo setup
- Astro static build configuration
- GitHub Actions deployment

**Deliverables:**
- A deployed site
- Confirmed working htmx + Alpine interaction
