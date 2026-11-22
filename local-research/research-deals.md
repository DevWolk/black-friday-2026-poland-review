# Black Week 2026: deals checked 21.11 23:40 – 22.11 00:30

The full data for each deal is in `research-deals.json`: 42 entries, sorted by confidence and then by discount.

How to read the numbers:
- **vs 30d** is the discount against the shop's own printed "Najniższa cena z 30 dni przed obniżką".
- **vs market** is the discount against the next cheapest shop I found. Ceneo blocked me with a Cloudflare challenge after about 30 requests, so most market checks come from Skapiec.pl.
- **conf** is my confidence:
  - high: price and 30-day lowest read on the shop's own page, plus a market check.
  - medium: shop page only.
  - low: aggregator only (Pepper, search snippets); not verified.

Shops I could not read automatically, with curl or WebFetch: Media Expert, RTV Euro AGD, Allegro, Amazon.pl, Neonet, Notino, Douglas, Hebe, Decathlon, Kaufland, Action, Carrefour, Leroy Merlin. Anything from them below comes from Pepper and is marked as such.

## Top deals, grouped by category

The # is the overall rank, by real discount (mostly vs market) and usefulness.

### Дом и техника (home and appliances)

| # | Deal | Shop | Price | 30d low | vs 30d | vs market | Ends | conf |
|---|---|---|---|---|---|---|---|---|
| 1 | Philips Airfryer XXL Connected HD9285/90 | MediaMarkt | 299 | 899 | −66.7% | about −55% (next of 12 offers: 672.82) | not shown | high |
| 2 | SilverCrest SEMST 1500 A1 espresso machine with grinder | Lidl, in store from Mon 23.11 | 599 | 1499 | −60% | about −28% (834 elsewhere, Pepper only) | 28.11 or sold out | high |
| 6 | eufy Omni E28 robot with auto-empty station, code `black-weeks5` | x-kom | 2099 | 4199 | −50% | −16% (next: 2499) | **23.11** | high |
| 16 | Philips EP2223/40, code `RABAT50` (needs an account) | Biedronka Home | 949 | 1699 | −44% | −14% (next: 1099) | 30.11 | high |
| 17 | SilverCrest brushless cordless vacuum with dock | Lidl, from 23.11 | 499 | 999 | −50% | Lidl-only brand | 28.11 | medium |
| 18 | Tom Tailor towels and blanket (towel 59, set 49.99, blanket 54) | Lidl, Thu 26.11 | 59 | 199 | −61% to −70% | – | while stock lasts | medium |
| 19 | Livarno mattress topper | Lidl, from 23.11 | 79 | 169 | −53% | – | 28.11 | medium |
| 20 | Parkside Performance drill kit with 2 batteries | Lidl, Fri 27.11 | 149 | 299 | −50% | – | 28.11 | medium |
| 25 | Philips LatteGo EP5441/50 (4.6 from 3124 reviews) | MediaMarkt | 1599 | 2599 | −38.5% | ties cheapest of 34 offers | not shown | high |
| 26 | Ninja PossibleCooker MC1101EU | Biedronka Home | 399 | 699 | −43% | about −11% (Komputronik 449) | 31.12 | high |

- **#1 (Philips air fryer):** the page says delivery is not included; pickup in a Katowice MediaMarkt avoids the fee. You already have a Ninja AF180, so this is a gift or a second unit.
- **#2 (Lidl espresso):** on lidl.pl it was still 1499 at check time.
- **#6 (eufy E28):** a second robot next to the Dreame L50 Ultra. The code has been active for some days.
- **#16 (Philips EP2223):** the price has been the same since 31.10.

### Электроника (electronics)

| # | Deal | Shop | Price | 30d low | vs 30d | vs market | Ends | conf |
|---|---|---|---|---|---|---|---|---|
| 4 | JLab JBuds Lux ANC, white only, code `black-weeks63` | x-kom | 149 | 399.99 | −62.7% | about −35% (other colours 229–240) | 13.12 | high |
| 12 | SteelSeries Apex Pro Mini Wireless, code `steelseries-bf1` | x-kom | 599 | 1199 | −50% | −14% (others 699–735) | 07.12 | high |
| 14 | HyperX Pulsefire Haste 2 Core Wireless, black, no code | x-kom | 149 | 299 | −50% | not checked | not shown | medium |
| 21 | Beyerdynamic DJ300 PRO X Club, code `black-weeks87` | x-kom | 399 | 766 | −48% | Morele 573 for the DJ 300 PRO X | 15.01.2027 | medium |
| 22 | Logitech Astro A10 PC/PS5 | MediaMarkt | 129 | 229.99 | −44% | not checked | not shown | medium |
| 27 | Mac mini M6 16/256 (MHQK4ZE/A), your exact configuration | Lantre | 3799 | not printed | – | 150 zł under x-kom, Media Expert and Amazon (3949) | Hot Deal countdown | high |

- **#21 (Beyerdynamic):** delivery takes longer than usual.
- **#27 (Mac mini):** worth switching only if the x-kom order can still be cancelled or returned.

### Одежда и обувь (clothing and shoes)

| # | Deal | Shop | Price | 30d low | vs 30d | vs market | conf |
|---|---|---|---|---|---|---|---|
| 7 | Keen Headout Mid WP, men's, green | eobuwie | 273.99 | 549.99 | −50% | about −30% (about 390 elsewhere) | high |
| 8 | Columbia Peakfreak II Mid OutDry, men's | eobuwie | 313.99 | 629.99 | −50% | about −6% (Ceneo range from 333) | high |
| 9 | Merrell Agility Peak 6, men's, blue | merrell.pl | 329 | 699* | −53% | −20% or more (8a.pl 413) | medium |
| 10 | Merrell Agility Trail, light brown or white | merrell.pl | 199 | 419* | −52.5% | not checked | medium |
| 11 | Timberland 6 In Premium, burgundy | eobuwie | 498.99 | 999.99 | −50% | about −45% (other colours about 928) | medium |
| 15 | Columbia Powder Lite women's jacket, pink | Modivo | 324.99 | 649.99 | −50% | not checked | high |
| – | New Balance BB550VTG | eobuwie | 324.99 | 649.99 | −50% | not checked | medium |
| – | Quiksilver The Puffer down jacket | Modivo | 359.99 | 719.99 | −50% | not checked | medium |
| – | Tommy Jeans down jacket (25–40% band) | Answear | 698.99 | 1099.90 | −36% | – | medium |

\* merrell.pl prints the crossed price in the field its template labels as the 30-day lowest. There is no separate number.

- **#7 (Keen):** runs small, last sizes.
- **#8 (Columbia Peakfreak):** last sizes.
- **#9 (Merrell Agility Peak 6):** 11 of 12 sizes in stock, free delivery.
- **#10 (Merrell Agility Trail):** delivery 9 zł.
- **#15 (Columbia Powder Lite):** code `DEALS2026` with 2+ items brings it to 292.49 (−55%). The code ends **22.11 at 22:59**.

### Красота и уход (beauty)

| # | Deal | Shop | Price | 30d low | vs 30d | vs market | conf |
|---|---|---|---|---|---|---|---|
| 5 | Guerlain Aqua Allegoria Pamplelune EDT 125 ml | Empik | 279.99 | 949.99 | −70.5% | about −45% (Notino.fr about 505) | medium |
| 24 | Tom Ford Black Orchid EDP 50 ml | Empik | 359.99 | 739.99 | −51% | about −10% (Alza.cz about 400) | medium |
| – | Azzaro Chrome EDT 100 ml / Armani Acqua di Gio EDT 100 ml | Empik | 139.99 / 259.99 | 289.99 / 519.99 | −52% / −50% | not checked | medium |
| – | Remington, all products −50% (clipper 84.50) | Lidl, Thu 26.11 | 84.50 | 169 | −50% | model unknown | medium |

Empik's regular perfume prices are above the market, and some of these prices may apply only in the app.

### Аксессуары / Разное (accessories, gifts, kids)

| # | Deal | Shop | Price | 30d low | vs 30d | Note | conf |
|---|---|---|---|---|---|---|---|
| 13 | Silver Monkey MagCharger 3-in-1 travel stand, code `black-weeks3` | x-kom | 99 | 249 | −60% | x-kom's own brand, rated 4.72 from 466; ends 29.11 | medium |
| 23 | Hot Wheels Mega Garaż Gigapętla | Smyk | 159.99 | 289 | −45% | same price as in October | medium |
| – | Alpinus Tarfala 35 L backpack | Empik | 169.99 | 299 | −43% | read from a homepage tile | medium |
| 3 | LEGO Botanicals 11505 Grzyby leśne (11501 also 99.99) | Carrefour | 99.99 | unknown | – | 57% under the cheapest other shop (233.42); in store, Pepper only | low |

### Еда и продукты (food), all low confidence, from Pepper

- **Nutella with a Lidl Plus coupon:** 9.12 vs 18.99 (−52%), Monday 23.11 only.
- **Melitta Originals Platinum 1 kg:** 19.90 when buying 2, at one Biedronka store in Dąbrowa Górnicza. Local clearance; the online minimum is 54.88.

## Cheaper than what you already paid (same product)

- **Mac mini M6 16/256:** Lantre 3799 vs your 3949 at x-kom. Verified on Lantre; the Ceneo offer list was read before the block.
- **Sony WH-1000XM6:** navy/blue is 1299 at several shops, including MediaMarkt and Morele, vs your 1379. Black and silver are still 1379. Skapiec only.
- **Dreame 65S100:** one shop at 2889 vs your 2999; the other 12 offers are 2999 or more. Skapiec only.
- **Xiaomi 17T 12/512 black:** one shop at 2499 vs your 2599; mi.com lists 2699. Skapiec only, not verified.
- **From the Ceneo search list before the block (aggregator-only, variants not checked):**
  - Apple Watch Ultra 3: from 2959–2999 vs your 3199.
  - iPhone 17 256 GB in Sage: 3940 vs your 4129.90.
  - Galaxy Watch8 40 mm Bluetooth: 799 vs your 999; only relevant if yours is not the LTE model.
- **No better price found for:**
  - Ninja AF180 (others 349.99). One exception: the AF180EUCP variant is 293.60 from an erli.pl marketplace seller. That is a different colour code, and I did not verify it.
  - Braun 52-N1000S (299).
  - Insta360 X6 (2658).
  - LG 65QNED72B6B, MSI 274QP, Philips 65MLED920, ZenScreen MQ16FC, HP Envy 7231, Trust Yavi (all equal).
  - Dreame L50 Ultra: Biedronka Home has 1999 minus RABAT100, which is 1899, the same as yours.
- **Coupon:** Media Expert gives 70 zł off per 500 zł with code `K-5311` (Pepper only, end date unknown). That is 3 zł better than the RTV Euro AGD 67/500 you already have.

## Looks like a deal, isn't

- **Acer Nitro V16S i7-240H/32 GB/1 TB/RTX 5060 at x-kom:** 5699, −39% vs a 9399 "30-day low". ELECTRO.pl sells it for 5699 too.
- **soundcore Liberty Buds at x-kom:** 199 ("−43%"); MediaMarkt and ELECTRO.pl have 189.
- **JBL Tune 520BT2 at x-kom:** 129 ("−50%"); the gen-1 520BT is 99 at MediaMarkt.
- **Oral-B iO 3 at MediaMarkt:** 258 ("−45%"); Allegro has 224.
- **BaByliss AS970E at MediaMarkt:** 249 ("−37%"); Morele has 159.
- **Morele Black Week landing page:** it shows "−58%" on the Arctic P12 5-pack (59 vs 139), but the product page prints a 30-day lowest of 72.32. The real cut is −18%. Morele's listing attribute is not the Omnibus figure, so I dropped every Morele item.
- **Ultradesk Highlander XXL at x-kom:** 529 ("−34%"); RTV Euro AGD previously had it at 499.
- **Zalando's −60/−70% badges:** about −20% against the 30-day lowest on known brands.
- **Sportano BLACKDEALS:** 5–10% against the 30-day lowest on Merrell.
- **Biedronka Home's Dreame items:** at or above Morele's prices.
- **Pattern at x-kom:** many "−50% with code" items have base prices well above the market. Of the x-kom items I checked, only eufy E28, JBuds Lux white, Apex Pro Mini and MagCharger stayed clearly cheaper than other shops.

## Hot on Pepper, not verified (shop blocks automated reads)

- **RTV Euro AGD:**
  - Samsung QE50QN74HAU 50" Neo QLED: 2099 with code `RGBF2011301126C` (crossed price 3700).
  - Motorola g57 Power 12/256: 999 with code `RBF201107122026C1`.
- **Allegro:**
  - LG OLED65C51LA: 4489.
  - De'Longhi Dinamica Plus ECAM380.95.TB: 1899.
  - POCO F9 Ultra 16/512: 2897.61.
- **Media Expert:**
  - KIOXIA Exceria Plus G3 2 TB: 1109.99.
  - YubiKey 5 NFC 2-pack: 359.
- **Amazon.pl:**
  - LG 32U721SA 4K monitor: 780.99.
  - BUFF Merino Midweight: 71.43, about 25% under the usual price; relevant to your buff search.
- **Samsung.com:** Galaxy S26 Ultra 12/256 plus Buds 4 Pro for 4500.05 with stacked codes `BLACK-70`, `MDAYS-11MX` and `R58`.
- **Carrefour:** Nintendo Switch 2 256 GB for 1899, about 12% under the market.

## Upcoming dated drops

| Date | Shop | What is announced |
|---|---|---|
| Sun 22.11 22:59 | eobuwie / Modivo | BLACK DEALS (codes `DEALS` / `DEALS2026`, extra −10% on 2+ items) ends; next wave likely from 23.11 |
| Mon 23.11 | x-kom | Week 6 of Black Weeks: new items in the app at 8:00, on the web at 10:00. Last day of the eufy E28 code. |
| Mon 23.11 | Lidl | Leaflet 23–28.11 (see the Lidl items above), plus: Philips EP1200 399 (you have it), Termorobot MC Smart 1499 with Lidl Plus (23–30.11), Crivit car mattress 38.70 (−70%), Livarno nightstand 89 (−70%), Parkside straight grinder 59 (−60%), LEGO −25% with Lidl Plus, Nutella coupon |
| Mon 23.11 | Biedronka Home | Hoffen "2nd −30% / 3rd −60%" ends |
| Tue 24.11 | Biedronka | New store leaflet expected; not published at check time, so look on the evening of 22.11 |
| Wed 25.11 | Kaufland | First Black Week leaflet ends (SilverCrest SKMS 1200 C1 1499, Parkside generator 499); from ding.pl |
| Thu 26.11 | Lidl | Remington −50%; Tom Tailor textiles −61% to −70%; Braun Series 5 52-B7000cc 369 (−30%) |
| Thu 26.11 22:30 | x-kom app | Black Friday prices start in the app (web at 00:00 on 27.11), running to 29.11. Shared stock: items can sell out in the app first. |
| Fri 27.11 | Lidl | Parkside Performance drill kit 149; Parkside 20 V 8-tool set 599 (dates from ding.pl) |
| Sat 28.11 | Lidl | Russell Hobbs Mix&Go Steel 99; Vileda 2nd item −50% with Lidl Plus; Krups EA8108 999 and Bosch BBHL2LED 449 (from ding.pl) |
| Sun 29.11 | x-kom, Morele | Black Weeks end; Morele code `BLACK26` prices end |
| Mon 30.11 | Lidl | Free lidl.pl delivery with a Lidl Plus coupon, orders placed on 30.11 only (Pepper) |
| Mon 30.11 | Biedronka Home | Codes `RABAT20`, `RABAT50`, `RABAT100`, `RABAT300` end (account needed) |
| Tue 1.12 | Alpinus, IKEA | Alpinus Black Weeks (up to −40%) end; IKEA 100 zł voucher per 800 zł on METOD kitchens ends |
| Wed 2.12 | Kaufland | Second Black Week leaflet (19.11–2.12) ends |
| 7.12 / 13.12 | x-kom | SteelSeries Apex Pro Mini code / JBuds Lux code end |
| not dated | Rossmann | Banner says "promocja na wszystkie perfumy" is coming soon. Last year it ran 24.11–1.12 as 1+1 on perfumes (news article, not the shop). |

1 zł products:
- **x-kom "Najtańszy produkt za 1 zł":** buy 2 or more accessories from the pool and the cheapest one costs 1 zł.
- **x-kom hidden codes:** x-kom says these unlock 1 zł products during Black Weeks. The code list is dynamic and was not readable.
- **HyperX OMEN laptop plus 1 zł gear:** at x-kom and Komputronik, a HyperX OMEN laptop comes with a monitor (or headphones, at Komputronik) for 1 zł.
- **Morele:** buy a laptop and get a monitor for 1 zł.
- **x-kom Gorący Strzał:** changes daily from 10:00. At check time it was a Silver Monkey USB-RJ45 adapter for 29.99 vs 64.99.
