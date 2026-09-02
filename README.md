# sigma-plugin-host

Static hosting for Sigma Computing custom plugins, served over
[jsDelivr](https://www.jsdelivr.com/) so a registered plugin renders from any
machine rather than only from the one running a local dev server.

Each folder is one plugin, entry point `index.html`:

```
https://cdn.jsdelivr.net/gh/govzzz/sigma-plugin-host@main/<folder>/index.html
```

| folder | plugin |
|---|---|
| `pinewood-vhc-action` | VHC Work-to-Action Board — a franchised dealer group's vehicle-health-check funnel, from identified work to invoiced work, with the value leaking out at each stage |

All numbers rendered when a plugin is unbound are synthetic illustrative
fallbacks, not any customer's data.
