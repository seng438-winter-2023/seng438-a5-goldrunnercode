**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       |   |
|-----------------|---|
| Student Names:  |   |
|                 |   |
|                 |   |
|                 |   |

# Introduction
We understand that reliability growth testing is important to track throughout a programs lifetime the reliability of the program so that you can determine when it meets the customers needs. It helps developers identify the root causes of failure in a system and by identifying these failures it can help them increase reliability. As Software Engineers we have to be thinking about the costs of unreliable software and we need to strive towards building software people can trust. 

We also understand that a reliability demonstration chart is a useful tool to figure out when your product is in an acceptable range for both the customers wanted risk and the devolopers wanted risk.
# 

# Assessment Using Reliability Growth Testing 
We were able to get Failure Data Set 2 working for the STRTAT program, unfortunately we found that most of the test datasets with the .DAT file type were unable to run so we did not use any of those. Because the dataset was so small to get explainable results from the data we decided that all of the data would be used, but by plugging in the data from the word document given in Falure Data Set 2 we were able to run the geometric and Little Wood and Varal's Bayesian Reliability models. You can see from the photos provided of running our tests we found that slowly the reliability of Failure Data Set two is growing, from these graphs it shows that over time the MTTF is increasing which shows signs that the reliability of the system is growing, it is not conclusive whether the system is actually reliable yet as we do not know the specifications of the system but we can conclude from both of these models that the MTTF is getting larger and thus our failure rate is decreasing so our reliability must be increasing. 

The advantages we found of Reliability growth testing is that it can help you track the progress of a SUT's reliability throughout the development of the system so that you can identify key failure points in the system whilst you are developing and testing it this leads to developers being able to fix failures more quickly and provide better customer satisfaction.

The disadvantages we found of reliability growth testing is that the data can be inconclusive depending on the SUT as if you do not have constant testing of your system to get a reliable dataset then reliability growth testing can give false results in regards to your actual reliability. Furthermore if the datasets that you are given are corrupted or unusable then you may have to figure out a tedious workaround to actually be able to access the data properly and even then your report might be inconclusive from the failure of a dataset. 
# Assessment Using Reliability Demonstration Chart 
We imported failure set 8 with A = -2.197 and B = 2.197. We chose failure set 8 as the number of failures was small and we had to input them all manually. After entering the cumulative failure count and the time at which the failur occured, the RDC chart was created. By changing the acceptable number of failures per inputs (or per amount of time) we can see changes in the points in the RDC. As we approach our final failure data point (16 failures in 80 hours), the end of the data also approaches the acceptable region of the RDC. With a mean time to failure of 5 hours, this puts our tests in the acceptable range. The image MTTF shows the RDC for 1 failure per 5 hours, while 2 failures per 5 hours is MTTF x 2, and 1 failure per 10 hours is MTTF div 2.

An advantage of an RDC graph was the ease of use. We found it very easy to mess around with parameters and get immediate results that we could quickly look at and understand.

This also could prove to be a disadvantage though, as we can't calculate specifics such as reliability and instead we only get a general overview of if our tests are accepted or not.
# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed
We split into groups of 2 and worked on parts 1 and 2 simultaneously, and then compared our results as well as the advantages and disadvantages we faced using our respective methods. 
# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
