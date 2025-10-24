# Custom Domain Setup (Optional)

1) Buy a domain (e.g., wasimtebraiz.com) from any registrar.
2) In this repo, create a file named `CNAME` (no extension) with just your domain name in it:
   wasimtebraiz.com
3) In your DNS, add records:
   - If using the **apex domain** (wasimtebraiz.com):
     A 185.199.108.153
     A 185.199.109.153
     A 185.199.110.153
     A 185.199.111.153
   - If using a **subdomain** (www.wasimtebraiz.com), add a CNAME:
     CNAME www → wasim-t.github.io
4) In GitHub: Settings → Pages → set the custom domain, then enable **Enforce HTTPS**.
