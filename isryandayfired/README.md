# isryandayfired.com

Single-page site that answers one question.

**To update:** edit `FIRED` and `LAST_CHECKED` near the bottom of `index.html`.

## Deploy (GitHub Pages)
1. Create a new repo (e.g. `isryandayfired`) and copy `index.html` + `CNAME` to its root.
2. Repo **Settings → Pages**: deploy from `main` branch, root.
3. At your registrar, add DNS records for `isryandayfired.com`:
   - `A` records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` `www` → `kylepetz.github.io`
4. Back in Pages settings, enable **Enforce HTTPS** once the cert is issued.
