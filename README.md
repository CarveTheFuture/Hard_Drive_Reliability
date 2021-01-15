# Hard_Drive_Reliability
Drive hard failures can be costly, but are mostly avoidable. This study will examine the details.


SMART
S.M.A.R.T. (often written as SMART) is a monitoring system included in computer hard disk drives (HDDs), solid-state drives (SSDs),[1] and eMMC drives. Its primary function is to detect and report various indicators of drive reliability with the intent of anticipating imminent hardware failures.

When S.M.A.R.T. data indicates a possible imminent drive failure, software running on the host system may notify the user so preventive action can be taken to prevent data loss, and the failing drive can be replaced and data integrity maintained.
A null check was performed. As shown there were no individual null values. Those only occured for the entire column, as described earlier.
![test](http://samplesite.com/somesample.jpg)
<img src="https://macdatarecoverysolutions.files.wordpress.com/2015/05/harddrivefailure_prime-100028965-large.jpg" width="300"/>





Data Source
Every month 
Since 2013, 
Backblaze has been generating 1 comma separated values spreadsheet with 
one entry per day 
for each of the 100s of thousands of drives in its data center. Each spreadsheet entry records  more than 50 of the 255 S.M.A.R.T. hard drive monitoring metrics.



![test](http://samplesite.com/somesample.jpg)
<img src="https://images.wondershare.com/recoverit/article/2019/06/common-causes-of-hard-drive-failure.jpg" width="300"/

In order to determine how to predict the lifespans with the health monitoring attributes, at first a regression analysis was performed. The remining useful days was calculated for each observation by subtracting the observation date from the failure date. This was then used as a target while the monitored attributes were used as features. The accuracy of this model was very low.

Next the observed lifespans for each unit were grouped into 12 sets. These were fed into a classifier model as targets, and monitored features as inputs. This time, the accuracy (0.81) was much higher. 

Thus we can for all the group predict with a greater than 60% success rate, whether it will suffer very early death or operate closer to the expected lifespans of >40000 hours.
