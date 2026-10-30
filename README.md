# us vps cheap: Real Plan Prices Compared, the Fine Print Nobody Explains, and When BandwagonHost's CN2 GIA Line Is Worth the Extra Dollars

Cheap US VPS searchers usually land in one of two camps: people who want the absolute lowest monthly bill, and people who want a cheap server that still routes well. The US market currently starts at about **$2/month** — BuyVM's Slice 512 (1 vCPU, 512 MB RAM, 10 GB SSD) was the cheapest disk-included plan in the US as of October 27, 2026, with Vultr's Atlanta entry at $2.50 and CloudCone's Los Angeles SSD VPS at $2.33. BandwagonHost does not play in that basement. Its cheapest US-routable plan costs **$49.99/year**, and what you get in exchange is a network that budget hosts can't match: CN2 GIA routing into China, 2.5 Gbps ports on the entry ecommerce plans, and a 30-day refund window that third-party reviews describe as genuinely honored.

This article covers the full current plan list with real prices, the refund and billing fine print that most listicles skip, where BandwagonHost makes sense versus a $2–3 budget host, and when you should just pick the cheaper competitor.

> **Quick picks**
> - Most readers searching for a cheap US VPS with usable China routing: **CN2 GIA-E entry tier, 2 cores / 1 GB / 20 GB SSD / 1 TB traffic, $49.99 per quarter or $169.99 per year.**
> - Absolute cheapest with a US IP and no routing requirements: BuyVM at $2/mo, Vultr at $2.50/mo, or RackNerd's annual specials from $11.29/year — none of these offer CN2 GIA.
> - 👉 [Check BandwagonHost's current plan list and stock](https://bit.ly/BandwaGon)

## What "cheap" actually buys you in the US VPS market

There are two separate price floors in the US VPS market, and mixing them up is where most buyers waste money.

The first floor is raw hardware cost. Aggregator data covering 17 providers across 29 US cities shows the cheapest disk-included plans at **$2–2.50/month**: BuyVM Slice 512 ($2, verified October 27, 2026), Vultr's 1 vCPU / 0.5 GB cloud compute in Atlanta ($2.50), and CloudCone's Los Angeles SSD VPS 1 ($2.33 for 2 vCPU / 1 GB / 30 GB / 4 TB, per its own VPS page — note that page carries an old date, so treat it as indicative). Cloudnium's Los Angeles entry is $2.99 for 2 cores, 2 GB, 20 GB NVMe on a 10 Gbps uplink, which is aggressive for the price. For pure compute per dollar, Contabo's Cloud VPS 4 (4 cores / 8 GB) at $6.15/month scored 97/100 on the same aggregator's value index.

The second floor is cheap *plus good routing*. That's BandwagonHost's territory. Its cheapest plans start at $49.99/year — $4.17/month effective — which is uncompetitive on hardware alone. RackNerd, a frequent alternative in the same budget bracket, sells annual specials from $11.29/year with solid community feedback (a July 2026 user quote on a pricing tracker: "The KVM Special VPS price was absolutely awesome... support team was quick and resolved the issue in less than 3 hours"). What BandwagonHost charges extra for is the network: China Telecom's CN2 GIA line, which the company's own product page describes as solving "quality of service on routes to/from China." Third-party analysis reports tri-network return routing (CN2 GIA + CMIN2 + Unicom premium) with 140–180 ms latency from mainland China and low packet loss at peak.

If your server never talks to users in China, that premium buys you nothing — go cheap. If it does, this is the pricing tier where it starts to matter.

## BandwagonHost's full plan list and prices

BandwagonHost currently runs **5 plan families across 14 datacenters**: KVM (regular), CN2 GIA-E, CN2 special, Hong Kong CN2 GIA, and Japan CN2 GIA. One quirk worth knowing before you browse: the homepage only displays the KVM family. The other four are reachable through direct order links, and any tier can show "out of stock" at any time.

All plans are self-managed KVM with full root access, 1–10 Gbps uplinks, and the in-house KiwiVM panel (start/stop, OS reload, emergency console, rDNS management, snapshots, datacenter migration, API). Supported OS images cover AlmaLinux, RockyLinux, CentOS, Debian, Ubuntu, CentOS Stream, and Fedora, with additional bootable ISOs added on request.

### US-focused families: KVM, CN2 special, and CN2 GIA-E

| Plan (tier) | CPU / RAM / SSD | Traffic | Port | Price |
| --- | --- | --- | --- | --- |
| KVM 1GB | 2C / 1 GB / 20 GB | 1 TB | 1 Gbps | $25.99 / 6 mo or $49.99 / yr — [Order](https://bit.ly/BandwaGon) |
| KVM 2GB | 3C / 2 GB / 40 GB | 2 TB | 1 Gbps | $27.99 / qtr or $99.99 / yr — [Order](https://bit.ly/BandwaGon) |
| KVM 4GB | 4C / 4 GB / 80 GB | 3 TB | 1 Gbps | $19.99 / mo or $199.99 / yr — [Order](https://bit.ly/BandwaGon) |
| KVM 8GB | 5C / 8 GB / 160 GB | 4 TB | 1 Gbps | $39.99 / mo or $399.99 / yr — [Order](https://bit.ly/BandwaGon) |
| KVM 16GB | 6C / 16 GB / 320 GB | 5 TB | 1 Gbps | $79.99 / mo or $799.99 / yr — [Order](https://bit.ly/BandwaGon) |
| KVM 24GB | 7C / 24 GB / 480 GB | 6 TB | 1 Gbps | $119.99 / mo or $1199.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 1GB | 1C / 1 GB / 20 GB | 1 TB | 1 Gbps | $29.99 / 6 mo or $49.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 2GB | 1C / 2 GB / 40 GB | 2 TB | 1 Gbps | $27.99 / qtr or $99.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 4GB | 2C / 4 GB / 80 GB | 3 TB | 1 Gbps | $19.99 / mo or $199.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 8GB | 2C / 8 GB / 160 GB | 5 TB | 1 Gbps | $39.99 / mo or $399.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 16GB | 3C / 16 GB / 320 GB | 8 TB | 1 Gbps | $79.99 / mo or $799.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 GIA-E 1GB | 2C / 1 GB / 20 GB | 1 TB | 2.5 Gbps | $49.99 / qtr or $169.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 GIA-E 2GB | 3C / 2 GB / 40 GB | 2 TB | 2.5 Gbps | $89.99 / qtr or $299.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 GIA-E 4GB | 4C / 4 GB / 80 GB | 3 TB | 2.5 Gbps | $56.99 / qtr or $549.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 GIA-E 8GB | 6C / 8 GB / 160 GB | 5 TB | 5 Gbps | $86.99 / qtr or $879.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 GIA-E 16GB | 8C / 16 GB / 320 GB | 8 TB | 5 Gbps | $159.99 / qtr or $1599.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 GIA-E 32GB | 10C / 32 GB / 640 GB | 10 TB | 10 Gbps | $289.99 / qtr or $2759.99 / yr — [Order](https://bit.ly/BandwaGon) |
| CN2 GIA-E 64GB | 12C / 64 GB / 1280 GB | 12 TB | 10 Gbps | $549.99 / qtr or $5399.99 / yr — [Order](https://bit.ly/BandwaGon) |

Notes on migration: KVM and CN2 plans can switch between 8–9 datacenters (the KVM family spans 9, with 8 swappable); CN2 GIA-E spans 11 datacenters including the two CN2 GIA locations. One trap: migrating a KVM or CN2 plan **into** a CN2 datacenter cuts your monthly traffic to one third. Plan for the line you actually need upfront.

CN2 GIA-E is the ecommerce-oriented line — it includes the San Jose Equinix SV10 location with CN2 GIA, China Unicom, and China Mobile connectivity — and its SLA tiers carry a 99.99% uptime commitment versus 99.9% on standard plans.

### Hong Kong and Japan CN2 GIA (premium, fixed-location)

| Plan | CPU / RAM / SSD | Traffic | Location | Price |
| --- | --- | --- | --- | --- |
| HK 2GB | 2C / 2 GB / 40 GB | 500 GB | Hong Kong CN2 GIA, 1 Gbps | $89.99 / mo or $899.99 / yr — [Order](https://bit.ly/BandwaGon) |
| HK 4GB | 4C / 4 GB / 80 GB | 1 TB | Hong Kong CN2 GIA, 1 Gbps | $159.99 / mo or $1559.99 / yr — [Order](https://bit.ly/BandwaGon) |
| HK 8GB | 6C / 8 GB / 160 GB | 2 TB | Hong Kong CN2 GIA, 1 Gbps | $299.99 / mo or $2999.99 / yr — [Order](https://bit.ly/BandwaGon) |
| HK 16GB | 8C / 16 GB / 320 GB | 4 TB | Hong Kong CN2 GIA, 1 Gbps | $589.99 / mo or $5899.99 / yr — [Order](https://bit.ly/BandwaGon) |

Japan CN2 GIA offers the identical four configurations at identical prices, also fixed-location with no datacenter migration. These are orders of magnitude above the "cheap" bracket, so most readers of this article can ignore them; they exist for latency-sensitive workloads where $899/year for 500 GB of Hong Kong traffic is a business expense.

👉 [See the CN2 GIA-E tiers and current availability](https://bit.ly/BandwaGon)

## The pricing quirks that affect what you should actually order

Three things in this price list are easy to misread.

**Quarterly billing on CN2 GIA-E costs measurably more than annual.** The entry tier runs $49.99 per quarter, which is $199.96 over four quarters against $169.99 for annual — a $30 difference for the identical server. The 4 GB tier is steeper: $56.99 × 4 = $227.96 versus $549.99 annually... wait, that one runs the other way, and it exposes the second quirk.

**BandwagonHost's tiers are not priced in a straight line.** In the CN2 GIA-E family, the quarterly price for the 4 GB plan ($56.99) is *lower* than the quarterly price for the 2 GB plan ($89.99), and the 8 GB plan's quarterly price ($86.99) undercuts both. The annual prices scale normally, but if you insist on quarterly billing, the mid-tier 4 GB and 8 GB plans are disproportionately cheap. Check the per-quarter column before assuming the smaller plan saves money.

**There is no meaningful promo code in circulation right now.** The long-running BWHCGLUKKB code (6.77% recurring) stopped working in the second half of 2025, and the 2025 Black Friday code ILOVEBANDWAGON (11% recurring) was a seasonal release, not a standing offer. Historically the brand alternates between seasonal codes and limited-edition restocks; 2022–2024 saw no dedicated Black Friday codes at all. Any site advertising a permanent "biggest discount" code for BandwagonHost today is worth doubting. Your two real discount channels are Black Friday–style seasonal codes and the limited-edition plans — more on those below.

## The refund rules and billing behavior most articles skip

BandwagonHost offers a **30-day money-back guarantee on new orders**, backed by a published 99.9% uptime guarantee (99.99% on ecommerce SLA tiers). Community reports consistently describe refunds inside the window as no-questions-asked. That's better than most sub-$10 hosts, several of which offer no refund at all on their cheapest tiers.

The exclusions are where articles usually stop short. Per the published terms:

- Renewals are not refundable. The 30-day window covers your first order only.
- IPs that have been blacklisted (typically for spam or abuse) void the refund.
- Using more than **10% of your monthly transfer** voids it. If you plan to stress-test bandwidth on day 29, you've already forfeited the guarantee.
- There is **no automatic rebilling**. Nothing charges your card on renewal — if you don't pay, the server is suspended after seven days. For anyone burned by hosts that silently renew at full price, this is a feature; just don't confuse the silence with a free extension.

Combined effect: if you want to evaluate the CN2 GIA routing from your own network, do it in the first two weeks and keep transfer under 100 GB on the 1 TB entry plan.

## Limited-edition plans: the third price tier nobody's listicle mentions

Beyond the regular catalog, BandwagonHost maintains a rotating stock of limited-edition plans that sell at a fraction of regular pricing. The best-known example, THE PLAN 2024, offers 2 cores / 2 GB / 40 GB SSD / 1 TB monthly traffic / 2.5 Gbps with switching across 18 datacenters for **$99/year** — the closest regular-tier equivalent (CN2 GIA-E 2GB) runs $299.99/year. The current limited lineup spans roughly 25 SKUs, including MINICHICKEN ($19/year, Fremont), the Box series on CN2 GIA at DC99, and location specials for Tokyo, Amsterdam, and Sydney.

The catch is availability: stock is small, restocks are unscheduled, and popular tiers sell out in minutes. If your search for a cheap US VPS isn't urgent, watching for a restock of one of these can save 50–70% versus the regular list. If it is urgent, the regular CN2 GIA-E entry tier is the reliable version of the same deal.

## Who should not buy BandwagonHost

Being straight about the misses:

- **You just need the cheapest working US server.** At $2–3/month, BuyVM, Vultr, or CloudCone deliver 2–4× the hardware per dollar of anything in BandwagonHost's catalog, and RackNerd's $11.29/year specials undercut everything here. You lose CN2 GIA routing; if that phrase means nothing to you, you weren't going to use it.
- **You need managed hosting.** Every plan is self-managed. There's no control-panel hand-holding, no "fix my WordPress" support tier. If you've never touched a Linux shell, a managed VPS or even shared hosting will serve you better.
- **You want month-to-month flexibility at the entry tier.** The flagship $49.99 tier is quarterly or annual only. Sub-$3 hosts bill monthly and cancel anytime.
- **You're comparing raw specs against Contabo-class providers.** $6.15/month for 4 cores and 8 GB at Contabo makes BandwagonHost's $199.99/year 4 GB plan look expensive. Different products, different networks — but the hardware gap is real and worth acknowledging.

## FAQ

**Is BandwagonHost good for a US VPS on a budget?**
For budgets under $5/month with no China-routing requirement, no — RackNerd, BuyVM, and Vultr are cheaper. For roughly $4–5/month effective ($169.99/year) with CN2 GIA routing, a 2.5 Gbps port, and a 30-day refund window, the CN2 GIA-E entry tier is one of the few options at that price.

**What's the cheapest BandwagonHost plan?**
$49.99/year, available in both the KVM family (2 cores / 1 GB / 20 GB / 1 TB, billed half-yearly at $25.99) and the CN2 family (1 core / 1 GB / same specs, $29.99 half-yearly). Same sticker price, different routing and migration options.

**Can I migrate between datacenters later?**
Yes, through KiwiVM, but with limits: KVM and CN2 plans swap across 8 datacenters, CN2 GIA-E across 11, and Hong Kong/Japan plans can't migrate at all. Migrating into a CN2 datacenter reduces your traffic quota to one third.

**Do promo codes work right now?**
No standing code is currently active; the 6.77% recurring code expired in late 2025, and 2025's Black Friday code was seasonal. Expect the next genuine discount around a major sale event or a limited-edition restock.

## Before you order

Match the plan to the job: pure budget with a US IP → a $2–3/month competitor serves you fine; China-facing routing on a budget → CN2 GIA-E at $169.99/year, paid annually to beat the quarterly pricing; patient and price-sensitive → watch for a limited-edition restock before paying list price. And whichever tier you pick, remember the refund clock: 30 days, under 10% of your transfer, first order only.

👉 [Pick your plan and check live stock on BandwagonHost](https://bit.ly/BandwaGon)
