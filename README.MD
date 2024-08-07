

# Project Structure and Purpose: Overview and Detailed Explanation



## Introduction

Welcome to my project! This repository houses a comprehensive exploration of various technologies, database models, and advanced analytics techniques applied in a unified framework. Our goal is to provide a detailed overview of how these components synergistically contribute to achieving our project objectives.

## Technologies Used

Python 3.11.9 | Docker | PostgreSQL | Jupyter Notebooks

## Libraries Used

- **scikit-learn (sklearn)**: Provides tools for machine learning, including algorithms for classification, regression, clustering, and model evaluation.
- **lifetimes**: Specializes in customer behavior analysis, predicting customer lifetime value (CLV), and modeling retention. 
- **pandas**: Offers data manipulation and analysis capabilities, including data structures and functions for handling structured data.
- **numpy**: Provides support for large, multi-dimensional arrays and matrices, along with mathematical functions to operate on these arrays.
- **matplotlib** & **seaborn**: Used for data visualization. matplotlib creates static, animated, and interactive plots, while seaborn provides a high-level interface for drawing attractive and informative statistical graphics.


### Frontend Technologies

While this project does not include a traditional frontend interface, it incorporates a unique frontend component through a ***GitHub Pages*** site. This site serves as a platform for deploying one of our ***Jupyter Notebook*** files, providing an accessible and user-friendly way to present our project's findings and analyses. [Website](https://aleqyan666.github.io/internship.github.io/#/)

The ***GitHub Pages*** site is designed to showcase the notebook in a format that is easy to navigate and interact with. It allows users to explore the detailed data analysis, visualizations, and insights generated by our project. By deploying the notebook on GitHub Pages, we offer a convenient means for stakeholders and other interested parties to engage with our work, even in the absence of a dedicated web application.
This approach leverages the power of ***Jupyter Notebooks*** to deliver interactive and dynamic content while maintaining a streamlined and efficient project structure.

### Backend Technologies

**Python**, complemented by a suite of versatile libraries such as ***SQLAlchemy*** and ***Pandas***, formed the backbone of our backend development. This combination empowered us with extensive capabilities for managing data effectively throughout the project lifecycle. In particular, our ***model.py*** housed meticulously crafted database models, defining the structure and relationships crucial for our ***PostgreSQL*** database. Meanwhile, ***data_ingest.py*** played a pivotal role in seamlessly populating these tables with relevant data, ensuring a comprehensive and up-to-date repository. Additionally, ***database.py*** facilitated secure and efficient connections to our database, enabling robust data interactions and management operations.

### Database Models

Various database models have been meticulously designed using **SQLAlchemy's ORM capabilities**, incorporating features like foreign keys to ensure robust data organization and efficient querying within our PostgreSQL database. These models are tailored to diverse data scenarios, optimizing data integrity and retrieval for specific project needs.

### Analytics Techniques

Analytics forms a cornerstone of our project, employing advanced techniques such statistical analysis, and data visualization tools. These techniques enable us to derive valuable insights. The aforementioned processes utilized ***Jupyter Notebooks*** along with Python libraries such as ***Pandas***, ***NumPy***, and ***others***.

## Project Structure


### Modular Architecture

To foster maintainability and collaboration, our project adopts a modular architecture. Each component, whether frontend views, backend services, or analytical models, is encapsulated within its own module with clear interfaces and dependencies. 
- **images**: Intended for storing files and images related to pictures and visual content.

- **Recommendation_engine/etl**: 

    - ***.env*** securely manages sensitive information and customizes configurations based on different deployment environments (development, testing, production, etc.) without hardcoding them into our application codebase.
    - ***requirement.txt*** lists the Python packages required for this project, ensuring compatibility and functionality across different environments. Each package serves a specific purpose.
    - ***Dockerfile*** efficiently sets up a Python application in a lightweight `python:3.10-slim-bullseye` container. It manages dependencies and essential system libraries, establishes a working directory, and exposes a port for external access. This streamlined approach enhances deployment consistency, scalability, and security, supporting modern software development practices effectively.
    - ***data_ingest.py***, ***database.py***, & ***models.py*** The process involves first establishing a secure connection with the database, followed by meticulously designing and implementing precise database models tailored to the application's data requirements. Subsequently, these models are used to populate database tables with the relevant data, ensuring comprehensive and organized data storage and retrieval capabilities.
            
- **Recommendation_engine/etl/data**: Houses ***CSV*** files utilized for data analytics and various database operations and table interactions.

- **Recommendation_engine/model**: Contains data and ***Jupyter Notebook*** files. This directory is used for performing **exploratory data analysis (EDA)**, creating visualizations, and training models. It serves as a central location for data handling and analysis tasks.

- **docker-compose.yaml**: orchestrates a development environment with a ***PostgreSQL*** database, ***pgAdmin*** for database management, and a specialized service ***db_setup*** for database initialization tasks. It ensures interdependent services are orchestrated properly, facilitating efficient development, testing, and deployment workflows in a Dockerized environment. Adjustments can be made based on specific project requirements and scaling needs.

## Purpose and Goals

Our project aims to:
- **Deliver a Seamless User Experience**: Integrating frontend and backend technologies to create a cohesive user interface that enhances usability and performance.
- **Ensure Data Integrity and Scalability**: Implementing robust database models and efficient data management practices to support current and future data needs.
- **Drive Informed Decision-Making**: Leveraging advanced analytics techniques to extract actionable insights from data, empowering stakeholders to make data-driven decisions.
- **Machine Learning Model for Predictions**: Engineered to forecast outcomes by analyzing data patterns. Utilizes advanced algorithms to provide accurate predictions and support data-driven decision-making.
## Entity Relationship Diagram


![Entity Relationship Diagram](images/erd_picture.png) 

## Conclusion

In this project, we set out to address critical questions regarding user behavior and phone usage patterns through a series of advanced analytical techniques. Our primary objectives were to **predict user behavior concerning phone changes, forecast the number of purchases within a specified period, and cluster users based on their phone usage and changing habits.**

***Predicting Phone Changes and Purchase Frequency:*** We developed predictive models to assess the likelihood of users changing their phones and estimated their number of purchases within a given timeframe. By analyzing historical data and user patterns, our models have provided actionable insights into user tendencies, allowing for more informed decision-making regarding inventory management and marketing strategies.

***Clustering Users Based on Behavior:*** Utilizing clustering techniques, we grouped users based on their phone usage habits, duration of being a customer, and the number of phones they have changed. This segmentation has enabled us to identify distinct user profiles, ranging from those who frequently change phones to those with more stable usage patterns. These clusters offer valuable insights into customer behavior and preferences, which can be leveraged to tailor services and promotions to different user segments.

***Insights and Impact:*** The findings from our analysis contribute to a deeper understanding of user behavior and phone usage patterns. By segmenting users and predicting their future actions, we can enhance customer engagement strategies, optimize marketing efforts, and improve the overall user experience. The results underscore the importance of data-driven decision-making in effectively managing customer relationships and driving business growth.

***Overall,*** this project demonstrates the power of advanced analytics in transforming raw data into meaningful insights, facilitating strategic decision-making, and improving business outcomes. The methodologies and results presented herein provide a solid foundation for further exploration and refinement of user behavior models in future work.

---
### Contacts
[Github Account](https://github.com/Aleqyan666) 
 
[LinkedIn Account](https://www.linkedin.com/in/hayk-alekyan-900797204/)

[Website](https://aleqyan666.github.io/internship.github.io/#/)
<!-- # Entity Relationship Diagram -->