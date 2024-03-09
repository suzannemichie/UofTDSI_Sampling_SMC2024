# Final Assessment
## Module 5: Sampling
## Submitted by Suzanne M Chalambalacis 9-Mar-2024

1. **For the following survey, describe briefly the _target population_, the _sampling frame_ and the _frame population_, and the sampled population (or the _study population_). Discuss possible problems/issues with the sampling frames and the survey data in terms of coverage error and nonresponse bias:**  
   A survey conducted by the Dean of Mathematics at University of Waterloo (UW) indicates that about 25% of UW Computer Science graduates went to positions in the United States. Data were collected through questionnaires emailed to graduates from the past 5 years.

   >**Answer:**
   >
   > Target Population: University of Waterloo (UW) Computer Science graduates
   > 
   > Sampling Frame: contactable UW Computer Science graduates from the past 5 years with active emails
   > 
   > Frame Population: UW Computer Science graduates from the past 5 years who are contactable by email
   > 
   > Sampled Population (or Study Population): UW Computer Science alum who actually respond to the emailed questionnaires
   > 
   > Possible Problems/Issues:
   > 
   > Coverage Error: the sampling frame does not include all UT Comp Sci grads from the past 5 years and would not cover those with missing emails, or outdated emails, which could lead to undercoverage and/or result in a biased estimation of the percentage of graduates in the United States.
   >    
   > Nonresponse Bias: Low Response Rate: If a significant portion of the sampled population does not respond to the survey, there may be nonresponse bias.
   > 
   > Selective Nonresponse: Respondents and non-respondents may differ systematically e.g. if succesful grads are more or less likely to respond, it could introduce bias.

2. **For the following survey, describe briefly the _target population_, the _sampling frame_ and the _frame population_, and the _sampled population_ (or the _study population_). Discuss possible problems/issues with the sampling frames and the survey data in terms of coverage error and nonresponse bias:**  
   A pilot survey for The Canadian Longitudinal Study on Aging (CLSA) was conducted in the province of Ontario. The survey intended to cover the general population of the province with age 45–80 (inclusive). Survey questionnaires were sent to selected individuals through regular mail. Individuals and their mailing addresses were selected and obtained from the Provincial Health Records.

   >**Answer:**
   >
   > Target Population: individuals aged 45 to 80 in Ontario
   > 
   > Sampling Frame: basis of the list are individuals and their mailing addresses obtained from the Provincial Health Records
   > 
   > Frame Population: individuals aged 45 to 80 in Ontario whose information is available in the Provincial Health Records, including their mailing addresses
   > 
   > Sampled Population (or Study Population): individuals who received the survey questionnaires via mail
   > 
   > Possible Problems/Issues:
   > 
   > Coverage Error: the sampling frame relies solely on Provincial Health Records, individuals who do not have records or are not included in the health system may be excluded, leading to under coverage.
   >    
   > Nonresponse Bias: Low Response Rate: the survey depends only on those who are contactable by mail and willing to respond.
   > 
   > Health Record Limitations: only those with health records and are mailable are being surveyed, exluding those that may not access health on a regular basis.
   > 
   > Mailed surveys: only those who are contactable by mail are being surveyed; additionally, not everyone will respond to a mailed survey leading to underrepresentation.

3. **For the following survey, describe briefly the _target population_, the _sampling frame_, the _sampling unit_, and _observation unit_. Discuss any possible sources of selection bias or inaccuracy of responses:**  
   The December 2003 issue of PC World reported the results from a survey of over 32,000 subscribers asking about reliability and service for personal computers and other electronic equipment. The magazine “invited subscribers to take the Web-based survey from April 1 through June 30, 2003” and received 32,051 responses. Survey respondents were entered in a drawing to win prizes. They reported that 46% of desktop PCs had at least one significant malfunction.

   >**Answer:**
   >
   > Target Population: subscribers of PC World magazine
   > 
   > Sampling Frame: subscribers of PC World magazine who had an active subscription at that time
   > 
   > Sampling Unit: individual subscribers of PC World magazine
   > 
   > Observation Unit: individual personal computer or electronic equipment reported by each respondent
   > 
   > Possible Problems/Issues:
   > 
   > Self-Selection/Volunteer Bias: participation in the survey was voluntary, and respondents may have different characteristics than those who chose not to respond like strong opinions.
   >    
   > Sampling Frame Limitations: survey is limited to PC World subscribers, excluding individuals who are not subscribers that could also have valuable insights into the reliability and service of personal computers.

4. **Consider a situation where a population’s size is _N_ = 3 and the population **U** is {1, 2, 3}. There are seven possible candidate samples:**  
   $$S_1 = \{1\}, \; S_2 = \{2\}, \; S_3 = \{3\}, \; S_4 = \{1,2\}, \; S_5 = \{1,3\}, \; S_6 = \{2,3\}, \; S_7 = \{1,2,3\}.$$  
   Note that S7 = U, which corresponds to a census. Here are two sampling designs:  
   $$P(S_k) = ⅙, k = 1, 2,..., 6 and P(S_7) = 0.$$
   $$P(S_k) = ⅓, k = 4, 5, 6 and P(S_k) = 0, k = 1,2,3,7.$$
   Let $πi = P(i ∈ S)$ be the probability that unit $i$ from $U$ is included in the sample. For each of the two probability sampling designs, calculate the inclusion probabilities $π1$, $π2$, and $π3$.

   >**Answer:**
   >
   > First sampling inclusion probabilities calculations:
   >
   > $π_1$ = $P(1 ∈ S)$ = $P(S_1)$ + $P(S_4)$ + $P(S_5)$ + $P(S_7)$ = ⅙ + ⅙ + ⅙ + 0 = ½
   > 
   > $π_2$ = $P(2 ∈ S)$ = $P(S_2)$ + $P(S_4)$ + $P(S_6)$ + $P(S_7)$ = ⅙ + ⅙ + ⅙ + 0 = ½
   > 
   > $π_3$ = $P(3 ∈ S)$ = $P(S_3)$ + $P(S_5)$ + $P(S_6)$  + $P(S_7)$ = ⅙ + ⅙ + ⅙ + 0 = ½
   > 
   > 
   > Second sampling inclusion probabilities calculations:
   >
   > $π_1$ = $P(1 ∈ S)$ = $P(S_4)$ + $P(S_5)$ + $P(S_6)$ = ⅓ + ⅓ + ⅓ = 1
   > 
   > $π_2$ = $P(2 ∈ S)$ = $P(S_4)$ + $P(S_5)$ + $P(S_6)$ = ⅓ + ⅓ + ⅓ = 1
   > 
   > $π_3$ = $P(3 ∈ S)$ = $P(S_5)$ + $P(S_6)$ = ⅓ + ⅓ = ⅔
   > 
   > For the first design, each unit has an inclusion probability of ½, while in the second the inclusion probabilities vary: $π_1$ = $π_2$ = 1 and $π_3$ = ⅔
   > 

5. Frankovic (2008) reported that in 1970, a poll conducted by the Harris organization for Virginia Slims, a brand of cigarettes marketed primarily to women, had the following question:
   **“There won’t be a woman president of the U.S. for a long time and that’s probably just as well.”**
Sixty-seven percent of female respondents agreed with the statement. Critique this question.

   >**Answer:**
   >
   > The statement within the question already introduces a bias by assuming that there won't be a woman president for a long time and that it's "probably just as well". This framing could influence respondents' answers, as it suggests a certain viewpoint and may lead participants to agree with the statement rather than disagree.

6. **The following questions, quoted in Kinsley (1981), were from a survey conducted by Cambridge Reports, Inc., and financed by Union Carbide Corporation. Critique these questions:**  

   > a. Some people say that granting companies tax credits for the taxes they actually pay to foreign nations could increase these companies’ international competitiveness. If you knew for a fact that the tax credits for taxes paid to foreign countries would increase the money available to US companies to expand and modernize their plants and create more jobs, would you favor or oppose such a tax policy?  
   >b. Do you favor or oppose changing environmental regulations so that while they still protect the public, they cost American businesses less and lower product costs?

   >**Answer:**
   > 
   > a. The question uses leading language by framing the tax credit proposal in a positive light and suggests (without eveidence) that potential benefits would increase international competitiveness by not paying taxes to foreign nations. The question assumes that respondents have detailed knowledge about the potential consequences of tax credits for taxes paid to foreign countries. It also assumes the response is binary by suggesting a scale (yes/no), even though reponses could be variable.
   > 
   > b. The question uses loaded terms like "cost American businesses less" and "lower product costs," which may bias responses. It also implies that changing environmental regulations would inherently lead to cost reduction without specifying how.

7. **Observe Figure 3.2 in Salganik (2018).**  
   ![Image](./Picture1.png)
   > a. Describe a situation in which these errors cancel out.  
   > b. Describe a situation in which these errors compound.

   >**Answer:**
   > 
   > a. 
   > 
   > Scenario: a survey is conducted on the satisfaction of residents in a small, closed community. In this case:
   > Target Population: All residents of the community.
   > 
   > Frame Population: A comprehensive and up-to-date list of all residents to ensure complete coverage.
   > 
   > Sample Population: A random sample drawn from the frame population.
   > 
   > Respondents: Everyone sampled responsds so there is no non-response error :)
   > 
   > In this ideal scenario, the coverage error is minimized because the frame population accurately represents the target population, sampling error is reduced as a representative sample is obtained, and non-response error is eliminated as all respond to the survey. As a result, coverage errror, sampling error, and non-response error cancel out.
   > 
   > b.
   > 
   > Scenario: a national survey on a specific health issue using telephone interviews.
   > 
   > Target Population: All individuals in the nation with the specific health condition.
   > 
   > Coverage Error: Only those with and active landline telephone number is surveyed, excluding individuals who rely solely on mobile phones or who do not have a phone at all. This would introduce coverage error as part of the target population is not represented in the frame population.
   > 
   > Frame Population: The frame population consists only of those with and active landline telephone number, leading to coverage error.
   > 
   > Sample Population: A random sample is drawn from the frame population, but due to the coverage error, it may not be representative of the entire target population.
   > 
   > Non-Response Error: A significant portion of those contacted refuse to participate, leading to a large non-response error.
   > 
   > Respondents: The respondents may not be a true representation of the entire target population due to coverage error and non-response error.
   > 
   > In this situation, coverage error, sampling error, and non-response error compound, making it challenging to generalize the survey findings to the entire target population.


8. **Let N = 6 and n = 3. For purposes of studying sampling distributions, assume that all population values are known.**  

   $y_1 = 90, \; y_2 = 110, \; y_3 = 150, \; y_4 = 129, \; y_5 = 194, \; y_6 = 200.$

   We are interested in the population mean. Two sampling plans are proposed.

   | **Sample Number** | **Sample, S** | **P(S)** | **Sample Number** | **Sample, S** | **P(S)** |
   | :-----------: | :-------: | :--: | :-----------: | :-------: | :--: |
   |       1       | {1, 3, 5} |  ⅛   |       1       | {1, 4, 6} |  ¼   |
   |       2       | {1, 3, 6} |  ⅛   |       2       | {2, 3, 6} |  ¼   |
   |       3       | {1, 4, 5} |  ⅛   |       3       | {1, 3, 5} |  ½   |
   |       4       | {1, 4, 6} |  ⅛   |               |           |      |
   |       5       | {2, 3, 5} |  ⅛   |               |           |      |
   |       6       | {2, 3, 6} |  ⅛   |               |           |      |
   |       7       | {2, 4, 5} |  ⅛   |               |           |      |
   |       8       | {2, 4, 6} |  ⅛   |               |           |      |

   > a. What is the value of the sample mean?  
   > b. Let y be the mean of the sample values. For each sampling plan, find E(y) and Var(y).  
   > c. Which sampling plan do you think is better? Why?

   >**Answer:**
   > 
   > a. Value of Sample Means
   > 
   > Sampling Plan 1: $yˉ_1 = (90+150+194)/3 = 144.67$
   > 
   > Sampling Plan 2: $yˉ_2 = (90+129+200)/3 = 139.67$
   > 
   > c. The better sampling plan is the one with a smaller variance, as it indicates less variability in the sample mean.

9. **Discuss whether an SRS would be appropriate for the following situations. What other designs might be used?**  
   > a. You want to estimate the percentage of topics in a medical website that have errors.  
   > b. A county election official wants to assess the accuracy of the machine that counts the ballots by taking a sample of the paper ballots and comparing the estimated vote tallies for candidates from the sample to the machine counts.

   >**Answer:**
   > 
   > a. A Simple Random Sample (SRS) might not be the most appropriate design in this situation because errors on a medical website could be distributed unevenly across different topics and an SRS may not ensure a representative sample of error-prone topics. A Stratified Random Sample where the medical website is divided into strata by topics (e.g., cardiology, neurology, etc.), and then randomly sampled within each strata may work better as it would help ensure representation for each medical topic.
   > 
   > b. A SRS could be used for this scenario but if the accuracy of the machine varies by location, an SRS may not capture these variations. A Stratified Random Sample by precincts/locations where samples are randomly select may ensure better representation from different areas and helps assess variations in accuracy.
   > 
10. Suppose that a city has 90,000 dwelling units, of which 35,000 are houses, 45,000 are apartments, and 10,000 are condominiums. You believe that the mean electricity usage is about twice as much for houses as for apartments or condominiums, and that the standard deviation is proportional to the mean so that S1 = 2S2 = 2S3. **How would you allocate a stratified sample of 900 observations if you wanted to estimate the mean electricity consumption for all households in the city?**

   >**Answer:**
   > 
   > A stratified sampling approach ensures that the sample is representative of the different types of dwelling units in the city, and takes into account the proportion and standard deviation relationships among the strata.
   > 
   > **Step 1: Calculate Proportion of Each Stratum**
   > 
   > $P_1$ = Number of Houses/Total Number of dwellings = 35,000/90,000 = 0.389	(38.89%)
   > 
   > $P_2$ = Number of Apartments/Total Number of dwellings = 45,000/90,000 = 0.500 (50.00%)
   > 
   > $P_3$ = Number of Condominiums/Total Number of dwellings = 10,000/90,000 = 0.111 (11.11%)
   > 
   > **Step 2: Allocate Sample Sizes**
   > 
   > Houses: $n_1$ = $P_1$ x 900 ≈ 350 observations
   > 
   > Apartments: $n_2$ = $P_2$ x 900 = 450 observations
   > 
   > Condominiums: $n_3$ = $P_3$ x 900 ≈ 100 observations
   > 
   > **Step 3: Allocate the Standard Deviation**
   > 
   > Standard Deviation Houses: $S_1$ = 2 $S_2$ = 2 $S_3$
   > 
   > Standard Deviation Apartments: $S_2$ = $S_2$
   > 
   > Standard Deviation Condominiums: $S_3$ = $S_2$
   > 

11. **What stratification variable(s) would you use for each of the following situations:**
    > a. A political poll to estimate the percentage of registered voters in Arizona that approve of the governor’s performance.  
    > b. A sample of public libraries in California to study the availability of computer resources, and the per capita expenditures.  
    > c. An aerial survey to estimate the number of walrus in the pack ice near Alaska between 173 degrees East and 154 degrees West longitude.

   >**Answer:**
   > 
   > a. Stratification Variable: Political/Party Affiliation; This would ensure that the sample includes a proportional representation of voters from each political affiliation.
   > 
   > b. Stratification Variables: Library Size, Location (rural, urban), Funding Type (public, private, mized); allows for a comprehensive examination of factors influencing computer resource availability and per capita expenditures across the state. 
   > 
   > c. Stratification Variable: Geographic Region; Stratifying the survey by geographic region to account for potential variations in walrus distribution across the survey area

12. A city council of a small city wants to know the proportion of eligible voters that oppose having an incinerator of Phoenix garbage opened just outside of the city limits. They randomly select 100 residential numbers from the city’s telephone book that contains 3,000 such numbers. Each selected residence is then called and asked for (a) the total number of eligible voters and (b) the number of voters opposed to the incinerator. A total of 157 voters were surveyed; of these, 23 refused to answer the question. Of the remaining 134 voters, 112 opposed the incinerator, so the council estimates the proportion by with: p = 112/134 = 0.83582 and V(p) = 0.83582(1 − 0.83582)/134 = 0.00102. **Are these estimates valid? Why, or why not?**

   >**Answer:**
   > 
   > The method used for sampling may not be valid due to bias introduced by using only residents listed it the telephone, and would exclude households that are not listed (e.g. those that have chosen not to be listed; those that may not have a landline phone). Also, if a portion of the sampled population does not respond this could lead to nonresponse bias.

13. Kleppel et al. (2004) report on a study of wetlands in upstate New York. Four wetlands were selected for the study: Two of the wetlands drain watersheds from small towns and the other two drain suburban watersheds. Quantities such as pH were measured at two to four randomly selected sites within each of the four wetlands. **Describe why this is a cluster sample. What are the psus? The ssus? How would you estimate the average pH in the suburban wetlands?**

   >**Answer:**
   > 
   > The area is divided into clusters based on watersheds from two small towns and two suburbs, and then data is selected from within these clusters.
   > 
   > PSUs: The four wetlands themselves are the primary sampling units
   > 
   > SSUs: The multiple sites selected within each wetland are the secondary sampling units where two to four pH measurements are randomly selected
   > 
   > I would estimate the average pH in the suburban wetlands based on the mean pH measurements from each of the sites at the chosen suburban wetlands.

14. The new candy Green Globules is being test-marketed in an area of upstate New York. The market research firm decided to sample 6 cities from the 45 cities in the area and then to sample supermarkets within cities, wanting to know the number of cases of Green Globules sold. 

    | City | Number of Supermarkets | Number of Cases Sold                           |
    |------|-----------------------|------------------------------------------------|
    | 1    | 52                    | 146, 180, 251, 152, 72, 181, 171, 361, 73, 186 |
    | 2    | 19                    | 99, 101, 52, 121                               |
    | 3    | 37                    | 199, 179, 98, 63, 126, 87, 62                  |
    | 4    | 39                    | 226, 129, 57, 46, 86, 43, 85, 165              |
    | 5    | 8                     | 12, 23                                         |
    | 6    | 14                    | 87, 43, 59                                     |

    Obtain summary statistics for each cluster. Estimate the total number of cases sold, and the average number sold per supermarket, along with the standard errors of your estimates.

   >**Answer:**
   >
   >**Summary Statistics**
   >| City | Total Number of Cases Sold (Sum) | Number of Supermarkets (Count) | Average Number Sold per Supermarket (Mean) | Standard Deviation | Standard Error |
   >|------|----------------------------------|--------------------------------| -------------------------------------------|------------------|------------------|
   >| 1    | 1773 | 10 | 177.3 |83.6 | 1.1|
   >| 2    | 373  | 4  | 93.3 |29.2 | 0.7|
   >| 3    | 814  | 7  | 116.3 |54.5 | 0.9|
   >| 4    | 837  | 8  | 104.6 |64.6 | 1.0|
   >| 5    | 35   | 2  | 17.5 |7.8 | 0.7|
   >| 6    | 189  | 3  | 63.0 |22.3 | 0.6|
   >| Total| 4021 | 34 | 118.3 |  |
   >
   > The total number of cases sold is 4,021, and the average number sold per supermarket is 118.3.


15. The American Council of Learned Societies (ACLS) used a stratified random sample of selected ACLS societies in seven disciplines to study publication patterns and computer and library use among scholars who belong to one of the member organizations of the ACLS (Morton and Price, 1989). The data are shown in the table below.

    | Discipline    | Membership | Number Mailed | Valid Returns | Female Members (%) |
    |---------------|------------|---------------|---------------|--------------------|
    | Literature    | 9,100      | 915           | 636           | 38                 |
    | Classics      | 1,950      | 633           | 451           | 27                 |
    | Philosophy    | 5,500      | 658           | 481           | 18                 |
    | History       | 10,850     | 855           | 611           | 19                 |
    | Linguistics   | 2,100      | 667           | 493           | 36                 |
    | Political Science | 5,500 | 833           | 575           | 13                 |
    | Sociology     | 9,000      | 824           | 588           | 26                 |
    | Totals        | 44,000     | 5,385         | 3,835         |                    |

    Calculate the response rate in each stratum for the survey. Is there evidence that the nonresponse rate varies among the strata, or that it is related to the percentage female membership?

   >**Answer:**
   >
   > **Response Rate = (Valid Returns/Number Mailed)x100**
   >
   >| Discipline    | Response Rate | Non-response Rate | Female Members (%) |
   >|---------------|---------------|-------------------|--------------------|
   >| Literature    | 69.51% | 30.49% | 38 |
   >| Classics      | 71.25% | 28.75% | 27 |
   >| Philosophy    | 73.10% | 26.90% | 18 |
   >| History       | 71.46% | 28.54% | 19 |
   >| Linguistics   | 73.91% | 26.09% | 36 |
   >| Political Science    | 69.03%  | 30.97% | 13 |
   >| Sociology     | 71.36% | 28.64% | 26 |
   >| Totals        | 71.22% | 28.78% |    |
   >
   >   The nonresponse rate varies among the strata where Political Science has the highest nonresponse rate, followed by Literature then the Classics. The nonresponse does not appear to be related to the percentage of female membership, where Literature has the highest, follow by Linguistics then the Classics (and where Political Science has the lowest rate, followed by Philosophy and History).


16. Kosmin and Lachman (1993) had a question on religious affiliation included in 56 consecutive weekly household surveys; the subject of household surveys varied from week to week from cable TV use, to preference for consumer items, to political issues. After four callbacks, the unit nonresponse rate was 50%; an additional 2.3% refused to answer the religion question. The authors say: “Nationally, the sheer number of interviews and careful research design resulted in a high level of precision . . . Standard error estimates for our overall national sample show that we can be 95% confident that the figures we have obtained have an error margin, plus or minus, of less than 0.2%. This means, for example, that we are more than 95% certain that the figure for Catholics is in the range of 25.0% to 26.4% for the U.S. population.”
    > a. Critique the preceding statement.  
    > b. If you anticipated item nonresponse, do you think it would be better to insert the question of interest in different surveys each week, as was done here, or to use the same set of additional questions in each survey? Explain your answer. How would you design an experiment to test your conjecture?

   >**Answer:**
   > 
   > a. The claim of a "high level of precision" is subjective without providing specific details on how precision is measured or compared to other studies - overall the precision is not quantified with standard errors. They note "we have obtained have an error margin, plus or minus, of less than 0.2%... the figure for Catholics is in the range of 25.0% to 26.4%" where the latter has a range of 1.4%. The callback rate of 50% and a refusal rate of 2.3% introduces nonresponse bias and the authors don't provide information on how they handled this. 
   > 
   > b. The advantage of different surveys each week might be keeping some respondents engaged, but others may fatigue and loose interest in answering each week. The advantage of the same set of additional questions in each survey allows for consistency and ability to do director comparisons across each week, but like the other method, there could be nonresponse due to repetition and fatigue.

17. The goal of the National Comorbidity Survey Replication is to estimate the prevalence of mental disorders in the United States. Read the survey description by Kessler et al. (2004). **What aspects of this survey might affect data quality? What design features were implemented to improve the quality of the survey?**

   >**Answer:**
   > 
   > The survey is comprehensive in its scope and includes various design features to enhance data quality. To ensure data quality, a number of design features were implemented:
   > 
   > Survey Mode and Administration:
   > 
   > • The survey was conducted between February 2001 and April 2003, over a two year period.
   > 
   > • Reponses were collected using face-to-face interviews via laptop computer-assisted personal interview (CAPI) and included accurate screening and household enumeration procedures to get a higher response rate compared to other modes like telephone, mail, or internet surveys.
   > 
   > • The NCS-R interview schedule was lengthy, ranging from 90 minutes to 5-6 hours, depending on the respondent's history of disorders.
   > 
   > • The survey used a multi-stage clustered area probability sample of households to ensure accurate representation of the US population.
   > 
   > • Weighting procedures were implemented to account for differential selection probabilities and correct biases introduced during sampling.
   > 
   > • Efforts were made to minimize nonresponse error e.g. short non-response interviews were conducted with initial non-respondents to gather partial information.
   > 
   > • Professional interviewers underwent general and study-specific training, including a certification test.
   > 
   > • Hard-to-recruit cases, including those difficult to contact or reluctant to participate, were addressed through persistent contact attempts, financial incentives, and a shortened version of the interview
   > 
   > • Verbal informed consent was obtained
   > 
   > Overall, the survey design was rigorous and thoughtful with various features aimed at addressing potential sources of bias and improving data quality, especially considering the sensitive nature of the topics covered in the interviews.

18. One problem that has occurred in surveys on sexual behavior in the United States is that, typically, men report more opposite-sex sexual partners than women do. This has led some researchers to be skeptical of the data quality, since one would expect the total number of opposite-sex partners for men to equal the total number of opposite-sex partners for women. Read the article by Tourangeau and Smith (1996) on asking sensitive questions. **What steps did the authors take to reduce measurement error in their study?**

   >**Answer:**
   > 
   > The study compares three methods: computer-assisted personal interviewing (CAPI), computer-assisted self-administered interviewing (CASI), and audio computer-assisted self-administered interviewing (ACASI). To address the issue of measurement error and improve data quality, the authors took several steps:
   > 
   > • Compared three different modes of data collection to assess their impact on respondents' willingness to report sensitive behaviors
   > 
   > • Conducted a randomized experiment involving an area probability sample of over 300 adults
   > 
   > • The study varied question formats by comparing open and closed questions about the number of sex partners
   > 
   > • The researchers analysized the reporting disparities between men and women by exploring the impact of data collection mode on this gender disparity
   > 
   > • In the Discussion, the findings suggest that responses to questions about sexual behavior are influenced by self-presentation concerns e.g. "findings on the reported number of sex partners are consistent with the view that responses to questions about sexual behavior are strongly affected by self-presentation concerns"
   > 
   > • The study found that questions done by an interviewer "sharply reduced the impact of the format of the sex partner questions on the answers. This finding also suggests that sex partner reports are produced through a somewhat different process when the answers must be reported to an interviewer." This suggests that the answers obtained though one of the self-administered reduced bias.
   > 
   > • The study acknowledged the limitations associated with the "relatively young, well-educated, and urban sample", highlighting the need for further research to test the generalizability of findings to different populations

## References
- Frankovic, K. (2008). Race, gender, and bias in the electorate. Retrieved March 4, 2022, from https://www.cbsnews.com/news/race-gender-and-bias-in-the-electorate/
- Kessler, R. C., Berglund, P., Chiu, W. T., Demler, O., Heeringa, S., Hiripi, E., et al. (2004). The US National Comorbidity Survey Replication (NCS-R): Design and field procedures. _International Journal of Methods in Psychiatric Research, 13, 69–92._
- Kleppel, G. S., Madewell, S. A., and Hazzard, S. E. (2004). Responses of emergent marsh wetlands in upstate New York to variations in urban typology. _Ecology and Society, 5_, Retrieved from www.ecologyandsociety.org/vol9/iss5/art1.
- Kinsley, M. (1981). The art of polling. _New Republic, 184_, 16–19.
- Kosmin, B. A., and Lachman, S. P. (1993). _One nation under God: Religion in contemporary American society._ New York, NY: Harmony Books.
- Morton, H. C., and Price, A. J. (1989). _The ACLS survey of scholars: Final report of views on publications, computers, and libraries._ Washington, DC: University Press of America.
- Salganik, M. J. (2018). _Bit by bit: Social research in the digital age._ Princeton, NJ: Princeton University Press.
- Tourangeau, R., and Smith, T. W. (1996). Asking sensitive questions: The impact of data collection mode, question format, and question context. _Public Opinion Quarterly, 60_, 275–304.
