# Technical Architecture

## Default direction
Use a lightweight static/edge-friendly architecture unless implementation requirements justify more.

## Suggested stack
- Frontend: semantic HTML/CSS/JS or lightweight framework.
- Hosting: Cloudflare Pages when compatible.
- Repository: GitHub.
- Images: optimized WebP/AVIF where supported.
- Maps: external map link first; embed only when useful.
- WhatsApp: direct CTA after number verification.

## Performance
Optimize images, avoid unnecessary JavaScript, lazy-load below-fold media, minimize third-party scripts, and control font loading.

## Security
No secrets in Git. No unnecessary backend endpoints. Validate future forms server-side. Use HTTPS and minimize third-party integrations.

## Deployment
GitHub → build/CI → hosting → production domain.
