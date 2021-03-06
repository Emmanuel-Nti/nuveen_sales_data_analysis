# Nuveen Sales Data Analysis


| Project Description | Libraries Used | Source of Data |
| :---------------------- | :---------------------- | :---------------------- | 
| Nuveen, a mutual fund company headquartered in Chicago, with major offices across the globe. Nuveen is tasked with marketing and selling mutual funds through investment professionals such as brokers, financial planners, and financial advisors. Nuveen charges investors a percent of assets under management (AUM). Therefore, the more they sell, and the longer it stays in their mutual funds, the more revenue they receive.Their goals are to acquire new clients cost-effectively, sell more to existing clients, reduce redemptions by acquiring, developing, and retaining (ADR). It is likely that Nuveen has a relatively small percent of clients that account for a high percentage of their profit As a data analyst, given transactions data for 2018, I would like to assist the sales and marketing team to improving their targeting by predicting the probability of clients adding new funds for the next 12 months. | *pandas*, *numpy*, *seaborn*, *matplotlib.pyplot*, *sklearn*, *scikitplot*, *statsmodels.api*, *missingno*, *imblearn* | Emeritus Institute of Management|

## Description of Data

- `CONTACT_ID`:	Distinct identification of FA
- `no_of_sales_12M_1`:	#of sales in last 12 M having >=1$
- `no_of_Redemption_12M_1`:	#of redemption in last 12 M having >=1$
- `no_of_sales_12M_10K`:	#of sales in last 12 M having >=10K$
- `no_of_Redemption_12M_10K`:	#of redemption in last 12 M having >=10K$
- `no_of_funds_sold_12M_1`:	# of funds sold to FA in last 12 months having >=1$
- `no_of_funds_redeemed_12M_1`:	# of funds redeemed by FA in last 12 months having >=1$
- `no_of_fund_sales_12M_10K`:	# of funds sold to FA in last 12 months having >=10K$
- `no_of_funds_Redemption_12M_10K`:	# of funds redeemed by FA in last 12 months having >=10K$
- `no_of_assetclass_sold_12M_1`:	# of asset class sold to FA in last 12 months having >=1$
- `no_of_assetclass_redeemed_12M_1`:	# of asset class redeemed by FA in last 12 months having >=1$
- `no_of_assetclass_sales_12M_10K`: 	# of asset class sold to FA in last 12 months having >=10K$
- `no_of_assetclass_Redemption_12M_10K`:	# of asset class redeemed by FA in last 12 months having >=10K$
- `No_of_fund_curr`:	# of funds currently held on the refresh date
- `No_of_asset_curr`:	# of funds currently held on the refresh date
- `AUM`:	AUM till current refresh date
- `sales_curr`: total sales in current month
- `sales_12M`:	total sales in last 12 months (excluding current month)
- `redemption_curr`:	total redemption in current month
- `redemption_12M`:	total redemption in last 12 months (excluding current month)
- `new_Fund_added_12M`:	new funds added in the last 12 Monts excluding current month
- `redemption_rate`:	total redemtion in current month/total AUM till current month
- *AUM for different asset class*
   - `aum_AC_EQUITY`	
   - `aum_AC_FIXED_INCOME_MUNI`	
   - `aum_AC_FIXED_INCOME_TAXABLE`	
   - `aum_AC_MONEY`	
   - `aum_AC_MULTIPLE`	
   - `aum_AC_PHYSICAL_COMMODITY`	
   - `aum_AC_REAL_ESTATE`	
- *AUM for different product type*
   - `aum_AC_TARGET`	
   - `aum_P_529`	
   - `aum_P_ALT`	
   - `aum_P_CEF`
   - `aum_P_ETF`	
   - `aum_P_MF`	
   - `aum_P_SMA`	
   - `aum_P_UCITS`	
   - `aum_P_UIT`
- `refresh_date`:	The date at which the data has been refreshed
