# ML Pipeline Project

## Project Overview
This project is designed to implement an end-to-end machine learning (ML) pipeline, covering the entire lifecycle from data ingestion to deployment. The focus is on creating a robust and scalable system that can handle real-world data, ensure data integrity, transform data appropriately, train a high-performing regression model, and deploy the model in a user-friendly application accessible through a web interface. The project leverages a variety of modern tools and technologies, ensuring that each step of the ML lifecycle is meticulously executed and documented to facilitate transparency, reproducibility, and maintainability.

## Objectives
1. **Develop a robust ML model to perform regression tasks:** Build a regression model capable of making accurate predictions.
2. **Create a scalable and maintainable pipeline for data ingestion, validation, transformation, training, and evaluation:** Design a pipeline that can efficiently handle large volumes of data, ensure data quality, and automate the ML workflow.
3. **Implement a user-friendly application for predictions using the trained model:** Develop a web application that allows users to input data and receive predictions in real-time.
4. **Deploy the application on AWS using CI/CD practices:** Automate the deployment using CI/CD practices, ensuring seamless integration and deployment on AWS.

## Tech Stack
- **Data Preparation:** pandas
- **ML Metrics:** sklearn
- **Data Visualization:** matplotlib, seaborn
- **Configuration:** pyyaml
- **Backend API:** Flask
- **Deployment:** AWS
- **Optional MLops:** For enhanced pipeline automation and monitoring.

## Project Structure
1. **Project Template Creation:** Establish the basic folder and file structure.
2. **Project Setup:** Initialize a virtual environment using conda and set up necessary configurations.
3. **Logging:** Implement logging mechanisms for tracking progress and debugging.
4. **Utilities:** Create a utils folder for frequently used code snippets.
5. **Exception Handling:** Integrate exception handling mechanisms.
6. **Data Ingestion:** Extract data from sources like GitHub or a database.
7. **Data Validation:** Ensure data integrity by cross-checking with schema definitions.
8. **Data Transformation:** Perform operations like train-test split, exploratory data analysis (EDA), and feature engineering.
9. **Model Training:** Train a regression model using ElasticNet to address overfitting and underfitting issues.
10. **Model Evaluation:** Assess the model's performance using appropriate metrics.
11. **Training Pipeline Implementation:** Automate the training process.
12. **Prediction Pipeline:** Set up the prediction workflow.
13. **User App Implementation:** Develop a user interface for model predictions.
14. **Dockerisation:** Containerize the application for consistency across environments.
15. **Deployment on AWS – CI/CD:** Automate the deployment process using AWS services.

## Workflow
- **Update Config Files:** Update config.yaml, schema.yaml, params.yaml to reflect the latest changes and requirements.
- **Entity Updates:** Update schemas and models to accommodate new data fields or changes in data formats.
- **Configuration Management:** Ensure configurations are correctly managed in the src config.
- **Component Updates:** Modify individual components as needed in response to changes in requirements or data.
- **Pipeline Updates:** Keep the pipeline code up-to-date, refactor code, add new steps, and optimize performance.
- **Main Script Updates:** Adjust the main.py script to integrate all components correctly.
- **App Script Updates:** Ensure app.py reflects the latest features and functionalities, providing a seamless user experience.