# HaPaDa public profile

> The `.github` repository for the HaPaDa GitHub organisation — a placeholder, with no
> profile page yet.

GitHub renders `profile/README.md` from an organisation's `.github` repository as the
public profile anyone sees on `github.com/hapada`. This repo exists so that page has a
home, but **no `profile/` directory has been written yet**, so the organisation shows
GitHub's default. It is a content repo: no code, no build, no dependencies. HaPaDa is
the company every brand in this workspace belongs to.

## Features

None yet — there is no `profile/` directory on the default branch, so nothing is
rendered.

## Requirements

- Anything that renders Markdown. There is no build step and nothing to install.
- To publish a page: add `profile/README.md` and push to the default branch. GitHub
  picks it up automatically; there is no deploy step.

## Getting started

```sh
mkdir -p profile   # then write profile/README.md
```

`carn-cloud/_github/public` is the worked example to copy the shape from.

## Development

| Path | What lives there |
| ---- | ---------------- |
| `profile/README.md` | The profile page GitHub will render, once written |

- There is no build, test or lint step; `/check` has nothing to run here.
- The root `README.md` (this file) is repo meta only — GitHub does **not** render it
  as the organisation profile. Only `profile/README.md` is used for that.

## Related repositories

- `hapada/_github/private` — the sibling internal profile repo for the same
  organisation.
- `carn-cloud/_github/public` and `carn-cloud/_github/private` — the two written
  examples in the workspace.
- `setup` — `projects.yaml`, which maps this directory to the `hapada` account and the
  `.github` repository.

## Licence

Copyright © HaPaDa. All rights reserved.

This is proprietary software (`LicenseRef-Proprietary`). No licence is granted to use,
copy, modify, or distribute it outside HaPaDa.
