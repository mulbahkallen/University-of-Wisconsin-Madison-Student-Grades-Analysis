# Modules 3 Project

## Make sure that you download https://www.kaggle.com/Madgrades/uw-madison-courses data source, put it in this file and change the name to "input"
The reason is this file is too large and we cannot push all of it to github

## Company Name EDU INC - Improving Education Through Analytics

Data Provided 
	- Grades: University of Wisconsin, Madison 
Kaggle Link 
	- https://www.kaggle.com/Madgrades/uw-madison-courses


## Partners
* Mulbah Kallen
* Hui Bui

## Methods & Techologies Used

* Statistically Significant Statistics 
	> Hypothesis Testing
	> T-Tests
	> Gaussian 
	> Naive Bayes
* Python Libraries
	> Pandas
	> Seaborn
	> Scipy
	> sqlite3 
* Data Visualization 
	> TableauPublic
* Canva presentation tool


## Methodology & Basis for Project
Questions to answer:
1)Does your teacher have a statistically significant correlation with the number of As earned in a course?
2)Does time of day have a statistically significant correlation with the number of As earned in a course?
3)Do STEM fields have a statistically significantly difference in the number of As earned when compared to the humanities?
4)Does longevity in teaching improve a professors average GPA 


## Project Steps
1) Obtain University of Wisconsin-Madison data.
    a) Using provided dataset  
        i. Preview data and data format
        ii. Data is provided in CSV as well as SQL format. Partners went with different 	    initial data retrieval methods
		a. Mulbah - SQL 
		b. Huy - CSV
2) Clean data and combine datasets - Perform EDA
    a) Drop columns that don't contain data relevant to the questions
    b) Data is provided in fragmented format so use of SQL(Mulbah) Pandas(Hui)
	to join relevant data 
3) Create statistical findings and visualization based on cleaned/joined data. 
4) Summarize findings 
    a) Finalize visualizations
    b) Create powerpoint
    

## Deliverables

### Jupyter Notebooks
Jupyter Notebook containing our code

README.md file
Canva Slide presentation explaining our hypothesis tests, findings, and relevance to the company/stakeholders.

    
### Data
1)Database.sqlite3
 Contains data on 
	>Courses Offered 
	>Grade Distributions 
	>Instructors
	>Subjects	
	>Departments ect.
2)Several portions of the data were filtered and exported in order to use TableuPublic
	a.fp.csv
	b.Final_prof_num.csv
	c.dept_status.csv 

### Others

1) Canva Presentation link
https://www.canva.com/design/DADnW-gXwNg/share/preview?token=SxfynlXxfaivUex473dsow&role=EDITOR&utm_content=DADnW-gXwNg&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton

# Summary 
Through Our data analysis we were able to conclude
	1) The best time/day for a student to take a class 
	2) Model data is not strong enough for Gaussina & Bayes techniques 
	3) STEM students are not at a disadvantage to their counterparts. They achieve the 	   same GPA on average compared to all other departments 
	4) The Probability of a student achieving a certain grade based on all previoius 	   grading data 
	5) Teaching more classes over time does in fact improve a professors average GPA 
	
