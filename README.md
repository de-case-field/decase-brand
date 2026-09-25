# de-Case Brand Identity

**Brand lock v0.1** — Core Identity mark (01) + blue-hyphen wordmark (05).

> de-Case is an open, operator-controlled boundary around a sovereign mission core.

## Live guidelines

After GitHub Pages is enabled on this folder / the `decase-brand` repo:

**https://de-case-field.github.io/decase-brand/**

Open `index.html` locally in a browser for the same kit offline.

## Official configurations

| Variant | File(s) | Use |
|---------|---------|-----|
| Mark only | `svg/decase-mark-*.svg` | Favicon, Operator icon, hardware badge |
| Mark + wordmark | `svg/decase-lockup-*.svg` | Primary company/product lockup |
| Wordmark | `svg/decase-wordmark-*.svg` | GitHub, docs, headers |
| Monochrome | `*-mono*.svg` | Engraving, PCB silkscreen |

No separate logos for Field / CaseMind / CaseNet / OS — inherit the identity.

## Brand colors

```
IBM Blue   #0F62FE
Deep Ink   #161616
Graphite   #262626
Gray       #393939
Light      #F4F4F4
White      #FFFFFF
```

Status colors (`#24A148`, `#F1C21B`, `#DA1E28`) are product semantics, not branding.

## Typography

- IBM Plex Sans SemiBold/Medium — wordmark direction
- IBM Plex Sans — product / docs
- IBM Plex Mono — device IDs, diagnostics, terminal

Wordmark SVGs use live text as a proxy; outline before production print.

## Taglines

| Context | Line |
|---------|------|
| Technical / investor | Portable Offline Intelligence Platform |
| Public / product | Offline Field Workstation |
| Under logo | Prefer none |

## Naming

`decase-[asset]-[variant].[format]`

## Publish (GitHub Pages)

From org `de-case-field`, either:

1. Dedicated public repo `decase-brand` with this `brand/` content at root, Pages from `/` (main), or
2. Pages on the Field monorepo serving `/brand`.

```bash
# Example: push brand kit as its own public Pages repo
gh repo create de-case-field/decase-brand --public --description "de-Case brand identity guidelines" --source=. --remote=brand-origin
```

See also: [LADS TV brand kit](https://ladstv.github.io/ladstv-brand/) (structural reference).
