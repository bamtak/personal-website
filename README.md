# Personal website: tajudeenkolawole.com

Static site, no build step. `public/index.html` holds every page (hash-routed: `#home`, `#work`, `#experience`, `#about`, `#contact` and one route per project). Images are in `public/img/`.

Hosted on Cloudflare Workers static assets. The config binds `tajudeenkolawole.com` and `www.tajudeenkolawole.com` as custom domains.

## Deploy

    cd /Users/kola/Documents/Projects/deepintel/personal-website
    npx wrangler login      # first time only
    npx wrangler deploy

## Edit

Change `public/index.html` (or add images under `public/img/`) and run `npx wrangler deploy` again.
