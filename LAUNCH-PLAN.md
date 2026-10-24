# Launch Plan: Freelancer Invoice & Expense Kit

## 1. The product and why it can sell

**What it is:** a single HTML file that works offline as an invoice and expense tracker. You sell it as a one-time digital download.

**Who buys it:** freelancers, side-hustlers and very small businesses who
- send roughly 1–20 invoices a month,
- don't want to pay a monthly fee for accounting software, and/or
- want their client data to stay on their own device.

**Positioning:** "Buy once, own it, private." Most full invoicing tools are subscriptions. This product doesn't compete on features. It competes on simplicity, one-time price and privacy.

**What is honestly unknown:** I have no data on how many people will buy this. Nobody can promise sales. Treat the first launch as a cheap experiment and judge it by your own numbers: page visits, conversion rate and refunds.

## 2. Before you sell: checklist

- [ ] **Make it yours** (see section 6 on copyright). Add your own design touches, text and features.
- [ ] Replace placeholders: `YEAR`, `YOUR NAME`, `YOUR_EMAIL`, `BUY_LINK` in
      `product/invoice-kit.html`, `product/LICENSE.txt`, `landing/index.html`.
- [ ] Pick a product name and **search trademarks** before using it (USPTO TESS/Trademark Search, or
      your country's registry) and search the name on Gumroad/Etsy.
- [ ] Test on Chrome, Firefox, Safari and Edge. Print to PDF from each.
- [ ] Re-take screenshots with your own branding (`landing/img/`).
- [ ] Zip the deliverable: `invoice-kit.html`, `QUICK-START.txt`, `LICENSE.txt`.

## 3. Where to sell (fees are approximate, so verify before launch)

| Platform | Fee per sale (as reported in 2026 sources) | Notes |
|---|---|---|
| **Lemon Squeezy** | ~5% + $0.50; +1.5% for international/PayPal | Merchant of record, so it handles sales tax/VAT for you |
| **Gumroad** | ~10% + $0.50, **plus** card processing; 30% on sales through its Discover marketplace | Simplest setup, has a small built-in audience |
| Etsy / Payhip / your own Stripe | varies | Etsy has a large audience for "templates"; Payhip is a Gumroad alternative |

Rough example at **$19**, domestic card: Lemon Squeezy leaves about $17.5. Gumroad direct leaves about $15.7 after the extra ~2.9% + $0.30 card fee. These are estimates. Check each platform's official pricing page, and check payout fees if you live outside the US.

**Recommendation:** start on **Gumroad or Lemon Squeezy** for speed. Both deliver the file and handle checkout. Host `landing/index.html` for free on GitHub Pages, Netlify or Cloudflare Pages, or just use the platform's product page.

## 4. Pricing

- Launch at **$19** (or $12–15 as an early-bird price for the first week) and test.
- Optional higher tier at **$39**: the same kit plus extras you create yourself, such as invoice colour themes, a "how to get paid on time" PDF guide, or email reminder templates.
- Don't offer a 50%-off discount on day one. Raise the price later if buyers find it easily worth it.

## 5. Getting the first buyers (free channels)

1. **Show, don't pitch.** Post a short screen recording (30–60s): create an invoice, then export a PDF. This works on Reddit, X, LinkedIn, TikTok and YouTube Shorts.
2. **Communities:** freelancer subreddits and forums, design/dev Discords, and Indie Hackers. Read each community's self-promotion rules first. Lead with useful content; the link comes second.
3. **Free lead magnet:** give away a free printable invoice template (PDF) in exchange for an email address, then offer the full kit.
4. **SEO page:** a blog post such as "How to invoice as a freelancer (free template)" that links to the kit.
5. **Product Hunt / Gumroad Discover:** low effort, one-time spikes.
6. **Ask early buyers** for one sentence of feedback. Use real testimonials only, never made-up ones.

Track three numbers weekly: **visitors → sales → refunds.** If fewer than ~1% of visitors buy, change the headline, screenshots or price before spending more effort on traffic.

## 6. Copyright and ownership (please read)

*This is general information, not legal advice.*

- Under Anthropic's terms, rights in Claude's outputs are assigned to you, so no one else claims them. But **whether code or text written mostly by AI is protected by copyright is a separate question.**
- The **US Copyright Office** (*Copyright and Artificial Intelligence, Part 2: Copyrightability*, Jan 29 2025) says copyright protects only **human authorship**. Prompts alone are not enough. Your own creative selection, arrangement and modification of the output *can* be protected, judged case by case. Other countries' rules differ.
- **What this means in practice:** to have strong, defensible rights, put real creative work of your own into the product: design changes, wording, new features, a guide you write yourself. Keep your edit history in git as evidence.
- Your **license terms** (`LICENSE.txt`) and the platform's terms of sale still bind buyers contractually, whatever the copyright position.
- Any digital file can be copied. Your protection is the license, a fair price, updates and support, not DRM.

## 7. Next product ideas (reuse the same audience)

- Time tracker plus hourly invoice add-on
- Client proposal/quote generator (same codebase pattern)
- Freelance rate calculator
- Bundle all three as a "Freelancer Toolkit" at a higher price
