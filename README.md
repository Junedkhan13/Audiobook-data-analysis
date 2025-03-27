Audiobook Data Analysis

Project Overview:

This project focuses on cleaning, analyzing, and visualizing an audiobook dataset using Python in Jupyter Notebook. The dataset contains information about audiobooks, including titles, authors, narrators, duration, release dates, languages, star ratings, and prices. The goal is to uncover insights into audiobook pricing trends, language distribution, and ratings while ensuring data quality.

Dataset Description:

The dataset consists of multiple columns, including:

    name: Title of the audiobook
    
    author: Author(s) of the audiobook
    
    narrator: Narrator(s) of the audiobook
    
    time: Duration of the audiobook (in minutes)
    
    releasedate: Date of publication
    
    language: Language of the audiobook
    
    stars: Star ratings (some entries were originally 'Not rated yet')
    
    price: Price of the audiobook (some books were listed as 'free')

Data Cleaning Steps:

The dataset required preprocessing to ensure accuracy and consistency.

Key cleaning steps included:

Fixing 'price' column: Converted all values to float, replaced 'free' with 0.00, and removed commas.

Standardizing 'author' names: Added spaces between first and last names where they were merged (e.g., WilliamShakespeare → William Shakespeare).

Handling missing values: Converted 'Not rated yet' in the 'stars' column to NaN.

Capitalizing 'language' column: Ensured consistent formatting.



Exploratory Data Analysis (EDA):

Using Pandas, Matplotlib, and Seaborn, we performed the following analyses:

Price Distribution: Visualized using a histogram.

Language Distribution: Checked the number of audiobooks per language.

Star Rating Trends: Analyzed books with high and low ratings.

Top Authors & Narrators: Identified the most frequently appearing authors and narrators.



Key Insights:

The majority of audiobooks are in English, followed by German, Spanish, and French.

Price distribution shows that most audiobooks fall within a specific price range, with some free options.

Highly rated books tend to have well-known narrators.



Contributions are welcome! If you find any issues or improvements, feel free to submit a pull request.

📜 License

This project is licensed under the MIT License.

