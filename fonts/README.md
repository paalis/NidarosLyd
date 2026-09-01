# Fonts

Self-hosted so the page loads no third-party font resources.

| File | Family | Source | License |
|---|---|---|---|
| `bebas-neue-latin-400.woff2` | Bebas Neue, weight 400, latin subset | [`@fontsource/bebas-neue`](https://www.npmjs.com/package/@fontsource/bebas-neue) 5.3.0 (Google Fonts v16) | OFL 1.1 |
| `dm-sans-latin-variable.woff2` | DM Sans, variable weight 100-1000, latin subset | [`@fontsource-variable/dm-sans`](https://www.npmjs.com/package/@fontsource-variable/dm-sans) 5.3.0 (Google Fonts v17) | OFL 1.1 |

Both are the `latin` subset (`U+0000-00FF` and friends), which covers the
Norwegian characters the page uses. Full license texts sit alongside as
`LICENSE-bebas-neue.txt` and `LICENSE-dm-sans.txt`.

To refresh:

```
npm pack @fontsource/bebas-neue @fontsource-variable/dm-sans
```

then copy `files/bebas-neue-latin-400-normal.woff2` and
`files/dm-sans-latin-wght-normal.woff2` out of the tarballs.
