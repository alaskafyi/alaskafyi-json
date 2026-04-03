# alaskafyi-json (in-repo)

This folder is the **public JSON** workspace in the monorepo: versioned open datasets, optional mirrors of site `/data/*` feeds, and machine-readable bundles for downstream tools.

- **No secrets** — same rules as the standalone [alaskafyi-json](https://github.com/alaskafyi/alaskafyi-json) GitHub repo.
- **Site build** — HTML and passthrough JSON still live under **`apps/web/`**. Drop curated files under **`apps/json/public/`**; the Eleventy build copies them to **`/json/`** on the live site (e.g. `https://alaska.fyi/json/index.json`).

See **[docs/data/repos-and-data-plane.md](../../docs/data/repos-and-data-plane.md)**.
