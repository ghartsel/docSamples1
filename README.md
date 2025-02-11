# Welcome to the *documentation samples*

This repo implements the UI for an index to documentation samples, including online publications, blog posts, and personal projects.

## Features

- Uses the Hugo static site generator with the [aafu](https://themes.gohugo.io/themes/aafu/) theme.
- Auto-deployed on Cloudflare Pages on ``git push``: https://docsamples1.pages.dev/. PDFs, not indexed through the UI, are deployed on Cloudflare R2; viewed with ``https://gh.works/<filename>.pdf``.

## Repository Content

- Given the aafu theme, the index elements is defined in the config.yaml file.
- Supporting index element formats are defined in modified /layouts/partials/accordion partials files.
