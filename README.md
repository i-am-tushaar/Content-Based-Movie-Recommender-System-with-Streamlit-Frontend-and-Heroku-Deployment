
Content-Based Movie Recommender System Using TMDb Dataset with Streamlit Frontend and Heroku Deployment.

This project presents a fully developed content-based movie recommender system built using the TMDb (The Movie Database) dataset. The system is designed to suggest movies to users based on their preferences by leveraging cosine similarity for content analysis. The project encompasses a complete pipeline, from data preprocessing and feature vectorization to building a user-friendly frontend with Streamlit and deploying the application on Heroku for public accessibility.

Key Features: Dataset and Preprocessing:

The TMDb dataset is used, which provides comprehensive metadata such as movie titles, genres, overviews, keywords, cast, and crew. Extensive preprocessing is performed, including: Removing null or duplicate entries. Converting genres, keywords, and cast into vectorizable formats. Tokenizing and cleaning textual data like movie descriptions. Applying feature extraction methods to create meaningful input for the recommendation engine. Vectorization:

Textual features are vectorized using NLP techniques, such as TF-IDF or Count Vectorizer, to create feature vectors for movies. Cosine similarity is then calculated between these feature vectors to measure the similarity between movies. This forms the basis for generating recommendations. Recommendation Engine:

Users input a movie title, and the engine finds and ranks similar movies based on cosine similarity scores. The system dynamically generates recommendations personalized to the user's input. Frontend Development with Streamlit:

A modern, interactive web interface is built using Streamlit to ensure seamless user interaction. Features include a search bar to input a movie title, an output section displaying recommended movies, and visual elements for user engagement. The interface is designed to be intuitive and visually appealing, enhancing the overall user experience. Deployment on Heroku:

The entire application is deployed on Heroku, a cloud platform-as-a-service (PaaS). Deployment ensures accessibility to users from any device via a browser, enabling real-world usability of the recommender system. Scalability and Extensibility:

The project is designed with scalability in mind, allowing easy incorporation of collaborative filtering or hybrid methods for future enhancements. It can be integrated with larger platforms, such as streaming services or movie databases. Outcome: The project successfully demonstrates the integration of machine learning techniques with modern web application frameworks and cloud deployment. The recommender system delivers accurate, relevant, and user-friendly movie recommendations in real time. The deployment on Heroku ensures accessibility and highlights the practical applicability of the solution.

Use Cases: Movie streaming platforms (e.g., Netflix, Hulu, Disney+) for personalized recommendations. Online movie discovery platforms to enhance user engagement. A prototype for educational purposes or as a foundation for more advanced recommendation systems. This project combines machine learning, software development, and deployment skills, showcasing a holistic approach to building production-ready applications.


## Author

- [@i-am-tushaar](https://github.com/https://github.com/i-am-tushaar)


## FAQ

#### How does this Content-Based Movie Recommender System generate recommendations?

The system analyzes movie metadata, including genres, keywords, cast, and crew, to find similar movies. Using TF-IDF vectorization and cosine similarity, it compares movie descriptions and suggests titles that closely match the user’s input. This ensures recommendations are personalized based on content rather than user behavior.

#### Where can I access and use this movie recommender system?

The application is deployed on Heroku, making it accessible via a web browser on any device. The Streamlit-based frontend provides an intuitive interface where users can enter a movie title and instantly receive recommendations. No installation is required—just visit the provided Heroku link and start exploring movie suggestions! 🚀


## Usage/Examples


import numpy as np # linear algebra 

import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)


import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))

## 🚀 About Me
Passionate data analyst, always exploring new technologies and building cool projects. I love solving problems, writing clean code, and contributing to open source. Let's connect and create something awesome!

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://i-am-tushaar.github.io/Portfolio-Website/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tushar-choudhary-401b1a262/)

