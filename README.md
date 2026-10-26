# Her & Earth — her & earth ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `herearthltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/herearthltd.mjs`).
> To change the content, edit that file and run `node build.mjs herearthltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@herearthltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per item / $Per refill / $Never) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Her & Earth Ltd is a London online retailer of natural and lower-impact products, trading since 2019. We sell skincare and body care, everyday and household goods, refills that reduce packaging, and gift sets, chosen for what they are made of and how they are made. Two promises shape how we write about them. Every environmental claim is one we can evidence: where a product is partly recycled, partly plastic-free or certified by a particular scheme, we say which part and which scheme rather than calling the whole thing eco. And a cosmetic is not a medicine, so we never claim a product treats, cures or prevents a condition, which would make it a medicine requiring authorisation. Everything bought online carries the statutory fourteen-day right to cancel. Site: herearthltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
