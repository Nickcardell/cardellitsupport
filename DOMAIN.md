# Domain cutover notes

Target: `cardellitsupport.com`

Status: pending registration (Sign + Nick). Fallback candidate if primary unavailable: `cardellit.com`. Do **not** use `cardelltechsupport.com` — brand is Cardell IT Support, not Tech Support.

After purchase:
1. Add file `CNAME` with contents `cardellitsupport.com`
2. At registrar DNS (GoDaddy until Cloudflare cutover later):
   - A @ → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - AAAA @ → 2606:50c0:8000::153, 2606:50c0:8001::153, 2606:50c0:8002::153, 2606:50c0:8003::153
   - CNAME www → cardellexhibits.github.io  (or cardellitsupport Pages hostname once confirmed)
3. GitHub Pages → Custom domain → Enforce HTTPS
4. Leave mail records alone if any exist

HOLD BEFORE CARD: Nick keys payment. Domain-only 1 year. Receipt → Finance as Cardell IT Support.
