# Case Study: Reading Term Sheets Like an Investor

| Instrument | Amount | Valuation | Round |
| ---------- | ------ | --------- | -------- |
| Convertible Promissory Note | $40,000 | $2M cap or 30% discount at financing vs. $1.5M cap at maturity  | [Pre-Seed Angel](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/ConvertibleNote.pdf) |
| Term Sheet | $400,000 | $1.2M pre-money and $1.6M post-money | [Series A Preferred](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/SeriesATermSheet.pdf) |
| Post-Money SAFE | Template | Template | [Seed](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/PostMoney.pdf) |
| Term Sheet | Template | Pre-money plus the option pool | [Seed Priced-Prefrred](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/ExampleTermSheet.pdf) |
| Revenue Buyback SAFE | Template | Fixed ownership with no cap | [Seed](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/IndieVCAgreement.pdf) |
| Profit-Sharing SAFE | Template | Cap used only on conversion or sale | [Seed Bootstrapped](https://github.com/thespcrewroy/ENTR5505-FinancingEntrepreneurialVenture/blob/main/assets/SharedEarningsAgreement.pdf) |

---

# Instrument: Pre-Seed Angel Convertible Note

## Timeline
- **Lending:** the investor lends $40,000 as debt instead of ownership with a maturity date of 24 months
- **Debt Start:** 5% simple interest of $2,000 per year (`5% interest x $40,000 loan = $2,000 interest-per-anum`)
- **Automatic Conversion:** if the company raises at least $250,000 of new equity (a "Qualified Financing"), the note turns into shares
- **Maturity (24 months):** if no qualified financing has happened, the investor chooses between a $1.5M cap or $42,000 debt repayment

*Assumption: the founder owns 1,000,000 shares*


### Scenario 1: A Qualified Financing Happens (Month 12)
- Angel investor gets the lower price per share from the following two scenarios to give themselves more shares:
    - **Discount Price:** 70% of the VC investor's calculated price per share
    - **Cap Price:** $2.00 per share (`$2M capped pre-money ÷ 1,000,000 shares = $2.00 per share`)
- A pre-money valuation of about **$2.86M** is the tipping point (`70% discount × $2.86M = $2M`)

### Cap Wins
- VC investor and founder negotiate a $3 million pre-money valuation based on its perceived worth
- VC investor leads the Seed round with a $500,000 investment, triggering the $250,000 qualified financing threshold
- VC investor pays $3.00 per share (`$3M pre-money ÷ 1,000,000 shares = $3.00 per share`)
- VC gets 166,667 shares (`$500,000 investment ÷ $3.00 per share = 166,666.66... shares`)
- Qualified financing triggers the angel's debt into equity conversion in tandem with the VC investor's investment
- Angel investor's equity gets the same rights as the VC investor's preferred stock
- The note converts at the lower $2M capped pre-money valuation (`70% discount x $3M = $2.1M > $2M`)
- $42,000 of debt converts into equity investment (`$40,000 loan x+ 5% interest = $42,000 investment`)
- Angel investor pays $2.00 per share (`$2M capped pre-money ÷ 1,000,000 shares = $2.00 per share`)
- Angel investor gets 21,000 shares (`$42,000 investment ÷ $2.00 per share = 21,000 shares`)

| Holder | Shares | Ownership After the Round |
| ------ | ------ | ------------------------- |
| Founder | 1,000,000 | 84.20% |
| Investor B | 166,667 | 14.03% |
| Angel (note) | 21,000 | 1.77% |
| **Total** | **1,187,667** | **100%** |

### Discount Wins
- VC investor and founder negotiate a $2.5 million pre-money valuation based on its perceived worth
- VC investor leads the Seed round with a $500,000 investment, triggering the $250,000 qualified financing threshold
- VC investor pays $2.50 per share (`$2.5M pre-money ÷ 1,000,000 shares = $2.50 per share`)
- VC gets 200,000 shares (`$500,000 investment ÷ $2.50 per share = 200,000 shares`)
- Qualified financing triggers the angel's debt into equity conversion in tandem with the VC investor's investment
- Angel investor's equity gets the same rights as the VC investor's preferred stock
- The note converts at the lower $1.75 pre-money valuation (`70% discount x $2.5M = $1.75M < $2M`)
- $42,000 of debt converts into equity investment (`$40,000 loan x+ 5% interest = $42,000 investment`)
- Angel investor pays $1.75 per share (`$2M capped pre-money ÷ 1,000,000 shares = $2.00 per share`)
- Angel investor gets 24,000 shares (`$42,000 investment ÷ $1.75 per share = 24,000 shares`)

| Holder | Shares | Ownership After the Round |
| ------ | ------ | ------------------------- |
| Founder | 1,000,000 | 81.70% |
| Investor B | 200,000 | 16.34% |
| Angel (note) | 24,000 | 1.96% |
| **Total** | **1,224,000** | **100%** |

### Scenario 2: No Qualified Financing by Maturity (Month 24)
- VC investor and founder negotiate a $2 million pre-money valuation based on its perceived worth
- VC investor leads the Seed round $200,000 at month 6 for preferred stock at a $2M pre-money
- VC investor pays $2.00 per share (`$2M pre-money ÷ 1,000,000 shares = $2.00 per share`)
- VC gets 100,000 shares (`$200,000 investment ÷ $2.00 per share = 100,000 shares`)
- Maturity date triggers a choice
    - **Debt Payment:** $44,000 (`$40,000 loan x+ (5% interest x 2 years) = $44,000 interest-loan`)
    - **Voluntary Conversion:** $1.5M capped pre-money valuation
- The angel voluntarily chooses to convert into common stock at the $1.5M cap as founders often have no money to pay
- $44,000 of debt converts into equity investment (`$40,000 loan x+ (5% interest x 2 years) = $44,000 investment`)
- Angel investor pays $1.36 per share (`$1.5M cap pre-money ÷ (1M shares + 100k investor shares) ≈ $1.36 per share`)
- Angel investor gets 32,267 shares (`$44,000 ÷ $1.36 per share ≈ 32,266.67 shares`)

| Holder | Shares | Type | Ownership After Conversion |
| ------ | ------ | ---- | -------------------------- |
| Founder | 1,000,000 | Common | 88.32% |
| VC Investor | 100,000 | Preferred | 8.83% |
| Angel | 32,267 | Common | 2.85% |
| **Total** | **1,132,267** | | **100%** |

### Scenario 3: The Company Is Sold Before a Qualified Financing (Month 12)
- No qualified financing reached by month 12
- A larger company offers to buy the startup for $5,000,000 at month 12
- The founder must give the angel written notice at least 5 days before the sale closes
- Angel investor gets the greater value option of the following two scenarios:
    - **Debt Payment:** $42,000 (`$40,000 loan x+ 5% interest = $42,000 investment`)
    - **Voluntary Conversion:** $1.5M capped pre-money valuation
- Calculating Voluntary Conversion
    - Angel investor would pay $1.50 per share (`$1.5M capped valuation ÷ 1,000,000 shares = $1.50 per share`)
    - Angel investor would get 28,000 shares (`$42,000 ÷ $1.50 per share = 28,000 shares`)
    - Angel investor would have 2.72% of the company (`28,000 angel shares ÷ 1,028,000 total shares = 2.72%`)
    - Angel investor's shares are worth $136,000 (`2.72% x $5,000,000 sale = $136,000`) 
- Automatic voluntary conversion to $1.5M capped pre-money valuation (`$136,000 > $42,000`)
- The angel takes **$136,187** and the founder receives **$4,863,813** from the sale

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

Not set today. The note delays pricing until the next round.

</details>

<details>
<summary><b>What happens if the company is acquired?</b></summary>
<br>

The investor gets the greater of:
1. Principal and interest
2. What they'd receive by voluntarily converting at the $1.5M cap

</details>

<details>
<summary><b>What two terms matter most?</b></summary>
<br>

1. The conversion price
2. Price at maturity with simple interest
</details>

  
---

# Instrument: Series A Memorandum of Terms

## Answers to the Activity Questions
<details>
<summary><b>What type of company [entity] is this?</b></summary>
<br>

A Delaware corporation. This is the standard for VC-backed startups.

</details>

<details>
<summary><b>What type of deal is this?</b></summary>
<br>

Series A Preferred Stock Priced-Equity Round.

</details>

<details>
<summary><b>Where is this company located?</b></summary>
<br>

Incorporated in Delaware.

</details>

<details>
<summary><b>How much is being raised?</b></summary>
<br>

$400,000.

</details>

<details>
<summary><b>What is the company valuation?</b></summary>
<br>

$1.2M pre-money and $1.6M post-money valuation with investors owning 25% (`$400,000 ÷ $1.6M = 25%`).

</details>

<details>
<summary><b>Can investors invest in future rounds?</b></summary>
<br>

Yes. Pro rata rights let them buy their share of new rounds. This privelage ends after 5 years or at the IPO.

</details>

<details>
<summary><b>How much do investors get in a sale?</b></summary>
<br>

$400K back immediately, followed by 25% of whatever is left at participation preferred.

</details>

## Investor Rights at a Glance
| Term | What it says | Who it favors |
| ---- | ------------ | ------------- |
| Liquidation Preference | 1x money back on a sale. Then, optional pro rata with common stock | Investor |
| Conversion | Optional 1:1 conversion from preferred to common stock automatic by IPO or vote | Neutral |
| Protective Provisions | 51% must approve charter changes, new preferred shares, merger, or sale | Investor |
| Redemption | Investors can force company to buy back shares after 5 years | Investor |
| Drag-Along | Founders must vote for an approved sale | Investor |
| Anti-Dilution | Weighted average adjustment in a down round | Investor |
| Board | 3 seats: 1 company, 1 investor, 1 mutually agreed independent | Neutral |
| Pro Rata Rights | Can invest future rounds for 5 years or until an IPO | Investor |
| Information Rights | Annual and quarterly financials, an annual budget, inspection rights | Investor |
| Founder Vesting | 1 year close then monthly for 3 years. 1 extra year if fired within a year sold | Investor |
| Co-Sale | Founders can't sell shares without investors getting a chance to join or buy them first | Investor |
| Founder Activities | Founders must work 100% of their time on the company | Investor |

---

# Instrument: Seed SAFE

## What Makes a SAFE Different
* No debt, no interest, no maturity date, and no repayment
* There's no minimum qualified financing size for conversion like the note's $250K threshold
* The investor's ownership is fixed upfront: `Ownership = Purchase Amount ÷ Post-Money Valuation Cap`
* The investor gets more of their money back in a sale or their as-converted share
* If the company shuts down, the investor is behind lenders in getting their money back
* No voting rights until loan converts into equity
* Valuation cap only with no discount price per share option

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

Priced purchase amount defined in the SAFE.

</details>

<details>
<summary><b>What is the company valuation?</b></summary>
<br>

The post-money valuation cap defined in the SAFE.

</details>

<details>
<summary><b>What happens if the company is acquired?</b></summary>
<br>

The greater valuation of either 1x money back or the valuation-as-converted value.

</details>

<details>
<summary><b>What two terms matter most?</b></summary>
<br>

1. Post-money valuation cap which sets ownership
2. Total SAFEs outstanding because stacking SAFEs quietly dilutes the founders

</details>

---

# Instrument: Seed Preferred Light Term Sheet

## What Makes It Different
* A short and founder-friendly version of the Series A Term Sheet
* The investor still gets preferred stock, but with far fewer protections
* 1x non-participating liquidation preference means the investor takes their money back OR converts to common stock
* No redemption right, no anti-dilution, no drag-along clause, and no dividends
* **Future Rights:** the investor automatically gets any better terms from the next series
* **Binding Terms:** only the 30-day, no-shop, and confidentiality rules are legally binding

## Investor Rights at a Glance
| Term | What it says | Who it favors |
| ---- | ------------ | ------------- |
| Liquidation Preference | 1x money back non-participating | Neutral |
| Conversion | Optional 1:1 conversion of preferred stock into common stock | Neutral |
| Protective Provisions | Majority vote to approve charter changes, buybacks, dividends, board, or sale | Investor |
| Information Rights | Major Purchasers only | Investor |
| Pro Rata Rights | Major Purchasers only | Investor |
| Board | Common, preferred, and mutually agreed seats | Balanced |
| Expenses | Company pays investor counsel a flat $10,000 | Investor |
| Future Rights | Investors automatically get any upgraded rights in future series | Investor |
| Founder Vesting | 4 years with full acceleration on a double trigger | Investor |
| No-Shop | 30-day, no-shop, and confidentiality rules are legally binding | Investor |


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
