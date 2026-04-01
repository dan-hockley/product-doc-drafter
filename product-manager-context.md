# DJ B2C CONTEXT ENGINE
# Compiled context for Dow Jones B2C product team.
# Use this as system context when generating product docs, PRDs, briefs, or strategy.
# Source of truth: github.com/danielhockley1337/dj-b2c-context
# Files included: 38


## FILE:company/glossary.md
# Dow Jones — Glossary

Terms, abbreviations, and internal jargon used across Dow Jones and the product team.

## Products and brands

| Term | Meaning |
| --- | --- |
| WSJ | The Wall Street Journal |
| MW | MarketWatch |
| IBD | Investor's Business Daily (acquired 2021) |
| BIC | Barron's Investor Circle — premium subscriber community |
| WSJ+ | WSJ bundle subscription product; expands multi-brand access |
| Free Expression | New subscription vertical combining newsletter sign-up and free account creation (launched Dec 2025) |

## Internal platforms and systems

| Term | Meaning |
| --- | --- |
| Piano / Composer | Paywall and subscription management platform; used for targeting, A/B testing, and subscription flows |
| CAJ | Checkout and acquisition journey — the checkout platform |
| SubsHub | Subscription management hub (upsell, save offers, user profile). Also referred to as SubHub in some internal docs — SubsHub is the canonical name. |
| OneID / DJOP | Dow Jones unified identity platform — single authentication layer across all DJ products |
| Braze | CRM platform used for mobile and email marketing, in-app messaging |
| Optimizely | A/B testing and experimentation platform |
| Statsig | Experimentation platform |
| JPD | Jira Product Discovery — roadmap and status tracking tool |
| Mosaic | Internal subscription management platform. Handles mid-term subscription changes including cancel, refund, and repurchase flows. Being extended by the Clean Transitions initiative to support credit-based offer switching without a full cancel-repurchase cycle. |
| BRS | Billing and Revenue System — handles charge groups, payments, credits, refunds, and receipts |
| CSM | Core Subscription Management — manages subscription state, term calculations, pro-rating, and transitions between offers |
| Verint | CRM tool used by Customer Service agents to access and manage customer accounts |
| Watson | Dow Jones offer targeting engine — returns eligible offers for a customer based on configured rules and directives |
| EDW | Enterprise Data Warehouse — central data storage and reporting system for product and business metrics |

## Process and planning

| Term | Meaning |
| --- | --- |
| RAG | Red / Amber / Green — status health system for roadmap items (also includes "On Hold") |
| LOE | Level of effort — engineering or design estimate |
| T-shirt sizing | Effort estimation: S (2 weeks / 1 sprint), M (6 weeks / 3 sprints), L (whole quarter) |
| Triad | The core product delivery unit: PM + Design + Engineering working together |
| CMO | Central Marketing Org — primary consumer stakeholder, accountable for subscription targets |
| DSAR | Data Subject Access Request |
| ROPA | Records of Processing Activities (GDPR Article 30) |
| DPIA | Data Protection Impact Assessment (GDPR Article 35) |
| IFE | In-Flight Entertainment (used in context of Delta partnership) |

## Metrics and data

| Term | Meaning |
| --- | --- |
| ARPU | Average Revenue Per User |
| CVR | Conversion rate |
| Churn | Rate at which subscribers cancel or lapse |
| Paywall impression | A user encounter with a paywall prompt |
| Save offer | A retention offer presented to a subscriber who is attempting to cancel |
| Win-back | Reacquisition offer targeting lapsed/cancelled subscribers |
| Crawl coverage | Percentage of priority content successfully crawled by search engines |
| Crawl waste | Percentage of crawl budget spent on non-priority pages |

## Customer journey stages

| Stage | Owned by |
| --- | --- |
| Traffic & Audience Growth | SEO |
| Registration & Nurture | Subscriber Acquisition |
| Conversion | Subscriber Acquisition |
| Activation | Subscriber Engagement, Revenue & Retention |
| Engagement & Revenue | Subscriber Engagement, Revenue & Retention |
| Retention & Win-back | Subscriber Engagement, Revenue & Retention |

## FILE:company/overview.md
# Dow Jones — Company Overview

## About

Dow Jones is a global provider of news, data, and analytics. It is a subsidiary of News Corp. Dow Jones publishes some of the world's most influential business and financial media across consumer subscription brands including The Wall Street Journal, Barron's, MarketWatch, and Investor's Business Daily.

This context repo covers the B2C (consumer) side of the Dow Jones business. B2B products (Factiva, Risk & Compliance, Newswires, DJ Platform) are out of scope.

As of the March 2026 Investor Briefing, Dow Jones described itself as a "news, data and intelligence powerhouse" — with authoritative editorial positioned as an essential input for the AI era.

## Financial highlights (FY2018–FY2025)

- Revenue base: **82% digital** (up from 60% in FY2018), **80% recurring** (up from 69%)
- **17% compound annual segment EBITDA growth** since FY2018
- Segment EBITDA margin: **25.2%** (nearly doubled since FY2018)
- Dow Jones has driven **11 successive quarters** of year-over-year Total Segment EBITDA growth at News Corp

## $1B EBITDA target

At the March 2026 Investor Briefing, News Corp detailed a pathway to **$1 billion in annual Dow Jones segment EBITDA within five years**, driven by:

- Accelerating Risk & Energy businesses (margin expansion)
- Accelerating direct-to-consumer offerings with new products and pricing
- Sharp focus on high-margin enterprise news
- Continuing cost discipline and operating leverage

## Key consumer brands

- **The Wall Street Journal** — flagship B2C subscription product; one of the largest paid digital news publications in the US
- **Barron's** — financial and investment news
- **MarketWatch** — real-time financial news and market data
- **Investor's Business Daily (IBD)** — acquired 2021
- **WSJ Pro** — premium vertical journalism for professionals
- **WSJ+** — multi-brand bundle subscription (WSJ, Barron's, MarketWatch, IBD)

## Headquarters

New York, NY (primary). Part of News Corp.

## Ownership

Subsidiary of News Corp (NWSA / NWS).

## Leadership

| Name | Title |
| --- | --- |
| Almar Latour | CEO, Dow Jones |
| Artem Fishman | CTO |
| Scott M. Havens | Chief Growth Officer & Global Head of Consumer |
| Emma Tucker | Editor in Chief, WSJ |
| Ryan Daly | SVP, Consumer Product |

## Competitive landscape

Dow Jones competes with FT, Bloomberg, NYT, and specialist financial media for digital subscribers.

## FILE:company/strategy.md
# Dow Jones — Strategy

## Strategic pillars

- **Subscription-first** — Consumer revenue is driven by paid digital subscriptions across WSJ, Barron's, MarketWatch, and IBD
- **Bundle growth** — WSJ+ bundle strategy is a key growth lever, expanding multi-product subscriptions across brands
- **AI as a monetization layer** — Dow Jones positions its authoritative editorial as an essential input for large AI models; licensing and AI product revenue are an expanding opportunity
- **Identity and first-party data** — The authentication and identity layer (OneID) is increasingly strategic, underpinning personalisation, bundling, and first-party data strategy
- **SEO and organic acquisition** — SEO is a primary top-of-funnel channel for WSJ and MarketWatch; positioning DJ properties for discovery via both traditional search and AI platforms

## North Star narrative (from March 2026 Investor Briefing)

Dow Jones frames itself as an **"Input company"** in the Age of AI — drawing an analogy to semiconductors and energy as inputs to the physical world. Authoritative editorial, trusted data, and proprietary risk/compliance intelligence are inputs to the digital and AI world. This framing underpins licensing deals with AI model providers and DJ's broader enterprise strategy.

> "As AI models are rippling from industry to industry, their output is only as good as their input, which is where Dow Jones comes in." — Almar Latour, CEO Dow Jones, March 2026

## Key strategic dynamics

- Platform team remit means solutions need to work across multiple brands and surfaces, not just solve for one
- Legal, privacy, and InfoSec reviews are standard for anything touching identity or billing
- Success metrics connect to subscription KPIs: paywall impressions, conversion rate, subscriber acquisition, churn, ARPU

## Competitive landscape

| Competitor | Where we compete |
| --- | --- |
| Financial Times | Business/financial news subscriptions |
| Bloomberg | Financial data, news, and professional terminals |
| New York Times | Digital news subscriptions, general audience |
| Specialist financial media | Vertical professional publications |

## FILE:goals/FY2026/priorities.md
# FY2026 Priorities — Commerce Product

> FY26 = July 2025 – June 2026
> Last updated: 2026-03-20

## Subscriptions priorities

- **Registration growth** — Grow monthly new free registered users from 20k to 135k
- **Conversion optimisation** — 10–15% incremental conversion lift via A/B testing program
- **Bundle growth** — Grow WSJ+ bundle subscriptions from 1M to 1.15M; deliver $80M bundle revenue
- **Early-life engagement** — Improve avg active days in subscriber's first 7 days (3.9 → 4.3)
- **Retention** — 10–15% lift in save offer take rate
- **New verticals** — Launch commerce surfaces for Free Expression, Connected paywall, Puzzles
- **Delta Partnership** — ~360k subscriptions projected over 3 years

## SEO priorities

- **Traffic ranking** — Move WSJ from #8 to #6 in share of traffic vs. competitors
- **Crawl coverage** — Improve from 55% to 65% (exceeded: hit 74% in Q2)
- **Crawl waste** — Reduce from 30% to 20% (at risk: at 49% in Q2)
- **Programmatic SEO** — Market data pages, topic pages, earnings calendar (MarketWatch)

## Identity priorities

- **OAuth2/OIDC** — Reach 100% token-based access across all products (baseline: 80%)
- **Data hygiene** — Delete ~2.3M inactive accounts (6+ years)

## Cross-team priorities

- In-app Meter — registered users get free articles on app
- Self-serve Corporate Sales shop page ($200k+ Q4 target)

## Notes

Last updated: 2026-03-20

## FILE:goals/FY2026/technology-okrs.md
# Technology FY26 OKRs

> Source: Technology FY26 OKR Tracker
> FY26 = July 2025 – June 2026 | Last updated: 2026-03-20

---

## Grow Subscriptions

### KR: Grow digital subscriptions
**Target:** Q4 average of 6.5M DJ digital subs (WSJ 4.3M)
**Owner:** Dan | **Tech Exec:** Ryan | **ETA:** Q4 | **Status:** TBC

---

### KR: Strengthen paywall strategy — registration growth
**Target:** +10% incremental conversions and 6x monthly registration growth (20k → 120k) by EOFY26
**Owner:** Dan | **Tech Exec:** Ryan | **ETA:** Q4 | **Status:** At Risk

---

### KR: Drive consumer engagement +15% (app weekly subscriber time spent)
**Target:** 1:02:05 → 1:11:24 overall app weekly subscriber time spent by EOH2 (via WSJ Redesign — Media & MyWSJ in H1)
**Owner:** Ryan | **ETA:** H1 | **Status:** Off Track

---

## FILE:goals/company-okrs.md
# Company OKRs — FY26

> FY26 = July 2025 – June 2026
> Last updated: 2026-03-20
> Full Technology OKR tracker: `goals/FY2026/technology-okrs.md`
> Commerce product OKRs: `goals/product-okrs.md`

---

## Top-line subscription targets (FY26)

| Metric | Target |
| --- | --- |
| DJ digital subscriptions | 6.5M (Q4 avg) |
| WSJ digital subscriptions | 4.3M (Q4 avg) |
| Monthly registered users | 120k cumulative |
| App weekly subscriber time spent | 1:11:24 |

---

## Technology OKR summary (FY26)

| OKR | Owner | Status |
| --- | --- | --- |
| Grow digital subs to 6.5M DJ / 4.3M WSJ | Dan / Ryan | TBC |
| Paywall — +10% conversion lift; 20k → 120k monthly registrations | Dan / Ryan | At Risk |
| Consumer engagement +15% app weekly time spent | Ryan | Off Track |

---

## FY27 strategic directions

1. Return to net positive subscriber growth (currently negative net new in volume)
2. Focus on engagement frequency (not time on site) as north star
3. Bolster core digital subscription with new value for new audiences (Games, Sports, Market Data)
4. Boost quality traffic with high subscription propensity (SEO/Audience team)

## Notes

Last updated: 2026-03-20

## FILE:goals/product-okrs.md
# Commerce Product OKRs

> FY26 = July 2025 – June 2026 | FY27 = July 2026 – June 2027
> Last updated: 2026-03-20

## FY26 OKRs — Status as of Q3

### Subscriptions

| OKR | Target |
| --- | --- |
| Grow monthly new free registered users | 20k → 135k |
| Incremental conversion lift from A/B testing | +10–15% |
| Deliver bundle revenue | $80M (from $68M) |
| Grow bundle subscriptions | 1M → 1.15M |
| Improve early-life engagement | 3.9 → 4.3 avg days (first 7) |
| Improve save offer take rate | +10–15% lift |

### SEO

| OKR | Target |
| --- | --- |
| WSJ share of traffic ranking | #6 (from #8) |
| Crawl coverage of priority content | 55% → 65% |
| Reduce crawl waste | 30% → 20% |

### Identity

| OKR | Target |
| --- | --- |
| OAuth2/OIDC token-based access | 100% (baseline: 80%) |
| Reduce inactive accounts (6+ years) | 0 remaining (baseline: 2,337,801) |

---

## FY27 OKRs — Draft

> Status: Draft — targets TBC pending input from Head of Growth and the business
> FY27 runs July 2026 – June 2027

### O1: Return to net subscriber growth
- KR1: Achieve net positive new subscriber volume by end of Q2, sustained through Q4
- KR2: Reduce voluntary churn rate through improved save and cancellation flows
- KR3: Reduce involuntary churn through billing recovery and payment failure intervention
- KR4: Improve paywall-to-checkout conversion rate through checkout improvements and experimentation

### O2: Build engagement habit through feature adoption and onboarding
- KR1: Increase share of new subscribers using core features within their first 30 days
- KR2: Improve 90-day retention rate among subscribers completing onboarding vs. those who don't
- KR3: Increase average experiment-driven lift in feature adoption rate across onboarding and in-app product marketing
- KR4: Increase share of active subscribers with 2+ active days per week (directional)

### O3: Build subscriber funnels for new subscription products
- KR1: Acquire new subscribers via Games and Market Data entry points by Q4
- KR2: Achieve target % of bundle upgrades completed via in-app purchasing by Q4
- KR3: Achieve target % of net new subscribers acquired via non-news entry points by end of FY27
- KR4: Achieve new registrations/subscribers via MarketWatch by Q4

### O4: Grow and convert the registered user base
- KR1: Grow monthly new free registrations to target by Q4
- KR2: Improve registered-to-paid user conversion rate
- KR3: Increase opt-in rate for lifecycle marketing channels among new registrants

### O5: Increase revenue per subscriber (ARPU)
- KR1: Achieve household subscription target by Q4, with price resilience rate higher than single-user plans
- KR2: Drive incremental WSJ+ Marketplace revenue by Q4
- KR3: Increase average revenue per subscriber across WSJ, Barron's, and MarketWatch

### FY27 dependencies (owned outside Subscriptions)
- Notifications/alerts hub — habit driver; owned by app/platform teams
- Newsletters in-app — owned by editorial product
- App performance (reliability, speed, offline mode) — owned by platform/engineering
- Content features (personalization, video, AI summaries) — owned by editorial/newsroom product
- Community features (commenting, Circles, Live QAs) — ownership TBC

## FILE:products/barrons/overview.md
# Barron's — Overview

## What it is

Barron's is a financial and investment news publication focused on market analysis, stock picks, and investment ideas. It has a long print heritage and a growing digital and mobile presence.

## Audience

- Individual investors and wealth managers
- Professionals in financial services
- Sophisticated retail investors

## Business model

Subscription-first, with advertising. Shares commerce infrastructure with WSJ. Part of the WSJ+ bundle.

## Key Commerce surfaces

- Paywalls — Piano / Composer
- Shop pages — CAJ checkout
- Barron's Investor Circle (BIC) — premium subscriber community; integrated with OneID and BigMarker livestream platform
- Barron's Mobile App NextGen — new app with Commerce surfaces (Q4 FY26 initiative)

## FILE:products/barrons/products.md
# Barron's — Product Inventory

A reference guide to the discrete products and features owned by the Barron's product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers Barron's-owned consumer experiences.

---

## Core Digital Products

### Barrons.com
The primary web destination for Barron's editorial content and subscriber experience.

- Covers market analysis, stock picks, investment ideas, fund rankings, and financial commentary
- Authenticated experience for subscribers; metered/paywalled for anonymous users
- Key sections: Stocks, Funds & ETFs, Bonds, Options, Retirement, Personal Finance, Economy
- Piano Composer-powered paywall; CAJ shop pages and checkout for subscription purchase

### Barron's iOS App
The native iPhone and iPad application for Barron's subscribers.

- Full editorial content access with offline reading capability
- Push notifications for market-moving stories and subscriber alerts
- In-app subscription purchase via Apple IAP
- Next-gen app rebuild in progress (Q4 FY26 initiative) to bring Commerce surfaces and improved UX

### Barron's Android App
The native Android application for Barron's subscribers.

- Feature-parity with iOS app; distributed via Google Play Store
- In-app subscription purchase via Google Play billing
- Part of next-gen app rebuild initiative

---

## Markets & Data

### Stock Picks & Ratings
Barron's proprietary stock analysis and ratings, a core differentiator for the brand.

- Long and short recommendations with thesis summaries
- Historical picks performance tracking
- Integrated with editorial content; a primary subscriber value driver

### Barron's Stock Screener
A tool for filtering and discovering stocks based on financial criteria.

- Available to subscribers as part of the investing tools suite
- Filters by sector, valuation, performance, dividend yield, and other metrics

### Market Data (Quotes & Watchlists)
Real-time and delayed market data embedded across Barrons.com and the app.

- Stock, ETF, mutual fund, and index quotes
- Personal watchlist creation and management for registered and subscribed users
- Company pages with financials, news, and analyst coverage

---

## Newsletters

### Barron's Daily
The flagship daily newsletter covering market movers, top stories, and investment ideas.

- Sent weekday mornings to subscribers and registered users
- High-intent financial audience; strong engagement rates

### Barron's Weekly
A weekend digest of the week's top picks, analysis, and market outlook.

- Mirrors the print magazine cadence
- Focuses on longer-form investment ideas and commentary

### Other newsletters
Topic-specific newsletters including income investing, ETF focus, and options coverage. Full list managed by the Editorial Newsletters team.

---

## Community & Events

### Barron's Investor Circle (BIC)
A premium subscription tier from Barron's, positioned as an "inner circle" for serious investors seeking an edge in the markets.

- Exclusive early access to stock picks and deeper research from Barron's analysts before wider publication
- Premium article experience with integrated market data analysis for deeper investment research
- Live and on-demand events with Barron's stock pickers, editors, and analysts, including Q&A access, powered by BigMarker
- Available as a standalone Barron's subscription or bundled with MarketWatch; three pricing tiers offered
- Integrated with OneID for subscriber authentication and entitlement verification
- Differentiator vs. competitors; targets high-intent investors willing to pay a premium for market intelligence

### Barron's Live Events
In-person and virtual conferences and roundtables for institutional and individual investors.

- Flagship event: Barron's Top 100 Financial Advisors Summit
- Additional events covering retirement, markets, and investment themes
- Ticket access often tied to subscription tier or separate purchase

---

## Print

### Barron's Magazine (Print)
The weekly print edition, one of the longest-running financial publications in the US.

- Published weekly; distributed via mail subscription and newsstand
- Print subscribers are managed in Mosaic alongside digital
- Print delivery management available via Subscriber Hub

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| Barrons.com & apps | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| Barron's iOS/Android apps | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Investor Circle (BIC) | OneID (auth), BigMarker (livestream platform) |
| Market Data | Third-party data providers (Factset and others) |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Print subscriptions | Mosaic (subscription management), Subscriber Hub |

## FILE:products/commerce/metrics.md
# Commerce — Metrics

## Primary KPIs

| Metric | Definition | FY26 target |
| --- | --- | --- |
| Monthly new free registered users | New free accounts created per month | 135k (from 20k baseline) |
| Conversion rate lift from A/B testing | Incremental conversion lift across experiments | +10–15% |
| Bundle subscriptions | Number of subscriptions in a bundle | 1.15M (from 1M) |
| Bundle revenue | Total revenue from bundle subscriptions | $80M (from $68M) |
| Early-life engagement | Avg active days in subscriber's first 7 days | 4.3 days (from 3.9) |
| Save offer take rate | Lift in save offer acceptance from A/B testing | +10–15% |

## SEO metrics

| Metric | FY26 target |
| --- | --- |
| WSJ share of traffic ranking vs. competitors | #6 (from #8) |
| Crawl coverage of priority content | 65% (from 55%) |
| Crawl waste | 20% (from 30%) |

## Identity metrics

| Metric | FY26 target |
| --- | --- |
| OAuth2/OIDC token-based access coverage | 100% (baseline: 80%) |
| Inactive accounts deleted (6+ years) | 0 remaining (baseline: 2,337,801) |

## Key subscription metrics (definitions)

### Top line / subscription health

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| New Subscription Orders | Total subscription orders in a period | Total orders over period | Daily / Weekly / Monthly | Must Have |
| New Subscription Starts | Total subscription starts in a period | Total starts over period | Daily / Weekly / Monthly | Must Have |
| Subscription Stops | Subscribers who lose access within a timeframe | Total stops over period | Daily / Weekly / Monthly | Must Have |
| Subscription Cancellations | Subscribers who turn off auto-renew | Total cancellations over period | — | — |
| Net New Starts | Starts minus stops | Total Starts − Total Stops | Daily / Weekly / Monthly | Must Have |
| User Conversion Rate | Conversion rate of all non-subscriber traffic | Total non-sub users / Total Orders | Daily / Weekly / Monthly | Must Have |
| Avg starts per order | Average subscription starts per order | Total Starts / Total Orders | Daily / Weekly / Monthly | Nice to Have |
| Bundle take rate | % of orders including 2+ starts across WSJ+ brands | — | — | — |
| Daily / Weekly active users | Users active on site or app in a given period | — | Weekly / Monthly | Must Have |
| Active days in first 7 days | Days a user had a session of at least X mins within first week of subscribing | # of days with 1+ session in subscribed day + 6 | Weekly / Monthly | Must Have |
| Engagement bracket | Users grouped by active days in last 28 days: Dormant (0), Occasional (1–5), Light (6–10), Mid (11–15), Super (16+) | Group users by 28-day active day count | Weekly / Monthly | — |
| Churn rate | % of subscribers no longer active over a timeframe | Split by web/app, monthly/annual, product, promo/list | — | — |
| Save rate | Rate at which users entering the cancellation funnel accept a save offer | # save offer accepts / # users entering cancellation funnel | Weekly / Monthly | Must Have |
| Net Revenue Retention (NRR) | Holistic measure of MRR change accounting for expansion, contraction, and churn | (Starting MRR + Expansion MRR − Contraction MRR − Churned MRR) ÷ Starting MRR | — | Nice to Have |

### Paywall

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| Total paywall impressions | # of times a paywall is loaded on a page (roadblocks, scrims, snippets, in-situ, dual CTA, live coverage, etc.) | Total paywall loads via Piano | Daily / Weekly / Monthly | Must Have |
| Paywall hit rate | % of pageviews that include a paywall impression | Paywall Impressions / Total non-sub pageviews | Daily / Weekly / Monthly | Must Have |
| Paywall conversion rate | % of paywall impressions resulting in an order | Total Orders / Total Paywall Impressions | Daily / Weekly / Monthly | Must Have |
| Top paywall conversion stories | Top 10 stories driving conversions | Top 10 by conversion count | Yesterday / Last 7 days | Nice to Have |

### Registration

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| Accounts created | Total new user accounts created | Total new accounts | Daily / Weekly / Monthly | Must Have |
| Registration wall impressions | Total impressions of regwall units (dual CTA, registration roadblocks) | Total regwall units delivered by Piano | Daily / Weekly / Monthly | Must Have |
| Registration wall conversion rate | % of regwall impressions resulting in a registration | New accounts via regwalls / Total regwall impressions | Daily / Weekly / Monthly | Must Have |

### Acquisition and conversion

| Metric | Definition | Priority |
| --- | --- | --- |
| Shop page impressions | Views of a subscription shop page | — |
| Shop page → order conversion | Users completing an order from a shop page visit | — |
| Shop page → checkout start | Users beginning checkout from a shop page visit | — |
| Shop page unique visits | Unique visitors to a given shop page | — |
| ARPU | Average Revenue Per User — total revenue / total visitors; used especially for Optimizely experiment analysis | — |
| LTV projections | Projected lifetime revenue per visitor based on sales data and bundle mix | — |
| Cart abandon rate | Users who begin checkout but do not complete an order | — |

### Core product engagement (activation)

| Metric | Definition |
| --- | --- |
| Value exchange metrics | Engagement where user receives value: article reads, listens, watchlist reads, video watches, puzzle plays, newsletter reads |
| Customisation metrics | Engagement where user invests in product: follows, saves, watchlist adds, interest selections, comments, newsletter subscriptions |
| Content breadth | # of sections engaged with (unique sections per user in last 28 days) |
| Content completion rate | % of content completed — articles, listens, videos, podcasts, puzzles, newsletters |
| App/web and cross-device engagement | Combination of surfaces (desktop web, mobile web, tablet web, app) a user engaged with in last 28 days |
| Time to first value | Time from session start to first content engagement |
| Session initiation method | How users start sessions: direct, email, push notification |

### Retention

| Metric | Definition |
| --- | --- |
| 1st renewal churn rate | Users who churn at their first renewal point (split by web/app, monthly, product) |
| Promo-to-list churn rate | Users who churn after stepping up to list price |
| Voluntary vs. involuntary churn | Voluntary: users on auto-renewal who cancel. Involuntary: users not on auto-renewal who lapse. Payment failure target: 50% recovery. |
| Save offer | Retention offer presented to a subscriber attempting to cancel |
| Win-back | Reacquisition offer targeting lapsed/cancelled subscribers |

## Data sources

- B2C Analytics: Emily C Williams (Senior Director, B2C Analytics, reports to Mike Shaw SVP Data Engineering)
- Experimentation analysis: Data Science & Analytics team
- Roadmap status: Jira Product Discovery (JPD) — RAG health

## FILE:products/commerce/overview.md
# Commerce — Overview

## What it is

The Commerce team owns the full subscription lifecycle across Dow Jones consumer products. This includes acquisition, conversion, billing, identity, and retention — across WSJ, Barron's, MarketWatch, IBD, and related brands.

Commerce operates as a **platform team** — solutions typically need to work across multiple brands and surfaces.

## Team lead

**Daniel Hockley** — VP of Product, Commerce (Mar 2025–Present)
Reports to: Ryan Daly (SVP, Consumer Product)

## Teams within Commerce

| Team | Focus | Customer journey stage |
| --- | --- | --- |
| SEO | Organic search visibility and traffic acquisition across WSJ, MarketWatch, Barron's | Traffic & Audience Growth |
| Subscriber Acquisition | Paywalls, shop pages, checkout, registration, offers | Registration & Nurture → Conversion |
| Subscriber Engagement, Revenue & Retention | Onboarding, upsell, save offers, win-back, churn reduction | Activation → Engagement → Retention |
| Subscriber Mobile | Mobile app subscription commerce across iOS and Android | Spans acquisition through retention |
| Identity & Entitlements | Authentication, access control, user identity across all platforms and brands | Infrastructure layer |

## Customer journey framework

```
Traffic & Audience Growth → Registration & Nurture → Conversion → Activation → Engagement & Revenue → Retention & Win-back
        (SEO)                   (Reg, Newsletters)    (Paywall/Checkout)  (Onboarding)    (Upsell, CRM)      (Save offers, Win-back)
```

## Products

The Commerce team owns a portfolio of discrete applications and platforms spanning this journey. See `products.md` for the full inventory with descriptions and dependencies.

Key product areas:
- **Full-funnel infrastructure** — Mosaic (subscription platform), Automated Pricing (ML-driven personalized offers)
- **Acquisition** — Paywall & Onsite Placements, CAJ Shop Pages, CAJ Checkout, Free Registration, Newsletter Sign-up, Partner Landing Sites, WSJ+ Marketplace, Corporate Self-Serve Checkout
- **Engagement & Retention** — CAJ Subscription Onboarding, Subscriber Hub, Braze CRM
- **Identity & Access** — One Identity/OneID (AuthN), PIB Entitlements (AuthZ)
- **SEO** — HTML Sitemap/News Archive (plus XML Sitemap, Robots.txt, Topic Collection Pages)

## Key platforms and tools

- **Piano / Composer** — paywall and subscription management, A/B testing, onsite placement targeting
- **Mosaic** — core backend subscription platform (order processing, billing, fulfillment)
- **CAJ** — customer acquisition journey: checkout, shop pages, onboarding
- **SubHub (Subscriber Hub)** — subscriber self-service account management
- **OneID / DJOP** — unified identity and authentication platform across all DJ products
- **PIB Entitlements** — authorization and access control platform
- **Braze** — CRM, email, in-app messaging, push notifications
- **ActionIQ** — customer data platform (CDP) used for segmentation and targeting
- **Watson** — rules engine for offer targeting and save offers
- **Optimizely / Statsig** — A/B testing and experimentation
- **BRS** — billing and payment processing backend
- **JPD (Jira Product Discovery)** — roadmap and initiative tracking

## Strategic context

- Identity/authentication layer is increasingly strategic — first-party data, personalisation, and bundling all depend on it
- WSJ+ bundle strategy is a key growth lever — expanding multi-product subscriptions
- Legal, privacy, and InfoSec reviews are standard dependencies for anything touching identity or billing
- Platform team remit means solutions typically need to work across multiple brands and surfaces
- Checkout friction is a known gap vs. competitors (NYT, Bloomberg) — reducing drop-off is an ongoing investment
- Registered user base is a key growth area — free registrations act as a nurture layer before paid conversion

## FILE:products/commerce/products.md
# Commerce — Product Inventory

A reference guide to the discrete products and applications owned by the Commerce team. Grouped by area of the customer journey.

---

## Full-Funnel Infrastructure

### Mosaic
The core backend subscription platform underpinning all consumer acquisition, engagement, and retention across Dow Jones brands. Originally launched 2008 on Oracle technology, now fully cloud-based. Consolidates various subscription platforms and adheres to PCI, SOX, and GDPR requirements.

- Handles order processing, billing, entitlement fulfillment, and subscription lifecycle management
- Integrates with BRS (billing), Snowflake data lake, AWS, app stores (Google Play, iOS, Samsung), and payment processors (Apple Pay, PayPal, Amazon)
- Used by: all consumer brands (WSJ, Barron's, MarketWatch, IBD) and enterprise/partner subscribers

### Automated Pricing
A dynamic pricing system that uses machine learning models to deliver personalized subscription price points based on customer attributes, behavior, and market conditions.

- Operates across four journeys: acquisition (new subscribers), renewals (step-up pricing), saves (cancellation deflection), and winbacks (lapsed subscribers)
- ML models built and maintained by Data Science; rules engine (Watson) accepts customer parameters and surfaces appropriate offers
- Integrates with ActionIQ for email and social media delivery to external channels
- Owned jointly with Marketing Operations and Data Science

---

## Acquisition

### Paywall & Onsite Placements
The front-end experience controlling content access for non-subscribers and free registered users across consumer brand websites and apps.

- Built on Piano Composer for ruleset management, targeting, A/B test delivery, and in-built propensity scoring
- Supports multiple formats: roadblocks, scrims, in-situ paywalls, dual CTAs, snippet paywalls, live coverage paywalls
- Also manages registration walls (regwalls) that gate content behind free account creation
- Content Access is the backend system handling entitlement checks, OneID session handshake, article encryption/decryption, Automated Pricing integration, bot whitelisting, and Google Extended Access
- Revenue User Profile persists user profile data and enables segmentation via ActionIQ

### CAJ Shop Pages
Web-based subscription offer pages where users view, compare, and select subscription packages before proceeding to checkout.

- Mobile responsive; supports web-desktop, web-mobile, and in-app webview rendering for next-gen apps
- Shop page templates are built by CAJ engineering; CircOps can configure new pages with `?page=` params for campaign targeting
- Supports personalized offers via Watson (offer targeting), Automated Pricing, and A/B testing
- Serves all DJ brands with brand-specific theming

### CAJ Checkout
The checkout and payment experience for completing subscription purchases across all Dow Jones brands.

- Handles account creation, payment processing, and order confirmation
- Supports credit cards, Apple Pay, and PayPal; responsive across web, mobile web, and in-app webviews
- Brand-specific theming for WSJ, Barron's, MarketWatch, and IBD (IBD has a slightly different account creation flow)
- Key known friction: checkout takes ~3 minutes vs ~1 minute for competitors (NYT, Bloomberg); ongoing work to reduce drop-off

### Free Registration
A lightweight account creation experience for users coming from the paywall who don't yet have an account.

- Allows manual sign-up or social sign-in (Facebook, Google, Apple)
- Creates a registered user entitlement granting limited free article access across DJ brands for a defined period
- Acts as a nurture step before prompting users to subscribe
- In-article placement work ongoing to improve time-to-first-value

### Newsletter Sign-up
A minimal application allowing users to sign up for specific newsletters by submitting their email address.

- Supports both anonymous email entry and single-click sign-up for registered users
- Consistent experience across brands
- Surfacing additional newsletter sign-up opportunities in new areas is an active focus

### Partner Landing Sites (PLS)
A redemption and registration platform for subscribers who acquired access through third-party channels (corporate group sales, app stores, partnerships).

- Two main components: customer-facing redemption/registration flow and a Partner Admin Portal for managing licenses and seats
- Supports WSJ, Barron's, MarketWatch, Financial News London, Private Equity News, and Mansion Global
- Admin Portal enables bulk invitations, redemption tracking, and seat management for corporate partners
- Also serves as the entry point for app store subscribers who need to register a web account

### WSJ+ Marketplace
An exclusive in-subscription commerce hub where WSJ+ subscribers can discover and purchase additional premium Dow Jones products at subscriber-only rates.

- Consolidates supplementary products (newsletters, investing tools, educational resources) into a single place and a single bill
- Currently targets WSJ+ subscribers on every-4-week billing; annual subscriber expansion planned
- Partner content expansion (e.g. The Economist) in discussion
- Removes the fragmented purchasing paths that exist when users discover add-ons across different brand sites

### Corporate Self-Serve Checkout
A self-service purchase funnel for small to medium business customers buying WSJ group subscriptions (10-25 seats) without sales team involvement.

- Includes a corporate-focused marketing landing page and a streamlined checkout with seat selection
- Designed to remove friction in a traditionally long sales process
- Currently WSJ-only; expansion to other brands and products planned
- Integrates with existing corporate subscription management systems

---

## Engagement & Retention

### CAJ Subscription Onboarding
A guided post-purchase onboarding flow that helps new subscribers understand their benefits, set preferences, and take first steps toward engagement.

- Personalizes the experience based on interests, industries, and content preferences
- Prompts key activation actions: app download, newsletter subscriptions, feature education (watchlists, alerts)
- Also used for upgrade flows and CRM-triggered re-onboarding campaigns
- Optimized for Time to Value — getting subscribers to first meaningful content engagement quickly

### Subscriber Hub (SubHub)
A self-service account management platform for existing subscribers to manage subscriptions, billing, and account details across all DJ brands.

- Covers: payment updates, subscription upgrades/downgrades, cancellation, print delivery management, and customer support access
- Presents save offers (pricing alternatives, pauses) to subscribers attempting to cancel
- Aims to reduce calls to customer service by enabling self-service resolution
- Integrates with One Identity, Mosaic, Twilio, Genesys, and Watson

### Braze CRM
The primary marketing automation and messaging platform used to engage subscribers and prospects with personalized communications.

- Supports email, in-app messaging, push notifications, and content cards across web and mobile (iOS, Android)
- Integrates with ActionIQ (CDP) for audience segmentation and AppsFlyer for attribution tracking
- Used across: WSJ, Barron's, MarketWatch web and app platforms
- Migrating from previous solution (Airship) to Braze for mobile messaging

---

## Identity & Access

### One Identity (OneID) — AuthN
The authentication platform that creates, stores, and verifies user identities across all Dow Jones products.

- Assigns unique user identifiers used for cross-product tracking throughout the DJ ecosystem
- Supports persistent login, social sign-in (Facebook, Google, Apple), SAML/SSO, IP whitelisting, and token-based authentication (OAuth2/OpenID Connect)
- Stores PII and manages user sessions across web and mobile platforms
- Serves both B2C (WSJ, Barron's, MarketWatch) and B2B (Factiva, Risk & Compliance, Newswires, etc.) products
- Target: 100% token-based (OAuth2/OIDC) coverage across all products; currently ~85%

### PIB Entitlements (AuthZ)
The authorization platform that determines and enforces what content and features users can access based on their subscription level and organizational permissions.

- Manages entitlements for both consumer subscribers and enterprise/B2B users
- Handles complex subscription models, contractual rules, regional restrictions, and legal compliance controls
- Cross-product integration enables seamless content access across multiple DJ products in a single session
- Target: 100% entitlement coverage across all products; currently ~85% (some complex B2B platforms still migrating)

---

## SEO

### HTML Sitemap (News Archive)
A structured, crawlable directory of all WSJ content designed to maximize search engine crawl efficiency.

- Hierarchical structure (years > months > days > articles) provides access to all content within 5-6 clicks
- Includes orphaned content (videos, live coverage) not accessible from main navigation
- Pagination removed to reduce crawl waste
- Primary consumer is search engine crawlers; secondary use is archived content navigation for readers

> Note: The SEO team also owns XML Sitemap, Robots.txt, and Topic Collection Pages — see the SEO team section for full coverage.

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| All acquisition flows | One Identity (account creation/login) |
| All acquisition flows | Mosaic (order processing) |
| CAJ Checkout | BRS (billing), Mosaic, OneID |
| Paywall / Regwall | Piano Composer, Content Access, OneID |
| Automated Pricing | Watson (rules engine), Data Science ML models |
| Partner Landing Sites | OneID, PIB Entitlements |
| Subscriber Hub | Mosaic, OneID, Watson |
| Braze CRM | ActionIQ (CDP), AppsFlyer |
| WSJ+ Marketplace | CAJ Checkout, Mosaic, OneID |

## FILE:products/commercial-tech/products.md
# Commercial Technology — Product Inventory

A reference guide to the discrete products owned by the Commercial Technology team. Commercial Technology is a monetization-focused team within the Dow Jones B2C org, separate from Commerce. It owns the ad products, ad infrastructure, privacy platform, and internal tooling that power advertising across Dow Jones properties (~$300M+ digital advertising business).

---

## Ad Products

### SafeSuite
A set of brand safety and suitability tools that help advertisers avoid unsafe or misaligned content environments, ensuring campaigns run against trusted, high-quality inventory.

### Thematic AI
An AI-driven audience and content understanding product that identifies themes, topics, and intents in Dow Jones content and user behavior to power more precise targeting and insights.

### Theme Definer
A classification and taxonomy tool that standardizes how content and audiences are grouped into "themes," enabling consistent targeting, reporting, and packaging across products and campaigns.

### Dynatic
A dynamic advertising and experience product that uses data signals and creative rules to tailor ad experiences and placements, improving relevance and performance for advertisers.

### Ad Formats
A suite of proprietary ad formats for direct-to-subscriber experiences. Formats include Hero, Titan, Folio, VStudio, and Mosaic, as well as vertical and horizontal video (VAST/VPAID), native desktop/app placements, and a Dynamic Market Data Tool that integrates live financial data into ad creatives.

- Targets readers and subscribers directly; enables campaign-specific KPIs and custom executions
- Used by MMS Sales; an alternative to internal DJ Design/Consulting for custom advertising

---

## Ad & Privacy Platforms

### Ad Platform
Core ad-serving and configuration infrastructure that standardizes how ads are requested, rendered, and managed across Dow Jones properties. Includes shared components such as the Universal Ad Component and Orchestrator, plus Geneva for centralized ad configuration.

### Privacy Platform (DJCMP)
The Dow Jones Consent Management Platform middleware that sits between third-party CMPs (e.g. Sourcepoint / IAB SDK) and Dow Jones products. Provides a unified API and framework to enforce consent, vendor management, privacy notices, DSARs, and data retention across stacks and brands.

### Newsletters Ad Platform (NAPL)
An advertising platform for native ads in newsletters. Manages newsletter ad inventory, targeting, tracking, and campaign execution across brands — giving Sales and Ad Ops a consistent way to sell, deliver, and report on newsletter ad products.

---

## Information Systems

### InSite
A proprietary first-party data-powered audience analytics suite. Marries data from Adobe (web analytics), Google Ad Manager (ad server), and the Dow Jones CDP to provide audience-based insights not available from any single platform.

- **Pre-sale:** Provides first-party data insights to quantify and support specific product pitches to advertisers
- **Post-sale:** Delivers campaign/line item/creative audience performance metrics for mid-campaign optimisation and end-of-campaign reporting
- **Content Insights:** Leverages audience data from previous campaigns to refine renewal discussions and future pitches
- Used by Planning, AdOps, RevOps, Performance, Sales, and Client Success across MMS

### Seawolf
An internal product that protects the advertising exchange business via stewardship and execution controls. Addresses the gap in the Order Management System for exclusive sponsorship coordination and campaign health monitoring.

- **Buyout Calendar:** Allows the DOCS team to manage bookings with an accurate picture of buyout availability for exclusive sponsorships (e.g. homepage takeovers). Augments the OMS with "holds" to eliminate reliance on email/Slack for cross-team coordination across hundreds of exclusive products
- **Cadence:** Monitors active campaigns against pre-launch requirements and in-flight thresholds; proactively alerts AdOps when intervention is needed rather than discovering issues after the fact
- Key outcome: near-zero makegoods due to double-booking; alerts responded to in a timely manner

### Monty
An in-house tool that allows Sales to independently build contracts and generate real-time quotes for advertising deals without relying on Planning — enabling faster deal closure and more efficient use of people.

- **Monty (Digital):** For digital advertising deals; Sales can create contracts for simpler clients independently
- **Print Monty:** Equivalent tool for print advertising deals
- Metrics tracked: average time to create a deal, percentage of deals using Monty, YoY revenue, average deal size, win rate

### DASH
An internal advertising data and operations system built on Tableau. Aggregates data from multiple source systems (Google Ad Manager, AdBook, IAS, Megaphone, etc.) into a single interface for campaign performance monitoring and end-of-campaign reporting.

- Supports the MMS teams across Planning, AdOps, RevOps, Performance, Sales, and Client Success
- Under evaluation for potential deprecation if Looker meets all MMS use cases

### WSJBG Ad Manager (DanAds)
Previously known as DanAds and WSJ Ad Manager. A self-serve advertising platform powered by the DanAds platform, enabling advertisers and agencies to plan, buy, and manage campaigns directly — without IO processing or managed-service involvement.

- Primary audience: advertisers and agencies (new and existing), particularly SMB advertisers who would be turned away by Direct Sales due to budget size or bandwidth
- Supports credit card and invoicing payment options; real-time campaign management and optimisation
- Secondary audience: MMS Sales team (Client Associates, Associate Client Partners, Client Partners)
- Competes with programmatic platforms (Google, Meta, LinkedIn) for SMB ad budgets

### Looker
The business intelligence and analytics layer for Commercial Technology. Connects to Snowflake and provides curated dashboards and data models for advertising, revenue, and operations across MMS teams.

- Platform partner: Google (Looker Core)
- Primary users: Planning, Performance, AdOps; secondary users: Sales, Client Success, RevOps
- Positioned to replace DASH as the single BI tool for MMS if it meets all use cases
- Supports monitoring and analysis of campaign performance, internal insights, and client-facing reporting

## FILE:products/fnlondon/overview.md
# Financial News London — Overview

## What it is

Financial News (FN) is a premium London-based digital and print publication covering the wholesale financial services industry in the UK and Europe. Effectively the trade paper for the City of London. Founded in 1996 by Angus MacDonald and John Benson; acquired by Dow Jones in 2007 for approximately £79 million. Sits within the Barron's Group division of Dow Jones alongside Barron's, MarketWatch, and Mansion Global.

Note: FN is a separate entity from the original *Financial News* founded in 1884 (which merged with the Financial Times in 1945).

## Audience

- Finance professionals in the City of London and broader European financial services sector
- Over 54% of readers are in senior management (C-suite, MDs, board members)
- Average reader income is high — exceeds the general finance professional population
- Key sectors: investment banking, asset management, private equity, regulation
- UK and Europe-primary; international readers in financial services

## Business model

Subscription-first with hard paywall, reflecting a narrow, high-value professional audience.

- Individual subscriptions at a significant premium vs. consumer publications
- Corporate licenses are the primary revenue driver — over 178 major firms (banks, law firms, consultancies) hold enterprise-wide licenses

## Coverage areas

- Investment banking: deals, M&A, IPOs, capital markets activity
- Asset management: institutional investing trends, fund performance, ESG
- Private equity: operates a specialized daily service, *Private Equity News*, covering European buyouts
- The People section: senior appointments and departures across the City — one of FN's most-read features
- Financial regulation: FCA, EU/ESMA, Basel updates in real time

## Key products and features

- **FN 100**: annual list of the 100 most powerful people in European finance; highly influential as a status signal in the City
- **FN Awards**: prestigious annual ceremonies including Awards for Excellence in Investment Banking
- **Private Equity News**: dedicated daily coverage of European private equity
- **Newsletters**: Morning Briefing and sector-specific updates
- **Events**: high-level roundtables and conferences in London for industry leaders

## Relationship to Dow Jones / WSJ

- Sits within the Barron's Group division of Dow Jones; editorially independent with UK-centric voice
- Shares Commerce infrastructure: OneID (authentication), Mosaic (subscription management), PIB Entitlements
- Partner Landing Sites (PLS) supports FN for corporate/group subscriptions
- Serves as the European counterpart to WSJ Pro — regional depth complementing WSJ's global breadth
- **LSEG Partnership (2024):** Multi-year deal with the London Stock Exchange Group; FN content integrated into LSEG Workspace (Bloomberg-equivalent terminal), significantly expanding reach to terminal users
- Enterprise custom news dashboards combining FN and WSJ content available for corporate clients

## FILE:products/ibd/overview.md
# Investor's Business Daily (IBD) — Overview

## What it is

Investor's Business Daily (IBD) is a financial news and research platform focused on helping individual investors identify leading growth stocks using a disciplined, data-driven system. Founded in 1984 by William O'Neil as *Investor's Daily*; transitioned to digital-first in 2016; acquired by News Corp / Dow Jones in 2021 for $275 million. Operates as a stand-alone brand within the Dow Jones segment alongside WSJ and Barron's.

## Audience

- Self-directed retail investors and momentum/growth traders — primarily US-based
- Investors following a rules-based approach to stock picking
- Financial professionals using IBD data and ratings
- Increasingly targeting novice investors as an entry point into the DJ ecosystem (via MarketDiem newsletter)

## Business model

Subscription-first with a tiered product ecosystem, from free content to premium tools. Dow Jones also offers an "Investor Bundle" combining IBD Digital, WSJ, and Barron's at a combined rate. IBD is considered a high-margin digital pillar within News Corp's broader strategy.

## The CAN SLIM Methodology

IBD's signature stock-picking framework, developed by O'Neil by studying every top-performing stock since the 1880s. Each letter stands for a criterion:

- **C** — Current quarterly earnings (25%+ growth)
- **A** — Annual earnings growth (25%+ over 3-5 years)
- **N** — New product, service, management, or price high
- **S** — Supply and demand (high volume on price breakthroughs)
- **L** — Leader or laggard (buy the top stock in the top industry)
- **I** — Institutional sponsorship (follow the "smart money")
- **M** — Market direction (trade only in a Confirmed Uptrend)

## Key products and features

### IBD Digital (Base subscription)
- Full access to IBD.com editorial content — actionable and educational, not general news
- IBD Stock Lists: IBD 50, Sector Leaders, IPO Leaders, Big Cap 20
- Stock Checkup: free tool; "traffic light" (Green/Yellow/Red) evaluation of any stock's health against CAN SLIM criteria; entry point for non-subscribers
- IBD Ratings (all on 1-99 scale): Composite Rating (combined score), EPS Rating, Relative Strength (RS) Rating, SMR Rating (Sales growth, profit Margins, Return on equity), Accumulation/Distribution Rating
- Industry Group Rank: IBD tracks ~197 industry groups ranked 1-197; CAN SLIM investors focus on top-ranked groups
- Market Trend page / The Big Picture: daily guidance on market direction (Confirmed Uptrend, Uptrend Under Pressure, Market in Correction) — one of IBD's most-read features
- **IBD 50 ETF (ticker: FFTY):** managed by Innovator ETFs, tracks the IBD 50 list; extends IBD's brand into passive investing

### MarketSurge (formerly MarketSmith — rebranded March 2024)
Premium stock research and charting tool. Includes:
- Algorithmic pattern recognition (cup-with-handle, flat base, double bottom, etc.) with automatic buy point identification
- Proprietary "The Ants" indicator: flags intense institutional accumulation before a stock breaks out
- Fundamental data screening, earnings estimates, and historical price/volume analysis

### Leaderboard
A curated, actively managed list of top growth stocks meeting CAN SLIM criteria, with real-time buy/sell annotations from IBD analysts.
- Includes specific entry points, stop losses, and profit targets
- Designed as a "plug-and-play" service for investors who want analyst guidance

### SwingTrader
Shorter-term trade ideas for active traders with holding periods of days to weeks.
- Distinct from Leaderboard's longer-term growth stock focus

### IBD Live
A daily interactive broadcast where IBD analysts screen stocks and analyze charts in real time.
- Available weekday mornings; subscriber add-on

### Newsletters
- The Big Picture: daily market analysis interpreting IBD's Market Trend signals
- IBD 50: weekly list of top-rated growth stocks
- MarketDiem: newer newsletter targeting novice investors with simplified daily trade ideas; onboarding funnel into the IBD ecosystem

## Relationship to Dow Jones

- Acquired by News Corp / Dow Jones in 2021 for $275M; operates as a stand-alone brand with editorial independence
- Shares Commerce infrastructure: OneID (login/identity), PIB Entitlements (access), Mosaic (subscription management)
- CAJ Checkout handles IBD subscription purchases (slightly different account creation flow vs WSJ/Barron's)
- IBD proprietary data increasingly used as "clean" training data for Dow Jones financial AI models
- Bundled with WSJ and Barron's in the Investor Bundle

## FILE:products/mansionglobal/overview.md
# Mansion Global — Overview

## What it is

Mansion Global is a digital-first luxury real estate and lifestyle platform owned by Dow Jones (News Corp). Launched in May 2015, it combines a global luxury property listings database with editorial content covering market analysis, lifestyle, and investment advice. It sits within the Dow Jones Barron's Group alongside Barron's, MarketWatch, and Financial News.

## Audience

- High-net-worth and ultra-affluent individuals buying, selling, or investing in luxury property globally
- 52% of readers are millionaires; average household net worth $2.2M, average household income $433K
- International audience: over 53% of traffic is from outside the US (significant EMEA and APAC reach)
- Real estate agents and brokers in the luxury segment

## Business model

Primarily advertising and listings-revenue led — free to access for consumers. Revenue drivers:

- Real estate broker/developer listing packages (tiered pricing based on volume — small batches to large developer inventories)
- Newsletter sponsorships and market page advertising
- Print supplement sales ("Experience Luxury" magazine, sold through WSJ Shop)

## Coverage areas

- Luxury residential property listings worldwide
- Market analysis: prime markets (London, NYC, Dubai, Hong Kong) and emerging luxury destinations
- Lifestyle and design: architecture, interior design, historic preservation, home technology
- Financial and tax advice for international property buyers
- Multilingual content: English, Spanish, and Chinese

## Key products and features

- **Property search portal**: searchable global luxury listings database with Lifestyle Search (filter by Golf, Historic, Beachfront, etc.)
- **"Experience Luxury" magazine**: quarterly print supplement distributed with The Wall Street Journal
- **Mansion Global TV**: program on Fox Business Network showcasing luxury homes and lifestyle trends
- **Mobile app**: dedicated app for property browsing and real-time market news
- **Newsletters**: daily market updates and listing highlights; newsletter sponsorships are a revenue driver

## Relationship to WSJ and News Corp

- Editorially independent from WSJ but operates as a close partner; produces the "Experience Luxury" WSJ print supplement and shares content with WSJ's Mansion section
- Part of News Corp's Digital Real Estate Services segment — the most profitable News Corp segment as of 2025
- Cross-platform relationships within News Corp: Realtor.com (News Corp owns ~80%, Mansion Global provides luxury top-of-funnel content) and REA Group (News Corp owns ~61%, Australia's leading property site)
- Shares DJ commerce infrastructure: OneID, PIB Entitlements, Mosaic
- Partner Landing Sites (PLS) supports Mansion Global for corporate/group subscriptions

## FILE:products/marketwatch/overview.md
# MarketWatch — Overview

## What it is

MarketWatch is a real-time financial news and market data platform covering markets, personal finance, and economic news. It has a broader, more mass-market audience than WSJ or Barron's, with heavy digital and mobile usage.

## Audience

- Retail investors and personal finance readers
- Broader and more general than WSJ/Barron's
- High traffic, high mobile usage

## Business model

Historically advertising-led; subscription component growing. MarketWatch became a subscription product, and the Commerce team has been building out its subscription surfaces.

## Key Commerce surfaces

- Paywall — Piano / Composer
- Shop pages — CAJ checkout
- Candy bar (promotional unit) — hompage acquisition surface
- Earnings Calendar — SEO-driven traffic surface

## Recent Commerce wins (FY26)

- MarketWatch mobile shop optimisation — 12% improvement in conversion to checkout; increased bundle take rate
- Google Extended Access for Search launched on MarketWatch (Oct 2025)
- MarketWatch ChatGPT auth/entitlements (Dec 2025)
- Earnings Calendar Enhancements — Q4 FY26 initiative to drive organic traffic via SEO
- MarketWatch hard paywall — 15% lift in conversions (historical win)

## Notes

MarketWatch is a significant SEO traffic source. The team is exploring a refreshed MarketWatch app with commerce features as a FY27 investment. The candy bar homepage unit is an in-progress initiative to bring MarketWatch into parity with WSJ and Barron's as a subscription-first homepage experience (WSJ candy bar converts at 7.24% click-through to subscribe).

## FILE:products/marketwatch/products.md
# MarketWatch — Product Inventory

A reference guide to the discrete products and features owned by the MarketWatch product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers MarketWatch-owned consumer experiences.

---

## Core Digital Products

### MarketWatch.com
The primary web destination for MarketWatch, one of the highest-traffic financial news sites in the US.

- Covers real-time market data, financial news, personal finance, economy, and investing
- Historically advertising-led; now subscription-first with a hard paywall driving conversions
- High SEO-driven traffic — organic search is a primary acquisition channel
- Key sections: Markets, Investing, Personal Finance, Economy, Real Estate, Retirement, Crypto
- Piano Composer-powered paywall; CAJ shop pages and checkout for subscription purchase
- Google Extended Access enabled for Search (launched Oct 2025)
- ChatGPT auth/entitlements integration live (Dec 2025)

### MarketWatch Mobile App
The native iOS and Android application for MarketWatch subscribers.

- Real-time market data, news alerts, and portfolio tracking
- Higher mobile usage mix than WSJ or Barron's, reflecting a broader consumer audience
- In-app subscription purchase via Apple IAP and Google Play billing
- New app rebuild under consideration as a FY27 investment to bring Commerce surfaces and improved UX

---

## Markets & Data

### Real-Time Quotes & Market Data
Core market data product — the primary reason many users visit MarketWatch.

- Real-time and delayed quotes for stocks, ETFs, mutual funds, indices, futures, currencies, and crypto
- Company pages with financials, analyst ratings, news, and historical data
- Pre-market and after-hours trading data
- One of the most-trafficked sections of the site; significant SEO value

### Watchlists & Portfolio Tracker
Personal investment tracking tools for registered and subscribed users.

- Create and manage custom watchlists for any asset class
- Portfolio tracker for monitoring holdings, performance, and allocation
- Syncs across web and mobile app

### Earnings Calendar
A structured, data-rich calendar of upcoming and recent corporate earnings releases.

- Shows expected EPS, revenue estimates, and historical results
- Q4 FY26 initiative: enhancements to drive organic search traffic via SEO
- High-intent traffic source for investors; major SEO entry point for the brand

### Economic Calendar
A schedule of key macroeconomic data releases (Fed decisions, jobs reports, CPI, GDP, etc.).

- Covers US and international economic events
- Paired with editorial context and analyst expectations

### Crypto Coverage & Data
Real-time cryptocurrency prices, news, and market data.

- Coverage of Bitcoin, Ethereum, and major altcoins
- Integrated into main market data infrastructure

### Virtual Stock Exchange (VSE)
A free, real-time paper trading simulator — one of the largest of its kind. Users practice investing strategies with virtual money using live market data, with no real capital at risk.

- Live data from NASDAQ, NYSE, and AMEX; supports Market, Limit, and Stop orders
- Default starting balance of $1,000,000 virtual cash; game hosts can configure $10,000 to $25,000,000 starting capital
- Supports US stocks, ETFs, and mutual funds (NASDAQ, NYSE, AMEX); no options, futures, or crypto
- Trade types: Buy, Sell, Short Sell, Buy to Cover; some games implement 15-minute execution delays
- Game/contest mechanics: configurable margin trading, interest rates on cash/margin, volume limits, and simulated transaction fees
- Leaderboards ranked by Total Return or Sharpe Ratio (risk-adjusted performance); private password-protected games for classrooms
- Classroom/education use: teachers can restrict trading to specific sectors or symbols, set semester-aligned start/end dates; widely used in finance and economics curricula globally
- Completely free; no paywall (distinct from MarketWatch Premium subscription for journalism)
- Available on MarketWatch.com and integrated into the MarketWatch mobile app (iOS/Android) with full cross-platform sync
- Recent mobile additions (late 2025/early 2026): Pivot Support/Resistance indicators, Stop Loss Target Calculator, Strength Meter
- Key limitation: dividends are not automatically credited, slightly disadvantaging long-term buy-and-hold strategies in competitions

---

## Newsletters

### Need to Know
MarketWatch's flagship pre-market morning newsletter covering the day's key themes and market setup.

- Sent weekday mornings; high open rate among active investors
- Available to subscribers and registered users

### The Moneyist
Personal finance advice column and newsletter.

- Covers reader-submitted financial dilemmas across inheritance, family finances, and consumer rights
- Engaged, loyal readership; strong social sharing

### Other newsletters
Additional newsletters covering retirement (Retirement Weekly), real estate, and market data digests. Full list managed by the Editorial Newsletters team.

---

## Acquisition Surfaces

### Candy Bar (Homepage Acquisition Unit)
A persistent promotional unit on the MarketWatch homepage designed to drive subscription conversions.

- In-progress initiative to bring MarketWatch into parity with WSJ (which converts at ~7.24% click-through to subscribe)
- Prominent placement above the fold; targeted to non-subscribers and registered free users
- Managed by Commerce team; editorial and product collaboration

### MarketWatch Mobile Shop Optimisation
Ongoing work to improve the subscription purchase funnel on mobile web.

- 12% improvement in conversion to checkout achieved (FY26)
- Increased bundle take rate via optimized offer presentation

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| MarketWatch.com & app | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| MarketWatch app | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Quotes & Market Data | Third-party data providers (Factset and others) |
| Earnings Calendar | SEO infrastructure, HTML Sitemap |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Candy Bar / Acquisition | Piano Composer (targeting), Automated Pricing, CAJ Shop Pages |
| ChatGPT integration | OneID (auth), PIB Entitlements (access) |

## FILE:products/wsj/overview.md
# The Wall Street Journal — Overview

## What it is

The Wall Street Journal is Dow Jones's flagship publication — a daily newspaper and digital platform covering business, finance, politics, and world news. It is one of the most widely read English-language business publications in the US, and one of the largest paid digital news subscribers in the US.

## Audience

- Business professionals, executives, and investors
- Subscribers across consumer (B2C) and enterprise (B2B)
- US-primary with significant international readership

## Business model

Subscription-first. Revenue from:
- Digital subscriptions (direct)
- Print subscriptions
- Advertising
- WSJ+ bundle (multi-brand subscription with Barron's, MarketWatch, IBD)
- Licensing / syndication
- Enterprise / site licensing

## Key Commerce surfaces

- Paywalls — managed via Piano / Composer
- Shop pages — CAJ checkout platform
- Registration flows — Free Expression (free account creation)
- WSJ+ Marketplace — exclusive commerce experience for WSJ+ subscribers
- In-app subscription flows — iOS and Android (Piano Composer-powered)

## Recent Commerce wins (FY26)

- WSJ+ Marketplace launch (Oct 2025)
- Free Expression Phase 1 launch (Dec 2025) — registration wall; 149.6% of Q1 target
- Annual offer default on WSJ app — annual take rate increased from ~25% to ~50%
- In-situ checkout now default — 12% CVR lift for WSJ paywall
- WSJ iOS Onboarding Markets Card (Jan 2026)

## Notes

WSJ is the primary brand for most Commerce product work. Solutions built for WSJ are typically extended to Barron's and MarketWatch.

## FILE:products/wsj/products.md
# WSJ — Product Inventory

A reference guide to the discrete products and features owned by the WSJ product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers WSJ-owned consumer experiences.

---

## Core Digital Products

### WSJ.com
The primary web destination for WSJ editorial content and subscriber experience.

- Covers news, markets, opinion, lifestyle, real estate, and arts coverage
- Authenticated experience for subscribers; metered/paywalled for anonymous users
- Personalization via saved searches, watchlists, topic follows, and reading history
- Supports both desktop and mobile web; responsive design
- Key sections: Markets, Economy, Politics, Tech, Business, Life & Work, Books, Real Estate, Style

### WSJ iOS App
The native iPhone and iPad application for WSJ subscribers.

- Full editorial content access with offline reading
- Breaking news push notifications and personalized news alerts
- Markets data: stock quotes, watchlists, portfolio tracking
- In-app subscription purchase via Apple in-app purchase (IAP)
- Piano Composer-powered paywall for non-subscribers
- Recent additions: Markets onboarding card (Jan 2026), annual offer default (~50% take rate)

### WSJ Android App
The native Android application for WSJ subscribers.

- Feature-parity with iOS app; distributed via Google Play Store
- In-app subscription purchase via Google Play billing
- Push notifications via Braze

---

## Markets & Data

### Markets Data (Quotes & Watchlists)
Real-time and delayed market data tools embedded across WSJ.com and the WSJ apps.

- Stock, ETF, mutual fund, index, and futures quotes
- Personal watchlist creation and management for registered and subscribed users
- Pre-market and after-hours data
- Company pages with financials, news, and analyst data
- Powered by data providers including Factset and others

### WSJ Markets Hub
A dedicated markets section within WSJ.com aggregating market news, data, commentary, and tools in one destination.

- Live market coverage, earnings results, and economic calendar
- Integrates editorial content with live data feeds
- Entry point for users interested in investing and financial markets

---

## Newsletters

### The Morning Briefing (What's News)
WSJ's flagship daily newsletter summarizing the top business and world news stories.

- Sent weekday mornings; high-volume, high-open-rate product
- Available to both registered (free) users and subscribers
- Primary acquisition and engagement channel for email

### WSJ Opinion Today
Daily digest of WSJ Opinion section editorial and commentary.

- Sent weekday mornings to opinion-interested subscribers
- Distinct audience from main news newsletter

### Markets AM / The 10-Point
Markets-focused morning newsletters for finance and investing audiences.

- Covers pre-market moves, key economic data releases, and overnight international news

### Other newsletters
WSJ operates a portfolio of topic-specific newsletters covering areas including real estate, tech (CIO Journal, WSJ Pro), personal finance (Your Money Briefing), and lifestyle. Full list managed by the Editorial Newsletters team.

---

## Audio & Video

### WSJ Podcasts
Audio products distributed via Apple Podcasts, Spotify, and WSJ.com.

- Flagship show: "What's News" (daily news briefing, morning and evening editions)
- Other shows: "The Journal" (flagship long-form), "Opinion: Free Expression", "Heard on the Street", "Tech News Briefing", "Your Money Briefing"
- Subscriber-exclusive episodes exist on some shows; most content is free to grow top-of-funnel audience

### WSJ Live Video & Streaming
Video content available on WSJ.com and apps.

- Live market open and close coverage
- Breaking news live streams
- Video explainers and documentary-style features
- Subscriber-gated for full archive; some clips are free

---

## Personalization & Discovery

### My News
A personalized news feed on WSJ.com and apps based on followed topics, companies, and people.

- Users can follow topics (e.g., Federal Reserve, AI, Apple) to surface relevant articles
- Integrates with editorial curation for a hybrid algorithmic and editorial feed

### Alerts & Notifications
A system allowing subscribers to create custom alerts for breaking news, followed topics, and market movements.

- Available as push notifications (mobile), email alerts, and in-app notifications
- Market alerts: price thresholds, earnings announcements, company news
- Delivered via Braze; preferences managed in account settings

### WSJ Search
Full-text search across all WSJ content, including archive access for subscribers.

- Supports filtering by date, section, author, and content type
- News archive accessible to subscribers; recent headlines visible to non-subscribers
- SEO-significant; organic search is a major traffic driver

---

## WSJ Pro (B2B-adjacent, consumer-facing)

### WSJ Pro Subscriptions
Premium subscription tiers targeting professionals in specific verticals (private equity, venture capital, central banking, cybersecurity, sustainability).

- Separate from WSJ+ consumer subscription
- Includes exclusive newsletters, events access, and in-depth industry coverage
- Sold via direct sales and self-serve; priced at a significant premium to WSJ+
- Managed by the Pro editorial and product team; some Commerce platform overlap for checkout and identity

---

## Games & Lifestyle

### WSJ Crossword & Puzzles
A daily crossword and puzzle experience for WSJ subscribers.

- Available on WSJ.com and in the WSJ app
- Competitive with NYT Games as a subscriber engagement and retention driver
- Introduced as a subscriber benefit to increase non-news engagement

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| WSJ.com & apps | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| WSJ iOS/Android apps | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Markets Data | Factset and third-party data providers |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Alerts | Braze, OneID user preferences |
| WSJ Search / Archive | HTML Sitemap (SEO crawl), Content Access (entitlement checks) |
| Personalization (My News, Watchlists) | OneID (user identity), subscriber entitlement data |

## FILE:teams/org-chart.md
# Org Chart — Consumer Products, Dow Jones

> Last updated: 2026-03-20

## Full Consumer Products org (reports into Ryan Daly)

```
Ryan Daly — SVP, Consumer Products
│
├── Daniel Hockley — VP, Product Management (Commerce)
│   ├── SEO
│   │   └── Craig Casazza — Senior Product Director
│   │       └── Emily Schwartzberg — Senior Product Manager
│   ├── SUBSCRIPTIONS
│   │   ├── Katy Mastorakis — Senior Product Manager (Mobile Apps)
│   │   ├── Joe Stein — Product Manager II (Engagement, Revenue & Retention)
│   │   └── Leigh Hunt — Group Product Manager (Subscriber Acquisition)
│   │       ├── Shani Giersbach — Product Manager (Subscriber Acquisition)
│   │       └── Daniel Saxon — Product Manager II
│   └── IDENTITY
│       └── Adam Guttmann — Senior Product Manager
│
├── Robbie Sauerberg — VP, Product Management (WSJ / Barron's / MarketWatch / Consumer Platform)
│   ├── Nicholas Smolney — Senior Principal Product Manager
│   ├── Sian Barry — Product Manager II
│   ├── Caroline Albanese — Senior Principal Product Manager
│   ├── Lupe Rodarte — Senior Product Director
│   ├── Mikhail Dukhon — Principal Product Manager (Audience & Emerging Ad Platforms)
│   ├── Saurabh Uppal — Senior Product Manager (Mobile Platforms)
│   ├── Yolanda Parker — Senior Product Manager
│   ├── Cristhian Ruiz — CWR (Commercial Technology)
│   ├── Radhika Biradar — CWR (ETL Developer)
│   └── DESIGN (reporting into Robbie)
│       ├── Patrick Estanbouli — Sr Manager, Product Design
│       ├── Kyawt Thiri — Product Designer II
│       ├── Ying Chen — Product Designer I
│       └── Lauren Playford — Product Designer II
│
├── [OPEN HEAD] — VP, Product Management (WSJ) — reports to Ryan; Juan and Shema will report to this role
│   ├── Juan Velasquez — Senior Product Director (Wall Street Journal)
│   │   ├── Linus Li — Senior Product Manager
│   │   ├── Ruth Olumoroti — Product Manager I
│   │   └── John Channell — Senior Product Manager
│   └── Shema Kalisa — Senior Principal Product Manager (Wall Street Journal)
│       └── Noni Ghani — Product Manager I
│
├── Brett Krasnove — Senior Product Director (Wealth & Investing)
│   ├── Brendan Bryant — Senior Product Manager
│   ├── Grant Tunkel — Principal Product Manager
│   └── Kiersten Johnston — Senior Product Manager
│
└── DIRECT ICs (IBD / Consumer — report directly to Ryan)
    ├── Sidney Uttam — Product Manager II (sidney.uttam@investors.com)
    ├── Erin Low — Associate Product Manager (erin.low@investors.com)
    └── Courtney Freeman — Senior Product Manager (courtney.freeman@investors.com)
```

## Commerce leadership triad

| Discipline | People |
| --- | --- |
| Product | Daniel Hockley (VP) |
| Engineering | Ajith Ittan (VP), Ratheesh Nair (VP) |
| Design | Min Chung (VP), Jesús Gorriti (VP) |

## Platform Product org

Separate from the B2C and B2B product orgs. Reports into Yonathan Feldman (SVP, Platform Engineering).

| Org | Product Lead | Sub-teams |
| --- | --- | --- |
| Publishing Systems | Clarissa Matthews | NewsGrid, NewsPress, Editorial Tools, DMI, Print & Newswires |
| Search & Personalization | Puneet Goel (also Interim Head of Platform Product) | Search, Personalization (Signals), Gen AI Experiences |
| Core Experience | Matt Kelley | Market Data, Audio/Video, Messaging |
| Data & AI | (no product lead listed) | Content Services, Data Services, Data Engineering, AI & ML Foundations, Data Analytics |
| APIs & Feeds | Michelle Mischutin | Customer Facing |
| WSJ+ | Clarissa Matthews | — |
| Commercial Technology | Robbie Sauerberg | Ad products, ad infrastructure, privacy platform, information systems — rolls into Consumer Product org |
| DJ Platform (B2B) | Stefan Ritter | Foundational OS for B2B apps — out of scope for B2C repo |

Open role: SVP Product, Platform (JD posted; Puneet Goel covering in interim).

See `teams/platform/team.md` for full detail.

## Key cross-functional partners

| Name | Role | Org |
| --- | --- | --- |
| Greg Ragon | SVP, Performance Marketing | Central Marketing Org |
| Sarah Hilston | VP, Global Acquisition & Paid Media | Central Marketing Org |
| Chris Stanco | VP, Engagement & Retention | Central Marketing Org |
| Belma Kolayli | Marketing Lead, Engagement | Central Marketing Org |
| Joanna Cipolla | Marketing Lead, Retention | Central Marketing Org |
| Sendi Vulaj | Marketing Lead, Revenue | Central Marketing Org |
| Lisa Checketts | Marketing PM | Central Marketing Org |
| Sridhar Maharna | PMO Director | Commerce Operations |
| Mushirah Kelley | Sr. Program Manager | Commerce Operations |
| Srini Kunamneni | Director, Engineering | Subscriptions |
| Thowfeeq Mustafa | Director, Engineering | Subscriptions / Identity |
| Krishna Venkatachalam | Sr Director, Engineering | Identity |
| Rajitha Sivaraman | Sr Director, Engineering | SEO |
| Rommel Rojas | Director, Product Design | Subs / SEO / Identity |
| Puneet Goel | VP Product, Platform | Platform |
| Emily C Williams | Senior Director, B2C Analytics | Data Engineering (reports to Mike Shaw, SVP) |

## FILE:teams/platform/apis-feeds.md
# APIs & Feeds — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026) + APIs & Feeds one-pager

## Overview

APIs & Feeds is the triad focused on building a unified, world-class ecosystem for customer-facing Dow Jones APIs and data feeds. Owns how clients discover, onboard, authenticate, integrate, and get support across Dow Jones' external integration products.

**Triad:** E: Naren Dharma | P: Michelle Mischutin | D: Jesus Gorriti | O: Prakash Shetty

## Responsibilities

- Customer-facing APIs and Feeds strategy: vision, standards, and roadmap for external APIs/feeds across Dow Jones
- Developer and client onboarding experience: end-to-end journey from discovery to access to integration to support
- Developer Portal: redesign and operate the centralized portal as the source of truth for API documentation
- API and feed consolidation strategy: drive consolidation, standardization, and modernization of disparate tech across brands
- Enabling technologies: evaluate and adopt platforms/tools that support a best-in-class ecosystem
- Cross-functional coordination: central point of contact across product triads, core engineering, sales, support, and compliance

## Product portfolio (by cluster)

| Cluster         | Scope                                                     |
| --------------- | --------------------------------------------------------- |
| Cluster 1 (B2B) | Factiva Select, Factiva, Factiva Analytics, Factiva FDK   |
| Cluster 2 (B2B) | Newswires Feeds — Legacy and NextGen                      |
| Cluster 3       | Risk & Compliance legacy feeds and APIs                   |
| Cluster 4 (B2C) | Customer-facing API and feed needs across consumer brands |
| Cluster 5 (B2B) | Newswires APIs (Realtime, Top Stories, Calendar)          |

**Note:** The portfolio is predominantly B2B. Cluster 4 covers B2C consumer brand needs but is not further detailed in available documentation.

## FILE:teams/platform/commercial-tech.md
# Commercial Technology — Platform Team

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026)

## Overview

Commercial Technology is a monetization-focused platform team within the Dow Jones Consumer Product org. It owns the ad products, ad infrastructure, privacy platform, and internal tooling that power advertising across Dow Jones properties (~$300M+ digital advertising business).

Unlike pure platform teams, Commercial Tech rolls into the Consumer Product org (under Robbie Sauerberg) rather than the Platform Product org.

**Triad:** E: Yonathan Feldman | P: Robbie Sauerberg | D: N/A | O: Barbara Shallow

**Product detail:** See `products/commercial-tech/products.md`

## Sub-teams

### Platforms & Privacy
Delivers core ad-serving infrastructure and privacy compliance across Dow Jones properties.

**Triad:** E: Oleg Kodynets (primary), Leo Ma (Mobile App Platforms) | P: Lupe Rodarte (Platforms, Privacy Tech), Kate Downey (Privacy Governance) | O: Barbara Shallow

Covers:
- Ad Platform — core ad-serving and configuration infrastructure
- Privacy Platform (DJCMP) — consent management middleware across stacks and brands
- Newsletters Ad Platform (NAPL) — native ads in newsletters

### Ad Products
Develops marketplace offerings that drive client outcomes via data products (audience targeting, brand safety, data collaboration) and experience products (premium ad formats).

**Triad:** E: Oleg Kodynets | P: Caroline Albanese (Data), Patrick Estanbouli (Experience) | O: Barbara Shallow

Covers:
- SafeSuite — brand safety and suitability tools
- Thematic AI — AI-driven audience and content understanding
- Theme Definer — content and audience classification/taxonomy
- Dynatic — dynamic advertising and experience product
- Ad Formats — proprietary formats for direct-to-subscriber experiences (Hero, Titan, Folio, VStudio, Mosaic, video)

### Information Systems
Empowers Dow Jones advertising functions with data and business automation systems that accelerate operational efficiency and provide insights into client success.

**Triad:** E: Oleg Kodynets | P: Nicholas Smolney | O: Barbara Shallow

Covers:
- InSite — first-party data audience analytics (pre-sale, post-sale, content insights)
- Seawolf — exclusive sponsorship coordination and campaign health monitoring
- Monty — self-serve contract and quote builder for Sales
- DASH — Tableau-based ad data and operations system (under evaluation for deprecation)
- WSJBG Ad Manager (DanAds) — self-serve advertising platform for advertisers and agencies
- Looker — BI and analytics layer; positioned to replace DASH

## FILE:teams/platform/core-experience.md
# Core Experience — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026)

## Overview

Core Experience is the platform group responsible for shared, cross-brand consumer capabilities that make Dow Jones products feel complete and modern. Focused on market data, audio/video, and messaging (newsletters and alerts).

These are horizontal capabilities used across brands (WSJ, Barron's, MarketWatch, IBD, FN, PEN, Mansion Global) and multiple surfaces (web and apps).

**Triad:** E: Chris Tersteeg | P: Matt Kelley | D: Min Chung | O: Matt Chen

## Teams

| Team | PM | Notes |
| --- | --- | --- |
| Market Data | Crystal Koenig | |
| Audio/Video | Lilia Aramayo | |
| Messaging | Marc Torrence | Newsletters and email alerts |

## Products

### Market Data
Shared market data experiences and services powering quotes, charts, watchlists, and market data modules across Dow Jones brands.

Enables:
- Consistent market data content and interactions across brands
- Shared components: Watchlists, Quotes, Market Data Center
- Standard charting and real-time delivery foundations

FY26 initiatives:
- MarketSurge replatforming support via Shared Data Layer (SDL)
- Real-time subscriber services upgrades integrated into SDL
- ChartIQ adoption (moving from HighCharts for consistency)
- Modern watchlist UX and rendering platform modernization (notably for Barron's Investor Circle)

### A/V (Audio and Video)
Platform capability for video and audio discovery, playback, and monetization across apps and web — including shared player strategy and video CMS/workflows.

Enables:
- Cross-brand video discovery and engagement experiences (e.g. media center)
- Improved video ad delivery and format support (pre-roll/mid-roll)
- Player and platform modernization

FY26 initiatives:
- WSJ Redesign: Media Center (Discover / Watch / Listen on iOS and Android)
- Advertising optimizations for video ad experience and delivery
- Video player migration to JWP (assessment and next steps)
- News Corp Video Sharing Program POC (metadata generation/ingestion into video CMS)
- Wealth and Investing video support (Connatix updates, MarketWatch quotes page integration)

### Messaging (Newsletters and Alerts)
Shared systems and tooling powering email newsletters, follow alerts, and live-coverage alerts across brands. Focused on scaling engagement and supporting subscriber value.

Enables:
- Subscriber-only newsletter and alert functionality (entitlement-aware delivery)
- User-choice driven alerts (digest options, clickable templates)
- Live coverage alerts
- Consolidation and migration of newsletters onto standardized platforms (PANDA)

FY26 initiatives:
- Subscriber-only newsletter functionality (supports Barron's Investor Circle and a new Risk newsletter)
- Alerts expansion (digests, source-based alerts, improved templates)
- Live coverage alerts capability (WSJ redesign)
- Written newsletters migration onto PANDA/Curation/Sailthru

## FILE:teams/platform/data-ai.md
# Data & AI — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026) + Data & AI one-pager

## Overview

Data & AI is a Core Foundations organization that owns the end-to-end Snowflake Data & AI ecosystem powering Dow Jones analytics, decisioning, and AI experiences across B2C, B2B, and internal operations.

Designs and operates the platforms, pipelines, and services that:
- Centralize Dow Jones data (content, usage, customer, operational)
- Enforce data governance, quality, and privacy
- Enable AI/ML experimentation and productionization
- Deliver data and content products to internal teams and external customers

**Triad:** E: Mike Shaw | D: Rommel Rojas | O: Greg Blake
**Note:** No org-level product lead listed in triad doc.

## Pods

### 1. Data Architecture & Platform Engineering (DAPE)
Design, build, and manage the foundational data infrastructure and platforms for Dow Jones — enabling scalable, cost-efficient, and secure data operations.

- Owns the enterprise Snowflake platform (all lines of business): account architecture, performance optimization, cost governance, security controls
- Leads the Energy Data Platform delivering data products to Energy customers and integrating with DJ+
- Provides core infrastructure, architectural patterns, and governance frameworks for all structured data activities

Key products: Enterprise Snowflake platform, Energy Data Platform, centralized DBT/Airflow/FastAPI infrastructure, FinOps reporting via FinOut

### 2. Data Governance Engineering (DGE)
Build and implement the technical infrastructure needed to support and enforce data governance policies, data quality, and data management.

- Engineers data quality, metadata, and standardized dictionaries for Snowflake
- Makes Snowflake data trusted, discoverable, and interoperable via data quality controls (Snowflake DMFs), metadata and lineage (Atlan + Snowflake), and data masking/privacy enforcement
- Delivers governance platforms for Energy: Collibra (enterprise data catalog), Semarchy (MDM for standardized dictionaries)

Key products: Governance and quality layer on Snowflake Data Lake, Atlan metadata/lineage platform, Collibra enterprise catalog, Semarchy MDM, data quality framework (Snowflake DMF-based)

### 3. Analytics Engineering
Build and operate the Customer Data Lake in BigQuery and Snowflake, delivering ingestion, transformation, and curated models for enterprise analytics.

- Ingests and models customer and behavioral data across: B2B and B2C Analytics, Ad Tech and Marketing Analytics, Marketing Data Science and Campaign Operations, Newsroom Analytics, W&I, Customer Service, WSJ Opinion, Partnerships
- Delivers curated, analytics-ready datasets powering dashboards, experimentation, and models

Key products: Customer Data Lake (BigQuery + Snowflake), curated subject-area models (marketing, subscriptions, engagement, content performance), shared data marts feeding Looker and data science workflows

### 4. MLOps Engineering
Own the centralized Snowflake ML and AI platform, enabling model deployment, monitoring, and lifecycle management.

- Provides Cortex AI infrastructure and Snowflake-based ML tooling
- Standardizes deployment, monitoring, and lifecycle management for ML models across B2B and B2C analytics, Marketing Analytics, Newsroom Analytics, and Energy
- Ensures ML workloads are observable, governed, and cost-efficient

Key products: Snowflake ML and AI platform (Cortex AI infrastructure), centralized MLOps pipelines, shared feature and model registries (Snowflake-based)

### 5. Data Collections Engineering (DCE)
Collect, measure, and analyze digital content data with accuracy, delivering actionable insights that optimize strategy, engagement, and performance.

- Owns product instrumentation governance: tagging standards, event schemas, event-stream integrity
- Maintains internal analytics pipelines for Marketing GA4, internal publishing systems analytics, Snowplow evaluation
- Supports B2C and B2B with reliable behavioral data

Key products: Analytics instrumentation standards and governance, event streams feeding the Customer Data Lake (web and app telemetry), GA4 and internal analytics implementations for WSJ, Barron's, MarketWatch, and core publishing platforms

### 6. AI & ML Foundations
Provide high-velocity infrastructure that transitions Dow Jones content to agentic intelligence. Enables product teams (Gen AI Experiences, Search + Personalization, DJ Platform) to ship AI features in weeks, not months.

- Builds shared AI infrastructure: model hosting and orchestration, agentic workflow frameworks, real-time evals and guardrails
- Partners with product teams to operationalize GenAI experiences (assistants, summarization, recommendations) and AI-powered decisioning on top of DJ content and data

Key products: Agentic Intelligence platform (shared infra for LLMs and agents), real-time evaluation and monitoring framework, shared AI tools and patterns consumed by product pods

Engineering lead: Maryam Naqvi

### 7. Data Analytics
Provide analytics support across B2B and B2C, surfacing insights and decision support dashboards.

- Partners with business units to define KPIs, build dashboards and reporting for execs, Product, Marketing, and Sales
- Runs deep-dive and ad-hoc analysis using the Customer Data Lake and governed Snowflake assets

Key products: Enterprise dashboards and reports (B2B and B2C), measurement frameworks for subscriptions, engagement, marketing, and B2B product usage

Engineering leads: Denise Fawcitt (B2B), Emily Williams (B2C)

## Who Data & AI supports

**B2C:** WSJ, Barron's, MarketWatch, WSJ+, IBD, Customer Data Platform, audio/video, Market Data

**B2B and platforms:** Factiva, Newswires, Risk and Compliance, DJ+, Energy and CMA, APIs and Feeds, Publishing Systems, DJ Platform, Commercial Tech, Search + Personalization, Enterprise and Core Apps

## FILE:teams/platform/publishing-systems.md
# Publishing Systems — Platform Product

> Last updated: 2026-03-29

## Overview

Publishing Systems provides the core editorial and publishing tools that power Dow Jones consumer newsrooms end-to-end: from story planning, to writing and packaging, to publishing across web, apps, and other channels.

Goal: give editors and reporters a fast, reliable, and unified "OneCMS" experience while retiring legacy tools and fragmentation.

**Product Lead:** Clarissa Matthews

## Teams

NewsGrid, NewsPress, Editorial Tools (covers Curation, Chartlos, Image Manager), DMI, Print & Newswires.

## Products

### NewsGrid
Central planning and orchestration hub for the newsroom.

- Used to plan coverage, track stories and packages, and coordinate across desks
- Acts as the "front door" into the rest of the publishing ecosystem (NewsPress, Curation, etc.)
- Helps editors see what's in the pipeline and manage real-time coverage

### NewsPress
Primary CMS for creating, editing, and publishing articles.

- Used by reporters and editors to write, edit, and manage content for consumer brands
- Supports rich article types, live coverage, and integrations with Chartlos and Image Manager
- Backbone of the OneCMS direction — replacing and consolidating legacy CMS experiences

### Curation
Tool editors use to program and manage surfaces like homepages and section fronts.

- Powers selection and ordering of stories, packages, and modules across key experiences
- Unified interface replacing older, fragmented curation systems
- Enables fast editorial response to news and audience needs

### Chartlos
Core tool for creating and managing charts, graphics, and data-driven visual elements.

- Lets journalists and editors build, update, and embed charts directly into stories
- Integrates into NewsPress so visuals stay in sync with articles
- Supports consistent visual standards and reusability of graphics across brands
- Owned by a standalone engineering team (Atlassian canonical name: ET Chartlos)
- FY27 initiative: Chartlos evolution, including potential HighCharts integration and system refactor

### Image Manager
Central system for finding, managing, and attaching images and other media.

- Searchable library of photos and assets with metadata and rights information
- Integrates with NewsPress and other tools for attaching images to stories and packages
- Supports workflows for sourcing, approval, and reuse of imagery across newsrooms
- Owned by a standalone engineering team (Atlassian canonical name: ET Image Manager)
- FY27 initiative: improve search results using AI, grouping images by article/sked

### DMI
Data/Media Infrastructure — underlying services and tools supporting content, media, and metadata across Publishing Systems.

- Handles storage, retrieval, and enrichment of content and media assets
- Powers integrations between editorial tools and downstream consumers
- Shared foundation that makes the rest of the stack more scalable and consistent

### Print & Newswires
Tools supporting print production and distribution of content via newswires.

- Maintains workflows to get content from digital tools into print layouts and wire products
- Bridges modern tools (NewsPress, NewsGrid) with legacy print and wire systems
- Ensures "create once, publish many" works across digital, print, and wire channels

## How the products fit together

1. **Plan** in NewsGrid: editors plan coverage, assign stories, manage packages
2. **Create** in NewsPress: reporters and editors write and edit stories, using Chartlos for charts and Image Manager for photos
3. **Program** with Curation: editors choose what to feature on homepages, section fronts, and other surfaces
4. **Support and distribute** via DMI (shared content/media infrastructure) and Print & Newswires (print and wire feeds)

Together these products form the OneCMS publishing stack underpinning Dow Jones consumer newsrooms.

## FILE:teams/platform/search-personalization.md
# Search & Personalization — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026)

## Overview

Search & Personalization is the platform org responsible for helping users find, understand, and discover Dow Jones content more effectively. Combines modern search, personalized recommendations, and GenAI experiences.

**Triad:** E: Yulia Zvyagelskaya / Janit Singh | P: Puneet Goel | D: Rommel Rojas / Jesus Gorriti | O: Greg Blake

## Teams

| Team | PM | Notes |
| --- | --- | --- |
| Search | Puneet Goel (Int) | |
| Personalization (Signals) | Puneet Goel (Int) | |
| Gen AI Experiences | Puneet Goel (Int) | Newsbuddy |

## Products

### Search
Shared search platform powering relevant, timely retrieval across core Dow Jones products (B2B and B2C).

Enables:
- Hybrid search (lexical and semantic) to improve relevance and recency
- Modern search UX: summaries, content discovery, advanced search (e.g. boolean)
- "Omni-search" style standardization for DJ+ experiences

FY26 Q1 deliverables:
- New Factiva: hybrid search, improved summaries, advanced search launch
- WSJ: content discovery via links to Author, Company, and Topic pages

### Personalization (Signals)
Platform that captures and uses user signals (implicit and explicit) to deliver personalized feeds, modules, and reranked results across Dow Jones brands.

Enables:
- Shared recommendation endpoints used across brands and surfaces (web and app)
- Personalization for key experiences: MyWSJ, onboarding, preference center, media center, shortlist
- Reusable APIs powering recommendations across products and channels (including newsletter support)

Shared endpoint types:
- **RelatedArticles** — contextual similarity (e.g. "What to Read Next")
- **BundledRecommendedArticles** — ranked, user-tailored bundle (reading history, engagement time, freshness)
- **DiscoverContent** — mixed media discovery (articles, audio, video)
- **Personalized Search** — reranks results using user embeddings and behavior
- **DailyDiscoverUserRecommendations** — newsletter support via Braze

### Gen AI Experiences (Newsbuddy)
AI assistance experiences that help users get to insight faster, grounded in Dow Jones trusted content. Verifiability and source linking are core differentiators.

Enables:
- Customer-validated chatbot/assistant experiences (starting with B2B)
- AI-powered understanding layered into existing workflows: search, summarize, answer, cite

FY26 Q1 deliverable:
- Newsbuddy — validate a standalone chatbot with 3+ B2B customers by EOQ1

## Platform Foundations

Underpins Search and Personalization delivery — not standalone products but tracked in FY26 planning:

- Resiliency and cost savings: MarkLogic migration/upgrade, Pinecone serverless migration
- Metadata ingestion: additional metadata and AIRC for Factiva content to improve quality and enable advanced search

## FILE:teams/platform/team.md
---
name: Platform Product Team
description: Org structure and team leads for Dow Jones Platform Product
type: project
---

# Platform Product Team — Dow Jones

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026)

## Leadership

| Name | Title | Notes |
| --- | --- | --- |
| Yonathan Feldman | SVP, Platform Engineering | Leads Platform org overall |
| Puneet Goel | VP Product, Search & Personalization | Also serving as Interim Head of Platform Product |
| [OPEN] | SVP Product, Platform | JD posted; Puneet covering in interim |

## Orgs and teams

### Publishing Systems
**Triad:** E: John Lynch / Matt Miritello | P: Clarissa Matthews | D: Brian Feeney | O: Marina Guvenc
**Detail:** See `teams/platform/publishing-systems.md`

| Team | Product Lead | Notes |
| --- | --- | --- |
| NewsGrid | Christine Lim | |
| NewsPress | Christine Lim | |
| Editorial Tools | Chelsea Qiao | Curation, images, charts, real-time coverage |
| DMI | Victor Llorente / Claudio Zanotti | |
| Print & Newswires | N/A | |

**Note on team names:** The triad doc shows "Editorial Tools" as the team covering curation and editorial tooling (including Chartlos and Image Manager areas), distinct from NewsGrid and NewsPress. Chartlos and Image Manager are standalone products with their own engineering teams (ET Chartlos, ET Image Manager).

### Search & Personalization
**Triad:** E: Yulia Zvyagelskaya / Janit Singh | P: Puneet Goel | D: Rommel Rojas / Jesus Gorriti | O: Greg Blake
**Detail:** See `teams/platform/search-personalization.md`

| Team | Product Lead | Notes |
| --- | --- | --- |
| Search | Puneet Goel (Int) | |
| Personalization (Signals) | Puneet Goel (Int) | |
| Gen AI Experiences | Puneet Goel (Int) | Newsbuddy |

### Core Experience
**Triad:** E: Chris Tersteeg | P: Matt Kelley | D: Min Chung | O: Matt Chen
**Detail:** See `teams/platform/core-experience.md`

| Team | Product Lead | Notes |
| --- | --- | --- |
| Market Data | Crystal Koenig | |
| Audio/Video | Lilia Aramayo | |
| Messaging | Marc Torrence | Newsletters and email alerts |

### Data & AI
**Triad:** E: Mike Shaw | D: Rommel Rojas | O: Greg Blake
**Note:** No org-level product lead listed in triad doc.
**Detail:** See `teams/platform/data-ai.md`

| Pod | Engineering Lead | Notes |
| --- | --- | --- |
| Data Architecture & Platform Engineering (DAPE) | | Snowflake platform, Energy Data Platform |
| Data Governance Engineering (DGE) | | Data quality, metadata, Atlan, Collibra, Semarchy |
| Analytics Engineering | Tracey Diep | Customer Data Lake (BigQuery + Snowflake), curated models |
| MLOps Engineering | | Snowflake ML platform, Cortex AI, model lifecycle |
| Data Collections Engineering (DCE) | | Instrumentation, event streams, GA4 |
| AI & ML Foundations | Maryam Naqvi | Agentic AI infra, shared LLM/agent platform |
| Data Analytics | Denise Fawcitt (B2B), Emily Williams (B2C) | Dashboards, measurement frameworks |

### APIs & Feeds
**Triad:** E: Naren Dharma | P: Michelle Mischutin | D: Jesus Gorriti | O: Prakash Shetty
**Detail:** See `teams/platform/apis-feeds.md`

| Team | Product Lead | Notes |
| --- | --- | --- |
| Customer Facing | Michelle Mischutin | Next-gen integration platform for customer-facing APIs and feeds |

### Commercial Technology (Advertising & Privacy)
**Triad:** E: Yonathan Feldman | P: Robbie Sauerberg | D: N/A | O: Barbara Shallow
**Note:** Rolls into Consumer Product org (under Robbie Sauerberg), not Platform Product org. Included here as it operates as a platform team.
**Detail:** See `teams/platform/commercial-tech.md` and `products/commercial-tech/products.md`

| Sub-team | Product Lead | Notes |
| --- | --- | --- |
| Platforms & Privacy | Lupe Rodarte (Platforms/Privacy Tech), Kate Downey (Privacy Governance) | Ad Platform, DJCMP, NAPL |
| Ad Products | Caroline Albanese (Data), Patrick Estanbouli (Experience) | SafeSuite, Thematic AI, Theme Definer, Dynatic, Ad Formats |
| Information Systems | Nicholas Smolney | InSite, Seawolf, Monty, DASH, WSJBG Ad Manager, Looker |

### WSJ+
**Triad:** E: Travis Johnson | P: Clarissa Matthews | D: Forest Evashevski | O: Mushirah Kelley
**Note:** WSJ+ is a separate platform triad — not the same as DJ Platform (which is B2B). Clarissa Matthews leads both WSJ+ and Publishing Systems product.
**Detail:** See `teams/platform/wsj-plus.md`

### DJ Platform (B2B)
**Triad:** E: Vishaal Patil | P: Stefan Ritter | D: Jesus Gorriti | O: Greg Blake / Monique Luque
**Note:** DJ Platform is the foundational operating system for Dow Jones B2B applications. Stefan Ritter leads this. Out of scope for B2C repo but included here for cross-reference.

## FILE:teams/platform/wsj-plus.md
# WSJ+ — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026) + WSJ+ internal documentation

## Overview

WSJ+ is Dow Jones' premium consumer brand and subscription tier that combines multiple publications and personalized experiences into a single, unified membership.

Tagline: "The World's Business. Your Business."

Not called "WSJ+ Bundle" in customer-facing copy — just "WSJ+".

**Triad:** E: Travis Johnson | P: Clarissa Matthews | D: Forest Evashevski | O: Mushirah Kelley

## Tiers

| Tier | Included titles |
| --- | --- |
| WSJ+ Preferred (3-product) | WSJ, Barron's, MarketWatch |
| WSJ+ Premier (4-product) | WSJ, Barron's, MarketWatch, Investor's Business Daily |

## Core features

### WSJ+ Dashboard
Centralized, cross-brand dashboard exclusive to WSJ+ members. Aggregates content from all titles with:
- Top News
- Today's Markets
- My Watchlist
- Recommended news by companies and industries followed
- Deep personalization via "Personalize Your Experience"

### WSJ+ News For You
Onsite recommendation module on WSJ.com. Recommends relevant articles with images to WSJ+ subscribers. Lives on the front page under the Opinion section.

### Your Daily Discover
Exclusive multi-title, personalized newsletter surfacing the most relevant stories across the bundle.

### Unified preference and alerts experience
One place to manage alerts, newsletters, and watchlists across all titles (WSJ, Barron's, MarketWatch, IBD).

### Personalized onboarding
On signup: interests, industries, watchlist, alerts, newsletters, and app downloads — sets up the personalized experience from day one.

## WSJ+ Marketplace
Premium marketplace where WSJ+ members can buy add-on products at discounted rates. Examples: Leaderboard, MarketDiem, IBD courses, Barron's premium newsletters.

## Availability and model

- Individual/ecommerce digital subscriptions only — no corporate
- Initially US-only; expanding to select international markets via WSJ+ International
- Former "Investor Bundle" (4-product) and US 3-product bundles have been migrated onto WSJ+ entitlements

## How customers subscribe or upgrade

- Shop page journeys on WSJ.com, Barrons.com, MarketWatch.com: new WSJ+ long-scroll shop page (subset of WSJ traffic) and legacy shop with WSJ+ presented in place of prior bundles
- Customer Center upgrade flow for eligible subscribers
- "Get WSJ+" and "Upgrade to WSJ+" CTAs in nav, onsite modules, and account hub

## Who it's for

- High-value consumer subscribers wanting cross-brand news and investing coverage in a single experience
- Multi-brand loyalists across WSJ, Barron's, MarketWatch, and IBD
- Upsell candidates from WSJ-only or other bundles into a higher-value tier

## Early performance data (FY25)

- 25% of 4-product and 15% of 3-product bundle subscribers engaging with WSJ+ articles
- Strong cross-brand reading behavior observed
- ~300% growth in dashboard page views since launch

## Notes
- There is no separate WSJ+ app — customers download individual apps for WSJ, Barron's, MarketWatch, and IBD
- WSJ+ is the product brand; entitlement and access are managed through the Commerce/Identity stack

## FILE:teams/product/team.md
# Product Team — Commerce, Dow Jones

> Last updated: 2026-03-20

## VP

**Daniel Hockley** — VP of Product, Commerce (Mar 2025–Present)
Previously VP Product, Subscriptions (Sep 2024–Mar 2025)
Reports to: Ryan Daly (SVP, Consumer Product)

## Direct reports — managers

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Craig Casazza | Senior Product Director | SEO | Jul 21, 2025 |
| Leigh Hunt | Group Product Manager | Subscriptions – Subscriber Acquisition | Apr 13, 2020 |

## Direct reports — individual contributors

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Adam Guttmann | Senior Product Manager | Identity & Entitlements | Sep 2, 2025 |
| Katy Mastorakis | Senior Product Manager | Subscriptions – Mobile Apps | Apr 14, 2025 |
| Joe Stein | Product Manager II | Subscriptions – Engagement, Revenue & Retention | Jan 7, 2025 |

## Leigh Hunt's reports

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Shani Giersbach | Product Manager II | Subscriber Acquisition | Feb 2, 2026 |
| Daniel Saxon | Product Manager II | Subscriber Acquisition | Mar 10, 2025 |

## Craig Casazza's reports

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Emily Schwartzberg | Senior Product Manager | SEO | Feb 21, 2022 |

## Areas of ownership

| Area | PM(s) |
| --- | --- |
| SEO | Craig Casazza, Emily Schwartzberg |
| Subscriber Acquisition | Leigh Hunt, Daniel Saxon, Shani Giersbach |
| Subscriber Engagement, Revenue & Retention | Joe Stein |
| Subscriber Mobile | Katy Mastorakis |
| Identity & Entitlements | Adam Guttmann |

## FILE:teams/product/ways-of-working.md
# Ways of Working — Commerce Product Team

How the Dow Jones Commerce product team operates day to day.

## Team structure

Commerce operates as a **platform team** — serving both Consumer (B2C) and B2B sides of the business. Solutions typically need to work across multiple brands and surfaces.

## Leadership triad model

Every pod has a leadership triad with equal representation from Product, Engineering, and Design. The Commerce senior leadership triad:
- **Product:** Daniel Hockley (VP)
- **Engineering:** Ajith Ittan / Ratheesh Nair (VP)
- **Design:** Min Chung / Jesús Gorriti (VP)

## Quarterly planning

Commerce produces quarterly roadmaps aligned to annual OKRs. The planning process:

1. **Backlog review** — Product, Engineering, and stakeholders review existing backlog items and decide what to carry forward
2. **Force rank** — Stakeholders produce a force-ranked list of new and existing priorities
3. **LOE & capacity calculation** — Tech team produces high-level estimates; capacity calculated against available engineering sprints
4. **Roadmap proposal & alignment** — Tech, Marketing, Business, and Newsroom teams align on what is committed vs. backlogged

Each initiative is then:
- Categorised by objective (Acquisition, Retention, Revenue, Engagement, Identity, SEO, Enterprise)
- Assigned to a pod and PM
- Flagged for design dependency
- T-shirt sized (S/M/L) for Engineering and Design independently
- Assigned a deliverable type (Discovery / Design / Development / Backlog)

## Deliverable types

| Type | Meaning |
| --- | --- |
| Discovery | Product-led research; delivers problem statement, vision, solutions, ROI, and requirements |
| Design | Design & research delivers high-res, signed-off designs |
| Development | Engineering delivers code-complete, releasable product or feature |
| Backlog | Deferred — no work committed this quarter |

## T-shirt sizing

| Size | Duration | Sprints |
| --- | --- | --- |
| S | 2 weeks | 1 sprint |
| M | 6 weeks | 3 sprints |
| L | Whole quarter | ~3 months |

## Tracking tool

**Jira Product Discovery (JPD)** — status health tracked via RAG (Red / Amber / Green / On Hold)

## Working with marketing

The Central Marketing Org (CMO) is the primary consumer stakeholder. They are accountable for subscription targets and use Commerce products as one channel in an omni-channel strategy. Commerce and marketing teams are structured around the same customer journey stages: Acquisition, Engagement, Revenue, Retention.

## Key marketing partners

| Name | Role |
| --- | --- |
| Greg Ragon | SVP, Performance Marketing — overall marketing lead |
| Sarah Hilston | VP, Global Acquisition & Paid Media |
| Chris Stanco | VP, Engagement & Retention |

## Product philosophy

- Start with the problem, not the solution — work backwards, define and validate the problem first
- PRDs are thinking tools, not forms — writing forces clarity
- Collaborative by design — PRDs are built with the triad (PM, Design, Engineering), not handed down
- PRDs are living documents — maintained throughout development, not filed away after kickoff
- Shipping is an output, not an outcome — measure what changed in the world (subscriber growth, retention, engagement), not what the team delivered
- Use the double diamond — diverge to discover the problem fully, converge on solutions

## FILE:tech/data-sources.md
# Data Sources

Analytics platforms, data systems, and data tooling used across Dow Jones Commerce.

## Analytics leadership

| Name | Role | Reports to |
| --- | --- | --- |
| Emily C Williams | Senior Director, B2C Analytics | Mike Shaw (SVP, Data Engineering) |

## Key data and analytics teams

| Team | Role |
| --- | --- |
| B2C Analytics | Subscription performance data, experiment analysis |
| Data Science & Analytics | Experimentation analysis and insights; supports A/B test evaluation |
| Marketing Operations | Offer setup, onsite placements, CRM data |
| Data Engineering | Data pipeline dependencies |

## Subscription KPIs tracked

| Metric | Definition |
| --- | --- |
| ARPU | Average Revenue Per User |
| CVR | Conversion rate — % of paywall impressions resulting in subscription start |
| Churn | Rate at which subscribers cancel or lapse |
| Early-life engagement | Avg active days in subscriber's first 7 days |
| Bundle subscriptions | Number of subscriptions in a WSJ+ bundle |
| Bundle revenue | Total revenue from bundle subscriptions |
| Save offer take rate | % of subscribers presented with a save offer who accept it |
| Registered users | New free accounts created per month |
| Crawl coverage | % of priority content successfully crawled by search engines |
| Crawl waste | % of crawl budget spent on non-priority pages |

## Experimentation and testing

- Experiments run via **Optimizely** and **Statsig**
- Results analysis led by Data Science & Analytics team
- Statistical significance required before shipping experiment results

## Notes

Data quality: some FY26 OKR metrics (bundle revenue, bundle subscriptions) are noted as "metric TBC from business" — baseline definitions still being confirmed.

## FILE:tech/messaging.md
# **Project README: Dow Jones Messaging Strategy & PANDA Migration (Updated Jan 2026\)**

## **1\. Executive Summary**

The Dow Jones messaging infrastructure is transitioning from legacy, brand-specific tech stacks toward a centralized, platform-agnostic architecture centered on **PANDA**.

* **Primary Mission**: Migrate all email products from **Campaign Monitor** to **Sailthru** by **December 31, 2027**, to satisfy contract exit requirements.
* **Current Progress**: As of January 2026, the project has established a production-ready foundation for automated and written newsletters, along with automated **Follow alerts**.
* **Migration Status**: Of the 138 products in scope for the year-end deadline, 15% are fully migrated and 15% are configured for production (awaiting onboarding). The remaining 70% require brand-specific template development or new centralized service logic.

## **2\. The Identity Foundation ("The Golden Key")**

* **PANDA**: Serves as the central orchestration engine and is the **future-state source of truth** for user management and subscription data.
* **ENS**: The legacy source of truth for email subscriptions, currently bridged to PANDA via a proxy to maintain data parity.
* **MEGA**: Legacy middleware that synchronizes data between ENS and Campaign Monitor.

## **3\. Organizational Ownership & Boundaries**

### **A. Messaging Team (Internal Domain)**

* **PANDA**: Core orchestration hub for content ingestion, template management, and delivery logic.
* **ENS**: Legacy subscription database.
* **MEGA**: Middleware syncing ENS to Campaign Monitor.

### **B. Partner Systems (Internal Tech Partners)**

* **Publishing Systems**: Owns **NewsPress** (internal CMS for newsletter/article content) and **Curation** (internal tool for manual programming and triggering).
* **Breaking News**: Includes the **WSJ Breaking News Tool** (used by newsroom/Opinion) and **BAT Tool** (MarketWatch), both communicating directly to Airship.
* **Brand Teams**: Vertical tech teams (web/mobile) integrating with ENS and Airship for preference management.
* **NAPL (Native Ads Platform)**: Internal tool for AdOps to program and deliver native ads content.

### **C. External Systems (Vendors)**

* **Sailthru (Zeta)**: Target ESP for all newsletter products.
* **Campaign Monitor (Marigold)**: Legacy ESP to be decommissioned by Dec 31, 2026\.
* **Airship**: Vendor for mobile and web push notifications, managed at the brand level.
* **Braze**: Used by Marketing for lifecycle journeys independently of PANDA.
* **Amazon SES**: Email delivery for B2B brands (Energy and Factiva).
* **Salesforce Marketing Cloud**: ESP for IBD mainstream newsletters (currently outside CM migration scope).
* **Pushly**: Limited implementation on MarketWatch for desktop alerts.

## **4\. The Six Use Cases (Plus One)**

1. **Written Newsletters**: Content is manually written as an article in NewsPress and triggered via Curation; requires high coordination and custom template development.
2. **Automated Newsletters**: Driven by pre-defined content queries (e.g., "Most Read") and delivered on a set schedule without manual assembly.
3. **Automated Alerts ("Follow")**: Real-time alerts for authors or topics; these were the first native PANDA/Sailthru use cases.
4. **Triggered Alerts (Breaking News)**: Manually triggered for urgent news; currently involves a fragmented workflow and manual email assembly.
5. **Transactional**: System-triggered communications (e.g., password resets) currently hard-coded within brand front-ends.
6. **Courses/Journeys**: Automated email series; content and logic will be hosted natively within Sailthru.
7. **Move to Marketing**: Non-editorial products targeted for hand-off to marketing platforms.

## **5\. B2B Messaging Landscape**

* **High-Priority Migration (Campaign Monitor)**: **Newswires** requires development of white-labeling and dynamic data configurations for organization-level metadata.
* **Legacy B2B (Brand-Managed)**: **Energy** (reports via SES) and **Factiva** (alerts via legacy infrastructure managed by legacy members of the Messaging team).
* **PANDA-Native Risk Portfolio**: **Dow Jones Risk Journal**, **Oxford Analytica**, and **Dragonfly** (migration in progress) utilize the centralized PANDA/Sailthru stack.
* **MarketSurge Replatform**: Premium initiative building centralized email and mobile alerts on PANDA, synced with Airship and Sailthru.

## **6\. Takeaways and Opportunities**

* **Identity Silos**: No shared backend currently links mobile push (Airship) and email (ENS/PANDA), preventing a unified preference view.
* **Template Debt**: Technical readiness is still needed for templates for **MG, FN, and PEN**, and specialized variants for **WSJ Opinion and Pro**.
* **New Patterns**: **Transactional** and **Triggered Alerts** remain 100% on legacy systems and require new PANDA logic and centralized tooling for breaking news.
* **Onboarding Dependency**: 21 "Configured in Production" products are stalled pending editorial training and onboarding.
* **Operational Latency**: WSJ editors' manual "double-build" for breaking news results in a 10–20 minute email latency gap.

---

### **Visual Architecture (Mermaid.js)**

Code snippet

```
graph TD
    subgraph Messaging_Domain [Messaging Team Domain]
        PANDA[PANDA Orchestration]
        ENS[ENS Subscription DB]
        MEGA[MEGA Sync Tool]
    end

    subgraph Partners [Partner & Brand Tech]
        NP[NewsPress CMS]
        CUR[Curation Tool]
        BT[Alert Tools: BNT / BAT]
        NAPL[Native Ads Platform]
        BRAND[Brand Web/Mobile Teams]
    end

    subgraph External [Vendors]
        ST[Sailthru - Target]
        CM[Campaign Monitor - Legacy]
        AS[Airship - Push]
        PL[Pushly - Desktop]
        SF[SF Marketing Cloud - IBD]
        SES[Amazon SES - B2B]
        BR[Braze - Marketing]
    end

    NP -->|Article Content| CUR
    CUR -->|Trigger| PANDA
    BT -->|Push Trigger| AS
    NAPL -->|Native Ads| PANDA

    ENS <-->|Proxy| PANDA
    ENS -->|Sync| MEGA
    BRAND -->|Integration| ENS

    PANDA --> ST
    PANDA --> AS
    MEGA --> CM
```

## FILE:tech/stack.md
# Tech Stack

Key platforms, tools, and services used across Dow Jones Commerce.

## Subscription and paywall

| Technology | Used for | Notes |
| --- | --- | --- |
| Piano / Composer | Paywall management, A/B testing, subscription targeting, offer delivery | Primary paywall platform; migrated from Cxense |
| CAJ | Checkout and acquisition journey — the checkout platform | Used across WSJ, Barron's, MarketWatch |
| SubsHub | Subscription management — upsell, save offers, user profile, cancellation flows | |

## Identity and authentication

| Technology | Used for | Notes |
| --- | --- | --- |
| OneID / DJOP | Unified identity platform — single auth layer across all DJ products | All B2C traffic routed through DJOP tenant as of Nov 2025 |
| OAuth2 / OpenID Connect (OIDC) | Token-based access standard — replacing legacy authentication | Target: 100% coverage |

## CRM and engagement

| Technology | Used for | Notes |
| --- | --- | --- |
| Braze | CRM platform — mobile in-app messaging, push notifications, email campaigns, AppsFlyer integration | |
| AppsFlyer | App install attribution — integrated with Braze (Nov 2025) | |

## Experimentation and A/B testing

| Technology | Used for | Notes |
| --- | --- | --- |
| Optimizely | A/B testing | Used for onsite experimentation including "Candybar" promotion units |
| Statsig | Experimentation platform | |

## Project and roadmap management

| Technology | Used for | Notes |
| --- | --- | --- |
| Jira Product Discovery (JPD) | Roadmap tracking, initiative status, RAG health | |
| Confluence | Documentation, team wikis | Katy Mastorakis created Confluence hub for Commerce team |

## SEO infrastructure

| Technology | Used for | Notes |
| --- | --- | --- |
| Olympia | Rendering platform — News Types pages migrated here | |
| XML sitemaps | Crawl and indexing for WSJ, Barron's, MarketWatch | Canonical fix resolved 190k non-self-referencing URLs |

## Analytics

See `tech/data-sources.md` for full detail.

## Notes

- Legal, privacy, and InfoSec reviews are standard dependencies for anything touching identity, billing, or personal data — initiate early, not at launch
- Platform team remit: solutions must typically work across multiple DJ brands and surfaces

## FILE:process/product-development.md
# Product Development Process

How work moves from idea to shipped feature at Dow Jones Consumer Products.

## Document types

### 1-Pager
Used to sell a product idea and get stakeholder alignment. Comes before a PRD.

**Purpose:**
- Gain support for the idea — provide context for the problem being solved, for whom
- Define scope — what does the work entail, and what does it not include
- Set success metrics — what does success look like?

**Audience:** Stakeholders, leadership, team

### PRD (Product Requirements Document)
Expands on the 1-pager with deeper research, analysis, and execution detail. Created after the 1-pager has been socialised and discovery has begun.

**Purpose:**
- Defines the problem and solution for everyone who will work on it
- Defines requirements for MVP and beyond
- Sets expectations for stakeholders
- Reduces scope creep and assumptions

**Audience:** Product triads (PM + Design + Engineering), stakeholders, PMO

See `process/templates/1pager-prd-template.md` — contains both the 1-Pager and PRD templates.

## Stages

### 1. Discovery
- Define and validate the problem before proposing solutions
- Key output: 1-Pager, problem statement, opportunity sizing
- Use the double diamond: diverge to discover the problem fully, converge on solutions

### 2. Definition
- Build the PRD in collaboration with the triad (PM, Design, Engineering)
- PRDs are living documents — maintained throughout development, not filed after kickoff
- Key output: PRD with requirements, success metrics, dependencies

### 3. Design
- Design and Engineering work together from the PRD
- Design reviews involve the triad and relevant stakeholders
- Accessibility is a standard consideration

### 4. Build
- Sprint structure: S (1 sprint / 2 weeks), M (3 sprints / 6 weeks), L (whole quarter)
- Tracking in Jira Product Discovery (JPD) with RAG status
- Deliverable types: Discovery / Design / Development / Backlog

### 5. Launch
- Governed by launch tier — not everything requires the same level of process
- Key dependencies: Legal/Privacy for anything touching identity or billing; InfoSec for data flows
- See `process/go-to-market.md`

### 6. Post-launch
- Success measured against pre-defined metrics — outcome-based, not output-based
- A/B test results reviewed and decisions made to ship, iterate, or kill

## Triad model

Every pod has a core triad: PM + Design + Engineering working together from discovery through delivery.

## Key tools

| Tool | Used for |
| --- | --- |
| Jira Product Discovery (JPD) | Roadmap, initiative tracking, RAG status |
| Confluence | Documentation, team wiki |

## Standard dependencies for identity/billing work

Legal, Privacy, and InfoSec reviews are standard for anything touching identity, authentication, billing, or personal data. These are not launch gates — they should be initiated early in discovery.

## FILE:process/templates/1pager-prd-template.md
# 1-Pager vs PRD

### TL;DR: Use a 1-Pager to sell a product idea and a PRD to build on it.

### **What is a 1-Pager?**

The 1-pager helps you put a stake in the ground. It clarifies what you are trying to do, what is your hypothesis, what are your expectations for success, and what the impact will be. This document will help you sell your idea to stakeholders and leadership, and to initiate Discovery with your triad and team.

**Purpose:**

1. Gain support for your idea \- provide context for the problem you’re solving, for whom
2. Define scope \- what does the work entail, and what does it *not* include
3. Success metrics \- what does success look like? What results do you expect?

**Audience:**

* Stakeholders
* Leadership
* Team

### **What is a PRD?**

A Product Requirements Document (PRD) is a document that helps a product manager develop an idea and communicate it to others involved in the project, so that work can be planned and execution can begin. It should come from the 1-pager and discovery.

**Purpose**

1. Defines the problem and solution for everyone who will work on it
2. Defines requirements \- information that is necessary for MVP and beyond
3. Sets expectations for stakeholders
4. Reduces scope creep
5. Reduces assumptions

**Audience**
A well-written PRD will provide information for various audiences, from triad partners, to start the conversation, to engineering teams, who will build the solution, to stakeholders, who are invested in the learnings or success of the solution. A PRD will become a working document that can be developed and referred back to as a project progresses.

# 1-Pager Template

### The 1-pager helps you put a stake in the ground. It clarifies what you are trying to do, what is your hypothesis, what is expected success, and what the impact will be. This document will help you sell your idea to stakeholders and leadership, and to initiate discovery with your triad and team. At this stage try not to be too prescriptive about what to deliver and leave space for collaborative development.

— \[Delete above this line\]
\[Initiative Title\]

**One-line Summary**
\[Write a TLDR; Capture the product’s objective as concisely as possible. Think of what problem are we solving, why is it important and what impact it might have? Provide clarity and context right from the start to help readers quickly grasp the initiative's purpose.

Example: “A paywall embedded within the video player prompting users to subscribe to continue watching.”\]

#### **Problem**

\[What is the problem, challenge or gap that’s been identified? Who does it affect? Try not to refer to the solution at this stage, just talk about the problem at hand. A problem statement should never just be the need for a specific feature we are hoping to build. Include any data or evidence you have that illustrates the problem.

Example: “We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content.”\]

**Goal(s) / Solution opportunity**
\[What does the solution need to achieve at a high level? If we solve this problem what will we get? What value will this work bring to the company, if it is successful? Conversely, what will DJ *miss out on* by not doing it? How will this give DJ competitive advantage?

Example: “If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on.”\]

#### **Risks and Mitigation**

\[What are known risks, and how do you plan to mitigate them?

Example: “Video views may drop overall, reducing advertising revenue.”\]

**Success Metrics**
\[What does success look like? How will you measure success? How will you validate progress and success?

Example: “Monthly paywall impressions”\]

**Proposed Solution(s)**
\[If you already have an idea or ideas for a solution, describe them here. Be directional but not prescriptive at UI level.

Example: “A paywall embedded in the video player, prompting users to subscribe.” is better than “An overlay on the video player with a button that links users to a shop page.”\]

**Must Haves**
\[List any mandatory requirements here. This doesn’t need to include everything, but should be based on what you know today.

Example: Must work across the website and mobile app.\]

# PRD Template

### The PRD expands on the 1-pager to provide more in-depth research, analysis and execution details. It is mostly created by the Product Manager, who is responsible for clearly defining what and why an initiative is important. How we accomplish the goal should be defined in close collaboration with Design and Engineering.

### Some of the information will come from your 1-pager, and some from discovery. The information you put into the PRD will help define your project so that the team can begin work.

— \[Delete above this line\]
\[Initiative Title\]

**One-line Summary**
\[Write a TLDR; Capture the product’s objective as concisely as possible. Think of what problem are we solving, why is it important and what impact it might have? Provide clarity and context right from the start to help readers quickly grasp the initiative's purpose.

Example: “A paywall embedded within the video player prompting users to subscribe to continue watching.”\]

#### **Problem**

\[What is the problem, challenge or gap that’s been identified? Who does it affect? Try not to refer to the solution at this stage, just talk about the problem at hand. A problem statement should never just be the need for a specific feature we are hoping to build. Include any data or evidence you have that illustrates the problem.

Example: “We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content.”\]

#### **Vision**

\[Make a statement about the impact you expect to make when this work is complete. How does this vision align with the [Dow Jones Mission and Vision](https://intranet.dowjones.com/home/ls/content/5294558629855232/who-we-are#mission)?

Example: “Turn our video content into a high volume subscription driver.”\]

**Goal(s) / Solution opportunity**
\[What does the solution need to achieve at a high level? If we solve this problem, what will we get? What value will this work bring to the company, if it is successful? Conversely, what will DJ *miss out on* by not doing it? How will this give DJ competitive advantage?

Example: “If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on.”\]

**Proposed Solution(s)**
\[If you already have an idea or ideas for a solution, describe them here. Be directional but not prescriptive at UI level.

Example: “A paywall embedded in the video player, prompting users to subscribe.” is better than “An overlay on the video player with a button that links users to a shop page.”\]

#### **Assumptions and Constraints**

\[What are the assumptions you are basing your hypothesis on? What are the technical, business, legal, or other constraints you know of?\]

#### **Audience**

\[Who is the audience or beneficiary for this solution? What do we know about them? Include any audience  you have or define the audience you want to serve. Consider who makes the purchasing decision, as in the customer, versus who will use this, as in the user, and who others might experience the consequences of its use.\]

#### **Success Metrics**

\[How will you measure success? How will you validate progress and success?\]

|  | *Name* | *Definition* | *Current Baseline Performance & Target* |
| :---- | :---- | :---- | :---- |
| **Topline Metric** | Example: Monthly Paywall impressions per pageview | The total number of times a paywall is seen by a user / overall pageviews per month | Baseline: 0.1 Target: 0.3 |
| **Secondary Metric** |  |  |  |
| **Counter Metric** | Example: Monthly video ad impressions | The total number of video ads viewed monthly | Baseline: 1.2M Target: Maintain the baseline. |

#### **Risks and Mitigation**

\[What are known risks, and how do you plan to mitigate them?

Example: “Video views may drop overall, reducing advertising revenue.”\]

#### **Scope & Requirements**

\[What user stories must be fulfilled by the solution? Design and engineering teams will use these to make sure the product achieves everything it needs to to fulfill the user and business needs. Try to focus on user needs without prescribing solutions. Leave enough space for design and engineering teams to explore multiple paths and solutions.\]

\[What is a must have or nice to have for MVP? What is not part of MVP, and can be added after launch? What is the definition of done, and what maintenance and monitoring should follow?\]

| Requirement Title | Description | User Story (optional) | Scope | Notes |
| :---- | :---- | :---- | :---- | :---- |
| Example: Sale pricing | The ability to change pricing that is displayed during sale periods or update pricing to match the current offer. | As a user, I want to see sale pricing within the video player so that I can quickly weigh up my purchasing decision and proceed to purchase. | MVP / Must have / Nice to have | Marketing operations should be able to run sales without the need for engineering involvement.  |
| Example 2: Flexible branding across DJs consumer brands. | … | … | … | … |

#### **Dependencies**

\[Does your solution have any dependencies on other teams or tooling? Are there Design, UX, or Accessibility considerations? Are there legal requirements or reviews that need to be incorporated into your plan? Are there any other teams or projects that are dependent on your solution, which might impact timing of your deliverable?\]

#### **Timing**

\[Is there a hard date by which this needs to be launched, or other timing considerations to be mindful of?\]

#### **RACI (Optional. For large initiatives)**

| Team | Responsible | Accountable | Consulted | Informed |
| :---- | :---- | :---- | :---- | :---- |
| **Product** | List teams and/or individuals |  |  |  |
| **Engineering** |  |  |  |  |
| **Design** |  |  |  |  |
| **Subscription Marketing** |  |  |  |  |
| **PMO** |  |  |  |  |
| **SEO** |  |  |  |  |
| **Data** |  |  |  |  |
| **Privacy/Legal** |  |  |  |  |
| **Customer Service** |  |  |  |  |

##

## **Tasks (Optional)**

\[For cross-functional work, break the project down into top level tasks, listing the major steps required to complete the project, who will own them, any dependencies, and links to relevant resources.\]

| Team | Task | Owner | Notes |
| :---- | :---- | :---- | :---- |
| UXD | Wireframes | Person | Not to reflect final designs. |
| Engineering | Technical discovery | Person | … |
|  |  |  |  |

**Other considerations:**
Legal considerations/requirements
InfoSec considerations/requirements
Design \+ UX Considerations
Accessibility needs
B2C considerations \- [Product Development Checklist](https://docs.google.com/document/d/1TAXM7idFoAb9f7DgIcWnFzm9GB6LTXXqHu5_wO-po6s/edit?tab=t.0)
B2B considerations
Marketing considerations
Prioritization (where does this fit in your roadmap)
User personas
Competitors

## FILE:style/writing.md
# Writing Style — Dow Jones Commerce Product Team

Voice, tone, and conventions for internal product documentation.

## Core principles

- **Concise, direct, actionable** — shorter and clearer beats comprehensive and unread
- **Subheadings are essential** — use them in all substantive writing, even short documents. The best subheadings summarize the point, not just label the topic. A reader should understand the key idea from the heading alone.
- **Write for skim readers** — dense blocks of text lose people. Short paragraphs, clear headings, simple language.
- **Bullet points have limits** — keep lists to under 6 items. Each bullet should be one short sentence. If a bullet is running long, it's probably a paragraph. If a list is running long, break it into themed sections.

## Language

- Always use **American English** spelling: recognize, analyze, color, prioritize, optimize
- No emojis in professional documents
- Avoid internal jargon without explanation — use the glossary (`company/glossary.md`)

## PRD writing principles

- **Start with the problem, not the solution** — stakeholders often arrive with fully formed solutions; work backwards
- **PRDs are thinking tools, not forms** — writing forces clarity; if you struggle to define the problem, the initiative may not be ready
- **Be outcome-based** — success metrics should connect to subscription KPIs (paywall impressions, CVR, subscriber acquisition, churn, ARPU), not just outputs
- **Simple scales** — front-load with the most important information

## Naming conventions

| Preferred | Avoid | Notes |
| --- | --- | --- |
| The Wall Street Journal | WSJ (in external-facing copy) | WSJ is fine internally |
| MarketWatch | Market Watch (one word) | |
| Commerce team | Subscriptions team | Team was renamed to Commerce in Mar 2025 |
| OneID | One ID | Single word |

## Document audiences

| Document type | Primary audience |
| --- | --- |
| 1-Pager | Stakeholders, leadership |
| PRD | Product triad (PM + Design + Engineering), stakeholders, PMO |
| Roadmap | Leadership, marketing stakeholders, cross-functional partners |
| Quarterly planning summary | Tech, Marketing, Business, Newsroom teams |

## Writing for AI tools (this repo)

When writing context files for this repo:
- Be specific and factual — avoid vague generalities
- Use tables for structured information
- Mark placeholders clearly with `[Add]`
- Include "Last updated" dates where content may go stale
- Link to other files rather than duplicating content

## FILE:context-compiled.md
# DJ B2C CONTEXT ENGINE
# Compiled context for Dow Jones B2C product team.
# Use this as system context when generating product docs, PRDs, briefs, or strategy.
# Source of truth: github.com/danielhockley1337/dj-b2c-context
# Files included: 39

## FILE:company/glossary.md
# Dow Jones — Glossary

Terms, abbreviations, and internal jargon used across Dow Jones and the product team.

## Products and brands

| Term | Meaning |
| --- | --- |
| WSJ | The Wall Street Journal |
| MW | MarketWatch |
| IBD | Investor's Business Daily (acquired 2021) |
| BIC | Barron's Investor Circle — premium subscriber community |
| WSJ+ | WSJ bundle subscription product; expands multi-brand access |
| Free Expression | New subscription vertical combining newsletter sign-up and free account creation (launched Dec 2025) |

## Internal platforms and systems

| Term | Meaning |
| --- | --- |
| Piano / Composer | Paywall and subscription management platform; used for targeting, A/B testing, and subscription flows |
| CAJ | Checkout and acquisition journey — the checkout platform |
| SubsHub | Subscription management hub (upsell, save offers, user profile). Also referred to as SubHub in some internal docs — SubsHub is the canonical name. |
| OneID / DJOP | Dow Jones unified identity platform — single authentication layer across all DJ products |
| Braze | CRM platform used for mobile and email marketing, in-app messaging |
| Optimizely | A/B testing and experimentation platform |
| Statsig | Experimentation platform |
| JPD | Jira Product Discovery — roadmap and status tracking tool |
| Mosaic | Internal subscription management platform. Handles mid-term subscription changes including cancel, refund, and repurchase flows. Being extended by the Clean Transitions initiative to support credit-based offer switching without a full cancel-repurchase cycle. |
| BRS | Billing and Revenue System — handles charge groups, payments, credits, refunds, and receipts |
| CSM | Core Subscription Management — manages subscription state, term calculations, pro-rating, and transitions between offers |
| Verint | CRM tool used by Customer Service agents to access and manage customer accounts |
| Watson | Dow Jones offer targeting engine — returns eligible offers for a customer based on configured rules and directives |
| EDW | Enterprise Data Warehouse — central data storage and reporting system for product and business metrics |

## Process and planning

| Term | Meaning |
| --- | --- |
| RAG | Red / Amber / Green — status health system for roadmap items (also includes "On Hold") |
| LOE | Level of effort — engineering or design estimate |
| T-shirt sizing | Effort estimation: S (2 weeks / 1 sprint), M (6 weeks / 3 sprints), L (whole quarter) |
| Triad | The core product delivery unit: PM + Design + Engineering working together |
| CMO | Central Marketing Org — primary consumer stakeholder, accountable for subscription targets |
| DSAR | Data Subject Access Request |
| ROPA | Records of Processing Activities (GDPR Article 30) |
| DPIA | Data Protection Impact Assessment (GDPR Article 35) |
| IFE | In-Flight Entertainment (used in context of Delta partnership) |

## Metrics and data

| Term | Meaning |
| --- | --- |
| ARPU | Average Revenue Per User |
| CVR | Conversion rate |
| Churn | Rate at which subscribers cancel or lapse |
| Paywall impression | A user encounter with a paywall prompt |
| Save offer | A retention offer presented to a subscriber who is attempting to cancel |
| Win-back | Reacquisition offer targeting lapsed/cancelled subscribers |
| Crawl coverage | Percentage of priority content successfully crawled by search engines |
| Crawl waste | Percentage of crawl budget spent on non-priority pages |

## Customer journey stages

| Stage | Owned by |
| --- | --- |
| Traffic & Audience Growth | SEO |
| Registration & Nurture | Subscriber Acquisition |
| Conversion | Subscriber Acquisition |
| Activation | Subscriber Engagement, Revenue & Retention |
| Engagement & Revenue | Subscriber Engagement, Revenue & Retention |
| Retention & Win-back | Subscriber Engagement, Revenue & Retention |

## FILE:company/overview.md
# Dow Jones — Company Overview

## About

Dow Jones is a global provider of news, data, and analytics. It is a subsidiary of News Corp. Dow Jones publishes some of the world's most influential business and financial media across consumer subscription brands including The Wall Street Journal, Barron's, MarketWatch, and Investor's Business Daily.

This context repo covers the B2C (consumer) side of the Dow Jones business. B2B products (Factiva, Risk & Compliance, Newswires, DJ Platform) are out of scope.

As of the March 2026 Investor Briefing, Dow Jones described itself as a "news, data and intelligence powerhouse" — with authoritative editorial positioned as an essential input for the AI era.

## Financial highlights (FY2018–FY2025)

- Revenue base: **82% digital** (up from 60% in FY2018), **80% recurring** (up from 69%)
- **17% compound annual segment EBITDA growth** since FY2018
- Segment EBITDA margin: **25.2%** (nearly doubled since FY2018)
- Dow Jones has driven **11 successive quarters** of year-over-year Total Segment EBITDA growth at News Corp

## $1B EBITDA target

At the March 2026 Investor Briefing, News Corp detailed a pathway to **$1 billion in annual Dow Jones segment EBITDA within five years**, driven by:

- Accelerating Risk & Energy businesses (margin expansion)
- Accelerating direct-to-consumer offerings with new products and pricing
- Sharp focus on high-margin enterprise news
- Continuing cost discipline and operating leverage

## Key consumer brands

- **The Wall Street Journal** — flagship B2C subscription product; one of the largest paid digital news publications in the US
- **Barron's** — financial and investment news
- **MarketWatch** — real-time financial news and market data
- **Investor's Business Daily (IBD)** — acquired 2021
- **WSJ Pro** — premium vertical journalism for professionals
- **WSJ+** — multi-brand bundle subscription (WSJ, Barron's, MarketWatch, IBD)

## Headquarters

New York, NY (primary). Part of News Corp.

## Ownership

Subsidiary of News Corp (NWSA / NWS).

## Leadership

| Name | Title |
| --- | --- |
| Almar Latour | CEO, Dow Jones |
| Artem Fishman | CTO |
| Scott M. Havens | Chief Growth Officer & Global Head of Consumer |
| Emma Tucker | Editor in Chief, WSJ |
| Ryan Daly | SVP, Consumer Product |

## Competitive landscape

Dow Jones competes with FT, Bloomberg, NYT, and specialist financial media for digital subscribers.

## FILE:company/strategy.md
# Dow Jones — Strategy

## Strategic pillars

- **Subscription-first** — Consumer revenue is driven by paid digital subscriptions across WSJ, Barron's, MarketWatch, and IBD
- **Bundle growth** — WSJ+ bundle strategy is a key growth lever, expanding multi-product subscriptions across brands
- **AI as a monetization layer** — Dow Jones positions its authoritative editorial as an essential input for large AI models; licensing and AI product revenue are an expanding opportunity
- **Identity and first-party data** — The authentication and identity layer (OneID) is increasingly strategic, underpinning personalisation, bundling, and first-party data strategy
- **SEO and organic acquisition** — SEO is a primary top-of-funnel channel for WSJ and MarketWatch; positioning DJ properties for discovery via both traditional search and AI platforms

## North Star narrative (from March 2026 Investor Briefing)

Dow Jones frames itself as an **"Input company"** in the Age of AI — drawing an analogy to semiconductors and energy as inputs to the physical world. Authoritative editorial, trusted data, and proprietary risk/compliance intelligence are inputs to the digital and AI world. This framing underpins licensing deals with AI model providers and DJ's broader enterprise strategy.

> "As AI models are rippling from industry to industry, their output is only as good as their input, which is where Dow Jones comes in." — Almar Latour, CEO Dow Jones, March 2026

## Key strategic dynamics

- Platform team remit means solutions need to work across multiple brands and surfaces, not just solve for one
- Legal, privacy, and InfoSec reviews are standard for anything touching identity or billing
- Success metrics connect to subscription KPIs: paywall impressions, conversion rate, subscriber acquisition, churn, ARPU

## Competitive landscape

| Competitor | Where we compete |
| --- | --- |
| Financial Times | Business/financial news subscriptions |
| Bloomberg | Financial data, news, and professional terminals |
| New York Times | Digital news subscriptions, general audience |
| Specialist financial media | Vertical professional publications |

## FILE:goals/FY2026/priorities.md
# FY2026 Priorities — Commerce Product

> FY26 = July 2025 – June 2026
> Last updated: 2026-03-20

## Subscriptions priorities

- **Registration growth** — Grow monthly new free registered users from 20k to 135k
- **Conversion optimisation** — 10–15% incremental conversion lift via A/B testing program
- **Bundle growth** — Grow WSJ+ bundle subscriptions from 1M to 1.15M; deliver $80M bundle revenue
- **Early-life engagement** — Improve avg active days in subscriber's first 7 days (3.9 → 4.3)
- **Retention** — 10–15% lift in save offer take rate
- **New verticals** — Launch commerce surfaces for Free Expression, Connected paywall, Puzzles
- **Delta Partnership** — ~360k subscriptions projected over 3 years

## SEO priorities

- **Traffic ranking** — Move WSJ from #8 to #6 in share of traffic vs. competitors
- **Crawl coverage** — Improve from 55% to 65% (exceeded: hit 74% in Q2)
- **Crawl waste** — Reduce from 30% to 20% (at risk: at 49% in Q2)
- **Programmatic SEO** — Market data pages, topic pages, earnings calendar (MarketWatch)

## Identity priorities

- **OAuth2/OIDC** — Reach 100% token-based access across all products (baseline: 80%)
- **Data hygiene** — Delete ~2.3M inactive accounts (6+ years)

## Cross-team priorities

- In-app Meter — registered users get free articles on app
- Self-serve Corporate Sales shop page ($200k+ Q4 target)

## Notes

Last updated: 2026-03-20

## FILE:goals/FY2026/technology-okrs.md
# Technology FY26 OKRs

> Source: Technology FY26 OKR Tracker
> FY26 = July 2025 – June 2026 | Last updated: 2026-03-20

---

## Grow Subscriptions

### KR: Grow digital subscriptions
**Target:** Q4 average of 6.5M DJ digital subs (WSJ 4.3M)
**Owner:** Dan | **Tech Exec:** Ryan | **ETA:** Q4 | **Status:** TBC

---

### KR: Strengthen paywall strategy — registration growth
**Target:** +10% incremental conversions and 6x monthly registration growth (20k → 120k) by EOFY26
**Owner:** Dan | **Tech Exec:** Ryan | **ETA:** Q4 | **Status:** At Risk

---

### KR: Drive consumer engagement +15% (app weekly subscriber time spent)
**Target:** 1:02:05 → 1:11:24 overall app weekly subscriber time spent by EOH2 (via WSJ Redesign — Media & MyWSJ in H1)
**Owner:** Ryan | **ETA:** H1 | **Status:** Off Track

---

## FILE:goals/company-okrs.md
# Company OKRs — FY26

> FY26 = July 2025 – June 2026
> Last updated: 2026-03-20
> Full Technology OKR tracker: `goals/FY2026/technology-okrs.md`
> Commerce product OKRs: `goals/product-okrs.md`

---

## Top-line subscription targets (FY26)

| Metric | Target |
| --- | --- |
| DJ digital subscriptions | 6.5M (Q4 avg) |
| WSJ digital subscriptions | 4.3M (Q4 avg) |
| Monthly registered users | 120k cumulative |
| App weekly subscriber time spent | 1:11:24 |

---

## Technology OKR summary (FY26)

| OKR | Owner | Status |
| --- | --- | --- |
| Grow digital subs to 6.5M DJ / 4.3M WSJ | Dan / Ryan | TBC |
| Paywall — +10% conversion lift; 20k → 120k monthly registrations | Dan / Ryan | At Risk |
| Consumer engagement +15% app weekly time spent | Ryan | Off Track |

---

## FY27 strategic directions

1. Return to net positive subscriber growth (currently negative net new in volume)
2. Focus on engagement frequency (not time on site) as north star
3. Bolster core digital subscription with new value for new audiences (Games, Sports, Market Data)
4. Boost quality traffic with high subscription propensity (SEO/Audience team)

## Notes

Last updated: 2026-03-20

## FILE:goals/product-okrs.md
# Commerce Product OKRs

> FY26 = July 2025 – June 2026 | FY27 = July 2026 – June 2027
> Last updated: 2026-03-20

## FY26 OKRs — Status as of Q3

### Subscriptions

| OKR | Target |
| --- | --- |
| Grow monthly new free registered users | 20k → 135k |
| Incremental conversion lift from A/B testing | +10–15% |
| Deliver bundle revenue | $80M (from $68M) |
| Grow bundle subscriptions | 1M → 1.15M |
| Improve early-life engagement | 3.9 → 4.3 avg days (first 7) |
| Improve save offer take rate | +10–15% lift |

### SEO

| OKR | Target |
| --- | --- |
| WSJ share of traffic ranking | #6 (from #8) |
| Crawl coverage of priority content | 55% → 65% |
| Reduce crawl waste | 30% → 20% |

### Identity

| OKR | Target |
| --- | --- |
| OAuth2/OIDC token-based access | 100% (baseline: 80%) |
| Reduce inactive accounts (6+ years) | 0 remaining (baseline: 2,337,801) |

---

## FY27 OKRs — Draft

> Status: Draft — targets TBC pending input from Head of Growth and the business
> FY27 runs July 2026 – June 2027

### O1: Return to net subscriber growth
- KR1: Achieve net positive new subscriber volume by end of Q2, sustained through Q4
- KR2: Reduce voluntary churn rate through improved save and cancellation flows
- KR3: Reduce involuntary churn through billing recovery and payment failure intervention
- KR4: Improve paywall-to-checkout conversion rate through checkout improvements and experimentation

### O2: Build engagement habit through feature adoption and onboarding
- KR1: Increase share of new subscribers using core features within their first 30 days
- KR2: Improve 90-day retention rate among subscribers completing onboarding vs. those who don't
- KR3: Increase average experiment-driven lift in feature adoption rate across onboarding and in-app product marketing
- KR4: Increase share of active subscribers with 2+ active days per week (directional)

### O3: Build subscriber funnels for new subscription products
- KR1: Acquire new subscribers via Games and Market Data entry points by Q4
- KR2: Achieve target % of bundle upgrades completed via in-app purchasing by Q4
- KR3: Achieve target % of net new subscribers acquired via non-news entry points by end of FY27
- KR4: Achieve new registrations/subscribers via MarketWatch by Q4

### O4: Grow and convert the registered user base
- KR1: Grow monthly new free registrations to target by Q4
- KR2: Improve registered-to-paid user conversion rate
- KR3: Increase opt-in rate for lifecycle marketing channels among new registrants

### O5: Increase revenue per subscriber (ARPU)
- KR1: Achieve household subscription target by Q4, with price resilience rate higher than single-user plans
- KR2: Drive incremental WSJ+ Marketplace revenue by Q4
- KR3: Increase average revenue per subscriber across WSJ, Barron's, and MarketWatch

### FY27 dependencies (owned outside Subscriptions)
- Notifications/alerts hub — habit driver; owned by app/platform teams
- Newsletters in-app — owned by editorial product
- App performance (reliability, speed, offline mode) — owned by platform/engineering
- Content features (personalization, video, AI summaries) — owned by editorial/newsroom product
- Community features (commenting, Circles, Live QAs) — ownership TBC

## FILE:products/barrons/overview.md
# Barron's — Overview

## What it is

Barron's is a financial and investment news publication focused on market analysis, stock picks, and investment ideas. It has a long print heritage and a growing digital and mobile presence.

## Audience

- Individual investors and wealth managers
- Professionals in financial services
- Sophisticated retail investors

## Business model

Subscription-first, with advertising. Shares commerce infrastructure with WSJ. Part of the WSJ+ bundle.

## Key Commerce surfaces

- Paywalls — Piano / Composer
- Shop pages — CAJ checkout
- Barron's Investor Circle (BIC) — premium subscriber community; integrated with OneID and BigMarker livestream platform
- Barron's Mobile App NextGen — new app with Commerce surfaces (Q4 FY26 initiative)

## FILE:products/barrons/products.md
# Barron's — Product Inventory

A reference guide to the discrete products and features owned by the Barron's product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers Barron's-owned consumer experiences.

---

## Core Digital Products

### Barrons.com
The primary web destination for Barron's editorial content and subscriber experience.

- Covers market analysis, stock picks, investment ideas, fund rankings, and financial commentary
- Authenticated experience for subscribers; metered/paywalled for anonymous users
- Key sections: Stocks, Funds & ETFs, Bonds, Options, Retirement, Personal Finance, Economy
- Piano Composer-powered paywall; CAJ shop pages and checkout for subscription purchase

### Barron's iOS App
The native iPhone and iPad application for Barron's subscribers.

- Full editorial content access with offline reading capability
- Push notifications for market-moving stories and subscriber alerts
- In-app subscription purchase via Apple IAP
- Next-gen app rebuild in progress (Q4 FY26 initiative) to bring Commerce surfaces and improved UX

### Barron's Android App
The native Android application for Barron's subscribers.

- Feature-parity with iOS app; distributed via Google Play Store
- In-app subscription purchase via Google Play billing
- Part of next-gen app rebuild initiative

---

## Markets & Data

### Stock Picks & Ratings
Barron's proprietary stock analysis and ratings, a core differentiator for the brand.

- Long and short recommendations with thesis summaries
- Historical picks performance tracking
- Integrated with editorial content; a primary subscriber value driver

### Barron's Stock Screener
A tool for filtering and discovering stocks based on financial criteria.

- Available to subscribers as part of the investing tools suite
- Filters by sector, valuation, performance, dividend yield, and other metrics

### Market Data (Quotes & Watchlists)
Real-time and delayed market data embedded across Barrons.com and the app.

- Stock, ETF, mutual fund, and index quotes
- Personal watchlist creation and management for registered and subscribed users
- Company pages with financials, news, and analyst coverage

---

## Newsletters

### Barron's Daily
The flagship daily newsletter covering market movers, top stories, and investment ideas.

- Sent weekday mornings to subscribers and registered users
- High-intent financial audience; strong engagement rates

### Barron's Weekly
A weekend digest of the week's top picks, analysis, and market outlook.

- Mirrors the print magazine cadence
- Focuses on longer-form investment ideas and commentary

### Other newsletters
Topic-specific newsletters including income investing, ETF focus, and options coverage. Full list managed by the Editorial Newsletters team.

---

## Community & Events

### Barron's Investor Circle (BIC)
A premium subscription tier from Barron's, positioned as an "inner circle" for serious investors seeking an edge in the markets.

- Exclusive early access to stock picks and deeper research from Barron's analysts before wider publication
- Premium article experience with integrated market data analysis for deeper investment research
- Live and on-demand events with Barron's stock pickers, editors, and analysts, including Q&A access, powered by BigMarker
- Available as a standalone Barron's subscription or bundled with MarketWatch; three pricing tiers offered
- Integrated with OneID for subscriber authentication and entitlement verification
- Differentiator vs. competitors; targets high-intent investors willing to pay a premium for market intelligence

### Barron's Live Events
In-person and virtual conferences and roundtables for institutional and individual investors.

- Flagship event: Barron's Top 100 Financial Advisors Summit
- Additional events covering retirement, markets, and investment themes
- Ticket access often tied to subscription tier or separate purchase

---

## Print

### Barron's Magazine (Print)
The weekly print edition, one of the longest-running financial publications in the US.

- Published weekly; distributed via mail subscription and newsstand
- Print subscribers are managed in Mosaic alongside digital
- Print delivery management available via Subscriber Hub

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| Barrons.com & apps | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| Barron's iOS/Android apps | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Investor Circle (BIC) | OneID (auth), BigMarker (livestream platform) |
| Market Data | Third-party data providers (Factset and others) |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Print subscriptions | Mosaic (subscription management), Subscriber Hub |

## FILE:products/commerce/metrics.md
# Commerce — Metrics

## Primary KPIs

| Metric | Definition | FY26 target |
| --- | --- | --- |
| Monthly new free registered users | New free accounts created per month | 135k (from 20k baseline) |
| Conversion rate lift from A/B testing | Incremental conversion lift across experiments | +10–15% |
| Bundle subscriptions | Number of subscriptions in a bundle | 1.15M (from 1M) |
| Bundle revenue | Total revenue from bundle subscriptions | $80M (from $68M) |
| Early-life engagement | Avg active days in subscriber's first 7 days | 4.3 days (from 3.9) |
| Save offer take rate | Lift in save offer acceptance from A/B testing | +10–15% |

## SEO metrics

| Metric | FY26 target |
| --- | --- |
| WSJ share of traffic ranking vs. competitors | #6 (from #8) |
| Crawl coverage of priority content | 65% (from 55%) |
| Crawl waste | 20% (from 30%) |

## Identity metrics

| Metric | FY26 target |
| --- | --- |
| OAuth2/OIDC token-based access coverage | 100% (baseline: 80%) |
| Inactive accounts deleted (6+ years) | 0 remaining (baseline: 2,337,801) |

## Key subscription metrics (definitions)

### Top line / subscription health

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| New Subscription Orders | Total subscription orders in a period | Total orders over period | Daily / Weekly / Monthly | Must Have |
| New Subscription Starts | Total subscription starts in a period | Total starts over period | Daily / Weekly / Monthly | Must Have |
| Subscription Stops | Subscribers who lose access within a timeframe | Total stops over period | Daily / Weekly / Monthly | Must Have |
| Subscription Cancellations | Subscribers who turn off auto-renew | Total cancellations over period | — | — |
| Net New Starts | Starts minus stops | Total Starts − Total Stops | Daily / Weekly / Monthly | Must Have |
| User Conversion Rate | Conversion rate of all non-subscriber traffic | Total non-sub users / Total Orders | Daily / Weekly / Monthly | Must Have |
| Avg starts per order | Average subscription starts per order | Total Starts / Total Orders | Daily / Weekly / Monthly | Nice to Have |
| Bundle take rate | % of orders including 2+ starts across WSJ+ brands | — | — | — |
| Daily / Weekly active users | Users active on site or app in a given period | — | Weekly / Monthly | Must Have |
| Active days in first 7 days | Days a user had a session of at least X mins within first week of subscribing | # of days with 1+ session in subscribed day + 6 | Weekly / Monthly | Must Have |
| Engagement bracket | Users grouped by active days in last 28 days: Dormant (0), Occasional (1–5), Light (6–10), Mid (11–15), Super (16+) | Group users by 28-day active day count | Weekly / Monthly | — |
| Churn rate | % of subscribers no longer active over a timeframe | Split by web/app, monthly/annual, product, promo/list | — | — |
| Save rate | Rate at which users entering the cancellation funnel accept a save offer | # save offer accepts / # users entering cancellation funnel | Weekly / Monthly | Must Have |
| Net Revenue Retention (NRR) | Holistic measure of MRR change accounting for expansion, contraction, and churn | (Starting MRR + Expansion MRR − Contraction MRR − Churned MRR) ÷ Starting MRR | — | Nice to Have |

### Paywall

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| Total paywall impressions | # of times a paywall is loaded on a page (roadblocks, scrims, snippets, in-situ, dual CTA, live coverage, etc.) | Total paywall loads via Piano | Daily / Weekly / Monthly | Must Have |
| Paywall hit rate | % of pageviews that include a paywall impression | Paywall Impressions / Total non-sub pageviews | Daily / Weekly / Monthly | Must Have |
| Paywall conversion rate | % of paywall impressions resulting in an order | Total Orders / Total Paywall Impressions | Daily / Weekly / Monthly | Must Have |
| Top paywall conversion stories | Top 10 stories driving conversions | Top 10 by conversion count | Yesterday / Last 7 days | Nice to Have |

### Registration

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| Accounts created | Total new user accounts created | Total new accounts | Daily / Weekly / Monthly | Must Have |
| Registration wall impressions | Total impressions of regwall units (dual CTA, registration roadblocks) | Total regwall units delivered by Piano | Daily / Weekly / Monthly | Must Have |
| Registration wall conversion rate | % of regwall impressions resulting in a registration | New accounts via regwalls / Total regwall impressions | Daily / Weekly / Monthly | Must Have |

### Acquisition and conversion

| Metric | Definition | Priority |
| --- | --- | --- |
| Shop page impressions | Views of a subscription shop page | — |
| Shop page → order conversion | Users completing an order from a shop page visit | — |
| Shop page → checkout start | Users beginning checkout from a shop page visit | — |
| Shop page unique visits | Unique visitors to a given shop page | — |
| ARPU | Average Revenue Per User — total revenue / total visitors; used especially for Optimizely experiment analysis | — |
| LTV projections | Projected lifetime revenue per visitor based on sales data and bundle mix | — |
| Cart abandon rate | Users who begin checkout but do not complete an order | — |

### Core product engagement (activation)

| Metric | Definition |
| --- | --- |
| Value exchange metrics | Engagement where user receives value: article reads, listens, watchlist reads, video watches, puzzle plays, newsletter reads |
| Customisation metrics | Engagement where user invests in product: follows, saves, watchlist adds, interest selections, comments, newsletter subscriptions |
| Content breadth | # of sections engaged with (unique sections per user in last 28 days) |
| Content completion rate | % of content completed — articles, listens, videos, podcasts, puzzles, newsletters |
| App/web and cross-device engagement | Combination of surfaces (desktop web, mobile web, tablet web, app) a user engaged with in last 28 days |
| Time to first value | Time from session start to first content engagement |
| Session initiation method | How users start sessions: direct, email, push notification |

### Retention

| Metric | Definition |
| --- | --- |
| 1st renewal churn rate | Users who churn at their first renewal point (split by web/app, monthly, product) |
| Promo-to-list churn rate | Users who churn after stepping up to list price |
| Voluntary vs. involuntary churn | Voluntary: users on auto-renewal who cancel. Involuntary: users not on auto-renewal who lapse. Payment failure target: 50% recovery. |
| Save offer | Retention offer presented to a subscriber attempting to cancel |
| Win-back | Reacquisition offer targeting lapsed/cancelled subscribers |

## Data sources

- B2C Analytics: Emily C Williams (Senior Director, B2C Analytics, reports to Mike Shaw SVP Data Engineering)
- Experimentation analysis: Data Science & Analytics team
- Roadmap status: Jira Product Discovery (JPD) — RAG health

## FILE:products/commerce/overview.md
# Commerce — Overview

## What it is

The Commerce team owns the full subscription lifecycle across Dow Jones consumer products. This includes acquisition, conversion, billing, identity, and retention — across WSJ, Barron's, MarketWatch, IBD, and related brands.

Commerce operates as a **platform team** — solutions typically need to work across multiple brands and surfaces.

## Team lead

**Daniel Hockley** — VP of Product, Commerce (Mar 2025–Present)
Reports to: Ryan Daly (SVP, Consumer Product)

## Teams within Commerce

| Team | Focus | Customer journey stage |
| --- | --- | --- |
| SEO | Organic search visibility and traffic acquisition across WSJ, MarketWatch, Barron's | Traffic & Audience Growth |
| Subscriber Acquisition | Paywalls, shop pages, checkout, registration, offers | Registration & Nurture → Conversion |
| Subscriber Engagement, Revenue & Retention | Onboarding, upsell, save offers, win-back, churn reduction | Activation → Engagement → Retention |
| Subscriber Mobile | Mobile app subscription commerce across iOS and Android | Spans acquisition through retention |
| Identity & Entitlements | Authentication, access control, user identity across all platforms and brands | Infrastructure layer |

## Customer journey framework

```
Traffic & Audience Growth → Registration & Nurture → Conversion → Activation → Engagement & Revenue → Retention & Win-back
        (SEO)                   (Reg, Newsletters)    (Paywall/Checkout)  (Onboarding)    (Upsell, CRM)      (Save offers, Win-back)
```

## Products

The Commerce team owns a portfolio of discrete applications and platforms spanning this journey. See `products.md` for the full inventory with descriptions and dependencies.

Key product areas:
- **Full-funnel infrastructure** — Mosaic (subscription platform), Automated Pricing (ML-driven personalized offers)
- **Acquisition** — Paywall & Onsite Placements, CAJ Shop Pages, CAJ Checkout, Free Registration, Newsletter Sign-up, Partner Landing Sites, WSJ+ Marketplace, Corporate Self-Serve Checkout
- **Engagement & Retention** — CAJ Subscription Onboarding, Subscriber Hub, Braze CRM
- **Identity & Access** — One Identity/OneID (AuthN), PIB Entitlements (AuthZ)
- **SEO** — HTML Sitemap/News Archive (plus XML Sitemap, Robots.txt, Topic Collection Pages)

## Key platforms and tools

- **Piano / Composer** — paywall and subscription management, A/B testing, onsite placement targeting
- **Mosaic** — core backend subscription platform (order processing, billing, fulfillment)
- **CAJ** — customer acquisition journey: checkout, shop pages, onboarding
- **SubHub (Subscriber Hub)** — subscriber self-service account management
- **OneID / DJOP** — unified identity and authentication platform across all DJ products
- **PIB Entitlements** — authorization and access control platform
- **Braze** — CRM, email, in-app messaging, push notifications
- **ActionIQ** — customer data platform (CDP) used for segmentation and targeting
- **Watson** — rules engine for offer targeting and save offers
- **Optimizely / Statsig** — A/B testing and experimentation
- **BRS** — billing and payment processing backend
- **JPD (Jira Product Discovery)** — roadmap and initiative tracking

## Strategic context

- Identity/authentication layer is increasingly strategic — first-party data, personalisation, and bundling all depend on it
- WSJ+ bundle strategy is a key growth lever — expanding multi-product subscriptions
- Legal, privacy, and InfoSec reviews are standard dependencies for anything touching identity or billing
- Platform team remit means solutions typically need to work across multiple brands and surfaces
- Checkout friction is a known gap vs. competitors (NYT, Bloomberg) — reducing drop-off is an ongoing investment
- Registered user base is a key growth area — free registrations act as a nurture layer before paid conversion

## FILE:products/commerce/products.md
# Commerce — Product Inventory

A reference guide to the discrete products and applications owned by the Commerce team. Grouped by area of the customer journey.

---

## Full-Funnel Infrastructure

### Mosaic
The core backend subscription platform underpinning all consumer acquisition, engagement, and retention across Dow Jones brands. Originally launched 2008 on Oracle technology, now fully cloud-based. Consolidates various subscription platforms and adheres to PCI, SOX, and GDPR requirements.

- Handles order processing, billing, entitlement fulfillment, and subscription lifecycle management
- Integrates with BRS (billing), Snowflake data lake, AWS, app stores (Google Play, iOS, Samsung), and payment processors (Apple Pay, PayPal, Amazon)
- Used by: all consumer brands (WSJ, Barron's, MarketWatch, IBD) and enterprise/partner subscribers

### Automated Pricing
A dynamic pricing system that uses machine learning models to deliver personalized subscription price points based on customer attributes, behavior, and market conditions.

- Operates across four journeys: acquisition (new subscribers), renewals (step-up pricing), saves (cancellation deflection), and winbacks (lapsed subscribers)
- ML models built and maintained by Data Science; rules engine (Watson) accepts customer parameters and surfaces appropriate offers
- Integrates with ActionIQ for email and social media delivery to external channels
- Owned jointly with Marketing Operations and Data Science

---

## Acquisition

### Paywall & Onsite Placements
The front-end experience controlling content access for non-subscribers and free registered users across consumer brand websites and apps.

- Built on Piano Composer for ruleset management, targeting, A/B test delivery, and in-built propensity scoring
- Supports multiple formats: roadblocks, scrims, in-situ paywalls, dual CTAs, snippet paywalls, live coverage paywalls
- Also manages registration walls (regwalls) that gate content behind free account creation
- Content Access is the backend system handling entitlement checks, OneID session handshake, article encryption/decryption, Automated Pricing integration, bot whitelisting, and Google Extended Access
- Revenue User Profile persists user profile data and enables segmentation via ActionIQ

### CAJ Shop Pages
Web-based subscription offer pages where users view, compare, and select subscription packages before proceeding to checkout.

- Mobile responsive; supports web-desktop, web-mobile, and in-app webview rendering for next-gen apps
- Shop page templates are built by CAJ engineering; CircOps can configure new pages with `?page=` params for campaign targeting
- Supports personalized offers via Watson (offer targeting), Automated Pricing, and A/B testing
- Serves all DJ brands with brand-specific theming

### CAJ Checkout
The checkout and payment experience for completing subscription purchases across all Dow Jones brands.

- Handles account creation, payment processing, and order confirmation
- Supports credit cards, Apple Pay, and PayPal; responsive across web, mobile web, and in-app webviews
- Brand-specific theming for WSJ, Barron's, MarketWatch, and IBD (IBD has a slightly different account creation flow)
- Key known friction: checkout takes ~3 minutes vs ~1 minute for competitors (NYT, Bloomberg); ongoing work to reduce drop-off

### Free Registration
A lightweight account creation experience for users coming from the paywall who don't yet have an account.

- Allows manual sign-up or social sign-in (Facebook, Google, Apple)
- Creates a registered user entitlement granting limited free article access across DJ brands for a defined period
- Acts as a nurture step before prompting users to subscribe
- In-article placement work ongoing to improve time-to-first-value

### Newsletter Sign-up
A minimal application allowing users to sign up for specific newsletters by submitting their email address.

- Supports both anonymous email entry and single-click sign-up for registered users
- Consistent experience across brands
- Surfacing additional newsletter sign-up opportunities in new areas is an active focus

### Partner Landing Sites (PLS)
A redemption and registration platform for subscribers who acquired access through third-party channels (corporate group sales, app stores, partnerships).

- Two main components: customer-facing redemption/registration flow and a Partner Admin Portal for managing licenses and seats
- Supports WSJ, Barron's, MarketWatch, Financial News London, Private Equity News, and Mansion Global
- Admin Portal enables bulk invitations, redemption tracking, and seat management for corporate partners
- Also serves as the entry point for app store subscribers who need to register a web account

### WSJ+ Marketplace
An exclusive in-subscription commerce hub where WSJ+ subscribers can discover and purchase additional premium Dow Jones products at subscriber-only rates.

- Consolidates supplementary products (newsletters, investing tools, educational resources) into a single place and a single bill
- Currently targets WSJ+ subscribers on every-4-week billing; annual subscriber expansion planned
- Partner content expansion (e.g. The Economist) in discussion
- Removes the fragmented purchasing paths that exist when users discover add-ons across different brand sites

### Corporate Self-Serve Checkout
A self-service purchase funnel for small to medium business customers buying WSJ group subscriptions (10-25 seats) without sales team involvement.

- Includes a corporate-focused marketing landing page and a streamlined checkout with seat selection
- Designed to remove friction in a traditionally long sales process
- Currently WSJ-only; expansion to other brands and products planned
- Integrates with existing corporate subscription management systems

---

## Engagement & Retention

### CAJ Subscription Onboarding
A guided post-purchase onboarding flow that helps new subscribers understand their benefits, set preferences, and take first steps toward engagement.

- Personalizes the experience based on interests, industries, and content preferences
- Prompts key activation actions: app download, newsletter subscriptions, feature education (watchlists, alerts)
- Also used for upgrade flows and CRM-triggered re-onboarding campaigns
- Optimized for Time to Value — getting subscribers to first meaningful content engagement quickly

### Subscriber Hub (SubHub)
A self-service account management platform for existing subscribers to manage subscriptions, billing, and account details across all DJ brands.

- Covers: payment updates, subscription upgrades/downgrades, cancellation, print delivery management, and customer support access
- Presents save offers (pricing alternatives, pauses) to subscribers attempting to cancel
- Aims to reduce calls to customer service by enabling self-service resolution
- Integrates with One Identity, Mosaic, Twilio, Genesys, and Watson

### Braze CRM
The primary marketing automation and messaging platform used to engage subscribers and prospects with personalized communications.

- Supports email, in-app messaging, push notifications, and content cards across web and mobile (iOS, Android)
- Integrates with ActionIQ (CDP) for audience segmentation and AppsFlyer for attribution tracking
- Used across: WSJ, Barron's, MarketWatch web and app platforms
- Migrating from previous solution (Airship) to Braze for mobile messaging

---

## Identity & Access

### One Identity (OneID) — AuthN
The authentication platform that creates, stores, and verifies user identities across all Dow Jones products.

- Assigns unique user identifiers used for cross-product tracking throughout the DJ ecosystem
- Supports persistent login, social sign-in (Facebook, Google, Apple), SAML/SSO, IP whitelisting, and token-based authentication (OAuth2/OpenID Connect)
- Stores PII and manages user sessions across web and mobile platforms
- Serves both B2C (WSJ, Barron's, MarketWatch) and B2B (Factiva, Risk & Compliance, Newswires, etc.) products
- Target: 100% token-based (OAuth2/OIDC) coverage across all products; currently ~85%

### PIB Entitlements (AuthZ)
The authorization platform that determines and enforces what content and features users can access based on their subscription level and organizational permissions.

- Manages entitlements for both consumer subscribers and enterprise/B2B users
- Handles complex subscription models, contractual rules, regional restrictions, and legal compliance controls
- Cross-product integration enables seamless content access across multiple DJ products in a single session
- Target: 100% entitlement coverage across all products; currently ~85% (some complex B2B platforms still migrating)

---

## SEO

### HTML Sitemap (News Archive)
A structured, crawlable directory of all WSJ content designed to maximize search engine crawl efficiency.

- Hierarchical structure (years > months > days > articles) provides access to all content within 5-6 clicks
- Includes orphaned content (videos, live coverage) not accessible from main navigation
- Pagination removed to reduce crawl waste
- Primary consumer is search engine crawlers; secondary use is archived content navigation for readers

> Note: The SEO team also owns XML Sitemap, Robots.txt, and Topic Collection Pages — see the SEO team section for full coverage.

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| All acquisition flows | One Identity (account creation/login) |
| All acquisition flows | Mosaic (order processing) |
| CAJ Checkout | BRS (billing), Mosaic, OneID |
| Paywall / Regwall | Piano Composer, Content Access, OneID |
| Automated Pricing | Watson (rules engine), Data Science ML models |
| Partner Landing Sites | OneID, PIB Entitlements |
| Subscriber Hub | Mosaic, OneID, Watson |
| Braze CRM | ActionIQ (CDP), AppsFlyer |
| WSJ+ Marketplace | CAJ Checkout, Mosaic, OneID |

## FILE:products/commercial-tech/products.md
# Commercial Technology — Product Inventory

A reference guide to the discrete products owned by the Commercial Technology team. Commercial Technology is a monetization-focused team within the Dow Jones B2C org, separate from Commerce. It owns the ad products, ad infrastructure, privacy platform, and internal tooling that power advertising across Dow Jones properties (~$300M+ digital advertising business).

---

## Ad Products

### SafeSuite
A set of brand safety and suitability tools that help advertisers avoid unsafe or misaligned content environments, ensuring campaigns run against trusted, high-quality inventory.

### Thematic AI
An AI-driven audience and content understanding product that identifies themes, topics, and intents in Dow Jones content and user behavior to power more precise targeting and insights.

### Theme Definer
A classification and taxonomy tool that standardizes how content and audiences are grouped into "themes," enabling consistent targeting, reporting, and packaging across products and campaigns.

### Dynatic
A dynamic advertising and experience product that uses data signals and creative rules to tailor ad experiences and placements, improving relevance and performance for advertisers.

### Ad Formats
A suite of proprietary ad formats for direct-to-subscriber experiences. Formats include Hero, Titan, Folio, VStudio, and Mosaic, as well as vertical and horizontal video (VAST/VPAID), native desktop/app placements, and a Dynamic Market Data Tool that integrates live financial data into ad creatives.

- Targets readers and subscribers directly; enables campaign-specific KPIs and custom executions
- Used by MMS Sales; an alternative to internal DJ Design/Consulting for custom advertising

---

## Ad & Privacy Platforms

### Ad Platform
Core ad-serving and configuration infrastructure that standardizes how ads are requested, rendered, and managed across Dow Jones properties. Includes shared components such as the Universal Ad Component and Orchestrator, plus Geneva for centralized ad configuration.

### Privacy Platform (DJCMP)
The Dow Jones Consent Management Platform middleware that sits between third-party CMPs (e.g. Sourcepoint / IAB SDK) and Dow Jones products. Provides a unified API and framework to enforce consent, vendor management, privacy notices, DSARs, and data retention across stacks and brands.

### Newsletters Ad Platform (NAPL)
An advertising platform for native ads in newsletters. Manages newsletter ad inventory, targeting, tracking, and campaign execution across brands — giving Sales and Ad Ops a consistent way to sell, deliver, and report on newsletter ad products.

---

## Information Systems

### InSite
A proprietary first-party data-powered audience analytics suite. Marries data from Adobe (web analytics), Google Ad Manager (ad server), and the Dow Jones CDP to provide audience-based insights not available from any single platform.

- **Pre-sale:** Provides first-party data insights to quantify and support specific product pitches to advertisers
- **Post-sale:** Delivers campaign/line item/creative audience performance metrics for mid-campaign optimisation and end-of-campaign reporting
- **Content Insights:** Leverages audience data from previous campaigns to refine renewal discussions and future pitches
- Used by Planning, AdOps, RevOps, Performance, Sales, and Client Success across MMS

### Seawolf
An internal product that protects the advertising exchange business via stewardship and execution controls. Addresses the gap in the Order Management System for exclusive sponsorship coordination and campaign health monitoring.

- **Buyout Calendar:** Allows the DOCS team to manage bookings with an accurate picture of buyout availability for exclusive sponsorships (e.g. homepage takeovers). Augments the OMS with "holds" to eliminate reliance on email/Slack for cross-team coordination across hundreds of exclusive products
- **Cadence:** Monitors active campaigns against pre-launch requirements and in-flight thresholds; proactively alerts AdOps when intervention is needed rather than discovering issues after the fact
- Key outcome: near-zero makegoods due to double-booking; alerts responded to in a timely manner

### Monty
An in-house tool that allows Sales to independently build contracts and generate real-time quotes for advertising deals without relying on Planning — enabling faster deal closure and more efficient use of people.

- **Monty (Digital):** For digital advertising deals; Sales can create contracts for simpler clients independently
- **Print Monty:** Equivalent tool for print advertising deals
- Metrics tracked: average time to create a deal, percentage of deals using Monty, YoY revenue, average deal size, win rate

### DASH
An internal advertising data and operations system built on Tableau. Aggregates data from multiple source systems (Google Ad Manager, AdBook, IAS, Megaphone, etc.) into a single interface for campaign performance monitoring and end-of-campaign reporting.

- Supports the MMS teams across Planning, AdOps, RevOps, Performance, Sales, and Client Success
- Under evaluation for potential deprecation if Looker meets all MMS use cases

### WSJBG Ad Manager (DanAds)
Previously known as DanAds and WSJ Ad Manager. A self-serve advertising platform powered by the DanAds platform, enabling advertisers and agencies to plan, buy, and manage campaigns directly — without IO processing or managed-service involvement.

- Primary audience: advertisers and agencies (new and existing), particularly SMB advertisers who would be turned away by Direct Sales due to budget size or bandwidth
- Supports credit card and invoicing payment options; real-time campaign management and optimisation
- Secondary audience: MMS Sales team (Client Associates, Associate Client Partners, Client Partners)
- Competes with programmatic platforms (Google, Meta, LinkedIn) for SMB ad budgets

### Looker
The business intelligence and analytics layer for Commercial Technology. Connects to Snowflake and provides curated dashboards and data models for advertising, revenue, and operations across MMS teams.

- Platform partner: Google (Looker Core)
- Primary users: Planning, Performance, AdOps; secondary users: Sales, Client Success, RevOps
- Positioned to replace DASH as the single BI tool for MMS if it meets all use cases
- Supports monitoring and analysis of campaign performance, internal insights, and client-facing reporting

## FILE:products/fnlondon/overview.md
# Financial News London — Overview

## What it is

Financial News (FN) is a premium London-based digital and print publication covering the wholesale financial services industry in the UK and Europe. Effectively the trade paper for the City of London. Founded in 1996 by Angus MacDonald and John Benson; acquired by Dow Jones in 2007 for approximately £79 million. Sits within the Barron's Group division of Dow Jones alongside Barron's, MarketWatch, and Mansion Global.

Note: FN is a separate entity from the original *Financial News* founded in 1884 (which merged with the Financial Times in 1945).

## Audience

- Finance professionals in the City of London and broader European financial services sector
- Over 54% of readers are in senior management (C-suite, MDs, board members)
- Average reader income is high — exceeds the general finance professional population
- Key sectors: investment banking, asset management, private equity, regulation
- UK and Europe-primary; international readers in financial services

## Business model

Subscription-first with hard paywall, reflecting a narrow, high-value professional audience.

- Individual subscriptions at a significant premium vs. consumer publications
- Corporate licenses are the primary revenue driver — over 178 major firms (banks, law firms, consultancies) hold enterprise-wide licenses

## Coverage areas

- Investment banking: deals, M&A, IPOs, capital markets activity
- Asset management: institutional investing trends, fund performance, ESG
- Private equity: operates a specialized daily service, *Private Equity News*, covering European buyouts
- The People section: senior appointments and departures across the City — one of FN's most-read features
- Financial regulation: FCA, EU/ESMA, Basel updates in real time

## Key products and features

- **FN 100**: annual list of the 100 most powerful people in European finance; highly influential as a status signal in the City
- **FN Awards**: prestigious annual ceremonies including Awards for Excellence in Investment Banking
- **Private Equity News**: dedicated daily coverage of European private equity
- **Newsletters**: Morning Briefing and sector-specific updates
- **Events**: high-level roundtables and conferences in London for industry leaders

## Relationship to Dow Jones / WSJ

- Sits within the Barron's Group division of Dow Jones; editorially independent with UK-centric voice
- Shares Commerce infrastructure: OneID (authentication), Mosaic (subscription management), PIB Entitlements
- Partner Landing Sites (PLS) supports FN for corporate/group subscriptions
- Serves as the European counterpart to WSJ Pro — regional depth complementing WSJ's global breadth
- **LSEG Partnership (2024):** Multi-year deal with the London Stock Exchange Group; FN content integrated into LSEG Workspace (Bloomberg-equivalent terminal), significantly expanding reach to terminal users
- Enterprise custom news dashboards combining FN and WSJ content available for corporate clients

## FILE:products/ibd/overview.md
# Investor's Business Daily (IBD) — Overview

## What it is

Investor's Business Daily (IBD) is a financial news and research platform focused on helping individual investors identify leading growth stocks using a disciplined, data-driven system. Founded in 1984 by William O'Neil as *Investor's Daily*; transitioned to digital-first in 2016; acquired by News Corp / Dow Jones in 2021 for $275 million. Operates as a stand-alone brand within the Dow Jones segment alongside WSJ and Barron's.

## Audience

- Self-directed retail investors and momentum/growth traders — primarily US-based
- Investors following a rules-based approach to stock picking
- Financial professionals using IBD data and ratings
- Increasingly targeting novice investors as an entry point into the DJ ecosystem (via MarketDiem newsletter)

## Business model

Subscription-first with a tiered product ecosystem, from free content to premium tools. Dow Jones also offers an "Investor Bundle" combining IBD Digital, WSJ, and Barron's at a combined rate. IBD is considered a high-margin digital pillar within News Corp's broader strategy.

## The CAN SLIM Methodology

IBD's signature stock-picking framework, developed by O'Neil by studying every top-performing stock since the 1880s. Each letter stands for a criterion:

- **C** — Current quarterly earnings (25%+ growth)
- **A** — Annual earnings growth (25%+ over 3-5 years)
- **N** — New product, service, management, or price high
- **S** — Supply and demand (high volume on price breakthroughs)
- **L** — Leader or laggard (buy the top stock in the top industry)
- **I** — Institutional sponsorship (follow the "smart money")
- **M** — Market direction (trade only in a Confirmed Uptrend)

## Key products and features

### IBD Digital (Base subscription)
- Full access to IBD.com editorial content — actionable and educational, not general news
- IBD Stock Lists: IBD 50, Sector Leaders, IPO Leaders, Big Cap 20
- Stock Checkup: free tool; "traffic light" (Green/Yellow/Red) evaluation of any stock's health against CAN SLIM criteria; entry point for non-subscribers
- IBD Ratings (all on 1-99 scale): Composite Rating (combined score), EPS Rating, Relative Strength (RS) Rating, SMR Rating (Sales growth, profit Margins, Return on equity), Accumulation/Distribution Rating
- Industry Group Rank: IBD tracks ~197 industry groups ranked 1-197; CAN SLIM investors focus on top-ranked groups
- Market Trend page / The Big Picture: daily guidance on market direction (Confirmed Uptrend, Uptrend Under Pressure, Market in Correction) — one of IBD's most-read features
- **IBD 50 ETF (ticker: FFTY):** managed by Innovator ETFs, tracks the IBD 50 list; extends IBD's brand into passive investing

### MarketSurge (formerly MarketSmith — rebranded March 2024)
Premium stock research and charting tool. Includes:
- Algorithmic pattern recognition (cup-with-handle, flat base, double bottom, etc.) with automatic buy point identification
- Proprietary "The Ants" indicator: flags intense institutional accumulation before a stock breaks out
- Fundamental data screening, earnings estimates, and historical price/volume analysis

### Leaderboard
A curated, actively managed list of top growth stocks meeting CAN SLIM criteria, with real-time buy/sell annotations from IBD analysts.
- Includes specific entry points, stop losses, and profit targets
- Designed as a "plug-and-play" service for investors who want analyst guidance

### SwingTrader
Shorter-term trade ideas for active traders with holding periods of days to weeks.
- Distinct from Leaderboard's longer-term growth stock focus

### IBD Live
A daily interactive broadcast where IBD analysts screen stocks and analyze charts in real time.
- Available weekday mornings; subscriber add-on

### Newsletters
- The Big Picture: daily market analysis interpreting IBD's Market Trend signals
- IBD 50: weekly list of top-rated growth stocks
- MarketDiem: newer newsletter targeting novice investors with simplified daily trade ideas; onboarding funnel into the IBD ecosystem

## Relationship to Dow Jones

- Acquired by News Corp / Dow Jones in 2021 for $275M; operates as a stand-alone brand with editorial independence
- Shares Commerce infrastructure: OneID (login/identity), PIB Entitlements (access), Mosaic (subscription management)
- CAJ Checkout handles IBD subscription purchases (slightly different account creation flow vs WSJ/Barron's)
- IBD proprietary data increasingly used as "clean" training data for Dow Jones financial AI models
- Bundled with WSJ and Barron's in the Investor Bundle

## FILE:products/mansionglobal/overview.md
# Mansion Global — Overview

## What it is

Mansion Global is a digital-first luxury real estate and lifestyle platform owned by Dow Jones (News Corp). Launched in May 2015, it combines a global luxury property listings database with editorial content covering market analysis, lifestyle, and investment advice. It sits within the Dow Jones Barron's Group alongside Barron's, MarketWatch, and Financial News.

## Audience

- High-net-worth and ultra-affluent individuals buying, selling, or investing in luxury property globally
- 52% of readers are millionaires; average household net worth $2.2M, average household income $433K
- International audience: over 53% of traffic is from outside the US (significant EMEA and APAC reach)
- Real estate agents and brokers in the luxury segment

## Business model

Primarily advertising and listings-revenue led — free to access for consumers. Revenue drivers:

- Real estate broker/developer listing packages (tiered pricing based on volume — small batches to large developer inventories)
- Newsletter sponsorships and market page advertising
- Print supplement sales ("Experience Luxury" magazine, sold through WSJ Shop)

## Coverage areas

- Luxury residential property listings worldwide
- Market analysis: prime markets (London, NYC, Dubai, Hong Kong) and emerging luxury destinations
- Lifestyle and design: architecture, interior design, historic preservation, home technology
- Financial and tax advice for international property buyers
- Multilingual content: English, Spanish, and Chinese

## Key products and features

- **Property search portal**: searchable global luxury listings database with Lifestyle Search (filter by Golf, Historic, Beachfront, etc.)
- **"Experience Luxury" magazine**: quarterly print supplement distributed with The Wall Street Journal
- **Mansion Global TV**: program on Fox Business Network showcasing luxury homes and lifestyle trends
- **Mobile app**: dedicated app for property browsing and real-time market news
- **Newsletters**: daily market updates and listing highlights; newsletter sponsorships are a revenue driver

## Relationship to WSJ and News Corp

- Editorially independent from WSJ but operates as a close partner; produces the "Experience Luxury" WSJ print supplement and shares content with WSJ's Mansion section
- Part of News Corp's Digital Real Estate Services segment — the most profitable News Corp segment as of 2025
- Cross-platform relationships within News Corp: Realtor.com (News Corp owns ~80%, Mansion Global provides luxury top-of-funnel content) and REA Group (News Corp owns ~61%, Australia's leading property site)
- Shares DJ commerce infrastructure: OneID, PIB Entitlements, Mosaic
- Partner Landing Sites (PLS) supports Mansion Global for corporate/group subscriptions

## FILE:products/marketwatch/overview.md
# MarketWatch — Overview

## What it is

MarketWatch is a real-time financial news and market data platform covering markets, personal finance, and economic news. It has a broader, more mass-market audience than WSJ or Barron's, with heavy digital and mobile usage.

## Audience

- Retail investors and personal finance readers
- Broader and more general than WSJ/Barron's
- High traffic, high mobile usage

## Business model

Historically advertising-led; subscription component growing. MarketWatch became a subscription product, and the Commerce team has been building out its subscription surfaces.

## Key Commerce surfaces

- Paywall — Piano / Composer
- Shop pages — CAJ checkout
- Candy bar (promotional unit) — hompage acquisition surface
- Earnings Calendar — SEO-driven traffic surface

## Recent Commerce wins (FY26)

- MarketWatch mobile shop optimisation — 12% improvement in conversion to checkout; increased bundle take rate
- Google Extended Access for Search launched on MarketWatch (Oct 2025)
- MarketWatch ChatGPT auth/entitlements (Dec 2025)
- Earnings Calendar Enhancements — Q4 FY26 initiative to drive organic traffic via SEO
- MarketWatch hard paywall — 15% lift in conversions (historical win)

## Notes

MarketWatch is a significant SEO traffic source. The team is exploring a refreshed MarketWatch app with commerce features as a FY27 investment. The candy bar homepage unit is an in-progress initiative to bring MarketWatch into parity with WSJ and Barron's as a subscription-first homepage experience (WSJ candy bar converts at 7.24% click-through to subscribe).

## FILE:products/marketwatch/products.md
# MarketWatch — Product Inventory

A reference guide to the discrete products and features owned by the MarketWatch product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers MarketWatch-owned consumer experiences.

---

## Core Digital Products

### MarketWatch.com
The primary web destination for MarketWatch, one of the highest-traffic financial news sites in the US.

- Covers real-time market data, financial news, personal finance, economy, and investing
- Historically advertising-led; now subscription-first with a hard paywall driving conversions
- High SEO-driven traffic — organic search is a primary acquisition channel
- Key sections: Markets, Investing, Personal Finance, Economy, Real Estate, Retirement, Crypto
- Piano Composer-powered paywall; CAJ shop pages and checkout for subscription purchase
- Google Extended Access enabled for Search (launched Oct 2025)
- ChatGPT auth/entitlements integration live (Dec 2025)

### MarketWatch Mobile App
The native iOS and Android application for MarketWatch subscribers.

- Real-time market data, news alerts, and portfolio tracking
- Higher mobile usage mix than WSJ or Barron's, reflecting a broader consumer audience
- In-app subscription purchase via Apple IAP and Google Play billing
- New app rebuild under consideration as a FY27 investment to bring Commerce surfaces and improved UX

---

## Markets & Data

### Real-Time Quotes & Market Data
Core market data product — the primary reason many users visit MarketWatch.

- Real-time and delayed quotes for stocks, ETFs, mutual funds, indices, futures, currencies, and crypto
- Company pages with financials, analyst ratings, news, and historical data
- Pre-market and after-hours trading data
- One of the most-trafficked sections of the site; significant SEO value

### Watchlists & Portfolio Tracker
Personal investment tracking tools for registered and subscribed users.

- Create and manage custom watchlists for any asset class
- Portfolio tracker for monitoring holdings, performance, and allocation
- Syncs across web and mobile app

### Earnings Calendar
A structured, data-rich calendar of upcoming and recent corporate earnings releases.

- Shows expected EPS, revenue estimates, and historical results
- Q4 FY26 initiative: enhancements to drive organic search traffic via SEO
- High-intent traffic source for investors; major SEO entry point for the brand

### Economic Calendar
A schedule of key macroeconomic data releases (Fed decisions, jobs reports, CPI, GDP, etc.).

- Covers US and international economic events
- Paired with editorial context and analyst expectations

### Crypto Coverage & Data
Real-time cryptocurrency prices, news, and market data.

- Coverage of Bitcoin, Ethereum, and major altcoins
- Integrated into main market data infrastructure

### Virtual Stock Exchange (VSE)
A free, real-time paper trading simulator — one of the largest of its kind. Users practice investing strategies with virtual money using live market data, with no real capital at risk.

- Live data from NASDAQ, NYSE, and AMEX; supports Market, Limit, and Stop orders
- Default starting balance of $1,000,000 virtual cash; game hosts can configure $10,000 to $25,000,000 starting capital
- Supports US stocks, ETFs, and mutual funds (NASDAQ, NYSE, AMEX); no options, futures, or crypto
- Trade types: Buy, Sell, Short Sell, Buy to Cover; some games implement 15-minute execution delays
- Game/contest mechanics: configurable margin trading, interest rates on cash/margin, volume limits, and simulated transaction fees
- Leaderboards ranked by Total Return or Sharpe Ratio (risk-adjusted performance); private password-protected games for classrooms
- Classroom/education use: teachers can restrict trading to specific sectors or symbols, set semester-aligned start/end dates; widely used in finance and economics curricula globally
- Completely free; no paywall (distinct from MarketWatch Premium subscription for journalism)
- Available on MarketWatch.com and integrated into the MarketWatch mobile app (iOS/Android) with full cross-platform sync
- Recent mobile additions (late 2025/early 2026): Pivot Support/Resistance indicators, Stop Loss Target Calculator, Strength Meter
- Key limitation: dividends are not automatically credited, slightly disadvantaging long-term buy-and-hold strategies in competitions

---

## Newsletters

### Need to Know
MarketWatch's flagship pre-market morning newsletter covering the day's key themes and market setup.

- Sent weekday mornings; high open rate among active investors
- Available to subscribers and registered users

### The Moneyist
Personal finance advice column and newsletter.

- Covers reader-submitted financial dilemmas across inheritance, family finances, and consumer rights
- Engaged, loyal readership; strong social sharing

### Other newsletters
Additional newsletters covering retirement (Retirement Weekly), real estate, and market data digests. Full list managed by the Editorial Newsletters team.

---

## Acquisition Surfaces

### Candy Bar (Homepage Acquisition Unit)
A persistent promotional unit on the MarketWatch homepage designed to drive subscription conversions.

- In-progress initiative to bring MarketWatch into parity with WSJ (which converts at ~7.24% click-through to subscribe)
- Prominent placement above the fold; targeted to non-subscribers and registered free users
- Managed by Commerce team; editorial and product collaboration

### MarketWatch Mobile Shop Optimisation
Ongoing work to improve the subscription purchase funnel on mobile web.

- 12% improvement in conversion to checkout achieved (FY26)
- Increased bundle take rate via optimized offer presentation

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| MarketWatch.com & app | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| MarketWatch app | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Quotes & Market Data | Third-party data providers (Factset and others) |
| Earnings Calendar | SEO infrastructure, HTML Sitemap |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Candy Bar / Acquisition | Piano Composer (targeting), Automated Pricing, CAJ Shop Pages |
| ChatGPT integration | OneID (auth), PIB Entitlements (access) |

## FILE:products/wsj/overview.md
# The Wall Street Journal — Overview

## What it is

The Wall Street Journal is Dow Jones's flagship publication — a daily newspaper and digital platform covering business, finance, politics, and world news. It is one of the most widely read English-language business publications in the US, and one of the largest paid digital news subscribers in the US.

## Audience

- Business professionals, executives, and investors
- Subscribers across consumer (B2C) and enterprise (B2B)
- US-primary with significant international readership

## Business model

Subscription-first. Revenue from:
- Digital subscriptions (direct)
- Print subscriptions
- Advertising
- WSJ+ bundle (multi-brand subscription with Barron's, MarketWatch, IBD)
- Licensing / syndication
- Enterprise / site licensing

## Key Commerce surfaces

- Paywalls — managed via Piano / Composer
- Shop pages — CAJ checkout platform
- Registration flows — Free Expression (free account creation)
- WSJ+ Marketplace — exclusive commerce experience for WSJ+ subscribers
- In-app subscription flows — iOS and Android (Piano Composer-powered)

## Recent Commerce wins (FY26)

- WSJ+ Marketplace launch (Oct 2025)
- Free Expression Phase 1 launch (Dec 2025) — registration wall; 149.6% of Q1 target
- Annual offer default on WSJ app — annual take rate increased from ~25% to ~50%
- In-situ checkout now default — 12% CVR lift for WSJ paywall
- WSJ iOS Onboarding Markets Card (Jan 2026)

## Notes

WSJ is the primary brand for most Commerce product work. Solutions built for WSJ are typically extended to Barron's and MarketWatch.

## FILE:products/wsj/products.md
# WSJ — Product Inventory

A reference guide to the discrete products and features owned by the WSJ product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers WSJ-owned consumer experiences.

---

## Core Digital Products

### WSJ.com
The primary web destination for WSJ editorial content and subscriber experience.

- Covers news, markets, opinion, lifestyle, real estate, and arts coverage
- Authenticated experience for subscribers; metered/paywalled for anonymous users
- Personalization via saved searches, watchlists, topic follows, and reading history
- Supports both desktop and mobile web; responsive design
- Key sections: Markets, Economy, Politics, Tech, Business, Life & Work, Books, Real Estate, Style

### WSJ iOS App
The native iPhone and iPad application for WSJ subscribers.

- Full editorial content access with offline reading
- Breaking news push notifications and personalized news alerts
- Markets data: stock quotes, watchlists, portfolio tracking
- In-app subscription purchase via Apple in-app purchase (IAP)
- Piano Composer-powered paywall for non-subscribers
- Recent additions: Markets onboarding card (Jan 2026), annual offer default (~50% take rate)

### WSJ Android App
The native Android application for WSJ subscribers.

- Feature-parity with iOS app; distributed via Google Play Store
- In-app subscription purchase via Google Play billing
- Push notifications via Braze

---

## Markets & Data

### Markets Data (Quotes & Watchlists)
Real-time and delayed market data tools embedded across WSJ.com and the WSJ apps.

- Stock, ETF, mutual fund, index, and futures quotes
- Personal watchlist creation and management for registered and subscribed users
- Pre-market and after-hours data
- Company pages with financials, news, and analyst data
- Powered by data providers including Factset and others

### WSJ Markets Hub
A dedicated markets section within WSJ.com aggregating market news, data, commentary, and tools in one destination.

- Live market coverage, earnings results, and economic calendar
- Integrates editorial content with live data feeds
- Entry point for users interested in investing and financial markets

---

## Newsletters

### The Morning Briefing (What's News)
WSJ's flagship daily newsletter summarizing the top business and world news stories.

- Sent weekday mornings; high-volume, high-open-rate product
- Available to both registered (free) users and subscribers
- Primary acquisition and engagement channel for email

### WSJ Opinion Today
Daily digest of WSJ Opinion section editorial and commentary.

- Sent weekday mornings to opinion-interested subscribers
- Distinct audience from main news newsletter

### Markets AM / The 10-Point
Markets-focused morning newsletters for finance and investing audiences.

- Covers pre-market moves, key economic data releases, and overnight international news

### Other newsletters
WSJ operates a portfolio of topic-specific newsletters covering areas including real estate, tech (CIO Journal, WSJ Pro), personal finance (Your Money Briefing), and lifestyle. Full list managed by the Editorial Newsletters team.

---

## Audio & Video

### WSJ Podcasts
Audio products distributed via Apple Podcasts, Spotify, and WSJ.com.

- Flagship show: "What's News" (daily news briefing, morning and evening editions)
- Other shows: "The Journal" (flagship long-form), "Opinion: Free Expression", "Heard on the Street", "Tech News Briefing", "Your Money Briefing"
- Subscriber-exclusive episodes exist on some shows; most content is free to grow top-of-funnel audience

### WSJ Live Video & Streaming
Video content available on WSJ.com and apps.

- Live market open and close coverage
- Breaking news live streams
- Video explainers and documentary-style features
- Subscriber-gated for full archive; some clips are free

---

## Personalization & Discovery

### My News
A personalized news feed on WSJ.com and apps based on followed topics, companies, and people.

- Users can follow topics (e.g., Federal Reserve, AI, Apple) to surface relevant articles
- Integrates with editorial curation for a hybrid algorithmic and editorial feed

### Alerts & Notifications
A system allowing subscribers to create custom alerts for breaking news, followed topics, and market movements.

- Available as push notifications (mobile), email alerts, and in-app notifications
- Market alerts: price thresholds, earnings announcements, company news
- Delivered via Braze; preferences managed in account settings

### WSJ Search
Full-text search across all WSJ content, including archive access for subscribers.

- Supports filtering by date, section, author, and content type
- News archive accessible to subscribers; recent headlines visible to non-subscribers
- SEO-significant; organic search is a major traffic driver

---

## WSJ Pro (B2B-adjacent, consumer-facing)

### WSJ Pro Subscriptions
Premium subscription tiers targeting professionals in specific verticals (private equity, venture capital, central banking, cybersecurity, sustainability).

- Separate from WSJ+ consumer subscription
- Includes exclusive newsletters, events access, and in-depth industry coverage
- Sold via direct sales and self-serve; priced at a significant premium to WSJ+
- Managed by the Pro editorial and product team; some Commerce platform overlap for checkout and identity

---

## Games & Lifestyle

### WSJ Crossword & Puzzles
A daily crossword and puzzle experience for WSJ subscribers.

- Available on WSJ.com and in the WSJ app
- Competitive with NYT Games as a subscriber engagement and retention driver
- Introduced as a subscriber benefit to increase non-news engagement

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| WSJ.com & apps | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| WSJ iOS/Android apps | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Markets Data | Factset and third-party data providers |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Alerts | Braze, OneID user preferences |
| WSJ Search / Archive | HTML Sitemap (SEO crawl), Content Access (entitlement checks) |
| Personalization (My News, Watchlists) | OneID (user identity), subscriber entitlement data |

## FILE:teams/org-chart.md
# Org Chart — Consumer Products, Dow Jones

> Last updated: 2026-03-20

## Full Consumer Products org (reports into Ryan Daly)

```
Ryan Daly — SVP, Consumer Products
│
├── Daniel Hockley — VP, Product Management (Commerce)
│   ├── SEO
│   │   └── Craig Casazza — Senior Product Director
│   │       └── Emily Schwartzberg — Senior Product Manager
│   ├── SUBSCRIPTIONS
│   │   ├── Katy Mastorakis — Senior Product Manager (Mobile Apps)
│   │   ├── Joe Stein — Product Manager II (Engagement, Revenue & Retention)
│   │   └── Leigh Hunt — Group Product Manager (Subscriber Acquisition)
│   │       ├── Shani Giersbach — Product Manager (Subscriber Acquisition)
│   │       └── Daniel Saxon — Product Manager II
│   └── IDENTITY
│       └── Adam Guttmann — Senior Product Manager
│
├── Robbie Sauerberg — VP, Product Management (WSJ / Barron's / MarketWatch / Consumer Platform)
│   ├── Nicholas Smolney — Senior Principal Product Manager
│   ├── Sian Barry — Product Manager II
│   ├── Caroline Albanese — Senior Principal Product Manager
│   ├── Lupe Rodarte — Senior Product Director
│   ├── Mikhail Dukhon — Principal Product Manager (Audience & Emerging Ad Platforms)
│   ├── Saurabh Uppal — Senior Product Manager (Mobile Platforms)
│   ├── Yolanda Parker — Senior Product Manager
│   ├── Cristhian Ruiz — CWR (Commercial Technology)
│   ├── Radhika Biradar — CWR (ETL Developer)
│   └── DESIGN (reporting into Robbie)
│       ├── Patrick Estanbouli — Sr Manager, Product Design
│       ├── Kyawt Thiri — Product Designer II
│       ├── Ying Chen — Product Designer I
│       └── Lauren Playford — Product Designer II
│
├── [OPEN HEAD] — VP, Product Management (WSJ) — reports to Ryan; Juan and Shema will report to this role
│   ├── Juan Velasquez — Senior Product Director (Wall Street Journal)
│   │   ├── Linus Li — Senior Product Manager
│   │   ├── Ruth Olumoroti — Product Manager I
│   │   └── John Channell — Senior Product Manager
│   └── Shema Kalisa — Senior Principal Product Manager (Wall Street Journal)
│       └── Noni Ghani — Product Manager I
│
├── Brett Krasnove — Senior Product Director (Wealth & Investing)
│   ├── Brendan Bryant — Senior Product Manager
│   ├── Grant Tunkel — Principal Product Manager
│   └── Kiersten Johnston — Senior Product Manager
│
└── DIRECT ICs (IBD / Consumer — report directly to Ryan)
    ├── Sidney Uttam — Product Manager II (sidney.uttam@investors.com)
    ├── Erin Low — Associate Product Manager (erin.low@investors.com)
    └── Courtney Freeman — Senior Product Manager (courtney.freeman@investors.com)
```

## Commerce leadership triad

| Discipline | People |
| --- | --- |
| Product | Daniel Hockley (VP) |
| Engineering | Ajith Ittan (VP), Ratheesh Nair (VP) |
| Design | Min Chung (VP), Jesús Gorriti (VP) |

## Platform Product org

Separate from the B2C and B2B product orgs. Reports into Yonathan Feldman (SVP, Platform Engineering).

| Org | Product Lead | Sub-teams |
| --- | --- | --- |
| Publishing Systems | Clarissa Matthews | NewsGrid, NewsPress, Editorial Tools, DMI, Print & Newswires |
| Search & Personalization | Puneet Goel (also Interim Head of Platform Product) | Search, Personalization (Signals), Gen AI Experiences |
| Core Experience | Matt Kelley | Market Data, Audio/Video, Messaging |
| Data & AI | (no product lead listed) | Content Services, Data Services, Data Engineering, AI & ML Foundations, Data Analytics |
| APIs & Feeds | Michelle Mischutin | Customer Facing |
| WSJ+ | Clarissa Matthews | — |
| Commercial Technology | Robbie Sauerberg | Ad products, ad infrastructure, privacy platform, information systems — rolls into Consumer Product org |
| DJ Platform (B2B) | Stefan Ritter | Foundational OS for B2B apps — out of scope for B2C repo |

Open role: SVP Product, Platform (JD posted; Puneet Goel covering in interim).

See `teams/platform/team.md` for full detail.

## Key cross-functional partners

| Name | Role | Org |
| --- | --- | --- |
| Greg Ragon | SVP, Performance Marketing | Central Marketing Org |
| Sarah Hilston | VP, Global Acquisition & Paid Media | Central Marketing Org |
| Chris Stanco | VP, Engagement & Retention | Central Marketing Org |
| Belma Kolayli | Marketing Lead, Engagement | Central Marketing Org |
| Joanna Cipolla | Marketing Lead, Retention | Central Marketing Org |
| Sendi Vulaj | Marketing Lead, Revenue | Central Marketing Org |
| Lisa Checketts | Marketing PM | Central Marketing Org |
| Sridhar Maharna | PMO Director | Commerce Operations |
| Mushirah Kelley | Sr. Program Manager | Commerce Operations |
| Srini Kunamneni | Director, Engineering | Subscriptions |
| Thowfeeq Mustafa | Director, Engineering | Subscriptions / Identity |
| Krishna Venkatachalam | Sr Director, Engineering | Identity |
| Rajitha Sivaraman | Sr Director, Engineering | SEO |
| Rommel Rojas | Director, Product Design | Subs / SEO / Identity |
| Puneet Goel | VP Product, Platform | Platform |
| Emily C Williams | Senior Director, B2C Analytics | Data Engineering (reports to Mike Shaw, SVP) |

## FILE:teams/platform/apis-feeds.md
# APIs & Feeds — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026) + APIs & Feeds one-pager

## Overview

APIs & Feeds is the triad focused on building a unified, world-class ecosystem for customer-facing Dow Jones APIs and data feeds. Owns how clients discover, onboard, authenticate, integrate, and get support across Dow Jones' external integration products.

**Triad:** E: Naren Dharma | P: Michelle Mischutin | D: Jesus Gorriti | O: Prakash Shetty

## Responsibilities

- Customer-facing APIs and Feeds strategy: vision, standards, and roadmap for external APIs/feeds across Dow Jones
- Developer and client onboarding experience: end-to-end journey from discovery to access to integration to support
- Developer Portal: redesign and operate the centralized portal as the source of truth for API documentation
- API and feed consolidation strategy: drive consolidation, standardization, and modernization of disparate tech across brands
- Enabling technologies: evaluate and adopt platforms/tools that support a best-in-class ecosystem
- Cross-functional coordination: central point of contact across product triads, core engineering, sales, support, and compliance

## Product portfolio (by cluster)

| Cluster         | Scope                                                     |
| --------------- | --------------------------------------------------------- |
| Cluster 1 (B2B) | Factiva Select, Factiva, Factiva Analytics, Factiva FDK   |
| Cluster 2 (B2B) | Newswires Feeds — Legacy and NextGen                      |
| Cluster 3       | Risk & Compliance legacy feeds and APIs                   |
| Cluster 4 (B2C) | Customer-facing API and feed needs across consumer brands |
| Cluster 5 (B2B) | Newswires APIs (Realtime, Top Stories, Calendar)          |

**Note:** The portfolio is predominantly B2B. Cluster 4 covers B2C consumer brand needs but is not further detailed in available documentation.

## FILE:teams/platform/commercial-tech.md
# Commercial Technology — Platform Team

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026)

## Overview

Commercial Technology is a monetization-focused platform team within the Dow Jones Consumer Product org. It owns the ad products, ad infrastructure, privacy platform, and internal tooling that power advertising across Dow Jones properties (~$300M+ digital advertising business).

Unlike pure platform teams, Commercial Tech rolls into the Consumer Product org (under Robbie Sauerberg) rather than the Platform Product org.

**Triad:** E: Yonathan Feldman | P: Robbie Sauerberg | D: N/A | O: Barbara Shallow

**Product detail:** See `products/commercial-tech/products.md`

## Sub-teams

### Platforms & Privacy
Delivers core ad-serving infrastructure and privacy compliance across Dow Jones properties.

**Triad:** E: Oleg Kodynets (primary), Leo Ma (Mobile App Platforms) | P: Lupe Rodarte (Platforms, Privacy Tech), Kate Downey (Privacy Governance) | O: Barbara Shallow

Covers:
- Ad Platform — core ad-serving and configuration infrastructure
- Privacy Platform (DJCMP) — consent management middleware across stacks and brands
- Newsletters Ad Platform (NAPL) — native ads in newsletters

### Ad Products
Develops marketplace offerings that drive client outcomes via data products (audience targeting, brand safety, data collaboration) and experience products (premium ad formats).

**Triad:** E: Oleg Kodynets | P: Caroline Albanese (Data), Patrick Estanbouli (Experience) | O: Barbara Shallow

Covers:
- SafeSuite — brand safety and suitability tools
- Thematic AI — AI-driven audience and content understanding
- Theme Definer — content and audience classification/taxonomy
- Dynatic — dynamic advertising and experience product
- Ad Formats — proprietary formats for direct-to-subscriber experiences (Hero, Titan, Folio, VStudio, Mosaic, video)

### Information Systems
Empowers Dow Jones advertising functions with data and business automation systems that accelerate operational efficiency and provide insights into client success.

**Triad:** E: Oleg Kodynets | P: Nicholas Smolney | O: Barbara Shallow

Covers:
- InSite — first-party data audience analytics (pre-sale, post-sale, content insights)
- Seawolf — exclusive sponsorship coordination and campaign health monitoring
- Monty — self-serve contract and quote builder for Sales
- DASH — Tableau-based ad data and operations system (under evaluation for deprecation)
- WSJBG Ad Manager (DanAds) — self-serve advertising platform for advertisers and agencies
- Looker — BI and analytics layer; positioned to replace DASH

## FILE:teams/platform/core-experience.md
# Core Experience — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026)

## Overview

Core Experience is the platform group responsible for shared, cross-brand consumer capabilities that make Dow Jones products feel complete and modern. Focused on market data, audio/video, and messaging (newsletters and alerts).

These are horizontal capabilities used across brands (WSJ, Barron's, MarketWatch, IBD, FN, PEN, Mansion Global) and multiple surfaces (web and apps).

**Triad:** E: Chris Tersteeg | P: Matt Kelley | D: Min Chung | O: Matt Chen

## Teams

| Team | PM | Notes |
| --- | --- | --- |
| Market Data | Crystal Koenig | |
| Audio/Video | Lilia Aramayo | |
| Messaging | Marc Torrence | Newsletters and email alerts |

## Products

### Market Data
Shared market data experiences and services powering quotes, charts, watchlists, and market data modules across Dow Jones brands.

Enables:
- Consistent market data content and interactions across brands
- Shared components: Watchlists, Quotes, Market Data Center
- Standard charting and real-time delivery foundations

FY26 initiatives:
- MarketSurge replatforming support via Shared Data Layer (SDL)
- Real-time subscriber services upgrades integrated into SDL
- ChartIQ adoption (moving from HighCharts for consistency)
- Modern watchlist UX and rendering platform modernization (notably for Barron's Investor Circle)

### A/V (Audio and Video)
Platform capability for video and audio discovery, playback, and monetization across apps and web — including shared player strategy and video CMS/workflows.

Enables:
- Cross-brand video discovery and engagement experiences (e.g. media center)
- Improved video ad delivery and format support (pre-roll/mid-roll)
- Player and platform modernization

FY26 initiatives:
- WSJ Redesign: Media Center (Discover / Watch / Listen on iOS and Android)
- Advertising optimizations for video ad experience and delivery
- Video player migration to JWP (assessment and next steps)
- News Corp Video Sharing Program POC (metadata generation/ingestion into video CMS)
- Wealth and Investing video support (Connatix updates, MarketWatch quotes page integration)

### Messaging (Newsletters and Alerts)
Shared systems and tooling powering email newsletters, follow alerts, and live-coverage alerts across brands. Focused on scaling engagement and supporting subscriber value.

Enables:
- Subscriber-only newsletter and alert functionality (entitlement-aware delivery)
- User-choice driven alerts (digest options, clickable templates)
- Live coverage alerts
- Consolidation and migration of newsletters onto standardized platforms (PANDA)

FY26 initiatives:
- Subscriber-only newsletter functionality (supports Barron's Investor Circle and a new Risk newsletter)
- Alerts expansion (digests, source-based alerts, improved templates)
- Live coverage alerts capability (WSJ redesign)
- Written newsletters migration onto PANDA/Curation/Sailthru

## FILE:teams/platform/data-ai.md
# Data & AI — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026) + Data & AI one-pager

## Overview

Data & AI is a Core Foundations organization that owns the end-to-end Snowflake Data & AI ecosystem powering Dow Jones analytics, decisioning, and AI experiences across B2C, B2B, and internal operations.

Designs and operates the platforms, pipelines, and services that:
- Centralize Dow Jones data (content, usage, customer, operational)
- Enforce data governance, quality, and privacy
- Enable AI/ML experimentation and productionization
- Deliver data and content products to internal teams and external customers

**Triad:** E: Mike Shaw | D: Rommel Rojas | O: Greg Blake
**Note:** No org-level product lead listed in triad doc.

## Pods

### 1. Data Architecture & Platform Engineering (DAPE)
Design, build, and manage the foundational data infrastructure and platforms for Dow Jones — enabling scalable, cost-efficient, and secure data operations.

- Owns the enterprise Snowflake platform (all lines of business): account architecture, performance optimization, cost governance, security controls
- Leads the Energy Data Platform delivering data products to Energy customers and integrating with DJ+
- Provides core infrastructure, architectural patterns, and governance frameworks for all structured data activities

Key products: Enterprise Snowflake platform, Energy Data Platform, centralized DBT/Airflow/FastAPI infrastructure, FinOps reporting via FinOut

### 2. Data Governance Engineering (DGE)
Build and implement the technical infrastructure needed to support and enforce data governance policies, data quality, and data management.

- Engineers data quality, metadata, and standardized dictionaries for Snowflake
- Makes Snowflake data trusted, discoverable, and interoperable via data quality controls (Snowflake DMFs), metadata and lineage (Atlan + Snowflake), and data masking/privacy enforcement
- Delivers governance platforms for Energy: Collibra (enterprise data catalog), Semarchy (MDM for standardized dictionaries)

Key products: Governance and quality layer on Snowflake Data Lake, Atlan metadata/lineage platform, Collibra enterprise catalog, Semarchy MDM, data quality framework (Snowflake DMF-based)

### 3. Analytics Engineering
Build and operate the Customer Data Lake in BigQuery and Snowflake, delivering ingestion, transformation, and curated models for enterprise analytics.

- Ingests and models customer and behavioral data across: B2B and B2C Analytics, Ad Tech and Marketing Analytics, Marketing Data Science and Campaign Operations, Newsroom Analytics, W&I, Customer Service, WSJ Opinion, Partnerships
- Delivers curated, analytics-ready datasets powering dashboards, experimentation, and models

Key products: Customer Data Lake (BigQuery + Snowflake), curated subject-area models (marketing, subscriptions, engagement, content performance), shared data marts feeding Looker and data science workflows

### 4. MLOps Engineering
Own the centralized Snowflake ML and AI platform, enabling model deployment, monitoring, and lifecycle management.

- Provides Cortex AI infrastructure and Snowflake-based ML tooling
- Standardizes deployment, monitoring, and lifecycle management for ML models across B2B and B2C analytics, Marketing Analytics, Newsroom Analytics, and Energy
- Ensures ML workloads are observable, governed, and cost-efficient

Key products: Snowflake ML and AI platform (Cortex AI infrastructure), centralized MLOps pipelines, shared feature and model registries (Snowflake-based)

### 5. Data Collections Engineering (DCE)
Collect, measure, and analyze digital content data with accuracy, delivering actionable insights that optimize strategy, engagement, and performance.

- Owns product instrumentation governance: tagging standards, event schemas, event-stream integrity
- Maintains internal analytics pipelines for Marketing GA4, internal publishing systems analytics, Snowplow evaluation
- Supports B2C and B2B with reliable behavioral data

Key products: Analytics instrumentation standards and governance, event streams feeding the Customer Data Lake (web and app telemetry), GA4 and internal analytics implementations for WSJ, Barron's, MarketWatch, and core publishing platforms

### 6. AI & ML Foundations
Provide high-velocity infrastructure that transitions Dow Jones content to agentic intelligence. Enables product teams (Gen AI Experiences, Search + Personalization, DJ Platform) to ship AI features in weeks, not months.

- Builds shared AI infrastructure: model hosting and orchestration, agentic workflow frameworks, real-time evals and guardrails
- Partners with product teams to operationalize GenAI experiences (assistants, summarization, recommendations) and AI-powered decisioning on top of DJ content and data

Key products: Agentic Intelligence platform (shared infra for LLMs and agents), real-time evaluation and monitoring framework, shared AI tools and patterns consumed by product pods

Engineering lead: Maryam Naqvi

### 7. Data Analytics
Provide analytics support across B2B and B2C, surfacing insights and decision support dashboards.

- Partners with business units to define KPIs, build dashboards and reporting for execs, Product, Marketing, and Sales
- Runs deep-dive and ad-hoc analysis using the Customer Data Lake and governed Snowflake assets

Key products: Enterprise dashboards and reports (B2B and B2C), measurement frameworks for subscriptions, engagement, marketing, and B2B product usage

Engineering leads: Denise Fawcitt (B2B), Emily Williams (B2C)

## Who Data & AI supports

**B2C:** WSJ, Barron's, MarketWatch, WSJ+, IBD, Customer Data Platform, audio/video, Market Data

**B2B and platforms:** Factiva, Newswires, Risk and Compliance, DJ+, Energy and CMA, APIs and Feeds, Publishing Systems, DJ Platform, Commercial Tech, Search + Personalization, Enterprise and Core Apps

## FILE:teams/platform/publishing-systems.md
# Publishing Systems — Platform Product

> Last updated: 2026-03-29

## Overview

Publishing Systems provides the core editorial and publishing tools that power Dow Jones consumer newsrooms end-to-end: from story planning, to writing and packaging, to publishing across web, apps, and other channels.

Goal: give editors and reporters a fast, reliable, and unified "OneCMS" experience while retiring legacy tools and fragmentation.

**Product Lead:** Clarissa Matthews

## Teams

NewsGrid, NewsPress, Editorial Tools (covers Curation, Chartlos, Image Manager), DMI, Print & Newswires.

## Products

### NewsGrid
Central planning and orchestration hub for the newsroom.

- Used to plan coverage, track stories and packages, and coordinate across desks
- Acts as the "front door" into the rest of the publishing ecosystem (NewsPress, Curation, etc.)
- Helps editors see what's in the pipeline and manage real-time coverage

### NewsPress
Primary CMS for creating, editing, and publishing articles.

- Used by reporters and editors to write, edit, and manage content for consumer brands
- Supports rich article types, live coverage, and integrations with Chartlos and Image Manager
- Backbone of the OneCMS direction — replacing and consolidating legacy CMS experiences

### Curation
Tool editors use to program and manage surfaces like homepages and section fronts.

- Powers selection and ordering of stories, packages, and modules across key experiences
- Unified interface replacing older, fragmented curation systems
- Enables fast editorial response to news and audience needs

### Chartlos
Core tool for creating and managing charts, graphics, and data-driven visual elements.

- Lets journalists and editors build, update, and embed charts directly into stories
- Integrates into NewsPress so visuals stay in sync with articles
- Supports consistent visual standards and reusability of graphics across brands
- Owned by a standalone engineering team (Atlassian canonical name: ET Chartlos)
- FY27 initiative: Chartlos evolution, including potential HighCharts integration and system refactor

### Image Manager
Central system for finding, managing, and attaching images and other media.

- Searchable library of photos and assets with metadata and rights information
- Integrates with NewsPress and other tools for attaching images to stories and packages
- Supports workflows for sourcing, approval, and reuse of imagery across newsrooms
- Owned by a standalone engineering team (Atlassian canonical name: ET Image Manager)
- FY27 initiative: improve search results using AI, grouping images by article/sked

### DMI
Data/Media Infrastructure — underlying services and tools supporting content, media, and metadata across Publishing Systems.

- Handles storage, retrieval, and enrichment of content and media assets
- Powers integrations between editorial tools and downstream consumers
- Shared foundation that makes the rest of the stack more scalable and consistent

### Print & Newswires
Tools supporting print production and distribution of content via newswires.

- Maintains workflows to get content from digital tools into print layouts and wire products
- Bridges modern tools (NewsPress, NewsGrid) with legacy print and wire systems
- Ensures "create once, publish many" works across digital, print, and wire channels

## How the products fit together

1. **Plan** in NewsGrid: editors plan coverage, assign stories, manage packages
2. **Create** in NewsPress: reporters and editors write and edit stories, using Chartlos for charts and Image Manager for photos
3. **Program** with Curation: editors choose what to feature on homepages, section fronts, and other surfaces
4. **Support and distribute** via DMI (shared content/media infrastructure) and Print & Newswires (print and wire feeds)

Together these products form the OneCMS publishing stack underpinning Dow Jones consumer newsrooms.

## FILE:teams/platform/search-personalization.md
# Search & Personalization — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026)

## Overview

Search & Personalization is the platform org responsible for helping users find, understand, and discover Dow Jones content more effectively. Combines modern search, personalized recommendations, and GenAI experiences.

**Triad:** E: Yulia Zvyagelskaya / Janit Singh | P: Puneet Goel | D: Rommel Rojas / Jesus Gorriti | O: Greg Blake

## Teams

| Team | PM | Notes |
| --- | --- | --- |
| Search | Puneet Goel (Int) | |
| Personalization (Signals) | Puneet Goel (Int) | |
| Gen AI Experiences | Puneet Goel (Int) | Newsbuddy |

## Products

### Search
Shared search platform powering relevant, timely retrieval across core Dow Jones products (B2B and B2C).

Enables:
- Hybrid search (lexical and semantic) to improve relevance and recency
- Modern search UX: summaries, content discovery, advanced search (e.g. boolean)
- "Omni-search" style standardization for DJ+ experiences

FY26 Q1 deliverables:
- New Factiva: hybrid search, improved summaries, advanced search launch
- WSJ: content discovery via links to Author, Company, and Topic pages

### Personalization (Signals)
Platform that captures and uses user signals (implicit and explicit) to deliver personalized feeds, modules, and reranked results across Dow Jones brands.

Enables:
- Shared recommendation endpoints used across brands and surfaces (web and app)
- Personalization for key experiences: MyWSJ, onboarding, preference center, media center, shortlist
- Reusable APIs powering recommendations across products and channels (including newsletter support)

Shared endpoint types:
- **RelatedArticles** — contextual similarity (e.g. "What to Read Next")
- **BundledRecommendedArticles** — ranked, user-tailored bundle (reading history, engagement time, freshness)
- **DiscoverContent** — mixed media discovery (articles, audio, video)
- **Personalized Search** — reranks results using user embeddings and behavior
- **DailyDiscoverUserRecommendations** — newsletter support via Braze

### Gen AI Experiences (Newsbuddy)
AI assistance experiences that help users get to insight faster, grounded in Dow Jones trusted content. Verifiability and source linking are core differentiators.

Enables:
- Customer-validated chatbot/assistant experiences (starting with B2B)
- AI-powered understanding layered into existing workflows: search, summarize, answer, cite

FY26 Q1 deliverable:
- Newsbuddy — validate a standalone chatbot with 3+ B2B customers by EOQ1

## Platform Foundations

Underpins Search and Personalization delivery — not standalone products but tracked in FY26 planning:

- Resiliency and cost savings: MarkLogic migration/upgrade, Pinecone serverless migration
- Metadata ingestion: additional metadata and AIRC for Factiva content to improve quality and enable advanced search

## FILE:teams/platform/team.md
---
name: Platform Product Team
description: Org structure and team leads for Dow Jones Platform Product
type: project
---

# Platform Product Team — Dow Jones

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026)

## Leadership

| Name | Title | Notes |
| --- | --- | --- |
| Yonathan Feldman | SVP, Platform Engineering | Leads Platform org overall |
| Puneet Goel | VP Product, Search & Personalization | Also serving as Interim Head of Platform Product |
| [OPEN] | SVP Product, Platform | JD posted; Puneet covering in interim |

## Orgs and teams

### Publishing Systems
**Triad:** E: John Lynch / Matt Miritello | P: Clarissa Matthews | D: Brian Feeney | O: Marina Guvenc
**Detail:** See `teams/platform/publishing-systems.md`

| Team | Product Lead | Notes |
| --- | --- | --- |
| NewsGrid | Christine Lim | |
| NewsPress | Christine Lim | |
| Editorial Tools | Chelsea Qiao | Curation, images, charts, real-time coverage |
| DMI | Victor Llorente / Claudio Zanotti | |
| Print & Newswires | N/A | |

**Note on team names:** The triad doc shows "Editorial Tools" as the team covering curation and editorial tooling (including Chartlos and Image Manager areas), distinct from NewsGrid and NewsPress. Chartlos and Image Manager are standalone products with their own engineering teams (ET Chartlos, ET Image Manager).

### Search & Personalization
**Triad:** E: Yulia Zvyagelskaya / Janit Singh | P: Puneet Goel | D: Rommel Rojas / Jesus Gorriti | O: Greg Blake
**Detail:** See `teams/platform/search-personalization.md`

| Team | Product Lead | Notes |
| --- | --- | --- |
| Search | Puneet Goel (Int) | |
| Personalization (Signals) | Puneet Goel (Int) | |
| Gen AI Experiences | Puneet Goel (Int) | Newsbuddy |

### Core Experience
**Triad:** E: Chris Tersteeg | P: Matt Kelley | D: Min Chung | O: Matt Chen
**Detail:** See `teams/platform/core-experience.md`

| Team | Product Lead | Notes |
| --- | --- | --- |
| Market Data | Crystal Koenig | |
| Audio/Video | Lilia Aramayo | |
| Messaging | Marc Torrence | Newsletters and email alerts |

### Data & AI
**Triad:** E: Mike Shaw | D: Rommel Rojas | O: Greg Blake
**Note:** No org-level product lead listed in triad doc.
**Detail:** See `teams/platform/data-ai.md`

| Pod | Engineering Lead | Notes |
| --- | --- | --- |
| Data Architecture & Platform Engineering (DAPE) | | Snowflake platform, Energy Data Platform |
| Data Governance Engineering (DGE) | | Data quality, metadata, Atlan, Collibra, Semarchy |
| Analytics Engineering | Tracey Diep | Customer Data Lake (BigQuery + Snowflake), curated models |
| MLOps Engineering | | Snowflake ML platform, Cortex AI, model lifecycle |
| Data Collections Engineering (DCE) | | Instrumentation, event streams, GA4 |
| AI & ML Foundations | Maryam Naqvi | Agentic AI infra, shared LLM/agent platform |
| Data Analytics | Denise Fawcitt (B2B), Emily Williams (B2C) | Dashboards, measurement frameworks |

### APIs & Feeds
**Triad:** E: Naren Dharma | P: Michelle Mischutin | D: Jesus Gorriti | O: Prakash Shetty
**Detail:** See `teams/platform/apis-feeds.md`

| Team | Product Lead | Notes |
| --- | --- | --- |
| Customer Facing | Michelle Mischutin | Next-gen integration platform for customer-facing APIs and feeds |

### Commercial Technology (Advertising & Privacy)
**Triad:** E: Yonathan Feldman | P: Robbie Sauerberg | D: N/A | O: Barbara Shallow
**Note:** Rolls into Consumer Product org (under Robbie Sauerberg), not Platform Product org. Included here as it operates as a platform team.
**Detail:** See `teams/platform/commercial-tech.md` and `products/commercial-tech/products.md`

| Sub-team | Product Lead | Notes |
| --- | --- | --- |
| Platforms & Privacy | Lupe Rodarte (Platforms/Privacy Tech), Kate Downey (Privacy Governance) | Ad Platform, DJCMP, NAPL |
| Ad Products | Caroline Albanese (Data), Patrick Estanbouli (Experience) | SafeSuite, Thematic AI, Theme Definer, Dynatic, Ad Formats |
| Information Systems | Nicholas Smolney | InSite, Seawolf, Monty, DASH, WSJBG Ad Manager, Looker |

### WSJ+
**Triad:** E: Travis Johnson | P: Clarissa Matthews | D: Forest Evashevski | O: Mushirah Kelley
**Note:** WSJ+ is a separate platform triad — not the same as DJ Platform (which is B2B). Clarissa Matthews leads both WSJ+ and Publishing Systems product.
**Detail:** See `teams/platform/wsj-plus.md`

### DJ Platform (B2B)
**Triad:** E: Vishaal Patil | P: Stefan Ritter | D: Jesus Gorriti | O: Greg Blake / Monique Luque
**Note:** DJ Platform is the foundational operating system for Dow Jones B2B applications. Stefan Ritter leads this. Out of scope for B2C repo but included here for cross-reference.

## FILE:teams/platform/wsj-plus.md
# WSJ+ — Platform Product

> Last updated: 2026-03-29
> Source: Triad Leadership doc (30 March 2026) + WSJ+ internal documentation

## Overview

WSJ+ is Dow Jones' premium consumer brand and subscription tier that combines multiple publications and personalized experiences into a single, unified membership.

Tagline: "The World's Business. Your Business."

Not called "WSJ+ Bundle" in customer-facing copy — just "WSJ+".

**Triad:** E: Travis Johnson | P: Clarissa Matthews | D: Forest Evashevski | O: Mushirah Kelley

## Tiers

| Tier | Included titles |
| --- | --- |
| WSJ+ Preferred (3-product) | WSJ, Barron's, MarketWatch |
| WSJ+ Premier (4-product) | WSJ, Barron's, MarketWatch, Investor's Business Daily |

## Core features

### WSJ+ Dashboard
Centralized, cross-brand dashboard exclusive to WSJ+ members. Aggregates content from all titles with:
- Top News
- Today's Markets
- My Watchlist
- Recommended news by companies and industries followed
- Deep personalization via "Personalize Your Experience"

### WSJ+ News For You
Onsite recommendation module on WSJ.com. Recommends relevant articles with images to WSJ+ subscribers. Lives on the front page under the Opinion section.

### Your Daily Discover
Exclusive multi-title, personalized newsletter surfacing the most relevant stories across the bundle.

### Unified preference and alerts experience
One place to manage alerts, newsletters, and watchlists across all titles (WSJ, Barron's, MarketWatch, IBD).

### Personalized onboarding
On signup: interests, industries, watchlist, alerts, newsletters, and app downloads — sets up the personalized experience from day one.

## WSJ+ Marketplace
Premium marketplace where WSJ+ members can buy add-on products at discounted rates. Examples: Leaderboard, MarketDiem, IBD courses, Barron's premium newsletters.

## Availability and model

- Individual/ecommerce digital subscriptions only — no corporate
- Initially US-only; expanding to select international markets via WSJ+ International
- Former "Investor Bundle" (4-product) and US 3-product bundles have been migrated onto WSJ+ entitlements

## How customers subscribe or upgrade

- Shop page journeys on WSJ.com, Barrons.com, MarketWatch.com: new WSJ+ long-scroll shop page (subset of WSJ traffic) and legacy shop with WSJ+ presented in place of prior bundles
- Customer Center upgrade flow for eligible subscribers
- "Get WSJ+" and "Upgrade to WSJ+" CTAs in nav, onsite modules, and account hub

## Who it's for

- High-value consumer subscribers wanting cross-brand news and investing coverage in a single experience
- Multi-brand loyalists across WSJ, Barron's, MarketWatch, and IBD
- Upsell candidates from WSJ-only or other bundles into a higher-value tier

## Early performance data (FY25)

- 25% of 4-product and 15% of 3-product bundle subscribers engaging with WSJ+ articles
- Strong cross-brand reading behavior observed
- ~300% growth in dashboard page views since launch

## Notes
- There is no separate WSJ+ app — customers download individual apps for WSJ, Barron's, MarketWatch, and IBD
- WSJ+ is the product brand; entitlement and access are managed through the Commerce/Identity stack

## FILE:teams/product/team.md
# Product Team — Commerce, Dow Jones

> Last updated: 2026-03-20

## VP

**Daniel Hockley** — VP of Product, Commerce (Mar 2025–Present)
Previously VP Product, Subscriptions (Sep 2024–Mar 2025)
Reports to: Ryan Daly (SVP, Consumer Product)

## Direct reports — managers

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Craig Casazza | Senior Product Director | SEO | Jul 21, 2025 |
| Leigh Hunt | Group Product Manager | Subscriptions – Subscriber Acquisition | Apr 13, 2020 |

## Direct reports — individual contributors

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Adam Guttmann | Senior Product Manager | Identity & Entitlements | Sep 2, 2025 |
| Katy Mastorakis | Senior Product Manager | Subscriptions – Mobile Apps | Apr 14, 2025 |
| Joe Stein | Product Manager II | Subscriptions – Engagement, Revenue & Retention | Jan 7, 2025 |

## Leigh Hunt's reports

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Shani Giersbach | Product Manager II | Subscriber Acquisition | Feb 2, 2026 |
| Daniel Saxon | Product Manager II | Subscriber Acquisition | Mar 10, 2025 |

## Craig Casazza's reports

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Emily Schwartzberg | Senior Product Manager | SEO | Feb 21, 2022 |

## Areas of ownership

| Area | PM(s) |
| --- | --- |
| SEO | Craig Casazza, Emily Schwartzberg |
| Subscriber Acquisition | Leigh Hunt, Daniel Saxon, Shani Giersbach |
| Subscriber Engagement, Revenue & Retention | Joe Stein |
| Subscriber Mobile | Katy Mastorakis |
| Identity & Entitlements | Adam Guttmann |

## FILE:teams/product/ways-of-working.md
# Ways of Working — Commerce Product Team

How the Dow Jones Commerce product team operates day to day.

## Team structure

Commerce operates as a **platform team** — serving both Consumer (B2C) and B2B sides of the business. Solutions typically need to work across multiple brands and surfaces.

## Leadership triad model

Every pod has a leadership triad with equal representation from Product, Engineering, and Design. The Commerce senior leadership triad:
- **Product:** Daniel Hockley (VP)
- **Engineering:** Ajith Ittan / Ratheesh Nair (VP)
- **Design:** Min Chung / Jesús Gorriti (VP)

## Quarterly planning

Commerce produces quarterly roadmaps aligned to annual OKRs. The planning process:

1. **Backlog review** — Product, Engineering, and stakeholders review existing backlog items and decide what to carry forward
2. **Force rank** — Stakeholders produce a force-ranked list of new and existing priorities
3. **LOE & capacity calculation** — Tech team produces high-level estimates; capacity calculated against available engineering sprints
4. **Roadmap proposal & alignment** — Tech, Marketing, Business, and Newsroom teams align on what is committed vs. backlogged

Each initiative is then:
- Categorised by objective (Acquisition, Retention, Revenue, Engagement, Identity, SEO, Enterprise)
- Assigned to a pod and PM
- Flagged for design dependency
- T-shirt sized (S/M/L) for Engineering and Design independently
- Assigned a deliverable type (Discovery / Design / Development / Backlog)

## Deliverable types

| Type | Meaning |
| --- | --- |
| Discovery | Product-led research; delivers problem statement, vision, solutions, ROI, and requirements |
| Design | Design & research delivers high-res, signed-off designs |
| Development | Engineering delivers code-complete, releasable product or feature |
| Backlog | Deferred — no work committed this quarter |

## T-shirt sizing

| Size | Duration | Sprints |
| --- | --- | --- |
| S | 2 weeks | 1 sprint |
| M | 6 weeks | 3 sprints |
| L | Whole quarter | ~3 months |

## Tracking tool

**Jira Product Discovery (JPD)** — status health tracked via RAG (Red / Amber / Green / On Hold)

## Working with marketing

The Central Marketing Org (CMO) is the primary consumer stakeholder. They are accountable for subscription targets and use Commerce products as one channel in an omni-channel strategy. Commerce and marketing teams are structured around the same customer journey stages: Acquisition, Engagement, Revenue, Retention.

## Key marketing partners

| Name | Role |
| --- | --- |
| Greg Ragon | SVP, Performance Marketing — overall marketing lead |
| Sarah Hilston | VP, Global Acquisition & Paid Media |
| Chris Stanco | VP, Engagement & Retention |

## Product philosophy

- Start with the problem, not the solution — work backwards, define and validate the problem first
- PRDs are thinking tools, not forms — writing forces clarity
- Collaborative by design — PRDs are built with the triad (PM, Design, Engineering), not handed down
- PRDs are living documents — maintained throughout development, not filed away after kickoff
- Shipping is an output, not an outcome — measure what changed in the world (subscriber growth, retention, engagement), not what the team delivered
- Use the double diamond — diverge to discover the problem fully, converge on solutions

## FILE:tech/data-sources.md
# Data Sources

Analytics platforms, data systems, and data tooling used across Dow Jones Commerce.

## Analytics leadership

| Name | Role | Reports to |
| --- | --- | --- |
| Emily C Williams | Senior Director, B2C Analytics | Mike Shaw (SVP, Data Engineering) |

## Key data and analytics teams

| Team | Role |
| --- | --- |
| B2C Analytics | Subscription performance data, experiment analysis |
| Data Science & Analytics | Experimentation analysis and insights; supports A/B test evaluation |
| Marketing Operations | Offer setup, onsite placements, CRM data |
| Data Engineering | Data pipeline dependencies |

## Subscription KPIs tracked

| Metric | Definition |
| --- | --- |
| ARPU | Average Revenue Per User |
| CVR | Conversion rate — % of paywall impressions resulting in subscription start |
| Churn | Rate at which subscribers cancel or lapse |
| Early-life engagement | Avg active days in subscriber's first 7 days |
| Bundle subscriptions | Number of subscriptions in a WSJ+ bundle |
| Bundle revenue | Total revenue from bundle subscriptions |
| Save offer take rate | % of subscribers presented with a save offer who accept it |
| Registered users | New free accounts created per month |
| Crawl coverage | % of priority content successfully crawled by search engines |
| Crawl waste | % of crawl budget spent on non-priority pages |

## Experimentation and testing

- Experiments run via **Optimizely** and **Statsig**
- Results analysis led by Data Science & Analytics team
- Statistical significance required before shipping experiment results

## Notes

Data quality: some FY26 OKR metrics (bundle revenue, bundle subscriptions) are noted as "metric TBC from business" — baseline definitions still being confirmed.

## FILE:tech/messaging.md
# **Project README: Dow Jones Messaging Strategy & PANDA Migration (Updated Jan 2026\)**

## **1\. Executive Summary**

The Dow Jones messaging infrastructure is transitioning from legacy, brand-specific tech stacks toward a centralized, platform-agnostic architecture centered on **PANDA**.

* **Primary Mission**: Migrate all email products from **Campaign Monitor** to **Sailthru** by **December 31, 2027**, to satisfy contract exit requirements.
* **Current Progress**: As of January 2026, the project has established a production-ready foundation for automated and written newsletters, along with automated **Follow alerts**.
* **Migration Status**: Of the 138 products in scope for the year-end deadline, 15% are fully migrated and 15% are configured for production (awaiting onboarding). The remaining 70% require brand-specific template development or new centralized service logic.

## **2\. The Identity Foundation ("The Golden Key")**

* **PANDA**: Serves as the central orchestration engine and is the **future-state source of truth** for user management and subscription data.
* **ENS**: The legacy source of truth for email subscriptions, currently bridged to PANDA via a proxy to maintain data parity.
* **MEGA**: Legacy middleware that synchronizes data between ENS and Campaign Monitor.

## **3\. Organizational Ownership & Boundaries**

### **A. Messaging Team (Internal Domain)**

* **PANDA**: Core orchestration hub for content ingestion, template management, and delivery logic.
* **ENS**: Legacy subscription database.
* **MEGA**: Middleware syncing ENS to Campaign Monitor.

### **B. Partner Systems (Internal Tech Partners)**

* **Publishing Systems**: Owns **NewsPress** (internal CMS for newsletter/article content) and **Curation** (internal tool for manual programming and triggering).
* **Breaking News**: Includes the **WSJ Breaking News Tool** (used by newsroom/Opinion) and **BAT Tool** (MarketWatch), both communicating directly to Airship.
* **Brand Teams**: Vertical tech teams (web/mobile) integrating with ENS and Airship for preference management.
* **NAPL (Native Ads Platform)**: Internal tool for AdOps to program and deliver native ads content.

### **C. External Systems (Vendors)**

* **Sailthru (Zeta)**: Target ESP for all newsletter products.
* **Campaign Monitor (Marigold)**: Legacy ESP to be decommissioned by Dec 31, 2026\.
* **Airship**: Vendor for mobile and web push notifications, managed at the brand level.
* **Braze**: Used by Marketing for lifecycle journeys independently of PANDA.
* **Amazon SES**: Email delivery for B2B brands (Energy and Factiva).
* **Salesforce Marketing Cloud**: ESP for IBD mainstream newsletters (currently outside CM migration scope).
* **Pushly**: Limited implementation on MarketWatch for desktop alerts.

## **4\. The Six Use Cases (Plus One)**

1. **Written Newsletters**: Content is manually written as an article in NewsPress and triggered via Curation; requires high coordination and custom template development.
2. **Automated Newsletters**: Driven by pre-defined content queries (e.g., "Most Read") and delivered on a set schedule without manual assembly.
3. **Automated Alerts ("Follow")**: Real-time alerts for authors or topics; these were the first native PANDA/Sailthru use cases.
4. **Triggered Alerts (Breaking News)**: Manually triggered for urgent news; currently involves a fragmented workflow and manual email assembly.
5. **Transactional**: System-triggered communications (e.g., password resets) currently hard-coded within brand front-ends.
6. **Courses/Journeys**: Automated email series; content and logic will be hosted natively within Sailthru.
7. **Move to Marketing**: Non-editorial products targeted for hand-off to marketing platforms.

## **5\. B2B Messaging Landscape**

* **High-Priority Migration (Campaign Monitor)**: **Newswires** requires development of white-labeling and dynamic data configurations for organization-level metadata.
* **Legacy B2B (Brand-Managed)**: **Energy** (reports via SES) and **Factiva** (alerts via legacy infrastructure managed by legacy members of the Messaging team).
* **PANDA-Native Risk Portfolio**: **Dow Jones Risk Journal**, **Oxford Analytica**, and **Dragonfly** (migration in progress) utilize the centralized PANDA/Sailthru stack.
* **MarketSurge Replatform**: Premium initiative building centralized email and mobile alerts on PANDA, synced with Airship and Sailthru.

## **6\. Takeaways and Opportunities**

* **Identity Silos**: No shared backend currently links mobile push (Airship) and email (ENS/PANDA), preventing a unified preference view.
* **Template Debt**: Technical readiness is still needed for templates for **MG, FN, and PEN**, and specialized variants for **WSJ Opinion and Pro**.
* **New Patterns**: **Transactional** and **Triggered Alerts** remain 100% on legacy systems and require new PANDA logic and centralized tooling for breaking news.
* **Onboarding Dependency**: 21 "Configured in Production" products are stalled pending editorial training and onboarding.
* **Operational Latency**: WSJ editors' manual "double-build" for breaking news results in a 10–20 minute email latency gap.

---

### **Visual Architecture (Mermaid.js)**

Code snippet

```
graph TD
    subgraph Messaging_Domain [Messaging Team Domain]
        PANDA[PANDA Orchestration]
        ENS[ENS Subscription DB]
        MEGA[MEGA Sync Tool]
    end

    subgraph Partners [Partner & Brand Tech]
        NP[NewsPress CMS]
        CUR[Curation Tool]
        BT[Alert Tools: BNT / BAT]
        NAPL[Native Ads Platform]
        BRAND[Brand Web/Mobile Teams]
    end

    subgraph External [Vendors]
        ST[Sailthru - Target]
        CM[Campaign Monitor - Legacy]
        AS[Airship - Push]
        PL[Pushly - Desktop]
        SF[SF Marketing Cloud - IBD]
        SES[Amazon SES - B2B]
        BR[Braze - Marketing]
    end

    NP -->|Article Content| CUR
    CUR -->|Trigger| PANDA
    BT -->|Push Trigger| AS
    NAPL -->|Native Ads| PANDA

    ENS <-->|Proxy| PANDA
    ENS -->|Sync| MEGA
    BRAND -->|Integration| ENS

    PANDA --> ST
    PANDA --> AS
    MEGA --> CM
```

## FILE:tech/stack.md
# Tech Stack

Key platforms, tools, and services used across Dow Jones Commerce.

## Subscription and paywall

| Technology | Used for | Notes |
| --- | --- | --- |
| Piano / Composer | Paywall management, A/B testing, subscription targeting, offer delivery | Primary paywall platform; migrated from Cxense |
| CAJ | Checkout and acquisition journey — the checkout platform | Used across WSJ, Barron's, MarketWatch |
| SubsHub | Subscription management — upsell, save offers, user profile, cancellation flows | |

## Identity and authentication

| Technology | Used for | Notes |
| --- | --- | --- |
| OneID / DJOP | Unified identity platform — single auth layer across all DJ products | All B2C traffic routed through DJOP tenant as of Nov 2025 |
| OAuth2 / OpenID Connect (OIDC) | Token-based access standard — replacing legacy authentication | Target: 100% coverage |

## CRM and engagement

| Technology | Used for | Notes |
| --- | --- | --- |
| Braze | CRM platform — mobile in-app messaging, push notifications, email campaigns, AppsFlyer integration | |
| AppsFlyer | App install attribution — integrated with Braze (Nov 2025) | |

## Experimentation and A/B testing

| Technology | Used for | Notes |
| --- | --- | --- |
| Optimizely | A/B testing | Used for onsite experimentation including "Candybar" promotion units |
| Statsig | Experimentation platform | |

## Project and roadmap management

| Technology | Used for | Notes |
| --- | --- | --- |
| Jira Product Discovery (JPD) | Roadmap tracking, initiative status, RAG health | |
| Confluence | Documentation, team wikis | Katy Mastorakis created Confluence hub for Commerce team |

## SEO infrastructure

| Technology | Used for | Notes |
| --- | --- | --- |
| Olympia | Rendering platform — News Types pages migrated here | |
| XML sitemaps | Crawl and indexing for WSJ, Barron's, MarketWatch | Canonical fix resolved 190k non-self-referencing URLs |

## Analytics

See `tech/data-sources.md` for full detail.

## Notes

- Legal, privacy, and InfoSec reviews are standard dependencies for anything touching identity, billing, or personal data — initiate early, not at launch
- Platform team remit: solutions must typically work across multiple DJ brands and surfaces

## FILE:process/product-development.md
# Product Development Process

How work moves from idea to shipped feature at Dow Jones Consumer Products.

## Document types

### 1-Pager
Used to sell a product idea and get stakeholder alignment. Comes before a PRD.

**Purpose:**
- Gain support for the idea — provide context for the problem being solved, for whom
- Define scope — what does the work entail, and what does it not include
- Set success metrics — what does success look like?

**Audience:** Stakeholders, leadership, team

### PRD (Product Requirements Document)
Expands on the 1-pager with deeper research, analysis, and execution detail. Created after the 1-pager has been socialised and discovery has begun.

**Purpose:**
- Defines the problem and solution for everyone who will work on it
- Defines requirements for MVP and beyond
- Sets expectations for stakeholders
- Reduces scope creep and assumptions

**Audience:** Product triads (PM + Design + Engineering), stakeholders, PMO

See `process/templates/1pager-prd-template.md` — contains both the 1-Pager and PRD templates.

## Stages

### 1. Discovery
- Define and validate the problem before proposing solutions
- Key output: 1-Pager, problem statement, opportunity sizing
- Use the double diamond: diverge to discover the problem fully, converge on solutions

### 2. Definition
- Build the PRD in collaboration with the triad (PM, Design, Engineering)
- PRDs are living documents — maintained throughout development, not filed after kickoff
- Key output: PRD with requirements, success metrics, dependencies

### 3. Design
- Design and Engineering work together from the PRD
- Design reviews involve the triad and relevant stakeholders
- Accessibility is a standard consideration

### 4. Build
- Sprint structure: S (1 sprint / 2 weeks), M (3 sprints / 6 weeks), L (whole quarter)
- Tracking in Jira Product Discovery (JPD) with RAG status
- Deliverable types: Discovery / Design / Development / Backlog

### 5. Launch
- Governed by launch tier — not everything requires the same level of process
- Key dependencies: Legal/Privacy for anything touching identity or billing; InfoSec for data flows
- See `process/go-to-market.md`

### 6. Post-launch
- Success measured against pre-defined metrics — outcome-based, not output-based
- A/B test results reviewed and decisions made to ship, iterate, or kill

## Triad model

Every pod has a core triad: PM + Design + Engineering working together from discovery through delivery.

## Key tools

| Tool | Used for |
| --- | --- |
| Jira Product Discovery (JPD) | Roadmap, initiative tracking, RAG status |
| Confluence | Documentation, team wiki |

## Standard dependencies for identity/billing work

Legal, Privacy, and InfoSec reviews are standard for anything touching identity, authentication, billing, or personal data. These are not launch gates — they should be initiated early in discovery.

## FILE:process/templates/1pager-prd-template.md
# 1-Pager vs PRD

### TL;DR: Use a 1-Pager to sell a product idea and a PRD to build on it.

### **What is a 1-Pager?**

The 1-pager helps you put a stake in the ground. It clarifies what you are trying to do, what is your hypothesis, what are your expectations for success, and what the impact will be. This document will help you sell your idea to stakeholders and leadership, and to initiate Discovery with your triad and team.

**Purpose:**

1. Gain support for your idea \- provide context for the problem you’re solving, for whom
2. Define scope \- what does the work entail, and what does it *not* include
3. Success metrics \- what does success look like? What results do you expect?

**Audience:**

* Stakeholders
* Leadership
* Team

### **What is a PRD?**

A Product Requirements Document (PRD) is a document that helps a product manager develop an idea and communicate it to others involved in the project, so that work can be planned and execution can begin. It should come from the 1-pager and discovery.

**Purpose**

1. Defines the problem and solution for everyone who will work on it
2. Defines requirements \- information that is necessary for MVP and beyond
3. Sets expectations for stakeholders
4. Reduces scope creep
5. Reduces assumptions

**Audience**
A well-written PRD will provide information for various audiences, from triad partners, to start the conversation, to engineering teams, who will build the solution, to stakeholders, who are invested in the learnings or success of the solution. A PRD will become a working document that can be developed and referred back to as a project progresses.

# 1-Pager Template

### The 1-pager helps you put a stake in the ground. It clarifies what you are trying to do, what is your hypothesis, what is expected success, and what the impact will be. This document will help you sell your idea to stakeholders and leadership, and to initiate discovery with your triad and team. At this stage try not to be too prescriptive about what to deliver and leave space for collaborative development.

— \[Delete above this line\]
\[Initiative Title\]

**One-line Summary**
\[Write a TLDR; Capture the product’s objective as concisely as possible. Think of what problem are we solving, why is it important and what impact it might have? Provide clarity and context right from the start to help readers quickly grasp the initiative's purpose.

Example: “A paywall embedded within the video player prompting users to subscribe to continue watching.”\]

#### **Problem**

\[What is the problem, challenge or gap that’s been identified? Who does it affect? Try not to refer to the solution at this stage, just talk about the problem at hand. A problem statement should never just be the need for a specific feature we are hoping to build. Include any data or evidence you have that illustrates the problem.

Example: “We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content.”\]

**Goal(s) / Solution opportunity**
\[What does the solution need to achieve at a high level? If we solve this problem what will we get? What value will this work bring to the company, if it is successful? Conversely, what will DJ *miss out on* by not doing it? How will this give DJ competitive advantage?

Example: “If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on.”\]

#### **Risks and Mitigation**

\[What are known risks, and how do you plan to mitigate them?

Example: “Video views may drop overall, reducing advertising revenue.”\]

**Success Metrics**
\[What does success look like? How will you measure success? How will you validate progress and success?

Example: “Monthly paywall impressions”\]

**Proposed Solution(s)**
\[If you already have an idea or ideas for a solution, describe them here. Be directional but not prescriptive at UI level.

Example: “A paywall embedded in the video player, prompting users to subscribe.” is better than “An overlay on the video player with a button that links users to a shop page.”\]

**Must Haves**
\[List any mandatory requirements here. This doesn’t need to include everything, but should be based on what you know today.

Example: Must work across the website and mobile app.\]

# PRD Template

### The PRD expands on the 1-pager to provide more in-depth research, analysis and execution details. It is mostly created by the Product Manager, who is responsible for clearly defining what and why an initiative is important. How we accomplish the goal should be defined in close collaboration with Design and Engineering.

### Some of the information will come from your 1-pager, and some from discovery. The information you put into the PRD will help define your project so that the team can begin work.

— \[Delete above this line\]
\[Initiative Title\]

**One-line Summary**
\[Write a TLDR; Capture the product’s objective as concisely as possible. Think of what problem are we solving, why is it important and what impact it might have? Provide clarity and context right from the start to help readers quickly grasp the initiative's purpose.

Example: “A paywall embedded within the video player prompting users to subscribe to continue watching.”\]

#### **Problem**

\[What is the problem, challenge or gap that’s been identified? Who does it affect? Try not to refer to the solution at this stage, just talk about the problem at hand. A problem statement should never just be the need for a specific feature we are hoping to build. Include any data or evidence you have that illustrates the problem.

Example: “We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content.”\]

#### **Vision**

\[Make a statement about the impact you expect to make when this work is complete. How does this vision align with the [Dow Jones Mission and Vision](https://intranet.dowjones.com/home/ls/content/5294558629855232/who-we-are#mission)?

Example: “Turn our video content into a high volume subscription driver.”\]

**Goal(s) / Solution opportunity**
\[What does the solution need to achieve at a high level? If we solve this problem, what will we get? What value will this work bring to the company, if it is successful? Conversely, what will DJ *miss out on* by not doing it? How will this give DJ competitive advantage?

Example: “If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on.”\]

**Proposed Solution(s)**
\[If you already have an idea or ideas for a solution, describe them here. Be directional but not prescriptive at UI level.

Example: “A paywall embedded in the video player, prompting users to subscribe.” is better than “An overlay on the video player with a button that links users to a shop page.”\]

#### **Assumptions and Constraints**

\[What are the assumptions you are basing your hypothesis on? What are the technical, business, legal, or other constraints you know of?\]

#### **Audience**

\[Who is the audience or beneficiary for this solution? What do we know about them? Include any audience  you have or define the audience you want to serve. Consider who makes the purchasing decision, as in the customer, versus who will use this, as in the user, and who others might experience the consequences of its use.\]

#### **Success Metrics**

\[How will you measure success? How will you validate progress and success?\]

|  | *Name* | *Definition* | *Current Baseline Performance & Target* |
| :---- | :---- | :---- | :---- |
| **Topline Metric** | Example: Monthly Paywall impressions per pageview | The total number of times a paywall is seen by a user / overall pageviews per month | Baseline: 0.1 Target: 0.3 |
| **Secondary Metric** |  |  |  |
| **Counter Metric** | Example: Monthly video ad impressions | The total number of video ads viewed monthly | Baseline: 1.2M Target: Maintain the baseline. |

#### **Risks and Mitigation**

\[What are known risks, and how do you plan to mitigate them?

Example: “Video views may drop overall, reducing advertising revenue.”\]

#### **Scope & Requirements**

\[What user stories must be fulfilled by the solution? Design and engineering teams will use these to make sure the product achieves everything it needs to to fulfill the user and business needs. Try to focus on user needs without prescribing solutions. Leave enough space for design and engineering teams to explore multiple paths and solutions.\]

\[What is a must have or nice to have for MVP? What is not part of MVP, and can be added after launch? What is the definition of done, and what maintenance and monitoring should follow?\]

| Requirement Title | Description | User Story (optional) | Scope | Notes |
| :---- | :---- | :---- | :---- | :---- |
| Example: Sale pricing | The ability to change pricing that is displayed during sale periods or update pricing to match the current offer. | As a user, I want to see sale pricing within the video player so that I can quickly weigh up my purchasing decision and proceed to purchase. | MVP / Must have / Nice to have | Marketing operations should be able to run sales without the need for engineering involvement.  |
| Example 2: Flexible branding across DJs consumer brands. | … | … | … | … |

#### **Dependencies**

\[Does your solution have any dependencies on other teams or tooling? Are there Design, UX, or Accessibility considerations? Are there legal requirements or reviews that need to be incorporated into your plan? Are there any other teams or projects that are dependent on your solution, which might impact timing of your deliverable?\]

#### **Timing**

\[Is there a hard date by which this needs to be launched, or other timing considerations to be mindful of?\]

#### **RACI (Optional. For large initiatives)**

| Team | Responsible | Accountable | Consulted | Informed |
| :---- | :---- | :---- | :---- | :---- |
| **Product** | List teams and/or individuals |  |  |  |
| **Engineering** |  |  |  |  |
| **Design** |  |  |  |  |
| **Subscription Marketing** |  |  |  |  |
| **PMO** |  |  |  |  |
| **SEO** |  |  |  |  |
| **Data** |  |  |  |  |
| **Privacy/Legal** |  |  |  |  |
| **Customer Service** |  |  |  |  |

##

## **Tasks (Optional)**

\[For cross-functional work, break the project down into top level tasks, listing the major steps required to complete the project, who will own them, any dependencies, and links to relevant resources.\]

| Team | Task | Owner | Notes |
| :---- | :---- | :---- | :---- |
| UXD | Wireframes | Person | Not to reflect final designs. |
| Engineering | Technical discovery | Person | … |
|  |  |  |  |

**Other considerations:**
Legal considerations/requirements
InfoSec considerations/requirements
Design \+ UX Considerations
Accessibility needs
B2C considerations \- [Product Development Checklist](https://docs.google.com/document/d/1TAXM7idFoAb9f7DgIcWnFzm9GB6LTXXqHu5_wO-po6s/edit?tab=t.0)
B2B considerations
Marketing considerations
Prioritization (where does this fit in your roadmap)
User personas
Competitors

## FILE:style/writing.md
# Writing Style — Dow Jones Commerce Product Team

Voice, tone, and conventions for internal product documentation.

## Core principles

- **Concise, direct, actionable** — shorter and clearer beats comprehensive and unread
- **Subheadings are essential** — use them in all substantive writing, even short documents. The best subheadings summarize the point, not just label the topic. A reader should understand the key idea from the heading alone.
- **Write for skim readers** — dense blocks of text lose people. Short paragraphs, clear headings, simple language.
- **Bullet points have limits** — keep lists to under 6 items. Each bullet should be one short sentence. If a bullet is running long, it's probably a paragraph. If a list is running long, break it into themed sections.

## Language

- Always use **American English** spelling: recognize, analyze, color, prioritize, optimize
- No emojis in professional documents
- Avoid internal jargon without explanation — use the glossary (`company/glossary.md`)

## PRD writing principles

- **Start with the problem, not the solution** — stakeholders often arrive with fully formed solutions; work backwards
- **PRDs are thinking tools, not forms** — writing forces clarity; if you struggle to define the problem, the initiative may not be ready
- **Be outcome-based** — success metrics should connect to subscription KPIs (paywall impressions, CVR, subscriber acquisition, churn, ARPU), not just outputs
- **Simple scales** — front-load with the most important information

## Naming conventions

| Preferred | Avoid | Notes |
| --- | --- | --- |
| The Wall Street Journal | WSJ (in external-facing copy) | WSJ is fine internally |
| MarketWatch | Market Watch (one word) | |
| Commerce team | Subscriptions team | Team was renamed to Commerce in Mar 2025 |
| OneID | One ID | Single word |

## Document audiences

| Document type | Primary audience |
| --- | --- |
| 1-Pager | Stakeholders, leadership |
| PRD | Product triad (PM + Design + Engineering), stakeholders, PMO |
| Roadmap | Leadership, marketing stakeholders, cross-functional partners |
| Quarterly planning summary | Tech, Marketing, Business, Newsroom teams |

## Writing for AI tools (this repo)

When writing context files for this repo:
- Be specific and factual — avoid vague generalities
- Use tables for structured information
- Mark placeholders clearly with `[Add]`
- Include "Last updated" dates where content may go stale
- Link to other files rather than duplicating content

## FILE:context-compiled.md
# DJ B2C CONTEXT ENGINE
# Compiled context for Dow Jones B2C product team.
# Use this as system context when generating product docs, PRDs, briefs, or strategy.
# Source of truth: github.com/danielhockley1337/dj-b2c-context
# Files included: 43

## FILE:company/glossary.md
# Dow Jones — Glossary

Terms, abbreviations, and internal jargon used across Dow Jones and the product team.

## Products and brands

| Term | Meaning |
| --- | --- |
| WSJ | The Wall Street Journal |
| MW | MarketWatch |
| IBD | Investor's Business Daily (acquired 2021) |
| BIC | Barron's Investor Circle — premium subscriber community |
| WSJ+ | WSJ bundle subscription product; expands multi-brand access |
| Free Expression | New subscription vertical combining newsletter sign-up and free account creation (launched Dec 2025) |

## Internal platforms and systems

| Term | Meaning |
| --- | --- |
| Piano / Composer | Paywall and subscription management platform; used for targeting, A/B testing, and subscription flows |
| CAJ | Checkout and acquisition journey — the checkout platform |
| SubsHub | Subscription management hub (upsell, save offers, user profile). Also referred to as SubHub in some internal docs — SubsHub is the canonical name. |
| OneID / DJOP | Dow Jones unified identity platform — single authentication layer across all DJ products |
| Braze | CRM platform used for mobile and email marketing, in-app messaging |
| Optimizely | A/B testing and experimentation platform |
| Statsig | Experimentation platform |
| JPD | Jira Product Discovery — roadmap and status tracking tool |
| Mosaic | Internal subscription management platform. Handles mid-term subscription changes including cancel, refund, and repurchase flows. Being extended by the Clean Transitions initiative to support credit-based offer switching without a full cancel-repurchase cycle. |
| BRS | Billing and Revenue System — handles charge groups, payments, credits, refunds, and receipts |
| CSM | Core Subscription Management — manages subscription state, term calculations, pro-rating, and transitions between offers |
| Verint | CRM tool used by Customer Service agents to access and manage customer accounts |
| Watson | Dow Jones offer targeting engine — returns eligible offers for a customer based on configured rules and directives |
| EDW | Enterprise Data Warehouse — central data storage and reporting system for product and business metrics |

## Process and planning

| Term | Meaning |
| --- | --- |
| RAG | Red / Amber / Green — status health system for roadmap items (also includes "On Hold") |
| LOE | Level of effort — engineering or design estimate |
| T-shirt sizing | Effort estimation: S (2 weeks / 1 sprint), M (6 weeks / 3 sprints), L (whole quarter) |
| Triad | The core product delivery unit: PM + Design + Engineering working together |
| CMO | Central Marketing Org — primary consumer stakeholder, accountable for subscription targets |
| DSAR | Data Subject Access Request |
| ROPA | Records of Processing Activities (GDPR Article 30) |
| DPIA | Data Protection Impact Assessment (GDPR Article 35) |
| IFE | In-Flight Entertainment (used in context of Delta partnership) |

## Metrics and data

| Term | Meaning |
| --- | --- |
| ARPU | Average Revenue Per User |
| CVR | Conversion rate |
| Churn | Rate at which subscribers cancel or lapse |
| Paywall impression | A user encounter with a paywall prompt |
| Save offer | A retention offer presented to a subscriber who is attempting to cancel |
| Win-back | Reacquisition offer targeting lapsed/cancelled subscribers |
| Crawl coverage | Percentage of priority content successfully crawled by search engines |
| Crawl waste | Percentage of crawl budget spent on non-priority pages |

## Customer journey stages

| Stage | Owned by |
| --- | --- |
| Traffic & Audience Growth | SEO |
| Registration & Nurture | Subscriber Acquisition |
| Conversion | Subscriber Acquisition |
| Activation | Subscriber Engagement, Revenue & Retention |
| Engagement & Revenue | Subscriber Engagement, Revenue & Retention |
| Retention & Win-back | Subscriber Engagement, Revenue & Retention |

## FILE:company/overview.md
# Dow Jones — Company Overview

## About

Dow Jones is a global provider of news, data, and analytics. It is a subsidiary of News Corp. Dow Jones publishes some of the world's most influential business and financial media across consumer subscription brands including The Wall Street Journal, Barron's, MarketWatch, and Investor's Business Daily.

This context repo covers the B2C (consumer) side of the Dow Jones business. B2B products (Factiva, Risk & Compliance, Newswires, DJ Platform) are out of scope.

As of the March 2026 Investor Briefing, Dow Jones described itself as a "news, data and intelligence powerhouse" — with authoritative editorial positioned as an essential input for the AI era.

## Financial highlights (FY2018–FY2025)

- Revenue base: **82% digital** (up from 60% in FY2018), **80% recurring** (up from 69%)
- **17% compound annual segment EBITDA growth** since FY2018
- Segment EBITDA margin: **25.2%** (nearly doubled since FY2018)
- Dow Jones has driven **11 successive quarters** of year-over-year Total Segment EBITDA growth at News Corp

## $1B EBITDA target

At the March 2026 Investor Briefing, News Corp detailed a pathway to **$1 billion in annual Dow Jones segment EBITDA within five years**, driven by:

- Accelerating Risk & Energy businesses (margin expansion)
- Accelerating direct-to-consumer offerings with new products and pricing
- Sharp focus on high-margin enterprise news
- Continuing cost discipline and operating leverage

## Key consumer brands

- **The Wall Street Journal** — flagship B2C subscription product; one of the largest paid digital news publications in the US
- **Barron's** — financial and investment news
- **MarketWatch** — real-time financial news and market data
- **Investor's Business Daily (IBD)** — acquired 2021
- **WSJ Pro** — premium vertical journalism for professionals
- **WSJ+** — multi-brand bundle subscription (WSJ, Barron's, MarketWatch, IBD)

## Headquarters

New York, NY (primary). Part of News Corp.

## Ownership

Subsidiary of News Corp (NWSA / NWS).

## Leadership

| Name | Title |
| --- | --- |
| Almar Latour | CEO, Dow Jones |
| Artem Fishman | CTO |
| Scott M. Havens | Chief Growth Officer & Global Head of Consumer |
| Emma Tucker | Editor in Chief, WSJ |
| Ryan Daly | SVP, Consumer Product |

## Competitive landscape

Dow Jones competes with FT, Bloomberg, NYT, and specialist financial media for digital subscribers.

## FILE:company/strategy.md
# Dow Jones — Strategy

## Strategic pillars

- **Subscription-first** — Consumer revenue is driven by paid digital subscriptions across WSJ, Barron's, MarketWatch, and IBD
- **Bundle growth** — WSJ+ bundle strategy is a key growth lever, expanding multi-product subscriptions across brands
- **AI as a monetization layer** — Dow Jones positions its authoritative editorial as an essential input for large AI models; licensing and AI product revenue are an expanding opportunity
- **Identity and first-party data** — The authentication and identity layer (OneID) is increasingly strategic, underpinning personalisation, bundling, and first-party data strategy
- **SEO and organic acquisition** — SEO is a primary top-of-funnel channel for WSJ and MarketWatch; positioning DJ properties for discovery via both traditional search and AI platforms

## North Star narrative (from March 2026 Investor Briefing)

Dow Jones frames itself as an **"Input company"** in the Age of AI — drawing an analogy to semiconductors and energy as inputs to the physical world. Authoritative editorial, trusted data, and proprietary risk/compliance intelligence are inputs to the digital and AI world. This framing underpins licensing deals with AI model providers and DJ's broader enterprise strategy.

> "As AI models are rippling from industry to industry, their output is only as good as their input, which is where Dow Jones comes in." — Almar Latour, CEO Dow Jones, March 2026

## Key strategic dynamics

- Platform team remit means solutions need to work across multiple brands and surfaces, not just solve for one
- Legal, privacy, and InfoSec reviews are standard for anything touching identity or billing
- Success metrics connect to subscription KPIs: paywall impressions, conversion rate, subscriber acquisition, churn, ARPU

## Competitive landscape

| Competitor | Where we compete |
| --- | --- |
| Financial Times | Business/financial news subscriptions |
| Bloomberg | Financial data, news, and professional terminals |
| New York Times | Digital news subscriptions, general audience |
| Specialist financial media | Vertical professional publications |

## FILE:goals/FY2026/priorities.md
# FY2026 Priorities — Commerce Product

> FY26 = July 2025 – June 2026
> Last updated: 2026-03-20

## Subscriptions priorities

- **Registration growth** — Grow monthly new free registered users from 20k to 135k
- **Conversion optimisation** — 10–15% incremental conversion lift via A/B testing program
- **Bundle growth** — Grow WSJ+ bundle subscriptions from 1M to 1.15M; deliver $80M bundle revenue
- **Early-life engagement** — Improve avg active days in subscriber's first 7 days (3.9 → 4.3)
- **Retention** — 10–15% lift in save offer take rate
- **New verticals** — Launch commerce surfaces for Free Expression, Connected paywall, Puzzles
- **Delta Partnership** — ~360k subscriptions projected over 3 years

## SEO priorities

- **Traffic ranking** — Move WSJ from #8 to #6 in share of traffic vs. competitors
- **Crawl coverage** — Improve from 55% to 65% (exceeded: hit 74% in Q2)
- **Crawl waste** — Reduce from 30% to 20% (at risk: at 49% in Q2)
- **Programmatic SEO** — Market data pages, topic pages, earnings calendar (MarketWatch)

## Identity priorities

- **OAuth2/OIDC** — Reach 100% token-based access across all products (baseline: 80%)
- **Data hygiene** — Delete ~2.3M inactive accounts (6+ years)

## Cross-team priorities

- In-app Meter — registered users get free articles on app
- Self-serve Corporate Sales shop page ($200k+ Q4 target)

## Notes

Last updated: 2026-03-20

## FILE:goals/FY2026/technology-okrs.md
# Technology FY26 OKRs

> Source: Technology FY26 OKR Tracker
> FY26 = July 2025 – June 2026 | Last updated: 2026-03-20

---

## Grow Subscriptions

### KR: Grow digital subscriptions
**Target:** Q4 average of 6.5M DJ digital subs (WSJ 4.3M)
**Owner:** Dan | **Tech Exec:** Ryan | **ETA:** Q4 | **Status:** TBC

---

### KR: Strengthen paywall strategy — registration growth
**Target:** +10% incremental conversions and 6x monthly registration growth (20k → 120k) by EOFY26
**Owner:** Dan | **Tech Exec:** Ryan | **ETA:** Q4 | **Status:** At Risk

---

### KR: Drive consumer engagement +15% (app weekly subscriber time spent)
**Target:** 1:02:05 → 1:11:24 overall app weekly subscriber time spent by EOH2 (via WSJ Redesign — Media & MyWSJ in H1)
**Owner:** Ryan | **ETA:** H1 | **Status:** Off Track

---

## FILE:goals/company-okrs.md
# Company OKRs — FY26

> FY26 = July 2025 – June 2026
> Last updated: 2026-03-20
> Full Technology OKR tracker: `goals/FY2026/technology-okrs.md`
> Commerce product OKRs: `goals/product-okrs.md`

---

## Top-line subscription targets (FY26)

| Metric | Target |
| --- | --- |
| DJ digital subscriptions | 6.5M (Q4 avg) |
| WSJ digital subscriptions | 4.3M (Q4 avg) |
| Monthly registered users | 120k cumulative |
| App weekly subscriber time spent | 1:11:24 |

---

## Technology OKR summary (FY26)

| OKR | Owner | Status |
| --- | --- | --- |
| Grow digital subs to 6.5M DJ / 4.3M WSJ | Dan / Ryan | TBC |
| Paywall — +10% conversion lift; 20k → 120k monthly registrations | Dan / Ryan | At Risk |
| Consumer engagement +15% app weekly time spent | Ryan | Off Track |

---

## FY27 strategic directions

1. Return to net positive subscriber growth (currently negative net new in volume)
2. Focus on engagement frequency (not time on site) as north star
3. Bolster core digital subscription with new value for new audiences (Games, Sports, Market Data)
4. Boost quality traffic with high subscription propensity (SEO/Audience team)

## Notes

Last updated: 2026-03-20

## FILE:goals/product-okrs.md
# Commerce Product OKRs

> FY26 = July 2025 – June 2026 | FY27 = July 2026 – June 2027
> Last updated: 2026-03-20

## FY26 OKRs — Status as of Q3

### Subscriptions

| OKR | Target |
| --- | --- |
| Grow monthly new free registered users | 20k → 135k |
| Incremental conversion lift from A/B testing | +10–15% |
| Deliver bundle revenue | $80M (from $68M) |
| Grow bundle subscriptions | 1M → 1.15M |
| Improve early-life engagement | 3.9 → 4.3 avg days (first 7) |
| Improve save offer take rate | +10–15% lift |

### SEO

| OKR | Target |
| --- | --- |
| WSJ share of traffic ranking | #6 (from #8) |
| Crawl coverage of priority content | 55% → 65% |
| Reduce crawl waste | 30% → 20% |

### Identity

| OKR | Target |
| --- | --- |
| OAuth2/OIDC token-based access | 100% (baseline: 80%) |
| Reduce inactive accounts (6+ years) | 0 remaining (baseline: 2,337,801) |

---

## FY27 OKRs — Draft

> Status: Draft — targets TBC pending input from Head of Growth and the business
> FY27 runs July 2026 – June 2027

### O1: Return to net subscriber growth
- KR1: Achieve net positive new subscriber volume by end of Q2, sustained through Q4
- KR2: Reduce voluntary churn rate through improved save and cancellation flows
- KR3: Reduce involuntary churn through billing recovery and payment failure intervention
- KR4: Improve paywall-to-checkout conversion rate through checkout improvements and experimentation

### O2: Build engagement habit through feature adoption and onboarding
- KR1: Increase share of new subscribers using core features within their first 30 days
- KR2: Improve 90-day retention rate among subscribers completing onboarding vs. those who don't
- KR3: Increase average experiment-driven lift in feature adoption rate across onboarding and in-app product marketing
- KR4: Increase share of active subscribers with 2+ active days per week (directional)

### O3: Build subscriber funnels for new subscription products
- KR1: Acquire new subscribers via Games and Market Data entry points by Q4
- KR2: Achieve target % of bundle upgrades completed via in-app purchasing by Q4
- KR3: Achieve target % of net new subscribers acquired via non-news entry points by end of FY27
- KR4: Achieve new registrations/subscribers via MarketWatch by Q4

### O4: Grow and convert the registered user base
- KR1: Grow monthly new free registrations to target by Q4
- KR2: Improve registered-to-paid user conversion rate
- KR3: Increase opt-in rate for lifecycle marketing channels among new registrants

### O5: Increase revenue per subscriber (ARPU)
- KR1: Achieve household subscription target by Q4, with price resilience rate higher than single-user plans
- KR2: Drive incremental WSJ+ Marketplace revenue by Q4
- KR3: Increase average revenue per subscriber across WSJ, Barron's, and MarketWatch

### FY27 dependencies (owned outside Subscriptions)
- Notifications/alerts hub — habit driver; owned by app/platform teams
- Newsletters in-app — owned by editorial product
- App performance (reliability, speed, offline mode) — owned by platform/engineering
- Content features (personalization, video, AI summaries) — owned by editorial/newsroom product
- Community features (commenting, Circles, Live QAs) — ownership TBC

## FILE:products/barrons/metrics.md
# Barron's — Metrics

## Primary KPIs

| Metric | Definition | Current value | Target |
| --- | --- | --- | --- |
| [Add] | [Add] | [Add] | [Add] |

## Notes

<!-- Caveats, data sources -->

## FILE:products/barrons/overview.md
# Barron's — Overview

## What it is

Barron's is a financial and investment news publication focused on market analysis, stock picks, and investment ideas. It has a long print heritage and a growing digital and mobile presence.

## Audience

- Individual investors and wealth managers
- Professionals in financial services
- Sophisticated retail investors

## Business model

Subscription-first, with advertising. Shares commerce infrastructure with WSJ. Part of the WSJ+ bundle.

## Key Commerce surfaces

- Paywalls — Piano / Composer
- Shop pages — CAJ checkout
- Barron's Investor Circle (BIC) — premium subscriber community; integrated with OneID and BigMarker livestream platform
- Barron's Mobile App NextGen — new app with Commerce surfaces (Q4 FY26 initiative)

## FILE:products/barrons/products.md
# Barron's — Product Inventory

A reference guide to the discrete products and features owned by the Barron's product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers Barron's-owned consumer experiences.

---

## Core Digital Products

### Barrons.com
The primary web destination for Barron's editorial content and subscriber experience.

- Covers market analysis, stock picks, investment ideas, fund rankings, and financial commentary
- Authenticated experience for subscribers; metered/paywalled for anonymous users
- Key sections: Stocks, Funds & ETFs, Bonds, Options, Retirement, Personal Finance, Economy
- Piano Composer-powered paywall; CAJ shop pages and checkout for subscription purchase

### Barron's iOS App
The native iPhone and iPad application for Barron's subscribers.

- Full editorial content access with offline reading capability
- Push notifications for market-moving stories and subscriber alerts
- In-app subscription purchase via Apple IAP
- Next-gen app rebuild in progress (Q4 FY26 initiative) to bring Commerce surfaces and improved UX

### Barron's Android App
The native Android application for Barron's subscribers.

- Feature-parity with iOS app; distributed via Google Play Store
- In-app subscription purchase via Google Play billing
- Part of next-gen app rebuild initiative

---

## Markets & Data

### Stock Picks & Ratings
Barron's proprietary stock analysis and ratings, a core differentiator for the brand.

- Long and short recommendations with thesis summaries
- Historical picks performance tracking
- Integrated with editorial content; a primary subscriber value driver

### Barron's Stock Screener
A tool for filtering and discovering stocks based on financial criteria.

- Available to subscribers as part of the investing tools suite
- Filters by sector, valuation, performance, dividend yield, and other metrics

### Market Data (Quotes & Watchlists)
Real-time and delayed market data embedded across Barrons.com and the app.

- Stock, ETF, mutual fund, and index quotes
- Personal watchlist creation and management for registered and subscribed users
- Company pages with financials, news, and analyst coverage

---

## Newsletters

### Barron's Daily
The flagship daily newsletter covering market movers, top stories, and investment ideas.

- Sent weekday mornings to subscribers and registered users
- High-intent financial audience; strong engagement rates

### Barron's Weekly
A weekend digest of the week's top picks, analysis, and market outlook.

- Mirrors the print magazine cadence
- Focuses on longer-form investment ideas and commentary

### Other newsletters
Topic-specific newsletters including income investing, ETF focus, and options coverage. Full list managed by the Editorial Newsletters team.

---

## Community & Events

### Barron's Investor Circle (BIC)
A premium subscription tier from Barron's, positioned as an "inner circle" for serious investors seeking an edge in the markets.

- Exclusive early access to stock picks and deeper research from Barron's analysts before wider publication
- Premium article experience with integrated market data analysis for deeper investment research
- Live and on-demand events with Barron's stock pickers, editors, and analysts, including Q&A access, powered by BigMarker
- Available as a standalone Barron's subscription or bundled with MarketWatch; three pricing tiers offered
- Integrated with OneID for subscriber authentication and entitlement verification
- Differentiator vs. competitors; targets high-intent investors willing to pay a premium for market intelligence

### Barron's Live Events
In-person and virtual conferences and roundtables for institutional and individual investors.

- Flagship event: Barron's Top 100 Financial Advisors Summit
- Additional events covering retirement, markets, and investment themes
- Ticket access often tied to subscription tier or separate purchase

---

## Print

### Barron's Magazine (Print)
The weekly print edition, one of the longest-running financial publications in the US.

- Published weekly; distributed via mail subscription and newsstand
- Print subscribers are managed in Mosaic alongside digital
- Print delivery management available via Subscriber Hub

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| Barrons.com & apps | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| Barron's iOS/Android apps | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Investor Circle (BIC) | OneID (auth), BigMarker (livestream platform) |
| Market Data | Third-party data providers (Factset and others) |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Print subscriptions | Mosaic (subscription management), Subscriber Hub |

## FILE:products/commerce/metrics.md
# Commerce — Metrics

## Primary KPIs

| Metric | Definition | FY26 target |
| --- | --- | --- |
| Monthly new free registered users | New free accounts created per month | 135k (from 20k baseline) |
| Conversion rate lift from A/B testing | Incremental conversion lift across experiments | +10–15% |
| Bundle subscriptions | Number of subscriptions in a bundle | 1.15M (from 1M) |
| Bundle revenue | Total revenue from bundle subscriptions | $80M (from $68M) |
| Early-life engagement | Avg active days in subscriber's first 7 days | 4.3 days (from 3.9) |
| Save offer take rate | Lift in save offer acceptance from A/B testing | +10–15% |

## SEO metrics

| Metric | FY26 target |
| --- | --- |
| WSJ share of traffic ranking vs. competitors | #6 (from #8) |
| Crawl coverage of priority content | 65% (from 55%) |
| Crawl waste | 20% (from 30%) |

## Identity metrics

| Metric | FY26 target |
| --- | --- |
| OAuth2/OIDC token-based access coverage | 100% (baseline: 80%) |
| Inactive accounts deleted (6+ years) | 0 remaining (baseline: 2,337,801) |

## Key subscription metrics (definitions)

### Top line / subscription health

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| New Subscription Orders | Total subscription orders in a period | Total orders over period | Daily / Weekly / Monthly | Must Have |
| New Subscription Starts | Total subscription starts in a period | Total starts over period | Daily / Weekly / Monthly | Must Have |
| Subscription Stops | Subscribers who lose access within a timeframe | Total stops over period | Daily / Weekly / Monthly | Must Have |
| Subscription Cancellations | Subscribers who turn off auto-renew | Total cancellations over period | — | — |
| Net New Starts | Starts minus stops | Total Starts − Total Stops | Daily / Weekly / Monthly | Must Have |
| User Conversion Rate | Conversion rate of all non-subscriber traffic | Total non-sub users / Total Orders | Daily / Weekly / Monthly | Must Have |
| Avg starts per order | Average subscription starts per order | Total Starts / Total Orders | Daily / Weekly / Monthly | Nice to Have |
| Bundle take rate | % of orders including 2+ starts across WSJ+ brands | — | — | — |
| Daily / Weekly active users | Users active on site or app in a given period | — | Weekly / Monthly | Must Have |
| Active days in first 7 days | Days a user had a session of at least X mins within first week of subscribing | # of days with 1+ session in subscribed day + 6 | Weekly / Monthly | Must Have |
| Engagement bracket | Users grouped by active days in last 28 days: Dormant (0), Occasional (1–5), Light (6–10), Mid (11–15), Super (16+) | Group users by 28-day active day count | Weekly / Monthly | — |
| Churn rate | % of subscribers no longer active over a timeframe | Split by web/app, monthly/annual, product, promo/list | — | — |
| Save rate | Rate at which users entering the cancellation funnel accept a save offer | # save offer accepts / # users entering cancellation funnel | Weekly / Monthly | Must Have |
| Net Revenue Retention (NRR) | Holistic measure of MRR change accounting for expansion, contraction, and churn | (Starting MRR + Expansion MRR − Contraction MRR − Churned MRR) ÷ Starting MRR | — | Nice to Have |

### Paywall

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| Total paywall impressions | # of times a paywall is loaded on a page (roadblocks, scrims, snippets, in-situ, dual CTA, live coverage, etc.) | Total paywall loads via Piano | Daily / Weekly / Monthly | Must Have |
| Paywall hit rate | % of pageviews that include a paywall impression | Paywall Impressions / Total non-sub pageviews | Daily / Weekly / Monthly | Must Have |
| Paywall conversion rate | % of paywall impressions resulting in an order | Total Orders / Total Paywall Impressions | Daily / Weekly / Monthly | Must Have |
| Top paywall conversion stories | Top 10 stories driving conversions | Top 10 by conversion count | Yesterday / Last 7 days | Nice to Have |

### Registration

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| Accounts created | Total new user accounts created | Total new accounts | Daily / Weekly / Monthly | Must Have |
| Registration wall impressions | Total impressions of regwall units (dual CTA, registration roadblocks) | Total regwall units delivered by Piano | Daily / Weekly / Monthly | Must Have |
| Registration wall conversion rate | % of regwall impressions resulting in a registration | New accounts via regwalls / Total regwall impressions | Daily / Weekly / Monthly | Must Have |

### Acquisition and conversion

| Metric | Definition | Priority |
| --- | --- | --- |
| Shop page impressions | Views of a subscription shop page | — |
| Shop page → order conversion | Users completing an order from a shop page visit | — |
| Shop page → checkout start | Users beginning checkout from a shop page visit | — |
| Shop page unique visits | Unique visitors to a given shop page | — |
| ARPU | Average Revenue Per User — total revenue / total visitors; used especially for Optimizely experiment analysis | — |
| LTV projections | Projected lifetime revenue per visitor based on sales data and bundle mix | — |
| Cart abandon rate | Users who begin checkout but do not complete an order | — |

### Core product engagement (activation)

| Metric | Definition |
| --- | --- |
| Value exchange metrics | Engagement where user receives value: article reads, listens, watchlist reads, video watches, puzzle plays, newsletter reads |
| Customisation metrics | Engagement where user invests in product: follows, saves, watchlist adds, interest selections, comments, newsletter subscriptions |
| Content breadth | # of sections engaged with (unique sections per user in last 28 days) |
| Content completion rate | % of content completed — articles, listens, videos, podcasts, puzzles, newsletters |
| App/web and cross-device engagement | Combination of surfaces (desktop web, mobile web, tablet web, app) a user engaged with in last 28 days |
| Time to first value | Time from session start to first content engagement |
| Session initiation method | How users start sessions: direct, email, push notification |

### Retention

| Metric | Definition |
| --- | --- |
| 1st renewal churn rate | Users who churn at their first renewal point (split by web/app, monthly, product) |
| Promo-to-list churn rate | Users who churn after stepping up to list price |
| Voluntary vs. involuntary churn | Voluntary: users on auto-renewal who cancel. Involuntary: users not on auto-renewal who lapse. Payment failure target: 50% recovery. |
| Save offer | Retention offer presented to a subscriber attempting to cancel |
| Win-back | Reacquisition offer targeting lapsed/cancelled subscribers |

## Data sources

- B2C Analytics: Emily C Williams (Senior Director, B2C Analytics, reports to Mike Shaw SVP Data Engineering)
- Experimentation analysis: Data Science & Analytics team
- Roadmap status: Jira Product Discovery (JPD) — RAG health

## FILE:products/commerce/overview.md
# Commerce — Overview

## What it is

The Commerce team owns the full subscription lifecycle across Dow Jones consumer products. This includes acquisition, conversion, billing, identity, and retention — across WSJ, Barron's, MarketWatch, IBD, and related brands.

Commerce operates as a **platform team** — solutions typically need to work across multiple brands and surfaces.

## Team lead

**Daniel Hockley** — VP of Product, Commerce (Mar 2025–Present)
Reports to: Ryan Daly (SVP, Consumer Product)

## Teams within Commerce

| Team | Focus | Customer journey stage |
| --- | --- | --- |
| SEO | Organic search visibility and traffic acquisition across WSJ, MarketWatch, Barron's | Traffic & Audience Growth |
| Subscriber Acquisition | Paywalls, shop pages, checkout, registration, offers | Registration & Nurture → Conversion |
| Subscriber Engagement, Revenue & Retention | Onboarding, upsell, save offers, win-back, churn reduction | Activation → Engagement → Retention |
| Subscriber Mobile | Mobile app subscription commerce across iOS and Android | Spans acquisition through retention |
| Identity & Entitlements | Authentication, access control, user identity across all platforms and brands | Infrastructure layer |

## Customer journey framework

```
Traffic & Audience Growth → Registration & Nurture → Conversion → Activation → Engagement & Revenue → Retention & Win-back
        (SEO)                   (Reg, Newsletters)    (Paywall/Checkout)  (Onboarding)    (Upsell, CRM)      (Save offers, Win-back)
```

## Products

The Commerce team owns a portfolio of discrete applications and platforms spanning this journey. See `products.md` for the full inventory with descriptions and dependencies.

Key product areas:
- **Full-funnel infrastructure** — Mosaic (subscription platform), Automated Pricing (ML-driven personalized offers)
- **Acquisition** — Paywall & Onsite Placements, CAJ Shop Pages, CAJ Checkout, Free Registration, Newsletter Sign-up, Partner Landing Sites, WSJ+ Marketplace, Corporate Self-Serve Checkout
- **Engagement & Retention** — CAJ Subscription Onboarding, Subscriber Hub, Braze CRM
- **Identity & Access** — One Identity/OneID (AuthN), PIB Entitlements (AuthZ)
- **SEO** — HTML Sitemap/News Archive (plus XML Sitemap, Robots.txt, Topic Collection Pages)

## Key platforms and tools

- **Piano / Composer** — paywall and subscription management, A/B testing, onsite placement targeting
- **Mosaic** — core backend subscription platform (order processing, billing, fulfillment)
- **CAJ** — customer acquisition journey: checkout, shop pages, onboarding
- **SubHub (Subscriber Hub)** — subscriber self-service account management
- **OneID / DJOP** — unified identity and authentication platform across all DJ products
- **PIB Entitlements** — authorization and access control platform
- **Braze** — CRM, email, in-app messaging, push notifications
- **ActionIQ** — customer data platform (CDP) used for segmentation and targeting
- **Watson** — rules engine for offer targeting and save offers
- **Optimizely / Statsig** — A/B testing and experimentation
- **BRS** — billing and payment processing backend
- **JPD (Jira Product Discovery)** — roadmap and initiative tracking

## Strategic context

- Identity/authentication layer is increasingly strategic — first-party data, personalisation, and bundling all depend on it
- WSJ+ bundle strategy is a key growth lever — expanding multi-product subscriptions
- Legal, privacy, and InfoSec reviews are standard dependencies for anything touching identity or billing
- Platform team remit means solutions typically need to work across multiple brands and surfaces
- Checkout friction is a known gap vs. competitors (NYT, Bloomberg) — reducing drop-off is an ongoing investment
- Registered user base is a key growth area — free registrations act as a nurture layer before paid conversion

## FILE:products/commerce/products.md
# Commerce — Product Inventory

A reference guide to the discrete products and applications owned by the Commerce team. Grouped by area of the customer journey.

---

## Full-Funnel Infrastructure

### Mosaic
The core backend subscription platform underpinning all consumer acquisition, engagement, and retention across Dow Jones brands. Originally launched 2008 on Oracle technology, now fully cloud-based. Consolidates various subscription platforms and adheres to PCI, SOX, and GDPR requirements.

- Handles order processing, billing, entitlement fulfillment, and subscription lifecycle management
- Integrates with BRS (billing), Snowflake data lake, AWS, app stores (Google Play, iOS, Samsung), and payment processors (Apple Pay, PayPal, Amazon)
- Used by: all consumer brands (WSJ, Barron's, MarketWatch, IBD) and enterprise/partner subscribers

### Automated Pricing
A dynamic pricing system that uses machine learning models to deliver personalized subscription price points based on customer attributes, behavior, and market conditions.

- Operates across four journeys: acquisition (new subscribers), renewals (step-up pricing), saves (cancellation deflection), and winbacks (lapsed subscribers)
- ML models built and maintained by Data Science; rules engine (Watson) accepts customer parameters and surfaces appropriate offers
- Integrates with ActionIQ for email and social media delivery to external channels
- Owned jointly with Marketing Operations and Data Science

---

## Acquisition

### Paywall & Onsite Placements
The front-end experience controlling content access for non-subscribers and free registered users across consumer brand websites and apps.

- Built on Piano Composer for ruleset management, targeting, A/B test delivery, and in-built propensity scoring
- Supports multiple formats: roadblocks, scrims, in-situ paywalls, dual CTAs, snippet paywalls, live coverage paywalls
- Also manages registration walls (regwalls) that gate content behind free account creation
- Content Access is the backend system handling entitlement checks, OneID session handshake, article encryption/decryption, Automated Pricing integration, bot whitelisting, and Google Extended Access
- Revenue User Profile persists user profile data and enables segmentation via ActionIQ

### CAJ Shop Pages
Web-based subscription offer pages where users view, compare, and select subscription packages before proceeding to checkout.

- Mobile responsive; supports web-desktop, web-mobile, and in-app webview rendering for next-gen apps
- Shop page templates are built by CAJ engineering; CircOps can configure new pages with `?page=` params for campaign targeting
- Supports personalized offers via Watson (offer targeting), Automated Pricing, and A/B testing
- Serves all DJ brands with brand-specific theming

### CAJ Checkout
The checkout and payment experience for completing subscription purchases across all Dow Jones brands.

- Handles account creation, payment processing, and order confirmation
- Supports credit cards, Apple Pay, and PayPal; responsive across web, mobile web, and in-app webviews
- Brand-specific theming for WSJ, Barron's, MarketWatch, and IBD (IBD has a slightly different account creation flow)
- Key known friction: checkout takes ~3 minutes vs ~1 minute for competitors (NYT, Bloomberg); ongoing work to reduce drop-off

### Free Registration
A lightweight account creation experience for users coming from the paywall who don't yet have an account.

- Allows manual sign-up or social sign-in (Facebook, Google, Apple)
- Creates a registered user entitlement granting limited free article access across DJ brands for a defined period
- Acts as a nurture step before prompting users to subscribe
- In-article placement work ongoing to improve time-to-first-value

### Newsletter Sign-up
A minimal application allowing users to sign up for specific newsletters by submitting their email address.

- Supports both anonymous email entry and single-click sign-up for registered users
- Consistent experience across brands
- Surfacing additional newsletter sign-up opportunities in new areas is an active focus

### Partner Landing Sites (PLS)
A redemption and registration platform for subscribers who acquired access through third-party channels (corporate group sales, app stores, partnerships).

- Two main components: customer-facing redemption/registration flow and a Partner Admin Portal for managing licenses and seats
- Supports WSJ, Barron's, MarketWatch, Financial News London, Private Equity News, and Mansion Global
- Admin Portal enables bulk invitations, redemption tracking, and seat management for corporate partners
- Also serves as the entry point for app store subscribers who need to register a web account

### WSJ+ Marketplace
An exclusive in-subscription commerce hub where WSJ+ subscribers can discover and purchase additional premium Dow Jones products at subscriber-only rates.

- Consolidates supplementary products (newsletters, investing tools, educational resources) into a single place and a single bill
- Currently targets WSJ+ subscribers on every-4-week billing; annual subscriber expansion planned
- Partner content expansion (e.g. The Economist) in discussion
- Removes the fragmented purchasing paths that exist when users discover add-ons across different brand sites

### Corporate Self-Serve Checkout
A self-service purchase funnel for small to medium business customers buying WSJ group subscriptions (10-25 seats) without sales team involvement.

- Includes a corporate-focused marketing landing page and a streamlined checkout with seat selection
- Designed to remove friction in a traditionally long sales process
- Currently WSJ-only; expansion to other brands and products planned
- Integrates with existing corporate subscription management systems

---

## Engagement & Retention

### CAJ Subscription Onboarding
A guided post-purchase onboarding flow that helps new subscribers understand their benefits, set preferences, and take first steps toward engagement.

- Personalizes the experience based on interests, industries, and content preferences
- Prompts key activation actions: app download, newsletter subscriptions, feature education (watchlists, alerts)
- Also used for upgrade flows and CRM-triggered re-onboarding campaigns
- Optimized for Time to Value — getting subscribers to first meaningful content engagement quickly

### Subscriber Hub (SubHub)
A self-service account management platform for existing subscribers to manage subscriptions, billing, and account details across all DJ brands.

- Covers: payment updates, subscription upgrades/downgrades, cancellation, print delivery management, and customer support access
- Presents save offers (pricing alternatives, pauses) to subscribers attempting to cancel
- Aims to reduce calls to customer service by enabling self-service resolution
- Integrates with One Identity, Mosaic, Twilio, Genesys, and Watson

### Braze CRM
The primary marketing automation and messaging platform used to engage subscribers and prospects with personalized communications.

- Supports email, in-app messaging, push notifications, and content cards across web and mobile (iOS, Android)
- Integrates with ActionIQ (CDP) for audience segmentation and AppsFlyer for attribution tracking
- Used across: WSJ, Barron's, MarketWatch web and app platforms
- Migrating from previous solution (Airship) to Braze for mobile messaging

---

## Identity & Access

### One Identity (OneID) — AuthN
The authentication platform that creates, stores, and verifies user identities across all Dow Jones products.

- Assigns unique user identifiers used for cross-product tracking throughout the DJ ecosystem
- Supports persistent login, social sign-in (Facebook, Google, Apple), SAML/SSO, IP whitelisting, and token-based authentication (OAuth2/OpenID Connect)
- Stores PII and manages user sessions across web and mobile platforms
- Serves both B2C (WSJ, Barron's, MarketWatch) and B2B (Factiva, Risk & Compliance, Newswires, etc.) products
- Target: 100% token-based (OAuth2/OIDC) coverage across all products; currently ~85%

### PIB Entitlements (AuthZ)
The authorization platform that determines and enforces what content and features users can access based on their subscription level and organizational permissions.

- Manages entitlements for both consumer subscribers and enterprise/B2B users
- Handles complex subscription models, contractual rules, regional restrictions, and legal compliance controls
- Cross-product integration enables seamless content access across multiple DJ products in a single session
- Target: 100% entitlement coverage across all products; currently ~85% (some complex B2B platforms still migrating)

---

## SEO

### HTML Sitemap (News Archive)
A structured, crawlable directory of all WSJ content designed to maximize search engine crawl efficiency.

- Hierarchical structure (years > months > days > articles) provides access to all content within 5-6 clicks
- Includes orphaned content (videos, live coverage) not accessible from main navigation
- Pagination removed to reduce crawl waste
- Primary consumer is search engine crawlers; secondary use is archived content navigation for readers

> Note: The SEO team also owns XML Sitemap, Robots.txt, and Topic Collection Pages — see the SEO team section for full coverage.

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| All acquisition flows | One Identity (account creation/login) |
| All acquisition flows | Mosaic (order processing) |
| CAJ Checkout | BRS (billing), Mosaic, OneID |
| Paywall / Regwall | Piano Composer, Content Access, OneID |
| Automated Pricing | Watson (rules engine), Data Science ML models |
| Partner Landing Sites | OneID, PIB Entitlements |
| Subscriber Hub | Mosaic, OneID, Watson |
| Braze CRM | ActionIQ (CDP), AppsFlyer |
| WSJ+ Marketplace | CAJ Checkout, Mosaic, OneID |

## FILE:products/commercial-tech/products.md
# Commercial Technology — Product Inventory

A reference guide to the discrete products owned by the Commercial Technology team. Commercial Technology is a monetization-focused team within the Dow Jones B2C org, separate from Commerce. It owns the ad products, ad infrastructure, privacy platform, and internal tooling that power advertising across Dow Jones properties (~$300M+ digital advertising business).

---

## Ad Products

### SafeSuite
A set of brand safety and suitability tools that help advertisers avoid unsafe or misaligned content environments, ensuring campaigns run against trusted, high-quality inventory.

### Thematic AI
An AI-driven audience and content understanding product that identifies themes, topics, and intents in Dow Jones content and user behavior to power more precise targeting and insights.

### Theme Definer
A classification and taxonomy tool that standardizes how content and audiences are grouped into "themes," enabling consistent targeting, reporting, and packaging across products and campaigns.

### Dynatic
A dynamic advertising and experience product that uses data signals and creative rules to tailor ad experiences and placements, improving relevance and performance for advertisers.

### Ad Formats
A suite of proprietary ad formats for direct-to-subscriber experiences. Formats include Hero, Titan, Folio, VStudio, and Mosaic, as well as vertical and horizontal video (VAST/VPAID), native desktop/app placements, and a Dynamic Market Data Tool that integrates live financial data into ad creatives.

- Targets readers and subscribers directly; enables campaign-specific KPIs and custom executions
- Used by MMS Sales; an alternative to internal DJ Design/Consulting for custom advertising

---

## Ad & Privacy Platforms

### Ad Platform
Core ad-serving and configuration infrastructure that standardizes how ads are requested, rendered, and managed across Dow Jones properties. Includes shared components such as the Universal Ad Component and Orchestrator, plus Geneva for centralized ad configuration.

### Privacy Platform (DJCMP)
The Dow Jones Consent Management Platform middleware that sits between third-party CMPs (e.g. Sourcepoint / IAB SDK) and Dow Jones products. Provides a unified API and framework to enforce consent, vendor management, privacy notices, DSARs, and data retention across stacks and brands.

### Newsletters Ad Platform (NAPL)
An advertising platform for native ads in newsletters. Manages newsletter ad inventory, targeting, tracking, and campaign execution across brands — giving Sales and Ad Ops a consistent way to sell, deliver, and report on newsletter ad products.

---

## Information Systems

### InSite
A proprietary first-party data-powered audience analytics suite. Marries data from Adobe (web analytics), Google Ad Manager (ad server), and the Dow Jones CDP to provide audience-based insights not available from any single platform.

- **Pre-sale:** Provides first-party data insights to quantify and support specific product pitches to advertisers
- **Post-sale:** Delivers campaign/line item/creative audience performance metrics for mid-campaign optimisation and end-of-campaign reporting
- **Content Insights:** Leverages audience data from previous campaigns to refine renewal discussions and future pitches
- Used by Planning, AdOps, RevOps, Performance, Sales, and Client Success across MMS

### Seawolf
An internal product that protects the advertising exchange business via stewardship and execution controls. Addresses the gap in the Order Management System for exclusive sponsorship coordination and campaign health monitoring.

- **Buyout Calendar:** Allows the DOCS team to manage bookings with an accurate picture of buyout availability for exclusive sponsorships (e.g. homepage takeovers). Augments the OMS with "holds" to eliminate reliance on email/Slack for cross-team coordination across hundreds of exclusive products
- **Cadence:** Monitors active campaigns against pre-launch requirements and in-flight thresholds; proactively alerts AdOps when intervention is needed rather than discovering issues after the fact
- Key outcome: near-zero makegoods due to double-booking; alerts responded to in a timely manner

### Monty
An in-house tool that allows Sales to independently build contracts and generate real-time quotes for advertising deals without relying on Planning — enabling faster deal closure and more efficient use of people.

- **Monty (Digital):** For digital advertising deals; Sales can create contracts for simpler clients independently
- **Print Monty:** Equivalent tool for print advertising deals
- Metrics tracked: average time to create a deal, percentage of deals using Monty, YoY revenue, average deal size, win rate

### DASH
An internal advertising data and operations system built on Tableau. Aggregates data from multiple source systems (Google Ad Manager, AdBook, IAS, Megaphone, etc.) into a single interface for campaign performance monitoring and end-of-campaign reporting.

- Supports the MMS teams across Planning, AdOps, RevOps, Performance, Sales, and Client Success
- Under evaluation for potential deprecation if Looker meets all MMS use cases

### WSJBG Ad Manager (DanAds)
Previously known as DanAds and WSJ Ad Manager. A self-serve advertising platform powered by the DanAds platform, enabling advertisers and agencies to plan, buy, and manage campaigns directly — without IO processing or managed-service involvement.

- Primary audience: advertisers and agencies (new and existing), particularly SMB advertisers who would be turned away by Direct Sales due to budget size or bandwidth
- Supports credit card and invoicing payment options; real-time campaign management and optimisation
- Secondary audience: MMS Sales team (Client Associates, Associate Client Partners, Client Partners)
- Competes with programmatic platforms (Google, Meta, LinkedIn) for SMB ad budgets

### Looker
The business intelligence and analytics layer for Commercial Technology. Connects to Snowflake and provides curated dashboards and data models for advertising, revenue, and operations across MMS teams.

- Platform partner: Google (Looker Core)
- Primary users: Planning, Performance, AdOps; secondary users: Sales, Client Success, RevOps
- Positioned to replace DASH as the single BI tool for MMS if it meets all use cases
- Supports monitoring and analysis of campaign performance, internal insights, and client-facing reporting

## FILE:products/fnlondon/metrics.md
# Financial News London — Metrics

<!-- Add KPIs, subscriber counts, traffic benchmarks, and success definitions here -->

## Key metrics to track

- Digital subscriber count
- Subscription revenue
- Monthly unique visitors
- Newsletter open rates
- Awards/events attendance and revenue

## Notes

FN is a niche B2B-adjacent consumer product. Success metrics are less focused on mass volume and more on subscriber quality and retention among high-value finance professionals.

## FILE:products/fnlondon/overview.md
# Financial News London — Overview

## What it is

Financial News (FN) is a premium London-based digital and print publication covering the wholesale financial services industry in the UK and Europe. Effectively the trade paper for the City of London. Founded in 1996 by Angus MacDonald and John Benson; acquired by Dow Jones in 2007 for approximately £79 million. Sits within the Barron's Group division of Dow Jones alongside Barron's, MarketWatch, and Mansion Global.

Note: FN is a separate entity from the original *Financial News* founded in 1884 (which merged with the Financial Times in 1945).

## Audience

- Finance professionals in the City of London and broader European financial services sector
- Over 54% of readers are in senior management (C-suite, MDs, board members)
- Average reader income is high — exceeds the general finance professional population
- Key sectors: investment banking, asset management, private equity, regulation
- UK and Europe-primary; international readers in financial services

## Business model

Subscription-first with hard paywall, reflecting a narrow, high-value professional audience.

- Individual subscriptions at a significant premium vs. consumer publications
- Corporate licenses are the primary revenue driver — over 178 major firms (banks, law firms, consultancies) hold enterprise-wide licenses

## Coverage areas

- Investment banking: deals, M&A, IPOs, capital markets activity
- Asset management: institutional investing trends, fund performance, ESG
- Private equity: operates a specialized daily service, *Private Equity News*, covering European buyouts
- The People section: senior appointments and departures across the City — one of FN's most-read features
- Financial regulation: FCA, EU/ESMA, Basel updates in real time

## Key products and features

- **FN 100**: annual list of the 100 most powerful people in European finance; highly influential as a status signal in the City
- **FN Awards**: prestigious annual ceremonies including Awards for Excellence in Investment Banking
- **Private Equity News**: dedicated daily coverage of European private equity
- **Newsletters**: Morning Briefing and sector-specific updates
- **Events**: high-level roundtables and conferences in London for industry leaders

## Relationship to Dow Jones / WSJ

- Sits within the Barron's Group division of Dow Jones; editorially independent with UK-centric voice
- Shares Commerce infrastructure: OneID (authentication), Mosaic (subscription management), PIB Entitlements
- Partner Landing Sites (PLS) supports FN for corporate/group subscriptions
- Serves as the European counterpart to WSJ Pro — regional depth complementing WSJ's global breadth
- **LSEG Partnership (2024):** Multi-year deal with the London Stock Exchange Group; FN content integrated into LSEG Workspace (Bloomberg-equivalent terminal), significantly expanding reach to terminal users
- Enterprise custom news dashboards combining FN and WSJ content available for corporate clients

## FILE:products/ibd/metrics.md
# IBD — Metrics

<!-- Add KPIs, subscriber counts, benchmarks, and success definitions here -->

## Key metrics to track

- Total subscriber count (across all tiers: Digital, MarketSmith, Leaderboard, SwingTrader)
- Revenue by product tier
- Subscriber retention / churn rate
- IBD Live viewership and engagement
- Stock list performance (used as a marketing and credibility metric)

## Notes

IBD's product portfolio is tiered — many subscribers enter at base Digital and upgrade to MarketSmith or Leaderboard. Upgrade rate and LTV per subscriber are important commercial metrics.

## FILE:products/ibd/overview.md
# Investor's Business Daily (IBD) — Overview

## What it is

Investor's Business Daily (IBD) is a financial news and research platform focused on helping individual investors identify leading growth stocks using a disciplined, data-driven system. Founded in 1984 by William O'Neil as *Investor's Daily*; transitioned to digital-first in 2016; acquired by News Corp / Dow Jones in 2021 for $275 million. Operates as a stand-alone brand within the Dow Jones segment alongside WSJ and Barron's.

## Audience

- Self-directed retail investors and momentum/growth traders — primarily US-based
- Investors following a rules-based approach to stock picking
- Financial professionals using IBD data and ratings
- Increasingly targeting novice investors as an entry point into the DJ ecosystem (via MarketDiem newsletter)

## Business model

Subscription-first with a tiered product ecosystem, from free content to premium tools. Dow Jones also offers an "Investor Bundle" combining IBD Digital, WSJ, and Barron's at a combined rate. IBD is considered a high-margin digital pillar within News Corp's broader strategy.

## The CAN SLIM Methodology

IBD's signature stock-picking framework, developed by O'Neil by studying every top-performing stock since the 1880s. Each letter stands for a criterion:

- **C** — Current quarterly earnings (25%+ growth)
- **A** — Annual earnings growth (25%+ over 3-5 years)
- **N** — New product, service, management, or price high
- **S** — Supply and demand (high volume on price breakthroughs)
- **L** — Leader or laggard (buy the top stock in the top industry)
- **I** — Institutional sponsorship (follow the "smart money")
- **M** — Market direction (trade only in a Confirmed Uptrend)

## Key products and features

### IBD Digital (Base subscription)
- Full access to IBD.com editorial content — actionable and educational, not general news
- IBD Stock Lists: IBD 50, Sector Leaders, IPO Leaders, Big Cap 20
- Stock Checkup: free tool; "traffic light" (Green/Yellow/Red) evaluation of any stock's health against CAN SLIM criteria; entry point for non-subscribers
- IBD Ratings (all on 1-99 scale): Composite Rating (combined score), EPS Rating, Relative Strength (RS) Rating, SMR Rating (Sales growth, profit Margins, Return on equity), Accumulation/Distribution Rating
- Industry Group Rank: IBD tracks ~197 industry groups ranked 1-197; CAN SLIM investors focus on top-ranked groups
- Market Trend page / The Big Picture: daily guidance on market direction (Confirmed Uptrend, Uptrend Under Pressure, Market in Correction) — one of IBD's most-read features
- **IBD 50 ETF (ticker: FFTY):** managed by Innovator ETFs, tracks the IBD 50 list; extends IBD's brand into passive investing

### MarketSurge (formerly MarketSmith — rebranded March 2024)
Premium stock research and charting tool. Includes:
- Algorithmic pattern recognition (cup-with-handle, flat base, double bottom, etc.) with automatic buy point identification
- Proprietary "The Ants" indicator: flags intense institutional accumulation before a stock breaks out
- Fundamental data screening, earnings estimates, and historical price/volume analysis

### Leaderboard
A curated, actively managed list of top growth stocks meeting CAN SLIM criteria, with real-time buy/sell annotations from IBD analysts.
- Includes specific entry points, stop losses, and profit targets
- Designed as a "plug-and-play" service for investors who want analyst guidance

### SwingTrader
Shorter-term trade ideas for active traders with holding periods of days to weeks.
- Distinct from Leaderboard's longer-term growth stock focus

### IBD Live
A daily interactive broadcast where IBD analysts screen stocks and analyze charts in real time.
- Available weekday mornings; subscriber add-on

### Newsletters
- The Big Picture: daily market analysis interpreting IBD's Market Trend signals
- IBD 50: weekly list of top-rated growth stocks
- MarketDiem: newer newsletter targeting novice investors with simplified daily trade ideas; onboarding funnel into the IBD ecosystem

## Relationship to Dow Jones

- Acquired by News Corp / Dow Jones in 2021 for $275M; operates as a stand-alone brand with editorial independence
- Shares Commerce infrastructure: OneID (login/identity), PIB Entitlements (access), Mosaic (subscription management)
- CAJ Checkout handles IBD subscription purchases (slightly different account creation flow vs WSJ/Barron's)
- IBD proprietary data increasingly used as "clean" training data for Dow Jones financial AI models
- Bundled with WSJ and Barron's in the Investor Bundle

## FILE:products/mansionglobal/metrics.md
# Mansion Global — Metrics

<!-- Add KPIs, traffic benchmarks, listings volume, and success definitions here -->

## Key metrics to track

- Monthly unique visitors
- Property listings volume and active listings
- Listing lead generation (agent/broker contact requests)
- Advertising revenue
- Newsletter subscribers and engagement
- Search-driven traffic (SEO is a significant channel)

## Notes

Mansion Global's primary revenue model is listings and advertising rather than subscriptions, so traffic and lead generation metrics are more central than subscriber count.

## FILE:products/mansionglobal/overview.md
# Mansion Global — Overview

## What it is

Mansion Global is a digital-first luxury real estate and lifestyle platform owned by Dow Jones (News Corp). Launched in May 2015, it combines a global luxury property listings database with editorial content covering market analysis, lifestyle, and investment advice. It sits within the Dow Jones Barron's Group alongside Barron's, MarketWatch, and Financial News.

## Audience

- High-net-worth and ultra-affluent individuals buying, selling, or investing in luxury property globally
- 52% of readers are millionaires; average household net worth $2.2M, average household income $433K
- International audience: over 53% of traffic is from outside the US (significant EMEA and APAC reach)
- Real estate agents and brokers in the luxury segment

## Business model

Primarily advertising and listings-revenue led — free to access for consumers. Revenue drivers:

- Real estate broker/developer listing packages (tiered pricing based on volume — small batches to large developer inventories)
- Newsletter sponsorships and market page advertising
- Print supplement sales ("Experience Luxury" magazine, sold through WSJ Shop)

## Coverage areas

- Luxury residential property listings worldwide
- Market analysis: prime markets (London, NYC, Dubai, Hong Kong) and emerging luxury destinations
- Lifestyle and design: architecture, interior design, historic preservation, home technology
- Financial and tax advice for international property buyers
- Multilingual content: English, Spanish, and Chinese

## Key products and features

- **Property search portal**: searchable global luxury listings database with Lifestyle Search (filter by Golf, Historic, Beachfront, etc.)
- **"Experience Luxury" magazine**: quarterly print supplement distributed with The Wall Street Journal
- **Mansion Global TV**: program on Fox Business Network showcasing luxury homes and lifestyle trends
- **Mobile app**: dedicated app for property browsing and real-time market news
- **Newsletters**: daily market updates and listing highlights; newsletter sponsorships are a revenue driver

## Relationship to WSJ and News Corp

- Editorially independent from WSJ but operates as a close partner; produces the "Experience Luxury" WSJ print supplement and shares content with WSJ's Mansion section
- Part of News Corp's Digital Real Estate Services segment — the most profitable News Corp segment as of 2025
- Cross-platform relationships within News Corp: Realtor.com (News Corp owns ~80%, Mansion Global provides luxury top-of-funnel content) and REA Group (News Corp owns ~61%, Australia's leading property site)
- Shares DJ commerce infrastructure: OneID, PIB Entitlements, Mosaic
- Partner Landing Sites (PLS) supports Mansion Global for corporate/group subscriptions

## FILE:products/marketwatch/metrics.md
# MarketWatch — Metrics

## Primary KPIs

| Metric | Definition | Current value | Target |
| --- | --- | --- | --- |
| [Add] | [Add] | [Add] | [Add] |

## Notes

<!-- Data sources, caveats -->

## FILE:products/marketwatch/overview.md
# MarketWatch — Overview

## What it is

MarketWatch is a real-time financial news and market data platform covering markets, personal finance, and economic news. It has a broader, more mass-market audience than WSJ or Barron's, with heavy digital and mobile usage.

## Audience

- Retail investors and personal finance readers
- Broader and more general than WSJ/Barron's
- High traffic, high mobile usage

## Business model

Historically advertising-led; subscription component growing. MarketWatch became a subscription product, and the Commerce team has been building out its subscription surfaces.

## Key Commerce surfaces

- Paywall — Piano / Composer
- Shop pages — CAJ checkout
- Candy bar (promotional unit) — hompage acquisition surface
- Earnings Calendar — SEO-driven traffic surface

## Recent Commerce wins (FY26)

- MarketWatch mobile shop optimisation — 12% improvement in conversion to checkout; increased bundle take rate
- Google Extended Access for Search launched on MarketWatch (Oct 2025)
- MarketWatch ChatGPT auth/entitlements (Dec 2025)
- Earnings Calendar Enhancements — Q4 FY26 initiative to drive organic traffic via SEO
- MarketWatch hard paywall — 15% lift in conversions (historical win)

## Notes

MarketWatch is a significant SEO traffic source. The team is exploring a refreshed MarketWatch app with commerce features as a FY27 investment. The candy bar homepage unit is an in-progress initiative to bring MarketWatch into parity with WSJ and Barron's as a subscription-first homepage experience (WSJ candy bar converts at 7.24% click-through to subscribe).

## FILE:products/marketwatch/products.md
# MarketWatch — Product Inventory

A reference guide to the discrete products and features owned by the MarketWatch product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers MarketWatch-owned consumer experiences.

---

## Core Digital Products

### MarketWatch.com
The primary web destination for MarketWatch, one of the highest-traffic financial news sites in the US.

- Covers real-time market data, financial news, personal finance, economy, and investing
- Historically advertising-led; now subscription-first with a hard paywall driving conversions
- High SEO-driven traffic — organic search is a primary acquisition channel
- Key sections: Markets, Investing, Personal Finance, Economy, Real Estate, Retirement, Crypto
- Piano Composer-powered paywall; CAJ shop pages and checkout for subscription purchase
- Google Extended Access enabled for Search (launched Oct 2025)
- ChatGPT auth/entitlements integration live (Dec 2025)

### MarketWatch Mobile App
The native iOS and Android application for MarketWatch subscribers.

- Real-time market data, news alerts, and portfolio tracking
- Higher mobile usage mix than WSJ or Barron's, reflecting a broader consumer audience
- In-app subscription purchase via Apple IAP and Google Play billing
- New app rebuild under consideration as a FY27 investment to bring Commerce surfaces and improved UX

---

## Markets & Data

### Real-Time Quotes & Market Data
Core market data product — the primary reason many users visit MarketWatch.

- Real-time and delayed quotes for stocks, ETFs, mutual funds, indices, futures, currencies, and crypto
- Company pages with financials, analyst ratings, news, and historical data
- Pre-market and after-hours trading data
- One of the most-trafficked sections of the site; significant SEO value

### Watchlists & Portfolio Tracker
Personal investment tracking tools for registered and subscribed users.

- Create and manage custom watchlists for any asset class
- Portfolio tracker for monitoring holdings, performance, and allocation
- Syncs across web and mobile app

### Earnings Calendar
A structured, data-rich calendar of upcoming and recent corporate earnings releases.

- Shows expected EPS, revenue estimates, and historical results
- Q4 FY26 initiative: enhancements to drive organic search traffic via SEO
- High-intent traffic source for investors; major SEO entry point for the brand

### Economic Calendar
A schedule of key macroeconomic data releases (Fed decisions, jobs reports, CPI, GDP, etc.).

- Covers US and international economic events
- Paired with editorial context and analyst expectations

### Crypto Coverage & Data
Real-time cryptocurrency prices, news, and market data.

- Coverage of Bitcoin, Ethereum, and major altcoins
- Integrated into main market data infrastructure

### Virtual Stock Exchange (VSE)
A free, real-time paper trading simulator — one of the largest of its kind. Users practice investing strategies with virtual money using live market data, with no real capital at risk.

- Live data from NASDAQ, NYSE, and AMEX; supports Market, Limit, and Stop orders
- Default starting balance of $1,000,000 virtual cash; game hosts can configure $10,000 to $25,000,000 starting capital
- Supports US stocks, ETFs, and mutual funds (NASDAQ, NYSE, AMEX); no options, futures, or crypto
- Trade types: Buy, Sell, Short Sell, Buy to Cover; some games implement 15-minute execution delays
- Game/contest mechanics: configurable margin trading, interest rates on cash/margin, volume limits, and simulated transaction fees
- Leaderboards ranked by Total Return or Sharpe Ratio (risk-adjusted performance); private password-protected games for classrooms
- Classroom/education use: teachers can restrict trading to specific sectors or symbols, set semester-aligned start/end dates; widely used in finance and economics curricula globally
- Completely free; no paywall (distinct from MarketWatch Premium subscription for journalism)
- Available on MarketWatch.com and integrated into the MarketWatch mobile app (iOS/Android) with full cross-platform sync
- Recent mobile additions (late 2025/early 2026): Pivot Support/Resistance indicators, Stop Loss Target Calculator, Strength Meter
- Key limitation: dividends are not automatically credited, slightly disadvantaging long-term buy-and-hold strategies in competitions

---

## Newsletters

### Need to Know
MarketWatch's flagship pre-market morning newsletter covering the day's key themes and market setup.

- Sent weekday mornings; high open rate among active investors
- Available to subscribers and registered users

### The Moneyist
Personal finance advice column and newsletter.

- Covers reader-submitted financial dilemmas across inheritance, family finances, and consumer rights
- Engaged, loyal readership; strong social sharing

### Other newsletters
Additional newsletters covering retirement (Retirement Weekly), real estate, and market data digests. Full list managed by the Editorial Newsletters team.

---

## Acquisition Surfaces

### Candy Bar (Homepage Acquisition Unit)
A persistent promotional unit on the MarketWatch homepage designed to drive subscription conversions.

- In-progress initiative to bring MarketWatch into parity with WSJ (which converts at ~7.24% click-through to subscribe)
- Prominent placement above the fold; targeted to non-subscribers and registered free users
- Managed by Commerce team; editorial and product collaboration

### MarketWatch Mobile Shop Optimisation
Ongoing work to improve the subscription purchase funnel on mobile web.

- 12% improvement in conversion to checkout achieved (FY26)
- Increased bundle take rate via optimized offer presentation

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| MarketWatch.com & app | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| MarketWatch app | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Quotes & Market Data | Third-party data providers (Factset and others) |
| Earnings Calendar | SEO infrastructure, HTML Sitemap |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Candy Bar / Acquisition | Piano Composer (targeting), Automated Pricing, CAJ Shop Pages |
| ChatGPT integration | OneID (auth), PIB Entitlements (access) |

## FILE:products/wsj/metrics.md
# The Wall Street Journal — Metrics

## Primary KPIs

<!-- What are the top metrics this product is measured against? -->

| Metric | Definition | Current value | Target |
| --- | --- | --- | --- |
| [Add] | [Add] | [Add] | [Add] |

## Secondary metrics

<!-- Supporting metrics that inform health of the product -->

| Metric | Definition |
| --- | --- |
| [Add] | [Add] |

## How we measure success

<!-- Context on measurement philosophy, data sources, and tooling -->
- Data sources: [Add]
- Reporting cadence: [Add]

## Notes

<!-- Caveats, known data quality issues, etc. -->

## FILE:products/wsj/overview.md
# The Wall Street Journal — Overview

## What it is

The Wall Street Journal is Dow Jones's flagship publication — a daily newspaper and digital platform covering business, finance, politics, and world news. It is one of the most widely read English-language business publications in the US, and one of the largest paid digital news subscribers in the US.

## Audience

- Business professionals, executives, and investors
- Subscribers across consumer (B2C) and enterprise (B2B)
- US-primary with significant international readership

## Business model

Subscription-first. Revenue from:
- Digital subscriptions (direct)
- Print subscriptions
- Advertising
- WSJ+ bundle (multi-brand subscription with Barron's, MarketWatch, IBD)
- Licensing / syndication
- Enterprise / site licensing

## Key Commerce surfaces

- Paywalls — managed via Piano / Composer
- Shop pages — CAJ checkout platform
- Registration flows — Free Expression (free account creation)
- WSJ+ Marketplace — exclusive commerce experience for WSJ+ subscribers
- In-app subscription flows — iOS and Android (Piano Composer-powered)

## Recent Commerce wins (FY26)

- WSJ+ Marketplace launch (Oct 2025)
- Free Expression Phase 1 launch (Dec 2025) — registration wall; 149.6% of Q1 target
- Annual offer default on WSJ app — annual take rate increased from ~25% to ~50%
- In-situ checkout now default — 12% CVR lift for WSJ paywall
- WSJ iOS Onboarding Markets Card (Jan 2026)

## Notes

WSJ is the primary brand for most Commerce product work. Solutions built for WSJ are typically extended to Barron's and MarketWatch.

## FILE:products/wsj/products.md
# WSJ — Product Inventory

A reference guide to the discrete products and features owned by the WSJ product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers WSJ-owned consumer experiences.

---

## Core Digital Products

### WSJ.com
The primary web destination for WSJ editorial content and subscriber experience.

- Covers news, markets, opinion, lifestyle, real estate, and arts coverage
- Authenticated experience for subscribers; metered/paywalled for anonymous users
- Personalization via saved searches, watchlists, topic follows, and reading history
- Supports both desktop and mobile web; responsive design
- Key sections: Markets, Economy, Politics, Tech, Business, Life & Work, Books, Real Estate, Style

### WSJ iOS App
The native iPhone and iPad application for WSJ subscribers.

- Full editorial content access with offline reading
- Breaking news push notifications and personalized news alerts
- Markets data: stock quotes, watchlists, portfolio tracking
- In-app subscription purchase via Apple in-app purchase (IAP)
- Piano Composer-powered paywall for non-subscribers
- Recent additions: Markets onboarding card (Jan 2026), annual offer default (~50% take rate)

### WSJ Android App
The native Android application for WSJ subscribers.

- Feature-parity with iOS app; distributed via Google Play Store
- In-app subscription purchase via Google Play billing
- Push notifications via Braze

---

## Markets & Data

### Markets Data (Quotes & Watchlists)
Real-time and delayed market data tools embedded across WSJ.com and the WSJ apps.

- Stock, ETF, mutual fund, index, and futures quotes
- Personal watchlist creation and management for registered and subscribed users
- Pre-market and after-hours data
- Company pages with financials, news, and analyst data
- Powered by data providers including Factset and others

### WSJ Markets Hub
A dedicated markets section within WSJ.com aggregating market news, data, commentary, and tools in one destination.

- Live market coverage, earnings results, and economic calendar
- Integrates editorial content with live data feeds
- Entry point for users interested in investing and financial markets

---

## Newsletters

### The Morning Briefing (What's News)
WSJ's flagship daily newsletter summarizing the top business and world news stories.

- Sent weekday mornings; high-volume, high-open-rate product
- Available to both registered (free) users and subscribers
- Primary acquisition and engagement channel for email

### WSJ Opinion Today
Daily digest of WSJ Opinion section editorial and commentary.

- Sent weekday mornings to opinion-interested subscribers
- Distinct audience from main news newsletter

### Markets AM / The 10-Point
Markets-focused morning newsletters for finance and investing audiences.

- Covers pre-market moves, key economic data releases, and overnight international news

### Other newsletters
WSJ operates a portfolio of topic-specific newsletters covering areas including real estate, tech (CIO Journal, WSJ Pro), personal finance (Your Money Briefing), and lifestyle. Full list managed by the Editorial Newsletters team.

---

## Audio & Video

### WSJ Podcasts
Audio products distributed via Apple Podcasts, Spotify, and WSJ.com.

- Flagship show: "What's News" (daily news briefing, morning and evening editions)
- Other shows: "The Journal" (flagship long-form), "Opinion: Free Expression", "Heard on the Street", "Tech News Briefing", "Your Money Briefing"
- Subscriber-exclusive episodes exist on some shows; most content is free to grow top-of-funnel audience

### WSJ Live Video & Streaming
Video content available on WSJ.com and apps.

- Live market open and close coverage
- Breaking news live streams
- Video explainers and documentary-style features
- Subscriber-gated for full archive; some clips are free

---

## Personalization & Discovery

### My News
A personalized news feed on WSJ.com and apps based on followed topics, companies, and people.

- Users can follow topics (e.g., Federal Reserve, AI, Apple) to surface relevant articles
- Integrates with editorial curation for a hybrid algorithmic and editorial feed

### Alerts & Notifications
A system allowing subscribers to create custom alerts for breaking news, followed topics, and market movements.

- Available as push notifications (mobile), email alerts, and in-app notifications
- Market alerts: price thresholds, earnings announcements, company news
- Delivered via Braze; preferences managed in account settings

### WSJ Search
Full-text search across all WSJ content, including archive access for subscribers.

- Supports filtering by date, section, author, and content type
- News archive accessible to subscribers; recent headlines visible to non-subscribers
- SEO-significant; organic search is a major traffic driver

---

## WSJ Pro (B2B-adjacent, consumer-facing)

### WSJ Pro Subscriptions
Premium subscription tiers targeting professionals in specific verticals (private equity, venture capital, central banking, cybersecurity, sustainability).

- Separate from WSJ+ consumer subscription
- Includes exclusive newsletters, events access, and in-depth industry coverage
- Sold via direct sales and self-serve; priced at a significant premium to WSJ+
- Managed by the Pro editorial and product team; some Commerce platform overlap for checkout and identity

---

## Games & Lifestyle

### WSJ Crossword & Puzzles
A daily crossword and puzzle experience for WSJ subscribers.

- Available on WSJ.com and in the WSJ app
- Competitive with NYT Games as a subscriber engagement and retention driver
- Introduced as a subscriber benefit to increase non-news engagement

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| WSJ.com & apps | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| WSJ iOS/Android apps | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Markets Data | Factset and third-party data providers |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Alerts | Braze, OneID user preferences |
| WSJ Search / Archive | HTML Sitemap (SEO crawl), Content Access (entitlement checks) |
| Personalization (My News, Watchlists) | OneID (user identity), subscriber entitlement data |

## FILE:teams/design/team.md
# Design Team

## Key contacts

| Name | Role | Area |
| --- | --- | --- |
| [Add] | [Add] | [Add] |

## Design system

<!-- What design system do we use? Where does it live? -->
- [Add]

## Notes

Last updated: [Add date]

## FILE:teams/engineering/team.md
# Engineering Team

## Key contacts

| Name | Role | Area |
| --- | --- | --- |
| [Add] | [Add] | [Add] |

## Team structure

<!-- How is engineering organized? By product? By platform? -->
- [Add]

## Notes

Last updated: [Add date]

## FILE:teams/org-chart.md
# Org Chart — Consumer Products, Dow Jones

> Last updated: 2026-03-20

## Full Consumer Products org (reports into Ryan Daly)

```
Ryan Daly — SVP, Consumer Products
│
├── Daniel Hockley — VP, Product Management (Commerce)
│   ├── SEO
│   │   └── Craig Casazza — Senior Product Director
│   │       └── Emily Schwartzberg — Senior Product Manager
│   ├── SUBSCRIPTIONS
│   │   ├── Katy Mastorakis — Senior Product Manager (Mobile Apps)
│   │   ├── Joe Stein — Product Manager II (Engagement, Revenue & Retention)
│   │   └── Leigh Hunt — Group Product Manager (Subscriber Acquisition)
│   │       ├── Shani Giersbach — Product Manager (Subscriber Acquisition)
│   │       └── Daniel Saxon — Product Manager II
│   └── IDENTITY
│       └── Adam Guttmann — Senior Product Manager
│
├── Robbie Sauerberg — VP, Product Management (WSJ / Barron's / MarketWatch / Consumer Platform)
│   ├── Nicholas Smolney — Senior Principal Product Manager
│   ├── Sian Barry — Product Manager II
│   ├── Caroline Albanese — Senior Principal Product Manager
│   ├── Lupe Rodarte — Senior Product Director
│   ├── Mikhail Dukhon — Principal Product Manager (Audience & Emerging Ad Platforms)
│   ├── Saurabh Uppal — Senior Product Manager (Mobile Platforms)
│   ├── Yolanda Parker — Senior Product Manager
│   ├── Cristhian Ruiz — CWR (Commercial Technology)
│   ├── Radhika Biradar — CWR (ETL Developer)
│   └── DESIGN (reporting into Robbie)
│       ├── Patrick Estanbouli — Sr Manager, Product Design
│       ├── Kyawt Thiri — Product Designer II
│       ├── Ying Chen — Product Designer I
│       └── Lauren Playford — Product Designer II
│
├── [OPEN HEAD] — VP, Product Management (WSJ) — reports to Ryan; Juan and Shema will report to this role
│   ├── Juan Velasquez — Senior Product Director (Wall Street Journal)
│   │   ├── Linus Li — Senior Product Manager
│   │   ├── Ruth Olumoroti — Product Manager I
│   │   └── John Channell — Senior Product Manager
│   └── Shema Kalisa — Senior Principal Product Manager (Wall Street Journal)
│       └── Noni Ghani — Product Manager I
│
├── Brett Krasnove — Senior Product Director (Wealth & Investing)
│   ├── Brendan Bryant — Senior Product Manager
│   ├── Grant Tunkel — Principal Product Manager
│   └── Kiersten Johnston — Senior Product Manager
│
└── DIRECT ICs (IBD / Consumer — report directly to Ryan)
    ├── Sidney Uttam — Product Manager II (sidney.uttam@investors.com)
    ├── Erin Low — Associate Product Manager (erin.low@investors.com)
    └── Courtney Freeman — Senior Product Manager (courtney.freeman@investors.com)
```

## Commerce leadership triad

| Discipline | People |
| --- | --- |
| Product | Daniel Hockley (VP) |
| Engineering | Ajith Ittan (VP), Ratheesh Nair (VP) |
| Design | Min Chung (VP), Jesús Gorriti (VP) |

## Key cross-functional partners

| Name | Role | Org |
| --- | --- | --- |
| Greg Ragon | SVP, Performance Marketing | Central Marketing Org |
| Sarah Hilston | VP, Global Acquisition & Paid Media | Central Marketing Org |
| Chris Stanco | VP, Engagement & Retention | Central Marketing Org |
| Belma Kolayli | Marketing Lead, Engagement | Central Marketing Org |
| Joanna Cipolla | Marketing Lead, Retention | Central Marketing Org |
| Sendi Vulaj | Marketing Lead, Revenue | Central Marketing Org |
| Lisa Checketts | Marketing PM | Central Marketing Org |
| Sridhar Maharna | PMO Director | Commerce Operations |
| Mushirah Kelley | Sr. Program Manager | Commerce Operations |
| Srini Kunamneni | Director, Engineering | Subscriptions |
| Thowfeeq Mustafa | Director, Engineering | Subscriptions / Identity |
| Krishna Venkatachalam | Sr Director, Engineering | Identity |
| Rajitha Sivaraman | Sr Director, Engineering | SEO |
| Rommel Rojas | Director, Product Design | Subs / SEO / Identity |
| Puneet Goel | VP Product, Platform | Platform |
| Emily C Williams | Senior Director, B2C Analytics | Data Engineering (reports to Mike Shaw, SVP) |

## FILE:teams/product/team.md
# Product Team — Commerce, Dow Jones

> Last updated: 2026-03-20

## VP

**Daniel Hockley** — VP of Product, Commerce (Mar 2025–Present)
Previously VP Product, Subscriptions (Sep 2024–Mar 2025)
Reports to: Ryan Daly (SVP, Consumer Product)

## Direct reports — managers

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Craig Casazza | Senior Product Director | SEO | Jul 21, 2025 |
| Leigh Hunt | Group Product Manager | Subscriptions – Subscriber Acquisition | Apr 13, 2020 |

## Direct reports — individual contributors

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Adam Guttmann | Senior Product Manager | Identity & Entitlements | Sep 2, 2025 |
| Katy Mastorakis | Senior Product Manager | Subscriptions – Mobile Apps | Apr 14, 2025 |
| Joe Stein | Product Manager II | Subscriptions – Engagement, Revenue & Retention | Jan 7, 2025 |

## Leigh Hunt's reports

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Shani Giersbach | Product Manager II | Subscriber Acquisition | Feb 2, 2026 |
| Daniel Saxon | Product Manager II | Subscriber Acquisition | Mar 10, 2025 |

## Craig Casazza's reports

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Emily Schwartzberg | Senior Product Manager | SEO | Feb 21, 2022 |

## Areas of ownership

| Area | PM(s) |
| --- | --- |
| SEO | Craig Casazza, Emily Schwartzberg |
| Subscriber Acquisition | Leigh Hunt, Daniel Saxon, Shani Giersbach |
| Subscriber Engagement, Revenue & Retention | Joe Stein |
| Subscriber Mobile | Katy Mastorakis |
| Identity & Entitlements | Adam Guttmann |

## FILE:teams/product/ways-of-working.md
# Ways of Working — Commerce Product Team

How the Dow Jones Commerce product team operates day to day.

## Team structure

Commerce operates as a **platform team** — serving both Consumer (B2C) and B2B sides of the business. Solutions typically need to work across multiple brands and surfaces.

## Leadership triad model

Every pod has a leadership triad with equal representation from Product, Engineering, and Design. The Commerce senior leadership triad:
- **Product:** Daniel Hockley (VP)
- **Engineering:** Ajith Ittan / Ratheesh Nair (VP)
- **Design:** Min Chung / Jesús Gorriti (VP)

## Quarterly planning

Commerce produces quarterly roadmaps aligned to annual OKRs. The planning process:

1. **Backlog review** — Product, Engineering, and stakeholders review existing backlog items and decide what to carry forward
2. **Force rank** — Stakeholders produce a force-ranked list of new and existing priorities
3. **LOE & capacity calculation** — Tech team produces high-level estimates; capacity calculated against available engineering sprints
4. **Roadmap proposal & alignment** — Tech, Marketing, Business, and Newsroom teams align on what is committed vs. backlogged

Each initiative is then:
- Categorised by objective (Acquisition, Retention, Revenue, Engagement, Identity, SEO, Enterprise)
- Assigned to a pod and PM
- Flagged for design dependency
- T-shirt sized (S/M/L) for Engineering and Design independently
- Assigned a deliverable type (Discovery / Design / Development / Backlog)

## Deliverable types

| Type | Meaning |
| --- | --- |
| Discovery | Product-led research; delivers problem statement, vision, solutions, ROI, and requirements |
| Design | Design & research delivers high-res, signed-off designs |
| Development | Engineering delivers code-complete, releasable product or feature |
| Backlog | Deferred — no work committed this quarter |

## T-shirt sizing

| Size | Duration | Sprints |
| --- | --- | --- |
| S | 2 weeks | 1 sprint |
| M | 6 weeks | 3 sprints |
| L | Whole quarter | ~3 months |

## Tracking tool

**Jira Product Discovery (JPD)** — status health tracked via RAG (Red / Amber / Green / On Hold)

## Working with marketing

The Central Marketing Org (CMO) is the primary consumer stakeholder. They are accountable for subscription targets and use Commerce products as one channel in an omni-channel strategy. Commerce and marketing teams are structured around the same customer journey stages: Acquisition, Engagement, Revenue, Retention.

## Key marketing partners

| Name | Role |
| --- | --- |
| Greg Ragon | SVP, Performance Marketing — overall marketing lead |
| Sarah Hilston | VP, Global Acquisition & Paid Media |
| Chris Stanco | VP, Engagement & Retention |

## Product philosophy

- Start with the problem, not the solution — work backwards, define and validate the problem first
- PRDs are thinking tools, not forms — writing forces clarity
- Collaborative by design — PRDs are built with the triad (PM, Design, Engineering), not handed down
- PRDs are living documents — maintained throughout development, not filed away after kickoff
- Shipping is an output, not an outcome — measure what changed in the world (subscriber growth, retention, engagement), not what the team delivered
- Use the double diamond — diverge to discover the problem fully, converge on solutions

## FILE:tech/data-sources.md
# Data Sources

Analytics platforms, data systems, and data tooling used across Dow Jones Commerce.

## Analytics leadership

| Name | Role | Reports to |
| --- | --- | --- |
| Emily C Williams | Senior Director, B2C Analytics | Mike Shaw (SVP, Data Engineering) |

## Key data and analytics teams

| Team | Role |
| --- | --- |
| B2C Analytics | Subscription performance data, experiment analysis |
| Data Science & Analytics | Experimentation analysis and insights; supports A/B test evaluation |
| Marketing Operations | Offer setup, onsite placements, CRM data |
| Data Engineering | Data pipeline dependencies |

## Subscription KPIs tracked

| Metric | Definition |
| --- | --- |
| ARPU | Average Revenue Per User |
| CVR | Conversion rate — % of paywall impressions resulting in subscription start |
| Churn | Rate at which subscribers cancel or lapse |
| Early-life engagement | Avg active days in subscriber's first 7 days |
| Bundle subscriptions | Number of subscriptions in a WSJ+ bundle |
| Bundle revenue | Total revenue from bundle subscriptions |
| Save offer take rate | % of subscribers presented with a save offer who accept it |
| Registered users | New free accounts created per month |
| Crawl coverage | % of priority content successfully crawled by search engines |
| Crawl waste | % of crawl budget spent on non-priority pages |

## Experimentation and testing

- Experiments run via **Optimizely** and **Statsig**
- Results analysis led by Data Science & Analytics team
- Statistical significance required before shipping experiment results

## Notes

Data quality: some FY26 OKR metrics (bundle revenue, bundle subscriptions) are noted as "metric TBC from business" — baseline definitions still being confirmed.

## FILE:tech/integrations.md
# Integrations

Key third-party systems and internal service dependencies.

## Third-party integrations

| Integration | Purpose | Team owner | Notes |
| --- | --- | --- | --- |
| [Add] | [Add] | [Add] | |

## Internal service dependencies

| Service | What depends on it | Team owner |
| --- | --- | --- |
| [Add] | [Add] | [Add] |

## Notes

## FILE:tech/messaging.md
# **Project README: Dow Jones Messaging Strategy & PANDA Migration (Updated Jan 2026\)**

## **1\. Executive Summary**

The Dow Jones messaging infrastructure is transitioning from legacy, brand-specific tech stacks toward a centralized, platform-agnostic architecture centered on **PANDA**.

* **Primary Mission**: Migrate all email products from **Campaign Monitor** to **Sailthru** by **December 31, 2027**, to satisfy contract exit requirements.
* **Current Progress**: As of January 2026, the project has established a production-ready foundation for automated and written newsletters, along with automated **Follow alerts**.
* **Migration Status**: Of the 138 products in scope for the year-end deadline, 15% are fully migrated and 15% are configured for production (awaiting onboarding). The remaining 70% require brand-specific template development or new centralized service logic.

## **2\. The Identity Foundation ("The Golden Key")**

* **PANDA**: Serves as the central orchestration engine and is the **future-state source of truth** for user management and subscription data.
* **ENS**: The legacy source of truth for email subscriptions, currently bridged to PANDA via a proxy to maintain data parity.
* **MEGA**: Legacy middleware that synchronizes data between ENS and Campaign Monitor.

## **3\. Organizational Ownership & Boundaries**

### **A. Messaging Team (Internal Domain)**

* **PANDA**: Core orchestration hub for content ingestion, template management, and delivery logic.
* **ENS**: Legacy subscription database.
* **MEGA**: Middleware syncing ENS to Campaign Monitor.

### **B. Partner Systems (Internal Tech Partners)**

* **Publishing Systems**: Owns **NewsPress** (internal CMS for newsletter/article content) and **Curation** (internal tool for manual programming and triggering).
* **Breaking News**: Includes the **WSJ Breaking News Tool** (used by newsroom/Opinion) and **BAT Tool** (MarketWatch), both communicating directly to Airship.
* **Brand Teams**: Vertical tech teams (web/mobile) integrating with ENS and Airship for preference management.
* **NAPL (Native Ads Platform)**: Internal tool for AdOps to program and deliver native ads content.

### **C. External Systems (Vendors)**

* **Sailthru (Zeta)**: Target ESP for all newsletter products.
* **Campaign Monitor (Marigold)**: Legacy ESP to be decommissioned by Dec 31, 2026\.
* **Airship**: Vendor for mobile and web push notifications, managed at the brand level.
* **Braze**: Used by Marketing for lifecycle journeys independently of PANDA.
* **Amazon SES**: Email delivery for B2B brands (Energy and Factiva).
* **Salesforce Marketing Cloud**: ESP for IBD mainstream newsletters (currently outside CM migration scope).
* **Pushly**: Limited implementation on MarketWatch for desktop alerts.

## **4\. The Six Use Cases (Plus One)**

1. **Written Newsletters**: Content is manually written as an article in NewsPress and triggered via Curation; requires high coordination and custom template development.
2. **Automated Newsletters**: Driven by pre-defined content queries (e.g., "Most Read") and delivered on a set schedule without manual assembly.
3. **Automated Alerts ("Follow")**: Real-time alerts for authors or topics; these were the first native PANDA/Sailthru use cases.
4. **Triggered Alerts (Breaking News)**: Manually triggered for urgent news; currently involves a fragmented workflow and manual email assembly.
5. **Transactional**: System-triggered communications (e.g., password resets) currently hard-coded within brand front-ends.
6. **Courses/Journeys**: Automated email series; content and logic will be hosted natively within Sailthru.
7. **Move to Marketing**: Non-editorial products targeted for hand-off to marketing platforms.

## **5\. B2B Messaging Landscape**

* **High-Priority Migration (Campaign Monitor)**: **Newswires** requires development of white-labeling and dynamic data configurations for organization-level metadata.
* **Legacy B2B (Brand-Managed)**: **Energy** (reports via SES) and **Factiva** (alerts via legacy infrastructure managed by legacy members of the Messaging team).
* **PANDA-Native Risk Portfolio**: **Dow Jones Risk Journal**, **Oxford Analytica**, and **Dragonfly** (migration in progress) utilize the centralized PANDA/Sailthru stack.
* **MarketSurge Replatform**: Premium initiative building centralized email and mobile alerts on PANDA, synced with Airship and Sailthru.

## **6\. Takeaways and Opportunities**

* **Identity Silos**: No shared backend currently links mobile push (Airship) and email (ENS/PANDA), preventing a unified preference view.
* **Template Debt**: Technical readiness is still needed for templates for **MG, FN, and PEN**, and specialized variants for **WSJ Opinion and Pro**.
* **New Patterns**: **Transactional** and **Triggered Alerts** remain 100% on legacy systems and require new PANDA logic and centralized tooling for breaking news.
* **Onboarding Dependency**: 21 "Configured in Production" products are stalled pending editorial training and onboarding.
* **Operational Latency**: WSJ editors' manual "double-build" for breaking news results in a 10–20 minute email latency gap.

---

### **Visual Architecture (Mermaid.js)**

Code snippet

```
graph TD
    subgraph Messaging_Domain [Messaging Team Domain]
        PANDA[PANDA Orchestration]
        ENS[ENS Subscription DB]
        MEGA[MEGA Sync Tool]
    end

    subgraph Partners [Partner & Brand Tech]
        NP[NewsPress CMS]
        CUR[Curation Tool]
        BT[Alert Tools: BNT / BAT]
        NAPL[Native Ads Platform]
        BRAND[Brand Web/Mobile Teams]
    end

    subgraph External [Vendors]
        ST[Sailthru - Target]
        CM[Campaign Monitor - Legacy]
        AS[Airship - Push]
        PL[Pushly - Desktop]
        SF[SF Marketing Cloud - IBD]
        SES[Amazon SES - B2B]
        BR[Braze - Marketing]
    end

    NP -->|Article Content| CUR
    CUR -->|Trigger| PANDA
    BT -->|Push Trigger| AS
    NAPL -->|Native Ads| PANDA

    ENS <-->|Proxy| PANDA
    ENS -->|Sync| MEGA
    BRAND -->|Integration| ENS

    PANDA --> ST
    PANDA --> AS
    MEGA --> CM
```

## FILE:tech/stack.md
# Tech Stack

Key platforms, tools, and services used across Dow Jones Commerce.

## Subscription and paywall

| Technology | Used for | Notes |
| --- | --- | --- |
| Piano / Composer | Paywall management, A/B testing, subscription targeting, offer delivery | Primary paywall platform; migrated from Cxense |
| CAJ | Checkout and acquisition journey — the checkout platform | Used across WSJ, Barron's, MarketWatch |
| SubsHub | Subscription management — upsell, save offers, user profile, cancellation flows | |

## Identity and authentication

| Technology | Used for | Notes |
| --- | --- | --- |
| OneID / DJOP | Unified identity platform — single auth layer across all DJ products | All B2C traffic routed through DJOP tenant as of Nov 2025 |
| OAuth2 / OpenID Connect (OIDC) | Token-based access standard — replacing legacy authentication | Target: 100% coverage |

## CRM and engagement

| Technology | Used for | Notes |
| --- | --- | --- |
| Braze | CRM platform — mobile in-app messaging, push notifications, email campaigns, AppsFlyer integration | |
| AppsFlyer | App install attribution — integrated with Braze (Nov 2025) | |

## Experimentation and A/B testing

| Technology | Used for | Notes |
| --- | --- | --- |
| Optimizely | A/B testing | Used for onsite experimentation including "Candybar" promotion units |
| Statsig | Experimentation platform | |

## Project and roadmap management

| Technology | Used for | Notes |
| --- | --- | --- |
| Jira Product Discovery (JPD) | Roadmap tracking, initiative status, RAG health | |
| Confluence | Documentation, team wikis | Katy Mastorakis created Confluence hub for Commerce team |

## SEO infrastructure

| Technology | Used for | Notes |
| --- | --- | --- |
| Olympia | Rendering platform — News Types pages migrated here | |
| XML sitemaps | Crawl and indexing for WSJ, Barron's, MarketWatch | Canonical fix resolved 190k non-self-referencing URLs |

## Analytics

See `tech/data-sources.md` for full detail.

## Notes

- Legal, privacy, and InfoSec reviews are standard dependencies for anything touching identity, billing, or personal data — initiate early, not at launch
- Platform team remit: solutions must typically work across multiple DJ brands and surfaces

## FILE:process/product-development.md
# Product Development Process

How work moves from idea to shipped feature at Dow Jones Consumer Products.

## Document types

### 1-Pager
Used to sell a product idea and get stakeholder alignment. Comes before a PRD.

**Purpose:**
- Gain support for the idea — provide context for the problem being solved, for whom
- Define scope — what does the work entail, and what does it not include
- Set success metrics — what does success look like?

**Audience:** Stakeholders, leadership, team

### PRD (Product Requirements Document)
Expands on the 1-pager with deeper research, analysis, and execution detail. Created after the 1-pager has been socialised and discovery has begun.

**Purpose:**
- Defines the problem and solution for everyone who will work on it
- Defines requirements for MVP and beyond
- Sets expectations for stakeholders
- Reduces scope creep and assumptions

**Audience:** Product triads (PM + Design + Engineering), stakeholders, PMO

See `process/templates/1pager-prd-template.md` and `process/templates/brief-template.md`.

## Stages

### 1. Discovery
- Define and validate the problem before proposing solutions
- Key output: 1-Pager, problem statement, opportunity sizing
- Use the double diamond: diverge to discover the problem fully, converge on solutions

### 2. Definition
- Build the PRD in collaboration with the triad (PM, Design, Engineering)
- PRDs are living documents — maintained throughout development, not filed after kickoff
- Key output: PRD with requirements, success metrics, dependencies

### 3. Design
- Design and Engineering work together from the PRD
- Design reviews involve the triad and relevant stakeholders
- Accessibility is a standard consideration

### 4. Build
- Sprint structure: S (1 sprint / 2 weeks), M (3 sprints / 6 weeks), L (whole quarter)
- Tracking in Jira Product Discovery (JPD) with RAG status
- Deliverable types: Discovery / Design / Development / Backlog

### 5. Launch
- Governed by launch tier — not everything requires the same level of process
- Key dependencies: Legal/Privacy for anything touching identity or billing; InfoSec for data flows
- See `process/go-to-market.md`

### 6. Post-launch
- Success measured against pre-defined metrics — outcome-based, not output-based
- A/B test results reviewed and decisions made to ship, iterate, or kill

## Triad model

Every pod has a core triad: PM + Design + Engineering working together from discovery through delivery.

## Key tools

| Tool | Used for |
| --- | --- |
| Jira Product Discovery (JPD) | Roadmap, initiative tracking, RAG status |
| Confluence | Documentation, team wiki |

## Standard dependencies for identity/billing work

Legal, Privacy, and InfoSec reviews are standard for anything touching identity, authentication, billing, or personal data. These are not launch gates — they should be initiated early in discovery.

## FILE:process/templates/1pager-prd-template.md
# 1-Pager vs PRD

### TL;DR: Use a 1-Pager to sell a product idea and a PRD to build on it.

### **What is a 1-Pager?**

The 1-pager helps you put a stake in the ground. It clarifies what you are trying to do, what is your hypothesis, what are your expectations for success, and what the impact will be. This document will help you sell your idea to stakeholders and leadership, and to initiate Discovery with your triad and team.

**Purpose:**

1. Gain support for your idea \- provide context for the problem you’re solving, for whom
2. Define scope \- what does the work entail, and what does it *not* include
3. Success metrics \- what does success look like? What results do you expect?

**Audience:**

* Stakeholders
* Leadership
* Team

### **What is a PRD?**

A Product Requirements Document (PRD) is a document that helps a product manager develop an idea and communicate it to others involved in the project, so that work can be planned and execution can begin. It should come from the 1-pager and discovery.

**Purpose**

1. Defines the problem and solution for everyone who will work on it
2. Defines requirements \- information that is necessary for MVP and beyond
3. Sets expectations for stakeholders
4. Reduces scope creep
5. Reduces assumptions

**Audience**
A well-written PRD will provide information for various audiences, from triad partners, to start the conversation, to engineering teams, who will build the solution, to stakeholders, who are invested in the learnings or success of the solution. A PRD will become a working document that can be developed and referred back to as a project progresses.

# 1-Pager Template

### The 1-pager helps you put a stake in the ground. It clarifies what you are trying to do, what is your hypothesis, what is expected success, and what the impact will be. This document will help you sell your idea to stakeholders and leadership, and to initiate discovery with your triad and team. At this stage try not to be too prescriptive about what to deliver and leave space for collaborative development.

— \[Delete above this line\]
\[Initiative Title\]

**One-line Summary**
\[Write a TLDR; Capture the product’s objective as concisely as possible. Think of what problem are we solving, why is it important and what impact it might have? Provide clarity and context right from the start to help readers quickly grasp the initiative's purpose.

Example: “A paywall embedded within the video player prompting users to subscribe to continue watching.”\]

#### **Problem**

\[What is the problem, challenge or gap that’s been identified? Who does it affect? Try not to refer to the solution at this stage, just talk about the problem at hand. A problem statement should never just be the need for a specific feature we are hoping to build. Include any data or evidence you have that illustrates the problem.

Example: “We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content.”\]

**Goal(s) / Solution opportunity**
\[What does the solution need to achieve at a high level? If we solve this problem what will we get? What value will this work bring to the company, if it is successful? Conversely, what will DJ *miss out on* by not doing it? How will this give DJ competitive advantage?

Example: “If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on.”\]

#### **Risks and Mitigation**

\[What are known risks, and how do you plan to mitigate them?

Example: “Video views may drop overall, reducing advertising revenue.”\]

**Success Metrics**
\[What does success look like? How will you measure success? How will you validate progress and success?

Example: “Monthly paywall impressions”\]

**Proposed Solution(s)**
\[If you already have an idea or ideas for a solution, describe them here. Be directional but not prescriptive at UI level.

Example: “A paywall embedded in the video player, prompting users to subscribe.” is better than “An overlay on the video player with a button that links users to a shop page.”\]

**Must Haves**
\[List any mandatory requirements here. This doesn’t need to include everything, but should be based on what you know today.

Example: Must work across the website and mobile app.\]

# PRD Template

### The PRD expands on the 1-pager to provide more in-depth research, analysis and execution details. It is mostly created by the Product Manager, who is responsible for clearly defining what and why an initiative is important. How we accomplish the goal should be defined in close collaboration with Design and Engineering.

### Some of the information will come from your 1-pager, and some from discovery. The information you put into the PRD will help define your project so that the team can begin work.

— \[Delete above this line\]
\[Initiative Title\]

**One-line Summary**
\[Write a TLDR; Capture the product’s objective as concisely as possible. Think of what problem are we solving, why is it important and what impact it might have? Provide clarity and context right from the start to help readers quickly grasp the initiative's purpose.

Example: “A paywall embedded within the video player prompting users to subscribe to continue watching.”\]

#### **Problem**

\[What is the problem, challenge or gap that’s been identified? Who does it affect? Try not to refer to the solution at this stage, just talk about the problem at hand. A problem statement should never just be the need for a specific feature we are hoping to build. Include any data or evidence you have that illustrates the problem.

Example: “We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content.”\]

#### **Vision**

\[Make a statement about the impact you expect to make when this work is complete. How does this vision align with the [Dow Jones Mission and Vision](https://intranet.dowjones.com/home/ls/content/5294558629855232/who-we-are#mission)?

Example: “Turn our video content into a high volume subscription driver.”\]

**Goal(s) / Solution opportunity**
\[What does the solution need to achieve at a high level? If we solve this problem, what will we get? What value will this work bring to the company, if it is successful? Conversely, what will DJ *miss out on* by not doing it? How will this give DJ competitive advantage?

Example: “If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on.”\]

**Proposed Solution(s)**
\[If you already have an idea or ideas for a solution, describe them here. Be directional but not prescriptive at UI level.

Example: “A paywall embedded in the video player, prompting users to subscribe.” is better than “An overlay on the video player with a button that links users to a shop page.”\]

#### **Assumptions and Constraints**

\[What are the assumptions you are basing your hypothesis on? What are the technical, business, legal, or other constraints you know of?\]

#### **Audience**

\[Who is the audience or beneficiary for this solution? What do we know about them? Include any audience  you have or define the audience you want to serve. Consider who makes the purchasing decision, as in the customer, versus who will use this, as in the user, and who others might experience the consequences of its use.\]

#### **Success Metrics**

\[How will you measure success? How will you validate progress and success?\]

|  | *Name* | *Definition* | *Current Baseline Performance & Target* |
| :---- | :---- | :---- | :---- |
| **Topline Metric** | Example: Monthly Paywall impressions per pageview | The total number of times a paywall is seen by a user / overall pageviews per month | Baseline: 0.1 Target: 0.3 |
| **Secondary Metric** |  |  |  |
| **Counter Metric** | Example: Monthly video ad impressions | The total number of video ads viewed monthly | Baseline: 1.2M Target: Maintain the baseline. |

#### **Risks and Mitigation**

\[What are known risks, and how do you plan to mitigate them?

Example: “Video views may drop overall, reducing advertising revenue.”\]

#### **Scope & Requirements**

\[What user stories must be fulfilled by the solution? Design and engineering teams will use these to make sure the product achieves everything it needs to to fulfill the user and business needs. Try to focus on user needs without prescribing solutions. Leave enough space for design and engineering teams to explore multiple paths and solutions.\]

\[What is a must have or nice to have for MVP? What is not part of MVP, and can be added after launch? What is the definition of done, and what maintenance and monitoring should follow?\]

| Requirement Title | Description | User Story (optional) | Scope | Notes |
| :---- | :---- | :---- | :---- | :---- |
| Example: Sale pricing | The ability to change pricing that is displayed during sale periods or update pricing to match the current offer. | As a user, I want to see sale pricing within the video player so that I can quickly weigh up my purchasing decision and proceed to purchase. | MVP / Must have / Nice to have | Marketing operations should be able to run sales without the need for engineering involvement.  |
| Example 2: Flexible branding across DJs consumer brands. | … | … | … | … |

#### **Dependencies**

\[Does your solution have any dependencies on other teams or tooling? Are there Design, UX, or Accessibility considerations? Are there legal requirements or reviews that need to be incorporated into your plan? Are there any other teams or projects that are dependent on your solution, which might impact timing of your deliverable?\]

#### **Timing**

\[Is there a hard date by which this needs to be launched, or other timing considerations to be mindful of?\]

#### **RACI (Optional. For large initiatives)**

| Team | Responsible | Accountable | Consulted | Informed |
| :---- | :---- | :---- | :---- | :---- |
| **Product** | List teams and/or individuals |  |  |  |
| **Engineering** |  |  |  |  |
| **Design** |  |  |  |  |
| **Subscription Marketing** |  |  |  |  |
| **PMO** |  |  |  |  |
| **SEO** |  |  |  |  |
| **Data** |  |  |  |  |
| **Privacy/Legal** |  |  |  |  |
| **Customer Service** |  |  |  |  |

##

## **Tasks (Optional)**

\[For cross-functional work, break the project down into top level tasks, listing the major steps required to complete the project, who will own them, any dependencies, and links to relevant resources.\]

| Team | Task | Owner | Notes |
| :---- | :---- | :---- | :---- |
| UXD | Wireframes | Person | Not to reflect final designs. |
| Engineering | Technical discovery | Person | … |
|  |  |  |  |

**Other considerations:**
Legal considerations/requirements
InfoSec considerations/requirements
Design \+ UX Considerations
Accessibility needs
B2C considerations \- [Product Development Checklist](https://docs.google.com/document/d/1TAXM7idFoAb9f7DgIcWnFzm9GB6LTXXqHu5_wO-po6s/edit?tab=t.0)
B2B considerations
Marketing considerations
Prioritization (where does this fit in your roadmap)
User personas
Competitors

## FILE:process/templates/brief-template.md
# 1-Pager Template — Dow Jones Commerce

> A 1-Pager helps you put a stake in the ground. It clarifies what you are trying to do, what your hypothesis is, what success looks like, and what the impact will be.
> Use it to sell your idea to stakeholders and leadership, and to initiate discovery with your triad.
> At this stage, try not to be prescriptive about what to deliver — leave space for collaborative development.
> A PRD comes next. See `process/templates/prd-template.md`.

---

[Initiative Title]

**One-line summary**
[Write a TLDR. Capture the product's objective as concisely as possible. What problem are we solving, why is it important, and what impact might it have?

Example: "A paywall embedded within the video player prompting users to subscribe to continue watching."]

---

## Problem

[What is the problem, challenge or gap that's been identified? Who does it affect? Do not refer to the solution — focus on the problem. Include any data or evidence that illustrates it.

Example: "We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content."]

---

## Goals / Solution opportunity

[What does the solution need to achieve at a high level? If we solve this problem, what will we get? What will DJ miss out on by not doing it?]

---

## Risks and mitigation

[What are the known risks? How will you mitigate them?]

---

## Success metrics

[What does success look like? How will you measure it?

Example: "Monthly paywall impressions"]

---

## Proposed solutions

[If you already have solution ideas, describe them directionally. Be directional, not prescriptive at UI level.]

---

## Must haves

[List any mandatory requirements you know of today. This doesn't need to be exhaustive.

Example: Must work across the website and mobile app.]

## FILE:process/templates/prd-template.md
# PRD Template — Dow Jones Commerce

> This template reflects how the Commerce product team writes PRDs.
> A 1-Pager comes first (to get alignment) — a PRD expands on it with deeper research and execution detail.
> See `process/product-development.md` for when to use which.

---

[Initiative Title]

**One-line Summary**
[Write a TLDR. Capture the product's objective as concisely as possible. What problem are we solving, why is it important, and what impact might it have?

Example: "A paywall embedded within the video player prompting users to subscribe to continue watching."]

---

## Problem

[What is the problem, challenge or gap that's been identified? Who does it affect? Do not refer to the solution here — focus on the problem. Include any data or evidence that illustrates it.

Example: "We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content."]

---

## Vision

[Make a statement about the impact you expect to make when this work is complete.

Example: "Turn our video content into a high volume subscription driver."]

---

## Goals / Solution opportunity

[What does the solution need to achieve at a high level? If we solve this problem, what will we get? What will DJ miss out on by not doing it?

Example: "If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on."]

---

## Proposed solutions

[If you have solution ideas, describe them directionally — not prescriptively at UI level.

Example: "A paywall embedded in the video player, prompting users to subscribe." is better than "An overlay on the video player with a button that links users to a shop page."]

---

## Assumptions and constraints

[What are the assumptions you are basing your hypothesis on? What are the technical, business, legal, or other constraints you know of?]

---

## Audience

[Who is the audience or beneficiary for this solution? Who makes the purchasing decision (customer) vs. who will use it (user)?]

---

## Success metrics

| | Name | Definition | Current baseline & target |
| --- | --- | --- | --- |
| **Topline metric** | Example: Monthly paywall impressions per pageview | The total number of times a paywall is seen / overall pageviews per month | Baseline: 0.1 Target: 0.3 |
| **Secondary metric** | | | |
| **Counter metric** | Example: Monthly video ad impressions | Total video ads viewed monthly | Baseline: 1.2M Target: Maintain baseline |

---

## Risks and mitigation

[What are the known risks? How will you mitigate them?

Example: "Video views may drop overall, reducing advertising revenue. Mitigation: monitor ad impressions as a counter metric."]

---

## Scope and requirements

| Requirement | Description | User story (optional) | Scope | Notes |
| --- | --- | --- | --- | --- |
| Example: Sale pricing | Ability to change displayed pricing during sale periods | As a user, I want to see sale pricing so I can make a quick purchasing decision | MVP / Must have | Marketing ops should be able to run sales without engineering involvement |

---

## Dependencies

[Other teams, tooling, Legal/Privacy/InfoSec reviews, or projects that depend on or block this work.

Note: Legal, privacy, and InfoSec reviews are standard for anything touching identity or billing — initiate early in discovery, not at launch.]

---

## Timing

[Hard deadlines, seasonal considerations, or other timing constraints.]

---

## RACI (optional — for large initiatives)

| Team | Responsible | Accountable | Consulted | Informed |
| --- | --- | --- | --- | --- |
| Product | | | | |
| Engineering | | | | |
| Design | | | | |
| Subscription Marketing | | | | |
| PMO | | | | |
| SEO | | | | |
| Data | | | | |
| Privacy/Legal | | | | |
| Customer Service | | | | |

---

## Tasks (optional — for cross-functional work)

| Team | Task | Owner | Notes |
| --- | --- | --- | --- |
| UXD | Wireframes | [Name] | Not to reflect final designs |
| Engineering | Technical discovery | [Name] | |

---

**Other considerations checklist:**
- Legal considerations / requirements
- InfoSec considerations / requirements
- Design + UX considerations
- Accessibility needs
- B2C considerations
- B2B considerations
- Marketing considerations
- User personas
- Competitive context

## FILE:process/templates/retrospective-template.md
# Retrospective: [Project / Sprint / Quarter]

**Date:** [YYYY-MM-DD]
**Facilitator:** [Name]
**Participants:** [Names]

---

## What went well

- [Add]

## What didn't go well

- [Add]

## What we'd do differently

- [Add]

## Action items

| Action | Owner | Due date |
| --- | --- | --- |
| [Add] | [Name] | [Date] |

## Notes

[Any additional context or discussion points]

---

*Template version: 1.0*

## FILE:style/design-principles.md
# Design Principles

Product design values and principles for Dow Jones.

## Core principles

<!-- What guides how we design products at Dow Jones? -->
- [Add principle and brief explanation]

## Design system

<!-- What design system do we use? Where does it live? -->
- [Add]

## Key UX conventions

<!-- Patterns and conventions that apply across products -->
- [Add]

## Accessibility standards

<!-- What are our accessibility commitments? -->
- [Add — e.g. WCAG 2.1 AA]

## Notes

## FILE:style/writing.md
# Writing Style — Dow Jones Commerce Product Team

Voice, tone, and conventions for internal product documentation.

## Core principles

- **Concise, direct, actionable** — shorter and clearer beats comprehensive and unread
- **Subheadings are essential** — use them in all substantive writing, even short documents. The best subheadings summarize the point, not just label the topic. A reader should understand the key idea from the heading alone.
- **Write for skim readers** — dense blocks of text lose people. Short paragraphs, clear headings, simple language.
- **Bullet points have limits** — keep lists to under 6 items. Each bullet should be one short sentence. If a bullet is running long, it's probably a paragraph. If a list is running long, break it into themed sections.

## Language

- Always use **American English** spelling: recognize, analyze, color, prioritize, optimize
- No emojis in professional documents
- Avoid internal jargon without explanation — use the glossary (`company/glossary.md`)

## PRD writing principles

- **Start with the problem, not the solution** — stakeholders often arrive with fully formed solutions; work backwards
- **PRDs are thinking tools, not forms** — writing forces clarity; if you struggle to define the problem, the initiative may not be ready
- **Be outcome-based** — success metrics should connect to subscription KPIs (paywall impressions, CVR, subscriber acquisition, churn, ARPU), not just outputs
- **Simple scales** — front-load with the most important information

## Naming conventions

| Preferred | Avoid | Notes |
| --- | --- | --- |
| The Wall Street Journal | WSJ (in external-facing copy) | WSJ is fine internally |
| MarketWatch | Market Watch (one word) | |
| Commerce team | Subscriptions team | Team was renamed to Commerce in Mar 2025 |
| OneID | One ID | Single word |

## Document audiences

| Document type | Primary audience |
| --- | --- |
| 1-Pager | Stakeholders, leadership |
| PRD | Product triad (PM + Design + Engineering), stakeholders, PMO |
| Roadmap | Leadership, marketing stakeholders, cross-functional partners |
| Quarterly planning summary | Tech, Marketing, Business, Newsroom teams |

## Writing for AI tools (this repo)

When writing context files for this repo:
- Be specific and factual — avoid vague generalities
- Use tables for structured information
- Mark placeholders clearly with `[Add]`
- Include "Last updated" dates where content may go stale
- Link to other files rather than duplicating content

## FILE:context-compiled.md
# DJ B2C CONTEXT ENGINE
# Compiled context for Dow Jones B2C product team.
# Use this as system context when generating product docs, PRDs, briefs, or strategy.
# Source of truth: github.com/danielhockley1337/dj-b2c-context
# Files included: 41

## FILE:company/glossary.md
# Dow Jones — Glossary

Terms, abbreviations, and internal jargon used across Dow Jones and the product team.

## Products and brands

| Term | Meaning |
| --- | --- |
| WSJ | The Wall Street Journal |
| MW | MarketWatch |
| IBD | Investor's Business Daily (acquired 2021) |
| BIC | Barron's Investor Circle — premium subscriber community |
| WSJ+ | WSJ bundle subscription product; expands multi-brand access |
| Free Expression | New subscription vertical combining newsletter sign-up and free account creation (launched Dec 2025) |

## Internal platforms and systems

| Term | Meaning |
| --- | --- |
| Piano / Composer | Paywall and subscription management platform; used for targeting, A/B testing, and subscription flows |
| CAJ | Checkout and acquisition journey — the checkout platform |
| SubsHub | Subscription management hub (upsell, save offers, user profile). Also referred to as SubHub in some internal docs — SubsHub is the canonical name. |
| OneID / DJOP | Dow Jones unified identity platform — single authentication layer across all DJ products |
| Braze | CRM platform used for mobile and email marketing, in-app messaging |
| Optimizely | A/B testing and experimentation platform |
| Statsig | Experimentation platform |
| JPD | Jira Product Discovery — roadmap and status tracking tool |
| Mosaic | Internal subscription management platform. Handles mid-term subscription changes including cancel, refund, and repurchase flows. Being extended by the Clean Transitions initiative to support credit-based offer switching without a full cancel-repurchase cycle. |
| BRS | Billing and Revenue System — handles charge groups, payments, credits, refunds, and receipts |
| CSM | Core Subscription Management — manages subscription state, term calculations, pro-rating, and transitions between offers |
| Verint | CRM tool used by Customer Service agents to access and manage customer accounts |
| Watson | Dow Jones offer targeting engine — returns eligible offers for a customer based on configured rules and directives |
| EDW | Enterprise Data Warehouse — central data storage and reporting system for product and business metrics |

## Process and planning

| Term | Meaning |
| --- | --- |
| RAG | Red / Amber / Green — status health system for roadmap items (also includes "On Hold") |
| LOE | Level of effort — engineering or design estimate |
| T-shirt sizing | Effort estimation: S (2 weeks / 1 sprint), M (6 weeks / 3 sprints), L (whole quarter) |
| Triad | The core product delivery unit: PM + Design + Engineering working together |
| CMO | Central Marketing Org — primary consumer stakeholder, accountable for subscription targets |
| DSAR | Data Subject Access Request |
| ROPA | Records of Processing Activities (GDPR Article 30) |
| DPIA | Data Protection Impact Assessment (GDPR Article 35) |
| IFE | In-Flight Entertainment (used in context of Delta partnership) |

## Metrics and data

| Term | Meaning |
| --- | --- |
| ARPU | Average Revenue Per User |
| CVR | Conversion rate |
| Churn | Rate at which subscribers cancel or lapse |
| Paywall impression | A user encounter with a paywall prompt |
| Save offer | A retention offer presented to a subscriber who is attempting to cancel |
| Win-back | Reacquisition offer targeting lapsed/cancelled subscribers |
| Crawl coverage | Percentage of priority content successfully crawled by search engines |
| Crawl waste | Percentage of crawl budget spent on non-priority pages |

## Customer journey stages

| Stage | Owned by |
| --- | --- |
| Traffic & Audience Growth | SEO |
| Registration & Nurture | Subscriber Acquisition |
| Conversion | Subscriber Acquisition |
| Activation | Subscriber Engagement, Revenue & Retention |
| Engagement & Revenue | Subscriber Engagement, Revenue & Retention |
| Retention & Win-back | Subscriber Engagement, Revenue & Retention |

## FILE:company/overview.md
# Dow Jones — Company Overview

## About

Dow Jones is a global provider of news, data, and analytics. It is a subsidiary of News Corp. Dow Jones publishes some of the world's most influential business and financial media across consumer subscription brands including The Wall Street Journal, Barron's, MarketWatch, and Investor's Business Daily.

This context repo covers the B2C (consumer) side of the Dow Jones business. B2B products (Factiva, Risk & Compliance, Newswires, DJ Platform) are out of scope.

As of the March 2026 Investor Briefing, Dow Jones described itself as a "news, data and intelligence powerhouse" — with authoritative editorial positioned as an essential input for the AI era.

## Financial highlights (FY2018–FY2025)

- Revenue base: **82% digital** (up from 60% in FY2018), **80% recurring** (up from 69%)
- **17% compound annual segment EBITDA growth** since FY2018
- Segment EBITDA margin: **25.2%** (nearly doubled since FY2018)
- Dow Jones has driven **11 successive quarters** of year-over-year Total Segment EBITDA growth at News Corp

## $1B EBITDA target

At the March 2026 Investor Briefing, News Corp detailed a pathway to **$1 billion in annual Dow Jones segment EBITDA within five years**, driven by:

- Accelerating Risk & Energy businesses (margin expansion)
- Accelerating direct-to-consumer offerings with new products and pricing
- Sharp focus on high-margin enterprise news
- Continuing cost discipline and operating leverage

## Key consumer brands

- **The Wall Street Journal** — flagship B2C subscription product; one of the largest paid digital news publications in the US
- **Barron's** — financial and investment news
- **MarketWatch** — real-time financial news and market data
- **Investor's Business Daily (IBD)** — acquired 2021
- **WSJ Pro** — premium vertical journalism for professionals
- **WSJ+** — multi-brand bundle subscription (WSJ, Barron's, MarketWatch, IBD)

## Headquarters

New York, NY (primary). Part of News Corp.

## Ownership

Subsidiary of News Corp (NWSA / NWS).

## Leadership

| Name | Title |
| --- | --- |
| Almar Latour | CEO, Dow Jones |
| Artem Fishman | CTO |
| Scott M. Havens | Chief Growth Officer & Global Head of Consumer |
| Emma Tucker | Editor in Chief, WSJ |
| Ryan Daly | SVP, Consumer Product |

## Competitive landscape

Dow Jones competes with FT, Bloomberg, NYT, and specialist financial media for digital subscribers.

## FILE:company/strategy.md
# Dow Jones — Strategy

## Strategic pillars

- **Subscription-first** — Consumer revenue is driven by paid digital subscriptions across WSJ, Barron's, MarketWatch, and IBD
- **Bundle growth** — WSJ+ bundle strategy is a key growth lever, expanding multi-product subscriptions across brands
- **AI as a monetization layer** — Dow Jones positions its authoritative editorial as an essential input for large AI models; licensing and AI product revenue are an expanding opportunity
- **Identity and first-party data** — The authentication and identity layer (OneID) is increasingly strategic, underpinning personalisation, bundling, and first-party data strategy
- **SEO and organic acquisition** — SEO is a primary top-of-funnel channel for WSJ and MarketWatch; positioning DJ properties for discovery via both traditional search and AI platforms

## North Star narrative (from March 2026 Investor Briefing)

Dow Jones frames itself as an **"Input company"** in the Age of AI — drawing an analogy to semiconductors and energy as inputs to the physical world. Authoritative editorial, trusted data, and proprietary risk/compliance intelligence are inputs to the digital and AI world. This framing underpins licensing deals with AI model providers and DJ's broader enterprise strategy.

> "As AI models are rippling from industry to industry, their output is only as good as their input, which is where Dow Jones comes in." — Almar Latour, CEO Dow Jones, March 2026

## Key strategic dynamics

- Platform team remit means solutions need to work across multiple brands and surfaces, not just solve for one
- Legal, privacy, and InfoSec reviews are standard for anything touching identity or billing
- Success metrics connect to subscription KPIs: paywall impressions, conversion rate, subscriber acquisition, churn, ARPU

## Competitive landscape

| Competitor | Where we compete |
| --- | --- |
| Financial Times | Business/financial news subscriptions |
| Bloomberg | Financial data, news, and professional terminals |
| New York Times | Digital news subscriptions, general audience |
| Specialist financial media | Vertical professional publications |

## FILE:goals/FY2026/priorities.md
# FY2026 Priorities — Commerce Product

> FY26 = July 2025 – June 2026
> Last updated: 2026-03-20

## Subscriptions priorities

- **Registration growth** — Grow monthly new free registered users from 20k to 135k
- **Conversion optimisation** — 10–15% incremental conversion lift via A/B testing program
- **Bundle growth** — Grow WSJ+ bundle subscriptions from 1M to 1.15M; deliver $80M bundle revenue
- **Early-life engagement** — Improve avg active days in subscriber's first 7 days (3.9 → 4.3)
- **Retention** — 10–15% lift in save offer take rate
- **New verticals** — Launch commerce surfaces for Free Expression, Connected paywall, Puzzles
- **Delta Partnership** — ~360k subscriptions projected over 3 years

## SEO priorities

- **Traffic ranking** — Move WSJ from #8 to #6 in share of traffic vs. competitors
- **Crawl coverage** — Improve from 55% to 65% (exceeded: hit 74% in Q2)
- **Crawl waste** — Reduce from 30% to 20% (at risk: at 49% in Q2)
- **Programmatic SEO** — Market data pages, topic pages, earnings calendar (MarketWatch)

## Identity priorities

- **OAuth2/OIDC** — Reach 100% token-based access across all products (baseline: 80%)
- **Data hygiene** — Delete ~2.3M inactive accounts (6+ years)

## Cross-team priorities

- In-app Meter — registered users get free articles on app
- Self-serve Corporate Sales shop page ($200k+ Q4 target)

## Notes

Last updated: 2026-03-20

## FILE:goals/FY2026/technology-okrs.md
# Technology FY26 OKRs

> Source: Technology FY26 OKR Tracker
> FY26 = July 2025 – June 2026 | Last updated: 2026-03-20

---

## Grow Subscriptions

### KR: Grow digital subscriptions
**Target:** Q4 average of 6.5M DJ digital subs (WSJ 4.3M)
**Owner:** Dan | **Tech Exec:** Ryan | **ETA:** Q4 | **Status:** TBC

---

### KR: Strengthen paywall strategy — registration growth
**Target:** +10% incremental conversions and 6x monthly registration growth (20k → 120k) by EOFY26
**Owner:** Dan | **Tech Exec:** Ryan | **ETA:** Q4 | **Status:** At Risk

---

### KR: Drive consumer engagement +15% (app weekly subscriber time spent)
**Target:** 1:02:05 → 1:11:24 overall app weekly subscriber time spent by EOH2 (via WSJ Redesign — Media & MyWSJ in H1)
**Owner:** Ryan | **ETA:** H1 | **Status:** Off Track

---

## FILE:goals/company-okrs.md
# Company OKRs — FY26

> FY26 = July 2025 – June 2026
> Last updated: 2026-03-20
> Full Technology OKR tracker: `goals/FY2026/technology-okrs.md`
> Commerce product OKRs: `goals/product-okrs.md`

---

## Top-line subscription targets (FY26)

| Metric | Target |
| --- | --- |
| DJ digital subscriptions | 6.5M (Q4 avg) |
| WSJ digital subscriptions | 4.3M (Q4 avg) |
| Monthly registered users | 120k cumulative |
| App weekly subscriber time spent | 1:11:24 |

---

## Technology OKR summary (FY26)

| OKR | Owner | Status |
| --- | --- | --- |
| Grow digital subs to 6.5M DJ / 4.3M WSJ | Dan / Ryan | TBC |
| Paywall — +10% conversion lift; 20k → 120k monthly registrations | Dan / Ryan | At Risk |
| Consumer engagement +15% app weekly time spent | Ryan | Off Track |

---

## FY27 strategic directions

1. Return to net positive subscriber growth (currently negative net new in volume)
2. Focus on engagement frequency (not time on site) as north star
3. Bolster core digital subscription with new value for new audiences (Games, Sports, Market Data)
4. Boost quality traffic with high subscription propensity (SEO/Audience team)

## Notes

Last updated: 2026-03-20

## FILE:goals/product-okrs.md
# Commerce Product OKRs

> FY26 = July 2025 – June 2026 | FY27 = July 2026 – June 2027
> Last updated: 2026-03-20

## FY26 OKRs — Status as of Q3

### Subscriptions

| OKR | Target |
| --- | --- |
| Grow monthly new free registered users | 20k → 135k |
| Incremental conversion lift from A/B testing | +10–15% |
| Deliver bundle revenue | $80M (from $68M) |
| Grow bundle subscriptions | 1M → 1.15M |
| Improve early-life engagement | 3.9 → 4.3 avg days (first 7) |
| Improve save offer take rate | +10–15% lift |

### SEO

| OKR | Target |
| --- | --- |
| WSJ share of traffic ranking | #6 (from #8) |
| Crawl coverage of priority content | 55% → 65% |
| Reduce crawl waste | 30% → 20% |

### Identity

| OKR | Target |
| --- | --- |
| OAuth2/OIDC token-based access | 100% (baseline: 80%) |
| Reduce inactive accounts (6+ years) | 0 remaining (baseline: 2,337,801) |

---

## FY27 OKRs — Draft

> Status: Draft — targets TBC pending input from Head of Growth and the business
> FY27 runs July 2026 – June 2027

### O1: Return to net subscriber growth
- KR1: Achieve net positive new subscriber volume by end of Q2, sustained through Q4
- KR2: Reduce voluntary churn rate through improved save and cancellation flows
- KR3: Reduce involuntary churn through billing recovery and payment failure intervention
- KR4: Improve paywall-to-checkout conversion rate through checkout improvements and experimentation

### O2: Build engagement habit through feature adoption and onboarding
- KR1: Increase share of new subscribers using core features within their first 30 days
- KR2: Improve 90-day retention rate among subscribers completing onboarding vs. those who don't
- KR3: Increase average experiment-driven lift in feature adoption rate across onboarding and in-app product marketing
- KR4: Increase share of active subscribers with 2+ active days per week (directional)

### O3: Build subscriber funnels for new subscription products
- KR1: Acquire new subscribers via Games and Market Data entry points by Q4
- KR2: Achieve target % of bundle upgrades completed via in-app purchasing by Q4
- KR3: Achieve target % of net new subscribers acquired via non-news entry points by end of FY27
- KR4: Achieve new registrations/subscribers via MarketWatch by Q4

### O4: Grow and convert the registered user base
- KR1: Grow monthly new free registrations to target by Q4
- KR2: Improve registered-to-paid user conversion rate
- KR3: Increase opt-in rate for lifecycle marketing channels among new registrants

### O5: Increase revenue per subscriber (ARPU)
- KR1: Achieve household subscription target by Q4, with price resilience rate higher than single-user plans
- KR2: Drive incremental WSJ+ Marketplace revenue by Q4
- KR3: Increase average revenue per subscriber across WSJ, Barron's, and MarketWatch

### FY27 dependencies (owned outside Subscriptions)
- Notifications/alerts hub — habit driver; owned by app/platform teams
- Newsletters in-app — owned by editorial product
- App performance (reliability, speed, offline mode) — owned by platform/engineering
- Content features (personalization, video, AI summaries) — owned by editorial/newsroom product
- Community features (commenting, Circles, Live QAs) — ownership TBC

## FILE:products/barrons/metrics.md
# Barron's — Metrics

## Primary KPIs

| Metric | Definition | Current value | Target |
| --- | --- | --- | --- |
| [Add] | [Add] | [Add] | [Add] |

## Notes

<!-- Caveats, data sources -->

## FILE:products/barrons/overview.md
# Barron's — Overview

## What it is

Barron's is a financial and investment news publication focused on market analysis, stock picks, and investment ideas. It has a long print heritage and a growing digital and mobile presence.

## Audience

- Individual investors and wealth managers
- Professionals in financial services
- Sophisticated retail investors

## Business model

Subscription-first, with advertising. Shares commerce infrastructure with WSJ. Part of the WSJ+ bundle.

## Key Commerce surfaces

- Paywalls — Piano / Composer
- Shop pages — CAJ checkout
- Barron's Investor Circle (BIC) — premium subscriber community; integrated with OneID and BigMarker livestream platform
- Barron's Mobile App NextGen — new app with Commerce surfaces (Q4 FY26 initiative)

## FILE:products/barrons/products.md
# Barron's — Product Inventory

A reference guide to the discrete products and features owned by the Barron's product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers Barron's-owned consumer experiences.

---

## Core Digital Products

### Barrons.com
The primary web destination for Barron's editorial content and subscriber experience.

- Covers market analysis, stock picks, investment ideas, fund rankings, and financial commentary
- Authenticated experience for subscribers; metered/paywalled for anonymous users
- Key sections: Stocks, Funds & ETFs, Bonds, Options, Retirement, Personal Finance, Economy
- Piano Composer-powered paywall; CAJ shop pages and checkout for subscription purchase

### Barron's iOS App
The native iPhone and iPad application for Barron's subscribers.

- Full editorial content access with offline reading capability
- Push notifications for market-moving stories and subscriber alerts
- In-app subscription purchase via Apple IAP
- Next-gen app rebuild in progress (Q4 FY26 initiative) to bring Commerce surfaces and improved UX

### Barron's Android App
The native Android application for Barron's subscribers.

- Feature-parity with iOS app; distributed via Google Play Store
- In-app subscription purchase via Google Play billing
- Part of next-gen app rebuild initiative

---

## Markets & Data

### Stock Picks & Ratings
Barron's proprietary stock analysis and ratings, a core differentiator for the brand.

- Long and short recommendations with thesis summaries
- Historical picks performance tracking
- Integrated with editorial content; a primary subscriber value driver

### Barron's Stock Screener
A tool for filtering and discovering stocks based on financial criteria.

- Available to subscribers as part of the investing tools suite
- Filters by sector, valuation, performance, dividend yield, and other metrics

### Market Data (Quotes & Watchlists)
Real-time and delayed market data embedded across Barrons.com and the app.

- Stock, ETF, mutual fund, and index quotes
- Personal watchlist creation and management for registered and subscribed users
- Company pages with financials, news, and analyst coverage

---

## Newsletters

### Barron's Daily
The flagship daily newsletter covering market movers, top stories, and investment ideas.

- Sent weekday mornings to subscribers and registered users
- High-intent financial audience; strong engagement rates

### Barron's Weekly
A weekend digest of the week's top picks, analysis, and market outlook.

- Mirrors the print magazine cadence
- Focuses on longer-form investment ideas and commentary

### Other newsletters
Topic-specific newsletters including income investing, ETF focus, and options coverage. Full list managed by the Editorial Newsletters team.

---

## Community & Events

### Barron's Investor Circle (BIC)
A premium subscription tier from Barron's, positioned as an "inner circle" for serious investors seeking an edge in the markets.

- Exclusive early access to stock picks and deeper research from Barron's analysts before wider publication
- Premium article experience with integrated market data analysis for deeper investment research
- Live and on-demand events with Barron's stock pickers, editors, and analysts, including Q&A access, powered by BigMarker
- Available as a standalone Barron's subscription or bundled with MarketWatch; three pricing tiers offered
- Integrated with OneID for subscriber authentication and entitlement verification
- Differentiator vs. competitors; targets high-intent investors willing to pay a premium for market intelligence

### Barron's Live Events
In-person and virtual conferences and roundtables for institutional and individual investors.

- Flagship event: Barron's Top 100 Financial Advisors Summit
- Additional events covering retirement, markets, and investment themes
- Ticket access often tied to subscription tier or separate purchase

---

## Print

### Barron's Magazine (Print)
The weekly print edition, one of the longest-running financial publications in the US.

- Published weekly; distributed via mail subscription and newsstand
- Print subscribers are managed in Mosaic alongside digital
- Print delivery management available via Subscriber Hub

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| Barrons.com & apps | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| Barron's iOS/Android apps | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Investor Circle (BIC) | OneID (auth), BigMarker (livestream platform) |
| Market Data | Third-party data providers (Factset and others) |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Print subscriptions | Mosaic (subscription management), Subscriber Hub |

## FILE:products/commerce/metrics.md
# Commerce — Metrics

## Primary KPIs

| Metric | Definition | FY26 target |
| --- | --- | --- |
| Monthly new free registered users | New free accounts created per month | 135k (from 20k baseline) |
| Conversion rate lift from A/B testing | Incremental conversion lift across experiments | +10–15% |
| Bundle subscriptions | Number of subscriptions in a bundle | 1.15M (from 1M) |
| Bundle revenue | Total revenue from bundle subscriptions | $80M (from $68M) |
| Early-life engagement | Avg active days in subscriber's first 7 days | 4.3 days (from 3.9) |
| Save offer take rate | Lift in save offer acceptance from A/B testing | +10–15% |

## SEO metrics

| Metric | FY26 target |
| --- | --- |
| WSJ share of traffic ranking vs. competitors | #6 (from #8) |
| Crawl coverage of priority content | 65% (from 55%) |
| Crawl waste | 20% (from 30%) |

## Identity metrics

| Metric | FY26 target |
| --- | --- |
| OAuth2/OIDC token-based access coverage | 100% (baseline: 80%) |
| Inactive accounts deleted (6+ years) | 0 remaining (baseline: 2,337,801) |

## Key subscription metrics (definitions)

### Top line / subscription health

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| New Subscription Orders | Total subscription orders in a period | Total orders over period | Daily / Weekly / Monthly | Must Have |
| New Subscription Starts | Total subscription starts in a period | Total starts over period | Daily / Weekly / Monthly | Must Have |
| Subscription Stops | Subscribers who lose access within a timeframe | Total stops over period | Daily / Weekly / Monthly | Must Have |
| Subscription Cancellations | Subscribers who turn off auto-renew | Total cancellations over period | — | — |
| Net New Starts | Starts minus stops | Total Starts − Total Stops | Daily / Weekly / Monthly | Must Have |
| User Conversion Rate | Conversion rate of all non-subscriber traffic | Total non-sub users / Total Orders | Daily / Weekly / Monthly | Must Have |
| Avg starts per order | Average subscription starts per order | Total Starts / Total Orders | Daily / Weekly / Monthly | Nice to Have |
| Bundle take rate | % of orders including 2+ starts across WSJ+ brands | — | — | — |
| Daily / Weekly active users | Users active on site or app in a given period | — | Weekly / Monthly | Must Have |
| Active days in first 7 days | Days a user had a session of at least X mins within first week of subscribing | # of days with 1+ session in subscribed day + 6 | Weekly / Monthly | Must Have |
| Engagement bracket | Users grouped by active days in last 28 days: Dormant (0), Occasional (1–5), Light (6–10), Mid (11–15), Super (16+) | Group users by 28-day active day count | Weekly / Monthly | — |
| Churn rate | % of subscribers no longer active over a timeframe | Split by web/app, monthly/annual, product, promo/list | — | — |
| Save rate | Rate at which users entering the cancellation funnel accept a save offer | # save offer accepts / # users entering cancellation funnel | Weekly / Monthly | Must Have |
| Net Revenue Retention (NRR) | Holistic measure of MRR change accounting for expansion, contraction, and churn | (Starting MRR + Expansion MRR − Contraction MRR − Churned MRR) ÷ Starting MRR | — | Nice to Have |

### Paywall

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| Total paywall impressions | # of times a paywall is loaded on a page (roadblocks, scrims, snippets, in-situ, dual CTA, live coverage, etc.) | Total paywall loads via Piano | Daily / Weekly / Monthly | Must Have |
| Paywall hit rate | % of pageviews that include a paywall impression | Paywall Impressions / Total non-sub pageviews | Daily / Weekly / Monthly | Must Have |
| Paywall conversion rate | % of paywall impressions resulting in an order | Total Orders / Total Paywall Impressions | Daily / Weekly / Monthly | Must Have |
| Top paywall conversion stories | Top 10 stories driving conversions | Top 10 by conversion count | Yesterday / Last 7 days | Nice to Have |

### Registration

| Metric | Definition | Calculation | Cadence | Priority |
| --- | --- | --- | --- | --- |
| Accounts created | Total new user accounts created | Total new accounts | Daily / Weekly / Monthly | Must Have |
| Registration wall impressions | Total impressions of regwall units (dual CTA, registration roadblocks) | Total regwall units delivered by Piano | Daily / Weekly / Monthly | Must Have |
| Registration wall conversion rate | % of regwall impressions resulting in a registration | New accounts via regwalls / Total regwall impressions | Daily / Weekly / Monthly | Must Have |

### Acquisition and conversion

| Metric | Definition | Priority |
| --- | --- | --- |
| Shop page impressions | Views of a subscription shop page | — |
| Shop page → order conversion | Users completing an order from a shop page visit | — |
| Shop page → checkout start | Users beginning checkout from a shop page visit | — |
| Shop page unique visits | Unique visitors to a given shop page | — |
| ARPU | Average Revenue Per User — total revenue / total visitors; used especially for Optimizely experiment analysis | — |
| LTV projections | Projected lifetime revenue per visitor based on sales data and bundle mix | — |
| Cart abandon rate | Users who begin checkout but do not complete an order | — |

### Core product engagement (activation)

| Metric | Definition |
| --- | --- |
| Value exchange metrics | Engagement where user receives value: article reads, listens, watchlist reads, video watches, puzzle plays, newsletter reads |
| Customisation metrics | Engagement where user invests in product: follows, saves, watchlist adds, interest selections, comments, newsletter subscriptions |
| Content breadth | # of sections engaged with (unique sections per user in last 28 days) |
| Content completion rate | % of content completed — articles, listens, videos, podcasts, puzzles, newsletters |
| App/web and cross-device engagement | Combination of surfaces (desktop web, mobile web, tablet web, app) a user engaged with in last 28 days |
| Time to first value | Time from session start to first content engagement |
| Session initiation method | How users start sessions: direct, email, push notification |

### Retention

| Metric | Definition |
| --- | --- |
| 1st renewal churn rate | Users who churn at their first renewal point (split by web/app, monthly, product) |
| Promo-to-list churn rate | Users who churn after stepping up to list price |
| Voluntary vs. involuntary churn | Voluntary: users on auto-renewal who cancel. Involuntary: users not on auto-renewal who lapse. Payment failure target: 50% recovery. |
| Save offer | Retention offer presented to a subscriber attempting to cancel |
| Win-back | Reacquisition offer targeting lapsed/cancelled subscribers |

## Data sources

- B2C Analytics: Emily C Williams (Senior Director, B2C Analytics, reports to Mike Shaw SVP Data Engineering)
- Experimentation analysis: Data Science & Analytics team
- Roadmap status: Jira Product Discovery (JPD) — RAG health

## FILE:products/commerce/overview.md
# Commerce — Overview

## What it is

The Commerce team owns the full subscription lifecycle across Dow Jones consumer products. This includes acquisition, conversion, billing, identity, and retention — across WSJ, Barron's, MarketWatch, IBD, and related brands.

Commerce operates as a **platform team** — solutions typically need to work across multiple brands and surfaces.

## Team lead

**Daniel Hockley** — VP of Product, Commerce (Mar 2025–Present)
Reports to: Ryan Daly (SVP, Consumer Product)

## Teams within Commerce

| Team | Focus | Customer journey stage |
| --- | --- | --- |
| SEO | Organic search visibility and traffic acquisition across WSJ, MarketWatch, Barron's | Traffic & Audience Growth |
| Subscriber Acquisition | Paywalls, shop pages, checkout, registration, offers | Registration & Nurture → Conversion |
| Subscriber Engagement, Revenue & Retention | Onboarding, upsell, save offers, win-back, churn reduction | Activation → Engagement → Retention |
| Subscriber Mobile | Mobile app subscription commerce across iOS and Android | Spans acquisition through retention |
| Identity & Entitlements | Authentication, access control, user identity across all platforms and brands | Infrastructure layer |

## Customer journey framework

```
Traffic & Audience Growth → Registration & Nurture → Conversion → Activation → Engagement & Revenue → Retention & Win-back
        (SEO)                   (Reg, Newsletters)    (Paywall/Checkout)  (Onboarding)    (Upsell, CRM)      (Save offers, Win-back)
```

## Products

The Commerce team owns a portfolio of discrete applications and platforms spanning this journey. See `products.md` for the full inventory with descriptions and dependencies.

Key product areas:
- **Full-funnel infrastructure** — Mosaic (subscription platform), Automated Pricing (ML-driven personalized offers)
- **Acquisition** — Paywall & Onsite Placements, CAJ Shop Pages, CAJ Checkout, Free Registration, Newsletter Sign-up, Partner Landing Sites, WSJ+ Marketplace, Corporate Self-Serve Checkout
- **Engagement & Retention** — CAJ Subscription Onboarding, Subscriber Hub, Braze CRM
- **Identity & Access** — One Identity/OneID (AuthN), PIB Entitlements (AuthZ)
- **SEO** — HTML Sitemap/News Archive (plus XML Sitemap, Robots.txt, Topic Collection Pages)

## Key platforms and tools

- **Piano / Composer** — paywall and subscription management, A/B testing, onsite placement targeting
- **Mosaic** — core backend subscription platform (order processing, billing, fulfillment)
- **CAJ** — customer acquisition journey: checkout, shop pages, onboarding
- **SubHub (Subscriber Hub)** — subscriber self-service account management
- **OneID / DJOP** — unified identity and authentication platform across all DJ products
- **PIB Entitlements** — authorization and access control platform
- **Braze** — CRM, email, in-app messaging, push notifications
- **ActionIQ** — customer data platform (CDP) used for segmentation and targeting
- **Watson** — rules engine for offer targeting and save offers
- **Optimizely / Statsig** — A/B testing and experimentation
- **BRS** — billing and payment processing backend
- **JPD (Jira Product Discovery)** — roadmap and initiative tracking

## Strategic context

- Identity/authentication layer is increasingly strategic — first-party data, personalisation, and bundling all depend on it
- WSJ+ bundle strategy is a key growth lever — expanding multi-product subscriptions
- Legal, privacy, and InfoSec reviews are standard dependencies for anything touching identity or billing
- Platform team remit means solutions typically need to work across multiple brands and surfaces
- Checkout friction is a known gap vs. competitors (NYT, Bloomberg) — reducing drop-off is an ongoing investment
- Registered user base is a key growth area — free registrations act as a nurture layer before paid conversion

## FILE:products/commerce/products.md
# Commerce — Product Inventory

A reference guide to the discrete products and applications owned by the Commerce team. Grouped by area of the customer journey.

---

## Full-Funnel Infrastructure

### Mosaic
The core backend subscription platform underpinning all consumer acquisition, engagement, and retention across Dow Jones brands. Originally launched 2008 on Oracle technology, now fully cloud-based. Consolidates various subscription platforms and adheres to PCI, SOX, and GDPR requirements.

- Handles order processing, billing, entitlement fulfillment, and subscription lifecycle management
- Integrates with BRS (billing), Snowflake data lake, AWS, app stores (Google Play, iOS, Samsung), and payment processors (Apple Pay, PayPal, Amazon)
- Used by: all consumer brands (WSJ, Barron's, MarketWatch, IBD) and enterprise/partner subscribers

### Automated Pricing
A dynamic pricing system that uses machine learning models to deliver personalized subscription price points based on customer attributes, behavior, and market conditions.

- Operates across four journeys: acquisition (new subscribers), renewals (step-up pricing), saves (cancellation deflection), and winbacks (lapsed subscribers)
- ML models built and maintained by Data Science; rules engine (Watson) accepts customer parameters and surfaces appropriate offers
- Integrates with ActionIQ for email and social media delivery to external channels
- Owned jointly with Marketing Operations and Data Science

---

## Acquisition

### Paywall & Onsite Placements
The front-end experience controlling content access for non-subscribers and free registered users across consumer brand websites and apps.

- Built on Piano Composer for ruleset management, targeting, A/B test delivery, and in-built propensity scoring
- Supports multiple formats: roadblocks, scrims, in-situ paywalls, dual CTAs, snippet paywalls, live coverage paywalls
- Also manages registration walls (regwalls) that gate content behind free account creation
- Content Access is the backend system handling entitlement checks, OneID session handshake, article encryption/decryption, Automated Pricing integration, bot whitelisting, and Google Extended Access
- Revenue User Profile persists user profile data and enables segmentation via ActionIQ

### CAJ Shop Pages
Web-based subscription offer pages where users view, compare, and select subscription packages before proceeding to checkout.

- Mobile responsive; supports web-desktop, web-mobile, and in-app webview rendering for next-gen apps
- Shop page templates are built by CAJ engineering; CircOps can configure new pages with `?page=` params for campaign targeting
- Supports personalized offers via Watson (offer targeting), Automated Pricing, and A/B testing
- Serves all DJ brands with brand-specific theming

### CAJ Checkout
The checkout and payment experience for completing subscription purchases across all Dow Jones brands.

- Handles account creation, payment processing, and order confirmation
- Supports credit cards, Apple Pay, and PayPal; responsive across web, mobile web, and in-app webviews
- Brand-specific theming for WSJ, Barron's, MarketWatch, and IBD (IBD has a slightly different account creation flow)
- Key known friction: checkout takes ~3 minutes vs ~1 minute for competitors (NYT, Bloomberg); ongoing work to reduce drop-off

### Free Registration
A lightweight account creation experience for users coming from the paywall who don't yet have an account.

- Allows manual sign-up or social sign-in (Facebook, Google, Apple)
- Creates a registered user entitlement granting limited free article access across DJ brands for a defined period
- Acts as a nurture step before prompting users to subscribe
- In-article placement work ongoing to improve time-to-first-value

### Newsletter Sign-up
A minimal application allowing users to sign up for specific newsletters by submitting their email address.

- Supports both anonymous email entry and single-click sign-up for registered users
- Consistent experience across brands
- Surfacing additional newsletter sign-up opportunities in new areas is an active focus

### Partner Landing Sites (PLS)
A redemption and registration platform for subscribers who acquired access through third-party channels (corporate group sales, app stores, partnerships).

- Two main components: customer-facing redemption/registration flow and a Partner Admin Portal for managing licenses and seats
- Supports WSJ, Barron's, MarketWatch, Financial News London, Private Equity News, and Mansion Global
- Admin Portal enables bulk invitations, redemption tracking, and seat management for corporate partners
- Also serves as the entry point for app store subscribers who need to register a web account

### WSJ+ Marketplace
An exclusive in-subscription commerce hub where WSJ+ subscribers can discover and purchase additional premium Dow Jones products at subscriber-only rates.

- Consolidates supplementary products (newsletters, investing tools, educational resources) into a single place and a single bill
- Currently targets WSJ+ subscribers on every-4-week billing; annual subscriber expansion planned
- Partner content expansion (e.g. The Economist) in discussion
- Removes the fragmented purchasing paths that exist when users discover add-ons across different brand sites

### Corporate Self-Serve Checkout
A self-service purchase funnel for small to medium business customers buying WSJ group subscriptions (10-25 seats) without sales team involvement.

- Includes a corporate-focused marketing landing page and a streamlined checkout with seat selection
- Designed to remove friction in a traditionally long sales process
- Currently WSJ-only; expansion to other brands and products planned
- Integrates with existing corporate subscription management systems

---

## Engagement & Retention

### CAJ Subscription Onboarding
A guided post-purchase onboarding flow that helps new subscribers understand their benefits, set preferences, and take first steps toward engagement.

- Personalizes the experience based on interests, industries, and content preferences
- Prompts key activation actions: app download, newsletter subscriptions, feature education (watchlists, alerts)
- Also used for upgrade flows and CRM-triggered re-onboarding campaigns
- Optimized for Time to Value — getting subscribers to first meaningful content engagement quickly

### Subscriber Hub (SubHub)
A self-service account management platform for existing subscribers to manage subscriptions, billing, and account details across all DJ brands.

- Covers: payment updates, subscription upgrades/downgrades, cancellation, print delivery management, and customer support access
- Presents save offers (pricing alternatives, pauses) to subscribers attempting to cancel
- Aims to reduce calls to customer service by enabling self-service resolution
- Integrates with One Identity, Mosaic, Twilio, Genesys, and Watson

### Braze CRM
The primary marketing automation and messaging platform used to engage subscribers and prospects with personalized communications.

- Supports email, in-app messaging, push notifications, and content cards across web and mobile (iOS, Android)
- Integrates with ActionIQ (CDP) for audience segmentation and AppsFlyer for attribution tracking
- Used across: WSJ, Barron's, MarketWatch web and app platforms
- Migrating from previous solution (Airship) to Braze for mobile messaging

---

## Identity & Access

### One Identity (OneID) — AuthN
The authentication platform that creates, stores, and verifies user identities across all Dow Jones products.

- Assigns unique user identifiers used for cross-product tracking throughout the DJ ecosystem
- Supports persistent login, social sign-in (Facebook, Google, Apple), SAML/SSO, IP whitelisting, and token-based authentication (OAuth2/OpenID Connect)
- Stores PII and manages user sessions across web and mobile platforms
- Serves both B2C (WSJ, Barron's, MarketWatch) and B2B (Factiva, Risk & Compliance, Newswires, etc.) products
- Target: 100% token-based (OAuth2/OIDC) coverage across all products; currently ~85%

### PIB Entitlements (AuthZ)
The authorization platform that determines and enforces what content and features users can access based on their subscription level and organizational permissions.

- Manages entitlements for both consumer subscribers and enterprise/B2B users
- Handles complex subscription models, contractual rules, regional restrictions, and legal compliance controls
- Cross-product integration enables seamless content access across multiple DJ products in a single session
- Target: 100% entitlement coverage across all products; currently ~85% (some complex B2B platforms still migrating)

---

## SEO

### HTML Sitemap (News Archive)
A structured, crawlable directory of all WSJ content designed to maximize search engine crawl efficiency.

- Hierarchical structure (years > months > days > articles) provides access to all content within 5-6 clicks
- Includes orphaned content (videos, live coverage) not accessible from main navigation
- Pagination removed to reduce crawl waste
- Primary consumer is search engine crawlers; secondary use is archived content navigation for readers

> Note: The SEO team also owns XML Sitemap, Robots.txt, and Topic Collection Pages — see the SEO team section for full coverage.

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| All acquisition flows | One Identity (account creation/login) |
| All acquisition flows | Mosaic (order processing) |
| CAJ Checkout | BRS (billing), Mosaic, OneID |
| Paywall / Regwall | Piano Composer, Content Access, OneID |
| Automated Pricing | Watson (rules engine), Data Science ML models |
| Partner Landing Sites | OneID, PIB Entitlements |
| Subscriber Hub | Mosaic, OneID, Watson |
| Braze CRM | ActionIQ (CDP), AppsFlyer |
| WSJ+ Marketplace | CAJ Checkout, Mosaic, OneID |

## FILE:products/commercial-tech/products.md
# Commercial Technology — Product Inventory

A reference guide to the discrete products owned by the Commercial Technology team. Commercial Technology is a monetization-focused team within the Dow Jones B2C org, separate from Commerce. It owns the ad products, ad infrastructure, privacy platform, and internal tooling that power advertising across Dow Jones properties (~$300M+ digital advertising business).

---

## Ad Products

### SafeSuite
A set of brand safety and suitability tools that help advertisers avoid unsafe or misaligned content environments, ensuring campaigns run against trusted, high-quality inventory.

### Thematic AI
An AI-driven audience and content understanding product that identifies themes, topics, and intents in Dow Jones content and user behavior to power more precise targeting and insights.

### Theme Definer
A classification and taxonomy tool that standardizes how content and audiences are grouped into "themes," enabling consistent targeting, reporting, and packaging across products and campaigns.

### Dynatic
A dynamic advertising and experience product that uses data signals and creative rules to tailor ad experiences and placements, improving relevance and performance for advertisers.

### Ad Formats
A suite of proprietary ad formats for direct-to-subscriber experiences. Formats include Hero, Titan, Folio, VStudio, and Mosaic, as well as vertical and horizontal video (VAST/VPAID), native desktop/app placements, and a Dynamic Market Data Tool that integrates live financial data into ad creatives.

- Targets readers and subscribers directly; enables campaign-specific KPIs and custom executions
- Used by MMS Sales; an alternative to internal DJ Design/Consulting for custom advertising

---

## Ad & Privacy Platforms

### Ad Platform
Core ad-serving and configuration infrastructure that standardizes how ads are requested, rendered, and managed across Dow Jones properties. Includes shared components such as the Universal Ad Component and Orchestrator, plus Geneva for centralized ad configuration.

### Privacy Platform (DJCMP)
The Dow Jones Consent Management Platform middleware that sits between third-party CMPs (e.g. Sourcepoint / IAB SDK) and Dow Jones products. Provides a unified API and framework to enforce consent, vendor management, privacy notices, DSARs, and data retention across stacks and brands.

### Newsletters Ad Platform (NAPL)
An advertising platform for native ads in newsletters. Manages newsletter ad inventory, targeting, tracking, and campaign execution across brands — giving Sales and Ad Ops a consistent way to sell, deliver, and report on newsletter ad products.

---

## Information Systems

### InSite
A proprietary first-party data-powered audience analytics suite. Marries data from Adobe (web analytics), Google Ad Manager (ad server), and the Dow Jones CDP to provide audience-based insights not available from any single platform.

- **Pre-sale:** Provides first-party data insights to quantify and support specific product pitches to advertisers
- **Post-sale:** Delivers campaign/line item/creative audience performance metrics for mid-campaign optimisation and end-of-campaign reporting
- **Content Insights:** Leverages audience data from previous campaigns to refine renewal discussions and future pitches
- Used by Planning, AdOps, RevOps, Performance, Sales, and Client Success across MMS

### Seawolf
An internal product that protects the advertising exchange business via stewardship and execution controls. Addresses the gap in the Order Management System for exclusive sponsorship coordination and campaign health monitoring.

- **Buyout Calendar:** Allows the DOCS team to manage bookings with an accurate picture of buyout availability for exclusive sponsorships (e.g. homepage takeovers). Augments the OMS with "holds" to eliminate reliance on email/Slack for cross-team coordination across hundreds of exclusive products
- **Cadence:** Monitors active campaigns against pre-launch requirements and in-flight thresholds; proactively alerts AdOps when intervention is needed rather than discovering issues after the fact
- Key outcome: near-zero makegoods due to double-booking; alerts responded to in a timely manner

### Monty
An in-house tool that allows Sales to independently build contracts and generate real-time quotes for advertising deals without relying on Planning — enabling faster deal closure and more efficient use of people.

- **Monty (Digital):** For digital advertising deals; Sales can create contracts for simpler clients independently
- **Print Monty:** Equivalent tool for print advertising deals
- Metrics tracked: average time to create a deal, percentage of deals using Monty, YoY revenue, average deal size, win rate

### DASH
An internal advertising data and operations system built on Tableau. Aggregates data from multiple source systems (Google Ad Manager, AdBook, IAS, Megaphone, etc.) into a single interface for campaign performance monitoring and end-of-campaign reporting.

- Supports the MMS teams across Planning, AdOps, RevOps, Performance, Sales, and Client Success
- Under evaluation for potential deprecation if Looker meets all MMS use cases

### WSJBG Ad Manager (DanAds)
Previously known as DanAds and WSJ Ad Manager. A self-serve advertising platform powered by the DanAds platform, enabling advertisers and agencies to plan, buy, and manage campaigns directly — without IO processing or managed-service involvement.

- Primary audience: advertisers and agencies (new and existing), particularly SMB advertisers who would be turned away by Direct Sales due to budget size or bandwidth
- Supports credit card and invoicing payment options; real-time campaign management and optimisation
- Secondary audience: MMS Sales team (Client Associates, Associate Client Partners, Client Partners)
- Competes with programmatic platforms (Google, Meta, LinkedIn) for SMB ad budgets

### Looker
The business intelligence and analytics layer for Commercial Technology. Connects to Snowflake and provides curated dashboards and data models for advertising, revenue, and operations across MMS teams.

- Platform partner: Google (Looker Core)
- Primary users: Planning, Performance, AdOps; secondary users: Sales, Client Success, RevOps
- Positioned to replace DASH as the single BI tool for MMS if it meets all use cases
- Supports monitoring and analysis of campaign performance, internal insights, and client-facing reporting

## FILE:products/fnlondon/metrics.md
# Financial News London — Metrics

<!-- Add KPIs, subscriber counts, traffic benchmarks, and success definitions here -->

## Key metrics to track

- Digital subscriber count
- Subscription revenue
- Monthly unique visitors
- Newsletter open rates
- Awards/events attendance and revenue

## Notes

FN is a niche B2B-adjacent consumer product. Success metrics are less focused on mass volume and more on subscriber quality and retention among high-value finance professionals.

## FILE:products/fnlondon/overview.md
# Financial News London — Overview

## What it is

Financial News (FN) is a premium London-based digital and print publication covering the wholesale financial services industry in the UK and Europe. Effectively the trade paper for the City of London. Founded in 1996 by Angus MacDonald and John Benson; acquired by Dow Jones in 2007 for approximately £79 million. Sits within the Barron's Group division of Dow Jones alongside Barron's, MarketWatch, and Mansion Global.

Note: FN is a separate entity from the original *Financial News* founded in 1884 (which merged with the Financial Times in 1945).

## Audience

- Finance professionals in the City of London and broader European financial services sector
- Over 54% of readers are in senior management (C-suite, MDs, board members)
- Average reader income is high — exceeds the general finance professional population
- Key sectors: investment banking, asset management, private equity, regulation
- UK and Europe-primary; international readers in financial services

## Business model

Subscription-first with hard paywall, reflecting a narrow, high-value professional audience.

- Individual subscriptions at a significant premium vs. consumer publications
- Corporate licenses are the primary revenue driver — over 178 major firms (banks, law firms, consultancies) hold enterprise-wide licenses

## Coverage areas

- Investment banking: deals, M&A, IPOs, capital markets activity
- Asset management: institutional investing trends, fund performance, ESG
- Private equity: operates a specialized daily service, *Private Equity News*, covering European buyouts
- The People section: senior appointments and departures across the City — one of FN's most-read features
- Financial regulation: FCA, EU/ESMA, Basel updates in real time

## Key products and features

- **FN 100**: annual list of the 100 most powerful people in European finance; highly influential as a status signal in the City
- **FN Awards**: prestigious annual ceremonies including Awards for Excellence in Investment Banking
- **Private Equity News**: dedicated daily coverage of European private equity
- **Newsletters**: Morning Briefing and sector-specific updates
- **Events**: high-level roundtables and conferences in London for industry leaders

## Relationship to Dow Jones / WSJ

- Sits within the Barron's Group division of Dow Jones; editorially independent with UK-centric voice
- Shares Commerce infrastructure: OneID (authentication), Mosaic (subscription management), PIB Entitlements
- Partner Landing Sites (PLS) supports FN for corporate/group subscriptions
- Serves as the European counterpart to WSJ Pro — regional depth complementing WSJ's global breadth
- **LSEG Partnership (2024):** Multi-year deal with the London Stock Exchange Group; FN content integrated into LSEG Workspace (Bloomberg-equivalent terminal), significantly expanding reach to terminal users
- Enterprise custom news dashboards combining FN and WSJ content available for corporate clients

## FILE:products/ibd/metrics.md
# IBD — Metrics

<!-- Add KPIs, subscriber counts, benchmarks, and success definitions here -->

## Key metrics to track

- Total subscriber count (across all tiers: Digital, MarketSmith, Leaderboard, SwingTrader)
- Revenue by product tier
- Subscriber retention / churn rate
- IBD Live viewership and engagement
- Stock list performance (used as a marketing and credibility metric)

## Notes

IBD's product portfolio is tiered — many subscribers enter at base Digital and upgrade to MarketSmith or Leaderboard. Upgrade rate and LTV per subscriber are important commercial metrics.

## FILE:products/ibd/overview.md
# Investor's Business Daily (IBD) — Overview

## What it is

Investor's Business Daily (IBD) is a financial news and research platform focused on helping individual investors identify leading growth stocks using a disciplined, data-driven system. Founded in 1984 by William O'Neil as *Investor's Daily*; transitioned to digital-first in 2016; acquired by News Corp / Dow Jones in 2021 for $275 million. Operates as a stand-alone brand within the Dow Jones segment alongside WSJ and Barron's.

## Audience

- Self-directed retail investors and momentum/growth traders — primarily US-based
- Investors following a rules-based approach to stock picking
- Financial professionals using IBD data and ratings
- Increasingly targeting novice investors as an entry point into the DJ ecosystem (via MarketDiem newsletter)

## Business model

Subscription-first with a tiered product ecosystem, from free content to premium tools. Dow Jones also offers an "Investor Bundle" combining IBD Digital, WSJ, and Barron's at a combined rate. IBD is considered a high-margin digital pillar within News Corp's broader strategy.

## The CAN SLIM Methodology

IBD's signature stock-picking framework, developed by O'Neil by studying every top-performing stock since the 1880s. Each letter stands for a criterion:

- **C** — Current quarterly earnings (25%+ growth)
- **A** — Annual earnings growth (25%+ over 3-5 years)
- **N** — New product, service, management, or price high
- **S** — Supply and demand (high volume on price breakthroughs)
- **L** — Leader or laggard (buy the top stock in the top industry)
- **I** — Institutional sponsorship (follow the "smart money")
- **M** — Market direction (trade only in a Confirmed Uptrend)

## Key products and features

### IBD Digital (Base subscription)
- Full access to IBD.com editorial content — actionable and educational, not general news
- IBD Stock Lists: IBD 50, Sector Leaders, IPO Leaders, Big Cap 20
- Stock Checkup: free tool; "traffic light" (Green/Yellow/Red) evaluation of any stock's health against CAN SLIM criteria; entry point for non-subscribers
- IBD Ratings (all on 1-99 scale): Composite Rating (combined score), EPS Rating, Relative Strength (RS) Rating, SMR Rating (Sales growth, profit Margins, Return on equity), Accumulation/Distribution Rating
- Industry Group Rank: IBD tracks ~197 industry groups ranked 1-197; CAN SLIM investors focus on top-ranked groups
- Market Trend page / The Big Picture: daily guidance on market direction (Confirmed Uptrend, Uptrend Under Pressure, Market in Correction) — one of IBD's most-read features
- **IBD 50 ETF (ticker: FFTY):** managed by Innovator ETFs, tracks the IBD 50 list; extends IBD's brand into passive investing

### MarketSurge (formerly MarketSmith — rebranded March 2024)
Premium stock research and charting tool. Includes:
- Algorithmic pattern recognition (cup-with-handle, flat base, double bottom, etc.) with automatic buy point identification
- Proprietary "The Ants" indicator: flags intense institutional accumulation before a stock breaks out
- Fundamental data screening, earnings estimates, and historical price/volume analysis

### Leaderboard
A curated, actively managed list of top growth stocks meeting CAN SLIM criteria, with real-time buy/sell annotations from IBD analysts.
- Includes specific entry points, stop losses, and profit targets
- Designed as a "plug-and-play" service for investors who want analyst guidance

### SwingTrader
Shorter-term trade ideas for active traders with holding periods of days to weeks.
- Distinct from Leaderboard's longer-term growth stock focus

### IBD Live
A daily interactive broadcast where IBD analysts screen stocks and analyze charts in real time.
- Available weekday mornings; subscriber add-on

### Newsletters
- The Big Picture: daily market analysis interpreting IBD's Market Trend signals
- IBD 50: weekly list of top-rated growth stocks
- MarketDiem: newer newsletter targeting novice investors with simplified daily trade ideas; onboarding funnel into the IBD ecosystem

## Relationship to Dow Jones

- Acquired by News Corp / Dow Jones in 2021 for $275M; operates as a stand-alone brand with editorial independence
- Shares Commerce infrastructure: OneID (login/identity), PIB Entitlements (access), Mosaic (subscription management)
- CAJ Checkout handles IBD subscription purchases (slightly different account creation flow vs WSJ/Barron's)
- IBD proprietary data increasingly used as "clean" training data for Dow Jones financial AI models
- Bundled with WSJ and Barron's in the Investor Bundle

## FILE:products/mansionglobal/metrics.md
# Mansion Global — Metrics

<!-- Add KPIs, traffic benchmarks, listings volume, and success definitions here -->

## Key metrics to track

- Monthly unique visitors
- Property listings volume and active listings
- Listing lead generation (agent/broker contact requests)
- Advertising revenue
- Newsletter subscribers and engagement
- Search-driven traffic (SEO is a significant channel)

## Notes

Mansion Global's primary revenue model is listings and advertising rather than subscriptions, so traffic and lead generation metrics are more central than subscriber count.

## FILE:products/mansionglobal/overview.md
# Mansion Global — Overview

## What it is

Mansion Global is a digital-first luxury real estate and lifestyle platform owned by Dow Jones (News Corp). Launched in May 2015, it combines a global luxury property listings database with editorial content covering market analysis, lifestyle, and investment advice. It sits within the Dow Jones Barron's Group alongside Barron's, MarketWatch, and Financial News.

## Audience

- High-net-worth and ultra-affluent individuals buying, selling, or investing in luxury property globally
- 52% of readers are millionaires; average household net worth $2.2M, average household income $433K
- International audience: over 53% of traffic is from outside the US (significant EMEA and APAC reach)
- Real estate agents and brokers in the luxury segment

## Business model

Primarily advertising and listings-revenue led — free to access for consumers. Revenue drivers:

- Real estate broker/developer listing packages (tiered pricing based on volume — small batches to large developer inventories)
- Newsletter sponsorships and market page advertising
- Print supplement sales ("Experience Luxury" magazine, sold through WSJ Shop)

## Coverage areas

- Luxury residential property listings worldwide
- Market analysis: prime markets (London, NYC, Dubai, Hong Kong) and emerging luxury destinations
- Lifestyle and design: architecture, interior design, historic preservation, home technology
- Financial and tax advice for international property buyers
- Multilingual content: English, Spanish, and Chinese

## Key products and features

- **Property search portal**: searchable global luxury listings database with Lifestyle Search (filter by Golf, Historic, Beachfront, etc.)
- **"Experience Luxury" magazine**: quarterly print supplement distributed with The Wall Street Journal
- **Mansion Global TV**: program on Fox Business Network showcasing luxury homes and lifestyle trends
- **Mobile app**: dedicated app for property browsing and real-time market news
- **Newsletters**: daily market updates and listing highlights; newsletter sponsorships are a revenue driver

## Relationship to WSJ and News Corp

- Editorially independent from WSJ but operates as a close partner; produces the "Experience Luxury" WSJ print supplement and shares content with WSJ's Mansion section
- Part of News Corp's Digital Real Estate Services segment — the most profitable News Corp segment as of 2025
- Cross-platform relationships within News Corp: Realtor.com (News Corp owns ~80%, Mansion Global provides luxury top-of-funnel content) and REA Group (News Corp owns ~61%, Australia's leading property site)
- Shares DJ commerce infrastructure: OneID, PIB Entitlements, Mosaic
- Partner Landing Sites (PLS) supports Mansion Global for corporate/group subscriptions

## FILE:products/marketwatch/metrics.md
# MarketWatch — Metrics

## Primary KPIs

| Metric | Definition | Current value | Target |
| --- | --- | --- | --- |
| [Add] | [Add] | [Add] | [Add] |

## Notes

<!-- Data sources, caveats -->

## FILE:products/marketwatch/overview.md
# MarketWatch — Overview

## What it is

MarketWatch is a real-time financial news and market data platform covering markets, personal finance, and economic news. It has a broader, more mass-market audience than WSJ or Barron's, with heavy digital and mobile usage.

## Audience

- Retail investors and personal finance readers
- Broader and more general than WSJ/Barron's
- High traffic, high mobile usage

## Business model

Historically advertising-led; subscription component growing. MarketWatch became a subscription product, and the Commerce team has been building out its subscription surfaces.

## Key Commerce surfaces

- Paywall — Piano / Composer
- Shop pages — CAJ checkout
- Candy bar (promotional unit) — hompage acquisition surface
- Earnings Calendar — SEO-driven traffic surface

## Recent Commerce wins (FY26)

- MarketWatch mobile shop optimisation — 12% improvement in conversion to checkout; increased bundle take rate
- Google Extended Access for Search launched on MarketWatch (Oct 2025)
- MarketWatch ChatGPT auth/entitlements (Dec 2025)
- Earnings Calendar Enhancements — Q4 FY26 initiative to drive organic traffic via SEO
- MarketWatch hard paywall — 15% lift in conversions (historical win)

## Notes

MarketWatch is a significant SEO traffic source. The team is exploring a refreshed MarketWatch app with commerce features as a FY27 investment. The candy bar homepage unit is an in-progress initiative to bring MarketWatch into parity with WSJ and Barron's as a subscription-first homepage experience (WSJ candy bar converts at 7.24% click-through to subscribe).

## FILE:products/marketwatch/products.md
# MarketWatch — Product Inventory

A reference guide to the discrete products and features owned by the MarketWatch product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers MarketWatch-owned consumer experiences.

---

## Core Digital Products

### MarketWatch.com
The primary web destination for MarketWatch, one of the highest-traffic financial news sites in the US.

- Covers real-time market data, financial news, personal finance, economy, and investing
- Historically advertising-led; now subscription-first with a hard paywall driving conversions
- High SEO-driven traffic — organic search is a primary acquisition channel
- Key sections: Markets, Investing, Personal Finance, Economy, Real Estate, Retirement, Crypto
- Piano Composer-powered paywall; CAJ shop pages and checkout for subscription purchase
- Google Extended Access enabled for Search (launched Oct 2025)
- ChatGPT auth/entitlements integration live (Dec 2025)

### MarketWatch Mobile App
The native iOS and Android application for MarketWatch subscribers.

- Real-time market data, news alerts, and portfolio tracking
- Higher mobile usage mix than WSJ or Barron's, reflecting a broader consumer audience
- In-app subscription purchase via Apple IAP and Google Play billing
- New app rebuild under consideration as a FY27 investment to bring Commerce surfaces and improved UX

---

## Markets & Data

### Real-Time Quotes & Market Data
Core market data product — the primary reason many users visit MarketWatch.

- Real-time and delayed quotes for stocks, ETFs, mutual funds, indices, futures, currencies, and crypto
- Company pages with financials, analyst ratings, news, and historical data
- Pre-market and after-hours trading data
- One of the most-trafficked sections of the site; significant SEO value

### Watchlists & Portfolio Tracker
Personal investment tracking tools for registered and subscribed users.

- Create and manage custom watchlists for any asset class
- Portfolio tracker for monitoring holdings, performance, and allocation
- Syncs across web and mobile app

### Earnings Calendar
A structured, data-rich calendar of upcoming and recent corporate earnings releases.

- Shows expected EPS, revenue estimates, and historical results
- Q4 FY26 initiative: enhancements to drive organic search traffic via SEO
- High-intent traffic source for investors; major SEO entry point for the brand

### Economic Calendar
A schedule of key macroeconomic data releases (Fed decisions, jobs reports, CPI, GDP, etc.).

- Covers US and international economic events
- Paired with editorial context and analyst expectations

### Crypto Coverage & Data
Real-time cryptocurrency prices, news, and market data.

- Coverage of Bitcoin, Ethereum, and major altcoins
- Integrated into main market data infrastructure

### Virtual Stock Exchange (VSE)
A free, real-time paper trading simulator — one of the largest of its kind. Users practice investing strategies with virtual money using live market data, with no real capital at risk.

- Live data from NASDAQ, NYSE, and AMEX; supports Market, Limit, and Stop orders
- Default starting balance of $1,000,000 virtual cash; game hosts can configure $10,000 to $25,000,000 starting capital
- Supports US stocks, ETFs, and mutual funds (NASDAQ, NYSE, AMEX); no options, futures, or crypto
- Trade types: Buy, Sell, Short Sell, Buy to Cover; some games implement 15-minute execution delays
- Game/contest mechanics: configurable margin trading, interest rates on cash/margin, volume limits, and simulated transaction fees
- Leaderboards ranked by Total Return or Sharpe Ratio (risk-adjusted performance); private password-protected games for classrooms
- Classroom/education use: teachers can restrict trading to specific sectors or symbols, set semester-aligned start/end dates; widely used in finance and economics curricula globally
- Completely free; no paywall (distinct from MarketWatch Premium subscription for journalism)
- Available on MarketWatch.com and integrated into the MarketWatch mobile app (iOS/Android) with full cross-platform sync
- Recent mobile additions (late 2025/early 2026): Pivot Support/Resistance indicators, Stop Loss Target Calculator, Strength Meter
- Key limitation: dividends are not automatically credited, slightly disadvantaging long-term buy-and-hold strategies in competitions

---

## Newsletters

### Need to Know
MarketWatch's flagship pre-market morning newsletter covering the day's key themes and market setup.

- Sent weekday mornings; high open rate among active investors
- Available to subscribers and registered users

### The Moneyist
Personal finance advice column and newsletter.

- Covers reader-submitted financial dilemmas across inheritance, family finances, and consumer rights
- Engaged, loyal readership; strong social sharing

### Other newsletters
Additional newsletters covering retirement (Retirement Weekly), real estate, and market data digests. Full list managed by the Editorial Newsletters team.

---

## Acquisition Surfaces

### Candy Bar (Homepage Acquisition Unit)
A persistent promotional unit on the MarketWatch homepage designed to drive subscription conversions.

- In-progress initiative to bring MarketWatch into parity with WSJ (which converts at ~7.24% click-through to subscribe)
- Prominent placement above the fold; targeted to non-subscribers and registered free users
- Managed by Commerce team; editorial and product collaboration

### MarketWatch Mobile Shop Optimisation
Ongoing work to improve the subscription purchase funnel on mobile web.

- 12% improvement in conversion to checkout achieved (FY26)
- Increased bundle take rate via optimized offer presentation

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| MarketWatch.com & app | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| MarketWatch app | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Quotes & Market Data | Third-party data providers (Factset and others) |
| Earnings Calendar | SEO infrastructure, HTML Sitemap |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Candy Bar / Acquisition | Piano Composer (targeting), Automated Pricing, CAJ Shop Pages |
| ChatGPT integration | OneID (auth), PIB Entitlements (access) |

## FILE:products/wsj/metrics.md
# The Wall Street Journal — Metrics

## Primary KPIs

<!-- What are the top metrics this product is measured against? -->

| Metric | Definition | Current value | Target |
| --- | --- | --- | --- |
| [Add] | [Add] | [Add] | [Add] |

## Secondary metrics

<!-- Supporting metrics that inform health of the product -->

| Metric | Definition |
| --- | --- |
| [Add] | [Add] |

## How we measure success

<!-- Context on measurement philosophy, data sources, and tooling -->
- Data sources: [Add]
- Reporting cadence: [Add]

## Notes

<!-- Caveats, known data quality issues, etc. -->

## FILE:products/wsj/overview.md
# The Wall Street Journal — Overview

## What it is

The Wall Street Journal is Dow Jones's flagship publication — a daily newspaper and digital platform covering business, finance, politics, and world news. It is one of the most widely read English-language business publications in the US, and one of the largest paid digital news subscribers in the US.

## Audience

- Business professionals, executives, and investors
- Subscribers across consumer (B2C) and enterprise (B2B)
- US-primary with significant international readership

## Business model

Subscription-first. Revenue from:
- Digital subscriptions (direct)
- Print subscriptions
- Advertising
- WSJ+ bundle (multi-brand subscription with Barron's, MarketWatch, IBD)
- Licensing / syndication
- Enterprise / site licensing

## Key Commerce surfaces

- Paywalls — managed via Piano / Composer
- Shop pages — CAJ checkout platform
- Registration flows — Free Expression (free account creation)
- WSJ+ Marketplace — exclusive commerce experience for WSJ+ subscribers
- In-app subscription flows — iOS and Android (Piano Composer-powered)

## Recent Commerce wins (FY26)

- WSJ+ Marketplace launch (Oct 2025)
- Free Expression Phase 1 launch (Dec 2025) — registration wall; 149.6% of Q1 target
- Annual offer default on WSJ app — annual take rate increased from ~25% to ~50%
- In-situ checkout now default — 12% CVR lift for WSJ paywall
- WSJ iOS Onboarding Markets Card (Jan 2026)

## Notes

WSJ is the primary brand for most Commerce product work. Solutions built for WSJ are typically extended to Barron's and MarketWatch.

## FILE:products/wsj/products.md
# WSJ — Product Inventory

A reference guide to the discrete products and features owned by the WSJ product team. Grouped by area of the customer journey.

> Note: Commerce platform products (paywall, checkout, shop pages, onboarding, Subscriber Hub, identity) are documented separately in `products/commerce/products.md`. This file covers WSJ-owned consumer experiences.

---

## Core Digital Products

### WSJ.com
The primary web destination for WSJ editorial content and subscriber experience.

- Covers news, markets, opinion, lifestyle, real estate, and arts coverage
- Authenticated experience for subscribers; metered/paywalled for anonymous users
- Personalization via saved searches, watchlists, topic follows, and reading history
- Supports both desktop and mobile web; responsive design
- Key sections: Markets, Economy, Politics, Tech, Business, Life & Work, Books, Real Estate, Style

### WSJ iOS App
The native iPhone and iPad application for WSJ subscribers.

- Full editorial content access with offline reading
- Breaking news push notifications and personalized news alerts
- Markets data: stock quotes, watchlists, portfolio tracking
- In-app subscription purchase via Apple in-app purchase (IAP)
- Piano Composer-powered paywall for non-subscribers
- Recent additions: Markets onboarding card (Jan 2026), annual offer default (~50% take rate)

### WSJ Android App
The native Android application for WSJ subscribers.

- Feature-parity with iOS app; distributed via Google Play Store
- In-app subscription purchase via Google Play billing
- Push notifications via Braze

---

## Markets & Data

### Markets Data (Quotes & Watchlists)
Real-time and delayed market data tools embedded across WSJ.com and the WSJ apps.

- Stock, ETF, mutual fund, index, and futures quotes
- Personal watchlist creation and management for registered and subscribed users
- Pre-market and after-hours data
- Company pages with financials, news, and analyst data
- Powered by data providers including Factset and others

### WSJ Markets Hub
A dedicated markets section within WSJ.com aggregating market news, data, commentary, and tools in one destination.

- Live market coverage, earnings results, and economic calendar
- Integrates editorial content with live data feeds
- Entry point for users interested in investing and financial markets

---

## Newsletters

### The Morning Briefing (What's News)
WSJ's flagship daily newsletter summarizing the top business and world news stories.

- Sent weekday mornings; high-volume, high-open-rate product
- Available to both registered (free) users and subscribers
- Primary acquisition and engagement channel for email

### WSJ Opinion Today
Daily digest of WSJ Opinion section editorial and commentary.

- Sent weekday mornings to opinion-interested subscribers
- Distinct audience from main news newsletter

### Markets AM / The 10-Point
Markets-focused morning newsletters for finance and investing audiences.

- Covers pre-market moves, key economic data releases, and overnight international news

### Other newsletters
WSJ operates a portfolio of topic-specific newsletters covering areas including real estate, tech (CIO Journal, WSJ Pro), personal finance (Your Money Briefing), and lifestyle. Full list managed by the Editorial Newsletters team.

---

## Audio & Video

### WSJ Podcasts
Audio products distributed via Apple Podcasts, Spotify, and WSJ.com.

- Flagship show: "What's News" (daily news briefing, morning and evening editions)
- Other shows: "The Journal" (flagship long-form), "Opinion: Free Expression", "Heard on the Street", "Tech News Briefing", "Your Money Briefing"
- Subscriber-exclusive episodes exist on some shows; most content is free to grow top-of-funnel audience

### WSJ Live Video & Streaming
Video content available on WSJ.com and apps.

- Live market open and close coverage
- Breaking news live streams
- Video explainers and documentary-style features
- Subscriber-gated for full archive; some clips are free

---

## Personalization & Discovery

### My News
A personalized news feed on WSJ.com and apps based on followed topics, companies, and people.

- Users can follow topics (e.g., Federal Reserve, AI, Apple) to surface relevant articles
- Integrates with editorial curation for a hybrid algorithmic and editorial feed

### Alerts & Notifications
A system allowing subscribers to create custom alerts for breaking news, followed topics, and market movements.

- Available as push notifications (mobile), email alerts, and in-app notifications
- Market alerts: price thresholds, earnings announcements, company news
- Delivered via Braze; preferences managed in account settings

### WSJ Search
Full-text search across all WSJ content, including archive access for subscribers.

- Supports filtering by date, section, author, and content type
- News archive accessible to subscribers; recent headlines visible to non-subscribers
- SEO-significant; organic search is a major traffic driver

---

## WSJ Pro (B2B-adjacent, consumer-facing)

### WSJ Pro Subscriptions
Premium subscription tiers targeting professionals in specific verticals (private equity, venture capital, central banking, cybersecurity, sustainability).

- Separate from WSJ+ consumer subscription
- Includes exclusive newsletters, events access, and in-depth industry coverage
- Sold via direct sales and self-serve; priced at a significant premium to WSJ+
- Managed by the Pro editorial and product team; some Commerce platform overlap for checkout and identity

---

## Games & Lifestyle

### WSJ Crossword & Puzzles
A daily crossword and puzzle experience for WSJ subscribers.

- Available on WSJ.com and in the WSJ app
- Competitive with NYT Games as a subscriber engagement and retention driver
- Introduced as a subscriber benefit to increase non-news engagement

---

## Key cross-product dependencies

| Product | Depends on |
| --- | --- |
| WSJ.com & apps | One Identity (auth), PIB Entitlements (access), Piano Composer (paywall) |
| WSJ iOS/Android apps | CAJ Checkout (in-app webview), Braze (push/messaging) |
| Markets Data | Factset and third-party data providers |
| Newsletters | Braze (delivery), ActionIQ (segmentation) |
| Alerts | Braze, OneID user preferences |
| WSJ Search / Archive | HTML Sitemap (SEO crawl), Content Access (entitlement checks) |
| Personalization (My News, Watchlists) | OneID (user identity), subscriber entitlement data |

## FILE:teams/design/team.md
# Design Team

## Key contacts

| Name | Role | Area |
| --- | --- | --- |
| [Add] | [Add] | [Add] |

## Design system

<!-- What design system do we use? Where does it live? -->
- [Add]

## Notes

Last updated: [Add date]

## FILE:teams/engineering/team.md
# Engineering Team

## Key contacts

| Name | Role | Area |
| --- | --- | --- |
| [Add] | [Add] | [Add] |

## Team structure

<!-- How is engineering organized? By product? By platform? -->
- [Add]

## Notes

Last updated: [Add date]

## FILE:teams/org-chart.md
# Org Chart — Consumer Products, Dow Jones

> Last updated: 2026-03-20

## Full Consumer Products org (reports into Ryan Daly)

```
Ryan Daly — SVP, Consumer Products
│
├── Daniel Hockley — VP, Product Management (Commerce)
│   ├── SEO
│   │   └── Craig Casazza — Senior Product Director
│   │       └── Emily Schwartzberg — Senior Product Manager
│   ├── SUBSCRIPTIONS
│   │   ├── Katy Mastorakis — Senior Product Manager (Mobile Apps)
│   │   ├── Joe Stein — Product Manager II (Engagement, Revenue & Retention)
│   │   └── Leigh Hunt — Group Product Manager (Subscriber Acquisition)
│   │       ├── Shani Giersbach — Product Manager (Subscriber Acquisition)
│   │       └── Daniel Saxon — Product Manager II
│   └── IDENTITY
│       └── Adam Guttmann — Senior Product Manager
│
├── Robbie Sauerberg — VP, Product Management (WSJ / Barron's / MarketWatch / Consumer Platform)
│   ├── Nicholas Smolney — Senior Principal Product Manager
│   ├── Sian Barry — Product Manager II
│   ├── Caroline Albanese — Senior Principal Product Manager
│   ├── Lupe Rodarte — Senior Product Director
│   ├── Mikhail Dukhon — Principal Product Manager (Audience & Emerging Ad Platforms)
│   ├── Saurabh Uppal — Senior Product Manager (Mobile Platforms)
│   ├── Yolanda Parker — Senior Product Manager
│   ├── Cristhian Ruiz — CWR (Commercial Technology)
│   ├── Radhika Biradar — CWR (ETL Developer)
│   └── DESIGN (reporting into Robbie)
│       ├── Patrick Estanbouli — Sr Manager, Product Design
│       ├── Kyawt Thiri — Product Designer II
│       ├── Ying Chen — Product Designer I
│       └── Lauren Playford — Product Designer II
│
├── [OPEN HEAD] — VP, Product Management (WSJ) — reports to Ryan; Juan and Shema will report to this role
│   ├── Juan Velasquez — Senior Product Director (Wall Street Journal)
│   │   ├── Linus Li — Senior Product Manager
│   │   ├── Ruth Olumoroti — Product Manager I
│   │   └── John Channell — Senior Product Manager
│   └── Shema Kalisa — Senior Principal Product Manager (Wall Street Journal)
│       └── Noni Ghani — Product Manager I
│
├── Brett Krasnove — Senior Product Director (Wealth & Investing)
│   ├── Brendan Bryant — Senior Product Manager
│   ├── Grant Tunkel — Principal Product Manager
│   └── Kiersten Johnston — Senior Product Manager
│
└── DIRECT ICs (IBD / Consumer — report directly to Ryan)
    ├── Sidney Uttam — Product Manager II (sidney.uttam@investors.com)
    ├── Erin Low — Associate Product Manager (erin.low@investors.com)
    └── Courtney Freeman — Senior Product Manager (courtney.freeman@investors.com)
```

## Commerce leadership triad

| Discipline | People |
| --- | --- |
| Product | Daniel Hockley (VP) |
| Engineering | Ajith Ittan (VP), Ratheesh Nair (VP) |
| Design | Min Chung (VP), Jesús Gorriti (VP) |

## Key cross-functional partners

| Name | Role | Org |
| --- | --- | --- |
| Greg Ragon | SVP, Performance Marketing | Central Marketing Org |
| Sarah Hilston | VP, Global Acquisition & Paid Media | Central Marketing Org |
| Chris Stanco | VP, Engagement & Retention | Central Marketing Org |
| Belma Kolayli | Marketing Lead, Engagement | Central Marketing Org |
| Joanna Cipolla | Marketing Lead, Retention | Central Marketing Org |
| Sendi Vulaj | Marketing Lead, Revenue | Central Marketing Org |
| Lisa Checketts | Marketing PM | Central Marketing Org |
| Sridhar Maharna | PMO Director | Commerce Operations |
| Mushirah Kelley | Sr. Program Manager | Commerce Operations |
| Srini Kunamneni | Director, Engineering | Subscriptions |
| Thowfeeq Mustafa | Director, Engineering | Subscriptions / Identity |
| Krishna Venkatachalam | Sr Director, Engineering | Identity |
| Rajitha Sivaraman | Sr Director, Engineering | SEO |
| Rommel Rojas | Director, Product Design | Subs / SEO / Identity |
| Puneet Goel | VP Product, Platform | Platform |
| Emily C Williams | Senior Director, B2C Analytics | Data Engineering (reports to Mike Shaw, SVP) |

## FILE:teams/product/team.md
# Product Team — Commerce, Dow Jones

> Last updated: 2026-03-20

## VP

**Daniel Hockley** — VP of Product, Commerce (Mar 2025–Present)
Previously VP Product, Subscriptions (Sep 2024–Mar 2025)
Reports to: Ryan Daly (SVP, Consumer Product)

## Direct reports — managers

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Craig Casazza | Senior Product Director | SEO | Jul 21, 2025 |
| Leigh Hunt | Group Product Manager | Subscriptions – Subscriber Acquisition | Apr 13, 2020 |

## Direct reports — individual contributors

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Adam Guttmann | Senior Product Manager | Identity & Entitlements | Sep 2, 2025 |
| Katy Mastorakis | Senior Product Manager | Subscriptions – Mobile Apps | Apr 14, 2025 |
| Joe Stein | Product Manager II | Subscriptions – Engagement, Revenue & Retention | Jan 7, 2025 |

## Leigh Hunt's reports

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Shani Giersbach | Product Manager II | Subscriber Acquisition | Feb 2, 2026 |
| Daniel Saxon | Product Manager II | Subscriber Acquisition | Mar 10, 2025 |

## Craig Casazza's reports

| Name | Title | Team | Started |
| --- | --- | --- | --- |
| Emily Schwartzberg | Senior Product Manager | SEO | Feb 21, 2022 |

## Areas of ownership

| Area | PM(s) |
| --- | --- |
| SEO | Craig Casazza, Emily Schwartzberg |
| Subscriber Acquisition | Leigh Hunt, Daniel Saxon, Shani Giersbach |
| Subscriber Engagement, Revenue & Retention | Joe Stein |
| Subscriber Mobile | Katy Mastorakis |
| Identity & Entitlements | Adam Guttmann |

## FILE:teams/product/ways-of-working.md
# Ways of Working — Commerce Product Team

How the Dow Jones Commerce product team operates day to day.

## Team structure

Commerce operates as a **platform team** — serving both Consumer (B2C) and B2B sides of the business. Solutions typically need to work across multiple brands and surfaces.

## Leadership triad model

Every pod has a leadership triad with equal representation from Product, Engineering, and Design. The Commerce senior leadership triad:
- **Product:** Daniel Hockley (VP)
- **Engineering:** Ajith Ittan / Ratheesh Nair (VP)
- **Design:** Min Chung / Jesús Gorriti (VP)

## Quarterly planning

Commerce produces quarterly roadmaps aligned to annual OKRs. The planning process:

1. **Backlog review** — Product, Engineering, and stakeholders review existing backlog items and decide what to carry forward
2. **Force rank** — Stakeholders produce a force-ranked list of new and existing priorities
3. **LOE & capacity calculation** — Tech team produces high-level estimates; capacity calculated against available engineering sprints
4. **Roadmap proposal & alignment** — Tech, Marketing, Business, and Newsroom teams align on what is committed vs. backlogged

Each initiative is then:
- Categorised by objective (Acquisition, Retention, Revenue, Engagement, Identity, SEO, Enterprise)
- Assigned to a pod and PM
- Flagged for design dependency
- T-shirt sized (S/M/L) for Engineering and Design independently
- Assigned a deliverable type (Discovery / Design / Development / Backlog)

## Deliverable types

| Type | Meaning |
| --- | --- |
| Discovery | Product-led research; delivers problem statement, vision, solutions, ROI, and requirements |
| Design | Design & research delivers high-res, signed-off designs |
| Development | Engineering delivers code-complete, releasable product or feature |
| Backlog | Deferred — no work committed this quarter |

## T-shirt sizing

| Size | Duration | Sprints |
| --- | --- | --- |
| S | 2 weeks | 1 sprint |
| M | 6 weeks | 3 sprints |
| L | Whole quarter | ~3 months |

## Tracking tool

**Jira Product Discovery (JPD)** — status health tracked via RAG (Red / Amber / Green / On Hold)

## Working with marketing

The Central Marketing Org (CMO) is the primary consumer stakeholder. They are accountable for subscription targets and use Commerce products as one channel in an omni-channel strategy. Commerce and marketing teams are structured around the same customer journey stages: Acquisition, Engagement, Revenue, Retention.

## Key marketing partners

| Name | Role |
| --- | --- |
| Greg Ragon | SVP, Performance Marketing — overall marketing lead |
| Sarah Hilston | VP, Global Acquisition & Paid Media |
| Chris Stanco | VP, Engagement & Retention |

## Product philosophy

- Start with the problem, not the solution — work backwards, define and validate the problem first
- PRDs are thinking tools, not forms — writing forces clarity
- Collaborative by design — PRDs are built with the triad (PM, Design, Engineering), not handed down
- PRDs are living documents — maintained throughout development, not filed away after kickoff
- Shipping is an output, not an outcome — measure what changed in the world (subscriber growth, retention, engagement), not what the team delivered
- Use the double diamond — diverge to discover the problem fully, converge on solutions

## FILE:tech/data-sources.md
# Data Sources

Analytics platforms, data systems, and data tooling used across Dow Jones Commerce.

## Analytics leadership

| Name | Role | Reports to |
| --- | --- | --- |
| Emily C Williams | Senior Director, B2C Analytics | Mike Shaw (SVP, Data Engineering) |

## Key data and analytics teams

| Team | Role |
| --- | --- |
| B2C Analytics | Subscription performance data, experiment analysis |
| Data Science & Analytics | Experimentation analysis and insights; supports A/B test evaluation |
| Marketing Operations | Offer setup, onsite placements, CRM data |
| Data Engineering | Data pipeline dependencies |

## Subscription KPIs tracked

| Metric | Definition |
| --- | --- |
| ARPU | Average Revenue Per User |
| CVR | Conversion rate — % of paywall impressions resulting in subscription start |
| Churn | Rate at which subscribers cancel or lapse |
| Early-life engagement | Avg active days in subscriber's first 7 days |
| Bundle subscriptions | Number of subscriptions in a WSJ+ bundle |
| Bundle revenue | Total revenue from bundle subscriptions |
| Save offer take rate | % of subscribers presented with a save offer who accept it |
| Registered users | New free accounts created per month |
| Crawl coverage | % of priority content successfully crawled by search engines |
| Crawl waste | % of crawl budget spent on non-priority pages |

## Experimentation and testing

- Experiments run via **Optimizely** and **Statsig**
- Results analysis led by Data Science & Analytics team
- Statistical significance required before shipping experiment results

## Notes

Data quality: some FY26 OKR metrics (bundle revenue, bundle subscriptions) are noted as "metric TBC from business" — baseline definitions still being confirmed.

## FILE:tech/integrations.md
# Integrations

Key third-party systems and internal service dependencies.

## Third-party integrations

| Integration | Purpose | Team owner | Notes |
| --- | --- | --- | --- |
| [Add] | [Add] | [Add] | |

## Internal service dependencies

| Service | What depends on it | Team owner |
| --- | --- | --- |
| [Add] | [Add] | [Add] |

## Notes

## FILE:tech/stack.md
# Tech Stack

Key platforms, tools, and services used across Dow Jones Commerce.

## Subscription and paywall

| Technology | Used for | Notes |
| --- | --- | --- |
| Piano / Composer | Paywall management, A/B testing, subscription targeting, offer delivery | Primary paywall platform; migrated from Cxense |
| CAJ | Checkout and acquisition journey — the checkout platform | Used across WSJ, Barron's, MarketWatch |
| SubsHub | Subscription management — upsell, save offers, user profile, cancellation flows | |

## Identity and authentication

| Technology | Used for | Notes |
| --- | --- | --- |
| OneID / DJOP | Unified identity platform — single auth layer across all DJ products | All B2C traffic routed through DJOP tenant as of Nov 2025 |
| OAuth2 / OpenID Connect (OIDC) | Token-based access standard — replacing legacy authentication | Target: 100% coverage |

## CRM and engagement

| Technology | Used for | Notes |
| --- | --- | --- |
| Braze | CRM platform — mobile in-app messaging, push notifications, email campaigns, AppsFlyer integration | |
| AppsFlyer | App install attribution — integrated with Braze (Nov 2025) | |

## Experimentation and A/B testing

| Technology | Used for | Notes |
| --- | --- | --- |
| Optimizely | A/B testing | Used for onsite experimentation including "Candybar" promotion units |
| Statsig | Experimentation platform | |

## Project and roadmap management

| Technology | Used for | Notes |
| --- | --- | --- |
| Jira Product Discovery (JPD) | Roadmap tracking, initiative status, RAG health | |
| Confluence | Documentation, team wikis | Katy Mastorakis created Confluence hub for Commerce team |

## SEO infrastructure

| Technology | Used for | Notes |
| --- | --- | --- |
| Olympia | Rendering platform — News Types pages migrated here | |
| XML sitemaps | Crawl and indexing for WSJ, Barron's, MarketWatch | Canonical fix resolved 190k non-self-referencing URLs |

## Analytics

See `tech/data-sources.md` for full detail.

## Notes

- Legal, privacy, and InfoSec reviews are standard dependencies for anything touching identity, billing, or personal data — initiate early, not at launch
- Platform team remit: solutions must typically work across multiple DJ brands and surfaces

## FILE:process/product-development.md
# Product Development Process

How work moves from idea to shipped feature at Dow Jones Consumer Products.

## Document types

### 1-Pager
Used to sell a product idea and get stakeholder alignment. Comes before a PRD.

**Purpose:**
- Gain support for the idea — provide context for the problem being solved, for whom
- Define scope — what does the work entail, and what does it not include
- Set success metrics — what does success look like?

**Audience:** Stakeholders, leadership, team

### PRD (Product Requirements Document)
Expands on the 1-pager with deeper research, analysis, and execution detail. Created after the 1-pager has been socialised and discovery has begun.

**Purpose:**
- Defines the problem and solution for everyone who will work on it
- Defines requirements for MVP and beyond
- Sets expectations for stakeholders
- Reduces scope creep and assumptions

**Audience:** Product triads (PM + Design + Engineering), stakeholders, PMO

See `process/templates/1pager-prd-template.md` and `process/templates/brief-template.md`.

## Stages

### 1. Discovery
- Define and validate the problem before proposing solutions
- Key output: 1-Pager, problem statement, opportunity sizing
- Use the double diamond: diverge to discover the problem fully, converge on solutions

### 2. Definition
- Build the PRD in collaboration with the triad (PM, Design, Engineering)
- PRDs are living documents — maintained throughout development, not filed after kickoff
- Key output: PRD with requirements, success metrics, dependencies

### 3. Design
- Design and Engineering work together from the PRD
- Design reviews involve the triad and relevant stakeholders
- Accessibility is a standard consideration

### 4. Build
- Sprint structure: S (1 sprint / 2 weeks), M (3 sprints / 6 weeks), L (whole quarter)
- Tracking in Jira Product Discovery (JPD) with RAG status
- Deliverable types: Discovery / Design / Development / Backlog

### 5. Launch
- Governed by launch tier — not everything requires the same level of process
- Key dependencies: Legal/Privacy for anything touching identity or billing; InfoSec for data flows
- See `process/go-to-market.md`

### 6. Post-launch
- Success measured against pre-defined metrics — outcome-based, not output-based
- A/B test results reviewed and decisions made to ship, iterate, or kill

## Triad model

Every pod has a core triad: PM + Design + Engineering working together from discovery through delivery.

## Key tools

| Tool | Used for |
| --- | --- |
| Jira Product Discovery (JPD) | Roadmap, initiative tracking, RAG status |
| Confluence | Documentation, team wiki |

## Standard dependencies for identity/billing work

Legal, Privacy, and InfoSec reviews are standard for anything touching identity, authentication, billing, or personal data. These are not launch gates — they should be initiated early in discovery.

## FILE:process/templates/1pager-prd-template.md
# 1-Pager vs PRD

### TL;DR: Use a 1-Pager to sell a product idea and a PRD to build on it.

### **What is a 1-Pager?**

The 1-pager helps you put a stake in the ground. It clarifies what you are trying to do, what is your hypothesis, what are your expectations for success, and what the impact will be. This document will help you sell your idea to stakeholders and leadership, and to initiate Discovery with your triad and team.

**Purpose:**

1. Gain support for your idea \- provide context for the problem you’re solving, for whom
2. Define scope \- what does the work entail, and what does it *not* include
3. Success metrics \- what does success look like? What results do you expect?

**Audience:**

* Stakeholders
* Leadership
* Team

### **What is a PRD?**

A Product Requirements Document (PRD) is a document that helps a product manager develop an idea and communicate it to others involved in the project, so that work can be planned and execution can begin. It should come from the 1-pager and discovery.

**Purpose**

1. Defines the problem and solution for everyone who will work on it
2. Defines requirements \- information that is necessary for MVP and beyond
3. Sets expectations for stakeholders
4. Reduces scope creep
5. Reduces assumptions

**Audience**
A well-written PRD will provide information for various audiences, from triad partners, to start the conversation, to engineering teams, who will build the solution, to stakeholders, who are invested in the learnings or success of the solution. A PRD will become a working document that can be developed and referred back to as a project progresses.

# 1-Pager Template

### The 1-pager helps you put a stake in the ground. It clarifies what you are trying to do, what is your hypothesis, what is expected success, and what the impact will be. This document will help you sell your idea to stakeholders and leadership, and to initiate discovery with your triad and team. At this stage try not to be too prescriptive about what to deliver and leave space for collaborative development.

— \[Delete above this line\]
\[Initiative Title\]

**One-line Summary**
\[Write a TLDR; Capture the product’s objective as concisely as possible. Think of what problem are we solving, why is it important and what impact it might have? Provide clarity and context right from the start to help readers quickly grasp the initiative's purpose.

Example: “A paywall embedded within the video player prompting users to subscribe to continue watching.”\]

#### **Problem**

\[What is the problem, challenge or gap that’s been identified? Who does it affect? Try not to refer to the solution at this stage, just talk about the problem at hand. A problem statement should never just be the need for a specific feature we are hoping to build. Include any data or evidence you have that illustrates the problem.

Example: “We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content.”\]

**Goal(s) / Solution opportunity**
\[What does the solution need to achieve at a high level? If we solve this problem what will we get? What value will this work bring to the company, if it is successful? Conversely, what will DJ *miss out on* by not doing it? How will this give DJ competitive advantage?

Example: “If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on.”\]

#### **Risks and Mitigation**

\[What are known risks, and how do you plan to mitigate them?

Example: “Video views may drop overall, reducing advertising revenue.”\]

**Success Metrics**
\[What does success look like? How will you measure success? How will you validate progress and success?

Example: “Monthly paywall impressions”\]

**Proposed Solution(s)**
\[If you already have an idea or ideas for a solution, describe them here. Be directional but not prescriptive at UI level.

Example: “A paywall embedded in the video player, prompting users to subscribe.” is better than “An overlay on the video player with a button that links users to a shop page.”\]

**Must Haves**
\[List any mandatory requirements here. This doesn’t need to include everything, but should be based on what you know today.

Example: Must work across the website and mobile app.\]

# PRD Template

### The PRD expands on the 1-pager to provide more in-depth research, analysis and execution details. It is mostly created by the Product Manager, who is responsible for clearly defining what and why an initiative is important. How we accomplish the goal should be defined in close collaboration with Design and Engineering.

### Some of the information will come from your 1-pager, and some from discovery. The information you put into the PRD will help define your project so that the team can begin work.

— \[Delete above this line\]
\[Initiative Title\]

**One-line Summary**
\[Write a TLDR; Capture the product’s objective as concisely as possible. Think of what problem are we solving, why is it important and what impact it might have? Provide clarity and context right from the start to help readers quickly grasp the initiative's purpose.

Example: “A paywall embedded within the video player prompting users to subscribe to continue watching.”\]

#### **Problem**

\[What is the problem, challenge or gap that’s been identified? Who does it affect? Try not to refer to the solution at this stage, just talk about the problem at hand. A problem statement should never just be the need for a specific feature we are hoping to build. Include any data or evidence you have that illustrates the problem.

Example: “We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content.”\]

#### **Vision**

\[Make a statement about the impact you expect to make when this work is complete. How does this vision align with the [Dow Jones Mission and Vision](https://intranet.dowjones.com/home/ls/content/5294558629855232/who-we-are#mission)?

Example: “Turn our video content into a high volume subscription driver.”\]

**Goal(s) / Solution opportunity**
\[What does the solution need to achieve at a high level? If we solve this problem, what will we get? What value will this work bring to the company, if it is successful? Conversely, what will DJ *miss out on* by not doing it? How will this give DJ competitive advantage?

Example: “If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on.”\]

**Proposed Solution(s)**
\[If you already have an idea or ideas for a solution, describe them here. Be directional but not prescriptive at UI level.

Example: “A paywall embedded in the video player, prompting users to subscribe.” is better than “An overlay on the video player with a button that links users to a shop page.”\]

#### **Assumptions and Constraints**

\[What are the assumptions you are basing your hypothesis on? What are the technical, business, legal, or other constraints you know of?\]

#### **Audience**

\[Who is the audience or beneficiary for this solution? What do we know about them? Include any audience  you have or define the audience you want to serve. Consider who makes the purchasing decision, as in the customer, versus who will use this, as in the user, and who others might experience the consequences of its use.\]

#### **Success Metrics**

\[How will you measure success? How will you validate progress and success?\]

|  | *Name* | *Definition* | *Current Baseline Performance & Target* |
| :---- | :---- | :---- | :---- |
| **Topline Metric** | Example: Monthly Paywall impressions per pageview | The total number of times a paywall is seen by a user / overall pageviews per month | Baseline: 0.1 Target: 0.3 |
| **Secondary Metric** |  |  |  |
| **Counter Metric** | Example: Monthly video ad impressions | The total number of video ads viewed monthly | Baseline: 1.2M Target: Maintain the baseline. |

#### **Risks and Mitigation**

\[What are known risks, and how do you plan to mitigate them?

Example: “Video views may drop overall, reducing advertising revenue.”\]

#### **Scope & Requirements**

\[What user stories must be fulfilled by the solution? Design and engineering teams will use these to make sure the product achieves everything it needs to to fulfill the user and business needs. Try to focus on user needs without prescribing solutions. Leave enough space for design and engineering teams to explore multiple paths and solutions.\]

\[What is a must have or nice to have for MVP? What is not part of MVP, and can be added after launch? What is the definition of done, and what maintenance and monitoring should follow?\]

| Requirement Title | Description | User Story (optional) | Scope | Notes |
| :---- | :---- | :---- | :---- | :---- |
| Example: Sale pricing | The ability to change pricing that is displayed during sale periods or update pricing to match the current offer. | As a user, I want to see sale pricing within the video player so that I can quickly weigh up my purchasing decision and proceed to purchase. | MVP / Must have / Nice to have | Marketing operations should be able to run sales without the need for engineering involvement.  |
| Example 2: Flexible branding across DJs consumer brands. | … | … | … | … |

#### **Dependencies**

\[Does your solution have any dependencies on other teams or tooling? Are there Design, UX, or Accessibility considerations? Are there legal requirements or reviews that need to be incorporated into your plan? Are there any other teams or projects that are dependent on your solution, which might impact timing of your deliverable?\]

#### **Timing**

\[Is there a hard date by which this needs to be launched, or other timing considerations to be mindful of?\]

#### **RACI (Optional. For large initiatives)**

| Team | Responsible | Accountable | Consulted | Informed |
| :---- | :---- | :---- | :---- | :---- |
| **Product** | List teams and/or individuals |  |  |  |
| **Engineering** |  |  |  |  |
| **Design** |  |  |  |  |
| **Subscription Marketing** |  |  |  |  |
| **PMO** |  |  |  |  |
| **SEO** |  |  |  |  |
| **Data** |  |  |  |  |
| **Privacy/Legal** |  |  |  |  |
| **Customer Service** |  |  |  |  |

##

## **Tasks (Optional)**

\[For cross-functional work, break the project down into top level tasks, listing the major steps required to complete the project, who will own them, any dependencies, and links to relevant resources.\]

| Team | Task | Owner | Notes |
| :---- | :---- | :---- | :---- |
| UXD | Wireframes | Person | Not to reflect final designs. |
| Engineering | Technical discovery | Person | … |
|  |  |  |  |

**Other considerations:**
Legal considerations/requirements
InfoSec considerations/requirements
Design \+ UX Considerations
Accessibility needs
B2C considerations \- [Product Development Checklist](https://docs.google.com/document/d/1TAXM7idFoAb9f7DgIcWnFzm9GB6LTXXqHu5_wO-po6s/edit?tab=t.0)
B2B considerations
Marketing considerations
Prioritization (where does this fit in your roadmap)
User personas
Competitors

## FILE:process/templates/brief-template.md
# 1-Pager Template — Dow Jones Commerce

> A 1-Pager helps you put a stake in the ground. It clarifies what you are trying to do, what your hypothesis is, what success looks like, and what the impact will be.
> Use it to sell your idea to stakeholders and leadership, and to initiate discovery with your triad.
> At this stage, try not to be prescriptive about what to deliver — leave space for collaborative development.
> A PRD comes next. See `process/templates/prd-template.md`.

---

[Initiative Title]

**One-line summary**
[Write a TLDR. Capture the product's objective as concisely as possible. What problem are we solving, why is it important, and what impact might it have?

Example: "A paywall embedded within the video player prompting users to subscribe to continue watching."]

---

## Problem

[What is the problem, challenge or gap that's been identified? Who does it affect? Do not refer to the solution — focus on the problem. Include any data or evidence that illustrates it.

Example: "We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content."]

---

## Goals / Solution opportunity

[What does the solution need to achieve at a high level? If we solve this problem, what will we get? What will DJ miss out on by not doing it?]

---

## Risks and mitigation

[What are the known risks? How will you mitigate them?]

---

## Success metrics

[What does success look like? How will you measure it?

Example: "Monthly paywall impressions"]

---

## Proposed solutions

[If you already have solution ideas, describe them directionally. Be directional, not prescriptive at UI level.]

---

## Must haves

[List any mandatory requirements you know of today. This doesn't need to be exhaustive.

Example: Must work across the website and mobile app.]

## FILE:process/templates/prd-template.md
# PRD Template — Dow Jones Commerce

> This template reflects how the Commerce product team writes PRDs.
> A 1-Pager comes first (to get alignment) — a PRD expands on it with deeper research and execution detail.
> See `process/product-development.md` for when to use which.

---

[Initiative Title]

**One-line Summary**
[Write a TLDR. Capture the product's objective as concisely as possible. What problem are we solving, why is it important, and what impact might it have?

Example: "A paywall embedded within the video player prompting users to subscribe to continue watching."]

---

## Problem

[What is the problem, challenge or gap that's been identified? Who does it affect? Do not refer to the solution here — focus on the problem. Include any data or evidence that illustrates it.

Example: "We are unable to paywall videos consistently across platforms, missing out on an opportunity to convert subscribers on premium video content."]

---

## Vision

[Make a statement about the impact you expect to make when this work is complete.

Example: "Turn our video content into a high volume subscription driver."]

---

## Goals / Solution opportunity

[What does the solution need to achieve at a high level? If we solve this problem, what will we get? What will DJ miss out on by not doing it?

Example: "If we paywall video content within the player we will increase paywall impressions on video content and drive subscription revenue we would otherwise miss out on."]

---

## Proposed solutions

[If you have solution ideas, describe them directionally — not prescriptively at UI level.

Example: "A paywall embedded in the video player, prompting users to subscribe." is better than "An overlay on the video player with a button that links users to a shop page."]

---

## Assumptions and constraints

[What are the assumptions you are basing your hypothesis on? What are the technical, business, legal, or other constraints you know of?]

---

## Audience

[Who is the audience or beneficiary for this solution? Who makes the purchasing decision (customer) vs. who will use it (user)?]

---

## Success metrics

| | Name | Definition | Current baseline & target |
| --- | --- | --- | --- |
| **Topline metric** | Example: Monthly paywall impressions per pageview | The total number of times a paywall is seen / overall pageviews per month | Baseline: 0.1 Target: 0.3 |
| **Secondary metric** | | | |
| **Counter metric** | Example: Monthly video ad impressions | Total video ads viewed monthly | Baseline: 1.2M Target: Maintain baseline |

---

## Risks and mitigation

[What are the known risks? How will you mitigate them?

Example: "Video views may drop overall, reducing advertising revenue. Mitigation: monitor ad impressions as a counter metric."]

---

## Scope and requirements

| Requirement | Description | User story (optional) | Scope | Notes |
| --- | --- | --- | --- | --- |
| Example: Sale pricing | Ability to change displayed pricing during sale periods | As a user, I want to see sale pricing so I can make a quick purchasing decision | MVP / Must have | Marketing ops should be able to run sales without engineering involvement |

---

## Dependencies

[Other teams, tooling, Legal/Privacy/InfoSec reviews, or projects that depend on or block this work.

Note: Legal, privacy, and InfoSec reviews are standard for anything touching identity or billing — initiate early in discovery, not at launch.]

---

## Timing

[Hard deadlines, seasonal considerations, or other timing constraints.]

---

## RACI (optional — for large initiatives)

| Team | Responsible | Accountable | Consulted | Informed |
| --- | --- | --- | --- | --- |
| Product | | | | |
| Engineering | | | | |
| Design | | | | |
| Subscription Marketing | | | | |
| PMO | | | | |
| SEO | | | | |
| Data | | | | |
| Privacy/Legal | | | | |
| Customer Service | | | | |

---

## Tasks (optional — for cross-functional work)

| Team | Task | Owner | Notes |
| --- | --- | --- | --- |
| UXD | Wireframes | [Name] | Not to reflect final designs |
| Engineering | Technical discovery | [Name] | |

---

**Other considerations checklist:**
- Legal considerations / requirements
- InfoSec considerations / requirements
- Design + UX considerations
- Accessibility needs
- B2C considerations
- B2B considerations
- Marketing considerations
- User personas
- Competitive context

## FILE:process/templates/retrospective-template.md
# Retrospective: [Project / Sprint / Quarter]

**Date:** [YYYY-MM-DD]
**Facilitator:** [Name]
**Participants:** [Names]

---

## What went well

- [Add]

## What didn't go well

- [Add]

## What we'd do differently

- [Add]

## Action items

| Action | Owner | Due date |
| --- | --- | --- |
| [Add] | [Name] | [Date] |

## Notes

[Any additional context or discussion points]

---

*Template version: 1.0*

## FILE:style/design-principles.md
# Design Principles

Product design values and principles for Dow Jones.

## Core principles

<!-- What guides how we design products at Dow Jones? -->
- [Add principle and brief explanation]

## Design system

<!-- What design system do we use? Where does it live? -->
- [Add]

## Key UX conventions

<!-- Patterns and conventions that apply across products -->
- [Add]

## Accessibility standards

<!-- What are our accessibility commitments? -->
- [Add — e.g. WCAG 2.1 AA]

## Notes

## FILE:style/writing.md
# Writing Style — Dow Jones Commerce Product Team

Voice, tone, and conventions for internal product documentation.

## Core principles

- **Concise, direct, actionable** — shorter and clearer beats comprehensive and unread
- **Subheadings are essential** — use them in all substantive writing, even short documents. The best subheadings summarize the point, not just label the topic. A reader should understand the key idea from the heading alone.
- **Write for skim readers** — dense blocks of text lose people. Short paragraphs, clear headings, simple language.
- **Bullet points have limits** — keep lists to under 6 items. Each bullet should be one short sentence. If a bullet is running long, it's probably a paragraph. If a list is running long, break it into themed sections.

## Language

- Always use **American English** spelling: recognize, analyze, color, prioritize, optimize
- No emojis in professional documents
- Avoid internal jargon without explanation — use the glossary (`company/glossary.md`)

## PRD writing principles

- **Start with the problem, not the solution** — stakeholders often arrive with fully formed solutions; work backwards
- **PRDs are thinking tools, not forms** — writing forces clarity; if you struggle to define the problem, the initiative may not be ready
- **Be outcome-based** — success metrics should connect to subscription KPIs (paywall impressions, CVR, subscriber acquisition, churn, ARPU), not just outputs
- **Simple scales** — front-load with the most important information

## Naming conventions

| Preferred | Avoid | Notes |
| --- | --- | --- |
| The Wall Street Journal | WSJ (in external-facing copy) | WSJ is fine internally |
| MarketWatch | Market Watch (one word) | |
| Commerce team | Subscriptions team | Team was renamed to Commerce in Mar 2025 |
| OneID | One ID | Single word |

## Document audiences

| Document type | Primary audience |
| --- | --- |
| 1-Pager | Stakeholders, leadership |
| PRD | Product triad (PM + Design + Engineering), stakeholders, PMO |
| Roadmap | Leadership, marketing stakeholders, cross-functional partners |
| Quarterly planning summary | Tech, Marketing, Business, Newsroom teams |

## Writing for AI tools (this repo)

When writing context files for this repo:
- Be specific and factual — avoid vague generalities
- Use tables for structured information
- Mark placeholders clearly with `[Add]`
- Include "Last updated" dates where content may go stale
- Link to other files rather than duplicating content

## FILE:gemini-gem/gemini-gem-instructions.md
# Instructions for the DJ B2C PRD Generator

You are a Principal Product Manager on the Dow Jones Consumer Product team. You help product managers across the WSJ, Barron's, MarketWatch, and IBD teams write 1-Pagers and PRDs.

Read context-compiled.md before doing anything else. Use it to ground every document you generate. Do not ask questions already answered there.

## Your role

Your job is to follow the template exactly and produce rigorous, well-reasoned documents. That means:
- Ask probing questions to surface gaps, assumptions, and unstated requirements
- Challenge weak reasoning or under-defined problems — directly but constructively
- Suggest angles, risks, or opportunities the PM may not have considered
- Never flatter or pad. Be direct.

## Core rules

1. Never produce a full document until you have asked enough questions to write it well.
2. Always start with a 1-Pager. Only move to a PRD when the PM asks, or when the initiative is clearly past early discovery.
3. Ask clarifying questions first. Then draft. Then refine. In that order.
4. Challenge ideas inline during Q&A — frame as "have you considered..." or "one risk here is..."
5. If a problem statement is actually a solution in disguise, say so directly.

## Clarifying questions

Before drafting, ask clarifying questions to gather what each section of the template requires. Ask one question at a time — do not list multiple questions in a single response. Ask the most important question first, wait for the answer, then ask the next. Do not ask about information the PM has already provided.

## Template — 1-Pager

Work through these steps in order. Do not skip, rename, or reorder any of them.

1. **Initiative Title** — the name of the initiative
2. **One-line Summary** — one sentence: what problem, why it matters, what the impact could be
3. **Problem** — what is the problem and who does it affect? Do not refer to the solution here. Include data or evidence where available.
4. **Goals / Solution Opportunity** — what does solving this achieve? What will DJ miss out on by not doing it?
5. **Risks and Mitigation** — known risks and how they will be mitigated
6. **Success Metrics** — how will success be measured? Include a baseline and a target for each metric.
7. **Proposed Solution(s)** — directional description of the solution(s). Do not be prescriptive at UI level.
8. **Must Haves** — mandatory requirements based on what is known today

Before outputting the draft, verify every one of these 8 sections is present, in this order, using these exact headings. If any are missing or renamed, correct them before responding.

## Template — PRD

A PRD extends the 1-Pager. Work through these steps in order. Do not skip, rename, or reorder any of them.

1. **Initiative Title**
2. **One-line Summary**
3. **Problem**
4. **Vision** — the impact expected when the work is complete
5. **Goal(s) / Solution Opportunity**
6. **Proposed Solution(s)**
7. **Assumptions and Constraints** — assumptions the hypothesis rests on; known technical, business, or legal constraints
8. **Audience** — who benefits? Who makes the purchasing decision vs. who uses it?
9. **Success Metrics** — table with columns: Type (Topline / Secondary / Counter), Name, Definition, Baseline, Target
10. **Risks and Mitigation**
11. **Scope & Requirements** — table with columns: Requirement Title, Description, User Story, Scope (MVP / Must have / Nice to have), Notes
12. **Dependencies** — other teams, tools, legal/privacy reviews, timing dependencies
13. **Timing** — hard deadlines or timing constraints
14. **Tasks**

Before outputting the draft, verify every required section is present, in this order, using these exact headings. If any are missing or renamed, correct them before responding.

## Pre-flight check

Before presenting any draft document, you must output a pre-flight check. List every section heading you are about to include, in order, and confirm each one matches the relevant checklist above. Do not present the document until this check is complete. If any section is missing or uses a different heading, correct it first.

Example format:
```
Pre-flight check (1-Pager):
1. Initiative Title ✓
2. One-line Summary ✓
3. Problem ✓
...
All sections present and correctly named. Proceeding.
```

## Incomplete information

If you do not have enough information to populate a section, include the heading and write: [More information required]. If a table cell is unknown, write: [TBC]. Never omit a section or column because information is missing.

## Stakeholder Questions

If there are unresolved questions — anything unclear, missing, or needing stakeholder input — add a **Stakeholder Questions** section after the last template section. Omit it if there are no genuine open questions.

- List the question only. Do not answer it, speculate, or suggest an answer.
- Only include questions not already answered in the document
- Frame each as something a person could answer in a meeting
- Where possible, name who should answer (e.g. "Head of Growth", "Engineering lead", "Legal/Privacy", "Data team")

## Specialist modes

Invoke on request. Adopt the persona fully and produce the relevant output.

- **Critic** — overall quality and logic gaps
- **Subscriptions Strategist** — commercial logic, funnel, LTV, pricing
- **UX Advocate** — usability, accessibility, user journey
- **Legal/Privacy Reviewer** — GDPR, CCPA, data handling, compliance
- **Sr. Principal PM** — senior strategic challenge: right problem, right now, right-sized?
- **Competitive Analyst** — competitor landscape and feature benchmarks
- **User Researcher** — research plans, interview guides, assumption maps
- **Data Analyst** — measurement frameworks, metric definitions, instrumentation
- **Technical PM** — technical dependencies, complexity, engineering questions
- **Stakeholder Comms** — executive summary or presentation narrative from an approved PRD

Example: "Run the critic on this." / "What would the Sr. Principal PM say?"

## Writing standards

- **Concise and direct** — shorter and clearer beats comprehensive and unread
- **Subheadings summarize the point** — a reader should understand the key idea from the heading alone. You can extend a template heading with a descriptor (e.g. "Problem - The current flow is losing revenue") but never replace or rename it.
- **Write for skim readers** — short paragraphs, clear headings, simple language
- **Bullet lists** — max 6 items, one short sentence each
- **American English** — recognize, analyze, color, prioritize, optimize
- **No emojis**
- **No em dashes** — use a hyphen, a colon, or rewrite the sentence
- **No marketing jargon** — plain, specific language. "High-quality" not "premium", "useful" not "value-led", "improve" not "enhance", "problem" not "pain point", "goal" not "north star". Do not adopt the language of source documents — extract the substance and rewrite in plain language.
- **Outcome-based metrics** — connect to subscription KPIs (paywall impressions, CVR, subscriber acquisition, churn, ARPU). Always include a baseline and a target.
- **Naming conventions** — The Wall Street Journal (WSJ internally is fine), MarketWatch (one word), Commerce team (not "Subscriptions team"), OneID (one word)