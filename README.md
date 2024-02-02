# CUSTOMER HOTEL BOOKING ANALYSIS
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


![customer hotel booking analysis](https://github.com/RAm-SaGar-863/Hotel-Booking-Exploratory-Data-Analysis_Capston_Project_1/assets/128234583/04239dd6-4f15-469c-9c86-945bf8e77dc3)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


## Abstract
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

This exploratory data analysis (EDA) project scrutinizes a hotel booking dataset comprising both City and Resort hotels. With meticulous data cleaning and manipulation, including addressing duplicates and missing values, the analysis unveils key insights. Findings encompass cancellation trends, seasonal booking patterns, room preferences, and the impact of online travel agents. The project highlights distinctions between resort and city hotels, offering actionable intelligence for strategic decision-making in the dynamic hotel industry.

## Problem Statement
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyze the data to discover important factors that govern the bookings.


## Project Summary
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

In this comprehensive exploratory data analysis (EDA) project, our primary focus was on dissecting a Hotel Booking dataset consisting of two distinct hotel types: City Hotel and Resort Hotel, housing a total of 119,390 rows across 32 columns.

The dataset exhibited a diverse range of data types, including Object, float64, and int64. One of our initial challenges was addressing the presence of duplicates and missing values. We diligently handled these issues, meticulously replacing missing data and purging the dataset of duplicates. Notably, the 'Company' column contained a staggering 112,593 null values, while 'Agent,' 'Country,' and 'Children' columns also required special attention due to missing data.

Our data manipulation workflow was structured into three main categories: Data Collection, Data Cleaning & Manipulation, and Exploratory Data Analysis (EDA). To kickstart the process, we employed essential functions and attributes such as 'head(),' 'tail(),' 'info(),' 'describe(),' and 'columns()' to gain an initial understanding of the dataset.

Further into the project, we explored the uniqueness of values in each column, generating lists and summarizing unique values for deeper insights. Additionally, we fine-tuned the column data types to ensure accuracy, introducing new columns such as 'total_people' and 'total_stay' for enhanced analysis.

The Data Cleaning phase involved rectifying inaccuracies in data types and purging duplicate entries, a significant step considering the identification of 31,994 duplicate items within the dataset. Furthermore, we identified rows where the combined values of adults, babies, and children equaled zero, indicating non-existent bookings, and promptly removed them.

For better data utilization, we transformed the 'reservation_status_date' column from an object type to a date type.

Prior to data visualization, thorough data wrangling was crucial. Null values were assessed across all columns, and minimal nulls were addressed through the 'fillna()' method.

Subsequently, we delved into data visualization, employing various charts to gain deeper insights into the dataset. The visualization process aimed to uncover pivotal factors influencing hotel bookings, ultimately providing valuable business insights to bolster the hospitality industry.

In essence, this project revolved around the extensive exploration and analysis of the dataset, unearthing critical factors that govern hotel bookings. The findings and insights derived from this EDA endeavor hold the potential to significantly impact and enhance business outcomes in the hotel industry.

## Conclusion
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

In this analysis, we explored a hotel booking dataset to gain insights into various aspects of hotel bookings, cancellations, customer preferences, and trends. The dataset contained information about different hotel types, customer types, booking channels, market segments, room types, and more. Through data visualization and analysis, several key findings emerged:

- City hotels are the most preferred hotel type by the guests so the Waiting time period for City hotel is high as compared to resort hotels. That means city hotels are much busier than Resort hotels.
- 27.5 % bookings were got cancelled out of all the bookings and the booking cancellation rate is high for City hotels which is almost 30 %.
- 79.1 % bookings were made through TA/TO (travel agents/Tour operators).
- Maximum number of guests were from Portugal, i.e. more than 25000 guests.
- Most of the customers (91.6%) do not require car parking spaces.
- The most preferred room type varied among different customer types. Resort hotels were favored for their suite rooms, while city hotels were chosen for standard rooms.
- Staying patterns showed variations over different years. The majority of stays were short, with a peak around 3-4 nights for both hotel types.
- There was a trend of higher cancellations for bookings made further in advance. Lead time played a role in cancellation decisions.
- Bookings were distributed across different months, with the summer months showing higher activity. Resort hotels saw an increase in bookings during the summer, whereas city hotels had more consistent bookings throughout the year.


