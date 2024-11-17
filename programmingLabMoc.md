### **Instructions: Q-1**  

1. **Generate Sales Data:**  
   - Create a Python dictionary named `sales_data` to store sales figures for four product categories:  
     - `Electronics`  
     - `Clothing`  
     - `Groceries`  
     - `Furniture`  
   - Each category should have a list of 12 random integers (representing sales figures in thousands of dollars), one for each month (January to December).  
   - Use the `random` module to generate these figures (range: 50–500).  

---

2. **Perform Data Analysis:**  
     - Write a function `calculate_average_sales(sales_data)` to:  
     - Calculate the monthly average sales for each category.  
     - Return a new dictionary `average_sales` with product categories as keys and their average sales as values.  
   - Write a function `get_sales_growth(sales_data)` to:  
     - Calculate the percentage sales growth (or decline) for each category by comparing December’s sales with January’s sales.  
     - Return a dictionary `sales_growth` with categories as keys and percentage growth as values.  

---

3. **String Operations:**  
   - **Generate Descriptive Summaries:**  
     Write a function `generate_category_summary(sales_data)` that generates a summary string for each category. For example:  
     ```  
     Electronics:  
     - Average Monthly Sales: $375,000  
     - Sales Growth: 12.5%  
     ```  
     Format the output neatly using string formatting techniques (e.g., `f-strings`, `str.format()`).  

   - **Search for Keywords:**  
     Write a function `search_category_by_keyword(sales_data, keyword)` that:  
     - Accepts a keyword input by the user.  
     - Searches for categories whose descriptions contain the keyword (case-insensitive).  
     - Returns matching categories and their total yearly sales.  

---

4. **Data Visualization:**  
   - **Line Chart:** Plot monthly sales trends for all categories (one line per category).  
   - **Pie Chart:** Show the percentage contribution of each category to the average yearly sales.  
   - **Scatter Plot:** Show the relationship between sales growth percentages (x-axis) and average yearly sales (y-axis) for each category.   
---


### **Instructions: Q-2**  

You are tasked with analyzing a dataset containing weather information for a fictional city over a year. Your objective is to process, analyze, and visualize this data to uncover trends and patterns.  

### **Dataset Structure:**  
The CSV file contains the following columns:  
- `Date`: The date of the observation (YYYY-MM-DD).  
- `Temperature (°C)`: The daily average temperature in Celsius.  
- `Humidity (%)`: The daily average humidity in percentage.  
- `Rainfall (mm)`: The total rainfall on that day in millimeters.  
- `Wind Speed (km/h)`: The average wind speed on that day in kilometers per hour.  
- `Weather Condition`: A categorical variable indicating the general weather condition (e.g., `Sunny`, `Cloudy`, `Rainy`, `Stormy`).  

---



#### **Step 1: Import and Explore the Data**  
1. Write a Python script to:  
   - Import the required libraries (`pandas`, `numpy`, `matplotlib`).  
   - Load the CSV file into a Pandas DataFrame.  
   - Display the first 10 rows of the DataFrame.  
   - Print a summary of the DataFrame, including column names, data types, and non-null counts.  

2. Check for missing values:  
   - If there are missing values, fill them with appropriate values:  
     - Use the mean for numerical columns (`Temperature`, `Humidity`, `Rainfall`, `Wind Speed`).  
     - Use the mode for categorical columns (`Weather Condition`).  

---

#### **Step 2: Data Processing and Analysis**  
1. **Daily Comfort Index:**  
   - Add a new column `Comfort Index` to the DataFrame using the formula:  
     ```python
     Comfort Index = (100 - Humidity) + (30 - abs(Temperature - 20))  
     ```  
     This index indicates how "comfortable" the weather was (higher values are more comfortable).  

2. **Weather Condition Analysis:**  
   - Calculate the number of days each weather condition (`Sunny`, `Cloudy`, etc.) occurred.  
   - Find the weather condition that occurred most frequently.  

3. **Monthly Analysis:**  
   - Convert the `Date` column to a `datetime` object.  
   - Group the data by `Month` and calculate:  
     - The average temperature, humidity, and wind speed for each month.  
     - The total rainfall for each month.  

4. **Extreme Conditions:**  
   - Identify the hottest and coldest days of the year, along with their dates.  
   - Identify the day with the highest rainfall and the day with the strongest wind speed.  

5. **Statistical Summary with NumPy:(bonus)**  
   - Use NumPy to calculate the following statistics for the `Temperature` and `Rainfall` columns:  
     - Mean  
     - Median  
     - Standard Deviation  
     - 90th Percentile  

---

#### **Step 3: Data Visualization**  
1. **Bar Chart:**  
   - Plot the total monthly rainfall.  

2. **Line Chart:**  
   - Plot the average monthly temperature, humidity, and wind speed on the same graph (use different colors for each metric).  

3. **Pie Chart:**  
   - Show the percentage distribution of weather conditions over the year.  

4. **Scatter Plot:**  
   - Create a scatter plot showing `Temperature (x-axis)` vs. `Humidity (y-axis)` with point sizes based on `Rainfall`.  

---

#### **Step 4: Save and Export the Results**  
1. Save the processed DataFrame (with the new `Comfort Index` column) to a new CSV file named `processed_weather_data.csv`.  
2. Save the visualizations as image files (e.g., PNG format) for inclusion in your report.  

---
