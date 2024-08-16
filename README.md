# Rishi Siddharth 
# Hi! Welcome to my Github!
This repository is an introduction about me, my current projects/work experince, and more. Enjoy!
Feel free to contact me - rs5309a@student.american.edu
![alt text](Rishi.jpg.png)

*American University and London School of Economics*

# Education 
American University, Graduating 2026
London School of Economics 2024-2025 (Jr Year)
Data Science major, International Business minor

# About Me!
I still manage to have fun outside of work. I love soccer, and still currently play on the club team at AU where I am a D1 practice player for the women's team as well. 

# Relevant Work Experience

Research Intern - Georgetown University                       May - August 2024
  Spatial Program: I participated in research projects funded by the NSA and NSF. Our research focused on builing a predictive stock portofilio analytic model using time series, webscraping, etc to predict the price change of the future month. Currrently I am working on publishing my findings. 
  
Summer Technology Helper - Menlo Park School District         Jun 2023 - Aug 2023
My main objective was quality maintenance for each iPads in the grade. I organized and managed data of the IPads, including routing numbers and serial numbers. Used JSON server to connect with laptops and integrate specific software to mitigate full usage of I-Pads for student.


More related work experiences can be found at: https://www.linkedin.com/in/rishi-siddharth-0024ba235/

# Languages 
- R, Python, Stata, SQL, Excel
- Currently learning: C, Julia, SAS


# MORE PROJECTS COMING SOON!

# [Project 0 - Stock Insight Analytic Tool]


This a comprehensive stock portfolio analytic tool that gives new users to the stock market an insight into the factors that actually affect a stock.

# Steps

1. We were able to source data, 128 stocks, that ranged from stocks within the AI/fintech sector to bonds and mutual funds, all from the yahoo finance library on python.

2. We were able to obtain 3 scores;
    a. Raw Total Score =  all the factors of a stock summed up
    b. Total Score =  The score of this was based on each factor being divided by the maximum amount out of all the stocks. For example, if the PE_SCORE minimum was -4.9, the absolute value of that would be added to each PE_SCORE for every stock. We would do this to eliminate all negative values. Then, we divided each columnn values by the maximum to create a scale of 0-1.
   c. Normalized Total Score = We simply took the Total Score and created a more reasonable scaling. It ranged from -100 to 100.
<img width="704" alt="Screenshot 2024-08-12 at 3 30 15 PM" src="https://github.com/user-attachments/assets/7c660c63-979c-42bb-a937-3e0095fa41d5">

4. Using the scores we were able to determine statistical outcomes when comparing to the factors that affected a stock.

5. Results = 
<img width="663" alt="Screenshot 2024-08-12 at 3 31 24 PM" src="https://github.com/user-attachments/assets/05b4903a-9cff-4f8e-9240-bf3bac883810">
<img width="693" alt="Screenshot 2024-08-12 at 3 31 47 PM" src="https://github.com/user-attachments/assets/f0a9cc69-b5a0-4bf5-b0b6-1632c9f0dc91">
<img width="704" alt="Screenshot 2024-08-12 at 3 32 02 PM" src="https://github.com/user-attachments/assets/d12ab3fd-9cf0-433b-9b84-991ed18b25fd">
<img width="684" alt="Screenshot 2024-08-12 at 3 32 14 PM" src="https://github.com/user-attachments/assets/aa1f5675-5e28-493f-8d9d-7f0740c697eb">
<img width="681" alt="Screenshot 2024-08-12 at 3 33 48 PM" src="https://github.com/user-attachments/assets/cdd8aa9d-e125-41fe-9a36-ca715bec5ed1">
<img width="646" alt="Screenshot 2024-08-12 at 3 34 01 PM" src="https://github.com/user-attachments/assets/d8428c47-3a6d-4364-b585-08ee2a71482d">









# [Project 1 - US Apartments](https://github.com/Rsiddharth54/U.S-Apartments-Project)
Abstract ----
The purpose of this project was to learn the basics of machine learning and to implement new data visualization techinques I wanted to play around with more. The dataset that featured US Apartments and their characteristics was a useful way to learn and utilize these concepts.


- Dataset involving apartments all over the U.S 
- Data cleaning, data manipulation
- Linear regression, mean sqaured error, and decision tree classifiers 
- Data visuals such as Matplotlib, confusion matric display, and the use of another dataset for accuracy comparison purposes

![alt text](imagwes/chart.png)
![alt text](images/matrix.png)
![alt text](images/usmap.png)


# [Project 2 - Violence in America](https://drive.google.com/file/d/1nDogpm4zgvAgjSiDvB5WUJTseWvjF-h3/view?usp=drive_link)

Abtract --------------------
With this project I wanted to utlize new concepts learned in R. This was my first project, and I wanted to maintain the skills used in this project, so I turned it into a lesson of some sort. With everything I did; from data cleaning, maniupulation, graphics, and statiscal tests I documented how I did it, why, and analyzed every output. I got some great insights from a great dataset that consisted of America's crime: violence, robbery, and murder plus demographics, age, race, etc. 

- Dataset that consisted of violence in America, split by murder, violence, robbery etc.
- Conducted in Rstudio
- Data manipulation, data cleaning,  (forcats, lubridate, ggplot, dplyr).
- Summary Statistics, data visualization, linear regression
- Spearman's rank, ANOVA, clear concise explaination of results

![alt text](images/usmap_murders.png)
![alt text](images/scatter_murders.png)
![alt text](images/state_barchart.png)

USAfacts.org posted an article on November 8, 2023, which showed the highest murder rates. In their article, they state “Although Washington, DC, had a higher homicide death rate (33.3 homicide deaths per 100,000 people) than every state, it’s not a state — given its population density, a fairer comparison is to counties in major metropolitan areas.” This is exactly what our data showed, which, like the article states, is somewhat of an unfair compariosn due to it’s population density.

https://usafacts.org/articles/which-states-have-the-highest-murder-rates/


