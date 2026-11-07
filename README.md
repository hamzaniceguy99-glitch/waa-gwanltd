# Waa-Gwan — information services

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `waa-gwanltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/waa-gwanltd.mjs`).
> To change the content, edit that file and run `node build.mjs waa-gwanltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@waa-gwanltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Waa-Gwan Ltd is a Gloucestershire company providing information services from Stroud, trading since May 2013. We find, check and supply information, and we publish it. The thing we tell anybody planning to let users post, comment or share on a website is the thing almost nobody has been told: the Online Safety Act has no small-business exemption. A service where content uploaded by one user can be encountered by another is a regulated service however small it is, with a UK regulator, an illegal content risk assessment that was due in March 2025, children's duties that followed in July 2025, and penalties reaching eighteen million pounds or ten per cent of qualifying worldwide revenue, whichever is larger. The duties themselves are proportionate to size and risk, but being in scope is not. The balancing fact matters just as much: real exclusions exist, and the one covering services whose only user content is comments or reviews on the provider's own published material takes a great many small publishers out of scope entirely. Working out which side of that line a site sits on takes about a day. Site: waa-gwanltd.shop
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
