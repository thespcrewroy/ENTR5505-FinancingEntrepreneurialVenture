# Case Study: Reading Term Sheets Like an Investor

This activity compares three ways an early-stage company can raise money:

| Instrument | Amount | Valuation | Artifact |
| ---------- | ------ | --------- | -------- |
| Convertible promissory note (debt that converts to equity) | $40,000 | $2M cap at a financing / $1.5M cap at maturity, 30% discount | [Convertible Note](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/ConvertibleNote.pdf) |
| Series A Preferred Stock (priced equity round) | $400,000 | $1.2M pre-money / $1.6M post-money | [Series A MOA](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/SeriesATermSheet.pdf) |
| Post-money SAFE, valuation cap only (Y Combinator form) | Blank template | Post-money cap (blank) | [Post-Money SAFE](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/PostMoney.docx) |

## The Activity Questions
With a partner, answer the following for each term sheet.

**Convertible note ($40K raise):**
1. What type of investor does this deal?
2. What type of company [entity] is this?
3. What type of deal is this?
4. Where is this company located?
5. How much is being raised?
6. What is the company valuation?
7. What happens if the company is acquired? Why is this important?
8. What two terms are the most important to worry about in this term sheet?

**Series A Memorandum of Terms:**
1. What type of company [entity] is this?
2. What type of deal is this?
3. Where is this company located?
4. How much is being raised?
5. What is the company valuation?
6. What rights do the investors have?
7. Can investors continue to invest in future rounds of financing?
8. How much money do the investors receive in the event of a sale?

**Twist:** Repeat the analysis for a SAFE (Simple Agreement for Future Equity).

---

# Part 1: Convertible Note ($40K Raise)

## The Timeline from the Whiteboard
```
Day 1            Interest (5%)          Qualified Financing           24 months (Maturity)
|------------------------|------------------------|-----------------------------|
$40K lent         $2,000/year accrues     Automatic conversion          Voluntary conversion
as debt                                   if new equity ≥ $250K          (1) Great  or  (2) Terrible
```
- **Day 1:** the investor lends $40,000. It starts as **debt**, not ownership
- **Interest:** 5% simple interest, or `$40,000 × 5% = $2,000 per year`, so `$44,000` is owed at 24 months
- **Automatic conversion:** if the company raises at least **$250,000** of new equity (a "Qualified Financing"), the note turns into shares
- **Maturity (24 months):** if no qualified financing has happened, the investor chooses:
    - **(1) Great:** convert into common stock at a **$1.5M** cap, which is cheap if the company has grown
    - **(2) Terrible:** demand repayment of `$44,000`, which a struggling startup may not be able to pay

## Answers to the Activity Questions
| Question | Answer |
| -------- | ------ |
| What type of investor does this deal? | Friends, family or an early angel. $40K is a small, simple, unsecured check |
| What type of company [entity] is this? | A **Virginia LLC** (see the red flag below) |
| What type of deal is this? | A **convertible promissory note**: debt now, equity later |
| Where is this company located? | Virginia |
| How much is being raised? | **$40,000** |
| What is the company valuation? | **Not set today.** The note delays pricing until the next round, subject to a **$2M cap**, a **30% discount** (converts at 70% of the new price), and a **$1.5M cap** if converted at maturity |
| What happens if the company is acquired? | Before a qualified financing, the investor gets the **greater of** (a) principal + interest, or (b) what they'd receive by converting at the $1.5M cap |
| What two terms matter most? | (1) **The conversion price**: the $2M cap and 30% discount. (2) **Maturity and repayment**: what happens at 24 months if no round closes |

## How Conversion Works
```
Conversion price = the LOWER of:
   (i)  70% × price per share paid in the Qualified Financing   ← 30% discount
   (ii) $2,000,000 ÷ fully diluted shares before the round       ← valuation cap
```
- The investor gets whichever price is **lower**, which means **more shares**
- **Example A, the cap wins:** next round at a $3M pre-money. 70% of $3M is $2.1M, but the cap is $2M, so the note converts at a **$2M** valuation. If converted at month 12: `$42,000 ÷ $2M ≈ 2.1%`
- **Example B, the discount wins:** next round at a $2.5M pre-money. 70% of $2.5M is **$1.75M**, below the $2M cap, so the discount applies: `$42,000 ÷ $1.75M ≈ 2.4%`

## Why the Acquisition Clause Matters
* It protects the investor on **both sides**:
    * **Downside:** in a small sale they at least get their money back with interest
    * **Upside:** in a big sale they share in it as if they had converted at $1.5M
* **Example:** a $3M sale at month 12. Repayment = `$42,000`. Converting at the $1.5M cap ≈ `$42K ÷ $1.5M ≈ 2.8%` of $3M ≈ **$84,000**. The investor takes the larger amount, about **$84K**, roughly 2x in one year
* Without this clause, a founder could sell the company early and hand back only $42K, leaving the investor with none of the upside they took the risk for

## Red Flags and Fine Print
* **It's an LLC, but the note talks about "shares of Common Stock."** LLCs have membership units, not stock. Most VC funds won't invest in an LLC because of pass-through taxation, so the company will likely need to **convert to a C-corporation** before any qualified financing. An investor should ask who pays for that and when
* **Unsecured:** the note is a general unsecured obligation, so if the company fails, the investor stands behind any secured lenders
* **No prepayment without investor approval:** the company can't simply pay off the note early to avoid giving up equity
* **"Benefits of the Qualified Financing":** at the investor's option, they also receive the same rights as the new-round investors

---

# Part 2: Series A Memorandum of Terms ($400K Raise)

## Answers to the Activity Questions
| Question | Answer |
| -------- | ------ |
| What type of company [entity] is this? | A **Delaware corporation** (the standard for VC-backed startups) |
| What type of deal is this? | A **priced equity round**: Series A Preferred Stock |
| Where is this company located? | Incorporated in **Delaware**; the operating location isn't stated |
| How much is being raised? | **$400,000** |
| What is the company valuation? | **$1.2M pre-money**, so **$1.6M post-money**. Investors own `$400K ÷ $1.6M = 25%` |
| What rights do the investors have? | Liquidation preference, protective provisions, redemption, drag-along, anti-dilution, a board seat, information rights, pro rata rights, co-sale and right of first refusal (see the table below) |
| Can investors invest in future rounds? | **Yes.** Pro rata rights let them buy their share of new offerings, ending at the IPO or **5 years** after |
| How much do investors get in a sale? | **Their $400K back first, and then 25% of whatever is left** (participating preferred; see below) |

## The Valuation Includes the Option Pool
```
Pre-money  $1,200,000 (INCLUDING the employee option pool)
+ Raise      $400,000
= Post-money $1,600,000      →   Investors: 25%   |   Founders + option pool: 75%
```
*Because the option pool sits **inside the pre-money**, it dilutes only the founders, not the new investors. The founders' real valuation is lower than $1.2M*

## Investor Rights at a Glance
| Term | What it says | Who it favors |
| ---- | ------------ | ------------- |
| Liquidation preference | 1x money back first, **then participates** pro rata with common | Investor (strongly) |
| Conversion | Optional 1:1 into common; automatic at an IPO or by majority vote | Neutral |
| Protective provisions | 51% of the Preferred must approve charter changes, new Preferred shares, or any merger or sale | Investor |
| Redemption | After **5 years**, investors can force the company to buy back their shares at the original price | Investor (a "put") |
| Drag-along | Founders must vote for an approved sale | Investor |
| Anti-dilution | **Weighted average** adjustment in a down round | Investor (moderate) |
| Board | 3 seats: 1 company, 1 investor, 1 mutually agreed independent | Balanced |
| Pro rata rights | Can buy into future rounds until the IPO or 5 years | Investor |
| Information rights | Annual and quarterly financials, an annual budget, inspection rights | Investor |
| Founder vesting | 1 year credited at closing, then monthly over 3 years; 1 extra year of vesting if fired within a year of a sale | Investor |
| Co-Sale | Founders can't sell shares without investors getting a chance to join or buy first | Investor |
| Founder activities | Founders must work 100% of their time on the company | Investor |

## How Much Investors Get in a Sale
The preference is **participating with no cap**: investors take their money back **and** 25% of the rest.
```
Investor payout = $400K + 25% × (Sale price − $400K)
```
| Sale price | Participating (this term sheet) | Investor % | Non-participating (standard) | Investor % |
| ---------- | ------------------------------- | ---------- | ---------------------------- | ---------- |
| $1M | $400K + $150K = **$550K** | 55% | $400K | 40% |
| $2M | $400K + $400K = **$800K** | 40% | $500K | 25% |
| $5M | $400K + $1.15M = **$1.55M** | 31% | $1.25M | 25% |
| $10M | $400K + $2.4M = **$2.8M** | 28% | $2.5M | 25% |

* In a **small sale**, investors take far more than their 25% (55% of a $1M sale)
* The gap narrows in big outcomes, but investors **always** take more than their ownership share
* **This is the founders' most important term to negotiate**, followed by the 5-year **redemption right**, which lets investors demand their money back from a company that's surviving but not growing

---

# Part 3: The Twist: SAFE (Simple Agreement for Future Equity)

## What Makes a SAFE Different
* **It isn't debt:** no interest, no maturity date, no repayment. The whiteboard's "terrible" maturity scenario doesn't exist
* **It converts in any priced round:** there's no minimum size like the note's $250K threshold
* **Post-money cap:** the investor's ownership is fixed upfront: `Ownership = Purchase Amount ÷ Post-Money Valuation Cap`
    * Example: $100K on a $5M post-money cap = **2%**, regardless of how many other SAFEs the company sells
    * Every later SAFE and any option pool increase dilutes the **founders**, not this investor
* **In a sale:** the investor gets the **greater of** their money back (the "Cash-Out Amount") or their as-converted share (the "Conversion Amount"). This works like the note's acquisition clause, but with no interest
* **If the company shuts down:** the investor is behind lenders, equal with other SAFEs and Preferred, and ahead of common stock
* **No voting rights** until it converts, and the investor must be **accredited**
* This version has a **valuation cap only**, with no discount

## Answers to the Activity Questions
| Question | Answer |
| -------- | ------ |
| What type of investor does this deal? | Angels and accelerators (it's Y Combinator's standard form) |
| What type of company [entity] is this? | A **corporation** (state left blank). SAFEs assume stock, so like the note, it doesn't fit an LLC |
| What type of deal is this? | A **post-money SAFE, valuation cap only** |
| Where is this company located? | Blank: the template is filled in per deal |
| How much is being raised? | Blank ("Purchase Amount") |
| What is the company valuation? | Blank ("Post-Money Valuation Cap") |
| What happens if the company is acquired? | Greater of money back (1x) or the as-converted value |
| What two terms matter most? | (1) **The post-money valuation cap**, which sets ownership. (2) **Total SAFEs outstanding**, because stacking SAFEs quietly dilutes the founders |

## Convertible Note vs. SAFE vs. Series A
| Feature | Convertible Note | SAFE | Series A Preferred |
| ------- | ---------------- | ---- | ------------------ |
| Is it debt? | Yes | No | No |
| Interest | 5% | None | None |
| Maturity | 24 months | None | Redemption after 5 years |
| Valuation set now? | No (cap + discount) | No (cap only) | Yes ($1.2M pre) |
| Converts when | Equity round ≥ $250K | Any priced equity round | Already equity |
| Sale before conversion | Greater of repayment or as-converted value | Greater of 1x or as-converted value | Participating 1x preference |
| Board seat / control | None | None | Board seat, protective provisions |
| Legal cost and speed | Low and fast | Lowest and fastest | High and slow |

---

## Conclusion
* **Convertible note:** quick and cheap, but it's debt with a deadline. If no round closes in 24 months, the investor can pick the outcome that's good for them (convert cheaply) or bad for the company (demand $44K)
* **SAFE:** removes the debt risk entirely and fixes the investor's ownership upfront. Simpler for founders.
* **Series A:** sets the price, but the **participating preference** and **redemption right** shift a lot of value to investors in small.
* **The lesson:** headline valuations are only part of the deal. Check **who gets paid first, how much, and when** before comparing offers

## Practical Caveat
*These are teaching documents with blanks and simplified terms, not legal advice. Exact payouts depend on the final share counts and definitions in the signed agreements, and founders should have a lawyer review any term sheet before signing.*
