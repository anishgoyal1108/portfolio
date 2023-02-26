# Data collection

Class: [[Advanced High School Statistics]]
Subject: #math 
Date: February 20, 2023
Teacher: [[Open Intro]]

## 1.1 Case study: using stents to prevent strokes
Topics: #statistical-significance  #statistical-investigation 

### 1.1.1 Case study
- The steps of a statistical investigation are as follows:
	1. Identify a question or problem
	2. Collect relevant data on the topic
	3. Analyze the data
	4. Form a conclusion
- Observations collected from the likes of field notes, surveys, and experiments are called [[data]].
- We consider an experiment studying the effectiveness of stents against patients at risk of stroke.
- Each volunteer patient was put into two groups: the [[treatment group]] and [[control group]].
- The [[control group]] provides a reference point against which we can measure the impact of stents in the treatment group.
- Researchers studied the effect of stents at two time periods: 30 days after and 365 days after:
![[Figure 1.1.png]]
- Performing a statistical data analysis allows us to consider all of the data simultaneously. The following table takes the total frequency of stroke and no stroke patients for each time period for each group:
![[Figure 1.2.png]]

#### Guided Practice 1.1
What proportion of the patients in the treatment group had no stroke within the first 30 days of the study?
- $\large \frac{191}{224} = 0.85$

- We can compute [[summary statistic]]s from the table; the results of the study after one year could be described by two summary statistics: the proportion of individuals with strokes in the treatment and control groups.
	- Proportion of treatment group with strokes: $\large \frac{45}{224}=0.2=20$%.
	- Proportion of control group with strokes: $\large \frac{28}{227}=0.12=12$%.
	- An additional 8% of patients in the control group had a stroke!
- The findings of these two summary statistics are important because:
	1. It is contrary to what doctors expected.
	2. It leads to a statistical question: does the data show a "real" difference between the groups?
		- This is basically asking whether the difference between the groups is due to chance or if it's [[statistically significant]].
- We can conclude that there is compelling evidence of harm by stents in the study of stroke patients; however, these findings cannot be generalized to all patients and all stents because the study looked at patients with very specific characteristics and there are many types of stents that exist.

### Section Summary
- To test the effectiveness of a treatment, researchers often carry out an experiment in which they randomly assign patients to a [[treatment group]] or a [[control group]].
- Researchers compare the relevant [[summary statistic]]s to get a sense of whether the treatment group did better, on average, than the control group.
- Ultimately, researchers want to know whether the difference between the two groups is [[statistically significant]], that is, larger than what would be expected by chance alone.

### Exercises
#### Migraine and acupuncture, Part I
A migraine is a particularly painful type of headache, which patients sometimes wish to treat with acupuncture. To determine whether acupuncture relieves migraine pain, researchers conducted a randomized controlled study where 89 females diagnosed with migraine headaches were randomly assigned to one of two groups: treatment or control. 43 patients in the treatment group received acupuncture that is specifically designed to treat migraines. 46 patients in the control group received placebo acupuncture (needle insertion at non-acupoint locations). 24 hours after patients received acupuncture, they were asked if they were pain free. Results are summarized in the contingency table below.
![[migraine-and-acupuncture.png]]
(a) What percent of patients in the treatment group were pain free 24 hours after receiving acupuncture?
- $\large \frac{10}{43} = 0.23 = 23$%
(b) What percent were pain free in the control group?
- $\large \frac{2}{46} = 0.04 = 4$%
(c) In which group did a higher percent of patients become pain free 24 hours after receiving acupuncture?
- The treatment group
(d) Your findings so far might suggest that acupuncture is an effective treatment for migraines for all people who suffer from migraines. However, this is not the only possible conclusion that can be drawn based on your findings so far. What is one other possible explanation for the observed difference between the percentages of patients that are pain free 24 hours after receiving acupunture in the two groups?
- The patients might have been told the specific type of acupunture they were receiving, which may have conditioned their response 24 hours after the process was complete.

#### Sinusitis and antibiotics, Part I
Researchers studying the effect of antibiotic treatment for acute sinusitis compared to symptomatic treatments randomly assigned 166 adults diagnosed with acute sinusitis to one of two groups: treatment or control. Study participants received either a 10-day course of amoxicillin (an antibiotic) or a placebo similar in appearance and taste. The placebo consisted of symptomatic treatments such as acetaminophen, nasal decongestants, etc. At the end of the 10-day period, patients were asked if they experienced improvement in symptoms. The distribution of responses is summarized below.
![[sinusitis-and-antibiotics.png]]
(a) What percent of patients in the treatment group experienced improvement in symptoms?
- $\large \frac{66}{85} = 0.77 = 77$%
(b) What percent experienced improvement in symptoms in the control group?
- $\large \frac{65}{81} = 0.80 = 80$%
(c) In which group did a higher percentage of patients experience improvement in symptoms?
- The control group.
(d) Your findings so far might suggest that a real difference in effectiveness of antibiotic and placebo treatments for improving symptoms of sinusitis exists. However this is not the only possible conclusion that can be drawn based on your findings so far. What is one other possible explanation for the observed difference between the percentages of patients that reported improvement in symptoms at the end of the 10-day period in the two groups?
- The percentage of patients that experienced improvement among both groups is almost the same. The number of patients in the control group is less than that of the treatment group, so the data was skewed towards the control group ever so slightly.

## 1.2 Data Basics
Topics: #variables #individuals #categorical #numerical #discrete #continuous #nominal #ordinal #association #independence

### 1.2.1 Observations, variables, and data matrices
The following table displays the first three and last rows of a data set for 50 randomly sampled loans offered through Lending Club, which is a peer-to-peer lending company. These observations will be referred to as the `loan50` data set.
![[Figure 1.3.png]]
![[Figure 1.4.png]]

#### Guided Practice 1.2
What is the grade of the first loan? And what is the home ownership status of the borrower for that loan?
- The grade of the first loan is "A". 
- The home ownership status of the borrower for that loan is rent.

- The formal name for a row is a [[case]] or [[observational unit]]. The columns represent characteristics, called [[variable]]s, for each of the loans.
- The data in Figure 1.3 represent a [[data matrix]]. Each row corresponds to a unique [[case]], and each column corresponds to a [[variable]]. 
- Use a [[data matrix]] when recording data unless you have a very good reason to use another structure. It allows new [[case]]s to be added as rows or new [[variable]]s as columns.

#### Guided Practice 1.3
The grades for assignments, quizzes, and exams in a course are often recorded in a gradebook that takes the form of a data matrix. How might you organize grade data using a data matrix?
- I would organize grade data by student name/student ID as the [[case]]s, and subject, teacher, assignment, weighting, and grade value as my [[variable]]s.

#### Guided Practice 1.4
We consider data for 3,142 counties in the United States, which includes each county’s name, the state in which it is located, its population in 2017, how its population changed from 2010 to 2017, poverty rate, and six additional characteristics. How might these data be organized in a data matrix?
- I would organize this as a data matrix by using the county's name as the [[case]], and its state, 2017 population, population change from 2010, poverty rate, and six additional characteristics as my variables.
![[Figure 1.5.png]]
![[Figure 1.6.png]]
### 1.2.2 Types of variables
- Examine the variables in the `county` data set:
		- `unemp_rate` is said to be a [[numerical]] variable, and it is sensible to add, subtract, or take averages with those values.
		- `pop` is also numerical, but can only take positive integers. For this reason `pop` is [[discrete]] while ``unemp_rate`` is [[continuous]].
		- `state` is [[categorical]] because it contains responses that are categories, and the possible values of a categorical [[variable]] is called its [[levels]].
		- `median_edu`, which describes the median education of a county, takes values ``below_hs``, ``hs_diploma``, ``some_college``, or ``bachelors`` per county. This variable is a hybrid: although the values themselves are [[categorical]], the levels have a natural ordering. A [[variable]] with these properties is called an [[ordinal]] variable, while a regular categorical variable without ordering is called a [[nominal]] variable.
![[Figure 1.7.png]]

#### Example 1.5
Data were collected about students in a statistics course. Three variables were recorded for each student: number of siblings, student height, and whether the student had previously taken a statistics course. Classify each of the variables as [[continuous]] numerical, [[discrete]] numerical, or [[categorical]].
- Number of siblings: discrete numerical
- Student height: continuous numerical
- Whether the student had previously taken a statistics course: categorical

#### Guided Practice 1.6
An experiment is evaluating the effectiveness of a new drug in treating migraines. A `group` variable is used to indicate the experiment group for each patient: treatment or control. The `num_migraines` variable represents the number of migraines the patient experienced during a 3-month period. Classify each variable as either [[numerical]] or [[categorical]].
- `group`:  categorical
- `num_migraines`: numerical (more specifically, [[discrete]] numerical)

### 1.2.3 Relationships between variables
- Many analyses are motivated by a researcher looking for a relationship between two or more variables. 
- To answer statistical questions, data must be collected. Examining summary statistics could provide insight for each of the statistical questions drawn. 
- Scatterplots are a type of graph used to study the relationship between two [[numerical]] variables.
- [[Figure 1.8.png|Figure 1.8]] compares ``homeownership`` and ``multi_unit``, which is the percent of units in multi-unit structures.
	- Each point on the plot represents a county
	- The scatterplot suggests that counties with a higher rate of multi-units tend to have lower home ownership rates.
- When two variables show some connection with each other, they are called [[associated]] variables. Associated variables can also be called [[dependent]] variables.
![[Figure 1.8.png]]

#### Guided Practice 1.7
Examine the variables in the `loan50` data set, which are described in [[Figure 1.4.png|Figure 1.4]]. Create two questions about possible relationships between variables in `loan50` that are of interest to you.
- Is there a relationship between a person's total income and home ownership status?
- Is there a relationship between the loan amount and the percent interest rate on that loan?

#### Example 1.8
This example examines the relationship between a county’s population change from 2010 to 2017 and median household income, which is visualized as a scatterplot in [[Figure 1.9.png|Figure 1.9]]. Are these variables associated?
![[Figure 1.9.png]]
- Yes; the larger the median household income, the larger the county's population growth is.

- Because there is a downward trend in [[Figure 1.8.png|Figure 1.8]], these variables are [[negative association|negatively associated]].
- A [[positive association]] is shown in the relationship between `median_hh_income` and `pop_change` in [[Figure 1.9.png|Figure 1.9]].
- If two variables are not associated, then they are [[independent]]. 
- A pair of variables can either be [[associated]] or [[independent]]. They *cannot* be both.

### Section summary
- Researchers often summarize data in a table, where the rows correspond to individuals or [[case|cases]] and the columns correspond to [[variable|variables]], the values of which are recorded for each individual.
- Variables can be [[numerical]] or [[categorical]]. Numerical variables can be [[continuous]] or [[discrete]] while categorical variables can be [[ordinal]] or [[nominal]].
- When there exists a relationship between two variables, the variables are said to be [[associated]] or [[dependent]]. If the variables are not associated, they are said to be [[independent]].

### Exercises
#### 1.3 Air pollution and birth outcomes, study components
Researchers collected data to examine the relationship between air pollutants and preterm births in Southern California. During the study air pollution levels were measured by air quality monitoring stations. Specifically, levels of carbon monoxide were recorded in parts per million, nitrogen dioxide and ozone in parts per hundred million, and coarse particulate matter ($\text{PM}_{10}$) in $µ\text{g/m}^3$ . Length of gestation data were collected on 143,196 births between the years 1989 and 1993, and air pollution exposure during gestation was calculated for each birth. The analysis suggested that increased ambient $\text{PM}_{10}$ and, to a lesser degree, CO concentrations may be associated with the occurrence of preterm births.
(a) Identify the main research question of the study. 
- Does there exist a relationship between air pollutants and preterm births?
(b) Who are the subjects in this study, and how many are included? 
- 143,196 births in Southern California between 1989 and 1993.
(c) What are the variables in the study? Identify each variable as numerical or categorical. If numerical, state whether the variable is discrete or continuous. If categorical, state whether the variable is ordinal.
- Length of gestation: Continuous numerical
- Air exposure during gestation: Continuous numerical

#### Buteyko method, study components
The Buteyko method is a shallow breathing technique developed by Konstantin Buteyko, a Russian doctor, in 1952. Anecdotal evidence suggests that the Buteyko method can reduce asthma symptoms and improve quality of life. In a scientific study to determine the effectiveness of this method, researchers recruited 600 asthma patients aged 18-69 who relied on medication for asthma treatment. These patients were randomly split into two research groups: one practiced the Buteyko method and the other did not. Patients were scored on quality of life, activity, asthma symptoms, and medication reduction on a scale from 0 to 10. On average, the participants in the Buteyko group experienced a significant reduction in asthma symptoms and an improvement in quality of life.
(a) Identify the main research question of the study.
- Does the Buteyko method reduce asthma symptoms and improve quality of life?
(b) Who are the subjects in this study, and how many are included? 
- 600 asthma patients aged 18-69 who relied on medication for asthma treatment
(c) What are the variables in the study? Identify each variable as numerical or categorical. If numerical, state whether the variable is discrete or continuous. If categorical, state whether the variable is ordinal.
- Quality of life: Descrete numerical
- Activity: Descrete numerical
- Asthma symptoms: Descrete numerical
- Medication reduction: Descrete numerical

#### Cheaters, study components
Researchers studying the relationship between honesty, age, and self-control conducted an experiment on 160 children between the ages of 5 and 15. Participants reported their age, sex, and whether they were an only child or not. The researchers asked each child to toss a fair coin in private and to record the outcome (white or black) on a paper sheet, and said they would only reward children who report white.
(a) Identify the main research question of the study.
- Does telling children not to cheat affect their likelihood to cheat?
(b) Who are the subjects in this study, and how many are included?
- 160 children between the ages of 5 and 15.
(c) The study’s findings can be summarized as follows: ”Half the students were explicitly told not to cheat and the others were not given any explicit instructions. In the no instruction group probability of cheating was found to be uniform across groups based on child’s characteristics. In the group that was explicitly told to not cheat, girls were less likely to cheat, and while rate of cheating didn’t vary by age for boys, it decreased with age for girls.” How many variables were recorded for each subject in the study in order to conclude these findings? State the variables and their types.
- Age: Continuous numerical
- Sex: Categorical
- Only child: Categorical 
- Did they cheat: Categorical

#### 1.6 Stealers, study components.
In a study of the relationship between socio-economic class and unethical behavior, 129 University of California undergraduates at Berkeley were asked to identify themselves as having low or high social-class by comparing themselves to others with the most (least) money, most (least) education, and most (least) respected jobs. They were also presented with a jar of individually wrapped candies and informed that the candies were for children in a nearby laboratory, but that they could take some if they wanted. After completing some unrelated tasks, participants reported the number of candies they had taken.
(a) Identify the main research question of the study. 
- Is there a relationship between socio-economic class and unethical behavior?
(b) Who are the subjects in this study, and how many are included? 
- 120 UC Berkeley undergraduates
(c) The study found that students who were identified as upper-class took more candy than others. How many variables were recorded for each subject in the study in order to conclude these findings? State the variables and their types.
- Socio-economic class distinction: Ordinal categorical
- How many candies they took: Discrete numerical

#### 1.7 Migraine and acupuncture, Part II.
[[Data collection#Exercises#Migraine and acupuncture, Part I|Exercise 1.1]] introduced a study exploring whether acupuncture had any effect on migraines. Researchers conducted a randomized controlled study where patients were randomly assigned to one of two groups: treatment or control. The patients in the treatment group received acupuncture that was specifically designed to treat migraines. The patients in the control group received placebo acupuncture (needle insertion at non-acupoint locations). 24 hours after patients received acupuncture, they were asked if they were pain free. What are the [[explanatory variable|explanatory]] and [[response variable|response variables]] in this study?
- Explanatory variable: acupunture or not
- Response variable: pain free or not

#### 1.8 Sinusitis and antibiotics, Part II.
[[Data collection#Exercises#Sinusitis and antibiotics, Part I|Exercise 1.2]] introduced a study exploring the effect of antibiotic treatment for acute sinusitis. Study participants either received either a 10-day course of an antibiotic (treatment) or a placebo similar in appearance and taste (control). At the end of the 10-day period, patients were asked if they experienced improvement in symptoms. What are the [[explanatory variable|explanatory]] and [[response variable|response variables]] in this study?
- Explanatory variable: antibiotic treatment or not
- Response variable: symptom improvement or not

#### 1.9 Fisher's irises
Sir Ronald Aylmer Fisher was an English statistician, evolutionary biologist, and geneticist who worked on a data set that contained sepal length and width, and petal length and width from three species of iris flowers (setosa, versicolor and virginica). There were 50 flowers from each species in the data set.
(a) How many cases were included in the data?
- $50 \cdot 3 = 150$ cases
(b) How many [[numerical]] variables are included in the data? Indicate what they are, and if they are [[continuous]] or [[discrete]].
- There are four numerical variables: sepal length and width and petal length and width which are all continuous numerical variables.
(c) How many categorical variables are included in the data, and what are they? List the corresponding [[levels]] (categories).
- There is only one categorical variable in the data and that is the iris flower species.
- The corresponding levels are: setosa, versicolor, and virginica.

#### 1.10 Smoking habits of UK residents
A survey was conducted to study the smoking habits of UK residents. Below is a data matrix displaying a portion of the data collected in this survey. Note that “£” stands for British Pounds Sterling, “cig” stands for cigarettes, and “N/A” refers to a missing component of the data.
![[smoking-habits.png]]
(a) What does each row of the data matrix represent?
- Each row of the data matrix represents a [[case]] of the data set, where each case is data collected on one UK resident.
(b) How many participants were included in the survey?
- 1691 UK residents
(c) Indicate whether each variable in the study is [[numerical]] or [[categorical]]. If numerical, identify as [[continuous]] or [[discrete]]. If categorical, indicate if the variable is [[ordinal]].
- `sex`: nominal categorical
- `age`: continuous numerical
- `marital`: nominal ordinal
- `grossIncome`: ordinal categorical
- `smoke`: nominal categorical
- `amtWeekends`: discrete numerical
- `amtWeekdays`: discrete numerical

#### 1.11 US Airports
The visualization below shows the geographical distribution of airports in the contiguous United States and Washington, DC. This visualization was constructed based on a dataset where each observation is an airport.
![[US-airports.png]]
(a) List the variables used in creating this visualization. 
- Privately owned?
- Publicly available?
- Longitude
- Latitude
(b) Indicate whether each variable in the study is [[numerical]] or [[categorical]]. If numerical, identify as [[continuous]] or [[discrete]]. If categorical, indicate if the variable is [[ordinal]].
- Privately owned: nominal categorical
- Publicly available: nominal categorical
- Longitude: continuous numerical
- Latitude: continuous numerical

#### 1.12 UN Votes
The visualization below shows voting patterns the United States, Canada, and Mexico in the United Nations General Assembly on a variety of issues. Specifically, for a given year between 1946 and 2015, it displays the percentage of roll calls in which the country voted yes for each issue. This visualization was constructed based on a dataset where each observation is a country/year pair.
![[UN-votes.png]]
(a) List the variables used in creating this visualization.
- % Yes
- Country
- Year
(b) Indicate whether each variable in the study is numerical or categorical. If numerical, identify as continuous or discrete. If categorical, indicate if the variable is ordinal.
-  % Yes: continuous numerical
- Country: nomincal categorical
- Year: discrete numerical

## 1.3 Overview of data collection principles
Topics: #population #sample #parameter #statistic #summarize #mean #proportion #anecdotal #census #sample-survey #experiment #observation-study #observational #experimental #causal-relationship #generalization

### 1.3.1 Populations and samples
Consider the following three research questions:
1. What is the average mercury content in swordfish in the Atlantic Ocean?
2. Over the last 5 years, what is the average time to complete a degree for Duke undergrads?
3. Does a new drug reduce the number of deaths in patients with severe heart disease?

- Every research question refers to a target [[population]].
	- Often times it is too difficult/expensive to collect data for every [[case]] in a population, so we take a [[sample]] instead.

#### Guided Practice 1.9
For the second and third questions above, identify the target population and what represents an individual case.
- Second question:
		- The target population is Duke graduates in the past five years. 
		- An individual case would be one such student.
- Third question:
		- The target population is patients with severe heart disease.
		- An indvidual case would be one such patient.

- We can also collect the mean, median, proportion, or some other summary of a population called [[parameters]].
		- The value of a parameter can be estimated by taking a sample and computing a numerical summary called a [[statistic]] based on that sample.
	- Notice that the two p's (population and parameter) go together and the two s's (sample and statistic) go together.

#### Example 1.10
Earlier we asked the question: what is the average mercury content in swordfish in the Atlantic Ocean? Identify the variable to be measured and the parameter and statistic of interest.
- Variable to be measured: Mercury content in each swordfish in the Atlantic Ocean
- Parameter of interest: *Average* mercury content of all swordfish in the Atlantic Ocean
- Statistic of interest: *Average* mercury content in swordfish among a sample of x swordfish

- The [[mean]] is labeled $\mu$ in the context of a population and $\bar{x}$ in the context of a sample.
	- We use $\bar{x}$ to estimate the population mean, $\mu$.
- The [[proportion]] is labeled $p$ in the context of a population and $\hat{p}$ in the context of a sample.
	- We use $\hat{p}$ to estimate the population proportion, $p$.

#### Example 1.11 
Is $\mu$ a parameter or a statistic? What about $\hat{p}$?
- $\mu$ is a parameter because it's an average of the entire population. $\hat{p}$ is a statistic because it is calculated from a sample of the entire population.

#### Example 1.12
For the second question regarding time to complete a degree for a Duke undergraduate, is the variable numerical or categorical? What is the parameter of interest?
- The variable "time to complete a degree for a Duke undergraduate" is a numerical variable.
- The parameter of interest is the *average*, or mean, time to complete a degree for all Duke undergraduates.

#### Guided Practice 1.13
The third question asked whether a new drug reduces deaths in patients with severe heart disease. Is the variable numerical or categorical? Describe the statistic that should be calculated in this study.
- The variable "whether a new drug reduced deaths in patients with severe heart disease" is categorical. 
- The statistic that should be calculated in this study is the sample proportion, $\hat{p}$, of patients with severe heart disease that died while taking the drug.

![[Figure 1.10.png]]

### 1.3.2 Anecdotal evidence
Consider the following possible responses to the three research questions:
1. A man on the news got mercury poisoning from eating swordsh, so the average mercury concentration in swordsh must be dangerously high.
2. I met two students who took more than 7 years to graduate from Duke, so it must take longer to graduate at Duke than at many other colleges.
3. My friend's dad had a heart attack and died after they gave him a new heart disease drug, so the drug must not work.

- There are two problems with these responses:
	1. The data only represents one or two cases.
	2. It is unclear whether these cases are representative of the entire population.
- Data that is collected in this haphazard fashion is called [[anecdotal evidence]].
- [[anecdotal evidence|Anecdotal evidence]] may be true and verifiable, but it may only represent extraordinary cases.
	- Instead of focusing on the most unusual cases, we should examine a representative sample of many cases.

### 1.3.3 Explanatory and response variables
Consider the following rephrasing of an earlier question about the `county` data set:
*If there is an increase in the median household income in a county, does this drive an
increase in its population?*
- When we ask whether one variable affects another, we are asking whether an [[explanatory variable]] affects a [[response variable]].
- In this scenario, median household income is the [[explanatory variable]] and population change is the [[response variable]].

#### Association does not apply causation
- Labeling two variables as [[explanatory variable|explanatory]] and [[response variable|response]] does not guarantee a causal relationship between them, even if there is an [[associated||associativity]] between the two.
- We only keep track of the [[explanatory variable|explanatory]] and [[response variable|response]] variables to keep track of which variables we *suspect* affect each other.
- In many cases, the causal relationship is unknown or complex. Despite the [[associated||associativity]] between variables *A* and *B*, there may be other factors at play.

### 1.3.4 Observational studies versus experiments
- Two primary types of data collection:
	- [[observational study|Observational studies]]: when [[data]] is collected without any interference with how the data arises.
		- Researchers could collect information via surveys, medical company records, or follow a [[cohort]] of similar individuals to determine why certain diseases might develop.
	- [[experiment|Experiments]]: when one wants to investigate the possibility of a causal relationship
		- For any experiment, the researcher must impose a [[treatment]].
		- To check if there is a causal relationship between the [[explanatory variable]] and the [[response variable]], researchers collect a sample and assign units into groups, which are assigned the [[treatment]].
		- When individuals are randomly assigned to a group, the experiment is called a [[randomized experiment]].

#### Example 1.14
Suppose that a researcher is interested in the average tip customers at a particular restaurant give. Should she carry out an observational study or an experiment?
- The researcher should carry out an observational study because there is no causal relationship to determine nor [[treatment]] to impose. The study would also require no interference, just simple data collection.

#### Association $\ne$ causation
- Association does not imply causation
- Causation can only be inferred from a [[randomized experiment]].

### Section summary
- The [[population]] is the entire group that the researchers are interested in. Because it is usually too costly to gather the data for the entire population, researchers will collect data from a [[sample]], representing a subset of the population.
- A [[parameters|parameter]] is a true quantity for the entire population, while a [[statistic]] is what is calculated from the sample. A parameter is about a population and a statistic is about a sample. *Remember: p goes with p and s goes with s.*
- Two common summary statistics are [[mean]] (for numerical variables) and [[proportion]] (for categorical variables).
- Finding a good estimate for a population parameter required a random sample; do not generalize from [[anecdotal evidence]].
- There are two primary types of data collection: [[observational study|observational studies]] and [[experiment|experiments]]. In an experiment, researchers impose a [[treatment]] to look for a causal relationship between the treatment and the response. In an observational study, researchers simply collect data without imposing any treatment.
- Remeber: *correlation is not causation!* In other words, an association between two variables does not imply that one causes the other. Proving a causal relationship requires a well-designed experiment.

### Exercises
#### 1.13 Air pollution and birth outcomes, scope of inference
[[Data collection#Exercises#1.3 Air pollution and birth outcomes, study components|Exercise 1.3]] introduces a study where researchers collected data to examine the relationship between air pollutants and preterm births in Southern California. During the study air pollution levels were measured by air quality monitoring stations. Length of gestation data were collected on 143,196 births between the years 1989 and 1993, and air pollution exposure during gestation was calculated for each birth.
(a) Identify the population of interest and the sample in this study.
- Population of interest: Human births
- Sample: Human births in Southern California between 1989 and 1993
(b) Comment on whether or not the results of the study can be generalized to the population, and if the findings of the study can be used to establish causal relationships.
- If the births are representative of all births in the geography, then it can be generalized for all births in Southern California. Since the study is strictly observational, however, there can be no causal relationship drawn.

#### 1.14 Cheaters, scope of inference.
[[Data collection#Exercises#Cheaters, study components|Exercise 1.5]] introduces a study where researchers studying the relationship between honesty, age, and self-control conducted an experiment on 160 children between the ages of 5 and 15. The researchers asked each child to toss a fair coin in private and to record the outcome (white or black) on a paper sheet, and said they would only reward children who report white. Half the students were explicitly told not to cheat and the others were not given any explicit instructions. Differences were observed in the cheating rates in the instruction and no instruction groups, as well as some differences across children's characteristics within each group.
(a) Identify the population of interest and the sample in this study.
- The population of interest for this study is all children children aged 5-15.
- The sample is 160 such children.
(b) Comment on whether or not the results of the study can be generalized to the population, and if the findings of the study can be used to establish causal relationships.
- These results cannot be generalized to the entire population of children because there are many factors that could affect a child's final decision whether to lie or not.  However, a causal relationship can be drawn between the presence of an award and the frequency of lies for a child, if the sample of children from the study was completely random.

#### 1.15 Buteyko method, scope of inference. 
[[Data collection#Exercises#Buteyko method, study components|Exercise 1.4]] introduces a study on using the Buteyko shallow breathing technique to reduce asthma symptoms and improve quality of life. As part of this study 600 asthma patients aged 18-69 who relied on medication for asthma treatment were recruited and randomly assigned to two groups: one practiced the Buteyko method and the other did not. Those in the Buteyko group experienced, on average, a signicant reduction in asthma symptoms and an improvement in quality of life.

(a) Identify the population of interest and the sample in this study.
- The population of interest is all asthma patients aged 18-69 who rely on medication for asthma treatment.
- The sample is 600 such patients.
(b) Comment on whether or not the results of the study can be generalized to the population, and if the findings of the study can be used to establish causal relationships.
- The results of this study can be generalized to the population if and only if they are considered respresentative of all asthma patients agred 18-69 who rely on medication for asthma treatment. The findings of this study can be used to establish causal relationships since it is experimental and the groups are completely random.

#### 1.16 Stealers, scope of inference. 
[[Data collection#Exercises#1.6 Stealers, study components|Exercise 1.6]] introduces a study on the relationship between socio-economic class and unethical behavior. As part of this study 129 University of California Berkeley undergraduates were asked to identify themselves as having low or high social-class by comparing themselves to others with the most (least) money, most (least) education, and most (least) respected jobs. They were also presented with a jar of individually wrapped candies and informed that the candies were for children in a nearby laboratory, but that they could take some if they wanted. After completing some unrelated tasks, participants reported the number of candies they had taken. It was found that those who were identied as upper-class took more candy than others.
(a) Identify the population of interest and the sample in this study.
- The population of interest is all adults.
- The sample is 129 UC Berkeley undergraduates.
(b) Comment on whether or not the results of the study can be generalized to the population, and if the findings of the study can be used to establish causal relationships.
- The findings of this study cannot be generalized to the population because UC Berkeley undergraduates are not representative of all adults. The findings of the study cannot be used to establish causal relationships because this is an [[observational study]].

#### 1.17 Relaxing after work.
The General Social Survey asked the question, "After an average work day, about how many hours do you have to relax or pursue activities that you enjoy?" to a random sample of 1,155 Americans. The average relaxing time was found to be 1.65 hours. Determine which of the following is an observation, a variable, a sample statistic (value calculated based on the observed sample), or a population parameter.
(a) An American in the sample.
- An observation
(b) Number of hours spent relaxing after an average work day.
- A variable
(c) 1.65.
- A sample statistics
(d) Average number of hours all Americans spend relaxing after an average work day.
- A population parameter

#### 1.18 Cats on YouTube.
Suppose you want to estimate the percentage of videos on YouTube that are cat videos. It is impossible for you to watch all videos on YouTube so you use a random video picker to select 1000 videos for you. You find that 2% of these videos are cat videos. Determine which of the following is an observation, a variable, a sample statistic (value calculated based on the observed sample), or a population parameter.
(a) Percentage of all videos on YouTube that are cat videos.
- A population parameter
(b) 2%.
- A sample statistic
(c) A video in your sample.
- An observation
(d) Whether or not a video is a cat video.
- A variable

## 1.4 Observational studies and sampling strategies
Topics: #confounding-factors #convenience-sample #volunteer-sample #random-sample #bias #undercoverage-bias #nonresponse-bias #response-bias #simple-random-sampling #systematic-random-sampling #stratified-random-sampling #cluster-random-sampling #sample-survey #generalization

### 1.4.1 Observational studies
- Data in [[observational study|observational studies]] are collected by monitoring what occurs.
- On the other hand, [[experiment|experiments]] require the primary [[explanatory variable]] in a study be assigned for each subject by the researchers.

#### Guided Practice 1.15
Suppose an observational study tracked sunscreen use and skin cancer, and it was found people who use sunscreen are more likely to get skin cancer than people who do not use sunscreen. Does this mean sunscreen *causes* skin cancer?
	- No, because this is an [[observational study]], and an [[experiment]] is needed in order to determine the causal relationship between the two.
	- In this scenario, sun exposure would be a [[confounding variable]] because it is associated with both the use of sunscreen and the development of skin cancer.
		- People who are out in the sun all day are more likely to use sunscreen, and people who are out in the sun all day are more likely to get skin cancer.

#### Confounding variables
- A [[confounding variable]] is a variable that is associated with both the [[explanatory variable|explanatory]] and [[response variable|response variables]]. 
- Because of the confounding variable's association with both variables, we do not know if the response is due to the explanatory variable or the confounding variable.

#### Example 1.16
In a study that followed 1,169 non-diabetic adults who had been hospitalized for a first heart attack, the people that reported eating chocolate had increased survival rate over the next 8 years than those that reported not eating chocolate. Also, those who ate more chocolate tended to live longer on average. The researchers controlled for several confounding factors, such as age, physical activity, smoking, and many other factors. Can we conclude that the consumption of chocolate caused the people to live longer?
- We cannot conclude that the consumption of chocolate caused people to live longer because this was an [[observational study]], and not a [[randomized experiment]]. 
- Furthermore, even if the researchers accounted for several confounding factors, there may have been many more confounding factors at play.

#### Example 1.17
The authors who conducted the study did warn in the article that additional studies would be necessary to determine whether the correlation between chocolate consumption and survival translates to any causal relationship. That is, they acknowledged that there may be confounding factors. One possible confounding factor not considered was mental health. In context, explain what it would mean for mental health to be a confounding factor in this study.
- If mental health was a confounding factor in this study, that would mean that a person's mental health is associated with both chocolate consumption and survival. For example, people with better mental health may eat more chocolate, but people with better mental health may *also* generally live longer.

#### Guided Practice 1.18
[[Figure 1.8.png|Figure 1.8]] shows a negative association between the homeownership rate and the percentage of multi-unit structures in a county. However, it is unreasonable to conclude that there is a causal relationship between the two variables. Suggest one or more other variables that might explain the relationship visible in [[Figure 1.8.png|Figure 1.8]].
- Population density is a confounding variable in this relationship. Counties with a higher population density have increased multi-unit structures but also decreased homeownership rates.

- [[observational study|Observational studies]] come in two forms:
	- [[prospective study|Prospective study]]: identifies individuals and collects information as events unfold
	- [[retrospective study|Retrospective study]]: collects data after events have taken place

### 1.4.2 Sampling from a population
Let's say that we try to estimate the time to graduation for Duke undergraduates in the last 5 years by collecting a sample of students.
- In order to be able to generalize the results of a sample study, the sample must be *randomly* selected from the population of interest.
- The most basic type of random selection ([[simple random sampling]]) is equivalent to how raffles are conducted.
	- This means that each case in the population has an equal chance of being included and there is no implied connection between the cases in the sample

![[Figure 1.11.png]]

Alternatively, why not just pick a sample by hand? Consider the following figure:

![[Figure 1.12.png]]

#### Example 1.19
Suppose we ask a student who happens to be majoring in nutrition to select several graduates for the study. What kind of students do you think she might select? Do you think her sample would be representative of all graduates?
	- The student would probably select geveral graduates that majored in health. 
	- This sample would not be representative of all graduates because it would be mainly composed of graduates that majored in a particular field.
	- In this example, [[undercoverage bias]] creates a problem because students that majored in health-based fields might have taken longer to graduate.
		- Since graduates from other fields would be less likely to be in the sample, the undercoverage bias would cause her to *overestimate* the [[parameters|parameter]].

- If the student picked a disproportionate amount of students from health-based fields, it would introduce [[undercoverage bias]] into the sample.
	- Sampling randomly resolves the problem of undercoverage bias, but only if the sample is randomly chosen from the *entire* population of interest, not a subset.
- Another common downfall is a [[convenience sample]], where easily accessible individuals are more likely to be included in the sample.
  ![[Figure 1.13.png]]
- A [[volunteer sample]] is a sample in which people's responses are solicited and only those who *choose*  to participate respond.
	- This is problematic because those who choose to participate may tend to have different opinions than the rest of the population.

#### Guided Practice 1.20
We can easily access ratings for products, sellers, and companies through websites. These ratings are based only on those people who go out of their way to provide a rating. If 50% of online reviews for a product are negative, do you think this means that 50% of buyers are dissatised with the product?
	- Probably not, as this is a [[volunteer sample]]. People are more likely to critique something they don't like than praise something they enjoy.

- Even when people are picked at random, caution has to be exhibited if the [[non-response]] is high.
	- If only 30% of randomly sampled individuals for a survey actually respond, then it is unclear whether the survey results are representative of the entire population and can be generalized.
	- This [[non-response bias]] can skew results.
- [[response bias|Response bias]] arises from a broad range of factors that can influence how people choose to respond to a survey, such as question wording, question order, and the influence an interviewer may have.
	- Can be present even when collecting a [[census]].
	- Often the most subtle type of bias.

#### Example 1.21
Suppose a high school student wants to investigate the student body's opinions on the food in the cafeteria. Let's assume that she manages to survey every student in the school. How might response bias arise in this context?
	- Students could respond differently if the high school student interviewing them is their friend or someone respectable. 
	- Alternatively, the wording of the questions may incur a certain type of response from the interviewee.

#### Watch out for bias
- Even if a sample is sampled randomly, undercoverage bias, non-response bias, and response bias can still exist.
- Always determine how a sample was chosen, ask what proportion of individuals failed to respond, and critically examine the wording of the questions.

- When there is no bias in a sample, increasing the sample size tends to increase the precision and reliability of the estimate.
- Conversely, when a sample is biased, it is difficult to decipher helpful information from the data, especially as it becomes larger.

#### Guided Practice 1.22
A researcher sends out questionnaires to 50 randomly selected households in a particular town asking whether or not they support the addition of a traffic light in their neighborhood. Because only 20% of the questionnaires are returned, she decides to mail questionnaires to 50 more randomly selected households in the same neighborhood. Comment on the usefulness of this approach.
	- This approach will not be that useful, as respondees from that same neighborhood have already been *determined* to have a low responsiveness. Instead, the researcher should try to solicit the respondees who did not respond for answers.

### 1.4.3 Simple, systematic, stratified, cluster, and multistage sampling
- Two properties are always true in [[simple random sampling]]:
		1. Each case in the population has an equal chance of being included in the sample.
		2. Each *group* of *n* cases has an equal chance of making up the sample.
		a. This property does not hold for the other four random sampling methods.
- [[systematic random sampling]] is sometimes used when there exists a list of all of the individuals of the population, or if the size of the population is known.

#### Example 1.23
A systematic sample is not the same as a simple random sample. Provide an example of a sample that can come from a simple random sample but not from a systematic random sample.
	- If we have a set of four objects, we can obtain a sample of them in the order {1, 2, 3, 4} with random sampling; however, with systematic random sampling, this would be impossible, as you would be sampling over an interval instead (e.g. every 2nd object).

![[Figure 1.14.png]]

- Whenever there is a variable that is known to be associated with a quantity you want to estimate, you could use [[stratified random sampling]].
	- The population groups are divided into groups called [[strata]].
	- The [[strata]] are chosen so that similar cases are grouped together and a sampling method (typically [[simple random sampling]]) is used to select a certain proportion of the whole within each stratum.

#### Example 1.24
For a group of 30 baseball teams, briefly explain how to select a [[stratified random sampling|stratified random sample]] of size *n* = 120.
	- Each team could serve as a [[strata|stratum]], with 4 players randomly chosen among the 30 teams, giving a "random" sample of 120 players. 

#### Example 1.25
[[stratified random sampling|Stratified random sampling]] is especially useful when the cases in each stratum are very similar *with respect to the outcome of interest.* Why is it good for cases within each stratum to be very similar?
	- We would get a more stable estimate for each of the subpopulations in the [[strata]] if the cases are more similar, which would give us a reliable output for the estimate of the full population. Essentially, it would assure proportional representation from each strata such that no group is overrepresentified due to random chance.

- [[cluster random sampling]] is much like [[simple random sampling]], but instead of randomly selecting *individuals*, we randomly select groups or [[clusters]].
	- Most helpful when there is a lot of case-to-case variability within a cluster but the clusters themselves don't look very different from one another
	- We expect individual [[strata]] to be [[homogeneous]] and individual [[clusters]] to be [[heterogeneous]] with respect to the variable of interest.
- [[multistage cluster random sampling|Multistage cluster random sampling]] is a two step strategy:
	1. Take a [[cluster random sampling|random cluster sample]].
	2. Instead of including all of the individuals in these [[clusters]] in our sample, employ a secondary sampling method (usually [[simple random sampling]]) within the clusters
		- Can be hierarchical with subclusters that are randomly sampled within clusters that were randomly sampled to begin with.
![[Figure 1.15.png]]

#### Example 1.26
Suppose we are interested in estimating the proportion of students at a certain school that have part-time jobs. It is believed that older students are more likely to work than younger students. What sampling method should be employed? Describe how to collect such a sample to get a sample size of 60.
	- [[stratified random sampling]] should be employed because grade level affects the likelihood of having a part-time job.
	- Create a [[strata|stratum]] for every grade level in the school and perform [[simple random sampling]] for $\large \frac{60}{\text{numStrata}}$ individuals.

#### Example 1.27
Suppose we are interested in estimating the malaria rate in a densely tropical portion of rural Indonesia. We learn that there are 30 villages in that part of the Indonesian jungle, each more or less similar to the next. Our goal is to test 150 individuals for malaria. What sampling method should be employed?
	- [[multistage cluster random sampling|Multistage cluster random sampling]] should be employed here, since we can randomly choose [[clusters]] of villages and then randomly choose its *n* residents of each cluster for malaria.

### Section summary
- In an [[observational study]], one must always consider the existence of [[confounding variable|confounding factors]]. A confounding factor is a "spoiler variable" that could explain an observed relationship between the [[explanatory variable]] and the [[response variable|response]].
- When taking a sample from a population, avoid [[convenience sample|convenience samples]] and [[volunteer sample|volunteer samples]], which likely introduce bias. Instead, use a random sampling method.
- Generalizations from a sample can be made to a population only if the sample is random. Furthermore, the generalization can be made only to the population from which the sample was randomly selected, not to a larger or different population.
- Random sampling from the entire population of interest avoids the problem of [[undercoverage bias]]. However, [[response bias]] and [[non-response bias]] can be present in any sample, random or not.
- In a [[simple random sampling|simple random sample]], every *individual* as well as *group of individuals* has the same probability of being included in the sample. A common way to select a simple random sample is to number each individual of the population 1 to N. Using a random digit table or random number generator, numbers are randomly selected without replacement and the corresponding individuals become part of the sample.
- A [[systematic random sampling|systematic random sample]] involves choosing from a population using a random starting point, and then selecting members according to a fixed, periodic interval.
- A [[stratified random sampling|stratified random sample]] involves randomly sampling from *every* [[strata]], wherer the strata should correspond to a variable thought to be associated with the variable of interest. This ensures that the sample will have appropriate representation from each of the different strata and reduces variability in the sample estimates.
- A [[cluster random sampling|cluster random sample]] involves randomly selecting a set of [[clusters]] and then collecting data on all individuals in the selected clusters. This can be useful when sampling clusters is more convenient and less expensive than sampling individuals, and it is an effective strategy when each cluster is approximately representative of the population.
- Remember: individual [[strata]] should be [[homogeneous]], while individual [[clusters]] should be [[heterogeneous]]. For example, if smoking is correlated with what is being estimated, let one stratum be all smokers and the other be all non-smokers, then randomly select an appropriate number of *individuals* from *each* strata. Alternatively, if age is correlated with the variable being estimated, one could randomly select a *subset* of clusters, where each cluster has mixed age groups.

### Exercises
#### 1.19 Course satisfaction across sections. 
A large college class has 160 students. All 160 students attend the lectures together, but the students are divided into 4 groups, each of 40 students, for lab sections administered by different teaching assistants. The professor wants to conduct a survey about how satisfied the students are with the course, and he believes that the lab section a student is in might affect the student's overall satisfaction with the course.
(a) What type of study is this?
	- This is an [[observational study]].
(b) Suggest a sampling strategy for carrying out this study.
	- Use [[stratified random sampling]] to randomly sample a fixed amount of students from each of the 4 groups.

#### 1.20 Housing proposal across dorms. 
On a large college campus first-year students and sophomores live in dorms located on the eastern part of the campus and juniors and seniors live in dorms located on the western part of the campus. Suppose you want to collect student opinions on a new housing structure the college administration is proposing and you want to make sure your survey equally represents opinions from students from all years.
(a) What type of study is this?
	- This is a sample study.
(b) Suggest a sampling strategy for carrying out this study.
	- [[multistage cluster random sampling]] could be used for carrying out this study. For the clusters of students that live on the eastern and western part of the college campus, you can randomly sample a fixed amount of students from each cluster.

#### 1.21 Internet use and life expectancy. 
The following scatterplot was created as part of a study evaluating the relationship between estimated life expectancy at birth (as of 2014) and percentage of internet users (as of 2009) in 208 countries for which such data were available.
![[internet-use-and-life-expectancy.png]]
(a) Describe the relationship between life expectancy and percentage of internet users.
	- Life expectancy and percentage of internet users have a [[positive association]].
(b) What type of study is this?
	- This is a [[retrospective study]].
(c) State a possible confounding variable that might explain this relationship and describe its potential effect.
	- The human development index (HDI) of the country may explain this relationship. Higher developed countries happen to have a higher percentage of internet users, and higher developed countries also happen to have a higher standard of living which causes a higher life expectancy. 

#### 1.22 Stressed out, Part I. 
A study that surveyed a random sample of otherwise healthy high school students found that they are more likely to get muscle cramps when they are stressed. The study also noted that students drink more coffee and sleep less when they are stressed.
(a) What type of study is this?
	- This is an [[observational study]].
(b) Can this study be used to conclude a causal relationship between increased stress and muscle cramps?
	- No, but it could be generalized for healthy high school students if the students were truly sampled randomly.
(c) State possible confounding variables that might explain the observed relationship between increased stress and muscle cramps.
	- Holding a position for a long time could increase with stress if a student has an assignment due. Holding a position fro a long time could also increase likelihood of muscle cramps.
	- Stress causes muscle tension. Increased muscle tension could cause cramps.

#### 1.23 Evaluate sampling methods. 
A university wants to determine what fraction of its undergraduate student body support a new $25 annual fee to improve the student union. For each proposed method below, indicate whether the method is reasonable or not.
(a) Survey a [[simple random sampling|simple random sample]] of 500 students.
	- This is a reasonable method, as long as you are conducting the random sampling on the entire undergraduate student population and not a subset. 
(b) Stratify students by their field of study, then sample 10% of students from each stratum.
	- This is a reasonable method, as student opinions may vary based on their field of study.
(c) Cluster students by their ages (e.g. 18 years old in one cluster, 19 years old in one cluster, etc.), then randomly sample three clusters and survey all students in those clusters.
	- This is not a reasonable method, as a disproportionate amount of students may be in a particular age group and choosing three clusters out of the age cluster groups may not be representative of the entire student undergraduate population.

#### 1.24 Random digit dialing. 
The Gallup Poll uses a procedure called random digit dialing, which creates phone numbers based on a list of all area codes in America in conjunction with the associated number of residential households in each area code. Give a possible reason the Gallup Poll chooses to use random digit dialing instead of picking phone numbers from the phone book.
	- Residents from the phone book of a particular area may express similar thoughts and opinions, skewing the poll.

#### 1.25 Haters are gonna hate, study confirms.
A study published in the *Journal of Personality* and *Social Psychology* asked a group of 200 randomly sampled men and women to evaluate how they felt about various subjects, such as camping, health care, architecture, taxidermy, crossword puzzles, and Japan in order to measure their attitude towards mostly independent stimuli. Then, they presented the participants with information about a new product: a microwave oven. This microwave oven does not exist, but the participants didn't know this, and were given three positive and three negative fake reviews. People who reacted positively to the subjects on the dispositional attitude measurement also tended to react positively to the microwave oven, and those who reacted negatively tended to react negatively to it. Researchers concluded that some people tend to like things, whereas others tend to dislike things, and a more thorough understanding of this tendency will lead to a more thorough understanding of the psychology of attitudes."
(a) What are the cases?
	- 200 randomly sampled men and women
(b) What is (are) the response variable(s) in this study?
	- Whether they reacted positively or not
(c) What is (are) the explanatory variable(s) in this study?
	- How the individual felt about each of the subjects presented
(d) Does the study employ random sampling?
	- Yes; the individuals selected were randomly selected.
(e) Is this an [[observational study]] or an [[experiment]]? Explain your reasoning.
	- This is an observational study because there was no attempt made to influence the outcome of the experiment and the individuals' responses were being observed. 
(f) Can we establish a causal link between the explanatory and response variables?
	- We cannot establish a causal link between the explanatory and response variables, as this was not a [[randomized experiment]].
(g) Can the results of the study be generalized to the population at large?
	- The results of the study can be generalized to the population at large because the sampling was random, which means it is representative of the entire population of men and women (or humans).

#### 1.26 Family size.
Suppose we want to estimate household size, where a "household" is dened as people living together in the same dwelling, and sharing living accommodations. If we select students at random at an elementary school and ask them what their family size is, will this be a good measure of household size? Or will our average be biased? If so, will it overestimate or underestimate the true value?
	- This survey will not be a good measure of household size, as families with children will be larger on average. This will make our average biased and overestimate the true value.

#### 1.27 Sampling strategies.
A statistics student who is curious about the relationship between the amount of time students spend on social networking sites and their performance at school decides to conduct a survey. Various research strategies for collecting data are described below. In each, name the sampling method proposed and any bias you might expect.
(a) He randomly samples 40 students from the study's population, gives them the survey, asks them to fill it out and bring it back the next day.
	- Sampling method: [[simple random sampling]]
	- Potential biases: [[response bias]], [[non-response bias]]
(b) He gives out the survey only to his friends, making sure each one of them fills out the survey.
	- Sampling method: [[convenience sample]]
	- Potential biases: [[response bias]] [[undercoverage bias]]
(c) He posts a link to an online survey on Facebook and asks his friends to fill out the survey.
	- Sampling method: [[convenience sample]]
	- Potential biases: [[response bias]] [[non-response bias]] [[undercoverage bias]]
(d) He randomly samples 5 classes and asks a random sample of students from those classes to fill out the survey.
	- Sampling method: [[multistage random sampling]]
	- Potential biases: [[response bias]] [[non-response bias]

#### 1.28 Reading the paper. 
Below are excerpts from two articles published in the *NY Times*:
(a) An article titled *Risks: Smokers Found More Prone to Dementia* states the following:
"Researchers analyzed data from 23,123 health plan members who participated in a voluntary exam and health behavior survey from 1978 to 1985, when they were 50-60 years old. 23 years later, about 25% of the group had dementia, including 1,136 with Alzheimer's disease and 416 with vascular dementia. After adjusting for other factors, the researchers concluded that pack-a-day smokers were 37% more likely than nonsmokers to develop dementia, and the risks went up with increased smoking; 44% for one to two packs a day; and twice the risk for more than two packs."
Based on this study, can we conclude that smoking causes dementia later in life? Explain your reasoning.
	- Despite the strong relationship that exists between smoking and dementia in the study, we cannot conclude that smoke causes dementia later in life. This is because the study is a [[retrospective study]], a type of observational study, rather than a [[randomized experiment]].
(b) Another article titled *The School Bully Is Sleepy* states the following: 
"The University of Michigan study, collected survey data from parents on each child's sleep habits and asked both parents and teachers to assess behavioral concerns. About a third of the students studied were identied by parents or teachers as having problems with disruptive behavior or bullying. The researchers found that children who had behavioral issues and those who were identied as bullies were twice as likely to have shown symptoms of sleep disorders." A friend of yours who read the article says, "The study shows that sleep disorders lead to bullying in school children." 
Is this statement justied? If not, how best can you describe the conclusion that can be drawn from this study?
	- This statement is not justified. The survey may be biased because the respondees are parents and teachers. There are also many [[confounding variable||confounding variables]] at play between bullying/disruptive behavior and those with symptoms of sleep disorders, such as mental health.

## 1.5 Experiments
Topics: #subjects #experimental-units #treatments #response-variables #experiment-design #direct-control #randomization #replication #placebo-effect #single-blind #double-blind #completely-randomized-design #blocked-design #matched-pairs-design #random-assignment #causal-relationship #number-of-factors #number-of-levels #number-of-treatments

### 1.5.1 Reducing bias in human experiments
- Just as randomization is essential in sampling in order to avoid selection bias, randomization is essential in the context of experiments to determine which subjects will receive such treatments.
- Randomized experiments are essential in identifying causal relationships, but they do not inherently ensure unbias.
- In an experiment, the [[explanatory variable]] is also called a [[factor]].
- Each factor has [[levels]], like a [[categorical|categorical variable]].
- When researchers keep patients uninformed about whether they are in the [[control group]] or [[treatment group]], the study is said to be [[single-blind]].
	- The problem with this: a patient will know they are in the control group if they do not receive a treatment.
	- The solution: give [[placebo|placebos]] to patients in the control group.
	- Often times, a placebo results in a slight, real improvement in patients, dubbed the [[placebo effect]].
- Modern studies employ a [[double-blind]] effect where the researchers that interact with the subjects *themselves* are unaware of the [[control group|control]] and [[treatment group|treatment]] groups.

#### Guided Practice 1.28
Look back to the study in [[Data collection#1.1 Case study: using stents to prevent strokes|Section 1.1]] where researchers were testing whether stents were effective at reducing strokes in at-risk patients. Is this an [[experiment]]? Was the study blinded? Was it [[double-blind|double-blinded]]?
	- The study from Section 1.1 was an experiment. The study was not blinded since the patients could distinguish whether they recieved stents or not. Since the study was not blinded, it could not have been double-blinded either.

### 1.5.2 Principles of experimental design
Well-conducted experiments are built on three main principles:
- [[direct control|Direct Control]]:
	- Researchers assign [[treatment|treatments]] to cases and do their best to control any differences in the groups.
	- The goal is to make all of the groups identical *except* the treatment so they can attribute any difference in response in the groups to the treatment.
	- A researcher can directly control the appearance of the treatment, time of day it is taken, etc.
- [[randomization|Randomization]]:
	- Researchers randomize patients into [[treatment group|treatment groups]] to account for variables that cannot be controlled.
	- Randomizing patients into the treatment and [[control group|control]] groups helps *even out* the effects of such differences and prevents accidental bias from entering the study.
- [[replication|Replication]]:
	- The more cases a researcher observes, the more accurately they can estimate the effect of the [[explanatory variable]] on the [[response variable|response]].
	- A group of scientists may replicate an entire study to verify a previous finding.
	- Each study should ensure a sufficiently large number of subjects because of funding or opportunity issues that may arise.

### 1.5.3 Completely randomized, blocked, and matched pairs design
- A [[completely randomized experiment]] is one in which the subjects/experimental units are randomly assigned to each group in the experiment.
- This method of randomly allocating subjects to treatments is not equivalent
to taking a [[simple random sampling|simple random sample]] as you are randomly *splitting* objects into groups and not sampling anything.
- Researchers may conduct a [[blocked experiment]] if they know or suspect that another variable, other than the [[treatment]], influences the response.
	- Individuals are grouped into [[blocks]] based on the identified variable.
	- Subjects within each block are randomized into the [[treatment group|treatment groups]].
	- By randomizing subjects to treatments within each block, we attempt to even out the effect of variables that we cannot block or directly control.
	- We can compare the results of the effect the [[treatment]] has on the [[blocks|block]] against the main group (or blocks against each other), to see whether the identified variable made a difference between both treatment groups.

#### Example 1.29
An experiment will be conducted to compare the effectiveness of two methods for quitting smoking. Identify a variable that the researcher might wish to use for blocking and describe how she would carry out a blocked experiment.
	- A reasonable variable for the researcher to use for blocking is the number of years the individual has smoked for. They could then divide the sample into [[blocks]] based on the number of years they have spent smoking and divide each block randomly between the two [[treatment group|treatment groups]].

![[Figure 1.16.png]]

- Even with randomized blocking, some other variables that affect the response may be unevenly distributed among the [[treatment group|treatment groups]].
- [[matched pairs|Matched pairs]], a special type of blocking, addresses this problem.

#### Guided Practice 1.30
How and why should [[randomization]] be incorporated into a [[matched pairs]] design?
	- We can randomly assign treatments to the matched pairs, or randomly choose the order if they are recieving both treatments. This is to help ensure that any observed treatment effects are due to the treatment itself, and not to other factors such as participant characteristics or differences in the environment.

#### Guided Practice 1.31
Matched pairs sometimes involves each subject receiving both treatments at the same time. For example, if a hand lotion was being tested, half of the subjects could be randomly assigned to put Lotion A on the left hand and Lotion B on the right hand, while the other half of the subjects would put Lotion B on the left hand and Lotion A on the right hand. Why would this be a better design than a completely randomized experiment in which half of the subjects put Lotion A on both hands and the other half put Lotion B on both hands?
	- You can compare the results of the hand lotion on an individual level with an individual's skin characteristics rather than comparing an individual to another individual.

### 1.5.4 Testing more than one variable at a time
- Some studies have multiple [[factor|factors]] ([[explanatory variable|explanatory variables]]) at a time, and each of those factors could have multiple [[levels]] at a time.
- Because those factors and levels could be related to one another, researchers experiment with using all possible combinations of those factors and levels---one for each experiment group.
	- Each combination is a [[treatment]].

#### Guided Practice 1.32
A researcher wants to compare the effectiveness of four different drugs. She also wants to test each of the drugs at two doses: low and high. Describe the [[factor|faactors]], [[levels]], and [[treatment|treatments]] of this experiment.
- The factors are drug type (4 levels) and dosage (2 levels).
- The treatments are the combinations of dosages for *each* of the drugs.

### Section summary
- In an [[experiment]], researchers impose a [[treatment]] to test its effects. In order for observed differences in the response to be attributed to the treatment and not some other factor, it is important to make the treatment groups and the conditions for the treatment groups as similar as possible.
- Researchers use [[direct control]], ensuring the variables that are within their power to modify are made the *same* for each [[treatment group]].
- Researchers randomly assign subjects to the treatment groups so that the effects of uncontrolled and potentially [[confounding variable|confounding variables]] are *evened out* among the treatment groups.
- [[replication|Replication]], or imposing the treatments on many subjects, gives more data and decreases the likelihood that the treatment groups differ on some characteristic due to chance alone.
- An ideal experiment is randomized, controlled, and [[double-blind]].
- A [[completely randomized experiment]] involves randomly assigning the subjects to the different treatment groups. To do this, first number the subjects 1 to N. Then, randomly choose some of those numbers and assign the corresponding subjects to a treatment group. Do this in such a way that the treatment group sizes are balanced, unless there exists a good reason to make one treatment group larger than the other.
- In a [[blocked experiment]], subjects are first separated by a variable thought to affect the [[response variable]]. Then, within *each* [[blocks|block]], subjects are randomly assigned to the treatment groups as described above, allowing the researcher to compare like to like within each block.
- When feasible, a [[matched pairs]] experiment is ideal, because it allows for the best comparison of like to like. A matched pairs experiment can be carried out on pairs of subjects that are meaningfully paired, such as twins, or it can involve all subjects receiving both treatments, allowing subjects to be compared to *themselves*.
- A treatment is also called a [[factor]] or [[explanatory variable]]. Each treatment/factor can have multiple [[levels]], such as yes/no/ or low/medium/high. When an [[experiment]] includes many factors, multiplying the number of levels of the factors together gives the total number of [[treatment group|treatment groups]].
- In an experiment, blocking, [[randomization]], and [[direct control]] are used to *control for confounding factors*.

### Exercises
#### 1.29 Light and exam performance.
A study is designed to test the effect of light level on exam performance of students. The researcher believes that light levels might have different effects on males and females, so wants to make sure both are equally represented in each treatment. The treatments are fluorescent overhead lighting, yellow overhead lighting, no overhead lighting (only desk lamps).
(a) What is the response variable?
	- Exam performance of students
(b) What is the explanatory variable? What are its levels?
	- Light level: fluorescent overhead lighting, yellow overhead lighting, and no overhead lighting.
(c) What is the blocking variable? What are its levels?
	- Sex: male and female

#### 1.30 Vitamin supplements.
To assess the effectiveness of taking large doses of vitamin C in reducing
the duration of the common cold, researchers recruited 400 healthy volunteers from staff and students at a university. A quarter of the patients were assigned a [[placebo]], and the rest were evenly divided between 1g Vitamin C, 3g Vitamin C, or 3g Vitamin C plus additives to be taken at onset of a cold for the following two days. All tablets had identical appearance and packaging. The nurses who handed the prescribed pills to the patients knew which patient received which treatment, but the researchers assessing the patients when they were sick did not. No signicant differences were observed in any measure of cold duration or severity between the four groups, and the placebo group had the shortest duration of symptoms.
(a) Was this an [[experiment]] or an [[observational study]]? Why?
	- This was an experiment because it occurred in a controlled environment and had different treatments.
(b) What are the explanatory and response variables in this study?
	- Explanatory variable: dosage of vitamin C received
	- Response variables: cold duration, cold severity
(c) Were the patients blinded to their treatment?
	- Yes; they did not know the treatment they had received.
(d) Was this study double-blind?
	- Yes; the researcher did not know which participants received which treatments.
(e) Participants are ultimately able to choose whether or not to use the pills prescribed to them. We might expect that not all of them will adhere and take their pills. Does this introduce a [[confounding variable]] to the study? Explain your reasoning.
	- This adds a confounding variable, whether the patient took the pills, to the study. It is associated with both the dosage of vitamin C the patient received and the cold duration and severity if the patient don't feel the effect of the pills and decide not to take it.

#### 1.32 Music and learning.
You would like to conduct an experiment in class to see if students learn better if they study without any music, with music that has no lyrics (instrumental), or with music that has lyrics. Briefly outline a design for this study.
	- Randomly select a number of students.
	- Randomly assign one-third of the number of students to each group.
	- Give students a test to assess their baseline knowledge.
	- Tell students to study the material for an hour. Give them the same study material and resources and music within their groups. Ensure that the environments they are studying in are as similar as possible.
	- After an hour, give the students another exam on the same material.
	- Compute the score differences between all three groups.

#### 1.33 Soda preference. 
You would like to conduct an experiment in class to see if your classmates prefer the taste of regular Coke or Diet Coke. Briefly outline a design for this study.
	- Randomly select a number of classmates.
	- For each participant, perform the following:
		- Blind the participant
		- Prepare two cups, one containing Coke and the other one containing Diet Coke, ensuring that the cups themselves are the same and contain equivalent soda amounts.
		- Unblind the participant
		- Tell them to drink both cups and rate each one on a scale from 1-10.

#### 1.34 Exercise and mental health
A researcher is interested in the effects of exercise on mental health and he proposes the following study: Use [[stratified random sampling]] to ensure representative proportions of 18-30, 31-40 and 4-55 year olds from the population. Next, randomly assign half the subjects from each age group to exercise twice a week, and instruct the rest not to exercise. Conduct a mental health exam at the beginning and at the end of the study, and compare the results.
(a) What type of study is this?
	- This is an [[experiment]].
(b) What are the treatment and control groups in this study?
	- Treatment group: The subjects told to exercise twice a week.
	- Control group: The subjects told not to exercise.
(c) Does this study make use of blocking? If so, what is the blocking variable?
	- This study makes use of blocking. The blocking variable is age.
(d) Does this study make use of blinding?
	- This study does not make use of blinding. 
(e) Comment on whether or not the results of the study can be used to establish a causal relationship between exercise and mental health, and indicate whether or not the conclusions can be generalized to the population at large.
	- The results of this study cannot be sused to establish a causal relationship on health because it was not a blind experiment and there are many other [[confounding variable|confounding variables]] at play. However, if the stratified random samples are representative of the entire population, the conclusions can be generalized.
(f) Suppose you are given the task of determining if this proposed study should get funding. Would you have any reservations about the study proposal?
	- I would certainly have reservations about the experimental design. It would be extremely difficult to establish a causal relationship between exercise and mental health without [[replication]], which would be very costly given the experiment duration, as the patients are not blind. There are also many other confounding variables at play (e.g. the environment of the patients are varied and could affect the response of mental health).

## Chapter highlights
- Researchers take a random sample in order to draw an inference to the larger population from which they were sampled. When examining observational data, even if the individuals were randomly sampled, a correlation does not imply a causal link.
- In an [[experiment]], researchers impose a [[treatment]] and use random assignment in order to draw causal conclusions about the effects of the treatment. While often implied, inferences to a larger population may not be valid if the subjects were not also *randomly sampled* from that population.
- Stratifying vs Blocking:
	- Stratifying is used when sampling, where the purpose is to *sample* a subgroup from each [[strata|stratum]] in order to arrive at a better *estimate* for a [[parameters|parameter]] of interest.
	- Blocking is used in an [[experiment]] to *separate* objects into [[blocks]] and then *compare* responses within those blocks. All subjects within a block are  used in the experiment, not just a sample of them.
- Random sampling vs Random Assignment:
	- Random sampling refers to sampling a subset of a population for the purpose of inference to that population. 
	- Random assignment is used in an experiment to separate subjects into groups for the purpose of comparison between those groups.
- When [[randomization]] is *not* employed, such as in an [[observational study]], neither inferences nor causal conclusions can be drawn. Always be mindful of [[confounding variables]] when interpreting the results of observation studies.

## Chapter exercises
### 1.35 Pet names
The city of Seattle, WA has an open data portal that includes pets registered in the city. For each registered pet, we have information on the pet's name and species. The following visualization plots the proportion of dogs with a given name versus the proportion of cats with the same name. The 20 most common cat and dog names are displayed. The diagonal line on the plot is the $x = y$ line; if a name appeared on this line, the name's popularity would be exactly the same for dogs and cats.
![[pet-names.png]]
(a) Are these data collected as part of an [[experiment]] or an [[observational study]]?
	- This data was collected as part of an observational study.
(b) What is the most common dog name? What is the most common cat name?
	- The most common dog name is Lucy. The most common cat name is Luna.
(c) What names are more common for cats than dogs?
	- Oliver and Lily are names that ar emore common for cats than dogs.
(d) Is the relationship between the two variables positive or negative? What does this mean in context of the data?
	- The relationship between the two variables is positive. This means that the popularity of a cat's name increases as the popularity of a dog's name increases and vice-versa.

### 1.36 Stressed out, Part II
In a study evaluating the relationship between stress and muscle cramps, half the subjects are randomly assigned to be exposed to increased stress by being placed into an elevator that falls rapidly and stops abruptly and the other half are left at no or baseline stress.
(a) What type of study is this?
	- This is an [[experiment]].
(b) Can this study be used to conclude a causal relationship between increased stress and muscle cramps?
	- Yes, as long as the subjects were randomly chosen out of the entire population, because [[randomization]] exists and the subjects are all exposed to the same enironment

### 1.37 Chia seeds and weight loss
Chia Pets---those terra-cotta gurines that sprout fuzzy green hair---made the chia plant a household name. But chia has gained an entirely new reputation as a diet supplement. In one 2009 study, a team of researchers recruited 38 men and divided them randomly into two groups: treatment or control. They also recruited 38 women, and they randomly placed half of these participants into the treatment group and the other half into the control group. One group was given 25 grams of chia seeds twice a day, and the other was given a [[placebo]]. The subjects volunteered to be a part of the study. After 12 weeks, the scientists found no signicant difference between the groups in appetite or weight loss.
(a) What type of study is this?
	- This is an [[experiment]].
(b) What are the experimental and control treatments in this study?
	- The experimental treatment is the 25 grams of chia seeds twice a day.
	- The control treatment is the placebo.
(c) Has blocking been used in this study? If so, what is the blocking variable?
	- Blocking has been used in this study; the blocking variable is sex.
(d) Has blinding been used in this study?
	- As long as the placebo is identical to the experimental treatment, then blinding has been successfully accomplished.
(e) Comment on whether or not we can make a causal statement, and indicate whether or not we can generalize the conclusion to the population at large.
	- We can make a causal statement for this study because [[randomization]] was employed during the experiment with a control group. The environment also remained the same during the experimentation period. The experiment was blind for the participants and blocking was used to separate sex as a potential [[confounding variable]], incurring no bias. We can generalize the conclusion to the population at large if and only if the study participants are representative of the entire population, since they were not randomly selected but volunteered.

### 1.38 City council survey
A city council has requested a household survey be conducted in a suburban area of their city. The area is broken into many distinct and unique neighborhoods, some including large homes, some with only apartments, and others a diverse mixture of housing structures. For each part below, identify the sampling methods described, and describe the statistical pros and cons of the method in the city's context.
(a) Randomly sample 200 households from the city.
	- Sampling method: [[simple random sampling]]
	- Pros: Randomly selected, incurring no selection bias
	- Cons: Some other biases could exist in the sample itself, the sample could be disproportionate due to chance alone.
(b) Divide the city into 20 neighborhoods, and sample 10 households from each neighborhood.
	- Sampling method: [[stratified sampling]]
	- Pros: Equal proportions of respondees coming from every neighborhood 
	- Cons: Categorizing and interpreting results can be difficult, it can be hard to make the [[strata]] [[homogenous]] when considering neighborhoods
(c) Divide the city into 20 neighborhoods, randomly sample 3 neighborhoods, and then sample all households from those 3 neighborhoods.
	- Sampling method: [[cluster random sampling]]
	- Pros: Takes clusters of data in at once which is less expensive
	- Cons: Difficult to analyze, prone to sampling errors, final results may be disproportionate due to random chance
(d) Divide the city into 20 neighborhoods, randomly sample 8 neighborhoods, and then randomly sample 50 households from those neighborhoods.
	- Sampling method: [[multistage cluster random sampling]]
	- Pros: Chooses the data more carefully, can distribute the neighborhoods into subclusters without restrictions, flexible 
	- Cons: Hard to analyze, high level of subjectivity, not fully accurate of the population
(e) Sample the 200 households closest to the city council offices.
	- Sampling method: [[convenience sample]]
	- Pros: Cheap cost, easy to gather data
	- Cons: [[undercoverage bias]] could exist due to similar opinions over a small geographic area.

### 1.39 Flawed reasoning
Identify the flaw(s) in reasoning in the following scenarios. Explain what the
individuals in the study should have done differently if they wanted to make such strong conclusions.
(a) Students at an elementary school are given a questionnaire that they are asked to return after their parents have completed it. One of the questions asked is, "Do you find that your work schedule makes it diffcult for you to spend time with your kids after school?" Of the parents who replied, 85% said "no." Based on these results, the school officials conclude that a great majority of the parents have no difficulty spending time with their kids after school.
	- There is clear [[response bias]] in this scenario. First of all, the school is giving a questionnaire to the students about themselves for their parents, but they may never give it to their parents and just fill it out themselves. On the off-chance that the parent actually receives it, they may fill out the questionnaire to paint themselves in a positive light. The school should send the questionnaire to the parents directly instead, maintaining that their responses will remain confidential to make the parents comfortable choosing any option they want.
(b) A survey is conducted on a simple random sample of 1,000 women who recently gave birth, asking them about whether or not they smoked during pregnancy. A follow-up survey asking if the children have respiratory problems is conducted 3 years later. However, only 567 of these women are reached at the same address. The researcher reports that these 567 women are representative of all mothers.
	- It is unlikely that the women reached three years later are a completely random sample, so no.
(c) An orthopedist administers a questionnaire to 30 of his patients who do not have any joint problems and finds that 20 of them regularly go running. He concludes that running decreases the risk of joint problems.
	- There are many [[confounding variable|confounding variables]] at play in this scenario, so the orthopedist cannot jump to that conclusion. Even if the conclusion was justified, it is not representative of the entire population of humans, as the sample is just his patients.

### 1.40 Income and education in U.S. counties
The scatterplot below shows the relationship between per capita income (in thousands of dollars) and percent of population with a bachelor's degree in 3,143 counties in the US in 2010.
![[income-and-education-in-us-counties.png]]
(a) What are the explanatory and response variables?
	- The explanatory variable is the percent of population with a bachelor's degree of a county.
	- The response variable is the per capita income of that county.
(b) Describe the relationship between the two variables. Make sure to discuss unusual observations, if any.
	- The variables have a strong [[positive association]]. The data seems to be clustered at the 20 and 30% mark, though. Only two counties had a bachelor's degree population percentage of over 70%, which I did not expect.
(c) Can we conclude that having a bachelor's degree increases one's income? 
	- We cannot conclude that having a bachelor's degree increases one's income because we are doing an [[observational study]]. The values are also calculated for an entire county and not individuals.

### 1.41 Eat better, feel better?
In a public health study on the effects of consumption of fruits and vegetables on psychological well-being in young adults, participants were randomly assigned to three groups: (1) diet-as-usual, (2) an ecological momentary intervention involving text message reminders to increase their fruits and vegetable consumption plus a voucher to purchase them, or (3) a fruit and vegetable intervention in which participants were given two additional daily servings of fresh fruits and vegetables to consume on top of their normal diet. Participants were asked to take a nightly survey on their smartphones. Participants were student volunteers at the University of Otago, New Zealand. At the end of the 14-day study, only participants in the third group showed improvements to their psychological well-being across the 14-days relative to the other groups.
(a) What type of study is this?
	- This is an [[experiment]].
(b) Identify the explanatory and response variables.
	- The explanatory variable is the type of treatment group.
	- The response variable is psychological well-being.
(c) Comment on whether the results of the study can be generalized to the population.
	- The results of this study cannot be generalized to the population. The participants were all student volunteers at the University of Otago, which implies no variance in the background of individuals in the sample. Thus, they are not considered representative of the population of young adults.
(d) Comment on whether the results of the study can be used to establish causal relationships.
	- The results of the study can be used to establish causal relationships because it was an experiment with [[randomization]].
(e) A newspaper article reporting on the study states, "The results of this study provide proof that giving young adults fresh fruits and vegetables to eat can have psychological benefits, even over a brief period of time." How would you suggest revising this statement so that it can be supported by the study?
	- I would change the population to more accurately fit the sample. Instead of it being all young adults, I would say students at the University of Otago, or say that it *implies* or *shows proof* that giving young adults fresh fruits and vegetables to eat can have psychological benefits.

### 1.42 Screens, teens, and psychological well-being
In a study of three nationally representative large-scale data sets from Ireland, the United States, and the United Kingdom (n = 17,247), teenagers between the ages of 12 to 15 were asked to keep a diary of their screen time and answer questions about how they felt or acted. The answers to these questions were then used to compute a psychological well-being score. Additional data were collected and included in the analysis, such as each child's sex and age, and on the mother's education, ethnicity, psychological distress, and employment. The study concluded that there is little clear-cut evidence that screen time decreases adolescent well-being.
(a) What type of study is this?
	- This is an [[observational study]].
(b) Identify the [[explanatory variable|explanatory variables]].
	- The explanatory variables are: psychological well-being score, child sex, child age, mother's education, psychological stress, and employment.
(c) Identify the [[response variable]].
	- The response variable is adolescent well-being.
(d) Comment on whether the results of the study can be generalized to the population, and why.
	- The results of the study can be generalized to the entire population because it was conducted over a wide geographic region for three different countries for over 17,000 adolescents.
(e) Comment on whether the results of the study can be used to establish causal relationships.
	- The results of this study cannot be used to establish causal relationships because it was not an [[experiment]].

### 1.43 Stanford open policing
The Stanford Open Policing project gathers, analyzes, and releases records from traffic stops by law enforcement agencies across the United States. Their goal is to help researchers, journalists, and policymakers investigate and improve interactions between police and the public. The following is an excerpt from a summary table created based off of the data collected as part of this project.
![[stanford-open-policing.png]]
(a) What variables were collected on each individual traffic stop in order to create to the summary table above?
	- County, state, driver's race, number of traffic stops per year, % of stopped cars searched, % of stopped drivers arrested
(b) State whether each variable is numerical or categorical. If numerical, state whether it is continuous or discrete. If categorical, state whether it is ordinal or not.
	- County: Nominal categorical
	- State: Nominal categorical
	- Driver's race: Nominal categorical
	- Numer of traffic stops per year: Discrete numerical
	- % of stopped cars searched: Continuous numerical
	- % of stopped drivers arrested: Continuous numerical
(c) Suppose we wanted to evaluate whether vehicle search rates are different for drivers of different races. In this analysis, which variable would be the response variable and which variable would be the explanatory variable?
	- The explanatory variable is the driver's race. The response variable would be the search rate.

### 1.44 Space launches
The following summary table shows the number of space launches in the US by the
type of launching agency and the outcome of the launch (success or failure).
![[space-launches.png]]
(a) What variables were collected on each launch in order to create to the summary table above?
	- Private, state, or startup?
	- Year launched
	- Success or failure?
(b) State whether each variable is numerical or categorical. If numerical, state whether it is continuous or discrete. If categorical, state whether it is ordinal or not.
	- Private, state, or startup: Nominal categorical
	- Year launched: Discrete numerical
	- Success or failure: Ordinal categorical
(c) Suppose we wanted to study how the success rate of launches vary between launching agencies and over time. In this analysis, which variable would be the response variable and which variable would be the explanatory variable?
	- Explanatory variable: Year launched
	- Response variable: Success rate of launches