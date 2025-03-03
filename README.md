# Hotel-Booking-Demand

## Abstract
This data article describes two datasets with hotel demand data. One of the hotels (H1) is a resort hotel and the other is a city hotel (H2). Both datasets share the same structure, with 31 variables describing the 40,060 observations of H1 and 79,330 observations of H2. Each observation represents a hotel booking. Both datasets comprehend bookings due to arrive between the 1st of July of 2015 and the 31st of August 2017, including bookings that effectively arrived and bookings that were canceled. Since this is hotel real data, all data elements pertaining hotel or costumer identification were deleted. Due to the scarcity of real business data for scientific and educational purposes, these datasets can have an important role for research and education in revenue management, machine learning, or data mining, as well as in other fields.


## Value of the data

    • Descriptive analytics can be employed to further understand patterns, trends, and anomalies in data;
    • Used to perform research in different problems like: bookings cancellation prediction, customer segmentation, customer satiation, seasonality, among others;
    • Researchers can use the datasets to benchmark bookings’ prediction cancellation models against results already known;
    • Machine learning researchers can use the datasets for benchmarking the performance of different algorithms for solving the same type of problem (classification, segmentation, or other);
    • Educators can use the datasets for machine learning classification or segmentation problems;
    • Educators can use the datasets to obtain either statistics or data mining training.

## Data
In tourism and travel related industries, most of the research on Revenue Management demand forecasting and prediction problems employ data from the aviation industry, in the format known as the Passenger Name Record (PNR). This is a format developed by the aviation industry [2]. However, the remaining tourism and travel industries like hospitality, cruising, theme parks, etc., have different requirements and particularities that cannot be fully explored without industry׳s specific data. Hence, two hotel datasets with demand data are shared to help in overcoming this limitation.
The datasets now made available were collected aiming at the development of prediction models to classify a hotel booking׳s likelihood to be canceled. Nevertheless, due to the characteristics of the variables included in these datasets, their use goes beyond this cancellation prediction problem.
One of the most important properties in data for prediction models is not to promote leakage of future information [3]. In order to prevent this from happening, the timestamp of the target variable must occur after the input variables’ timestamp. Thus, instead of directly extracting variables from the bookings database table, when available, the variables’ values were extracted from the bookings change log, with a timestamp relative to the day prior to arrival date (for all the bookings created before their arrival date).
Not all variables in these datasets come from the bookings or change log database tables. Some come from other tables, and some are engineered from different variables from different tables. A diagram presenting the PMS database tables from where variables were extracted is presented in Fig. 1. A detailed description of each variable is offered in the following section.
