# Publish the corporate landing page

The existing wedding site responds with `server: GitHub.com` and the wedding repository CNAME contains weddings.soundsdjevents.com. Use a separate repository for the corporate GitHub Pages site. Do not upload this package over the wedding repository's root or change its CNAME.

1. Create a GitHub repository under soundsdj, for example sounds-corporate. A public repository works with GitHub Free Pages; private repository Pages availability depends on your plan.
2. Upload the CONTENTS of github-upload to the root of its main branch, retaining the assets folder. Do not upload the ZIP itself or nest the site inside github-upload. Include .nojekyll if using Git locally; the GitHub browser uploader may hide that dotfile. This site also works without it.
3. In Settings > Pages, select Deploy from a branch, main, / (root), and save.
4. Set the custom domain to corporate.soundsdjevents.com and save BEFORE adding DNS.
5. At your DNS provider add CNAME: name corporate, target soundsdj.github.io. Do not include the repository name or https://. If a corporate record already exists, inspect it before replacing it. Leave wedding and main website DNS alone.
6. Once GitHub's DNS check and certificate provisioning finish, enable Enforce HTTPS. This can take up to 24 hours.
7. Open https://corporate.soundsdjevents.com/ on desktop and mobile. Check both hero buttons, all photos, FAQs, and the embedded form. Submit one clearly labelled owner test inquiry and confirm its receipt and any confirmation/redirect behavior in GoHighLevel. This has not yet been done.
8. In Google Search Console use an existing verified soundsdjevents.com Domain property (covers subdomains), or verify a new corporate URL-prefix property. Submit https://corporate.soundsdjevents.com/sitemap.xml and request indexing for the homepage. Indexing is not immediate or guaranteed.

## Included SEO
Corporate-specific title and description; canonical URL; index/follow directive; Open Graph and Twitter sharing metadata; Organization, WebSite, WebPage, Service/Offer, and FAQPage JSON-LD; the exact two fixed package prices in CAD; sitemap.xml; robots.txt; descriptive image alt text and semantic heading structure. FAQ data matches visible FAQs; structured data does not guarantee rich results. No city pages, invented reviews, or unsupported business claims added. Web-sized copies of the supplied photos are included; original source photos remain unchanged.

## Form and analytics
The corporate ProfitFlo iframe, official embed script, original cookie-consent attributes, and fallback contact link are included. Its actual submission destination, automations, consent behavior, and success page are controlled in GoHighLevel and require a live check. No successful submission is claimed.
The wedding tracking.js was reviewed but not copied: it contains wedding-specific routing and a $2,900 lead value. Analytics is separate from SEO. This package does not add GA4, Ads, Meta, or Clarity tags; existing form-side tracking may still run. Corporate conversion tracking should be configured against a verified successful corporate submission, not a Check My Date click.

## References
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

No GitHub repository, DNS, hosting, or live wedding files were changed. Live rendering, external font loading, iframe resizing, and submission remain to be checked after deployment.
