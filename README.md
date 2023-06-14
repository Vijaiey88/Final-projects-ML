# Rating of Udemy Courses

This project aims to predict the ratings given by learners to Udemy courses. The dataset used for this project contains information about Udemy courses, including course title, price, number of subscribers, number of reviews, number of lectures, course level, content duration, and rating.

## Dataset

The dataset used for this project is sourced from [Udemy](https://www.udemy.com/) and is available in`(https://www.kaggle.com/datasets/andrewmvd/udemy-courses)`. It contains the following columns:

- course_title: The title of the Udemy course
- price: The price of the course
- num_subscribers: The number of subscribers for the course
- num_reviews: The number of reviews for the course
- num_lectures: The number of lectures in the course
- level: The level of the course (Beginner, Intermediate, Expert)
- content_duration: The content duration of the course
- Rating: The rating of the course

## Regression Model

In this project, a regression model is developed to predict the ratings given by learners to the Udemy courses. The XGBoost regressor and Random Forest regressor models are implemented and evaluated for their performance.

The XGBoost regressor is trained using the dataset and evaluated using mean squared error (MSE), mean absolute error (MAE), and R-squared score. Similarly, the Random Forest regressor is trained and evaluated using the same metrics.

The evaluation metrics obtained from the models provide insights into the accuracy and performance of the models in predicting the course ratings.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/rating-udemy-courses.git`
2. Navigate to the project directory: `cd rating-udemy-courses`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the Jupyter notebooks in the `notebooks/` directory to explore the data and train the models.
5. Use the trained models for predictions or further analysis.

Feel free to customize the project as per your requirements and explore additional features or regression models to improve the predictions.

