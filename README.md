
# Retail Price and Yield Analysis of Vegetables and Fruits

## Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on a dataset containing retail price information for various fruits and vegetables. The goal is to understand the relationships between various features such as price, yield, and equivalent cup sizes. In addition, we explore pricing trends and how they vary across different forms (fresh, canned, etc.) and categories.

## Problem Statement
The project aims to provide **insights into retail price trends** for fruits and vegetables, along with their yield and price per unit of volume. By analyzing the dataset, we hope to uncover patterns and trends that can help stakeholders in the agriculture and retail sectors make informed decisions.

## Data Description
The dataset contains information on the following columns:

- **Vegetable/Fruit**: The name of the vegetable or fruit.
- **Form**: The form in which the product is available (e.g., fresh, canned).
- **RetailPrice**: The retail price of the product.
- **RetailPriceUnit**: The unit of measurement for the retail price.
- **Yield**: Yield of the vegetable or fruit.
- **CupEquivalentSize**: The equivalent size of the fruit or vegetable in cups.
- **CupEquivalentUnit**: The unit of measurement for the cup equivalent size.
- **CupEquivalentPrice**: The price per equivalent cup size.

## Key Steps Taken in the Analysis
1. **Data Cleaning**: Handling missing values and correcting data types.
2. **Exploratory Data Analysis (EDA)**: Investigating the relationship between the various features, and visualizing the data to understand trends.
3. **Data Visualizations**: Generating various plots such as:
   - Histograms and Boxplots for understanding price distributions.
   - Pair plots to examine relationships between numerical variables.
   - Treemaps and bar charts for visualizing categorical variables.
4. **Feature Engineering**: Creating new features like price per unit yield to assess the efficiency of different vegetables and fruits.

## Key Findings
- Retail prices and yield data show interesting trends for different vegetables and fruits.
- The equivalent cup size for different forms (fresh, canned, etc.) also significantly affects the price.
- Certain vegetables and fruits have more consistent pricing across various forms than others.

## Technologies and Libraries Used
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib & Seaborn**: For visualizations.
- **Squarify**: For creating treemaps.
- **Scikit-learn**: For label encoding and other preprocessing tasks.

## Installation
To run this project, you need to have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn squarify
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vegetable-fruit-price-analysis.git
   cd vegetable-fruit-price-analysis
   ```
2. Install the necessary libraries as mentioned above.
3. Run the Jupyter notebook for EDA and visualizations:
   ```bash
   jupyter notebook analysis.ipynb
   ```

## Kaggle Notebook
For an interactive version of this analysis, you can view and run the Kaggle notebook here:  
[Kaggle Notebook: Retail Price and Yield Analysis of Vegetables and Fruits](https://www.kaggle.com/code/miadul/data-analysis-and-price-insights-of-fruits-and-veg)

## YouTube Video
Watch the video walkthrough of this project on YouTube:  
[YouTube: Retail Price and Yield Analysis of Vegetables and Fruits](https://www.youtube.com/watch?v=your_video_id)

## LinkedIn Profile
Feel free to connect with me on LinkedIn:  
[LinkedIn Profile: Arif Miah](www.linkedin.com/in/arif-miah-8751bb217)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

