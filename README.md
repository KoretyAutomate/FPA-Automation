# FPA-Automation
FP&amp;A professional, trying to replace himself
The final goal is to completely replace FP&A with automation/AI but I will take step by step automating part of FP&A work. For those who are not familiar with the job of FP&A, FP&A does simply 3 things (but usually in many different and complex ways).
1) Drive Resource Allocation: using facts and scenario planning, addressing key business needs. In Pharma, focus usually is "Unmet Medical Needs" or "Unmet Patient Needs". The end result of this usually is budget.
2) Variance Analysis: Comparing sales and costs performance vs Budget, Forecast, Prior Year, Prior Quarter, Prior Month. Mostly vs Budget, Forecast, and Prior Year.
3) Scenario Planning: Both Budget and Forecast are including these, which includes Base Case and Risks & Opportunities. It shows the ranges of the plan Management is deciding for, and fluctuation factors by showing "What-if" analysis

# Initial Task to tackle
Sales driver analysis for Pharmaceutical Business. If automation of this process is achieved, it basically means confirmation that "Variance Analysis" automation is possible, and defines the data structure + charactoristic of required dataset to run Variance Analysis, which will ultimately define what needs to be considered in Scenario Planning. Once both Variance Analysis and Scenario Planning are automated, Driving Resource Allocation is only requiring facilitation and can eliminate the job functionality itself if Managements are fine with having AI as an interface.

Drivers:
1) Demand: this means ex-WS sales if WS is involved, if not, ex-Manufacturer sales
2) WS Inv: In other words, trade inventory. Sales increase / decrease from this usually is not considered as pure performance. Requires monitoring of fluctuation and WS Inv level from healthy business operation
3) Price: This focus on Gross price changes of the product. US has price increase as a norm while ex-US are more common to observe price decrease
4) GTN / Rebate / Discount: Naming could vary depending on the company, but this basically shows the difference between Gross Sales and Net Sales. It indicates how competitive the product is priced
5) Other: Anything which doesn't fall in above category, like 
