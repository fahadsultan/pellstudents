
# Computer Science as a Path to Upward Mobility 

## Abstract 

Computer science jobs are among the highest paying jobs in the United States and students on Pell Grants often come from the lowest income households. In this work, we explore the relationship between the two by analyzing the median earnings of students 4 years after graduation and comparing it to annual household income of students who received Pell Grants. Using 2022 data from the College Scorecard and IPEDS, we find that Computer Science majors on Pell Grants have a significantly higher median income after 4 years of graduation when compared to median household income of grant recipients. We also find that median income of graduates from an institution is negatively correlated with the percentage of Pell Grant recipients at the institution, the size of the institution and the Carnegie Classification of the institution. There also exist key differences across regions of the United States with respect to the relationship between median earnings of Pell Grant recipients and key institutional characteristics.

Here we explore Computer Science as a path to upward mobility for students on Pell Grants. Using 2022 data from the College Scorecard and IPEDS, we analyze the median earnings of students 4 years after graduation and compare it to annual household income of students who received Pell Grants. Our results show that compared to other majors, Computer Science majors on Pell Grants have a significantly higher median income after 4 years of graduation when compared to median household income of grant repients, thus suggesting that Computer Science is very conducive to upward mobility for students. Our results also show that median income of graduates from an institution is negatively correlated with the percentage of Pell Grant recipients at the institution, the size of the institution and the Carnegie Classification of the institution. There also exist key differences across regions of the United States with respect to the relationship between median earnings of Pell Grant recipients and key institutional characteristics.

## Introduction

College education is often seen as a path to upward mobility in the United States. However, the cost of college education has been rising over the years and students from low-income households often find it difficult to afford college education. Pell Grants are a form of financial aid that are awarded to students from low-income households to help them pay for college. In this work, we study upward mobility by comparing median earnings of students 4 years after graduation and the annual income of student households who received Pell Grants. While all college degrees are equally important, some degrees are more conducive to upward mobility than others. In this report, we explore the relationship between majoring in Computer Science and upward mobility for students on Pell Grants. Here we focus on Computer Science as a major because it is one of the highest paying majors in the United States and has the most potential to be a path to upward mobility for students.

Datasets used in this work include the College Scorecard and IPEDS. The College Scorecard is a dataset that provides information on the median earnings of students 4 years after graduation, the percentage of students who received Pell Grants, the size of the institution and the Carnegie Classification of the institution. IPEDS is a dataset that provides information on the percentage of students who received Pell Grants at the institution. Both datasets 

We use data from the College Scorecard and IPEDS to analyze the median earnings of students 4 years after graduation and compare it to annual household income of students who received Pell Grants. 

The question of how characteristics of institutions affect earnings of students is also explored. Institutional characteristics we focus on here include the percentage of total student body recieving Pell Grants at the institution, the size of the institution and the Carnegie Classification of the institution. 

Lastly, we explore how the relationship between median earnings of Pell Grant recipients and key institutional characteristics varies across regions of the United States.

 institutional characteristics varies across regions of the United States The relationship between median earnings of Pell Grant recipients and key




## Data 

The data used in this work comes from the College Scorecard and Integrated Postsecondary Education Data System (IPEDS). Details of the data are as follows:

### IPEDS 

Integrated Postsecondary Education Data System (IPEDS) is a comprehensive data collection program managed by the National Center for Education Statistics (NCES). It gathers information from every college, university, and technical and vocational institution that participates in federal student financial aid programs in the United States. IPEDS data encompasses a wide range of metrics, including enrollment numbers, graduation rates, financial aid distribution, faculty qualifications, and institutional finances. This data is critical for policymakers, researchers, and the public, as it provides a detailed view of the landscape of higher education, facilitating informed decisions and analyses regarding the accessibility, quality, and performance of educational institutions nationwide.

Here we use IPEDS for institutions and 

We also use \texttt{UPGRNTP} \textit{``Percent of undergraduate students awarded Pell grants''} from the ``Student Financial Aid and Net Price'' survey table ``Student financial aid and net price: 2021-22''

### College Scorecard

The College Scorecard provides data at the institution-level and data by field of study. It was launched in 2015 with the primary goal of providing granular information on the cost and value of higher education focusing on tuition, graduation rate, employment rate, loans and student debt. It is maintained by the US Department of Education and updated regularly. Here in this study we use the variables \texttt{variable=EARN_PELL_WNE_MDN_4YR} with descriptions ``Median earnings of graduates who received a Pell Grant and were working and not enrolled 4 year after completing" and \texttt{variable=EARN_NOPELL_WNE_MDN_4YR}  and "Median earnings of graduates who did not receive a Pell Grant and were working and not enrolled 4 year after completing"

cost, graduation rate, employment rate, loans. 


The College Scorecard provides data at the institution-level and data by field of study. It is maintained by the US Department of Education and updated annually. The data used in this work is from the 2022 College Scorecard. The College Scorecard provides information on the median earnings of students 4 years after graduation, the percentage of students who received Pell Grants, the size of the institution and the Carnegie Classification of the institution.

is a dataset maintained by the US Department of Education that provides information on the median earnings of students 4 years after graduation, the percentage of students who received Pell Grants, the size of the institution and the Carnegie Classification of the institution.

## Results 

**Computer Science vs. Other Areas of Study** 

When comparing median earnings of students 4 years after graduation between students who majored in Computer Science and other areas of study, we find that students who majored in Computer Science have a significantly higher median income after 4 years of graduation. 

These findings are consistent with previous studies that have shown that Computer Science is one of the highest paying majors in the United States and here serve as a good sanity check for our analysis and data.

#### Earnings of Pell Grant Recipients vs. Others 

Figure~\ref{fig:mobility} also shows that the median earnings of low-income students who received Pell Grants (in orange) compared to  median earnings of students who did not receive Pell Grants (in blue). This is shown for both students who majored in Computer Science and other areas of study (x-axis). 

While the median earnings of students who received Pell Grants is lower than students who did not receive Pell Grants, in Computer Science and others, in neither case is this difference statistically significant. 

In contrast, the median earnings of students on Pell Grants in Computer Science vs. students on Pell Grants (boxplot 2 and 4 from the left) in other areas of study is statistically significant. 

Median earnings of students who did not receive Pell Grants in Computer Science vs. students who did not receive Pell Grants in other areas of study was also found to be statistically significant.

This suggests that students who received Pell Grants are less likely to experience upward mobility compared to students who did not receive Pell Grants.

Altogether, the result of these statistical tests suggest that Pell Grant recipients have similar median earnings as non-Pell Grant recipients in both Computer Science and other areas of study. 

### Upward Mobility: Student Earnings vs. Household Income

To study upward mobility, we compare the median earnings of students 4 years after graduation to the annual household income of students who received Pell Grants.

For household income, we use Pell Grant Statistics from the Education Data Initiative~\cite{} which provides information on the annual household income of students who received Pell Grants. 

Education Data Initiative report that 51% of Pell Grant recipients come from families with an annual household income of less than $20,000. This is shown as a dotted line in Figure~\ref{fig:mobility}. They also report that 90% of Pell Grant recipients come from families with an annual household income of less than $50,000. This is shown as a dashed line in Figure~\ref{fig:mobility}. Finally, less than 6% of Pell Grant recipients come from families with an annual household income of more than $60,000. This is shown as a solid line in Figure~\ref{fig:mobility}.

Using these household income statistics, it can be seen in the Figure~\ref{fig:mobility} that the median earnings of students in Computer 4 years after graduation is well above the annual household income of students 94% of Pell Grant recipients i.e. \$60,000.

In contrast, the median earnings of students in other areas of study is significantly higher for 50% of students who come from households with an annual income of less than \$20,000.

In all, while college education offers a path to upward mobility for atleast 51% of Pell Grant recipients, the path to upward mobility is more pronounced for students who majored in Computer Science.

## Influence of Institutional Characteristics on Student Earnings

We also explore how institutional characteristics affect the median earnings of students 4 years after graduation. 

Here we focus on three key institutional characteristics: 

Institutional characteristics we focus on here include the percentage of total student body recieving Pell Grants at the institution, the size of the institution and the Carnegie Classification of the institution.

The relationship between median earnings of Pell Grant recipients and all three institutional characteristics listed above is shown in Figure~\ref{fig:institutional}.

Our results show that the median income of graduates from an institution is positively correlated with the size of the institution. That is, the larger the institution, generally the higher the median income of graduates from the institution. The Pearson and Spearman correlation coefficient between median earnings of Pell Grant recipients and the percentage of Pell Grant recipients at the institution are \textcolor{red}{Insert} and \textcolor{red}{Insert} respectively. 

The size of an institution is a proxy for many other characteristics of an institute. Larger institutions, for instance, tend to be more research oriented and are also often publically funded. Smaller institutions, on the other hand, tend to be more teaching oriented and are often private. This can also been seen in ~\ref{fig:institutional} with respect to the Carnegie Classification of the institution. That is, Doctoral Universities tend to be larger institutions and also have higher median earnings of Pell Grant recipients compared Baccalaureate or Associates Colleges. The median earnings of Pell Grant recipients in Computer Science are given in Table~\ref{tab:institutional}.

Another key institution characteristic we explore is the percentage of the total student body that are Pell Grant recipients. This is the x-axis in Figure~\ref{fig:institutional}. Our results show that the median income of graduates from an institution is negatively correlated with the percentage of Pell Grant recipients at the institution. That is, the higher the percentage of Pell Grant recipients at an institution, the lower the median income of graduates from the institution. The Pearson and Spearman correlation

It can also be seen from Figure~\ref{fig:institutional} that smaller institutions that are often Associates Colleges, Baccaleurate Colleges or Masters Colleges and Universities tend to have a higher percentage of their student body that recieved Pell Grants. Given the fact that Pell Grants are only given to students from low-income households, this finding suggests that students that come from lower income households are more likely to attend smaller institutions and undergo relatively lower mobility compared to students from higher income households at larger institutions.

~Figure~\ref{fig:pct_on_pell} casts more light on this relationship. Here we round the percentage of Pell Grant recipients at an institution to the nearest 5% and aggregate the median earnings of Pell Grant recipients for each percentage. The results show that this negative relationship between earnings and percentage of Pell Grant recipients at an institution holds true for both Computer Science and other areas of study. Computer Science Pell Recipients however for all percentages have higher median earnings compared to other areas of study. 

The correlation coefficients between median earnings of Pell Grant recipients and the percentage of Pell Grant recipients at the institution for Computer Science and other areas of study are \textcolor{red}{Insert} and \textcolor{red}{Insert} respectively.

Figure~\ref{fig:pct_on_pell} adds to our understanding of the relationship between median earnings of Pell Grant recipients for Computer Science and other areas of study. It reinforces the conclusion from Figure~\ref{fig:mobility} that Computer Science is more conducive to upward mobility for students on Pell Grants compared to other areas of study. The added insight here is upward mobility is not uniform and smaller, more teaching oriented institutions are less conducive to upward mobility for students on Pell Grants compared to larger, more research oriented institutions.

## Regional Differences 

Expanding further on the relationship between median earnings of Pell Grant recipients and key institutional characteristics, we explore how this relationship varies across regions of the United States.

Figure~\ref{fig:regions} shows the relationship between median earnings of Pell Grant recipients and the percentage of Pell Grant recipients at the institution for each region of the United States. The regions, as defined by the US Census Bureau, and their breakdown with respect to states is given in Table~\ref{tab:regions}.

Our results show that the relationship between median earnings of Pell Grant recipients and the percentage of Pell Grant recipients is negative or at best neutral across all regions of the United States. 

One key observation is that institutions with high percentages of Pell Grant recipients are geographically not uniformly distributed across the United States. For instance, New England, Plains, Far West and Great Lakes regions of the country have no institutions with a percentage of Pell Grant recipients greater than 60%. In stark contrast, all institutions in the region labeled "Outlying Areas" that include Virgin Islands, Puerto Rico, Guam among others have a percentage of Pell Grant recipients of greater or equal to 60%.

Our results also show that despite the existence of institutions with high percentages of Pell Grant recipients and negative or neutral relationship between median earnings of Pell Grant recipients and the percentage of Pell Grant recipients, for most regions of the United States, the median income is greater than $60,000, which is the annual household income of 94% of Pell Grant recipients. This yet again reinforces the argument for Computer Science as providing a path to upward mobility for students on Pell Grants.

## Conclusion 

From our analysis of earnings, household income and institutional characteristics, we can conclude the following:

1. Computer Science is a path to upward mobility for students on Pell Grants. Students who majored in Computer Science have a significantly higher median income after 4 years of graduation compared to students who majored in other areas of study.

2. The median earnings of students who received Pell Grants and majored in Computer Science is significantly higher than the annual household income of \textcolor{red}{90%} of students who received Pell Grants. This suggests that Computer Science is very conducive to upward mobility for students on Pell Grants, more so than other areas of study.

3. The median earnings of students who received Pell Grants is similar to students who did not receive Pell Grants in both Computer Science and other areas of study. This suggests that Pell Grant recipients have similar median earnings as non-Pell Grant recipients in both Computer Science and other areas of study.

4. Our results show that the larger and more research oriented an institution, the higher the median income of Pell Grant recipients from the institution. In contrast, the smaller and more teaching oriented an institution, the lower the median income of Pell Grant recipients from the institution.

 institution the higher the median income of graduates from the institution. This relationship holds true for both Computer Science and other areas of study.

5. The median income of graduates from an institution is negatively correlated with the percentage of Pell Grant recipients at the institution. Institutions with more Pell Grant recipients also tend to be smaller and more teaching oriented. Institutions where greater than 60% of students are Pell Grant recipients are geographically not uniformly distributed across the United States. 

6. The relationship between median earnings of Pell Grant recipients and the percentage of Pell Grant recipients at the institution is negative or at best neutral across all regions of the United States. 

The relationship between median earnings of Pell Grant recipients and the percentage of Pell Grant recipients at the institution is negative or at best neutral across all regions of the United States.

## Related Work 


A review of the literature reveals a number of studies focused on college as a path to upward mobility, particularly for low-income and Pell-eligible students~\cite{klor2019university, romano2017community}. These studies show that more than half the students raised in households in the two lowest-income quintiles manage to reach the two highest quintiles by their 30s. Furthermore, \cite{klor2019university}~shows that college completion, field of study, spending levels and selectivity are the factors most closely associated with upward mobility. \cite{romano2017community} shows that it pays to go to the community college both in terms of lifetime earnings and rates of return on investment. \cite{chetty2017mobility} shows confirms that community colleges score high on access but low on student success (completion).

Other work exists which uses IPEDS and College Scorecard data to study the graduation rates of Pell Grant recipients~\cite{yang2021which, joy2017college}. These studies focuse on factors such as included GPA by the end of the first academic year, the number of STEM and English courses taken by the end of the second academic year, as well as whether the students successfully passed the courses, etc. can predict students’ persistence and graduation status. The results of these studies that Pell recipients face more challenges to graduate and also emphasized the critical importance of STEM and English courses for all students.

~\cite{narayanan2018upward} is the only study we found focusing on upward mobility and graduation rates specifically for Computer Science students. The focus of this idea is however on a cohort-based, three-year computer science bachelor’s degree program that increased graduation rates of traditionally underrepresented computer science students and a clear pathway for upward socio-economic mobility into
the high-paying technology industry. 

Our work here extends the state of the art by focusing on studying the impact and efficacy of specifically existing Computer Science programs in lifting students on Pell Grants out of bottom income quintiles. We also extend the body of work that studies the relationship between institutional characteristics and student earnings in the narrow focused context of Computer Science.