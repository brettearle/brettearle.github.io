# Thinking in Motion

Personal blog built with [Hugo](https://gohugo.io) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, deployed to GitHub Pages.

## Setup

    git clone --recurse-submodules <repo-url>

Requires Hugo extended 0.158.0 or newer.

## Writing

    hugo new content posts/my-post-title/index.md   # new draft
    hugo server -D                                  # preview at localhost:1313, drafts included

Set `draft: false` to publish. Pushing to `main` builds and deploys the site.

## Updating the theme

    git submodule update --remote themes/PaperMod
