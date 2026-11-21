# Project notes for Claude

## Who this is for
Yu Li (李昱) is a licensed Washington real estate broker with John L. Scott in Renton, WA, serving King & Pierce Counties in English and Mandarin. Yu is **new to coding** and is building this site to learn: briefly explain the "why" behind each step, and let Yu do the steps in GitHub, GitHub Desktop and other websites.

## The site
- Plain HTML/CSS: `index.html` is the live page. There is no build step.
- Hosted on GitHub Pages: https://bobli88-wq.github.io/yu-li-website/ (repo `bobli88-wq/yu-li-website`, branch `main`). A push to `main` updates the live site in about a minute.
- **Don't set a custom domain** in the Pages settings unless Yu has bought one; a mistaken `yuli.com` entry once broke the site.
- Footer must keep the firm name (John L. Scott Real Estate) and license number, since Washington advertising rules require the firm name. Don't use John L. Scott logos.

## Chosen design: "Pacific Northwest" (Nov 21, 2026)
Reference mock-up: `previews/b-northwest.html`. Rebuild `index.html` in this style.
- Colors: forest `#233d30`, forest-2 `#2f5240`, sage `#9db59a`, sage-soft `#e3ebdf`, clay `#b8643a` (buttons), stone `#f2efe8`, paper `#faf8f3`, ink `#1d2721`
- Fonts: DM Serif Display (headings), Source Sans 3 (body), from Google Fonts
- Layout: green hero with a mountain silhouette, services 01/02/03, arch-shaped photo in About, green reviews band, contact box with tabs
- Profile photos go in `images/`. Resize them for the web before using them.

## Roadmap (from a 10-step "learn by building" plan)
1. ✅ Page built  2. ✅ Git + GitHub + GitHub Pages
3. ⏭ Rebuild in design B with Yu's photos
4. Messages & reviews: visitors send a private message (no sign-in) or sign in with Google to post a public review. Planned backend: Supabase (free tier). Yu should ask the managing broker about testimonial rules before publishing reviews.
5. Show Yu where that data is stored (the Supabase dashboard)
6. "Ask about Yu" AI button. **The API key must stay server-side**, never in the page.
7. Knowledge base for the AI (résumé, FAQs)
8. Visitor analytics, to measure growth
9. Write up the journey (keep the learning log in README.md updated)
10. LinkedIn post once traffic grows 10x

## Working across computers
Yu uses more than one computer. Remind Yu to **Fetch/Pull** in GitHub Desktop before starting and to **Commit + Push** when done.
