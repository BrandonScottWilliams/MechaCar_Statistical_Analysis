# MechaCar_Statistical_Analysis
## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/99148657/174500673-7bc49734-29b0-4134-87b9-a399a4039312.png)
![image](https://user-images.githubusercontent.com/99148657/174500691-884df080-28ad-4561-9cbe-7ce4008b6fa5.png)
The design specifications for the MechaCar suspension coils dictate that the variance of each suspension coil should not exceed 100 PSI. The only non-compliant lot is lot 3 with a variance of 170.29. This heavily skews the overall variance as lot 1 and 2 are stable with variances of 0.98 and 7.47 respectively. The manufacturing lots on a whole have a variance of 62.3 which on its own does not exceed the threshhold.


## T-Tests on Suspension Coils
### Test all lots
![image](https://user-images.githubusercontent.com/99148657/174502703-792ed9fe-71a0-42bd-8b98-204e1f623081.png)
 
The mean of the sample is 1498.78. Because the p-Value is 0.06 and the significance level is lower at 0.06 there isn't enough evidence to reject the null hypothesis. The PSI across all manufacturing lots are different from the population mean of 1500 pounds per square inch.


### Test lot 1
![image](https://user-images.githubusercontent.com/99148657/174502102-2d5fada5-0898-4d26-aac3-476e6e733881.png)

Lot 1 has a true sample mean of 1500 and a p value of 1 meaning that we accept the null hypothesis. There are no statistical differences between the sample and population mean.
###  Test lot 2
![image](https://user-images.githubusercontent.com/99148657/174502109-19e188c1-ab5b-48dc-8a0a-c6950b15952b.png)
Lot 2 has a true sample mean of 1500.02 and a p value of 0.61 meaning that we accept the null hypothesis. There are no statistical differences between the sample and population mean.
### Test lot 3
![image](https://user-images.githubusercontent.com/99148657/174502116-4c0d6819-4d71-497e-8aab-d737f509a9ef.png)

Lot 3 has a true sample mean of 1496.14 and a p value of 0.04 meaning that we reject the null hypothesis.

