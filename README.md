# QTM 151 Stats Computing Final Project
Examine how workload, GPA, gender, social media usage correlate with Emory students' sleeping time. 

# I. Introduction and Motivation
Sleep is very important for people. People need sleep to restore energy and stay healthy. It is important for people to follow their circadian clock and get enough sleep, or they will easily get tired and ill. After getting good sleep, a person will not only feel healthy, but also have a positive mood and better concentration when working or studying (UGA Health Center). However, as technology develops, there are more and more distractions. It becomes hard for people to get good sleep every night.

<img width="562" alt="1" src="https://user-images.githubusercontent.com/73702692/98128882-6aa4bf00-1ef3-11eb-9193-04c9833c9f93.png">

College students are notoriously deprived of sleep with bad sleeping habits. Every time I complete the midnight-due homework and leave library, I see lots of students still struggling with their academic assignments. An article indicates that “An average adult needs between 7.5 and 8 hours of sleep per night.” (Gina Shaw, 2010) However, I think most students around me sleep less than standard. Sleep seems to become a luxury that college students can not afford. Moreover, as students go into college, they have more choices of life and have to balance their study, sleep and other activities. As social media occupies a big part of people’s life, it’s harder for college students to get enough sleep.

A research conducted in Australia demonstrates that “less than 5 h sleep in the 24 h prior to work and/or more than 16 h of wakefulness can significantly increase the likelihood of fatigue-related impairment and error at work.” (Dorrian, Jillian, 2010) For students, such sleep deprivation may make them more stressful and less efficient at work, and thus negatively influence their GPA. In this project, I will explore the relationship between sleep hours, workload, length of time spent on social media as factors, and GPA as potential result from deprivation of sleep for Emory students.

<img width="466" alt="2" src="https://user-images.githubusercontent.com/73702692/98128988-90ca5f00-1ef3-11eb-97c3-305227e4b35d.png">

## II. Hypothesis
Hypothesis: 1. Emory students get less sleep than US adults average. 2. Students with heavier workload get less sleep. 3. As students spend more time on social media, they will get less sleep. 4. Students with deprived sleep will receive lower GPA. 5. Male and female have same average sleep hours.

## III. The Dataset
The data is collected from 108 students from Econ 220 class Spring2020. They take surveys at the beginning of semester. Effective questions and answers are recorded. From the whole dataset, I pick five variables for my interest—sleep hours per day, credits enrolled this semester, hours spent on social media per day, GPA and gender.

### Selection of Variables
As we only have 24 hours a day, the length of sleep should be affected by many activities in our life. However, since the data is collected from Emory students in order to explore of sleep habits among college students, I chose credit hours enrolled and hours spent on social media as factor variables because academic workload and social media are two of the biggest factors occupying students’ life, and thus affecting their sleeping length. For the result variable, since college students’ biggest concern is their GPA, I choose that.

I’m not going to divide the data into Year groups. Students taking this class are mostly sophomores and juniors. Freshmen and seniors are unrepresentative. Instead, I’ll add gender as a group variable, but I won’t use it in every analysis.

### Summary Statistics

### Sleep hours distribution in tables
Beginning analyzing the data, we first take a look at the sleep hour distribution in two tables. The first is mere sleep hours and their frequency. The second adds gender as a group variable. We find that most students sleep between 6-7 hours per night. From the histogram of sleep hours grouped by gender, we find that female tend to sleep more than male students.

<img width="251" alt="Screenshot 2020-11-04 at 11 22 54 PM" src="https://user-images.githubusercontent.com/73702692/98129943-adb36200-1ef4-11eb-9466-d55bc953f2a0.png">

<img width="253" alt="Screenshot 2020-11-04 at 11 23 51 PM" src="https://user-images.githubusercontent.com/73702692/98130060-ce7bb780-1ef4-11eb-85b4-a8482f7b797d.png">

<img width="532" alt="3" src="https://user-images.githubusercontent.com/73702692/98130109-dd626a00-1ef4-11eb-9a54-00ecfe049f0b.png">

### Summary of Factor and Result Variables
The table below shows the summary statistics of sleep hours, along with three variables–credits enrolled, hours spent on social media and GPA. The summary statistics include min, mean, max, and the quartiles.

<img width="477" alt="Screenshot 2020-11-04 at 11 25 02 PM" src="https://user-images.githubusercontent.com/73702692/98130211-f8cd7500-1ef4-11eb-8594-6c466c30fcdc.png">

## Data Analysis
### Analysis of Sleep Hours Distribution
The histogram of sleep hours below demonstrates a distribution slightly skewed to the left, which indicates less sleep. The mean of students’ sleep hours is 6.72, indicated by the perpendicular dotted line. Such a mean corresponds to a finding that “70%-96% of students get less than 8-hours of sleep per night during the week.” (Shelley Hershner, 2015).

From the graph, we can also find that none of the 108 students sleep more than 9 hours, and more than 10% students sleep five hours or less on average. This shows that Emory students are all diligent and busy. However, such short duration of sleep is bad for their health and life.

<img width="675" alt="4" src="https://user-images.githubusercontent.com/73702692/98130318-1569ad00-1ef5-11eb-8d71-9f8b416789aa.png">

### Relationship between sleep hours and credit hours enrolled
First, we want to see whether sleeping hours has relationship with students’ workload, which is measured by number of credits they enroll in this semester. Group number of credits by workload, demonstrate the means in a table and we find that the means for the groups with light workload, medium workload, heavy workload are 6.5, 6.5 and 6.75, almost the same. It sheds to conclusion that no significant differences exist between sleep hours of the three groups.

Then, from the boxplot we see that all three groups have almost the same median. However, those with medium workload tend to sleep less than those with light workload or heavy workload from the distribution. The distribution for those with light workload and heavy workload are roughly same except that those with heavy workload have a heavier right tail, which indicates longer sleep hours. Therefore, from the boxplot we see no clear pattern of correlation between sleep hours and amount of workload.

<img width="292" alt="5" src="https://user-images.githubusercontent.com/73702692/98130326-1995ca80-1ef5-11eb-9d6f-a4f440cdff3b.png">

<img width="671" alt="6" src="https://user-images.githubusercontent.com/73702692/98130347-1f8bab80-1ef5-11eb-8738-f7479de81fd1.png">

### Relationship between sleep hours and hours spent on social media
The scatterplot below shows distribution between hours spent on social media and average hours of sleep per night with workload as a group facet. In all three facet groups, the smooth line shows no clear trend, demonstrating no correlation between time spent on social media and sleep length.

Among the facet groups, I also find that students with medium workload tend to spend more time on social media than other two groups, which correlates with their relatively less sleep time.

<img width="672" alt="7" src="https://user-images.githubusercontent.com/73702692/98130369-231f3280-1ef5-11eb-9925-58980193115d.png">

### Relationship between sleep hours and GPA
The scatterplot below shows distribution between hours spent hours of sleep per night and GPA with points and lines colored by gender. The graph shows a slightly upward trend, indicating longer sleep correlates with higher GPA. Further test needs to be done to draw more convincing conclusion.

Besides the sleep pattern, from the scatterplot I also find that female students generally have higher GPA than male. Although the smooth line for male is leftward relative to that for female, we can’t conclude that male generally sleep less than female because of the existence of two outliers.

<img width="665" alt="8" src="https://user-images.githubusercontent.com/73702692/98130377-274b5000-1ef5-11eb-8239-b0943624ee6d.png">

## Tests and Confidence Intervals
### One-way t-test between sleep hours and overall mean
At the beginning of data analysis, I mention that a research indicates adult needs an average of 7.5 to 8 hours of sleep per night.(Shaw Gina, 2010) So I compare the sleep hours in our survey with the overall average as 7.75 and 0.05 as the critical value to see whether students at Emory sleep less the average. We use the null hypothesis that sleep hours in US overall and in Emory are the same and the alternative hypothesis that students in Emory sleep less than overall average.

From the one-way t-test, I get t value -11.18 and p-value 2.2e-16 < 0.05. Thus, we have enough evidence to reject the null hypothesis that sleep hours in US overall and in Emory are the same. We have evidence that to demonstrate that **Emory students are sleep deprived.**

### Avova test between sleep hours and workload
Since there are three groups for the workload factor variable, we use Avova test to compare means between three groups, and 0.05 as critical value. In this case, p-value is 0.217>0.05 and F-value is 1.551. We don’t have enough evidence to reject null hypothesis that means among three groups are the same. We conclude that little variation exists between sleep hours of three groups and **students’ sleep time is not significantly correlated with the amount of workload.**

### Correlation test between sleep hours and time spent on social media
We use a correlation test to find whether there is correlation between students’ sleep hours and their time spent on social media. The result demonstrate that the correlation value between the two varaibles is about -0.150. However, p-value is 0.122>0.05, and confidence interval is betwen -0.33 and 0.04, which contains 0. So we don’t have enough evidence to reject the null hypothesis that correlation coefficient is NOT significantly different from 0. In other words, evidence shows that **there is little or no correlation between sleep hours and time spent on social media.**

### Correlation test between sleep hours and GPA
We use a correlation test to explore whether correlation exists between sleep hours and students’ GPA. The result shows that the p-value is 0.286 > 0.05, and the confidence interval betwen -0.087 and 0.288, which contains 0. So we don’t have enough evidence to reject the null hypothesis that correlation coefficient is NOT significantly different from 0. In other words, evidence shows that there is little or no correlation between sleep hours and GPA.

### T test between sleep hours and gender
We use a t-test to check whether sleep hours is affected by gender. As a result, the p-value is 0.59>0.05, and the confidence interval betwen -0.46 and 0.27 contains 0. So we don’t have enough evidence to reject the null hypothesis that sleep hours between male and female are the same. In other words, evidence shows that sleep hours is not significantly affected by gender.

# Conclusion
From the graphs and tests, we find that Emory students don’t have enough sleep compared with7.5 to 8 hours sleep for average US adults. Thus, we can conclude that Emory students are deprived of sleep. It seems that students are willing to sacrifice their rest time in order to engage in other parts of school life.

However, from exploration of the cause and result variables, we find no clear relationship between sleep hours and workload, time spent on social media and GPA. My original hypothesis with those variables are rejected. Maybe students’ sleep time is not significantly affected by their workload and time spent on social media. Instead, sleep length depends more on more internal things like students’ self-discipline, life habits and time managing ability. A student with good habits and high level of self-discipline can smartly plan various things in their life and maintain good balance between sleep, study and social life. So even they have heavy workload and spend much time on social media, they can save time from other things like eating, watching TV and participating in club to have more hours of sleep.

Moreover, sleep time also doesn’t affect students’ GPA a lot. Maybe different students need different length of sleep to stay awake during the day. Or maybe those who are deprived of sleep can find other effective ways to maintain wakefulness and efficiency, like buying a coffee. However, although the result shows no clear positive correlation between sleep and GPA, students should still have enough sleep in order to maintain their health to improve long-run competitiveness.

However, there are also shortcomings of the project. First, the sample is unrepresentative of college students overall since the sample size is relatively small and limited only to our Econ220 class. For example, if we expand the sample outside Emory, maybe the average sleep time will be longer. However, other variables and correlations between variables are hard to predict with more data. Moreover, little insights are shed on potential causes and results of sleep time for students. The findings in this project should be combined with data from other resources for us to draw more conclusive conclusions.

<img width="698" alt="9" src="https://user-images.githubusercontent.com/73702692/98130407-2dd9c780-1ef5-11eb-97b4-1fc3513c4aea.png">

# Further Explorations
* Use a larger sample beyond Econ 220 class and Emory to find more comprehensive results.
* Explore interactions between some of the cause and result variables, and see whether such interactions affect our knowledge of sleep hours.
* Explore more cause and result variables for sleep hours to get deeper insights into the causes and effects of length of sleep.
* Combine data results with practical knowledge to find potential ways to increase students’ sleep time in order to improve their health and efficiency during the day.
* Beyond the length of sleep, explore quality of sleep to get more comprehensive understanding of the role of sleep in students’ life.

# References
1. Dorrian, Jillian, et al. “Work Hours, Workload, Sleep and Fatigue in Australian Rail Industry Employees.” Applied Ergonomics, vol. 42, no. 2, 2011, pp. 202–209., doi:10.1016/j.apergo.2010.06.009.
2. Hershner, Shelley. “Is Sleep a Luxury That College Students Cannot Afford?”Sleep Health, vol. 1, no. 1, 2015, pp. 13–14., doi:10.1016/j.sleh.2014.12.006.
3. Shaw, Gina. “Adult Sleep Needs at Every Age: From Young Adults to the Elderly.”WebMD, WebMD, 20 Oct. 2010, www.webmd.com/sleep-disorders/features/adult-sleep-needs-and-habits#1.
4. “Sleep Rocks! …Get More of It!” University Health Center | Managing Stress | Sleep | University Health Center, www.uhs.uga.edu/sleep.
