### 1. The Team

a) Who's on the team? (Include names and UNIs)
* Priyanka Lahoti (UNI: pvl2111)
* Hima Bindu Bhardwaj (UNI: hb2635)
* Jasmine Bao (UNI: sb4320)
* Yingnan Wu (UNI: yw3431)  



b) How do you plan to divide up the work? (Grading is on a group basis. The point of asking is to encourage you to think about this.)
* Priyanka Lahoti: Question a) and b)
* Hima Bindu Bhardwaj: Collecting datasets and Question c)
* Jasmine Bao: Collecting datasets and Question c)
* Yingnan Wu: Question a) and b)



### 2. The Questions

List three questions that you hope you will be able to answer from your research.

* General visualization explorations of wars, such as:
    + what types of wars happened most frequently,
    + which country initiated inter-state wars most frequently, 
    + which war type caused the most number of deaths,  
    + what wars caused the most number of deaths, 
    + is the number of deaths correlated to whether the country is an initiator of an inter-state war or not, 
    + is there a pattern between initiators and winners of inter-state wars, 
    + what countries had most losses of human lives due to the war, 
    + what countries participated most actively in the wars, 
    + is there a pattern of the starting month of all wars, etc.

* What are the similarities and differences between World War I and World War II? (e.g., How were the global food prices affected during WW1 and WW2 time periods?)

* What are the effects of wars on the economics, food production, population, and education of some countries? (We may focus on some countries like Japan, Russia, Germany, China, United Kingdom, France that both participated in WWI and WWII.)  




### 3. Which output format do you plan to use to submit the project?

**bookdown book**



### 4. The Data

What is your data source?  What is your method for importing data? Please be specific. Provide relevant information such as any obstacles you're encountering and what you plan to do to overcome them.


Our data is from [The Correlates of War Project](http://www.correlatesofwar.org/), a project that seeks to facilitate the collection, dissemination, and use of accurate and reliable quantitative data in international relations. There are four data sets which are about extra-state wars, inter-state wars, intra-state wars, and non-state wars respectively. Each data set is available as a `csv` file and comes with a codebook that defines each variable clearly. Therefore, our method of importing data is simply downloading the datasets and importing into RStudio with `read.csv()` function. 

In addition, we plan to merge other data sets about economics into our analysis, especially for the third question in Part 2 above. Our population and real GDP per capital data is from the [Maddison Project Database](https://www.rug.nl/ggdc/historicaldevelopment/maddison/releases/maddison-project-database-2018) which provides information on comparative economic growth and income levels over the very long run. Specifically, this dataset includes data on real GDP per capita in 2011 US dollars and population for the two world wars and is available in csv format.
