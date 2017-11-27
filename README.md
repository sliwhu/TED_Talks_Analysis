# Which Talks Are Popular and Why -- TED Talks Analysis
![Ted Talks](http://dailygenius.com/wp-content/uploads/2014/09/ted-talks.png)

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>

## Project Goal  
TED is a nonprofit organization born in 1984. Originally, it was set up as a platform for professionals to share their innovative ideas and the topics were restricted in technology, entertainment and design fields. Nowadays, TED has already become an unparalleled phenomenon, attracting millions of people worldwide to watch, present, discuss and think on hundreds of topics. With such diverse range of topics and speakers, which TED Talks are popular and why? Current TED Talks popularity studies are generally quite shallow as listing the top viewed talks or the top speakers, deeper studies based on real-world data to answer the question of what are the specific factors that contribute to TED Talks popularity are lacking. Therefore, I conducted this study to answer 5 research questions that relates to TED Talks popularity and reflect on ways of how can we use the results of this study to understand TED talks audiences and design better TED talks in the future. 

## Project Overview  
This project is consisted of six sections:
### 1. Introduction  
### 2. Research Questions  
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1  RQ1: Define Popularity  
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1.1 Number of views 
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1.2 Number of comments  
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1.3 Number of comments per view 
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1.4 Number of languages 
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.2  RQ2: Topic Vs Popularity  
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.2.1 Hypothesis2a Ted Topics related to technology, entertainment and design are more popular. 
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.2.1 Hypothesis2a Ted Topics related to technology, entertainment and design are more popular. 
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.2.2 Hypothesis2b Some topics are more popular because they are informative rather than funny or surprising. 
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3 RQ3: Time Vs Popularity  
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3.1 Hypothesis3a TED Talks are becoming more and more popular over the past 10 years. 
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3.2 Hypothesis3b TED Talks popularity is not related to published months. 
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3.3 Hypothesis3c TED Talks are more popular on weekends than weekdays.  
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.4 RQ4: Speaker Vs Popularity 
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.4.1 Hypothesis4a TED Talks given by speakers with occupations having more chances to give public speeches are more popular  7
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.4.2 Hypothesis4b Top popular speakers will be different when measuring popularity in terms of views, comments, comments per view and number of languages. 
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.5 RQ5: Presentation Skills Vs Popularity 
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.5.1 Hypothesis5a Medium length TED Talks are more popular 
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.5.2 Hypothesis5b TED Talks that started with a question are more popular  
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.5.3 Hypothesis5c TED Talks presented in humorous ways are more popular  
### 3. Data Collection, Processing and Analysis  
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.1 Data Sources and License  
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.2 Data Collection
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.3 Data Processing 
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.4 Data Analysis 
### 4. Conclusions 
### 5. Human-Centered Data Science Reflections
### 6. References    

## Project Structure
```
Which Talks Are Popular and Why -- TED Talks Analysis/  
  |- Data/  
     |- ted_main.csv  
     |- transcripts.csv   
     |- h2a_result.csv
     |- theme_why.csv  
  |- LICENSE
  |- README.md
  |- Project_Plan.ipynb
  |- TED_Talks_Analysis.ipynb
  |- Project_Presentation.pptx
  |- Project_Presentation_record.mov
  |- Figures/
     |-2-1-1 Top and bottom 10 viewed TED talks.png
     |-2-1-2 Top and bottom 10 commented TED talks.png
     |-2-1-3 Top and bottom 10 comments_per_view TED talks.png
     |-2-1-4 Top and bottom 10 number of languages TED talks.png
     |-2-2-1 Top topics by view rate.png
     |-2-2-1 Top topics by comment rate.png
     |-2-2-1 Top topics by comments per view rate.png
     |-2-2-1 Top topics by language rate.png
     |-2-2-2 Topic themes by view rate.png
     |-2-2-2 Topic themes by comment rate.png
     |-2-2-2 Topic themes by comment per view rate.png
     |-2-2-2 Topic themes by language rate.png
     |-2-3 Number of views over time.png
     |-2-3 Number of comments over time.png
     |-2-3 Number of comments per view over time.png
     |-2-3 Number of languages over time.png
     |-2-4-1 Top speakers by number of views.png
     |-2-4-1 Top speakers by number of comments.png
     |-2-4-1 Top speakers by number of comments per view.png
     |-2-4-1 Top speakers by number of languages.png
     |-2-4-2 Top speakers occupations by number of views.png
     |-2-4-2 Top speakers occupations by number of comments.png
     |-2-4-2 Top speakers occupations by number of comments per view.png
     |-2-4-2 Top speakers occupations by number of languages.png
     |-2-5-1 Number of views grouped by length of TED talks.png
     |-2-5-1 Number of comments grouped by length of TED talks.png
     |-2-5-1 Number of comments per view grouped by length of TED talks.png
     |-2-5-1 Number of languages grouped by length of TED talks.png
     |-2-5-2 Rank of views distribution w and wo question mark in title of TED talks.png
     |-2-5-2 Rank of comments distribution w and wo question mark in title of TED talks.png
     |-2-5-2 Rank of comments per view distribution w and wo question mark in title of TED talks.png
     |-2-5-2 Rank of languages distribution w and wo question mark in title of TED talks.png
     |-2-5-3 Rank of views distribution w and wo laughter in transcript of TED talks.png
     |-2-5-3 Rank of comments distribution w and wo laughter in transcript of TED talks.png
     |-2-5-3 Rank of comments per view distribution w and wo laughter in transcript of TED talks.png
     |-2-5-3 Rank of languages distribution w and wo laughter in transcript of TED talks.png
```

## Source Data Licensing 
The original data was scraped from the official TED Website and is available under the Creative Commons License(Released Under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)).

## Source Data documentation
Two datasets will be used for this project with 18 variables and ~2500 records in total. They were available under creative commons licence from a [Kaggle Competition](https://www.kaggle.com/rounakbanik/ted-talks). The datasets contain all audio-video recordings of TED talks on the official TED website from January 10th, 2006 to September 21st, 2017. 

## Data Output and main findings
#### Summary of hypotheses

|      Hypothesis       |       Supported?    |                  Description                      |
|-----------------------|---------------------|---------------------------------------------------|
|    Hypothesis2a       |     Yes, partially  |Technology, entertainment and design are indeed belong to the top 10 popular topics.The most top popular topics, however, are technology, culture, science and global issues.  |
|    Hypothesis2b       |       Yes           |TED talks are popular mostly because they are "inspiring" according to the audiences top ratings, followed by "informative" and "fascinating".|
|    Hypothesis3a       |       No            |TED talks popularity was climbing from 2006 to 2013, and experienced decline from 2013 to nowadays.|
|    Hypothesis3b       |       No            |TED talks are more popular in summer.|
|    Hypothesis3c       |       No            |TED talks are more popular on weekdays. |
|    Hypothesis4a       |     Yes, partially  |Top popular speakers are indeed different when measuring popularity differently, however, Ken Robinson, Brene Brown and Hans Rosling are the top popular speakers across all four definition of popularity lists.|
|    Hypothesis4b       |     No              |Writer, journalist, entrepreneur give the most popular talks. They are not necessarily occupations with more chances for public speaking, instead they generally have diverse experience and good at sharing sympathy with the audience. |
|    Hypothesis5a       |     Yes             |Medium length talks (10-20 mins) are most common and most popular talks as well.|
|    Hypothesis5b       |     Yes             |TED talks with a question mark in their titlesare generally more popular.|
|    Hypothesis5c       |     Yes, partially  |TED talks with at least one ‘laughter’ in their transcripts are generally more often viewed. However, they don’t raise more discussions per view compared to other talks.|

#### Summary of findings 
##### section 2.1
* “Do schools kill creativity”, “Your body language may shape who you are” and “How great leaders inspire action” are the top popular talks (made into all four top 10 lists using different definition of popularity)
* Top 1 viewed talk “Do schools kill creativity” didn’t even make into the top 10 comments per view list. On the contrary, “Militant atheism” raised more comments compared to its view numbers.
* Top 10 talks translated into most number of languages list is quite different from the rest three lists. US audiences preferences are apparently different from global average.
* When comparing top 10 lists of four popularity definitions, there are most overlap between top 10 viewed list and the TED official website, indicating TED mostly consider number of views as their criteria for popularity. Less attention were given to number of comments/comments per view/number of languages.

##### section 2.2.1
* Technology, entertainment and design are indeed belong to the top 10 popular topics. 
* The most top popular topics, however, are technology, culture, science and global issues (made into all four top 10 lists using different definition of popularity).
* TEDx is a Program which is designed to help communities, organizations and individuals to spark conversation and connection through local TED-like experiences. TEDx is a top tag as well.
* Business, Psychology and brains are other top popular topics that received more views than discussions. On the contrary, politics and health are popular topics raises more discussions per view.  
* Art related talks, is relatively easy to be translated to more languages.

##### section 2.2.2
* Topics are more popular mostly because they are inspiring! (90% of top 1 rating out of all four popularity lists are inspiring).
* Topics are more popular also because they are informative or fascinating. 
* Other reasons topics are more popular include persuasive, ingenious and funny.
* Positive ratings such as beautiful, courageous, jaw-dropping didn't make into the top reasons for popularity list. 

##### section 2.3
* TED talks are not becomming more and more popular over the past 10 years. There was peak times in terms of views and comments. 2010-2013 are generally peak times for TED talks. (Higher number across all four popularity definition lists)
* 2017 result is unknown yet since full year data is not available.
* TED talks popularity seems quite evenly distributed over the 12 months, however, it is generally more viewed/commented in summer (Mar-July) than winter (Oct-Dec). Interestingly, Aug is the bottom month across all four popularity lists.
* TED talks are much more popular on weekdays than weekends. More over, Mon to Wed are usually more popular than Thur to Fri.

##### section 2.4
* Top popular speakers are indeed different when measuring popularity in terms of views, comments, comments per view and number of languages. However, Ken Robinson, Brene Brown and Hans Rosling (made into all four top 10 lists) 
* Other top popular speakers are Jill Bolte Taylor and Amy Cuddy (made into three out of four top 10 lists)
* Writer, Journalist, entrepreneur are the most popular occupations among the most popular talks. (made into all four top 10 lists).
* Other top popular occupations among the most popular talks are psychologist, photographer and artist.(made into three out of four top 10 lists). 
* Among the most common occupations for TED talks, architect and filmmaker do not give as popular talks as other top occupations. 

##### section 2.5
*  Medium length talks (10-20 mins) are most common and most popular talks as well. Followed by short(less than 10 mins), long(20-30 minutes) and extra long talks(>30 mins).
* For TED talks with a question mark in their titles, they are generally more popular (rank higher in popularity lists) than those without, but not significant differences.
* For TED talks with at least one ‘laughter’ in their transcripts, they are generally more often viewed. 
* However, these humorous talks don’t raise more discussions per view compared to other talks, suggest that the ability to inspire people is more important than make people laugh in order to raise follow up thoughts among audiences. 

#### Conclusions
##### section 2.1
* Analysis results are drastically different using different definition of popularity!
* The comparision of my top 10 list with the most popular talks list on the TED official website indicate TED mostly consider number of views as their criteria for popularity. Less attention were given to number of comments/comments per view/number of languages.

##### section 2.2.1
* Technology, entertainment and design are belong to the top 10 popular topics, but technology, culture, science and global issues are the most top popular topics. 

* Business, Psychology and brains received more views, while politics and health tends to raise more comments, and art is welcome globally.

##### section 2.2.2
* TED talks are popular because they inspire people to make changes to their own life!

##### section 2.3
* TED talks popularity was climbing from 2006 (since its available free online) to 2013, and experienced decline from 2013 to nowadays.
* TED talks are more popular in summer and on weekdays.

##### section 2.4
* Ken Robinson, Brene Brown and Hans Rosling are the top popular speakers across all four different definitions of popularity.
* Writer, journalist, entrepreneur give the most popular talks. They are not necessarily occupations with more chances for public speaking, instead they generally have diverse experience and good at sharing sympathy with the audience. 

##### section 2.5
* Presentation skills are indeed important and related to popularity. Specifically, medium length talks and starting the presentation with a question will help audience focus and engage. Presenting in a humorous way helps draw attention, but the contents ultimately determine whether the audiences will be inspired or not. 


All other analyzed results were stored either as figures or tables in figures folder. All analysis and findings details are recorded in TED_Talks_Analysis.ipynb.

## Human-Centered Data Science Reflections
* Reproducibility and replicability of open research

This study will be an open research, the methodology will be freely available via the internet, along with any data or results derived from the study. The reason why I want to make it open research is to increase the scientific impact of my work, especially to help TED to appeal more audiences and make larger impact to them. As a result, reproducibility(reproducing a research study involves applying the same methods to the same data and achieving an identical result) as well as replicability(replicating a research study involves applying the same methods to new data and achieving a commensurate, confirming, or contradictory result) are important for this study. 
To fully take this human-centered data science aspect into consideration, my efforts were:
1) Clearly defined popularity concepts, four different aspects were considered, so my the audiences of my study can use results wisely based on their preference of popularity concepts.
2) All calculation metrics and constraints were clearly defined in this study, such as view rank/comment rank, view rate/comment rate. 
3) Any literature or code references were clearly claimed.

* Bias exist in both source data and my study design/analysis

Both bias in original data and bias in study design are exist for this study. Bias in original data is illustrated under section 1 in "Unknowns and Limitations of This Study" part. 
Bias in study design: 
1) Four definitions of popularity are proposed, which may be limited definitions. Popularity can still be assessed in other ways. 
2) Research questions are designed surrounding four aspects: topic, speaker, time and presentation skills, which may be limited. Popularity may well associated with other factors. Other study design limitations are the way I propose specific hypotheses. For example, I hypothesize 3 things in presentation skills vs popularity and they are: talk length, starting the talk with a question, presenting talk in a humourous way. There might be more presentation skills can be revealed from the transcripts! However, due to time limit of the research project, I might be bias of only selecting these three presentation skills over others, it doesn't mean these skills are more important than others. 
