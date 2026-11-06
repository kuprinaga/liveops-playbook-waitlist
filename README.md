# LiveOps Playbook — Waitlist

Static landing page + waitlist form for Ana Kuprina's LiveOps Playbook session series.
Signups post directly to Kit (ConvertKit) form 10150569 via the public v3 API.

- **Live**: https://liveops.anastasiakuprina.com (via GitHub Pages, CNAME in repo root)
- **Fallback URL**: https://kuprinaga.github.io/liveops-playbook-waitlist/
- **Source project**: local Vite/React app — rebuild with `npm run build`, copy `dist/*` here, push to `main`. Pages redeploys automatically.

## DNS (Namecheap)
CNAME record: host `liveops` → `kuprinaga.github.io` (TTL automatic).
