## Employee Attrition Dataset — Data Dictionary				
                
Column Name	Category / Data Type	Definition	Expected Values / Format	Analytical Handling
Age	Demographic / Whole Number	Employee's age in years	Numeric	Used for age-group and attrition analysis
Attrition	Outcome / Text	Indicates whether the employee left the company	Yes / No	Primary outcome variable
BusinessTravel	Employment / Text	Frequency of business travel	Non-Travel, Travel_Rarely, Travel_Frequently	Used to compare attrition by travel frequency
DailyRate	Compensation / Whole Number	Daily rate value associated with the employee	Numeric	Used for exploratory analysis
Department	Employment / Text	Department where the employee works	Human Resources, Research & Development, Sales	Used for department-level comparisons
DistanceFromHome	Demographic / Whole Number	Distance from home to work, in miles	Numeric	Used to analyze commuting distance and attrition
Education	Demographic / Ordinal Number	Employee's education level	1–5	Converted into Education_Label
EducationField	Demographic / Text	Employee's field of education	Life Sciences, Medical, Marketing, Technical Degree, Human Resources, Other	Used to compare attrition by education field
EmployeeCount	Data Quality / Whole Number	Employee count field included in the dataset	Expected constant value: 1	Checked for variation; not used as a main KPI
EmployeeNumber	Identifier / Whole Number	Unique employee identification number	Numeric identifier	Used for record counts and duplicate checks
EnvironmentSatisfaction	Satisfaction / Ordinal Number	Employee's satisfaction with the work environment	1–4	Converted into EnvironmentSatisfaction_Label
Gender	Demographic / Text	Employee's recorded gender	Female, Male	Used for descriptive comparisons
HourlyRate	Compensation / Whole Number	Hourly rate value associated with the employee	Numeric	Used for exploratory analysis
JobInvolvement	Satisfaction / Ordinal Number	Employee's level of job involvement	1–4	Converted into JobInvolvement_Label
JobLevel	Employment / Ordinal Number	Employee's job level within the organization	1–5	Used to compare attrition by job level
JobRole	Employment / Text	Employee's job role	Nine job-role categories	Used for job-role attrition analysis
JobSatisfaction	Satisfaction / Ordinal Number	Employee's job satisfaction level	1–4	Converted into JobSatisfaction_Label
MaritalStatus	Demographic / Text	Employee's marital status	Single, Married, Divorced	Used for descriptive comparisons
MonthlyIncome	Compensation / Whole Number	Employee's monthly income	Numeric	Used to calculate average income and Income_Band
MonthlyRate	Compensation / Whole Number	Monthly rate value associated with the employee	Numeric	Used for exploratory analysis
NumCompaniesWorked	Employment / Whole Number	Number of companies the employee has worked for	Numeric	Used to explore work history and attrition
Over18	Demographic / Text	Indicates whether the employee is over 18	Expected value: Y	Checked for consistency; limited analytical use
OverTime	Employment / Text	Indicates whether the employee works overtime	Yes / No	Used to compare attrition rates for overtime and non-overtime employees
PercentSalaryHike	Compensation / Whole Number	Percentage salary increase	Numeric percentage value	Used for exploratory analysis
PerformanceRating	Performance / Ordinal Number	Employee's performance rating	1–4	Converted into PerformanceRating_Label
RelationshipSatisfaction	Satisfaction / Ordinal Number	Employee's satisfaction with workplace relationships	1–4	Converted into RelationshipSatisfaction_Label
StandardHours	Data Quality / Whole Number	Standard-hours field included in the dataset	Expected constant value: 80	Checked for variation; not used as a main KPI
StockOptionLevel	Compensation / Ordinal Number	Employee's stock option level	0–3	Used for exploratory analysis
TotalWorkingYears	Employment / Whole Number	Total years of work experience	Numeric	Used to compare experience and attrition
TrainingTimesLastYear	Training / Whole Number	Number of training sessions attended in the previous year	Numeric	Used to explore training and attrition
WorkLifeBalance	Satisfaction / Ordinal Number	Employee's work-life balance rating	1–4	Converted into WorkLifeBalance_Label
YearsAtCompany	Employment / Whole Number	Number of years the employee has worked at the company	Numeric	Used for tenure analysis
YearsInCurrentRole	Employment / Whole Number	Number of years in the current role	Numeric	Used to compare role tenure by attrition status
YearsSinceLastPromotion	Employment / Whole Number	Years since the employee's last promotion	Numeric	Used to explore promotion history and attrition
YearsWithCurrManager	Employment / Whole Number	Number of years working with the current manager	Numeric	Used to compare manager tenure by attrition status
Education_Label	Derived / Text	Text description of the education level	Below College, College, Bachelor, Master, Doctor	Used in readable summaries and PivotTables
EnvironmentSatisfaction_Label	Derived / Text	Text description of environment satisfaction	Low, Medium, High, Very High	Used in satisfaction comparisons
JobInvolvement_Label	Derived / Text	Text description of job involvement	Low, Medium, High, Very High	Used in involvement comparisons
JobSatisfaction_Label	Derived / Text	Text description of job satisfaction	Low, Medium, High, Very High	Used in satisfaction summaries
PerformanceRating_Label	Derived / Text	Text description of performance rating	Low, Good, Excellent, Outstanding	Used in readable performance summaries
RelationshipSatisfaction_Label	Derived / Text	Text description of relationship satisfaction	Low, Medium, High, Very High	Used in satisfaction comparisons
WorkLifeBalance_Label	Derived / Text	Text description of work-life balance rating	Bad, Good, Better, Best	Used in work-life balance analysis
Attrition_Flag	Derived / Whole Number	Numeric version of the attrition outcome	1 = Yes; 0 = No	Used for numeric calculations where appropriate
Income_Band	Derived / Text	Groups employees by monthly income	0–3,000; 3,001–6,000; 6,001–10,000; 10,001+	Used to compare attrition across income ranges
Distance_Band	Derived / Text	Groups employees by distance from home	0–5 miles; 6–10 miles; 11–15 miles; 16+ miles	Used to compare attrition across commuting distances
Tenure_Band	Derived / Text	Groups employees by years at the company	0–1 years; 2–5 years; 6–10 years; 11+ years	Used to compare attrition by company tenure


