# Election_Analysis

### **Overview** ###
By the request of Colorado Board of Elections an audit for the congressional election of Arapahoe, Denver and Jefferson counties was performed. The audit was performed on the votes collected by the Board of Elections on and before election date and gathered by manual counting, scanner reading and electronic voting machines. The data contained 3 types of information; the unique Ballot ID assigned to every counted vote, the County in which the vote was recorded and the candidate who received credit for the vote. The goal of the inspection was to tabulate the winner candidate of the election by popular vote along with examination on voter turnout by county. 

### **Audit methodology** ###
The data was provided by the Board of Elections. The analysis was performed using the software’s Python 3.6.1 and PyCharm. First the total number of votes was calculated from the data set and all candidates that received votes were identified. Every vote was linked to the respective candidate and the percentage of votes each candidate received was calculated. The winner of the election by popular vote was identified and the analysis result was returned to the Colorado Board of Elections. 
From the raw data, we performed the following analysis. A. Calculated the total numbers of votes B. Identified all the candidates that received votes C. Tallied the total number of votes every candidate received D. Calculated the percentage of votes every candidate received. E. After analyzing the data, the winner of the election by popular vote was identified.

### **Election and Audit Results** ###
*	Total Number of Votes 	 	**	369,711**    **Percentage**
  *	Denver				306,055	    82.8%
  *	Jefferson 		  	  38,855		    10.5%
  *	Arapahoe 		  	  24,801		      6.7%


•	County with highest participation was **Denver**

![Vote Distribution by County](https://user-images.githubusercontent.com/85839235/125385532-ae947180-e368-11eb-8493-faf366717325.png)


•	Votes by Congressional Candidate		       **Percentage**
o	Diana DeGette	 	             272,892		73.8%
o	Charles Casper Stockham 	 85,213		23.0%
o	Raymon Anthony Doane 	 11,606		  3.1%

•	The Winner of the popular vote for the Congressional election was **Diana DeGette** who received **272,892 total votes** from all counties and had **73.8% of the total votes**. 

![Election Results Chart](https://user-images.githubusercontent.com/85839235/125385563-bf44e780-e368-11eb-8bb7-ddeb4c60144b.png)

### **Election and Audit Results** ###
   #### Scalability Possibilities ####
The audit of the election was performed by creating a code with the programming language, Python, that will extract the requested information from the voting data and presents it in an easy-to-understand format. There are multiple benefits of using a robust machine analysis but primarily, it provides an accurate and fast assessment of data that could prevent human counting errors or influence. 
The parameters that were designed in this code can be modified in order to be used in analysis for other elections. The code is scalable and can process larger amounts of data while maintaining its integrity. It can also be adjusted to process other variables of data, from multiple public officials positions in the same election to breaking down vote’s categories by city. To expand in the scalability options, a timer was inserted in the code 1️⃣ in order to calculate the amount of time it took to process the data. The current analysis parameters were produced in 0.017 seconds. This also presents the prospect to provide frequent election status updates to the public shortly after the data is received.

![Run Time timer](https://user-images.githubusercontent.com/85839235/125385668-ee5b5900-e368-11eb-81e2-536541164090.png)

   #### Multiple Variable Processing ####
If necessary and desired, the code can also provide other insights from the data set received. By example, with the current data we could identify how many votes every candidate received by county. In addition, if information regarding the number of registered voters by county is received, we could modify the code in order to provide understanding regarding voter participation.  Such analysis could provide awareness regarding the voting process by area and be the first path to identifying if there is any unbalanced voting dynamic between counties. 
Furthermore, if candidates were aligned with a specific political party, it would be possible to calculate the results with political party affiliation filters. Depending on local and State election laws, that analysis may be necessary in order to assist in post-election decisions. 

#### ****References and Links**** ####
1️⃣ https://docs.python.org/3/library/profile.html#module-cProfile

Code used for timer

![Code for timer](https://user-images.githubusercontent.com/85839235/125385878-5873fe00-e369-11eb-8cf3-329dd14fbb3d.png)

