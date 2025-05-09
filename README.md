# IBM-Applied-Data-Science-Capstone

📄 Project Overview
SpaceX is a pioneer in the commercial space industry, significantly reducing launch costs by reusing the first stage of its Falcon 9 rockets. While a typical Falcon 9 launch costs around $62 million, other providers charge over $165 million. The cost savings are largely due to SpaceX's ability to recover and reuse the rocket’s first stage.

The objective of this project is to use publicly available data and machine learning models to predict whether the first stage will successfully land, and therefore, be reusable.

❓ Key Questions
How do features such as payload mass, launch site, flight number, and orbit type impact first stage landing success?

Has the success rate of landings improved over time?

Which binary classification algorithm provides the best performance for this prediction task?

🧪 Methodology
1. Data Collection
Used SpaceX REST API

Performed web scraping from Wikipedia

2. Data Wrangling
Filtered and cleaned raw data

Handled missing values

Applied One Hot Encoding to prepare data for machine learning models

3. Exploratory Data Analysis (EDA)
Conducted thorough EDA using data visualizations and SQL queries

4. Interactive Visualizations
Built interactive maps and dashboards using Folium and Plotly Dash

5. Predictive Modeling
Implemented and fine-tuned multiple classification models

Evaluated models to identify the best-performing algorithm
