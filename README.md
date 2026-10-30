# Decathalon-Dashboard
## 1 Business Scenario 
The retail management team needs one interactive report page to monitor sales, profitability, order activity, and product performance. Managers must be able to compare the current year with the equivalent period last year and identify the sports, product types, regions, and brands driving results. The dashboard must support investigation of performance by state, sport, product colour, payment method, and promotion. It should help users identify where further investigation or commercial action is needed; it must not imply causes that the data does not establish.
## 2 Business questions 
1.	What are current YTD net sales and gross profit, and how do they compare with PYTD? 
2.	Is gross margin improving, and by how many percentage points? 
3.	How have units, order count, and average order value changed? 
4.	Which months show growth or decline against the same period last year? 
5.	Which sports generate the most YTD net sales? 
6.	Which product types combine strong sales with strong margins? 
7.	How much does each region contribute to YTD sales? 
8.	Which brands have the strongest and weakest YTD sales growth? 
9.	How do these answers change when a user applies the available filters? 
## 3. Scope 
Deliver one interactive Power BI report page containing a reporting-period header, six KPI cards, five analytical visuals, a left filter panel, and a reset button. 
Included: sales and gross profitability, same-period comparisons, product and geographic segmentation, and report interactions. 
Excluded: sales targets, forecasting, inventory availability, customer retention, market-share analysis, and claims about promotion effectiveness. These require additional data or analysis. Benchmark lines in this report are internal calculations, not market benchmarks.
## 4.KPI requirements : 
Each card must show the primary YTD result, the PYTD result, and the year-over-year change.
## 5. Filters and interactions : Use dropdown slicers with clear headings and multi-select support
Slicer label 	Field 
State 	store[State] 
Sport 	products[Sport] 
Colour 	products[Colour] 
Payment Method 	sales[Payment_Method] 
Promotion 	sales[Promotion] 

### Screenshot (https://github.com/milindwasekar/Decathalon-Dashboard/blob/main/Decathelon_Report.png)
