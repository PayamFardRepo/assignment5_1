Report on Coupon Acceptance Analysis for Various Drivers

Dataset Overview

    - The dataset contains 12,684 entries with 26 attributes, including demographic details, dining habits, and coupon redemption behavior.
    - The data was cleaned to retain 12,079 valid records after removing missing values.

Key Findings

- Overall Coupon Acceptance
  - Out of 12,079 observations, 6,877 (56.9%) accepted coupons.
  - This suggests a moderate engagement with coupons in the dataset.
- Bar Coupon Analysis
  - The dataset contained 1,996 instances of bar coupons.
  - 819 (41%) of these were accepted, which is lower than the overall acceptance rate.
- Factors Influencing Acceptance
  - Drivers who accepted the bar coupons have the following characteristics:
      - They have income levels more than 50K
      - They are mainly under the age of 30
      - They do not have kids in their cars
      - They are not windowed
      - They do not frequently go to cheap restaurants
- Independent Investigation Findings on Weather and Temperature
  - Weather seems to have significant effect on whether coupon is accepted or not. As you can see snowy days have significantly less acceptance (i.e. 76)
  - Rainy has more but significantly less than sunny days (i.e. 156) and sunny has the most number of acceptance (i.e. 587)
  - Temperature seems to have impacts also on acceptance. When the weather is not too hot or too cold, acceptance has been highest (i.e. on temperature of 55, 425 acceptance)
     - Too cold has the least acceptance (i.e. temperature of 30 has only 138 acceptance)
     - Too hot has much more than too cold but much less than comfortable temperature (i.e. on temperature 80, 256 acceptance)
		
