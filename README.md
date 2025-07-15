# Planning Trip to New York with Travel Planner Chatbot

The Travel Planner Chatbot project is an intelligent, user-driven assistant that recommends Airbnb listings in New York City (or other city) based on personalized preferences such as price range, room type (e.g., entire home/apt), and neighborhood. Built by using Python, OpenAI’s GPT model, and LangChain’s Retrieval-Augmented Generation (RAG) framework, the chatbot leverages structured CSV data (from Kaggle) and vector search to match users with relevant, high-quality rental options. It enhances reliability by including only listings with sufficient reviews, high ratings, and confirmed current availability based on both dataset filtering and real-time URL checks.

The final output delivers concise listing suggestions that include pricing, rating, room details, and direct Airbnb links for checking the accomodation details for travelers. While the dataset does not include images, the system is structured to allow clickable listing URLs for users to view photos and book directly. The project demonstrates how AI, embeddings, and structured data can come together to solve real-world planning problems, offering a scalable template for other cities or platforms in future travel applications.

## Dataset: New York Airbnb Open Data 2024

Airbnb listings and metrics in NYC, NY, USA as of 05 January, 2024.  The dataset is available at [Kaggle.](https://www.kaggle.com/datasets/vrindakallu/new-york-dataset)
