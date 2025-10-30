🎬 Netflix EDA Project
📌 Overview
This project performs Exploratory Data Analysis (EDA) on the Netflix dataset obtained from Kaggle.
The goal of this analysis is to understand how Netflix’s content library has evolved over time —
which types of content dominate, which countries produce the most shows, and when Netflix adds the most titles.


📂 Dataset Information:
The dataset contains details about movies and TV shows available on Netflix, including:

| Column Name      | Description                                         |
| ---------------- | --------------------------------------------------- |
| **show_id**      | Unique ID for every show                            |
| **type**         | Whether the content is a Movie or TV Show           |
| **title**        | Title of the content                                |
| **director**     | Director of the content                             |
| **cast**         | Main actors                                         |
| **country**      | Country of origin                                   |
| **date_added**   | Date the content was added to Netflix               |
| **release_year** | Year of release                                     |
| **rating**       | Age rating                                          |
| **duration**     | Duration (minutes for movies, seasons for TV shows) |
| **listed_in**    | Genre/category                                      |
| **description**  | Summary of the content                              |


🧠 Key Steps Performed:
1. Data Loading and Cleaning
* Checked dataset info, shape, and null values.
* Handled missing values for columns like director, cast, and country.
* Converted date_added into datetime format and created new columns:
--> year_added
--> month_added

2. Exploratory Data Analysis
* Analyzed the growth of Netflix content over the years.
* Compared Movies vs TV Shows.
* Found top genres, countries, and release patterns.

3. Data Visualization
* Visualized key trends using Matplotlib and Seaborn


📊 Visual Insights
1️⃣ Content Added Over the Years
📈 Observation: Netflix has rapidly expanded its library since 2015, showing a steep rise in new titles.

2️⃣ Month-wise Content Addition
📊 Observation: July had the highest content additions, while February had the least — suggesting more releases mid-year.

3️⃣ Type of Content (Movies vs TV Shows)
🎥 Observation: Movies dominate Netflix’s catalog, but TV shows have been growing steadily.

4️⃣ Top Genres
🎭 Observation: “Dramas,” “International Movies,” and “Comedies” are among the most frequent genres.

5️⃣ Top Countries Producing Content
🌍 Observation: The United States, India, and the United Kingdom lead in content production on Netflix.


🛠️ Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook


📁 Project Files
Netflix_EDA.ipynb → Jupyter notebook containing full analysis and visualizations
netflix_titles.csv → Dataset (if included)
README.md → Project overview


💡 Conclusion
Netflix has seen significant content growth in recent years, especially between 2015–2020.
The platform primarily focuses on movies, with a strong presence in drama and international categories.
The data shows Netflix’s global expansion and evolving strategy to provide diverse content throughout the year.
