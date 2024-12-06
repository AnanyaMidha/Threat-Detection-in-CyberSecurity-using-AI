# Threat-Detection-in-CyberSecurity-using-AI
"AI-Powered Threat Sentinel: Advanced Cybersecurity Detection System"
This project aims to create a cutting-edge cybersecurity system using machine learning to detect and classify threats effectively. The development process is broken into several critical steps, each contributing to the overall objective of enhancing network security. Here's a step-by-step breakdown:

Step 1: Data Preparation (PreProcessing.ipynb)
The first step focuses on preparing the dataset for training machine learning models.

The CIC-IDS2017 dataset is used, stored in the CSVs directory within the project folder.
This step involves cleaning, normalizing, and preprocessing the raw data to ensure compatibility with machine learning pipelines.

Step 2: Attack Categorization (AttackDivision.ipynb)
This stage filters and organizes the dataset for detailed analysis.

Using the all_data.csv file, the program segregates records into separate files based on attack types.
These categorized files are saved in the ./attacks/ directory for further processing.
The dataset includes 12 distinct attack types, enabling individual examination and targeted analysis.

Step 3: Feature Optimization (FeatureSelection.ipynb)
To enhance model efficiency, this step focuses on selecting the most significant features for each attack type.

Feature selection algorithms identify the four most important features for every attack file.
These optimized features serve as input for the machine learning models, improving accuracy and performance.

Step 4: Model Evaluation and Visualization (MachineLearningSep.ipynb)
In the final step, multiple machine learning algorithms are applied to the attack-specific datasets to evaluate their performance.

Seven different algorithms are tested on each attack file, with repeated trials to ensure reliability.
The results are saved to the ./attacks/results_1.csv file.
Additionally, box-and-whisker plots are generated to visualize the outcomes. These visualizations and results are stored in the ./attacks/result_graph_1/ folder.
