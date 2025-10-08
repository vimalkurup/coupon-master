
Link to Jupyter notebook:https://github.com/vimalkurup/coupon-master/blob/master/m5_coupon_analysis.ipynb
GitHub Repo: https://github.com/vimalkurup/coupon-master

Business Problem
The goal of this project is to understand key features that distinguish between customers who accepted a driving coupon versus those that did not

Key Takeaway
Based on coupon types, we are able to distinguish the appeal to difference demographics. This could used to build a recommendation system to customers as coupon engine is rolled out


Findings
Bar Coupon
	- High likelihood of customer accepting coupons when with Friends; Passengers with kids had the lowest likelihood of accepting
	- Coupons issued after 6PM saw higher acceptance compared to coupons issued prior
	- Coupon had higher acceptance when weather was Sunny vs Snowy/Rainy conditions
	- Customers single had the highest acceptance rate within marital status cohorts

Coffee Coupon
	- Customers travelling with Friends/Partner had the highest likelihood of accepting coffee coupon
	- 10AM was the sweet spot for timing the coupon
	- Rainy and Sunny weather saw highest change of coupon acceptance
	- All relationship status with the exception of Widowed showed high levels of accepting coffee coupon

TakeOut
	- Customers travelling with Friends/Partner had the highest likelihood of accepting takeout coupon
	- Post 2pm, customers had higher coupon acceptance
	- Sunny weather followed by Snowy weather correlated with higher coupon acceptance
	- Widowed customers showed great deal of separation compared to other relationship cohorts

Restaurant<20
	- Customers travelling with Friends/Partner had the highest likelihood of accepting coupon
	- 2pm-6pm, customers had higher coupon acceptance
	- Sunny weather showed higher coupon acceptance
	- Single/Unmarried customers showed great deal of separation compared to other relationship cohorts

Restaurant20-50
	- Customers travelling with Friends/Partner had the highest likelihood of accepting takeout coupon
	- Customers had higher coupon acceptance at 10AM followed by 2pm
	- Sunny weather followed by Snowy weather correlated with higher coupon acceptance
	- Unmarried and Single customers showed higher rates of coupon acceptance



Technicality
- Pandas for data reading/wranging/cleanup
- Plotly for Visualization (Scatter plots and Bar graphs)

Assumptions
- Customers missing details on numbers of visits to Bar/Restaurant etc were assumed to have never visited

Credits
- https://github.com/toby-gardner-ai/uc-berkeley-aiml-course/blob/main/notebooks/Mod4_Data_Analytics.ipynb

Limitations
- Visuals on Plotly were saved as html to share in the directory. I personally prefered looking at visuals on Notebooks to write this summary up
