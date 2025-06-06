 cheena ji# ⚡ Electric Vehicles Market Size Analysis 🚗📊

This project presents a comprehensive analysis of the Electric Vehicle (EV) market using real-world registration data. It includes exploratory data analysis, visualizations, and forecasting using exponential growth models to estimate future EV adoption trends.

A deep dive into the evolution, distribution, and future of the Electric Vehicle (EV) market using real-world registration data.
“The electric vehicle revolution isn’t coming. It’s already here — and data is the road map.” 🧠

Market size analysis is a crucial aspect of market research that determines the potential sales volume within a given market. It helps businesses understand the magnitude of demand, assess market saturation levels, and identify growth opportunities.

## Electric Vehicles Market Size Analysis: 
## Process We Can Follow

Market size analysis for electric vehicles involves a multi-step process that includes defining the market scope, collecting and preparing data, analytical modelling, and communicating findings through visualization and reporting. Below is the process you can follow for the task of electric vehicles market size analysis:

1. Define whether the analysis is global, regional, or focused on specific countries.
2. Gather information from industry associations, market research firms (e.g., BloombergNEF, IEA), and government publications relevant to the EV market.
3. Use historical data to identify trends in EV sales, production, and market.
4. Analyze the market size and growth rates for different EV segments.
5. Based on the market size analysis, provide strategic recommendations for businesses looking to enter or expand in the EV market.

## 📁 Dataset

**Electric Vehicles Market Size Analysis using Python**
Now, let’s get started with the task of electric vehicles market size analysis by importing the necessary Python libraries and the dataset:

<img width="652" alt="Screenshot 2025-06-06 at 3 39 31 PM" src="https://github.com/user-attachments/assets/d65f985a-bcae-4a60-affa-df67202571b3" />


So, this data is based on the EV population in the United Sates. Now, lets clean the data.

<img width="677" alt="Screenshot 2025-06-06 at 3 40 28 PM" src="https://github.com/user-attachments/assets/07a85b1a-41f2-402b-bbc9-029306e5d863" />

<img width="700" alt="Screenshot 2025-06-06 at 3 40 50 PM" src="https://github.com/user-attachments/assets/d8db745f-d5ee-443d-947b-db43564c092d" />

For the task of market size of electric cehicles analysis, we can explore the following areas:

This project explores the growth and characteristics of electric vehicles registered over the years. It provides detailed exploratory data analysis, insightful visualizations, and forecast modeling to uncover:

1. **EV Adoption Over Time**: Analyze the growth of the EV population by model year.

2. **Geographical Distribution**: Understand where EVs are most commonly registered (e.g., by county or city).

3. **EV Types**: Breakdown of the dataset by electric vehicle type (BEV, etc.).
4. **Make and Model Popularity**: Identify the most popular makes and models among the registered EVs.

5. **Electric Range Analysis**: Analyze the electric range of vehicles to see how EV technology is progressing.

6. **Estimated Growth in Market Size**: Analyze and find the estimated growth in the market size of electric vehicles.


## 📌 Project Overview

1. EV adoption trends over time 🕰️
2. Popular makes & models 🏎️
3. City & county-level distributions 🗺️
4. Range statistics 🔋
5. Forecast of future EV adoption 🔮

## 🧪 Technologies Used
1. Python
2. Pandas – data loading, cleaning, and manipulation
3. Matplotlib & Seaborn – for visualizing trends and distributions
4. NumPy – numerical operations
5. SciPy – curve fitting and exponential forecasting

## 📈 Key Visual Insights

1. EV Adoption Over Time
2. Top Cities in Top Counties
3. Electric Vehicle Types Distribution
4. Top EV Manufacturers
5. Top EV Models in Leading Makes
6. Electric Range Distribution
7. Average Range by Model Year
8. Top Models by Average Electric Range
9. EV Market Forecast (2024–2029)

## Analysis:

## Plot 1

Let's start with analyzing the EV Adoption Over Time by visualizing the number of EVs registered by modal year. It will give us an insight into how the EV population has grown over the years:

<img width="1116" alt="Screenshot 2025-06-06 at 3 41 15 PM" src="https://github.com/user-attachments/assets/7935aef8-fe0b-43a2-bcff-56d138a709e9" />

From the above bar chart, it’s clear that EV adoption has been increasing over time, especially noting a significant upward trend starting around 2016. The number of vehicles registered grows modestly up until that point and then begins to rise more rapidly from 2017 onwards. The year 2023 shows a particularly sharp increase in the number of registered EVs, with the bar for 2023 being the highest on the graph, indicating a peak in EV adoption.

## Plot 2

Now, let’s start by selecting the top 3 counties based on EV registrations and then analyze the distribution of EVs within the cities of those counties:

<img width="631" alt="Screenshot 2025-06-06 at 3 44 51 PM" src="https://github.com/user-attachments/assets/8ea23fe0-7f25-48b5-8d8e-d1722f22ee86" />

The above graph compares the number of electric vehicles registered in various cities within three counties: King, Snohomish, and Pierce. The horizontal bars represent cities, and their length corresponds to the number of vehicles registered, colour-coded by county. Here are the key findings from the above graph:

1. Seattle, which is in King County, has the highest number of EV registrations by a significant margin, far outpacing the other cities listed.

2. Bellevue and Redmond, also in King County, follow Seattle with the next highest registrations, though these are considerably less than Seattle’s.

3. Cities in Snohomish County, such as Kirkland and Sammamish, show moderate EV registrations.

4. Tacoma and Tukwila, representing Pierce County, have the fewest EV registrations among the cities listed, with Tacoma slightly ahead of Tukwila.

5. The majority of cities shown are from King County, which seems to dominate EV registrations among the three counties.

6.Overall, the graph indicates that EV adoption is not uniform across the cities and is more concentrated in certain areas, particularly in King County.

## Plot 3

Next, let’s explore the types of electric vehicles represented in this dataset. Understanding the breakdown between different EV types, such as Battery Electric Vehicles (BEV) and Plug-in Hybrid Electric Vehicles (PHEV), can provide insights into consumer preferences and the adoption patterns of purely electric vs. hybrid electric solutions. So, let’s visualize the distribution of electric vehicle types to see which categories are most popular among the registered vehicles:

<img width="1038" alt="Screenshot 2025-06-06 at 3 45 13 PM" src="https://github.com/user-attachments/assets/491f0672-148d-41dd-8eaa-2b679541f16b" />

The above graph shows that BEVs are more popular or preferred over PHEVs among the electric vehicles registered in the United States.

## Pot 4

Let’s now focus on the popularity of electric vehicle manufacturers and models among the registered vehicles. This analysis will help us identify which manufacturers and specific models dominate the EV market, potentially indicating consumer preferences, brand loyalty, and the success of various manufacturers’ strategies in promoting electric mobility.
So, let’s have a look at the most popular manufacturers and then drill down into the most popular models within those manufacturers:

<img width="1124" alt="Screenshot 2025-06-06 at 3 45 31 PM" src="https://github.com/user-attachments/assets/ff66b037-73fb-40c6-bae9-1e58939a4b99" />

The above chart shows that:

1. TESLA leads by a substantial margin with the highest number of vehicles registered.

2. NISSAN is the second most popular manufacturer, followed by CHEVROLET, though both have significantly fewer registrations than TESLA.

3. FORD, BMW, KIA, TOYOTA, VOLKSWAGEN, JEEP, and HYUNDAI follow in decreasing order of the number of registered vehicles.

## Plot 5

Next, let’s drill down into the most popular models within these top manufacturers to get a more detailed understanding of consumer preferences at the model level:

<img width="654" alt="Screenshot 2025-06-06 at 3 46 51 PM" src="https://github.com/user-attachments/assets/4c22a712-d0bd-4159-b41f-941fc040208a" />

The above graph shows the distribution of electric vehicle registrations among different models from the top three manufacturers: TESLA, NISSAN, and CHEVROLET. Here are the findings:

1. TESLA’s MODEL Y and MODEL 3 are the most registered vehicles, with MODEL Y having the highest number of registrations.

2. NISSAN’s LEAF is the third most registered model and the most registered non-TESLA vehicle.

3. TESLA’s MODEL S and MODEL X also have a significant number of registrations.

4. CHEVROLET’s BOLT EV and VOLT are the next in the ranking with considerable registrations, followed by BOLT EUV.

5. NISSAN’s ARIYA and CHEVROLET’s SPARK have the least number of registrations among the models shown.

## Plot 6

Next, we’ll explore the electric range of vehicles, which is a critical factor for analyzing the market size of electric vehicles. The electric range indicates how far an EV can travel on a single charge, and advancements in battery technology have been steadily increasing these ranges over the years. So, let’s look at the distribution of electric ranges in the dataset and identify any notable trends, such as improvements over time or variations between different vehicle types or manufacturers:

<img width="1056" alt="Screenshot 2025-06-06 at 3 47 12 PM" src="https://github.com/user-attachments/assets/a9e9518e-ea87-467c-a469-76a72561fbfc" />

The above graph shows the mean electric range. Key observations from the graph include:

1.There is a high frequency of vehicles with a low electric range, with a significant peak occurring just before 50 miles.

2.The distribution is skewed to the right, with a long tail extending towards higher ranges, although the number of vehicles with higher ranges is much less frequent.

3.The mean electric range for this set of vehicles is marked at approximately 58.84 miles, which is relatively low compared to the highest ranges shown in the graph.

4.Despite the presence of electric vehicles with ranges that extend up to around 350 miles, the majority of the vehicles have a range below the mean.

It suggests that while there are EVs available with high electric ranges, the average range is skewed lower due to a substantial number of vehicles with shorter ranges.

## Plot 7

Now, let’s delve into the trend of electric ranges over model years, which can provide insights into how advancements in battery technology and vehicle design have influenced the electric range capabilities of electric vehicles over time. A positive trend in this analysis would indicate continuous improvements, offering consumers EVs with longer driving ranges and potentially addressing one of the major concerns regarding the EV market (range anxiety):

<img width="1056" alt="Screenshot 2025-06-06 at 3 47 26 PM" src="https://github.com/user-attachments/assets/7ee7ec5d-7e68-481b-8cfb-5963a3fb518d" />
