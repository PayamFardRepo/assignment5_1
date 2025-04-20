Report on Coupon Acceptance Analysis for Various Drivers

Dataset Overview
•	The dataset contains 12,684 entries with 26 attributes, including demographic details, dining habits, and coupon redemption behavior.
•	The data was cleaned to retain 12,079 valid records after removing missing values.

Key Findings

1.	Overall Coupon Acceptance
	o	Out of 12,079 observations, 6,877 (56.9%) accepted coupons.
	o	This suggests a moderate engagement with coupons in the dataset.
2.	Bar Coupon Analysis
	o	The dataset contained 1,996 instances of bar coupons.
	o	819 (41%) of these were accepted, which is lower than the overall acceptance rate.
3.	Factors Influencing Acceptance
	o	Drivers who accepted the bar coupons have the following characteristics:
		1.	They have income levels more than 50K
		2.	They are mainly under the age of 30
		3.	They do not have kids in their cars
		4.	They are not windowed
		5.	They do not frequently go to cheap restaurants
4.	Independent Investigation Findings on Weather and Temperature
	o	Weather seems to have significant effect on whether coupon is accepted or not. As you can see snowy days have significantly less acceptance (i.e. 76)
	o	Rainy has more but significantly less than sunny days (i.e. 156) and sunny has the most number of acceptance (i.e. 587)
	o	Temperature seems to have impacts also on acceptance. When the weather is not too hot or too cold, acceptance has been highest (i.e. on temperature of 55, 425 acceptance)
		1.	Too cold has the least acceptance (i.e. temperature of 30 has only 138 acceptance)
		2.	Too hot has much more than too cold but much less than comfortable temperature (i.e. on temperature 80, 256 acceptance)
