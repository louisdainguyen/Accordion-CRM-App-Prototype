# Accordion CRM Agentic Software

Prototype UI for **Accordion**, a CRM where AI agents (Rune, Aether, Syntax, Theo and Clara) help you manage customers, contracts and conversations.

The whole prototype is a single, self-contained `index.html`, with no build step.

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
# or
python3 -m http.server 8000
```

To host it, enable **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root).

## What's inside

- **Ask Rune (Agents)**: home with composer, quick prompts, previous chats and suggested apps; full chat view with mock answers, file cards and charts; chat as drawer, popup, full page or minimised; Quick Chat.
- **App drawer**: details for connected apps (e.g. Stripe MCP).
- **Customers**: 50-company table with sticky columns, selection, Filter & Sort, column resize and drag-to-reorder, Calculate footer, CSV export. List View and Kanban show "coming soon" empty states.
- **Customer page**: profile, editable detail rows (hover ⋯ menu), About, and tabs: Overview (6 metric cards), Activities, Tasks, Documents, Members, Settings.
- **Sidebar**: collapsible (56px rail) with animated transitions; Appearance toggles light/dark mode.
- **Mobile**: off-canvas sidebar, bottom-sheet drawers and menus, overflow menu in the top bar.

## Notes

- Tailwind is loaded from its CDN (`cdn.tailwindcss.com/3.4.17`) and fonts from Google Fonts, so the page needs an internet connection.
- Data is mock data; column widths, column order and theme are remembered in `localStorage`.
