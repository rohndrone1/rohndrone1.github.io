# ContextCue project website

A minimal static website introducing the ContextCue research prototype.

The page contains fictional example screens, a technical architecture overview, an official ACL resource link and a demo-request email. No videos, personal biography, patient data, model weights or backend databases are included.

## GitHub Pages

The `docs/` directory is the public site. Configure GitHub Pages to publish the main branch, /docs folder. The repository uses the account’s root GitHub Pages address so docs/robots.txt is served at /robots.txt. The application source can be added separately later.

## Crawler directives

Every page includes noindex/nofollow/noarchive/nosnippet directives and robots.txt disallows all crawlers. These are voluntary instructions to search engines, not password protection. The public GitHub source repository itself may be discoverable.

## Preview

Serve docs/ or dist/ with a static web server. No dependency installation or build step is required.
