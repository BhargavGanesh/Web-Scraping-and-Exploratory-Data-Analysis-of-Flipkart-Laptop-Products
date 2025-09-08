# Flipkart Web Scraping & EDA Project  
This project involves web scraping laptop product listings from Flipkart and performing Exploratory Data Analysis (EDA) to analyze specifications, pricing, ratings, and reviews.

## Project Overview
- **Web Scraping:**
Automated extraction of laptop details from Flipkart using Python (requests, BeautifulSoup).
- **Data Extraction:** 
Product Name,
Product Price,
Processor,
RAM,
Operating System,
SSD Storage,
Display Information,
Warranty,
Ratings,
Reviews.

- **EDA & Visualization:**
Price distribution by processor & RAM.
Correlation between ratings/reviews and price.
Popular configurations (e.g., OS, SSD size).
Insights into warranty offerings and display types.

## Structure
- **Flipkart_Laptop_EDA.ipynb** ---Main notebook (scraping + analysis).
- **README.md** ---Project Documentation.
- (Optional: data files if available)

## Technologies Used
- Python 3.x
- Jupyter Notebook
- requests
- BeautifulSoup4
- pandas
- matplotlib
- seaborn
  
## Steps in the Project
### 1. Web Scraping 
- Sent HTTP requests to Flipkart laptop listings.
- Parsed HTML with BeautifulSoup.
- Extracted product details into structured format.

### 2. Data Cleaning
- Removed missing/invalid values.
- Converted Product_Price, Ratings, Reviews, SSD into numeric formats.
- Standardized column names and data types.

### 3. Exploratory Data Analysis (EDA)
- Distribution of laptop prices.
- Average price vs. processor type (i3, i5, i7, Ryzen, etc.).
- RAM size impact on pricing.
- Ratings and reviews analysis.
- Warranty and SSD storage trends.

### 4. Visualization
- Bar plots, count plots, and histograms using Seaborn and Matplotlib.
- Price vs. Ratings scatter plots.
- Popular configurations vs review counts.

## How to Run This Project
1. Clone/download this repository.
2. Open the notebook file (Flipkart_Laptop_EDA.ipynb) in Jupyter Notebook.
3. Run each cell sequentially to replicate scraping, analysis, and visualization.
4. Ensure you have an active internet connection and required packages installed: pip install requests beautifulsoup4 pandas matplotlib seaborn.

## Notes
- This project is for educational purposes only.
- Always respect Flipkart’s Terms of Service and robots.txt when scraping.
- Requires an active internet connection for scraping.

## Author
Karri Bhargav Ganesh
