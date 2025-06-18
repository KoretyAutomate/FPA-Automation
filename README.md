# FPA-Automation

> An initiative to automate the core functions of Financial Planning & Analysis, by an FP&A professional attempting to automate his own job.

## The Vision: Autonomous Financial Planning

This project aims to systematically automate the high-value, repetitive tasks of Financial Planning & Analysis (FP&A). The ultimate goal is to create a system that can autonomously handle core analytical functions, transforming the role of FP&A from manual data processing to strategic oversight and decision-making.

At its core, FP&A revolves around three critical functions:

1.  **Drive Resource Allocation:** Guide strategic investment and budgeting decisions using data-driven scenario planning to address key business opportunities (e.g., "Unmet Patient Needs" in the pharmaceutical industry).
2.  **Variance Analysis:** Evaluate business performance by comparing actual financial results (sales, costs) against benchmarks like the Budget, Forecast, and Prior Year. This analysis is crucial for course correction and adapting investment decisions.
3.  **Scenario Planning:** Model a range of potential future outcomes (Base Case, Risks, Opportunities) to understand the potential impact of different variables and support robust management decisions.

## 🎯 Phase 1: Automating Sales Driver Analysis

The first major milestone is to build a robust and automated **Sales Driver Analysis** module, specifically for the pharmaceutical industry.

This initial task was chosen strategically:

* **Foundation of Variance Analysis:** A successful sales driver module is the cornerstone of automating variance analysis.
* **Defines the Data Architecture:** It forces the creation of a clean, structured dataset, which will be the backbone for all future automation.
* **Unlocks Scenario Planning:** Understanding what drives historical variance is the key to accurately modeling future scenarios.

### Key Sales Drivers to Analyze

The analysis will focus on quantifying the impact of the following common sales drivers:

* **Demand:** The underlying consumption of the product. Often referred to as ex-wholesaler or ex-manufacturer sales.
* **Wholesaler Inventory:** The change in inventory levels held by distributors. Fluctuations here can distort underlying performance and require careful monitoring.
* **Price:** The impact of gross price increases or decreases on revenue.
* **Gross-to-Net (GTN):** The impact of rebates, discounts, and chargebacks. This is a critical indicator of market access and pricing competitiveness.
* **Other:** A catch-all for unique, ad-hoc events (e.g., competitor supply issues, clinical trial purchase, etc.) that need to be isolated.

## Technology & Methodology

The initial prototype and proof-of-concept for the Sales Driver Analysis will be developed using a rapid iteration approach with readily available tools:

* **Microsoft Excel:** For data presentation and the initial user interface.
* **VBA (Visual Basic for Applications):** To automate repetitive tasks within the Excel prototype, such as refreshing data connections and managing user inputs.
* **Power Query:** For data extraction, transformation, and loading (ETL) from various sources.
* **Power Pivot (Excel Data Model):** For creating the relational data model and performing complex calculations using DAX.

This stack allows for quick validation of the core logic and data architecture. Once the methodology is proven and refined, the long-term vision is to evolve this project into a standalone software application.

## The Problem Space: Common Challenges to Overcome

This project directly addresses the following real-world challenges that plague traditional FP&A processes:

1.  **Siloed Systems:** Planning and actuals data often live in different tools (e.g., ERPs, planning software), requiring complex and fragile master data mapping.
2.  **External Data Integration:** Analysis requires manually blending internal data with external sources like wholesaler reports, market research, and third-party syndicated data.
3.  **Mismatched Granularity:** There is often a mismatch in the level of detail between planning data (high-level) and actuals data (transaction-level).
4.  **Poor Data Quality:** Issues like unallocated rebates or ambiguous commentary on performance submitted by local teams make analysis slow and subjective.
5.  **Manual Consolidation:** Aggregating and consolidating analyses from individual markets to a regional or global level is a time-consuming and error-prone process.

## Hypothesis Tracking

This project will be managed using a hypothesis-driven approach. New ideas for features, models, or process improvements will be documented as formal hypotheses. We will use GitHub's features to track them:

* **GitHub Issues:** Each hypothesis will be logged as an issue, tagged with `hypothesis`.
* **GitHub Projects:** A Kanban board will be used to visualize the status of each hypothesis (e.g., `Backlog`, `Testing`, `Validated`, `Invalidated`).
* **Pull Requests:** Code written to test a hypothesis will be linked to the corresponding issue to maintain a clear connection between the idea and its implementation.

## Contributing

Currently, this is a solo project, but insights, suggestions, and feedback are welcome. Please open an issue to start a discussion.

## License

MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
