# Project TunnelEnd
## Machine Learning and Artificial Intelligence for Mental Health and Well-being

### Introduction
In 2012, an estimated 6,500 former military personnel died by suicide. More veterans succumbed to suicide than were killed in Iraq: 177 active-duty soldiers died by suicide compared to 176 soldiers killed in combat. In 2012, the study concluded that the Army had the highest number of suicides compared to any other service branch.

In 2013, the VA released a study that covered suicides from 1999 to 2010, which showed that roughly 22 veterans were dying by suicide per day, or one every 65 minutes. Some sources suggest that this rate may be undercounting suicides. A recent analysis found a suicide rate among veterans of about 30 per 100,000 population per year, compared with the civilian rate of 14 per 100,000. However, the comparison was not adjusted for age and sex.

The total number of suicides differs by age group; 31% of these suicides were by veterans 49 and younger while 69% were by veterans aged 50 and older. As with suicides in general, suicide of veterans is primarily male, with about 97 percent of the suicides being male in the states that reported gender.

In 2015, the Clay Hunt Veterans Suicide Prevention Act passed in the Senate and was then enacted as Pub.L. 114–2 on February 12, 2015.

### Major causes of suicides
A study published in the Cleveland Clinic Journal of Medicine found that,

Combat veterans are not only more likely to have suicidal ideation, often associated with posttraumatic stress disorder (PTSD) and depression, but they are more likely to act on a suicidal plan. Especially since veterans may be less likely to seek help from a mental health professional, non-mental health physicians are in a key position to screen for PTSD, depression, and suicidal ideation in these patients.

The same study also found that in veterans with PTSD related to combat experience, combat-related guilt may be a significant predictor of suicidal ideation and attempts.

Craig Bryan of the University of Utah National Center for Veterans Studies said that veterans have the same risk factors for suicide as the general population, including feelings of depression, hopelessness, post-traumatic stress disorder, a history of trauma, and access to firearms.

A study done by the Department of Veterans Affairs discovered that veterans are more likely to develop symptoms of PTSD for a number of reasons such as:
- Longer times at war
- Lower level of education
- More severe combat conditions
- Other soldiers around them killed
- Brain/head trauma
- Female gender
The Department of Veterans Affairs also discovered that where you were deployed and which branch of military you are with can also have drastic effects on your mental status after returning from service. As in most combat wars, your experiences will vary depending on where you are stationed.

### About this project
This project is based on the data inferred from surveys conducted from the year 2005 to the year 2011, which contains information regarding state-wise statistics of civilian and veteran suicides based on gender, along with their probabilities. Using the assimilated data, we helped create machine learning models to identify places of high alert and growth rates in each of those states. 

We utilized the following learning model algorithms, compared them, and utilized the most efficient one for the final result:

|    Algorithm      |   Score   |
|---------------    |---------- |
| Random Forest     | 5.53-5.85 |
|    SVR            |70.61-80.18|
|  Linear Regression| 4.13-5.05 |

A visual representation of the accuracies of the models is as follows:

![aaa](https://user-images.githubusercontent.com/23614555/44804734-dc7c7200-abdf-11e8-9860-a4954ae1fd79.png)

This helped us come to the conclusion.

### Conclusion
Since the accuracy of Linear Regression is the highest (off by the lowest value of suicides), it helped us infer that with each year, the rate of US veteran suicides increases. Next, we tried comparing it to the rate of civilian suicides over the years, which concluded as:

![aab](https://user-images.githubusercontent.com/23614555/44804835-30875680-abe0-11e8-9185-78b8c472fb8f.png)

This led to the unfortunate inference that the rate of suicides have progressively increased with each year for both civilians, and US veterans, although the rate has increased faster for the latter.

### Utilization of results
The gathered results have the following possible uses:
- Identify high-alert areas for veterans and/or civilians
- Set up health camps and rehabs in those places in order to provide help to more people
- Spread the concern in order to possibly bring upon infrastructures or arrangements to make life after war easier for the veterans

### References
- Kaggle for the dataset (https://kaggle.com)
- Wikipedia for studies' results and observations (https://en.wikipedia.org/wiki/United_States_military_veteran_suicide)

