# Global Aid Investment Evaluator: Data-Driven Funding Strategy
Group Project - Kartik , Neel   

#Problem Statement-

Categorize the countries using some socio-economic and health factors
that determine the overall development of the country, to finally suggest the countries which the CEO
needs to focus on the most. HELP International is an international humanitarian NGO that is
committed to fighting poverty and providing the people of backward countries with basic amenities
and relief during the time of disasters and natural calamities. HELP International has been able to
raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money
strategically and effectively.


#Solution - 


The CEO has to make a decision to choose the countries that are in
the direst need of aid. In order to achieve this, we use multiple methods for clustering the data into
the categories such as ‘Help needed’, ‘Might need help’ and ‘No help needed’.

#CONCLUSION


1)We discarded the DBSCAN method, because it is not showing good results.
2)Rest of the models are giving appropriate results that support each other.
3)As it is difficult to discard other clustering methods ,We will use all other methods and maintain the frequency of occurrence of each country in the ‘Needy country’ cluster using Dictionary.
4)To remove anomalies in the model results, we are using a method similar to voting.
5)We will use a threshold to remove the countries due to the anomalies in the model and place the countries in a sequence so that we know how to distribute our money.

According to their decreasing order of frequency, the CEOs of NGO can invest money in the corresponding countries. 



![image](https://github.com/KSN7630/Unsupervised-Learning-on-Country-Data-using-Machine-Learning/assets/120741965/f4caeef3-6027-469e-ae8f-b433000ccdef)



