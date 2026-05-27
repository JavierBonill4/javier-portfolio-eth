# Javier Bonilla — Ethereum Developer Portfolio

A single-page portfolio site. No framework, no build step — pure HTML with Tailwind CDN.

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Import at [vercel.com](https://vercel.com) → auto-detected as static site
3. Deploy — done

## Connect ENS

In Vercel Dashboard → **Domains**:
- Add `yourname.eth.limo` (works automatically with ENS + eth.limo gateway)
- Or add a custom domain and point your ENS contenthash to it via IPFS/IPNS

## Edit

All content is in `index.html`. Search for:
- `Hi, I'm` — edit your bio
- `What I Care About` — edit the interest cards
- Project URLs are already set to your live Vercel deployments
