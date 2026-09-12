# Maya

Jason Polachak’s personal Counsel. Slice 1 only: paste one incoming message, optionally name the point you want to make, tap **Analyze**, and get three outputs — a suggested reply, a read on the cycle move, and a few things to consider.

Calm, adult, mobile-first. One static page. **$0.** Nothing leaves the device.

## Open locally

Double-click `index.html`, or from this folder:

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

Works offline. No install, no keys, no build.

## GitHub Pages

Project site (after Pages is turned on):

**https://jasonpolachak.github.io/maya/**

Enable from `main` (exact setup):

1. Repo → **Settings** → **Pages**
2. Build and deployment → Source: **Deploy from a branch**
3. Branch: **`main`** / folder: **`/ (root)`**
4. Save

A `.nojekyll` file is in the repo so GitHub does not run Jekyll on the page.

Until Pages is enabled, use the local open steps above.

## What Analyze does

1. Paste an incoming message (for example a long text).
2. Optional short field: *the point I want to make*.
3. Tap **Analyze**.
4. Three outputs:
   - **Recommendation** — a suggested reply that lands your point without one-upping.
   - **Understanding** — what she may actually be asking for / the cycle move, with tagged heuristics.
   - **Things to consider** — 2–4 short bullets.

All processing is in the browser. No network calls. No storage.

## Coaching engine (transparent heuristics)

Maya tags **likely moves** in the incoming text. It does **not** invent clinical diagnoses or attachment styles.

- [Gottman Four Horsemen](https://www.gottman.com/blog/the-four-horsemen-recognizing-criticism-contempt-defensiveness-and-stonewalling/) — criticism, contempt, defensiveness, stonewalling
- [EFT](https://iceeft.com/what-is-eft/) — protest over not being gotten (a reach that can sound like attack)

This is heuristic coaching, not therapy.

## Out of scope (later slices)

Phone sync, Grok ingest, audio, timeline, attachment diagnosis, accounts, backend, paid APIs.
