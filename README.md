
# Fragrances Recommender System

## Overview
The **Fragrances Recommender System** is designed to provide personalized perfume recommendations based on customer preferences and fragrance reviews. It is tailored to assist businesses, such as Macy's, in enhancing customer engagement and improving satisfaction by delivering tailored suggestions.

## Authors
- Pranav Garg  
- Ronak Goyal  
- Utkarsh Garg  
- Alexander Imhoff  
- John Izzo  
- Akash Barathan

## Features
- **Personalized Recommendations**: Matches user-input attributes (e.g., "exotic") with fragrance reviews.
- **Sentiment Analysis**: Analyzes reviews for sentiment (positive, negative, neutral).
- **Topic Modeling**: Identifies key themes in reviews using advanced NLP techniques like BERT.
- **Customer Insights**: Highlights popular attributes and products customers desire.
- **API Integration**: Built to support online and in-store applications.

## Data Source
- Scraped over **44,000 fragrance reviews** from the **Base Notes** forum up to December 2019.
- Reviews include sentiment ratings and detailed fragrance descriptions.

## Use Case
Example: A customer visits a store, looking for an "exotic" fragrance. They input their preference into the kiosk system, which recommends suitable perfumes based on historical reviews and attributes.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/pranvgarg/Fragrances-Recommender-System.git
   cd Fragrances-Recommender-System
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- Open and run the `Fragrance_recommender_system_Base_Notes.ipynb` notebook to execute the recommendation engine.
- Use `Base_note_scrapper.ipynb` to scrape and process additional fragrance reviews.

## Future Enhancements
- **Sentence Transformers** for scalable and efficient topic modeling.
- Integration of **customer behavior metadata** (e.g., demographics, clickstream data) for richer personalization.
- **Pricing API** to include budget-based recommendations.
- **In-store Mapping**: Output aisle numbers for easier product location in stores.

## License
This project is licensed under the [MIT License](LICENSE).

