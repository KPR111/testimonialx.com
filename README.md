# TestimonialX — Collect & Embed Twitter Testimonials Automatically

> **[TestimonialX](https://testimonialx.com)** is the easiest way to collect real testimonials from Twitter/X, approve them in one click, and embed a beautiful widget on your website — no coding required.

[![Live App](https://img.shields.io/badge/Live%20App-testimonialx.com-black?style=for-the-badge)](https://testimonialx.com)
[![Twitter Testimonials](https://img.shields.io/badge/Twitter-Testimonials-1DA1F2?style=for-the-badge&logo=twitter)](https://x.com/TestimonialXcom)
[![Embed Widget](https://img.shields.io/badge/Embed-Widget-00C853?style=for-the-badge)](https://testimonialx.com)

---

## What is TestimonialX?

**TestimonialX** is a SaaS tool that connects to your Twitter/X account, automatically finds tweets that mention your product or brand, lets you approve them with one click, and generates an embeddable testimonial widget you can drop onto any website.

It solves a real problem: **you already have social proof sitting on Twitter — TestimonialX turns it into revenue-generating testimonials automatically.**

🔗 **Website:** [https://testimonialx.com](https://testimonialx.com)

---

## Key Features

### 🐦 Twitter/X OAuth Integration
Authenticate with your Twitter/X account via secure OAuth 2.0. TestimonialX reads tweets that mention your brand or product, surfaces them in your dashboard, and lets you approve or reject in seconds.

### ✅ One-Click Approval Workflow
Stop copy-pasting screenshots. Every incoming tweet testimonial lands in your approval queue. One click publishes it to your public-facing testimonial wall and embed widget.

### 🧩 Embeddable Testimonial Widget
Paste one line of JavaScript onto any website — Webflow, Framer, WordPress, Shopify, or custom HTML — and a live, auto-updating testimonial widget appears. No iFrame hacks. Clean, fast, customizable.

### 🔄 Testimonial Exchange Marketplace
Connect with other creators and SaaS founders. Exchange verified testimonials with complementary products. Grow your social proof network without cold outreach.

### 💳 Credit-Based Payment System
Flexible credit packs — buy what you need. No surprise invoices. Credits power testimonial collection, exchange requests, and API access.

### 📊 Auto-Post to X
When a testimonial goes live, TestimonialX can auto-post a thank-you or highlight tweet back to the original author — turning social proof into more social engagement.

### 🔍 Public Testimonial Pages (`/p/[id]`)
Every approved testimonial gets a public, SEO-indexed page. Share it in proposals, cold emails, or press kits. Google indexes them — giving your testimonials permanent search real estate.

---

## Who Is TestimonialX For?

| User Type | Use Case |
|---|---|
| **SaaS Founders** | Turn product mentions into embeddable proof on your landing page |
| **Indie Hackers** | Collect first testimonials fast without emailing customers |
| **Agencies** | Manage client testimonials from one dashboard |
| **Content Creators** | Showcase audience love without manual screenshots |
| **E-commerce Brands** | Surface Twitter reviews directly on product pages |

---

## How It Works

```
1. Connect your Twitter/X account via OAuth 2.0
2. TestimonialX scans for tweets mentioning your product
3. Review and approve testimonials in your dashboard
4. Copy the embed snippet → paste on your site
5. Widget goes live and auto-updates as you approve more
```

No plugins. No complex setup. **Under 5 minutes from signup to live widget.**

---

## Embed Example

```html
<!-- TestimonialX Widget — paste before </body> -->
<div id="testimonialx-widget" data-project="YOUR_PROJECT_ID"></div>
<script src="https://testimonialx.com/widget.js" async></script>
```

That's it. The widget is responsive, theme-aware (light/dark), and loads asynchronously so it never slows your page.

---

## Tech Stack

TestimonialX is built on a modern, production-grade stack:

- **Frontend:** Next.js 14 (App Router), Tailwind CSS, shadcn/ui
- **Backend:** [Convex](https://convex.dev) — real-time serverless database & functions
- **Auth:** NextAuth v4 + custom RS256/JWKS bridge for Convex
- **Payments:** Dodo Payments (credit packs, subscriptions)
- **Fonts/Design:** Syne, General Sans

---

## SEO & Public Testimonial Pages

Every testimonial published on TestimonialX gets:
- A permanent public URL: `https://testimonialx.com/p/[id]`
- Server-side rendered HTML (Googlebot-friendly)
- `og:` meta tags for rich social sharing
- JSON-LD structured data (`Review` schema) for rich search snippets
- Inclusion in the auto-generated sitemap

This means your testimonials don't just live on your website — they get **indexed by Google independently**, creating additional search surface area for your brand.

---

## Comparisons

### TestimonialX vs Senja

| Feature | TestimonialX | Senja |
|---|---|---|
| Twitter/X Auto-Collection | ✅ Native OAuth | ❌ Manual import |
| Testimonial Exchange Marketplace | ✅ Built-in | ❌ Not available |
| Public SEO Pages per Testimonial | ✅ Yes | ✅ Yes |
| Credit-Based Pricing | ✅ Flexible | ❌ Seat-based |
| Auto-Post Back to Twitter | ✅ Yes | ❌ No |

### TestimonialX vs Testimonial.to

| Feature | TestimonialX | Testimonial.to |
|---|---|---|
| Twitter/X OAuth Integration | ✅ Native | ⚠️ Limited |
| Testimonial Exchange | ✅ Marketplace | ❌ No |
| Embed Widget | ✅ JS snippet | ✅ iFrame |
| Free Tier | ✅ Credits included | ✅ Limited |

### TestimonialX vs EmbedSocial

| Feature | TestimonialX | EmbedSocial |
|---|---|---|
| Focus | Testimonials (Twitter-native) | Broad social aggregator |
| Approval Workflow | ✅ Per-tweet control | ⚠️ Feed-level |
| Exchange Marketplace | ✅ Yes | ❌ No |
| Pricing Model | Credits (pay as you go) | Monthly seat |

---

## Frequently Asked Questions

**Q: Do I need a Twitter developer account?**  
A: No. TestimonialX handles the OAuth connection. You just authorize with your regular Twitter/X login.

**Q: Will TestimonialX post anything without my approval?**  
A: Never. Every testimonial goes through your approval queue first. Auto-posting to X is also opt-in per project.

**Q: What happens if someone deletes their tweet?**  
A: Approved testimonials are stored in TestimonialX's database. Deletion from Twitter does not remove them from your widget.

**Q: Can I use this on multiple websites?**  
A: Yes. Each project gets its own embed snippet. One TestimonialX account can manage multiple projects/sites.

**Q: Is the embed widget customizable?**  
A: Yes — theme (light/dark/auto), layout (grid/list/carousel), and accent color are all configurable from your dashboard.

**Q: Does TestimonialX work with Webflow / Framer / WordPress?**  
A: Yes. Paste the JS snippet into any page that allows custom code. Works with all major website builders.

<!-- ---

## Roadmap

- [ ] Video testimonial support (Loom / YouTube embed)
- [ ] LinkedIn testimonial import
- [ ] Zapier / Make.com integration
- [ ] White-label embed (custom domain)
- [ ] CSV export for CRM import
- [ ] G2 / Trustpilot review import

--- -->

## Get Started Free

👉 **[Sign up at testimonialx.com](https://testimonialx.com/login)** — free credits included on signup, no credit card required.

<!-- ---

## Related Resources

- [How to collect Twitter testimonials automatically](https://testimonialx.com/blog/collect-twitter-testimonials)
- [Best testimonial widget for SaaS websites](https://testimonialx.com/blog/testimonial-widget-saas)
- [Social proof statistics that increase conversion](https://testimonialx.com/blog/social-proof-statistics)
- [How to embed testimonials on Webflow](https://testimonialx.com/blog/embed-testimonials-webflow)

--- -->

## License

This repository hosts the public documentation and GitHub Pages site for [TestimonialX](https://testimonialx.com). The TestimonialX application is proprietary software.

---

*TestimonialX — Turn Twitter mentions into your most powerful sales asset.*  
🔗 [https://testimonialx.com](https://testimonialx.com)
