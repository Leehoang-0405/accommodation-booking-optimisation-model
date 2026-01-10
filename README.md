# Revenue Optimization & Booking Management Decision Support System

## 1. Executive Summary
Coastal Nest Motel, a 20-unit boutique property, required a robust framework to navigate the volatility of peak holiday seasons. This project replaced static pricing strategies with a **Monte Carlo Simulation** model to balance occupancy, overbooking, and financial risk. By identifying that a "safe" $120 nightly rate yielded only $119 in average daily profit, this solution optimized pricing to $150, increasing average profit to **$613 per day** while maintaining a less than 2% probability of loss. This work empowered management to move from conservative, low-yield decisions to data-backed, high-reward strategies.

## 2. Business Problem
**The Decision:** Motel management was repeatedly making critical decisions regarding nightly room rates and overbooking levels based on fixed assumptions of holiday demand.

**The Failure:** The existing logic was flawed because it treated highly variable factors,such as late cancellations, walk-in arrivals, and miscellaneous expenses—as constants. This led to a "one-in-four risk of loss" at lower price points and a failure to capture significant revenue during high-demand windows.

**The Impact:** Inefficient pricing and poor overbooking management meant the motel was either overpaying for "bumped" guests or leaving rooms empty during its most profitable season. Without a stochastic model, the motel faced high volatility where even profitable days seldom reached their full earning potential.

## 3. Methodology
* **Conceptual Model Construction:** Developed a structured Input-Process-Output framework integrating four sources of uncertainty (Stochastic Inputs) with three managerial levers.
* **Monte Carlo Simulation:** Utilized MS Excel to simulate daily operations across peak-season windows (Dec 1 – Feb 28/29), accounting for late-cancellation percentages and varying net demand.
* **Scenario Analysis:** Systematically tested decision variables, including room nightly rates ($120, $150, $180) and overbooking levels, to identify the optimal "sweet spot" for total daily profit.
* **Stochastic Integration:** Modeled discrete and continuous distributions (e.g., for walk-in arrivals and housekeeping costs) to reflect real-world operational fluctuations.

## 4. Demonstration of Skills and Capabilities
* **Advanced Risk Analysis:** Calculated the "probability of loss" for different pricing tiers, proving that an $180 rate carries a high-risk "one-in-three" chance of losing money, whereas $150 virtually eliminates daily losses.
* **Revenue Optimization:** Determined the optimal overbooking level that balances the revenue gained from full occupancy against the compensation costs required for "bumped" guests.
* **Quantitative Modeling:** Built a comprehensive spreadsheet-based decision model that calculates total room availability and net demand by factoring in daily online reservations and cancellation fees.
* **Commercial Strategy:** Evaluated the trade-offs between "sold-out status" and profit margins, ensuring that the model prioritizes robust buffers against cost fluctuations.

## 5. Results & Business Recommendations
* **Optimal Pricing:** The $150 nightly rate is the clear optimal choice, delivering a high average profit ($613/day) and filling nearly all rooms under base demand.
* **Risk Mitigation:** While the $180 rate seems attractive, its volatility requires stronger demand guarantees; the $150 rate is recommended as it delivers strong profits on 97% of simulated days.
* **Strategic Buffer:** Over half of the profitable days at the recommended rate generate $600–$1,000 in profit, providing a robust buffer to absorb unforeseen miscellaneous expenses.
* **Avoidance of "Safe" Traps:** The analysis proved that the most conservative rate ($120) is too inefficient, yielding nearly 80% less profit than the optimized $150 rate.

## 6. Model Integrity & Risk Assessment
While the model successfully identifies the $150 rate as the optimal profit driver, a critical assessment reveals areas for further technical hardening:
* **Financial Logic Refinement:** The current model treats payments to overbooked guests as a simple refund. In real-world operations, "bumping" a guest typically requires additional compensation as a goodwill gesture. Underestimating this cost may slightly skew the net profit outcomes.
* **Exploration of Decision Space:** The current analysis sampled a subset of decision levels. To ensure the findings represent a global optimum, a full systematic evaluation of all 27 possible combinations of decision variables is required.
* **Statistical Governance:** The justifications for specific stochastic inputs, such as whether they were based on historical data, estimated ranges, or expert judgment, require more explicit documentation to improve the realism and credibility of the simulation inputs.
* **Distribution Validation:** While the selected distributions align with motel operations, further justification regarding their key properties (discrete vs. continuous, skewness, and range) is necessary to build total trust in the model's structure.

## 7. Next Steps
* **Incorporate Service Recovery Costs:** Update the model logic to distinguish between simple payment reversals and additional "Goodwill Compensation" to reflect the true financial impact of overbooking.
* **Full-Grid Sensitivity Analysis:** Execute a complete 27-combination simulation set to map the entire decision space and identify any hidden risks or opportunities.
* **Stochastic Hardening:** Provide a detailed rationale for each selected distribution, explaining how parameters were determined, whether calculated from historical data or estimated through expert judgment.
* **Model Transparency:** Enhance the "Assumptions" section by clarifying why each listed constraint is reasonable in the context of Airbnb-style operations, thereby building higher credibility for the model’s outputs.

## 8. Context and Credits
* **Client:** Coastal Nest Motel (Boutique Property).
* **Market Benchmarking:** The property profile and operational parameters are **benchmarked against market research of small-to-medium sized motels (SMEs) in the Melbourne beachside tourist sector.**
* **Program:** MIS775: Decision Modelling for Business Analytics.
* **Individual Contributor:** Ba Huy Hoang Le (s224309594).
* **AI Disclosure:** Generative AI tools were used for refining content and code snippets within the original reports.
