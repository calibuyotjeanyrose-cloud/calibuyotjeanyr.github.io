# Website Check Report

Target URL: `https://calibuyotjeanyrose-cloud.github.io/jeanyrose.ph/`

## Result from this environment

I attempted to check the website with:

```bash
curl -I -L https://calibuyotjeanyrose-cloud.github.io/jeanyrose.ph/
```

The request could not complete from this execution environment due to a network/proxy restriction (`CONNECT tunnel failed, response 403`).

## What this means

- The URL may still be working for normal browsers.
- This environment currently cannot verify external availability for that domain.

## Quick checks to run locally

Run these on your own machine to confirm status:

```bash
curl -I -L https://calibuyotjeanyrose-cloud.github.io/jeanyrose.ph/
```

```bash
npx lighthouse https://calibuyotjeanyrose-cloud.github.io/jeanyrose.ph/ --view
```

## If the site does not load

1. Verify the GitHub Pages repository is public and Pages is enabled.
2. Confirm the site path is correct (`/jeanyrose.ph/`) and links use the same base path.
3. Check Actions/Pages deployment logs for failed builds.
4. Confirm DNS settings if a custom domain is used.
