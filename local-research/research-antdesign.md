# Ant Design Q1 V2: price, shipping and codes (checked 2026-11-21 ~23:50 CET)

## Prices in the official store (Poland market, PLN, no FX conversion)
Shopify market Poland, rate 4.1244 PLN/USD; the store states "MADE IN SPAIN · NO IMPORT DUTIES".

| Variant | Price | Shipping to 40-001 Katowice | Total | List price before | Stock |
|---|---|---|---|---|---|
| Q1 V2 Aluminium Black (also Blue) | 79.00 zł | Economy – Tracked 29.00 zł, 7–9 business days | **108.00 zł** | $39 (~161 zł) | yes |
| Q1 V2 Aluminium Blue/Pink Splash | 79.00 zł | 29.00 zł | 108.00 zł | | yes |
| Q1 V2 POM White | 87.00 zł | 29.00 zł | 116.00 zł | | yes |
| Q1 V2 PEI Amber | 103.00 zł | 29.00 zł | 132.00 zł | | yes |
| Q1 V2 Titanium Gray | 120.00 zł | 29.00 zł | **149.00 zł** | $49 (~202 zł) | yes |
| Q1 V2 S Titanium | 79.00 zł | | | | sold out |

Shipping is flat 29 zł per order (same for 1 or 2 items; checked via cart shipping estimate and in checkout with a test Katowice address, order not placed). Al + Ti in one order: 199 + 29 = 228 zł.
Extra male connectors (add-on, "20% off" block on the product page): Al 25 zł, Ti 41 zł; a Q1 V2 base is required.

The site shows the current price as the sale price against the old $39/$49 (-51% / -41%). No Omnibus 30-day minimum is shown; the price was the same on 20.11, so this is a standing sale, not a confirmed Black Friday price.

## Codes tested
Method 1: Shopify cart API (`/cart/update.js {discount}`) on a 199 zł cart (Al + Ti), 44 codes: all `applicable: false`.
Method 2: the real checkout discount field (distinguishes "Enter a valid discount code" = code does not exist, from "reached its usage limit" = real but used up), 44 codes incl. a fake control code.

| Result | Codes |
|---|---|
| Real code, **usage limit reached** | XZVJNCZZ (Checkmate), CKLT3CH3 (Checkmate/Hotdeals, "5%") |
| Does not exist | SAVE20, WELCOME20, 10OFF, W3Z0B4ST3HB2 (all revealed on Checkmate), NEW10/15/20, EXTRA10/15/20, SAVE10/15/25, WELCOME5/10/15, THANKYOU5/10/15/20, BLACKFRIDAY, BLACKFRIDAY2026, BF2026, BFCM, BFCM2026, BFCM20, BLACK10, BLACK20, BF10, BF20, BLACKWEEK, CYBERMONDAY, CYBER20, HOLIDAY, HOLIDAY10, XMAS, XMAS10, EDC, EDC10, ANT10, ANT20, ANTDESIGN, ANTDESIGN10, FIRST10, WELCOME, SUBSCRIBE, NEWSLETTER, SIGNUP10, TRITIUM, TITANIUM, Q1V2, GIFT10, VIP10, SUMMER10, FALL10, NOV10 |

Checkmate also lists masked codes TDM#####, NE###, EXT####, SHF#########, THA####### that could not be revealed without their browser extension; the obvious completions (NEW10, EXTRA10, THANKYOU10…) do not exist. Community reports on Checkmate mark most codes "not working" for 3–12 months.

Conclusion: no public code works right now. The only working discount route is the store's own newsletter pop-up ("10% off", name + email, marketing consent). Hotdeals claims "up to 25%" for subscribers; not verified. Subscribing needs the buyer's email, so it was not done.

If the newsletter 10% applies to the item price only: Al 71.10 + 29 = **100.10 zł**, Ti 108.00 + 29 = **137.00 zł**.

Other sellers: no Amazon / AliExpress / Allegro listing of the original Q1 V2 found; the Allegro "magnetic quick-release" is a no-name lookalike with conflicting specs.

## Picks
1. Cheapest: **Aluminium Black, 108 zł** (100.10 zł with the newsletter 10%).
2. Quality: **Titanium Gray, 149 zł** (137 zł with the newsletter 10%). Grade 5 Ti, 7.6 g vs 5.7 g for Al 7075-T6; lifetime warranty on both.
Buying both in one order saves one 29 zł shipping (228 zł for two).
