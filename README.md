# ContextCue project website

A minimal static website introducing the ContextCue research prototype.

Website: https://rohndrone1.github.io/contextcue/

The root address redirects to /contextcue/.

The page contains fictional example screens, a video demonstration, a technical architecture overview, an official ACL resource link and a demo-request email. No patient data, model weights or backend databases are included.

## GitHub Pages

The `docs/` directory is the public site, with the project page in `docs/contextcue/`. Configure GitHub Pages to publish the main branch, /docs folder. The repository uses the account’s root GitHub Pages address so docs/robots.txt is served at /robots.txt. The application source can be added separately later.

## Crawler directives

The HTML pages include noindex/nofollow/noarchive/nosnippet directives. The robots.txt file blocks crawling of the video and its poster while allowing crawlers to read the HTML noindex tags. These are voluntary instructions to search engines, not password protection. The site, video file and public GitHub source repository can all be accessed by anyone who discovers their URLs.

## Preview

Serve docs/ or dist/ with a static web server. No dependency installation or build step is required.
