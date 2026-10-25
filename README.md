# toonengine.ai

Stealth coming-soon page for Toon Engine, a product of Upon Dev.

Plain static site with no build step: `index.html` plus `robots.txt`. Vercel deploys it on every push to `main`.

While in stealth, the page carries a `noindex` meta tag so search engines leave it out of results. `robots.txt` allows crawling on purpose: link-preview bots (iMessage, Slack, X, LinkedIn) need it to fetch the share image, and Google has to crawl the page to see the noindex. Remove the noindex tag at public launch.
