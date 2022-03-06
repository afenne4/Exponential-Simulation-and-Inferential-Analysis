# Exponential-Simulation-and-Inferential-Analysis

There are two files in this repository, "Exponential-Simulation-script.pdf" and "Inferential-Analysis-of-Tooth-Growth.pdf". 
The first is primarily concerned with conducting a monte carlo simulation of the exponential distribution to examine how summary statistics 
are distributed. It was discovered that mean values were normally distributed, but variance was skewed. Further analysis demonstrates that 
with larger sample sizes the distribution of variances approaches a normal distribution.

In the second file, "Inferential-Analysis-of-Tooth-Growth.pdf", data from the ToothGrowth dataset in R was analyzed. The data comes from the 
following study Crampton, E. W. (1947). The growth of the odontoblast of the incisor teeth as a criterion of vitamin C intake of the guinea pig. The Journal of Nutrition, 33(5), 491–504. doi: 10.1093/jn/33.5.491.
The goal of this study was to measure the effect of Vitamin C dosage level and delivery method on odontoblast (tooth) growth in guinea pigs. 10 
guinea pigs were assigned to each manipulation level resulting in a total of 60 observations. 
There are 3 variables of interest in this data set:

    -Tooth (Odontoblast) length measured in cm 
    -Supplement type ascerbic acid (VC) or orange juice (OJ)  
    -Dose in milligrams/day (0.5, 1.0, 2.0)

A preliminary exploratory data analysis and data visualization was first conducted in order to determine any patterns in the data. Based on this,
a t-test was used to determine if delivery method of Vitamin C had an impact on tooth growth. This analysis showed that orange juice resulted in more
tooth growth than ascerbic acid. Following this, two t-tests were used to determine if increasing doseage resulted in increased tooth growth. The 
results from these tests provided evidence in support of this hypothesis.
