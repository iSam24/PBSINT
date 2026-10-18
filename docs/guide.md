### 1. What a top professional would do that you didn’t ask for
Replace the flat energy assumption with an hourly dispatch model. 

For a peaking engine, the revenue is made or lost in a few hundred scarcity hours, and my “1,200 hours at an average price” hides exactly that. 

a). They would optimise dispatch against a price curve with:
* start costs
* minimum run times and ramp limits. 

Forecast prices under several fundamental scenarios and report P50/P90. That means gas, carbon, coal exit, solar and battery build-out, and cross-border flows. The P90 case, not the base case, sizes the debt. Treat the capacity price as a distribution. 

b). They would simulate the auction using PSE’s certification data (supply by technology, de-rating, demand) to estimate how likely a 5–10 MW engine project is to win, at what price, and for how long. Model the policy cliff explicitly. State aid and the coal derogation expire at end-2028. They would assign probabilities to a new scheme, changed de-rating factors and a gap, rather than run a single downside case. 

c). Test heat as the base case. A standalone engine competes with batteries and large gas plants, while a CHP engine on a district heating network has a different revenue stack and support scheme. Run the financing and structuring analysis. That covers debt sizing on P90 cash flows, interest-limitation rules, withholding tax leakage through the holding structure, and FX hedging cost from forward points.Run a competitive and legal check. Who bids against you, which licences and environmental permits apply to engines, and whether your project meets the capacity-market eligibility rules. 

d). Set kill criteria. They would define up front the capex, capacity price and gas price at which the project stops being worth doing, and compare Poland against your other shortlisted markets on the same basis.

### 2. The rawest material to start from
Prices and system data: hourly day-ahead and intraday prices, load, generation by type and cross-border flows from the ENTSO-E Transparency Platform and TGE; PSE’s balancing market data (imbalance prices, reserve procurement and activation).
Capacity market primary documents: the Capacity Market Act and rules, the ministerial regulation setting each auction’s parameters (de-rating factors, capex thresholds, demand), PSE’s certification data (“Rynek mocy w liczbach”), and the final results published by the regulator, URE.
Rules and tariffs: PSE’s balancing rules and network code, the distribution network codes and connection-capacity data of the four DSOs, and URE’s gas transmission and distribution tariff decisions.
Policy documents: the EU Commission’s state aid decision on the Polish capacity market, and the Polish energy plans (National Energy and Climate Plan and the energy policy to 2040).
Forward curves: ICE EUA and TTF futures, TGE power and gas forwards, and FX forward points.
Project economics: firm quotes and long-term service agreement terms from engine makers, EPC bids, DSO written connection conditions, and filed accounts of existing Polish engine and CHP companies from the national court register.

### 3. Methods and tools
Dispatch and revenue: a mixed-integer dispatch optimisation in Python (Pyomo with HiGHS) or a commercial market model such as PLEXOS or Aurora. Price paths come from a merit-order model calibrated to ENTSO-E data, with price shape resampled from historical hours.
Capacity auction: a descending-clock auction simulation using certified supply and demand, run over many scenarios.
Financial model: built to the FAST standard in Excel with a Python mirror. It would include debt sculpted to DSCR, Polish corporate tax and interest limits, withholding tax, FX hedging, Monte Carlo for P50/P90, a tornado chart, and break-even solves for the target IRR.
Reconciliation: back out implied prices from disclosed winners, for example PGE’s reported 538 MW 15-year contract worth over PLN 4bn, and check that the model reproduces them.

### 4. What, other than you or me, would show the result is right
A third-party model audit. Specialist firms such as Operis or Mazars check logic, not just numbers.
A backtest. Run the dispatch model on 2025 actual prices and compare it with the realised revenues of a comparable Polish peaking or CHP asset. If it can’t reproduce the past, it can’t be trusted on the future.
Reproducing published auction results. The simulation should land near PLN 465.02 and PLN 534.09 from PSE’s own certification data.
An independent market study from an adviser lenders recognise, such as Aurora, AFRY or Baringa.
Binding third-party documents: DSO connection conditions, OEM and EPC quotes, a gas supplier’s indicative offer, and a lender’s indicative term sheet showing gearing and margin.
Polish counsel and tax adviser opinions on ownership, licensing and withholding tax.

The strongest of these are the backtest and the lender’s technical and market advisers, because lenders put their own money behind the answer.