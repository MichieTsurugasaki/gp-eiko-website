# GP EIKO website

A lightweight static-site starter for GP EIKO. The current copy and visual theme are provisional and can be replaced when the site's purpose and content are decided.

## Preview locally

Open `index.html` in a browser, or serve this directory with any static file server.

## Deploy with Cloudflare Pages

1. Push the contents of this directory to a new GitHub repository.
2. In Cloudflare, open **Workers & Pages → Create application → Pages → Connect to Git** and select that repository.
3. Use these build settings:
   - Framework preset: **None**
   - Build command: leave blank
   - Build output directory: `/`
4. Deploy. Subsequent pushes to the production branch will deploy automatically.
5. In the Pages project, add `gp-eiko.com` and `www.gp-eiko.com` under **Custom domains** if both addresses should work.

### Existing domain attachment

The supplied Cloudflare screenshot shows `gp-eiko.com` attached to the `sparkling-glade-d2f1` Worker. Before attaching the same hostname to Pages, remove or change that Worker custom-domain binding in Cloudflare. Do this only when ready to switch production traffic; then add the hostname to Pages and follow Cloudflare's DNS prompts. Avoid changing DNS records manually unless Cloudflare instructs you to.
