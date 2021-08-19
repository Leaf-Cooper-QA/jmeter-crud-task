# Jmeter task Read Me
## features
This application tests carries out load, spike, stress and soak tests for the TDL application previously created
JSON assertions are made throughout the CRUD tests to ensure the returned values are accurate, and will error if this is not the case
The CRUD elements are collected into a transcation controller for extra readability
The total throughput for the testing was approx. 240 transactions/s and each individual feature was approximately 60 transactions/s
Achieving an acceptable throughput was part of a compromise with avoiding clientside errors, specifically including timers would reduce errors but also throughput
With more time, more altering of the parameters would be useful to achieve a better compromise
However, this is the highest current throughput found to produce no errors, and thus the throughput that the application is able to handle