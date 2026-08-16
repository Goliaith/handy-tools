# Handy Tools

A clean collection of practical, fully functional tools.

## How It Works

A problem is identified. Features are designed. A working self-contained tool is built. It is published here so anyone can try it instantly in the browser or download a private standalone version.

The entire site is static and can be deployed anywhere (Netlify, Vercel, GitHub Pages, etc.).

## The Tools

A collection of practical, self-contained tools. Each is a single HTML file that works in the browser or can be downloaded for private/offline use.

- **Real Estate Accounting** — Multi-property income/expense tracker with live P&L and charts
- **Investment Return Calculator** — Deal modeling, CoC, IRR, sensitivity
- **Tenant Screening & CRM** — Applicant tracking + automatic scoring
- **Kanban Task Board** — Drag & drop with priorities and due dates
- **Habit Tracker** — Streaks, calendars, progress visualization
- **Invoice Generator** — Line items, tax, print/PDF ready invoices
- **Client Proposal Builder** — Scope, price, timeline, accept/decline signature block
- **Personal Budget Tracker** — Income/expense logging + category breakdown
- **Time Tracker** — Live timers, session logs, daily/weekly totals
- **Group Expense Splitter** — Shared bills with automatic who-owes-whom balances
- **Recipe & Meal Planner** — Save recipes, plan the week, auto-generate shopping lists
- **Travel Itinerary & Budget Planner** — Daily plans + live budget tracking with exports

More tools are added over time.

## Adding a New Tool

1. Identify a clear, practical need.
2. Build a self-contained HTML + Tailwind + vanilla JS file in `/tools/`.
3. Add a card in `index.html`.
4. Create the matching `-standalone.html` variant.
5. Update README if needed.
6. Deploy.

All tools are real and usable (not just mockups).

## Downloading Tools

Visitors to the portfolio can download any published tool as a standalone HTML file using the "Download Standalone HTML" button on each tool card. The downloaded file works completely independently of this site and can be opened locally or hosted elsewhere.

For example, the Real Estate Accounting tool can be downloaded as `real-estate-accounting.html` and used offline.

## The Process

Spot a real problem → design minimal useful features → build a working standalone-friendly tool → publish with public demo + private download option.

## Deployment

See the detailed step-by-step guide in [DEPLOY.md](./DEPLOY.md).

**Quick Netlify deploy:**
1. Go to https://app.netlify.com/drop
2. Drag the whole `tools-portfolio` folder onto the page.
3. After the first deploy, go to **Site configuration → Forms** and enable email notifications for the `suggest-tool` form.

The site also works great on Vercel, Cloudflare Pages, etc.

All tools are 100% client-side and free to use.

## Next Steps

Suggest a problem or idea using the form on the site. It gets reviewed, a tool can be built, and published here.

All tools are 100% client-side and free.