<b> Understanding the issue: </b>
1. What is the main motivation of this project? The goal is to predict the number of applications for admission to American colleges based on 777 observations of 17 independent random variables. The purpose of the problem is to fit an optimal model to the data to better predict the variable named “Apps”.

2. What can the output of such a project be used for? Predicting the variable of the number of applications for admission to universities can be used in future educational planning and a better understanding of the variables affecting the number of applications of applicants, for example:

	- What variables have the greatest impact on the number of applications and examine the possibility of strengthening them in future educational planning.

	- What variables have the least impact on the number of applications for admission to universities.

	- What variables are not effective or, in other words, independent of “Apps” and examine the possibility of omitting them.

3. Who might be interested in the results of this project?

	- Educational regulatory organization such as the Ministry of Science,
	- Universities and educational centers,
	- Research organizations in the field of education.
	
<b> Understanding data:</b>
1. Where did the data come from and how was it collected? This dataset was taken from the StatLib library which is maintained at Carnegie Mellon University. The dataset was used in the ASA Statistical Graphics Section’s 1995 Data Analysis Exposition.

2. What do each of the variables measure?
	- Private: A factor with levels No and Yes indicating private or public university
	- Apps: Number of applications received
	- Accept: Number of applications accepted
	- Enroll: Number of new students enrolled
	- Top10perc: Pct. new students from top 10% of H.S. class
	- Top25perc: Pct. new students from top 25% of H.S. class
	- F.Undergrad: Number of fulltime undergraduates
	- P.Undergrad: Number of parttime undergraduates
	- Outstate: Out-of-state tuition
	- Room.Board: Room and board costs
	- Books: Estimated book costs
	- Personal: Estimated personal spending
	- PhD:Pct. of faculty with Ph.D.’s
	- Terminal: Pct. of faculty with terminal degree
	- S.F.Ratio:Student/faculty ratio
	- perc.alumni:Pct. alumni who donate
	- Expend:Instructional expenditure per student
	- Greatad.Rate:Graduation rate
	
3. Is there any ambiguity in the definitions of the data? Yes, there is some ambiguity in the definition or calculation of some variables such as the perc. alumni, Grad.Rate, Student-to-Faculty Ratio, and S.F.Ratio.

4. Is there an error in measuring variables or recording data? Yes, for various reasons such as:

	- Lack of equal definitions or different interpretations of a definition by different people who are responsible for collecting data in different universities.
	- Error in data entry by the operator.
5. What other variables, if any, could help solve the problem? Independent variables such as:

	- Number of courses available in the university
	- The number of outstanding professors in each field based on the number of articles cited in reliable scientific journals.
	- International University Rank
6. What are the existing variables (categorical-numerical)? Except for one variable named ”private”, which is a binary variable (discrete categorical variable), other variables are numerical.
