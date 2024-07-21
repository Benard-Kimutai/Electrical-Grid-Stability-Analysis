# Electrical-Grid-Stability-Analysis

## Project Inspiration
I have always been intrigued by the complexities of electrical grids and their stability. The idea of analyzing the stability of a 4-node star electrical grid system, specifically one that implements the Decentral Smart Grid Control concept, sparked my interest.

## Project Overview

I embarked on this project to analyze the "Electrical Grid Stability Simulated Data" dataset, which consists of 10,000 instances and 14 features. The features include reaction times, nominal power consumed/produced, and coefficients proportional to price elasticity, among others. The target variable indicates whether the system is stable or unstable.

## Objectives and Achievements

1. **Dimensionality Reduction and Visualization Using PCA**:
   - **Objective**: Apply PCA to the dataset (excluding the target variable `stabf`), reduce it to the first three principal components, and visualize the data using a 3D scatter plot.
   - **Achievement**: Successfully applied PCA, reduced the dataset, and created a 3D visualization, which provided a clear view of the data distribution.

2. **Classification Using SVM (Linear Kernel)**:
   - **Objective**: Train an SVM model with a linear kernel, evaluate its performance, and report the metrics.
   - **Achievement**: Trained the model and achieved an accuracy of 81.35%, with detailed classification metrics, showcasing the model's effectiveness in predicting grid stability.

3. **Dimensionality Reduction and Visualization Using t-SNE**:
   - **Objective**: Apply t-SNE to the dataset (excluding the target variable `stabf`), reduce it to the first three components, and visualize the data.
   - **Achievement**: Successfully applied t-SNE, reduced the dataset, and visualized it using a 3D scatter plot, revealing intricate patterns in the data.

4. **Classification Using SVM (RBF Kernel)**:
   - **Objective**: Train an SVM model with an RBF kernel, perform hyperparameter tuning, evaluate its performance, and report the metrics.
   - **Achievement**: Trained the model with optimized hyperparameters and achieved an accuracy of 88.6%, demonstrating significant improvement and robustness in predictions.

5. **Understanding Hyperparameter Tuning**:
   - **Objective**: Analyze and compare the hyperparameters used in the SVM models, and discuss their impact on performance.
   - **Achievement**: Conducted a thorough analysis of hyperparameters, providing insights into their roles and effects on model performance.

## Personal Reflections

This project has been an incredible journey, deepening my understanding of machine learning applications in complex systems like electrical grids. It has honed my skills in dimensionality reduction, classification algorithms, and hyperparameter tuning, and provided me with valuable experience in data visualization.

## Future Directions

Looking ahead, I plan to explore other machine learning algorithms, such as Random Forests and Neural Networks, and apply this methodology to real-world electrical grid data. I am excited about the potential insights and contributions this work can bring to the field of smart grid technology.

## Conclusion

By undertaking this project, I have demonstrated my ability to tackle complex data science problems and derive actionable insights. I am eager to apply these skills in a professional setting, contributing to innovative solutions and advancing my career in data science.

