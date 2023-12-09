# ABOUT THE PROJECT
Bluemazon is an E-Commerce that focuses on selling electronic items. The company has run the business for some year and want to improve its sales strategy. They want to analyze 2019 sales and generate insights from sales data, trends, and metrics to set targets. They need data analysts to provide insights about the top-performing and underperforming products, the problems in selling and market opportunities, and sales activities that generate revenue.

### Goals and Objective
- Generate insight and recommendations based on 2019 sales data.
- Process and Analyze the dataset to create a bundle of recommendations.

### Getting Started
To run this project you will need a Jupyter notebook to run data analysis.

### Built with 
[![Python][Python.com]][Python-url] [![Jupyter][Jupyter.com]][Jupyter-url]
<a href="https://pandas.pydata.org/">
    <img src="https://img.shields.io/badge/pandas-000000?style=for-the-badge&logo=pandas&logoColor=white" alt="Logo" >
</a>
<a href="https://matplotlib.org/stable/index.html">
    <img src="https://img.shields.io/badge/matplotlib-000000?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Logo" >
</a>
<a href="https://seaborn.pydata.org/index.html">
    <img src="https://img.shields.io/badge/seaborn-000000?style=for-the-badge&logo=seaborn&logoColor=white" alt="Logo" >
</a>
  
### Prerequisites
These are some libraries you need to run the project, I put the pip installation to make it easy for you.

```sh
pip install pandas
```
```sh
pip install matplotlib
```
```sh
pip install seaborn
```

### Resources
For more detailed dataset information visit <a href='https://www.kaggle.com/datasets/knightbearr/sales-product-data?datasetId=1695352&sortBy=voteCount'>kaggle</a> page.

Available data are 12 CSV files for each month's sales data for the year 2019. Datasets were concatenated resulting in 186,850 orders data. The dataset contains 545 null values and some unmatch feature data types. Extract some features such as month, day, hour, city, and sales.

<img src="images/image1.png" alt="Logo" width="500" height="auto">

Customers mostly order 1 item at once, some small groups order 2 items at once, highest orders are for 9 items at once. Sales for each order are in the range 2.99 to 3400. Distribution for sales and Price Each relatively the same it is because most quantity order is 1. Summary sales 2019, total revenue <b>34,483,365.68 USD, 185,916 orders and 209,038 items sold.</b>

<img src="images/image2.png" alt="Logo" width="500" height="auto">

Most of the orders are from California (CA), San Francisco and Los Angeles with more than 40,000 and 30,000 orders. Average orders in cities are around 18,000 orders.

<img src="images/image3.png" alt="Logo" width="500" height="auto">

High orders happen in December and October have 25,000 and 20,000 orders. There are increasing pattern orders in January to April then a decrease in September.

<img src="images/image4.png" alt="Logo" width="500" height="auto">

There is a peak of sales from around 9:00 to 21:00. This pattern can be a good spot to promote products to increase sales.

<img src="images/image5.png" alt="Logo" width="500" height="auto">

The top products sold are Battery products, followed by Charging cables, and Headphones.

### Some Useful Insight

##### Product Combination 
There are some frequent combinations of products in customer order behaviour. Most of the combinations are in the : 

<img src="images/image6.png" alt="Logo" width="300" height="auto">

- Phone product + Charging cable 
- Phone product + Headphone
- Charging cable + Headphone
- This data can support product bundling to increase sales of specific products.

##### Rush Hour 
There is a peak of sales from around 9:00 to 21:00. It means that in this time range most customers tend to place orders. This peak can be a sweet spot to promote advertising.

<img src="images/image4.png" alt="Logo" width="500" height="auto">
This data can be supported to post more ads on the rush hour time span.

##### Order Probability 
Charging cables have relatively the same probability. iPhone has a higher probability than Google Phone. Wired Headphones have the highest order probability on headphone product type.

<img src="images/image7.png" alt="Logo" width="500" height="auto">
This data can support having more product stock and marketing on higher product order probability.



[Python.com]: https://img.shields.io/badge/python-000000?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[VScode.com]: https://img.shields.io/badge/vscode-000000?style=for-the-badge&logo=visual-studio-code&logoColor=white
[VScode-url]: https://code.visualstudio.com/
[Jupyter.com]: https://img.shields.io/badge/jupyter-000000?style=for-the-badge&logo=jupyter&logoColor=white
[Jupyter-url]: https://jupyter.org/
[Selenium.com]: https://img.shields.io/badge/selenium-000000?style=for-the-badge&logo=selenium&logoColor=white
[Selenium-url]: https://www.selenium.dev/
[BS.com]: https://img.shields.io/badge/Beautifulsoup-000000?style=for-the-badge&logo=&logoColor=white
[BS-url]: https://www.crummy.com/software/BeautifulSoup/bs4/doc/
[pandas.com]: https://pandas.pydata.org/
[pandas-url]: https://img.shields.io/badge/pandas-000000?style=for-the-badge&logo=&logoColor=white
[matplotlib.com]: https://matplotlib.org/stable/index.html
[matplotlib-url]: https://img.shields.io/badge/matplotlib-000000?style=for-the-badge&logo=matplotlib&logoColor=white
[seaborn.com]: https://seaborn.pydata.org/index.html
[seaborn-url]: https://img.shields.io/badge/seaborn-000000?style=for-the-badge&logo=seaborn&logoColor=white
