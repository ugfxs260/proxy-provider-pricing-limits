# best proxy provider: how to pick one without overpaying, plus real 9Proxy prices and limits

Search this phrase and you'll get a stack of listicles that contradict each other. PCMag leads with enterprise names, ZDNET leads with consumer-friendly ones, benchmark sites rank by response time, and affiliate blogs rank by whatever pays that month. None of them are lying, which is exactly the problem.

There is no single best proxy provider, because the bill is decided by one thing most comparison posts bury: are you buying traffic, or buying identities? A per-GB plan and a per-IP plan can differ by thousands of dollars for the same job, and choosing the wrong billing model hurts more than choosing the "wrong" brand.

So this does two things. First, the questions that actually settle the choice. Then a full run-through of one provider — 9Proxy — with its current price list, third-party test numbers, and the cases where you should buy somewhere else.

## The questions that decide it, in the order they matter

**Are you buying traffic or identities?** Per-GB pricing rents bandwidth. You rotate across a whole pool, each request can come from a different IP, and your cost scales with bytes moved. Per-IP pricing rents specific addresses with unlimited data attached — usually the better fit when a session has to survive across many requests, or when the volume per IP is large and unpredictable.

A quick sanity test: if your scraping pulls kilobytes per request but needs a fresh IP each time, per-GB wins. If each session downloads megabytes and needs to stay on one address, per-IP wins. If you genuinely need both, bundle plans exist for that, and they're usually cheaper than buying the two separately.

**How big is the pool, and where?** Pool size is marketed heavily and matters less than coverage where your targets live. "195 countries" sounds better than "90 countries" until you check whether the extra countries are ones you'll actually use. Verify the specific country before committing, especially for niche markets.

**What does success rate look like on *your* targets?** This is the number that decides whether a cheap provider is actually cheap. AIMultiple's residential benchmark put every provider they tested between roughly 50% and 67% on success rate, with no clear leader — which tells you something important: advertised pool size and advertised price don't predict whether requests complete. Only testing against your own target domains does.

**Can you test before you commit?** Free trials, low-cost entry plans, and refund policies matter more here than in most software categories, because a proxy that performs at 97% on one site can sit at 55% on another.

## Where 9Proxy sits in that picture

9Proxy is a residential-only provider launched in 2023. It advertises 20M+ residential IPs across 90+ countries, HTTP(S) and SOCKS5 support, and targeting down to country, city, ZIP code, and ISP. Billing is balance-based rather than subscription-based — you buy a package, and nothing auto-renews.

Two delivery models, and the difference matters operationally:

- **Residential by IPs** — fixed packages of residential IPs with unlimited bandwidth. IPs don't expire, but each individual IP has a natural lifespan of a few hours up to about 24 hours. Access runs through a desktop app that does local port forwarding, with optional proxy authentication.
- **Residential by GB** — you buy traffic, generate unlimited endpoints, and rotate dynamically or hold sticky sessions. Works straight from the dashboard with username/password or IP whitelisting, no app required. Traffic carries a 180-day validity window, unlimited on the enterprise tiers.

The IP-based product is the one worth understanding before you buy, because the "unlimited bandwidth" part is the whole pitch and the app requirement is the catch nobody mentions in a bullet list.

## Every 9Proxy package currently on sale

Prices below reflect the adjustment 9Proxy applied on 1 June 2026, which raised IP-based and bundle pricing; GB-based pricing was left unchanged. All packages are one-off purchases against an account balance — there is no monthly subscription on any of them.

| Package | Type | What's included | Price | Billing detail | Order |
| --- | --- | --- | --- | --- | --- |
| 100 IPs | Residential by IP | 100 residential IPs, unlimited bandwidth | $24 ($0.24/IP) | One-off, unused IPs never expire | [Get the 100 IP package](https://bit.ly/9-Proxy) |
| 500 IPs | Residential by IP | 500 residential IPs, unlimited bandwidth | $72 ($0.144/IP) | One-off, unused IPs never expire | [Order 500 IPs](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | Residential by IP | 1,500 IPs total including 500 bonus | $126 ($0.084/IP) | One-off, unused IPs never expire | [Claim the 1,000 IP package with 500 bonus](https://bit.ly/9-Proxy) |
| 2,500 IPs | Residential by IP | 2,500 residential IPs, unlimited bandwidth | $210 ($0.084/IP) | One-off, unused IPs never expire | [Order 2,500 IPs](https://bit.ly/9-Proxy) |
| 5,000 IPs | Residential by IP | 5,000 residential IPs, unlimited bandwidth | $360 ($0.072/IP) | One-off, unused IPs never expire | [Order 5,000 IPs](https://bit.ly/9-Proxy) |
| 15,000 IPs | Residential by IP | 15,000 residential IPs, unlimited bandwidth | $720 ($0.048/IP) | One-off, unused IPs never expire | [Order 15,000 IPs](https://bit.ly/9-Proxy) |
| 25,000 IPs | Residential by IP | 25,000 residential IPs, unlimited bandwidth | $863 ($0.035/IP) | One-off, unused IPs never expire | [Order 25,000 IPs](https://bit.ly/9-Proxy) |
| 50,000 IPs | Residential by IP | 50,000 residential IPs, unlimited bandwidth | $1,438 ($0.029/IP) | One-off, unused IPs never expire | [Order 50,000 IPs](https://bit.ly/9-Proxy) |
| 100,000 IPs | Business IP | High-volume tier, unlimited bandwidth | $2,300 ($0.023/IP) | One-off, unused IPs never expire | [Order the 100,000 IP business package](https://bit.ly/9-Proxy) |
| 200,000 IPs | Business IP | High-volume tier, unlimited bandwidth | $4,140 ($0.021/IP) | One-off, unused IPs never expire | [Order the 200,000 IP business package](https://bit.ly/9-Proxy) |
| 500,000 IPs | Business IP | Highest advertised volume tier | $8,625 ($0.018/IP) | One-off, unused IPs never expire | [Order the 500,000 IP business package](https://bit.ly/9-Proxy) |
| 5 GB | Residential by GB | 5 GB of rotating residential traffic | $15 ($3.00/GB) | 180-day validity | [Buy 5 GB of traffic](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | Residential by GB | 55 GB total | $105 ($2.10/GB) | 180-day validity | [Buy the 50 GB package with 5 GB bonus](https://bit.ly/9-Proxy) |
| 100 GB | Residential by GB | 100 GB of rotating residential traffic | $150 ($1.50/GB) | 180-day validity | [Buy 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | Residential by GB | 200 GB of rotating residential traffic | $200 ($1.00/GB) | 180-day validity | [Buy 200 GB](https://bit.ly/9-Proxy) |
| 1,000 GB | Residential by GB | 1,000 GB of rotating residential traffic | $800 ($0.80/GB) | 180-day validity | [Buy 1,000 GB](https://bit.ly/9-Proxy) |
| 2,000 GB | Residential by GB | 2,000 GB of rotating residential traffic | $1,500 ($0.75/GB) | 180-day validity | [Buy 2,000 GB](https://bit.ly/9-Proxy) |
| 3,000 GB | Enterprise GB | Bulk traffic, no expiry | $2,160 ($0.72/GB) | Validity unlimited | [Order the 3,000 GB enterprise package](https://bit.ly/9-Proxy) |
| 6,000 GB | Enterprise GB | Bulk traffic, no expiry | $4,200 ($0.70/GB) | Validity unlimited | [Order the 6,000 GB enterprise package](https://bit.ly/9-Proxy) |
| 10,000 GB | Enterprise GB | Bulk traffic, no expiry | $6,800 ($0.68/GB) | Validity unlimited | [Order the 10,000 GB enterprise package](https://bit.ly/9-Proxy) |
| Starter bundle | Bundle | 100 IPs + 5 GB | $30 | One-off; traffic carries 180-day validity | [Get the Starter bundle](https://bit.ly/9-Proxy) |
| Popular bundle | Bundle | 1,500 IPs + 50 GB | $180 | One-off; traffic carries 180-day validity | [Get the Popular bundle](https://bit.ly/9-Proxy) |
| Pro bundle | Bundle | 5,000 IPs + 500 GB | $720 | One-off; traffic carries 180-day validity | [Get the Pro bundle](https://bit.ly/9-Proxy) |

One note on that table: checkout has a coupon field, and the order summary shows the discount breakdown before you pay. Prices above are list. If there's an active code on your account, the number you actually pay is lower than the column.

## Which package matches which job

**One small scraper, one site, low volume.** The 5 GB package at $15 is the cheapest way in, and 180 days is generous enough for a proof of concept. If instead your job needs stable addresses rather than rotating ones, 100 IPs at $24 does more work than the GB figure suggests, because bandwidth on that model is unmetered.

**SEO rank tracking and SERP checks.** Request payloads are small, volume is high, rotation matters constantly. This is GB territory, and it's the reason the 100 GB and 200 GB tiers exist. Cost per GB drops from $3.00 to $1.00 between the smallest and fourth tiers — a 66% cut for a 40x larger commitment.

**Account and profile management.** Stable sessions, mixed traffic, and usually the requirement that an address behaves the same way across a long working session. IP-based packages fit better, and the unlimited bandwidth removes the anxiety of leaving a session open. Worth knowing: if you need an address alive for days, not hours, this model doesn't offer that — IPs run a few hours to roughly 24.

**Agency work with mixed projects.** The bundle tiers are the honest answer. Popular at $180 covers 1,500 IPs plus 50 GB, which is enough to run several client projects on different billing logic without splitting purchases.

**Reselling or running production infrastructure.** The Business and Enterprise tiers discount hard: $0.018 per IP at 500,000 IPs, $0.68 per GB at 10,000 GB. Those are commitment prices, not entry prices, and 9Proxy also runs a separate reseller program with wholesale pricing if that's your model.

## What independent testing actually found

Geekflare's review ran 300 requests against the network. 293 succeeded — 97.7%. Average response time came in at 0.63 seconds. Five CAPTCHA challenges all came from a single IP range, and rotating away from that range cleared them immediately, which is normal residential behaviour rather than a systemic problem.

Two caveats from the same review worth repeating here:

- There is **no self-serve free trial** on the site. Access to test IPs is arranged through community channels where the 9Proxy team is active, which is an extra step that more established providers don't impose.
- Coverage is **90+ countries, not 195**. US, UK, Europe, and Southeast Asia are solid. For niche geographies, verify before you commit.

The review also notes that the low Trustpilot scores trace back to refund-policy friction rather than proxy performance — users who bought a plan that didn't fit their use case and couldn't get the spend back. The practical lesson from that isn't about 9Proxy specifically; it applies to every provider that sells prepaid balances. Buy the smallest package that lets you test your real workload.

Directory listings put 9Proxy at 3.9/5 (ProxyLook) and around 4.78 user rating on Caproxy, where a March 2026 reviewer reported stable, fast residential IPs working with browser antidetect tools, and a July 2026 reviewer reported the service being down for about a week. That outage report is a single data point, not a pattern, but it's the kind of thing a comparison table won't tell you.

## Discounts: what's real and what's rotated out

Packages above already include the standing bonuses — 500 extra IPs bundled into the 1,000 IP tier, 5 GB extra on the 50 GB tier. Beyond that:

- **Payment methods.** Certain checkout methods carry an additional 5% discount or a 5% product bonus. It's visible on the checkout page, and it's the easiest discount to collect because it requires no code.
- **Referral discount.** 9Proxy's own partner FAQ states that users who sign up through a referral get a discount, with commissions of up to 15% paid to the referrer. Sign-up links carry the invite parameter, so this applies automatically rather than needing a code typed in.
- **Seasonal promos.** These rotate and expire fast. Lunar New Year 2026 ran an 8% discount on regular IP and GB packages with a public code; an April 2026 GB sale issued a personal 9% back coupon that expired 30 June. The pattern is real, the specific codes aren't permanently valid, so treat any coupon you find in a blog post as worth checking at checkout and nothing more.

9Proxy doesn't run a subscription, so there's no auto-renewal to cancel and no reason to buy more than your next quarter of work.

## When 9Proxy is the wrong purchase

Being straight about this saves you a refund argument:

- **You need datacenter or mobile proxies.** 9Proxy is residential-only. Datacenter access has been listed as upcoming, not available.
- **You need an address that lives for days or weeks.** IP lifespan runs hours to about 24. If your workflow needs a fixed address for a month, this isn't it.
- **You need 195-country coverage or pinpoint niche geos.** 90+ countries, and niche locations should be verified against your target list first.
- **You want a no-signup free trial.** There isn't one on the site.
- **You need enterprise paperwork.** MSAs, DPAs, and security questionnaires are the territory of Bright Data and Oxylabs, at correspondingly higher per-GB rates.
- **You're brand new to proxies and want zero setup.** The IP-based model requires a desktop app for port forwarding. Caproxy's listing puts it plainly: not the best pick for beginners.

## FAQ

**Is 9Proxy cheap compared to the big names?** On residential specifically, yes — significantly. Bright Data and Oxylabs start residential around $8.40–$12 per GB at low volume and $10.50/GB according to another 2026 comparison. 9Proxy starts at $3.00/GB and bottoms out at $0.68/GB. What you're trading for that is pool size (20M+ versus 72M+ or 100M+) and coverage breadth.

**Do unused IPs expire?** No. On the IP-based model, balance carries until you use it. GB packages expire after 180 days, except the Enterprise tiers, which don't expire at all.

**What payment methods work?** Credit cards, bank cards, cryptocurrency (USDT, BTC, ETH, LTC, DOGE and others), Alipay, Apple Pay, Google Pay, plus region-specific local payment options at checkout.

**Can I share an account with my team?** Yes — there's a sharing code and sub-account feature for managing access across people.

**Is it rotating or sticky?** Both models rotate. On GB plans you choose per-request rotation or sticky sessions with a configured session length. On IP plans, rotation runs through an Auto Rotation Proxy that switches at intervals you set on selected ports.

## The short version

If your workload is residential, rotation-heavy, price-sensitive, and doesn't need 200 countries, 9Proxy's numbers are hard to argue with: $3.00/GB at entry, $1.00/GB at 200 GB, or $0.24/IP at entry with unlimited bandwidth on top. Independent testing backs up the performance claims closely enough — 97.7% success over 300 requests, sub-second average response.

If you need datacenter IPs, long-lived sticky addresses, a self-serve trial, or a signed compliance agreement, go elsewhere and don't spend time on the comparison.

The one decision that matters more than the brand: work out whether you're buying traffic or identities before you open a pricing page. Get that right, and the rest of the shortlist narrows itself.

👉 [Check the current 9Proxy packages and coupon field at checkout](https://bit.ly/9-Proxy)
