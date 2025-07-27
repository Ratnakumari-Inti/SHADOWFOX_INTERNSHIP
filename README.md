## Project Structure

* SHADOWFOX\_\_LEVEL2.ipynb – Main Jupyter Notebook with analysis
* delhiaqi.csv – Raw AQI dataset (Delhi Jan 2023)
* shadowfox\_LEVEL1.pdf – Level 1 documentation (Matplotlib vs Seaborn)
* shadowfox\_LEVEL2.pdf – Level 2 walkthrough report
## Objectives

* Load and clean Delhi AQI data
* Explore pollutant trends over time
* Identify peak pollution hours and days
* Compare weekday vs weekend air quality
* Evaluate safety limits against WHO standards
* Visualize data with Matplotlib & Seaborn

## Dataset Information

* **Source**: Kaggle / Central Pollution Control Board (adapted sample)
* **Format**: CSV
* **Period**: January 2023
* **Features**: `date`, `co`, `no`, `no2`, `o3`, `so2`, `pm2_5`, `pm10`, `nh3`

## Technologies Used

* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## How to Run

1. Clone this repo or download the files.
2. Launch Jupyter Notebook:
   `jupyter notebook SHADOWFOX__LEVEL2.ipynb`
3. Install required libraries:
   `pip install pandas matplotlib seaborn`
4. Run each cell to explore the analysis.

## Key Features

### Data Preparation

* Loaded CSV using `pandas.read_csv()`
* Converted `date` column to datetime format
* Extracted features: hour, day, weekday/weekend

### Visualization Highlights

* **Hourly AQI Line Plot**: Identifies morning (6-10AM) and evening (6-10PM) pollution peaks
* **Boxplot**: Distribution of key pollutants (PM2.5, PM10, CO, NO2)
* **Correlation Heatmap**: Shows strong correlation between PM2.5 and PM10
* **Bar Chart by Weekday**: Reveals cleaner air on weekends
* **Exceedance Analysis**: Compares pollutant levels to WHO safety standards

### Research Questions Answered

1. When are pollution levels highest during the day?
2. Which pollutants exceed WHO safety limits the most?
3. How does air quality differ between weekdays and weekends?

## Final Insights

* PM2.5 and PM10 exceed safety limits 100% of the time
* Peak pollution observed at 5 PM (worst hour)
* Weekends show 34.8% improvement in air quality
* Morning and evening traffic hours align with AQI spikes

## References

* Matplotlib Documentation: [https://matplotlib.org/](https://matplotlib.org/)
* Seaborn Documentation: [https://seaborn.pydata.org/](https://seaborn.pydata.org/)
* WHO Air Quality Guidelines: [https://www.who.int/news-room/air-pollution](https://www.who.int/news-room/air-pollution)

## Credits

* Prepared by: Ratnakumari Inti
* Guide: SHADOWFOX Internship Program
* Date: July 2025

## License
This project is for educational and research purposes only.

