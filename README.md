
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You need to have a Python 3.x environment. I used anaconda. This project uses some packages, which you might need to install using the statement "pip install my_package" in your conda console.

Used special packages:
* pydotplus (optional for visualization of Decision Trees)


## Project Motivation<a name="motivation"></a>

I used the WHO life expectancy data set from Kaggle (https://www.kaggle.com/kumarajarshi/life-expectancy-who) to answer some business questions:
1)	How do developing countries differ from developed ones in terms of Life expectancy?
2)	Is there a development within the Life expectancy over the years?
3)	Does Immunization have an impact on the life expectancy?
4)	Is there a coherence between Total expenditure and infant deaths / Adult mortality?
5)	Can a prediction model be derived from the data set?


## File Descriptions <a name="files"></a>

* WHO_LifeExpactancy-final.ipynb contains the analysis with output written in python and used in Jupyter Notebook / Jupyter Lab
* data_in/Life Expectancy Data.csv the data set which can also be downloaded from Kaggle
* data_out/model_dtc_status.png a visualized decision tree

## Results<a name="results"></a>

The findings to the previously defined business questions are discussed in this [blogpost on medium](https://medium.com/@MatthiasSchroeder/who-life-expectancy-how-to-live-longer-2377738f948a)

Short conclusion:
The WHO life expectancy data set reveals some interesting relations between social and economic characteristics in relation to their life expectancy. It is shown that the correlation between life expectancy and higher expenditures is given, while countries with lower immunization tend to compensate this by increased expenditures on healthcare.
On the downside the quality of the provided data set on Kaggle is poor to moderate: missing values are easier to handle, but wrong data points like total expenditure, population, developing/develop classification limits the business conclusions. It is recommended to do the analysis on a better data set with plausible data points. 


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I used the data from Kaggle. All the licensing for the data and other information can be found on [Kaggle](https://www.kaggle.com/kumarajarshi/life-expectancy-who)
