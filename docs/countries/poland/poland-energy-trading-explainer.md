# How energy is traded in Poland

**In one paragraph:** Poland is a single bidding zone with a central-dispatch system run by the transmission operator, PSE. Power is sold bilaterally or on the Polish Power Exchange (TGE), which is coupled to the wider European market. Anything that is not matched in advance settles in PSE's balancing market. On top of energy sales, a separate **capacity market** pays plants for being available when the system is short. To get any of this, a new plant must first win a **grid connection**, which became more expensive and more tightly time-limited on 30 April 2026.

---

## 1. How power is traded

### The building blocks

| Layer | What it is | Who runs it |
|---|---|---|
| Bilateral (OTC) | Direct contracts between generators, traders and customers | The parties |
| Day-ahead market (DAM, *RDN*) | Hourly auction for next-day delivery, coupled with the rest of Europe | TGE |
| Intraday market (IDM) | Continuous trading and auctions up to shortly before delivery, including 15-minute products | TGE |
| Forward market | Weekly, monthly, quarterly and yearly baseload and peak contracts | TGE |
| Balancing market (*RB*) | Real-time balancing, reserves and imbalance settlement | PSE |
| Capacity market | Payments for availability (section 2) | PSE |

**Sources:** TGE is the only licensed commodity exchange in Poland and the nominated electricity market operator for the Polish zone, active in the European day-ahead (SDAC) and intraday (SIDC) coupling ([TGE corporate folder 2026](https://tge.pl/pub/TGE/Publikacje/TGE_corporate_folder_2026.pdf); [TGE summary of 2023 trading](https://tge.pl/pub/TGE/komunikaty/2024/01/2024.01.05_summary%20of%20trading%20activity%20at%20tge%20in%202023.pdf)). The detailed day-ahead rules are in [TGE's trading and clearing rules](https://www.tge.pl/pub/TGE/files/RTG/2026/20260512_SZOiR_RDN_EN.pdf).

### Good to know

- **Legal base.** The Energy Act of 1997 is the main law. Electricity can be traded over the counter or on an exchange, access to the networks is on a third-party-access basis, and every participant must either be a balancing responsible party or appoint one ([Mondaq primer](https://www.mondaq.com/oil-gas-electricity/199620/wholesale-electricity-trading-in-poland-a-basic-primer-to-electricity-and-gas-wholesale-trading); [Modo Energy](https://modoenergy.com/research/poland-pl-balancing-market-bm-revenue-imbalance-central-dispatch-gb-germany-volumes-pln-intraday-)). The primer is older, so check licensing requirements with counsel.
- **15-minute resolution.** TGE added 15-minute intraday instruments and PSE moved balancing settlement to 15-minute periods when it reformed the balancing market in June 2024 ([TGE announcement](https://tge.pl/pub/TGE/komunikaty/2024/06/2024.06.14_tge%20implements%20new%20solutions%20on%20the%20electricity%20spot%20market.pdf)).
- **Central dispatch.** Unlike Great Britain or Germany, where generators self-dispatch, PSE decides in its scheduling process when large units run. When the system is short, the imbalance price clears at the higher of the day-ahead and balancing prices ([Modo Energy](https://modoenergy.com/research/poland-pl-balancing-market-bm-revenue-imbalance-central-dispatch-gb-germany-volumes-pln-intraday-)).
- **Reserves.** Poland joined the European aFRR platform PICASSO on 11 July 2025. PSE procures roughly 400–500 MW of aFRR in each direction and 197 MW of FCR ([Modo Energy on aFRR](https://modoenergy.com/research/en/poland-afrr-picasso-bess-capacity-energy)).
- **Intraday growth.** Intraday volume reached 6.7 TWh in 2025, up 170% on 2024, and evening prices above €150/MWh occur when solar fades and coal cannot ramp fast enough ([Modo Energy](https://modoenergy.com/research/en/poland-pl-capacity-market-bess-cm-auction-merchant-revenue-stack-battery-march-2026)).

### Recent price levels

In August 2026 the day-ahead market averaged PLN 583.66/MWh, the 2027 baseload forward averaged PLN 495.52/MWh, and gas on TGE's spot market averaged PLN 280.22/MWh ([TGE August 2026 summary](https://tge.pl/pub/TGE/komunikaty/2026/09/2026.09.03_summary%20of%20trading%20activity%20at%20tge%20in%20august%202026.pdf)).

### What this means for a 5–10 MW gas engine

Sites this size would normally sell through a trader or aggregator that acts as balancing responsible party. Evening and scarcity hours matter far more than the baseload average. This is my reading of the market structure, not a sourced rule: confirm with PSE's balancing rules and a prospective trading partner.

---

## 2. How the capacity market works

### The idea

A plant is paid for what it promises to be able to deliver, not only for energy it sells. The product is net dispatchable capacity during a delivery period, together with the **capacity obligation**: a duty to deliver that capacity during system stress events ([PSE foreign-provider guideline](https://www.pse.pl/documents/31287/20965895/2024.08.06-Guideline+%28v.1.3%29/ccbba7b7-6798-4919-81b6-7c2e5f911b32); definitions in the [Capacity Market Act, English text](https://www.pse.pl/documents/31287/20965895/09.06.2026_The+Act+of+8+December+2017+on+the+Capacity+Market.pdf/4c7d0397-0dc5-467c-bee3-e24e7330a88a)). PSE owns and runs the capacity market register and counterparty arrangements, and the cost is recovered from electricity users through a charge ([Enerdata](https://www.enerdata.net/publications/daily-energy-news/european-commission-clears-polands-eu5bn-chp-support-scheme.html)). The PSE guideline is written for foreign providers, so domestic steps differ slightly (for example, there is no pre-auction for Polish units).

### Step by step

1. **Certification.** The owner registers a capacity market unit in PSE's portal (PURM) and submits technical data: net and gross capacity, efficiency, ramp rate, emission factor, costs and a declaration that the unit meets the 550 g CO2/kWh limit. The offered obligation must be at least 2 MW, so 5–10 MW sites qualify. The declarations also confirm that no unit is supported under Poland's renewable or CHP tender systems ([PSE guideline](https://www.pse.pl/documents/31287/20965895/2024.08.06-Guideline+%28v.1.3%29/ccbba7b7-6798-4919-81b6-7c2e5f911b32)).
2. **Auction parameters.** The energy minister publishes the demand and price parameters at least 18 weeks before the main auction ([PSE guideline](https://www.pse.pl/documents/31287/20965895/2024.08.06-Guideline+%28v.1.3%29/ccbba7b7-6798-4919-81b6-7c2e5f911b32)).
3. **Auction.** A descending-price, pay-as-clear auction: bidders exit as the price falls until supply matches the demand curve. All winners in the zone receive the clearing price.
4. **Results and contract.** PSE publishes provisional results within three working days and the regulator (URE) confirms final results on the first working day after the 21st day. The capacity agreement is then concluded with PSE ([PSE guideline](https://www.pse.pl/documents/31287/20965895/2024.08.06-Guideline+%28v.1.3%29/ccbba7b7-6798-4919-81b6-7c2e5f911b32)).
5. **Delivery.** The unit stays available and responds when PSE calls a stress event.
6. **Settlement.** Payments are made for performance, with penalties for non-delivery.

### Auction types

| Type | Delivery period | Notes |
|---|---|---|
| Main (T-5) | Calendar year, five years ahead | Where new plants win long contracts |
| Supplementary / catch-up | Calendar year, after the main auction | Introduced by the 14 February 2025 amendment ([PSE](https://www.pse.pl/web/pse-eng/news/tso-announcements/-/asset_publisher/tKwP8XWSkdU8/content/entry-into-force-of-the-act-amending-the-capacity-market-act-introducing-supplementary-auctions)) |
| Additional / T-1 | Quarter or year, closer to delivery | Used to top up capacity ([DWF](https://dwfgroup.com/en-ie/news-and-insights/insights/2025/5/additional-auctions-are-coming-to-the-capacity-market)) |

### Recent clearing prices

| Auction | Delivery | Price (PLN/kW/year) | Source |
|---|---|---|---|
| Catch-up, July 2025 | 2029 | 534.09, 17-year contracts, about 2.7 GW incl. seven new gas units | [Beyond Fossil Fuels / reglobal](https://reglobal.org/capacity-markets-in-europe/) |
| Main, December 2025 | 2030 | 465.02, 6,887.64 MW, about 2.4 GW gas | [ESS News](https://www.ess-news.com/2025/12/30/poland-downgrades-bess-availability-plummets-total-awards-in-capacity-market-auction/) |
| T-1, September 2026 | 2027 | 325.55 | [Modo Energy](https://modoenergy.com/research/en/poland-capacity-market-supplementary-auction-bess-2027) |

Earlier history: PLN 172.85 for 2025 and PLN 259.87 for 2024 ([Forum Energii](https://forum-energii.eu/en/blog/rynek-mocy-drogo-drozej-najdrozej)).

### Contract length and indexation

New units can win long contracts: PGE secured a 15-year contract for at least 538 MW in the 2030 auction ([Globenergia](https://globenergia.pl/aukcja-rynku-mocy-rozstrzygnieta-wygraly-elektrownie-gazowe/)), and the July 2025 catch-up auction gave 17 years. Long-contract prices are indexed annually by average consumer price inflation from the second year ([Cyfrowy Polsat filing](https://www.parkiet.com/komunikaty-espi/art42722101-cyfrowy-polsat-spolka-akcyjna-wynik-dogrywkowej-aukcji-rynku-mocy-na-rok-dostaw-2029)). Recent regulations set a minimum capital spend of PLN 2,400/kW for the 15-period category ([2026 parameters regulation](https://eli.gov.pl/eli/DU/2021/1480/ogl/pol/pdf)); check the figure for the auction you target.

### How much you can sell: availability factors

Your maximum obligation is net capacity multiplied by a technology-specific availability correction factor. For example, a 200 MW combined-cycle plant with a factor of 93.79% could offer 187.58 MW ([DWF](https://dwfgroup.com/en-ie/news-and-insights/insights/2025/5/additional-auctions-are-coming-to-the-capacity-market)). For batteries the factor was cut to 13.39% in the December 2025 auction ([ESS News](https://www.ess-news.com/2025/12/30/poland-downgrades-bess-availability-plummets-total-awards-in-capacity-market-auction/)). I did not find the factor for gas engines in the sources I reached.

### Performing the obligation

- **System stress event.** An hour in which available dispatchable reserve falls below the required margin. PSE may call one for a full hour between 07:00 and 22:00 on working days, announced at least eight hours ahead ([PSE guideline](https://www.pse.pl/documents/31287/20965895/2024.08.06-Guideline+%28v.1.3%29/ccbba7b7-6798-4919-81b6-7c2e5f911b32)).
- **Test events.** PSE can call a test stress event up to once a quarter, also with eight hours' notice.
- **Quarterly demonstration.** The unit must deliver its highest obligation for at least one working-day hour each quarter, or the quarter's remuneration is refunded.
- **Penalties.** Non-delivery in a real or test event incurs a penalty equal to a unit rate multiplied by undelivered capacity.
- **Secondary market.** Obligations can be transferred between units, and after an event over-performance can be reallocated to under-performing units.

### The 550 g rule and your engines

Natural gas emits about 0.202 tCO2 per MWh of fuel (my calculation from standard emission factors). At that factor, a gas engine needs net electrical efficiency of roughly 37% or more to stay under 550 g CO2/kWh. Modern large engines operate well above this, but part-load efficiency matters for certification.

### Policy risk

EU rules allowed Poland to pay high-emission units, mainly coal, until the end of 2028 ([PSE](https://www.pse.pl/web/pse-eng/news/tso-announcements/-/asset_publisher/tKwP8XWSkdU8/content/entry-into-force-of-the-act-amending-the-capacity-market-act-introducing-supplementary-auctions); [BiznesAlert](https://biznesalert.com/brussels-to-flood-poland-with-billions/)). The state aid approval for the scheme is due to expire and a new proposal is expected ([reglobal](https://reglobal.org/capacity-markets-in-europe/)). The regulator has also tuned technology parameters in favour of gas, which critics say conflicts with technology neutrality.

---

## 3. How a grid connection application works

Rules for connections above 1 kV changed on 30 April 2026. A 5–10 MW engine site will generally connect to the distribution operator's medium-voltage or 110 kV network, so these rules apply.

### Process

1. **Prepare.** Secure land rights, a technical concept and a view of local grid capacity. Operators must now publish data on available capacity, applications and refusals ([Polskie Radio](https://www.polskieradio.pl/395/7786/Artykul/3630987,poland-approves-overhaul-of-power-grid-connection-rules)).
2. **Apply for connection conditions** (*warunki przyłączenia*) to the distribution operator, or to PSE for transmission-level connections. Pay the application fee and the advance payment with the application. The application is not reviewed until you pay ([Wolf Theiss](https://www.wolftheiss.com/insights/amendment-to-polands-energy-law-the-so-called-grid-act/)).
3. **Operator review.** The operator assesses technical feasibility, and may re-verify the conditions when you sign the agreement ([CMS](https://cms.law/en/pol/legal-updates/poland-amends-energy-law-unlocking-grid-capacity-and-combating-zombie-projects)). Operators can designate no-connection zones with justification ([Polskie Radio](https://www.polskieradio.pl/395/7786/Artykul/3630987,poland-approves-overhaul-of-power-grid-connection-rules)).
4. **Conditions issued.** They are now valid for 12 months instead of two years, so you must sign the connection agreement within that window ([Wolf Theiss](https://www.wolftheiss.com/insights/amendment-to-polands-energy-law-the-so-called-grid-act/)).
5. **Connection agreement and collateral.** Collateral is due within 14 days of signing, or the agreement lapses.
6. **Permits and milestones.** The agreement expires automatically if you do not obtain a final building permit within the statutory deadline. Deadlines listed are 24 months for photovoltaics, storage and some other categories and 36 months for wind and biogas. Gas engines are not listed in that summary, so confirm the deadline for thermal plants with counsel ([Wolf Theiss](https://www.wolftheiss.com/insights/amendment-to-polands-energy-law-the-so-called-grid-act/)).
7. **Build, commission and operate.** If an agreement is terminated for missing milestones, the operator must auction the freed connection point ([CMS](https://cms.law/en/pol/legal-updates/poland-amends-energy-law-unlocking-grid-capacity-and-combating-zombie-projects)). Generation also needs the approvals and licences from the energy regulator described in the [Chambers Poland guide](https://gpg-pdf.chambers.com/power-generation-transmission-and-distribution-2026/272/).

### Costs at a glance

| Item | Amount | When |
|---|---|---|
| Application fee | PLN 1/kW, capped at PLN 100,000, non-refundable | With the application |
| Advance on connection fee | PLN 60/kW, capped at PLN 6m (previously PLN 30/kW) | With the application |
| Performance collateral | PLN 30/kW below 100 MW, capped overall at PLN 12m | Within 14 days of signing the agreement |

Source: [Wolf Theiss](https://www.wolftheiss.com/insights/amendment-to-polands-energy-law-the-so-called-grid-act/); the increase from PLN 30 to PLN 60/kW is also covered by [CMS](https://cms.law/en/pol/legal-updates/poland-amends-energy-law-unlocking-grid-capacity-and-combating-zombie-projects). For a 10 MW site: PLN 10,000 application fee, PLN 600,000 advance, PLN 300,000 collateral.

### New agreement types

- **Flexible agreement.** You connect now at limited output until the operator finishes grid reinforcement. The limit may last at most three years from signing, and the operator must tell you within 30 days of completing the works.
- **Customisable agreement.** For locations where unrestricted connection is not possible even after expansion. Limits can vary by time or grid conditions, and the operator need not lift them.
- **Capacity tenders.** Until the end of 2028 operators may allocate part of the available capacity by competitive tender instead of queue order.

Source for all three: [Wolf Theiss](https://www.wolftheiss.com/insights/amendment-to-polands-energy-law-the-so-called-grid-act/). See also the legal summaries from [Schoenherr](https://schoenherr.eu/content/poland-s-grid-connection-reform-a-necessary-reset-for-the-energy-transition) and [Baker McKenzie](https://www.bakermckenzie.com/en/insight/publications/2026/03/poland-grid-act-to-change-res-and-bess-grid-connection-rules).

---

## 4. Glossary

| Polish | English |
|---|---|
| *Rynek Dnia Następnego (RDN)* | Day-ahead market |
| *Rynek Bilansujący (RB)* | Balancing market |
| *Rynek mocy* | Capacity market |
| *Obowiązek mocowy* | Capacity obligation |
| *Okres zagrożenia* | System stress event |
| *Warunki przyłączenia* | Connection conditions |
| *Umowa o przyłączenie* | Connection agreement |
| *OSD* | Distribution system operator |
| *URE* | Energy Regulatory Office |

---

## 5. What I could not verify

- Whether the old rule requiring generators to sell a share of output on the exchange still applies. I did not find a current source.
- The licensing threshold for a gas engine plant. Confirm with counsel.
- The availability correction factor for gas engines in the next auction.
- The statutory deadline for the operator to issue connection conditions, and the building-permit deadline for thermal plants.
- Whether a CHP plant can hold a CHP support premium and a capacity contract at the same time. The certification declarations suggest it cannot, so check before assuming you can combine them.
- Typical elapsed times for conditions and connection works. Ask the relevant distribution operator.

Secondary sources (law-firm notes, trade press and analyst blogs) should be checked against the primary documents: the Capacity Market Act, PSE's capacity market rules, TGE's rules and the Energy Law.

*Not legal, tax or investment advice.*
