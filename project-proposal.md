# DATA620 - Final Project Proposal

## Project Title: Analyzing Amazon Reviews for Product Insights
### The P < 0.05 Team - Haig Bedros, Nori Selina, Julia Ferris, Matthew Roland

### The Question:
How do different product features and review characteristics affect customer satisfaction as shown by review ratings on Amazon?

### Motivation:
We want to use Amazon reviews to learn what customers like or dislike about products. By studying the review text and product information, we can find out what factors lead to high or low ratings. This will help us understand customer behavior and improve products.

### Data Sources:
We will use the Amazon Review Data (2018) provided by Jianmo Ni from UCSD. This dataset includes reviews (ratings, text, helpfulness votes), product details (descriptions, categories, price, brand, and image features), and links (also viewed/also bought graphs). It covers reviews from May 1996 to October 2018 and includes 233.1 million reviews.

### Project Plan:

#### Tasks and Responsibilities:

**1. Data Preparation and Cleaning**
- **Assigned to:** ???
- **Responsibilities:**
  - Load the dataset and parse the JSON files.
  - Clean the data by removing HTML/CSS content, duplicates, and irrelevant information.

**2. Descriptive Analysis and Visualization**
- **Assigned to:** ???
- **Responsibilities:**
  - Perform basic statistics on the dataset (e.g., average rating, number of reviews per product).
  - Create visualizations to show key metrics like rating distribution, number of reviews per category, and product pricing.

**3. Network Analysis**
- **Assigned to:** ???
- **Responsibilities:**
  - Create and analyze the "also viewed" and "also bought" graphs to find popular product groups.
  - Use centrality measures to find important products in these networks.

**4. NLP and Text Mining**
- **Assigned to:** ???
- **Responsibilities:**
  - Perform sentiment analysis on review texts to measure customer satisfaction.
  - Do topic modeling to find common themes in positive and negative reviews.

**5. Predictive Analysis**
- **Assigned to:** ??? and ???
- **Responsibilities:**
  - Train machine learning models to predict review ratings based on review text and product features.
  - Evaluate model performance and improve it as needed.

### Concerns:
- The large dataset might be hard to handle. We will start with a smaller subset and scale up if needed.
- We need to ensure good teamwork and task division to meet project deadlines.

### Conclusion:
This project aims to find useful insights into customer satisfaction and product performance on Amazon. By combining network analysis, NLP, and predictive modeling, we hope to identify patterns and factors that affect review ratings. Each team member will focus on specific tasks, ensuring a thorough approach to the project.

### Citation:
If you use this data, please cite the following paper:

Justifying recommendations using distantly-labeled reviews and fine-grained aspects  
Jianmo Ni, Jiacheng Li, Julian McAuley  
Empirical Methods in Natural Language Processing (EMNLP), 2019