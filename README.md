# epyhia.com

Static site for epyhia.com deployed via GitHub Actions.

## Deploy

Push to `main` — GitHub Actions builds and deploys automatically.

## Custom domain setup

1. In your repo, go to **Settings > Pages**.
2. Set **Build and deployment** source to **GitHub Actions**.
3. Add `epyhia.com` (and optionally `www.epyhia.com`) under **Custom domain**.
4. At your DNS provider, create an `A` record pointing to GitHub Pages IPs:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
   Or use a `CNAME` record pointing to `<username>.github.io`.
