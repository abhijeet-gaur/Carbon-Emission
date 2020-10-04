README
Carbon Emission (mili-metric tons) from 1751-2010
This story is about the carbon emission from fossils stating the data from 1751 to 2010. Showing the growth of the C in atmosphere with a change of 3054.66%
The data source is https://datahub.io/core/co2-fossil-global.
The task is pretty simple. The data is available year wise from 1751-2010.
Copy the data to the excel sheet
To see the percentage each fossil holds:
=SUM(B2:B261) to get the total fossil emission
Similarly =SUM(M2:M261), where M can be (C,D,E,F) to check the total emission by gas fuel,liquid fuel,solid fuel,cement and flare gas respectevily.
To see the percentage change for each use:
=((old-new)/old)*100 
eg: =((B2-B261)/B261)
To calculate the average of the same and see the average polution in the years:
=AVERAGE(B2:B261)
To calculate the percentage of each fuel emitting the amount of carbon:
=(SUM(C2:C261)/SUM(B2:B61))*100

Run the above functions to get the desired result. The result can be further be sorted into in which the Carbon emission was maximum.
Read the full story here at:https://medium.com/@abhijeetgaur8/increasing-fossil-carbon-emission-takes-us-back-to-1751-2eb41c12d16c
