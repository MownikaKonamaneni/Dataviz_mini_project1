# Marathon Results Analysis

This project aims to analyze marathon data from the year 2017. The dataset used for analysis is "marathon_results_2017.csv". The main objectives of this project are to:

1. Analyze the number of finishers by age group.
2. Visualize the age distribution of finishers.
3. Investigate the age distribution based on gender.
4. Determine the top 10 countries with the fastest runners based on average finishing time.

## Project Structure

marathon-results-analysis/
```
├── data/
│ └── marathon_results_2017.csv
├── report/
│ ├── Dataviz_miniproj1.Rmd
│ └── Dataviz_miniproj1.nb.html
├── Mini Project 1 - Marathon results.Rmd
├── Mini Project 1 - Marathon results.nb.html
├── Mini Project 1.Rproj
└── README.md
```
## Running the Analysis

To run the analysis on your local machine, follow these steps:

1. Clone the repository to your local machine using the following command:

   $ git clone https://github.com/MownikaKonamaneni/Dataviz_mini_project1.git


2. Open the R project file (`Mini Project 1.Rproj`) in RStudio.

3. Make sure you have the necessary libraries installed by running the following command:

```R
install.packages(c("tidyverse", "ggplot2"))
```
4. Open the Mini Project 1 - Marathon results.Rmd file and run the code chunks to perform the analysis and generate the visualizations.

## Results

The analysis of the marathon data from 2017 yielded the following insights:

- The highest number of finishers fell within the age group of 40-45, followed closely by the age group of 45-50. The number of finishers gradually increased with age until the mid-40s, and then it started gradually decreasing with increasing age.
![](https://github.com/MownikaKonamaneni/Dataviz_mini_project1/blob/main/Figures/Number%20of%20finishers%20by%20age%20group.jpg)
- The age distribution of finishers followed a relatively normal distribution with a peak in the mid-40s. This finding suggests that we have high number of finishers in mid 40s compared to other age groups.
![](https://github.com/MownikaKonamaneni/Dataviz_mini_project1/blob/main/Figures/Age%20distribution%20of%20finishers.jpg)
- There were differences in the age distribution based on gender. The age distribution of female finishers was on a lower scale compared to male finishers, indicating that, on average, female finishers have a lower age compared to male finishers.
![](https://github.com/MownikaKonamaneni/Dataviz_mini_project1/blob/main/Figures/Age%20distribution%20based%20on%20gender.jpg)
- The majority of marathon finishers were male, accounting for approximately 55% of the total finishers, while female participants constituted around 45%.
![](https://github.com/MownikaKonamaneni/Dataviz_mini_project1/blob/main/Figures/Gender%20specific%20finishers.jpg)
- The top 10 countries with the fastest runners, based on average finishing time, included Zimbabwe, Kenya, Brunei, and Ethiopia. These countries stood out as leading countries in terms of marathon performance, with only minor differences distinguishing them. Notably, Zimbabwe emerged as the country with the fastest runners.
![](https://github.com/MownikaKonamaneni/Dataviz_mini_project1/blob/main/Figures/Top%2010%20countries.jpg)

## Conclusion

This project report presented an analysis of marathon data from the year 2017. The analysis included exploring the number of finishers by age group, visualizing the age distribution of finishers, investigating the age distribution based on gender, and determining the top 10 countries with the fastest runners based on average finishing time. 

The findings from this analysis provide valuable insights into the demographics and performance of marathon runners. Understanding the age distribution, participation trends, and top-performing countries can be useful for marathon organizers, trainers, and participants in planning and improving future marathons.

Further analysis could be conducted to explore additional factors such as performance by age and gender, regional variations in marathon participation, and correlations between finishing time and other variables like weather conditions or training regimes.

Feel free to explore the detailed project report for more in-depth analysis, code implementation, and visualizations.

