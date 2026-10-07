# Desert Lakes LLC

Static business landing page at https://desertlakes.space/.
Repository: https://github.com/cyberlightdev/desertlakes

## Publish

In Settings → Pages, choose Deploy from a branch, select main and / (root), and Save. Set the custom domain to desertlakes.space. The CNAME file is included. Enable Enforce HTTPS once the certificate is available.

## DNS

For the apex domain, use an ALIAS/ANAME record to cyberlightdev.github.io if supported, or these four A records:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

For www, use a CNAME to cyberlightdev.github.io (no repository path).

Official guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Edit

Edit index.html for content, styles.css for design, and favicon.svg for the mark. No build system or JavaScript is required. Local preview: python3 -m http.server 8000.

The business email has intentionally been left out until one is provided. The Vast.ai link opens the general marketplace; replace it with your host/listing link when available.
