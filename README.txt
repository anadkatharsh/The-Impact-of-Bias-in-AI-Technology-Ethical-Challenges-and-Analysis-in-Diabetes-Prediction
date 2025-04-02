The Impact of Bias in AI: Ethical Challenges in Diabetes Prediction With Facial Recognition
Project Description
This project explores the ethical challenges associated with using facial recognition technology for diabetes prediction, focusing on the potential for bias in AI systems. By analyzing how demographic and physiological factors influence predictions, the project aims to uncover biases that could lead to unfair or inaccurate outcomes. The study emphasizes the importance of ethical AI practices, particularly in sensitive areas like healthcare, where biased models can disproportionately affect marginalized groups. The findings aim to guide the development of equitable and transparent AI systems.

Key Findings & Results
Bias Identification:

Significant disparities were observed in prediction accuracy across different demographic groups (e.g., gender, age, and ethnicity).

Models exhibited higher error rates for underrepresented groups, highlighting the need for balanced datasets and fairness-aware algorithms.

Ethical Implications:

The use of facial recognition for health predictions raises privacy concerns and risks reinforcing societal biases.

Transparent reporting on model limitations and biases is critical to ensure trustworthiness in AI applications.

Model Performance:

While predictive models achieved high accuracy overall, their performance varied significantly across subgroups, emphasizing the need for fairness metrics beyond standard accuracy measures.

Tools & Technologies Used
Programming Language: Python

Libraries: TensorFlow, Scikit-learn, Pandas, NumPy, Matplotlib

Techniques: Machine Learning (classification models), Bias Detection Frameworks

Visualization Tools: Heatmaps, Confusion Matrices, Disparity Metrics

How to Run the Code
Setup Environment:

Install Python (version 3.8 or later).

Install required libraries using:

bash
pip install tensorflow scikit-learn pandas numpy matplotlib
Prepare Data:

Ensure the dataset is placed in the data/ directory.

Preprocess the data by running:

bash
python data_preprocessing.py
Train Models:

Execute the script to train and evaluate models:

bash
python train_models.py
Bias Analysis:

Analyze bias in predictions using:

bash
python bias_analysis.py
View Results:

Outputs include performance metrics (accuracy, precision, recall) and fairness metrics (disparity scores) saved as .csv files.

Visualizations are saved as images in the outputs/ directory.