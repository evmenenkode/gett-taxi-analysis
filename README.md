# GetTaxi Order Analysis

## Overview
This project focuses on analyzing GetTaxi order data to understand the distribution of failed orders, cancellation trends, and average ETA variations by hour. The analysis includes plotting the distribution of orders based on reasons for failure, examining the distribution of failed orders by hour, comparing the average time to cancellation with and without a driver assigned, and exploring the distribution of average ETA by hour. Additionally, the project includes a bonus task of visualizing the geographical distribution of orders using H3 hexagons.

## Dataset
The dataset used in this project contains information about GetTaxi orders, including:

- Order date and time
- Origin longitude and latitude
- Estimated time of arrival (ETA)
- Order status key
- Driver assignment status
- Cancellation time in seconds
## Assignment Tasks
1. Distribution of Orders According to Reasons for Failure: Build a distribution of orders based on reasons for failure, including cancellations before and after driver assignment and reasons for order rejection. Analyze the resulting plot to identify the category with the highest number of orders.
2. Distribution of Failed Orders by Hours: Plot the distribution of failed orders by hours to identify any trends or abnormally high proportions of specific categories. Determine the hours with the highest proportion of failed orders and provide an explanation.
3. Average Time to Cancellation with and without Driver, by Hour: Plot the average time to cancellation with and without a driver assigned, categorized by the hour of the order. Remove any outliers from the data and draw conclusions based on the plot.
4. Distribution of Average ETA by Hours: Plot the distribution of average ETA by hours to understand variations throughout the day. Provide an explanation for the observed trends.
5. Hexagons Visualization: Utilize the h3 and folium packages to calculate the number of size 8 hexes containing 80% of all orders from the original dataset. Visualize the hexes on a map, coloring them based on the number of failed orders.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, folium, h3

## Instructions
Clone this repository to your local machine.
Ensure that you have the necessary Python libraries installed (listed in the requirements section).
Run the provided Python scripts in the specified order to perform data analysis and visualization.
Review the generated plots and insights to understand various aspects of the GetTaxi order data.
Customize the analysis or visualization as needed for your specific requirements.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any suggestions or improvements.
