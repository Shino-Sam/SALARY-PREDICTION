# Software Developer Salary Prediction

This project provides an interactive web application to explore and predict software developer salaries based on various factors like experience, education, and country. The app is built using Streamlit, and it leverages a machine learning model for salary prediction. You can explore the average salary data from various countries and experience levels, as well as use the app to predict the salary for a given set of input parameters.

## Features

Explore Salaries: Visualize the distribution of software developer salaries across different countries and experience levels.
Salary Prediction: Input your country, education level, and years of experience to predict your salary as a software developer.
  
## Technologies Used

Streamlit: For building the interactive web application.
Pandas: For data manipulation and preprocessing.
Matplotlib: For data visualization (e.g., pie charts and bar charts).
Scikit-Learn: For the machine learning model used to predict salaries.
Pickle: For loading pre-trained model and label encoders.

## Installation

To run this project locally, follow these steps:

### Step 1: Clone the repository
git clone https://github.com/your-username/salary-prediction.git
cd salary-prediction

### Step 2: Install dependencies
You can install the required Python libraries using pip. Create a virtual environment (optional but recommended) and install the dependencies.

### Step 3: Download the data
Download the dataset `survey_results_public.csv` from the source or make sure it is available in the project directory.

### Step 4: Run the application
Once you have installed the dependencies and prepared the data, you can run the Streamlit app.

streamlit run app.py


## Usage

1. Explore Page:
       On the "Explore" page, you can view visualizations that show:
       The distribution of data across different countries.
       The average salary by country.
       The average salary based on years of experience.

2. Predict Page:
         On the "Predict" page, you can input the following information:
         Country: Select your country from a predefined list.
         Education Level: Choose your highest completed level of education.
         Years of Experience: Use the slider to input your years of experience.
    After submitting, the application will predict the estimated salary for a software developer with the provided details.


Replace the pre-trained model
Once you've trained the model, you can replace the `saved_steps.pkl` file in the repository with the newly saved one.

## Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome!

## License

This project is open-source and available under the MIT License.
