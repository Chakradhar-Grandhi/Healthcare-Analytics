# Synthetic Healthcare Dataset

## About the Dataset

### Context
This dataset is a synthetic creation aimed at anyone keen on exploring data science, machine learning, or data analysis, particularly within the healthcare sector. It’s designed to replicate the nuances of real-world healthcare data, offering a sandbox for practicing and showcasing your analytical skills without any of the privacy concerns associated with actual patient data.

### Inspiration
Healthcare data is incredibly valuable for learning, but it's also one of the most challenging to access due to privacy laws and ethical considerations. To bridge this gap, I’ve used Python's Faker library to craft a dataset that mirrors what you might encounter in real-world healthcare settings. The goal here is to support innovation, learning, and experimentation in healthcare analytics, all within a safe and controlled environment.

## Dataset Information

This dataset comes packed with various columns, each telling a part of the patient's journey through the healthcare system—from admission to discharge, including the medical services they received. Here’s a quick rundown of what each column represents:

- **Name:** The patient's name.
- **Age:** How old the patient is at the time of admission.
- **Gender:** The patient's gender, either "Male" or "Female."
- **Blood Type:** The patient's blood type (like "A+", "O-", etc.).
- **Medical Condition:** The primary medical issue or diagnosis for the patient, such as "Diabetes," "Hypertension," or "Asthma."
- **Date of Admission:** The date when the patient was admitted to the healthcare facility.
- **Doctor:** The attending doctor responsible for the patient’s care.
- **Hospital:** The name of the hospital where the patient was treated.
- **Insurance Provider:** The insurance company covering the patient, such as "Aetna," "Blue Cross," "Cigna," "UnitedHealthcare," or "Medicare."
- **Billing Amount:** The total cost billed for the patient’s care during their stay.
- **Room Number:** The room where the patient was accommodated during their stay.
- **Admission Type:** Indicates whether the admission was "Emergency," "Elective," or "Urgent."
- **Discharge Date:** The date the patient was discharged, calculated based on their admission date and a realistic length of stay.
- **Medication:** Any medication prescribed or administered during the stay, like "Aspirin," "Ibuprofen," "Penicillin," or "Lipitor."
- **Test Results:** The outcome of a medical test conducted during the stay, categorized as "Normal," "Abnormal," or "Inconclusive."

## Usage Scenarios

This dataset is incredibly versatile and can be used in a number of ways, including:

- **Building and testing predictive models**: Use the data to train machine learning models and predict outcomes.
- **Practicing data cleaning and transformation**: Hone your skills in preparing and wrangling data for analysis.
- **Creating visualizations**: Gain insights into healthcare trends and patterns by visualizing the data.
- **Educational purposes**: Perfect for teaching and learning data science and machine learning concepts in a healthcare context.

### Multi-Class Classification Task

This problem can be treated as a multi-classification problem and it is solved in the **Test Results** column, which has 3 categories, "Normal," "Abnormal," or "Inconclusive."

## Included Notebooks

I’ve included two Jupyter notebooks to help you get started:

1. **Data Analysis Notebook (`Healthcare-Data-Analysis.ipynb`)**: Dive into an exploratory data analysis (EDA) of this dataset. You'll find everything from data cleaning to visualization techniques aimed at extracting meaningful insights.

2. **Healthcare Classification Notebook (`Healthcare-Classification.ipynb`)**: This notebook walks you through the process of building and evaluating classification models to predict test results. Various algorithms are used to demonstrate model training, evaluation, and comparison.

## Acknowledgments

I created this dataset with the utmost respect for healthcare data privacy. Rest assured, this dataset is entirely synthetic, meaning it contains no real patient information and does not violate any privacy regulations.

I hope this dataset sparks curiosity and innovation, allowing you to explore, learn, and maybe even create something groundbreaking in the field of healthcare analytics. Feel free to dig in, analyze, and share what you discover!

## References

You can find the original dataset on Kaggle here: [Synthetic Healthcare Dataset on Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset).

## License

This dataset is licensed under the MIT License, which allows you to freely use, modify, and distribute the data, provided you include the original copyright notice and this permission notice in any copies of the data. For more details, refer to the [LICENSE](./LICENSE) file.
