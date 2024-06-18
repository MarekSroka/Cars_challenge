

**Analytics and visalization of claims process**

**PROCESS DESCRIPTION:**

	• **Excel** initial analysis of data
	• In a normal process, it would be necessary to clarify the **duplicates** with the business unit (different customer id's for the same cars and different claim results), but at this point, due to their       relatively   small level (1862 duplicates up to 70k rows) and very limited time, they were all removed from further analysis.
  • Tables merged in Power Query  
	• Loading data do Python jupyter notebook
	• Preprocessing data (descrpition of process in the jupyter file)
	• After that process Data were consist 14 variables (incl. Target column)
	• The plan was to visualize data in the sweetviz library (or second choice - ydata-profiling)  to get the visualization  and based on this - to draw conclusions and make recommendations for further action. 
	
 This last point in the process was unfortunately not completed (**Errors regarding the correct implementation of these libraries**).
	

