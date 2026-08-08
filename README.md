# DealFire marketing site

Public marketing surface for **DealFire** (repo name `dealdiamondcrm-site` is legacy; product branding is DealFire).

## Live destinations

| Surface | URL |
| --- | --- |
| DealFire app / CRM (product) | https://dealdiamondcrm-web.vercel.app |
| Custom domain on the app (Vercel) | https://dealfirepro.com |
| This marketing site (GitHub Pages) | https://mikepflanagan.github.io/dealdiamondcrm-site/ |
| Onboarding | https://dealdiamondcrm-web.vercel.app/onboarding?plan=FREE |
| Log in | https://dealdiamondcrm-web.vercel.app/login |

`dealfirepro.com` is served by the **Vercel CRM app**, not this static repo. Do **not** add a GitHub Pages `CNAME` for `dealfirepro.com` here — that would fight the live app domain.

Related public site: [`dealfire-site`](https://github.com/MikePFlanagan/dealfire-site) (CNAME `dealfire.net`).

## Local files

- `index.html` — landing
- `offer.html` — full plans & pricing
- `.nojekyll` — GitHub Pages static serve

All primary CTAs open the live DealFire CRM onboarding/login routes above.
