# Restaurant Success Analysis Using YELP Dataset 🍽️📊

This project leverages the **Yelp dataset** to analyze the relationship between **user engagement** (reviews, tips, and check-ins) and business success metrics such as **review count** and **average star rating** for restaurants. The raw data is first converted into a **JSON file** for easier manipulation, and then Python and SQL are used to perform the analysis.

## 📝 Problem Statement

In the competitive restaurant industry, understanding the factors that contribute to business success is vital for stakeholders. This project aims to investigate how **user engagement** influences **business success**, measured through **review counts** and **ratings**.

## 🎯 Research Objectives

- **Quantify the correlation** between user engagement (reviews, tips, check-ins) and review count/average star rating: 
  - This will help determine if restaurants with higher user engagement see an increase in reviews and ratings.

- **Analyze the impact of sentiment** on review count and star ratings:
  - Investigate whether **positive sentiment** in reviews and tips is associated with higher star ratings and a greater number of reviews.

- **Explore time trends** in user engagement:
  - Determine if **consistent user engagement** over time is a stronger indicator of long-term success compared to sporadic bursts of activity.

## 🧪 Hypothesis Testing

1. 📈 **User Engagement Hypothesis**: Higher levels of user engagement (more reviews, tips, and check-ins) correlate with higher review counts and ratings for restaurants.

2. 😀 **Sentiment Hypothesis**: Positive sentiment in reviews and tips contributes to higher overall ratings and review counts for restaurants.

3. ⏳ **Consistency Hypothesis**: Consistent engagement over time is positively associated with sustained business success for restaurants.

## 🔧 Data Processing and Analysis

1. **Raw Data Conversion**:
    - The raw data from the Yelp dataset is first converted into a **JSON file** for better data handling and structured analysis.

2. **SQL & Python Integration**:
    - **SQL** is used to store and manage the dataset efficiently.
    - **Python** is used for data extraction, transformation, and performing statistical analysis on user engagement and success metrics.

## 🔧 Installation

To use this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/restaurant-success-analysis.git
    cd restaurant-success-analysis
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up the dataset**:
    - Convert the raw Yelp dataset into a JSON file as per the instructions in the `data/README.md`.
    - Load the JSON file into the SQL database using provided scripts.

4. **Run analysis scripts**:
    ```bash
    python analysis.py
    ```

## 📂 Project Structure

- **Raw Data**: Contains raw data in CSV or other formats.
- **JSON Data**: Data converted into JSON format.
- **SQL**: SQL is used for querying and managing large datasets efficiently.
- **Python**: The project uses Python for data processing, analysis, and visualization.

## 🖼️ Example Visualizations

You can visualize correlations, sentiment analysis results, and engagement trends over time using this project’s generated plots.


## 🤝 Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for any suggestions or improvements.

## 📝 License

This project is licensed under the MIT License.

---

Made with 💡 and Python.
