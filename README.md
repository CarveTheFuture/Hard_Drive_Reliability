# Hard_Drive_Reliability
Have you ever lost data due to hard drive failure? The use of hard drives has been growing exponentially, a they are used on computers to store data.
Drive hard failures can be costly and painful, especially as more voluminous, and freqently valuable, data is stored on them.
The causes of hard drive failures are varied.
Some may be due to mishaps, such as :
	Water Damage,
	Human Error,
	Unforeseen Mishaps, and
	Extreme Energy (Thermal/Magnetic).
Some which are possibly preventable are:
	Virus or Faulty Software,
	Un-allocated Space Issue,
	Hardware Issues,
	Mechanical Flaws,
	Power Issues, and
	Firmware Corruption .

This study will examine the details for those failure casuses which are preventable.

About 20 years ago, a Google paper reported that up to 40% of units which failed, did not have any associated SMART flags.

SMART
One might be asking - 'What are SMART flags?' According to Wikipedia, S.M.A.R.T. (often written as SMART) is a monitoring system included in computer hard disk drives (HDDs), solid-state drives (SSDs),[1] and eMMC drives. Its primary function is to detect and report various indicators of drive reliability with the intent of anticipating imminent hardware failures.

When S.M.A.R.T. data indicates a possible imminent drive failure, software running on the host system may notify the user so preventive action can be taken to prevent data loss, and the failing drive can be replaced and data integrity maintained.


![test](http://samplesite.com/somesample.jpg)
<img src="https://macdatarecoverysolutions.files.wordpress.com/2015/05/harddrivefailure_prime-100028965-large.jpg" width="300"/>





Data Source
Every month, since 2013, Backblaze (http://www.Backblaze.com) has been generating 1 comma separated values spreadsheet with one entry per day for each of the 100s of thousands of drives in its data center. Each spreadsheet entry records  more than 50 of the 255 S.M.A.R.T. hard drive monitoring metrics.



![test](http://samplesite.com/somesample.jpg)
<img src="https://images.wondershare.com/recoverit/article/2019/06/common-causes-of-hard-drive-failure.jpg" width="300"/

After extensive review of the data, Seagate model STD4000D000 was selected because its units seemed to have a fairly consistent performance profile.

In order to determine how to predict the lifespans with the SMART health monitoring attributes, at first a regression analysis was performed. The remaining useful days was calculated for each observation by subtracting the observation date from the failure date. This was then used as a target while the monitored attributes were used as features. The accuracy of this model was very low.

Next the observed lifespans for each unit were grouped into 12 sets. These were fed into a classifier model as targets, with monitored features as inputs. This time, the accuracy (0.81) was much higher. 

Thus we can say that for all the group, the algorithm predicts with a greater than 60% success rate, whether it will suffer very early death or operate closer to the expected lifespan of >40000 hours.
