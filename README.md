# Bias for estimating life expectancy from age at death: A simulation approach applied to Morquio Syndrome A
Life expectancy is accurate when we assess the life length of a cohort of individuals born in the same year and followed since their births to their deaths. Due to the difficulties and time consuming of following a cohort, we usually assess life expectancy based on death rates. However, this may cause bias since we neglect the possible changes in the environment or medical improvements that influence the length of life.To investigate whether there is bias when assessing life expectancy on death data, we simulate the survival data of individuals with Morquio syndrome A under four different scenarios. Under different scenarios, we calculate their means and medians of survival time of individuals deceased in the last 36 years and compare them with expected survival time at the end of the period.

## Code directory 
weibull_distribution.R: functions that used in the following Rmd files.

figure1_weibull_distribution_plot.Rmd and .html: Rmd file generates the density of a Weibull distribution with mean and median of age at death based on the data. html file is the output of Rmd file.

figure2_real_means_medians.Rmd and .html: Rmd file displays the changes of real mean and median survival time for simulating in four different scenarios. html file is the output of the Rmd file.

figure3_boxplots_of_four_scenarios.Rmd and .html: Rmd file has four boxplots showing the average mean and median survival time of individuals deceased during the last 36 years and comparing them with the true mean and median values.

Tabel1.rmd and .html: Rmd file displays the true mean and median survival, average estimated mean and median survival and naive mean and median survival across 1000 simulation runs, for each of the 4 scenarios. 

Tabel2.rmd and.html: Rmd file displays the Kaplan Meier median survival time across 1000 simulation runs, for each of the 4 scenarios

## Data directory
M_Type_A_survival.csv: Deaths that occurred between 1975 and 2010 in the United Kingdom collected by the the Society for Mucopolysaccharide Disease in the United Kingdom. A total of 27 deaths were recorded, with the dataset being made fully available and including date of birth, gender, date of death, and primary cause of death.  

## Figure directory
Figures in this paper can be generated from the code directly. 

Figure 1 shows the weibull distribution for first simulation scenario,generated by figure1_weibull_distribution_plot.Rmd. 

Figure 2 displays the true mean and median for generating survival data under four different scenarios,generated by figure2_real_means_medians.Rmd. 

Figure 3 shows the boxplots of average mean and median survival time under four different scenarios, generated by figure3_boxplots_of_four_scenarios.Rmd.
