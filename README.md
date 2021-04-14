# ADS Project 5: 

Term: Spring 2021

+ Team #2
+ Project title: <b>To Tweet or Not to Tweet: Predicting Trump's Deleted Tweets.</b>
+ Team members
	+ Olha Maslova
	+ Mark Morrissey
	+ Amir Idris
	+ Yutong Yang
	+ Yibai Liu
	+ Daryl Kow

<img src="figs/trump.png" width="200">

**Project summary:** In this project we want to explore which of the of the Donald Trump's tweets were deleted and try to build a predictive model. In order to do so, we create additional features using sentiment analysis and topic modeling. We also perform EDA to gain insights about the data we are working with. Our report can be found ([here](doc/main.pdf)). 

**Project Conclusion:** Twitter did not delete random tweets, or even tweets that were the most popular. Twitter appears to have followed their guidelines and deleted tweets relating to or spreading misinformation. This is why deletions are not random, and why certain topics come up among deletions frequently, such as the election (fraud).

Why do we care? As Twitter continues to strengthen their content monitoring, we want to investigate how it is being implemented and how closely it follows their guidelines, since these guidelines will not go away now that Trump is out of office.
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

+ Individual Contributions:
	+ Olha Maslova: Cleaned data for sentiment analysis. Researched various sentiment analysis techniques. Implemented Vader and TextBlob algorithms. Wrote Github READMEs. Contributed to PPT. 
	+ Mark Morrissey: Cleaned data for topic modeling. Collaborated on implementing topic modeling and predictive model. Contributed to PPT. 
	+ Amir Idris: Performed Exploratory Data Analysis and visualization. Contributed to presentation. 
	+ Yutong Yang: Collaborated on implementing topic modeling. Lead the development of predictive model. Contributed to PPT. Presented the project. 
	+ Yibai Liu: Performed Exploratory Data Analysis and visualization. Contributed to topic modeling and PPT. 
	+ Daryl Kow: Implemented Word-to-vec based Sentiment analysis algorithm. Combined all 3 approaches for sentiment analysis to yeild a single output.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
