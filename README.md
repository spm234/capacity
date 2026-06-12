# Capacity Planner

A team capacity planning tool hosted on GitHub Pages.

## Files

| File | Purpose |
|------|---------|
| `capacity.html` | The application (rarely changes) |
| `data.json` | All data — people, projects, allocations (update to publish) |
| `_headers` | GitHub Pages CSP headers |

## How to publish updates

1. Open `capacity.html` in your browser
2. Switch to **User** mode (password: `capacity123`) and make your changes
3. Click **📤 Save & Publish** — downloads `data.json`
4. Commit `data.json` to this repo
5. GitHub Pages deploys in ~30 seconds — everyone sees the update

## Modes

| Mode | Password | Can do |
|------|----------|--------|
| 👁 Viewer | None | View all data, click around, see utilization |
| ✏ User | `capacity123` | All viewer actions + add/edit people, projects, allocations |
| ⚙ Admin | `delivery123` | Configure dropdown options (statuses, types, portfolios, etc.) + import/export |

## GitHub Pages setup

1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / root
4. Save — your URL will be `https://yourusername.github.io/repo-name/capacity.html`

## Updating the app itself

If `capacity.html` needs updates, replace it in the repo. Data in `data.json` is loaded separately so no data is lost when the app file changes.
