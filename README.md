# Phoenix Kate site

New Phoenix Kate home, built to the Phoenix Kate brand: twilight palette (deep plum, lavender, rose, peach, constellation gold), serif display type, constellation motif. Deliberately a different skeleton from the Byers Design and Thicket and Bone sites. No Dark Moon Collective content.

## Files

- `index.html`: the whole site, one page (hero, The Work, Samhain Collection, About, Subscribe)
- `styles.css`: the theme
- `CNAME`: PhoenixKate.com for GitHub Pages

## Stripe links: DONE (2026-10-20)

All five buy buttons in `index.html` carry live Stripe payment links:

1. Grief Grimoire: https://buy.stripe.com/4gMbJ36Hp1kv9jNefU5Ne0a
2. Ancestors: https://buy.stripe.com/5kQ6oJ6Hpe7h2Vp3Bg5Ne09
3. Tarot Collection: https://buy.stripe.com/bJe14p9TB1kvanR6Ns5Ne08
4. Thinning the Veil: https://buy.stripe.com/9B65kF6Hp0grcvZdbQ5Ne07
5. Bundle: https://buy.stripe.com/14AcN71n5aV5brVb3I5Ne06

Prices as set: singles $14 each, bundle $39 (137 pages total, saves $17). Receipt/thank-you page copy lives at ~/workspace/your_files/samhain-collection/stripe-receipt-page-copy.md; each Stripe link should redirect to its thank-you page after purchase.

## Deploy (GitHub Pages, same as your other sites)

1. Upload `index.html`, `styles.css`, and `CNAME` to the repo.
2. Point PhoenixKate.com DNS at GitHub Pages (the same four A records: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a www CNAME to your github.io address.
3. After the domain verifies, turn on Enforce HTTPS.

## Notes

- Substack subscribe links point to https://phoenixkate.substack.com and Instagram to @pho3nixkate.
- Product descriptions match the Samhain listing kit page counts (27, 26, 47, 37 pages).
- Want changes (a Hecate devotional waitlist section, MoonX links, different copy)? Say the word.
