# clowneau

My personal website, built with Hugo and hosted on GitHub Pages.

## Working on the site

Open the project:

```bash
cd ~/Projects/clowneau-site
```

Start the local development server:

```bash
hugo server -D
```

Preview at http://localhost:1313/

## Creating content

New blog post:

```bash
hugo new content posts/my-post.md
```

New album review:

```bash
hugo new content listening/my-album.md
```

Both commands automatically generate front matter using their respective archetypes.

## Publishing

When ready to publish:

```bash
publish "Describe your changes"
```

This stages changes, creates a Git commit and pushes to GitHub.

Live website: https://clowneau.com/

## Notes

- `draft: true` keeps content off the live site.
- `draft: false` makes content eligible for publishing.
- Images go in `static/images/`.
- Blog posts go in `content/posts/`.
- Album reviews go in `content/listening/`.
