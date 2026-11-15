# Case Study: Reading Term Sheets Like an Investor

| Instrument | Amount | Valuation | Artifact |
| ---------- | ------ | --------- | -------- |
| Convertible Promissionary Note | $40,000 | $2M cap at a financing / $1.5M cap at maturity, 30% discount | [Convertible Note](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/ConvertibleNote.pdf) |
| Series A Preferred Stock | $400,000 | $1.2M pre-money / $1.6M post-money | [Series A MOA](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/SeriesATermSheet.pdf) |
| Post-money SAFE | Template | Template | [Post-Money SAFE](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/PostMoney.pdf) |
| Seed Preferred Stock | Template | Pre-money, including the option pool | [Light Term Sheet](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/ExampleTermSheet.pdf) |
| Indie.VC Agreement | Template | Fixed ownership Percentage, no cap | [Revenue Redemption](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/IndieVCAgreement.pdf) |
| Calm Fund Company SEA | Template | Valuation cap, used only on conversion or sale | [Shared Earnings Ag.](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/SharedEarningsAgreement.pdf) |

---

# Part 1: Convertible Note ($40K Raise)

## Timeline

- **Lending:** the investor lends $40,000 on day 1. It starts as debt instead of ownership. It is due back with interest after 24 months
- **Debt Start:** 5% simple interest (`$2,000 per year`). $44,000 is owed at 24 months
- **Automatic Conversion:** if the company raises at least **$250,000** of new equity (a "Qualified Financing"), the note turns into shares
- **Maturity (24 months):** if no qualified financing has happened, the investor chooses:
    - **(1) Great:** convert into common stock at a **$1.5M** cap, which is cheap if the company has grown
    - **(2) Terrible:** demand repayment of `$44,000`, which a struggling startup may not be able to pay

## Answers to the Activity Questions
<details>
<summary><b>What type of investor does this deal?</b></summary>
<br>

Friends, family, or an early angel. $40K is a small, simple, unsecured check.

</details>

<details>
<summary><b>What type of company [entity] is this?</b></summary>
<br>

Virginia LLC.

</details>

<details>
<summary><b>What type of deal is this?</b></summary>
<br>

A convertible promissory note that produces debt now and equity later.

</details>

<details>
<summary><b>Where is this company located?</b></summary>
<br>

Virginia.

</details>

<details>
<summary><b>How much is being raised?</b></summary>
<br>

$40,000.

</details>

<details>
<summary><b>What is the company valuation?</b></summary>
<br>

Not set today. The note delays pricing until the next round, subject to a $2M cap, a 30% discount (converts at 70% of the new price), and a $1.5M cap if converted at maturity.

</details>

<details>
<summary><b>What happens if the company is acquired?</b></summary>
<br>

Before a qualified financing, the investor gets the greater of:
1. Principal and interest
2. What they'd receive by converting at the $1.5M cap

</details>

<details>
<summary><b>What two terms matter most?</b></summary>
<br>

1. The conversion price: the $2M cap and 30% discount
2. Maturity and repayment: what happens at 24 months if no round closes
</details>

## How Conversion Works

- The investor gets whichever price is lower that results in more shares
- The Cap Wins?
    - Next round at a $3M pre-money
    - 70% of $3M is $2.1M, but the cap is $2M, so the note converts at a $2M valuation
    - If converted at month 12: `$42,000 ÷ $2M ≈ 2.1%`
- The Discount Wins?
    - Next round at a $2.5M pre-money
    - 70% of $2.5M is $1.75M, so the note coverts at below the $2M cap
    - The discount applies: `$42,000 ÷ $1.75M ≈ 2.4%`
  
---

# Part 2: Series A Memorandum of Terms ($400K Raise)

## Answers to the Activity Questions
<details>
<summary><b>What type of company [entity] is this?</b></summary>
<br>

A Delaware corporation. This is the standard for VC-backed startups.

</details>

<details>
<summary><b>What type of deal is this?</b></summary>
<br>

Series A Preferred Stock Priced Equity Round.

</details>

<details>
<summary><b>Where is this company located?</b></summary>
<br>

Incorporated in Delaware, however, the operating location isn't stated.

</details>

<details>
<summary><b>How much is being raised?</b></summary>
<br>

$400,000.

</details>

<details>
<summary><b>What is the company valuation?</b></summary>
<br>

$1.2M pre-money means a $1.6M post-money. Investors own $400K ÷ $1.6M = 25%.

</details>

<details>
<summary><b>Can investors invest in future rounds?</b></summary>
<br>

Yes. Pro rata rights let them buy their share of new offerings ending at the IPO or 5 years after.

</details>

<details>
<summary><b>How much do investors get in a sale?</b></summary>
<br>

Their $400K back first, and then 25% of whatever is left at preferred participation.

</details>

## Option Pool Calculation
```
Pre-money  $1,200,000 (INCLUDING the employee option pool)
+ Raise      $400,000
= Post-money $1,600,000      →   Investors: 25%   |   Founders + Option Pool: 75%
```

## Investor Rights at a Glance
| Term | What it says | Who it favors |
| ---- | ------------ | ------------- |
| Liquidation Preference | 1x money back first, **then participates** pro rata with common | Investor (strongly) |
| Conversion | Optional 1:1 into common; automatic at an IPO or by majority vote | Neutral |
| Protective Provisions | 51% must approve charter changes, new preferred shares, merger, or sale | Investor |
| Redemption | After 5 years, investors can force the company to buy back shares at the original price | Investor |
| Drag-Along | Founders must vote for an approved sale | Investor |
| Anti-Dilution | Weighted average adjustment in a down round | Investor (moderate) |
| Board | 3 seats: 1 company, 1 investor, 1 mutually agreed independent | Balanced |
| Pro Rata Rights | Can buy into future rounds until the IPO or 5 years | Investor |
| Information Rights | Annual and quarterly financials, an annual budget, inspection rights | Investor |
| Founder Vesting | 1 year at closing, then monthly for 3 years. 1 extra year if fired within a year sold | Investor |
| Co-Sale | Founders can't sell shares without investors getting a chance to join or buy first | Investor |
| Founder Activities | Founders must work 100% of their time on the company | Investor |

## How Much Investors Get in a Sale
```
Investor Payout = $400K + 25% × (Sale Price − $400K)
```
| Sale price | Participating (This Term Sheet) | Investor % | Non-Participating (Standard) | Investor % |
| ---------- | ------------------------------- | ---------- | ---------------------------- | ---------- |
| $1M | $400K + $150K = **$550K** | 55% | $400K | 40% |
| $2M | $400K + $400K = **$800K** | 40% | $500K | 25% |
| $5M | $400K + $1.15M = **$1.55M** | 31% | $1.25M | 25% |
| $10M | $400K + $2.4M = **$2.8M** | 28% | $2.5M | 25% |

* The preference is participating with no cap where investors take their money back and 25% of the rest
* In a small sale, investors take far more than their 25% (55% of a $1M sale)
* The gap narrows in big outcomes, but investors always take more than their ownership share
* Founder's most important term to negotiate, followed by the 5-year redemption right, which lets investors demand their money back

---

# Part 3: The Twist: SAFE (Simple Agreement for Future Equity)

## What Makes a SAFE Different
* No interest, no maturity date, no repayment. The whiteboard's "terrible" maturity scenario doesn't exist
* There's no minimum size like the note's $250K threshold
* The investor's ownership is fixed upfront: `Ownership = Purchase Amount ÷ Post-Money Valuation Cap`
* The investor gets more of their money back in a sale or their as-converted share
* If the company shuts down, the investor is behind lenders, equal with other SAFEs and Preferred, and ahead of common stock
* No voting rights until it converts, and the investor must be **accredited**
* Valuation cap only with no discount

## Answers to the Activity Questions
<details>
<summary><b>What type of investor does this deal?</b></summary>
<br>

Angels and accelerators.

</details>

<details>
<summary><b>What type of company [entity] is this?</b></summary>
<br>

A corporation. SAFEs assume stock which doesn't fit an LLC model.

</details>

<details>
<summary><b>What type of deal is this?</b></summary>
<br>

A post-money SAFE with a valuation cap only.

</details>

<details>
<summary><b>How much is being raised?</b></summary>
<br>

Purchase Amount.

</details>

<details>
<summary><b>What is the company valuation?</b></summary>
<br>

Post-Money Valuation Cap.

</details>

<details>
<summary><b>What happens if the company is acquired?</b></summary>
<br>

Greater of money back (1x) or the as-converted value.

</details>

<details>
<summary><b>What two terms matter most?</b></summary>
<br>

1. Post-money valuation cap which sets ownership
2. Total SAFEs outstanding because stacking SAFEs quietly dilutes the founders

</details>

---

# Part 4: Light Seed Preferred Term Sheet

## What Makes It Different
* A short, founder-friendly version of the Series A in Part 2. The investor still gets preferred stock, but with far fewer protections
* **1x non-participating** liquidation preference: the investor takes their money back **or** converts to common, not both
* No redemption right, no anti-dilution, no drag-along and no dividends
* **Future Rights:** the investor automatically gets whatever better terms the next series of preferred gets
* **Binding Terms:** only the 30-day no-shop and confidentiality are legally binding

## Answers to the Activity Questions
<details>
<summary><b>What type of investor does this deal?</b></summary>
<br>

Accredited angels and seed funds approved by the company.

</details>

<details>
<summary><b>What type of company [entity] is this?</b></summary>
<br>

A corporation, [Delaware] in brackets as the default.

</details>

<details>
<summary><b>What type of deal is this?</b></summary>
<br>

A priced seed round of preferred stock.

</details>

<details>
<summary><b>How much is being raised?</b></summary>
<br>

Left blank: `$[_________]` in aggregate.

</details>

<details>
<summary><b>What is the company valuation?</b></summary>
<br>

A blank pre-money valuation **that includes the option pool**, so the pool dilutes the founders, not the new investors.

</details>

<details>
<summary><b>What happens if the company is acquired?</b></summary>
<br>

A sale counts as a liquidation. Preferred gets 1x its Original Issue Price (plus declared but unpaid dividends), and the rest goes to common. Investors can convert to common instead if that pays more.

</details>

<details>
<summary><b>What two terms matter most?</b></summary>
<br>

1. Pre-money valuation, and whether it includes the option pool
2. Liquidation preference, because 1x non-participating is the standard, founder-friendly version

</details>

## Investor Rights at a Glance
| Term | What it says | Who it favors |
| ---- | ------------ | ------------- |
| Liquidation Preference | 1x, non-participating | Balanced |
| Conversion | Optional 1:1 into common | Neutral |
| Protective Provisions | Majority of preferred must approve charter changes, new senior or equal preferred, buybacks, dividends, board size, or a sale | Investor |
| Information Rights | Major Purchasers only | Investor |
| Pro Rata Rights | Major Purchasers only | Investor |
| Board | Common, preferred and mutually agreed seats (blank counts) | Balanced |
| Expenses | Company pays investor counsel a flat $10,000 | Investor |
| Future Rights | Gets the next series' rights | Investor |
| Founder Vesting | 4 years, full acceleration on a double trigger, IP assigned to the company | Investor |
| No-Shop | 30 days, binding | Investor |

## Part 2 vs. Part 4 in a Sale (Same $400K for 25%)
| Sale price | Participating (Part 2) | Non-Participating (Part 4) |
| ---------- | ---------------------- | -------------------------- |
| $1M | $550K | $400K (takes the preference) |
| $2M | $800K | $500K (converts to common) |
| $10M | $2.8M | $2.5M (converts to common) |

---

# Part 5: Indie.VC Agreement (Revenue Redemption)

## How It Works
* The investor (OATV IV, LP, the fund behind Indie.VC) buys a fixed **Percentage** of the company for the Purchase Amount
* Starting on the Redemption Start Date, the company pays a monthly **Redemption Amount** equal to a % of **gross revenue**
* Payments stop at **3x the Purchase Amount** (the Max Redemption Payment)
* Each payment buys back part of the investor's stake. Paying the full 3x shrinks the Percentage to **1%**
* If the company later raises a priced round of at least the Conversion Trigger, the remaining Percentage converts into that round's preferred stock

## Example: $100,000 for 10%
- **Max Redemption Payment:** `3 × $100,000 = $300,000`
- **Redeemable stake:** 90% of the 10% = 9 points, so 1% always stays with the investor
- **After $100,000 paid (1x):** 3 points redeemed, so the investor owns 7%
- **After $300,000 paid (3x):** 9 points redeemed, so the investor owns 1%
- **Missed payments:** two months in a row, or any three in 12 months, let the investor demand the **entire $300,000 at once**

## Answers to the Activity Questions
<details>
<summary><b>What type of investor does this deal?</b></summary>
<br>

A revenue-focused VC (Indie.VC) backing companies that may never raise a big round.

</details>

<details>
<summary><b>What type of company [entity] is this?</b></summary>
<br>

A corporation (`[State] corporation`). It converts into preferred stock, so it assumes stock.

</details>

<details>
<summary><b>What type of deal is this?</b></summary>
<br>

A hybrid of equity and revenue-based financing: ownership now, repaid out of revenue later.

</details>

<details>
<summary><b>How much is being raised?</b></summary>
<br>

The Purchase Amount (blank).

</details>

<details>
<summary><b>What is the company valuation?</b></summary>
<br>

No cap or price. The Percentage fixes ownership, so the implied post-money valuation is `Purchase Amount ÷ Percentage` (for example, $100K ÷ 10% = $1M).

</details>

<details>
<summary><b>What happens if the company is acquired?</b></summary>
<br>

Before a Next Financing, the investor gets the greater of:
1. The current Percentage × the sale proceeds
2. The unredeemed Purchase Amount

</details>

<details>
<summary><b>What two terms matter most?</b></summary>
<br>

1. The Percentage, which sets ownership
2. The Redemption Amount and the 3x cap: a % of **gross revenue**, not profit, so it can squeeze a low-margin business

</details>

---

# Part 6: Calm Company Fund Shared Earnings Agreement

## How It Works
* The investor gets a **Percentage of Founder Earnings** each quarter, not ownership
* **Founder Earnings** = net income + founders' salaries, so founders can't avoid payments by paying themselves more
* Founders keep a **Founder Earnings Threshold** (per founder, per year) before anything is shared
* Payments stop once the investor receives the **Shared Earnings Cap** (__x the investment)
* If the company later raises a priced round, the investor can convert its **Equity Basis** (the greater of the unpaid cap or the investment) into shares at the lower of the round price or the **Valuation Cap**

## Example: $100,000 at 10%, $100K Threshold per Founder, 2 Founders, 3x Cap
- **Quarterly founder earnings:** $50,000 net income + $60,000 founder salaries = `$110,000`
- **Quarterly threshold:** `2 founders × $100,000 ÷ 4 = $50,000`
- **Shared this quarter:** `10% × ($110,000 − $50,000) = $6,000`
- **Payments stop at:** `3 × $100,000 = $300,000`

## Answers to the Activity Questions
<details>
<summary><b>What type of investor does this deal?</b></summary>
<br>

A fund backing profitable, bootstrapped "calm" companies that may never raise VC.

</details>

<details>
<summary><b>What type of company [entity] is this?</b></summary>
<br>

Not specified. The payments come from earnings, so it can work for an LLC, but the conversion clause assumes shares.

</details>

<details>
<summary><b>What type of deal is this?</b></summary>
<br>

A shared earnings agreement: profit-sharing up to a cap, with an option to convert to equity.

</details>

<details>
<summary><b>How much is being raised?</b></summary>
<br>

The Amount of Investment (blank).

</details>

<details>
<summary><b>What is the company valuation?</b></summary>
<br>

None today. The Valuation Cap only matters if the investor converts in a later priced round or the company is sold.

</details>

<details>
<summary><b>What happens if the company is acquired?</b></summary>
<br>

The investor gets the greater of:
1. Any unpaid amount of the Shared Earnings Cap
2. What it would receive by converting the Equity Basis at the Valuation Cap

</details>

<details>
<summary><b>What two terms matter most?</b></summary>
<br>

1. The Percentage and the Founder Earnings Threshold, which decide how much is paid each quarter
2. The Shared Earnings Cap, which decides when payments stop

</details>

## Investor Rights at a Glance
| Term | What it says | Who it favors |
| ---- | ------------ | ------------- |
| Information Rights | Standard rights, plus the records needed to verify Shared Earnings | Investor |
| Board Observer | Can attend board meetings, no vote | Balanced |
| Pro Rata Rights | Can buy into future equity rounds | Investor |
| Confidentiality | The only binding term | Investor |

---

## Conclusion
* **Note:** quick and cheap, but it's debt with a deadline. If no round closes in 24 months, the investor can pick the best outcome.
* **SAFE:** removes the debt risk entirely and fixes the investor's ownership upfront. Simpler for founders.
* **Series A:** sets the price, but the **participating preference** and **redemption right** shift a lot of value to investors in small sales.
* **Light Seed Preferred:** the same priced round with a **1x non-participating** preference and few extras, the founder-friendly baseline.
* **Indie.VC:** ownership the founder can **buy back out of revenue**, up to 3x. Good for companies that may never raise again, painful if margins are thin.
* **Shared Earnings:** no ownership unless the investor converts. Founders pay a share of **profits above their own salary threshold** until a cap. Built for profitable companies that don't want VC.

*Headline valuations are only part of the deal. Check who gets paid first, how much, and when before comparing offers.*
