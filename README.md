# The Starch Trap — WID Datathon, Slow Cooked

**Women in Data Datathon 2026 · "What's Cooking?"**

> The world trades calories, not nutrition. Half of all dietary energy now crosses a border before it's eaten, but imported calories are systematically less nutrient-dense than domestically produced ones. Which countries have traded their way into a starch-rich, micronutrient-poor food supply, and does it show up in women's nutrition outcomes? Which additional countries are trending toward this by 2030, and can trade composition serve as an early-warning signal for rising anemia risk?

| | |
|---|---|
| 🌐 **Website (data story)** | [`index.html`](index.html) |
| 🎤 **Presentation (7-minute pitch)** | [`presentation.html`](presentation.html) — press **N** for speaker notes, **F** for full screen |

---

## The answer in four lines

| Question | Answer |
|---|---|
| **Which countries?** | **12** are import-heavy, starch-heavy *and* micronutrient-poor at once: Lesotho, Gambia, Mauritania, Liberia, Yemen, Djibouti, Botswana, Eswatini, Namibia, Iraq, Bhutan, Timor-Leste. |
| **Does it show up in women?** | **Yes, between countries:** median anemia in women 15–49 is **32.8%** in trap countries vs **24.7%** elsewhere. The starch effect keeps 74–86% of its size after controlling for malaria, water, sanitation, fertility and stunting. |
| **Who's next by 2030?** | A watch list, not a forecast: **Morocco, Cabo Verde and Haiti** each meet two of three conditions and sit very close to the third. |
| **Early-warning signal?** | Trade composition flags **who** is exposed, not **when** anemia will rise. |

## Key findings

- **The premise holds.** The average imported share of calories rose from **43.0% (2010) to 50.4% (2023)**. In **146 of 178** countries, home-grown calories are more nutrient-dense than imported ones.
- **The world ships what keeps.** Sugar, oils and cereals are the most traded foods and carry the least iron per calorie; vegetables, eggs and roots mostly stay home.
- **Iron form beats iron amount.** Niger supplies 24.2 mg of iron a day, yet 47% of women are anemic; only 4% of that iron comes from animal sources.
- **It's a women's story.** Women are more food-insecure than men in 98 of 135 countries, animal-source foods cost 1.8× starchy staples, and anemia in women rose in 123 of 162 countries since 2010.
- **What didn't hold.** Import dependence alone, within-country changes in diet, a 3-year lagged early-warning signal, and food prices as the channel. **Trade isn't the villain — it's the amplifier.**

## Recommendations

1. **Fortify imported staples at the port** — wheat, rice, maize and oil.
2. **Rebalance the import basket** toward pulses, fish, eggs and milk.
3. **Protect the nutrient-dense food grown at home.**
4. **Put women 15–49 first** — iron–folic acid supplementation and vouchers for iron-rich foods.
5. **Run a yearly starch-trap monitor** to catch watch-list countries early.
6. **Treat the non-food causes** — malaria control and clean water where trade isn't the route.

## Data sources

- FAOSTAT **Food Balance Sheets** and **Supply Utilization Accounts** (178 countries, 2010–2023)
- World Bank WDI — anemia in women 15–49 (`SH.ANM.ALLW.ZS`), GDP per capita PPP (`NY.GDP.PCAP.PP.KD`), malaria incidence (`SH.MLR.INCD.P3`)
- WHO Global Health Observatory — malaria, water, sanitation, adolescent births, stunting
- DHS Program — measured anemia and iron supplementation
- FAOSTAT Food Security Indicators, Cost of a Healthy Diet, Detailed Trade Matrix
- WFP Global Market Monitor and World Bank Commodity Price Data (Pink Sheet)

## Limitations

National food **supply** is not individual **intake**, and it hides who eats what within a household. Results are cross-country associations, not proof of cause. Anemia figures are WHO modelled estimates. Price projections are simple extrapolations of world US-dollar prices, not inflation-adjusted.

## Viewing locally

Both pages are single self-contained HTML files. Download and open them in any modern browser — no build step required. Fonts load from Google Fonts when online.

---

*Built for the Women in Data "What's Cooking?" Datathon 2026.*
