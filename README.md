# Food-Delivery_real_problem

**Objective:**  
The goal in logistic is to make Average of delivery time of each zone less than 23 mins, and the total cost is fixed.  
  
**Questions:**
+ How much the *CPO should be during *peak / off-peak time for each zone, to affect rider behavior and hit the logitic target? Why?
+ Are there any other key findings from this data can also help achieve the goal?
+ What external factors do you think have not been considered in this data?
+ And what will you do if you have them?

# Assumption:  
+ planned_rh: The expected time spent for all drivers from pickup orders to arrive at customer in a given region and specific time
+ actual_rh: The actual time spent for all drivers from pickup orders to arrive at customer in a given region and specific time
+ total_payment:  
    + qual to CPO here.  
    + Avg.CPO = total_payment / orders 
+ Interval_idle_rh: The overall timeframe drivers is idling, which is [planned_rh] - [actual_rh]
+ Day_of_week: Assuming the weekday or weekend would make no difference in this scenario
