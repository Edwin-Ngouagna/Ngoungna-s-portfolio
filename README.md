# Ngouagna-s-portfolio
<p><b>##Analytics porfolio<b><p>
#Project 1: IBM SPSS Fundamentals of data analysis: In this project, I organised and taught data analysis in IBM SPSS beginning from basic
definitions through non-parametric to parametric tests and survival analysis.(https://www.youtube.com/channel/UC_sdb3ymcFQE9yePQUBg-Iw/featured)

#Project 2:  Here, I prepared successive video clips in which I demonstrated in a succinct manner how to analyse heathcare data in Microsoft excel ranging from patient attendance through number admitted to financial analysis, calculations and visualizations.(https://www.youtube.com/channel/UC_sdb3ymcFQE9yePQUBg-Iw/featured)

#Project 3: https://github.com/Edwin-Ngouagna/Stats-in-R
Intestinal parasitic infection data cleaning and analysis in R ~ Test of asssociation.  In this project, I analyzed the dataset on the topic “INTESTINAL PARASITIIC INFECTION AND DETERMINANT FACTORS AMONG HIV POSITIVE PATIENTS ATTENDING A LOCAL HOSPITAL” The name of the hospital hasn’t been disclosed for ethical reasons. In this study, the researchers sought to know the:

Prevalence of Intestinal Parasitic Infection among HIV positive patients attending the hospital
Identify the different types of intestinal parasites infesting HIV positive patients attending the hospital
Outline the determinant factors of Intestinal parasitic infections among HIV positive patients attending the hospital (Association between demographic factors and prevalence of parasites)
Outline the significant risk factors and the odds of being infested by a parasite amongst the participants.
Hypothesis Ho – There are no intestinal parasites amongst HIV patients

There is no significant relationship between demographic factors and presence of intestinal parasites
There is no significant relationship between risk factors and presence of intestinal parasites
The odds of getting infested by an intestinal parasites is 1. Analysis The data was analyzed using R statistical software version 4.2.1. First we imported the data into R, Missing value analysis Assign labels to dummy variables Data exploration to fully understand the data Get the Demographic characters frequencies Analyzed prevalence of intestinal parasites Got the frequencies of the different parasites I ran the crosstabs and chi square test to see the demographic factors that were significantly associated with the presence of the parasites I ran a second crosstab and chi square test to determine any significant association between risk factors and the presence of the parasites. Lastly, I ran a logistic regression model using all factors that were significant from the chi square test to the odds of a patient getting infestation with a parasite.
#Project 4:https://github.com/Edwin-Ngouagna/Georgia-crime-data-analyzed
  In this project, I analyzed the Georgia crime dataset downloaded from Georgia - Uniform Crime Reporting – FBI (https://ucr.fbi.gov/crime-in-the-u.s/2018/crime-in-the-u.s.-2018/tables/table-8/table-8-state-cuts/georgia.xls) Note that the dataset is subject to updates, the results you will have may not be exactly what I present here. In analysis, I sought to know the:

If there is a linear relationship between population (specifically where population ≤150,000) and murder rate in Georgia.
Hypothesis Ho – There are no significant linear relationship between population (specifically where population ≤150,000) and murder rate in Georgia.

Analysis The data was analyzed using R statistical software version 4.2.1. First we imported the data into R, Missing value analysis Filter the data Rename some variables (dplyr package) Data exploration to fully understand the data (glimpse using the EpiR package) Check for normality (Shapiro Wilk test and histograms) Check for linearity Data transformation using the mutate function Simple linear regression Interpretation
