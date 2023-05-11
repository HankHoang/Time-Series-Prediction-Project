# Time Series Prediction Project
## Time Series Prediction on LA Crime Dataset

The dataset records instances of criminal activities in Los Angeles starting in 2020. The information is transcribed from written crime reports, which may contain errors. Some location fields may have missing data and are indicated as (0°, 0°), while address fields only provide approximate information to protect privacy. 

*The project is to predict the possible time in which illegal behaviors can happen in the future. Therefore it can support the police department in preparing and preventing criminals in time.*

* Experiment EDA with 5000 rows of the dataset showed nearly similar EDA results with the original dataset(690454 observations).
* Refining the original data into day and month series with occurrences.
* The fluctuation range of the number of crimes tends to increase from 2020 to 2022.
* The massive amount of criminal activities happened in the first couple days of every month (from the 1st to the 3rd of a month), with more than 800 cases. An exception was the day 2020-05-30 with 912 cases.
* ARIMA and RNN models did not capture the pattern that the illegal occurrences often reach high values every first month.
* ARIMA model is able to predict the suitable average number of crime activities in a day but fails to predict precisely the figures close to the actual number in the report(misprediction of around 60 cases on average). Therefore, the ARIMA model is not reliable in prediction with this dataset.

## Further Developments:
* Require more data and information or even studies to build high accuracy in a time series model, such as criminal psychology research to identify attributes causing illegal behaviors.
* Finding a suitable approach with up-to-date, relevant articles or research.

Link to the dataset: https://catalog.data.gov/dataset/crime-data-from-2020-to-present
