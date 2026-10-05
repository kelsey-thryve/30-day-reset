# 30 Day Reset

A one-page dashboard for a 30 day reset. Open `index.html`, or publish it with GitHub Pages.

## What it tracks

| Type | Items |
|---|---|
| Daily ticks | 5–10k steps · 180g protein · Read 10 pages · 6am wake-up · No vaping · No credit card spending |
| Weekly targets | Workouts (4/week) · Runs (2/week). Tick them on the day you do them. |
| Weigh-ins | Optional daily weight, charted against the 88kg goal |
| End-of-month goals | Get to 88kg · Get to 10k per month · Stop spending on the credit card · Stop vaping |

The reset runs from **Tuesday 6 October to Wednesday 4 November 2026** (set by `start` in `CONFIG`).

Week 5 is only Days 29–30, so its targets are scaled down (2 workouts, 1 run).

## Publish with GitHub Pages

1. Optional: rename the default branch to `main` under **Settings → General → Default branch** (pencil icon).
2. Go to **Settings → Pages**. Under **Build and deployment**, pick **Deploy from a branch**, then choose the default branch and `/ (root)`.
3. The site appears at `https://kelsey-thryve.github.io/30-day-reset/` after a minute or so.

## Saving and devices

Ticks are saved in the browser you use (`localStorage`). They don't sync between devices. To move your progress, use **Export backup** on one device and **Import backup** on the other. Clearing browser data for the site wipes your progress, so export a backup now and then.

## Changing the list

Edit the `CONFIG` block near the top of the `<script>` in `index.html`. You can rename labels freely. Changing an item's `id` drops the ticks saved under the old id.
