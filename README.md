#  Tesla and GameStop Stock & Revenue Data Analysis

This Jupyter Notebook contains Python code to extract historical stock price and revenue data for **Tesla (TSLA)** and **GameStop (GME)**, process the data into pandas DataFrames, and visualize the trends.


##  Features

* Extracts stock price data using `yfinance`
* Scrapes revenue data from online sources 
* Converts both datasets into `pandas` DataFrames
* Cleans and formats the data
* Creates graphs to visualize:

  * Historical share prices
  * Historical revenue trends


##  Files

* `Final Assignment.ipynb`: Main Jupyter Notebook with all code and plot
* `README.md`: Documentation for the project


##  Technologies Used

* Python 3.x
* Jupyter Notebook
* Libraries:

  * `pandas`
  * `matplotlib`
  * `yfinance`
  * `requests`
  * `BeautifulSoup` (for web scraping)


##  Output

The notebook generates:

* Charts of Tesla and GameStop stock prices over time
* Charts of Tesla and GameStop quarterly revenue


##  Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/datum-carin/Coursera_PyProjectForDataScience.git
cd Coursera_PyProjectForDataScience
```

### 2. Install dependencies

Make sure you have Jupyter and the necessary libraries installed:

```bash
pip install yfinance pandas matplotlib requests beautifulsoup4
```

### 3. Launch the notebook

```bash
jupyter notebook Final Assignment.ipynb
```


##  Notes

* Revenue data is scraped from online sources and may change structure; inspect HTML if errors occur.
* Always handle web scraping responsibly and check the website's terms of use.


##  License

This project primarily contains materials provided by IBM Corporation, along with some of my own additions.

This project includes content © IBM Corporation 2020. All rights reserved.  
The content is provided for educational purposes only and may not be reused, redistributed, or modified without explicit permission from IBM.

Please refer to the original source or course terms for additional licensing details.



##  Author

* **Carin**
  [GitHub](https://github.com/Carinelia)

