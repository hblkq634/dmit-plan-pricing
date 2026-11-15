# Is DMIT Worth It? What $9.99/mo Buys, Why Two Different Plans Cost $36.9/Year, and Who Should Skip It (Plan, Price and Refund Tables)

DMIT is worth the money if you need a server that stays usable from mainland China between 8pm and 11pm, when cheap international routes fall apart. It is a bad buy if you just want a cheap box somewhere in the US, or if a Japan node is non-negotiable.

Entry price is **$9.99/month** for a Los Angeles CN2 GIA plan, and the limited annual plans start at **$36.9/year**. Those two numbers sit at opposite ends of the catalog and represent completely different products, which is the first thing most reviews fail to explain.

Below: every plan DMIT currently lists, the real latency numbers third-party testers report, the official refund terms (including the cases where you get nothing back), and the purchase mistake that costs people a year of bad routing.

> **Quick verdict**
> - **Most people asking this question:** LAX.Pro.TINY, $9.99/mo, 1 vCPU / 2 GB / 1 TB. Real CN2 GIA to all three Chinese carriers, cancel anytime.
> - **China Unicom or Mobile users who want more traffic per dollar:** LAX.EB.TINY, same $9.99/mo, 50% more traffic, CMIN2 return route instead of CN2 GIA.
> - **No Chinese users in your audience:** LAX.T1.TINY at $6.90/mo. Same hardware, international transit, roughly a third less.
> - 👉 [Check current DMIT plans and stock](https://www.dmit.io/aff.php?aff=9081)

Prices and configurations below come from third-party plan listings compiled from DMIT's site. Stock moves weekly and some pages are months old, so treat every figure as a starting point and confirm on the order page.

## Every DMIT plan, by product line

DMIT sells one thing in three grades: a KVM slice on AMD EPYC hardware, with the network quality as the variable you pay for.

- **Premium (Pro):** CN2 GIA on all three Chinese carriers. The most expensive, the most stable at peak.
- **Eyeball (EB):** CMIN2 from Los Angeles, CMI from Hong Kong. One step down, more traffic for the same money.
- **Tier 1 (T1):** International transit with no mainland China optimization. Cheapest.

### Los Angeles Premium (LAX.Pro), CN2 GIA

| Plan | vCPU / RAM / SSD | Traffic / port | Price | Order |
| --- | --- | --- | --- | --- |
| Pro.TINY | 1 / 2 GB / 20 GB | 1 TB / 1 Gbps | $9.99/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.Pocket | 1 / 2 GB / 40 GB | 1.5 TB / 4 Gbps | $14.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.STARTER | 2 / 2 GB / 80 GB | 3 TB / 10 Gbps | $29.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MINI † | 2 / 4 GB / 80 GB | 5 TB / 10 Gbps | $58.80/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MICROv3 | 4 / 4 GB / 160 GB | 7 TB / 10 Gbps | $74.99/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MEDIUMv2 | 4 / 8 GB / 160 GB | 14 TB / 10 Gbps | $168.88/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.Large | 8 / 16 GB / 320 GB | 25 TB / 10 Gbps | $338.88/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.GIANT | 8 / 24 GB / 640 GB | 50 TB / 10 Gbps | $620/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |

† Sources disagree on the vCPU count for Pro.MINI (2 vs 4). Confirm on the order page.

### Los Angeles Eyeball (LAX.EB), CMIN2 return

| Plan | vCPU / RAM / SSD | Traffic / port | Price | Order |
| --- | --- | --- | --- | --- |
| EB.TINY | 1 / 2 GB / 20 GB | 1.5 TB / 2 Gbps | $9.99/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| EB.Pocket | 2 / 2 GB / 40 GB | 3 TB / 4 Gbps | $14.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| EB.STARTER | 2 / 2 GB / 80 GB | 5 TB / 10 Gbps | $29.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| EB.MINI | 4 / 4 GB / 80 GB | 10 TB / 10 Gbps | $58.80/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| EB.MICRO | 4 / 4 GB / 160 GB | 14 TB / 10 Gbps | $74.99/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| EB.MEDIUM | 6 / 8 GB / 160 GB | 30 TB / 10 Gbps | $168.88/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| EB.Large | 8 / 16 GB / 320 GB | 50 TB / 10 Gbps | $338.88/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| EB.GIANT | 12 / 24 GB / 640 GB | 100 TB / 10 Gbps | $620/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |

Compare EB.TINY against Pro.TINY line by line: same $9.99, 500 GB more traffic, double the port speed, lower-grade route. That is the trade DMIT makes across the whole EB catalog.

### Los Angeles Tier 1 (LAX.T1), international transit

| Plan | vCPU / RAM / SSD | Traffic / port | Price | Order |
| --- | --- | --- | --- | --- |
| T1.TINY | 1 / 1 GB / 20 GB | 2 TB / 4 Gbps | $6.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| T1.STARTER † | 1 / 2 GB / 40 GB | 4 TB / 10 Gbps | $12.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| T1.MINI | 2 / 2 GB / 60 GB | 8 TB / 10 Gbps | $21.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| T1.MICRO | 4 / 4 GB / 80 GB | 16 TB / 10 Gbps | $32.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |

† One listing shows 2 vCPU for T1.STARTER. Confirm before ordering.

### Annual-only limited plans

These are the plans people search for by price. They are also the ones that sell out.

| Plan | vCPU / RAM | Traffic / port | Price | Order |
| --- | --- | --- | --- | --- |
| LAX.Pro.WEE | 1 / 1 GB | 500 GB / 500 Mbps | $36.9/yr | [Order](https://www.dmit.io/aff.php?aff=9081) |
| LAX.Pro.MALIBU | 1 / 1 GB | 1 TB / 1 Gbps | $49.9/yr | [Order](https://www.dmit.io/aff.php?aff=9081) |
| LAX.EB.WEE | 1 / 1 GB | 1 TB / 1 Gbps | $39.9/yr | [Order](https://www.dmit.io/aff.php?aff=9081) |
| LAX.T1.WEE | 1 / 1 GB / 20 GB SSD | 1 TB / 4 Gbps | $36.9/yr | [Order](https://www.dmit.io/aff.php?aff=9081) |
| HKG.Pro.MongKok | 1 / 1 GB | 200 GB / 150 Mbps | $149.9/yr | [Order](https://www.dmit.io/aff.php?aff=9081) |

### Hong Kong Premium (HKG.Pro), CN2 GIA

| Plan | vCPU / RAM / SSD | Traffic / port | Price | Order |
| --- | --- | --- | --- | --- |
| Pro.TINY | 1 / 1 GB / 20 GB | 500 GB / 1 Gbps | $39.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.STARTER | 1 / 2 GB / 40 GB | 1 TB / 1 Gbps | $79.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MINI | 2 / 2 GB / 60 GB | 1.5 TB / 1 Gbps | $119.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MICRO † | 2 / 4 GB / 80 GB | 2 TB / 1 Gbps | $159.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MEDIUM | 4 / 4 GB / 160 GB | 2.5 TB / 1 Gbps | $180/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.LARGE | 4 / 8 GB / 240 GB | 3 TB / 1 Gbps | $240/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.GIANT | 8 / 16 GB / 320 GB | 6 TB / 1 Gbps | $500/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |

† Sources disagree on the core count for HKG Pro.MICRO (2 vs 4).

Hong Kong Eyeball and Tier 1 exist but are poorly documented and frequently out of stock. The one plan with a stable public listing is HKG.EB.TINY: 1 vCPU / 1 GB / 20 GB, 1 TB at 1 Gbps, $29.90/mo. Everything else in those two lines needs checking on the product page.

### Tokyo (TYO)

Tokyo Eyeball was discontinued in March 2026. Pro and Tier 1 remain, and both go out of stock regularly. Current listings, from a snapshot dated August 2026:

| Plan | vCPU / RAM / SSD | Traffic / port | Price | Order |
| --- | --- | --- | --- | --- |
| TYO.T1.TINY | 1 / 1 GB / 20 GB | 2 TB | $6.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| TYO.T1.STARTER | 1 / 2 GB / 40 GB | 4 TB | $12.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| TYO.Pro.TINY | 1 / 1 GB / 20 GB | 500 GB / 1 Gbps | $21.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| TYO.Pro.STARTER | 1 / 2 GB / 40 GB | 1 TB / 1 Gbps | $45.90/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |

### The two specialized lines

| Plan | vCPU / RAM / SSD | Traffic / port | Price | Order |
| --- | --- | --- | --- | --- |
| sPro.CREATOR (DDoS-protected) | 2 / 2 GB / 20 GB | 1.5 TB / 100 Mbps | $71.99/quarter | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.uMINI (unmetered) | 2 / 2 GB / 20 GB | Unmetered / 30 Mbps | $239.99/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.uMICRO (unmetered) | 4 / 8 GB / 50 GB | Unmetered / 50 Mbps | $399.99/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.uMEDIUM (unmetered) | 4 / 8 GB / 80 GB | Unmetered / 100 Mbps | $799.99/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |
| Pro.uLARGE (unmetered) | 8 / 16 GB / 100 GB | Unmetered / 200 Mbps | $1399.99/mo | [Order](https://www.dmit.io/aff.php?aff=9081) |

sPro routes inbound traffic through Cloudflare Magic Transit (5 Tbps+ scrubbing) and returns over CN2 GIA. The unmetered line is priced for sustained throughput, not for volume: a 30 Mbps port running flat out moves roughly 9 to 10 TB a month, which a $168.88 Pro.MEDIUMv2 with 14 TB already covers. Buy unmetered when you need a guaranteed pipe, not a traffic allowance.

## What the premium actually buys

Two things: a route that holds up at peak, and hardware that isn't the bottleneck.

On the route, third-party testers report Los Angeles CN2 GIA sitting at **140–180 ms** between 20:00 and 23:00 China time with loss close to zero. One breakdown by carrier puts Telecom at 145–160 ms, Unicom at 150–170 ms, and Mobile at 170–190 ms, the last one detouring slightly. Hong Kong lands at roughly **10–50 ms**. Both figures are tester measurements under specific conditions, not vendor guarantees, and your own result depends on your ISP and city.

On the hardware, everything runs KVM on AMD EPYC, and the newer Los Angeles nodes have moved to the EPYC 9004 platform. No plan in the catalog is short of CPU for a normal web workload.

The operational detail that matters more than either: **T1 plans and some Eyeball plans throttle when you exhaust the traffic allowance instead of suspending the server.** LAX.T1.WEE drops to 100 Mbps after overage, Hong Kong and Tokyo T1 drop to 50 Mbps. A site that gets crawled hard at the end of the month keeps serving pages. Don't assume the same for Pro plans; that behavior isn't documented for them.

## When DMIT is the wrong purchase

Four cases where you should close the tab.

**You want the cheapest VPS you can find.** A $6.90 T1.TINY is fine hardware, but you can rent comparable international-transit capacity elsewhere for less. The premium here is for the China route, and if you're not buying the route you're overpaying for the logo.

**You need a Japan node this week.** Tokyo has four plans, two of them Pro, and all four disappear from stock regularly. Eyeball in Tokyo no longer exists. If your application needs a Japanese IP, plan around availability rather than assuming it.

**You have never configured an SSH key.** DMIT ships key-only authentication with password login disabled by default. There are Chinese-language tutorials on the site, and it's a twenty-minute problem for anyone who has done it before. For someone who hasn't, it's an evening, and support may or may not walk you through it in your language.

**You need to migrate between locations later.** Three regions, no free relocation. If your project might move from Los Angeles to Hong Kong in six months, that's a new order and a migration.

For the first and second cases, look at DMIT's T1 line or at a different provider entirely. For the third and fourth, budget the time or the rebuild.

## The real cost: monthly billing, annual billing, and why "recurring" matters

Almost every DMIT plan bills monthly. The annual prices you see in forum posts belong to a handful of limited plans that come and go.

That makes coupons the main lever on cost, and DMIT's coupons have an unusual property: most carry a `RECUR` or `RECURRING` suffix, meaning the discount applies to every renewal, not just the first invoice. A 20% recurring code doesn't save you 20% once; it sets your price for the life of the account.

| Plan | List price | Code | Effective rate | 12 months |
| --- | --- | --- | --- | --- |
| LAX.EB.TINY | $9.99/mo | 20% off, quarterly or longer | about $8.00/mo | about $96 |
| LAX.T1.TINY | $6.90/mo | 30% off, quarterly or longer | about $4.83/mo | about $58 |

Codes currently circulating in third-party listings:

- `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF` — Los Angeles EB, 20% off, quarterly billing or longer
- `2025-T1-HI-GSL-NON-MONTHLY-30OFF` — Los Angeles T1, 30% off, quarterly or longer
- `202510_HKG_TYO_PRO_20OFF_RECURRING` — Hong Kong and Tokyo Pro, 20% off, quarterly or longer
- `202510_HKG_TYO_T1_30OFF_RECURRING` — Hong Kong and Tokyo T1 (excluding WEE plans), 30% off, quarterly or longer
- `HKG-EB-V2-ANNUALLY-15OFF-RECUR` — Hong Kong EB, 15% off annual billing
- `HKG-T1-ANNUALLY-45OFF-RECUR` — Hong Kong T1, annual billing, reportedly with extra vCPU and doubled storage

Two sources list different codes for the Hong Kong and Tokyo T1 line, which suggests one set has been superseded. Apply the code in the cart and watch whether the discounted total survives to the renewal line before you pay. If it doesn't apply, the order page will tell you immediately, and a monthly order costs you nothing but the first month.

👉 [See which plans are in stock and apply a code at checkout](https://www.dmit.io/aff.php?aff=9081)

## The $36.9/year trap: two plans, identical price, different networks

This is the most expensive mistake in the catalog, and it's easy to make because both products cost exactly **$36.9/year**.

- **LAX.Pro.WEE** runs on CN2 GIA. 1 vCPU, 1 GB RAM, 500 GB of traffic at 500 Mbps.
- **LAX.T1.WEE** runs on international transit. 1 vCPU, 1 GB RAM, 20 GB SSD, 1 TB of traffic at 4 Gbps.

T1.WEE looks better on paper: twice the traffic, eight times the port speed. Those numbers describe a pipe, not a route. If your users are in China, T1.WEE gives you a fast port onto a congested path, and 4 Gbps of port speed does nothing for you at 9pm when the transit provider is dropping packets. Pro.WEE gives you half the traffic over the route you were actually shopping for.

The same logic runs through the whole catalog. Check the product line code in the plan name before you compare prices:

- `Pro` = CN2 GIA
- `EB` = CMIN2 from LA, CMI from Hong Kong
- `T1` = international, no China optimization
- `sPro` = CN2 GIA return plus DDoS scrubbing
- `Pro.u` = unmetered CN2 GIA

DMIT also warns that non-Pro lines can have their routing changed in response to attacks or cost pressure. If a specific route is the reason you're buying, buy Pro and stop optimizing.

## DMIT vs BandwagonHost, at the checkout level

Both sell CN2 GIA to the same audience, and the honest differences are operational rather than technical.

|  | DMIT | BandwagonHost |
| --- | --- | --- |
| China payment | Alipay and WeChat Pay accepted directly | Requires a workaround |
| IP replacement | Self-service since early 2026 | More cumbersome |
| Locations | Three regions, no relocation | More locations, can migrate between them |
| Control panel | Standard panel | KiwiVM, more polished, easier plan upgrades |
| Stock | Popular plans frequently unavailable | Generally broader availability |

Route quality between the two flagship lines is broadly comparable according to third-party write-ups. What decides it for most people is whether the flexibility of moving a server between data centers matters more than paying with Alipay in two clicks. If you'll want to relocate, BandwagonHost is the better fit. If you want to swap a blocked IP without opening a ticket, DMIT is.

## Limits worth knowing before you pay

**Stock is not reliable.** Los Angeles Pro.MINI, Pro.MICRO and Pro.MEDIUM have been out of stock long-term. Hong Kong and Tokyo high-end plans sell out regularly. Tokyo Eyeball is gone. If a plan matters to your project, don't plan a launch around a restock.

**Refunds follow a written policy, and it has teeth.** From DMIT's official documentation: full refund within 3 days if you've used **no more than 30 GB** of transfer; partial refund within 30 days, calculated against either remaining traffic or remaining time, whichever works out lower; processing typically within 48 hours. Refund to account credit is free. Refund to your original payment method deducts the payment provider's fee, except Alipay, where the fee is returned.

**Some reasons for a refund get rejected outright.** Being targeted by DDoS is excluded. So is "the network isn't good enough," IP geolocation complaints, and any IP that isn't reachable in some region once you've burned through 3 GB. Three refunds on the same product series ends the privilege. Read that list before you buy a route you haven't tested, because "the latency was worse than the review said" is explicitly not a refundable complaint.

**Blocked IPs.** The standard rule is one free replacement every 15 days, then $5 per change. Self-service replacement went live in early 2026, so you no longer wait on a ticket.

**Payment and language.** Alipay and WeChat Pay work directly, and there's Chinese-language documentation. Support quality in Chinese is reported inconsistently across sources; assume English tickets are the reliable path.

👉 [Start with a 3-day refundable plan and test the route yourself](https://www.dmit.io/aff.php?aff=9081)

## FAQ

**Can DMIT unblock Netflix and TikTok?**
Plans use native IPs, and testers report Netflix and TikTok working. The vendor makes no written guarantee, so treat it as a likely bonus rather than a feature you're paying for.

**What happens when I hit my traffic limit?**
On T1 plans and some Eyeball plans, the port is throttled and the server keeps running: 100 Mbps on LAX.T1.WEE, 50 Mbps on Hong Kong and Tokyo T1. Pro plans don't carry the same published behavior, so size your traffic allowance for Pro honestly.

**Can I get my money back if the latency is bad?**
Not on those grounds. The 3-day full refund requires under 30 GB of usage and excludes "network is not good enough" claims. Test with a monthly plan before committing to a year.

**Is it hard to set up for someone who has never used a VPS?**
Password login is off by default and SSH keys are required. Anyone who has generated a keypair before will be running in ten minutes. Complete beginners should expect to spend an evening on it.

**Do the coupons really apply to renewals?**
The ones ending in `RECUR` or `RECURRING` are described as recurring, which is a materially better deal than a first-invoice discount. Verify in the cart, since availability changes and some codes have been replaced.

## How to pick in one minute

- **Users in mainland China, latency is the whole point:** HKG.Pro.TINY at $39.90/mo. 10–50 ms beats any Los Angeles plan, and you pay for it.
- **Users in China, budget under $15/mo:** LAX.Pro.TINY at $9.99/mo. The cheapest real CN2 GIA in the catalog.
- **China Unicom or Mobile users, traffic-heavy, willing to accept CMIN2:** LAX.EB.TINY at $9.99/mo with the 20% recurring code.
- **Audience outside China:** LAX.T1.TINY at $6.90/mo or TYO.T1.TINY at $6.90/mo. Don't pay for a route nobody uses.
- **Facing DDoS:** sPro.CREATOR at $71.99/quarter.
- **Sustained throughput, no traffic ceiling:** the Pro.u line, starting at $239.99/mo.

Two things to confirm on the order page before you enter card details. First, the product line in the plan name matches what you think you're buying, because $36.9/year buys two very different networks. Second, the coupon applied and the discounted price carried through to the renewal terms rather than just the first invoice.

👉 [Compare DMIT's current plans, stock and renewal pricing](https://www.dmit.io/aff.php?aff=9081)
